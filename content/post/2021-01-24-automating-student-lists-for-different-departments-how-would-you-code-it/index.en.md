---
title: Automating Student Lists, How Would You Code It?
author: Whitney M. Marks
date: '2021-01-24'
slug: []
categories:
  - How would you code it
tags:
  - code
  - process improvement
Description: ''
Tags: []
Categories: []
DisableComments: no
---

#### Brief Problem Description:

The purpose of this code is to provide student lists to colleges for a particular department during the enrollment cycle, which had previously been a manual process for an office staff member. I was asked to automate it.

I pulled and cleaned the student information from SQL Server and produced `enrolled_clean`, the starting point of the below code.

**The task is to ensure:**
- The student lists are segmented by college, term, session, section number, and faculty member
- The name of the file would have important identifying class information
- The DD or dynamically dated session, the second snippet, would also need the start month of the course in the file name to help staff identify the correct file
- The output would be a CSV file written to SharePoint 

The script is run on windows task scheduler during enrollment periods so that the lists will be updated daily.

#### Code I Wrote:


```{r}
#write files for synchronous sessions
enrolled_clean %>%
  filter(session %in% c("A1", "A2", "A3", "A4", "O1")) %>%
  group_by(college, term, session, section_number, faculty_last_name) %>%
  group_walk(~write_csv(.x, paste0(.y$course_college, "/", .y$faculty_last_name, "_", .y$session, "_", 
  .y$section_number, ".csv")))

 
#write files for asynchronous sessions
enrolled_clean %>%
  filter(session %in% c("DD")) %>%
  group_by(college, term, session, section_number, faculty_last_name, start_month) %>%
  group_walk(~write_csv(.x, paste0(.y$course_college, "/", .y$faculty_last_name, "_", .y$session, 
  "_", .y$start_month, "_", .y$section_number, ".csv")))

```

#### How would you have tackled this problem with code? 

