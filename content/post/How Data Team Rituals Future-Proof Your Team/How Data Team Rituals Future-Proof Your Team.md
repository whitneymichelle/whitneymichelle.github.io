 
---
title: How Data Team Rituals Future-Proof Your Team
author: Whitney M. Marks
date: '2021-06-13'
slug: []
categories:
  - data teams
tags:
  - professional development
images:
  - site-feature-img.png
---

When I first started contemplating wanting to work in data and specifically on the data team at my last organization, what data teams talked about and how they worked was very elusive. I had a few conversations with members of the data team I would eventually work on, but some aspects of the job still did not feel entirely concrete until I actually began working as a data analyst. 

In this article, I seek to demystify some of the rituals data teams partake in--particularly the rituals they create around professional development and keeping up-to-date with best practices. Obviously, the conversations data teams have will differ depending on the context and industry of the data team and the technology being used. Also, some conversations will look different depending on if the data team is structured to provide [data as a product or as a service](https://locallyoptimistic.com/post/run-your-data-team-like-a-product-team/).

I’ve worked on two data teams, one which set up data as a product and the other as a service. Even with the differences, on each data team, I have found certain rituals and practices beneficial to my development. And sometimes, I have found them not only beneficial to my professional growth but simply enjoyable. 

While I believe these rituals may not be unique to data teams, I focus specifically on these practices within the context of a data team, a type of team which perhaps has to evolve more rapidly than other team types because of advances in technology. As I have written about before, [I was an academic advisor on a student services team before becoming a data analyst](https://whitneymichelle.netlify.app/post/from-academic-advisor-to-data-analyst/from-academic-advisor-to-data-analyst/). While people are doing wonderful education/student services research, research to practice in education often occurs more slowly, if at all, than in technology and in the data space. Rituals and the study of the rituals may be more important in spaces in which change, if it increases efficiency, is expected and welcomed.

Data teams are closely linked with technological advances (sometimes data people or teams are the authors of these technological advances), and there’s always--as there should be--a focus on optimization. In this post, I outline the rituals of my past and present data team, how these rituals were implemented, why they were or are helpful, and why they were or are enjoyable. I outline how these rituals were constructed and, sometimes, how they evolved. 

#### Lunch and Learns

My first data team, near the end of my tenure, consistently held monthly Lunch and Learns. However, before this consistency, our team only held these Lunch and Learn sessions a handful of times over a two-year period. Perhaps partly because of working remotely during the COVID-19 pandemic and wanting more facetime with my colleagues, I reintroduced the Lunch and Learn idea to the team. My manager was supportive and guided the team through co-creating expectations. 

We had a conversation regarding expectations, including timing, topics, and hosting--to see if this was something the team wanted to commit to. The conclusion of the conversion was that we would hold monthly sessions, that we would rotate hosting duties, and that topics could be broad. Topics could be data-related, yes, but also could encompass anything that would make us stronger as individual data analysts or as a team. Another important decision the team made was that preparation for Lunch and Learns could be minimal. We could lead a discussion around an article or present something in an unpolished draft form. Lunch and Learns--we decided--would be unapologetically informal.

I believe our established informality rules allowed Lunch and Learns to be sustainable on our busy team. We also discussed periodically revisiting the format to see if we collectively thought Lunch and Learns were still useful and still serving an important purpose.

The Lunch and Learn topic I enjoyed the most was about reframing problems in order to see solutions from different perspectives. Even though not always explicitly framed this way, data analysts are asked to produce data products that solve a problem. So making a connection from the problem-reframing Lunch and Learn to our work was easy. And topics, just like the individual interests on our team, were varied. Even though we worked on the same team, the field of data science is broad; many of us were interested in different aspects of the work. So gaining a snippet into what others were learning and exploring was interesting and, at times, spurred me to look into some topics more deeply. At other times, the sessions gave me a reference point for ideas I had not previously considered.

#### Open Forums 

Both of my data teams, past and present, had some version of the Open Forum during the weekly staff meeting. The Open Forum from my last data team was for items that required a larger group discussion. For instance, setting the Lunch and Learn guidelines was a topic of one of the Open Forums. Sometimes the Open Forum was used for parsing out work for larger projects. On my current team, although it is not referred to as an Open Forum, there is a call for topics from all members of the team ahead of the staff meeting that functions the same way as the Open Forum. I think establishing time for team members to bring issues or conversations to the forefront is essential, and it’s a time to work through problem-solving. 

This Open Forum type discussion was new to me because in my previous roles outside of being an analyst, topics for conversation were usually solely established by managers. I think this occurred for two main reasons. One is that decisions were mostly made using a top-down approach. And the other was because the previous teams were larger, which seems to minimize calls for input due to time constraints. An interesting topic, which I do not discuss in this post, is how to create collaborative rituals on large data teams. (The data teams I have worked on have ranged from 4 to 7 people, and I imagine some rituals would have to be adapted differently in larger teams).

#### Show and Tells

Show and Tells are also a part of the structure of my current team’s staff meeting. On my last team, there was a space for this in our staff meeting time as well--although that space and time was not referred to as Show and Tell. But I believe this ritual works better on my current data team because the expectation is that you will have something to share. Each team member takes around five minutes to show something that they are working on or that they learned over the week. I like that the expectation is that you will share and that it is seen more as a requirement than optional. As a data person, I cannot imagine that I would not learn anything new or interesting over a week’s period. I’m always learning something new, even if it’s just a new resource or interesting article.

I also enjoy Show and Tell because I get to visually see and not just hear about what other people are working on. Often, documents or lines of code or websites will be shared. I love the tangibility of seeing projects. I like that this time gives me insight into the work other team members are doing, even if I don’t have in-depth context of the topic; any context I can get is appreciated. I think this ritual will be helpful even when I have been on the team longer, as I am a new team member. But it’s particularly helpful as a new team member to get a sense of the problems people care about and are trying to solve. 

#### Data Quality Meetings

All data teams are concerned with data quality. But the way that teams are structured, the technical proficiency of the team, the technology that’s being used, and the culture of the team all make this conversation look different on different teams.

On my last data team, when I was about a year and a half into the role and a couple of months after we hired a new director, we started having bimonthly data quality meetings. We had a traditional ETL setup. So while we had tables that we didn’t understand well and rarely used or had to gain context around in order to start using, most of our work centered around fairly well-understood tables and data that was modeled for us by the engineering team. We had the flexibility to create our own views and models on top of this, to help operational teams with various student initiatives and to track KPIs and other important metrics for the institution. Our data quality meeting evolved into establishing code quality guidelines and a code review process for frequently used code and a library for this code. Our review process was manual, and we were not using the established best-practice framework for our newly established code library--which would have been using a repository manager. But I think it was a move in the right direction and a realistic step for our team.

On my current team, we also have discussions about code quality--but they are usually part of staff meeting topics, and the conversations around the topic and how we go about establishing quality look different than from my last team. We use a modern data stack with an ELT setup. Raw tables enter directly into the data warehouse, and the data team is responsible for modeling that data with [dbt](https://blog.getdbt.com/what--exactly--is-dbt-/) and loading the transformed model back into the data warehouse. We use a repository manager, Gitlab, and our code is tested and under version control. We are still concerned with our modeling being accurate and properly reflecting the methodology that our stakeholders think it should reflect. But we are also concerned about the raw incoming tables of our data--which we have less control over but ultimately will affect downstream models. Some of the conversations are about when and how to test so that problems with our data are known or knowable.

Rituals around data quality have helped me understand issues around testing and testing philosophies, and I’m still very much learning. In my current role, I’m learning the issues of data quality that are of concern in the [analytics engineering](https://www.getdbt.com/what-is-analytics-engineering/) framework.

#### Data Team Channel

On my current team, we have a Slack channel for side conversations that are not formally linked to work projects. The channel mostly consists of sharing interesting blog posts, articles, and software updates. I’ve also learned about some interesting software being developed for the productivity of data teams. I usually bookmark things I’m interested in and take an hour on Friday to read through them. Team members have also shared information on blog posts they have themselves written or talks they are giving. It’s nice to see what team members are contributing to the data space.

#### The Efficacy of Rituals

You can google the efficacy of rituals and will find articles about the psychological and sociological benefits of rituals. Our personal rituals, like coffee in the morning or reading blog posts before work, I imagine provide us some benefits and are satisfying some higher-level needs. The same can be said for team rituals. 

And in the data space, and perhaps all spaces, team rituals can be used to create efficiency. They create efficiency in the stuff you learn during them but also what you learn in their creation and takeaways. And I would argue that data team rituals solve today’s problems but also tomorrow’s problems. Talking about different issues in the field and sharing possible solutions helps build a knowledge base to circle back to when it’s time to solve a new problem or perhaps a problem you have been putting off solving. Some data team rituals can be fun and create meaning, but they are also this natural way to future-proof a team.

