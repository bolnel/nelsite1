+++
title = "Leveraging Kanban Principles and Metrics. Scrum+Kanban Exam Guide"
description = "Looking into the key Kanban metrics that enable consistent value delivery and a level of predictability. Tips for preparing for a Kanban certification."
date = "2026-02-03"
lastmod = "2026-02-03"
slug = "kanban-principles-metrics-littles-law-scrum"
featured = "/article_images/kanban-principles-metrics-littles-law-scrum-hero.jpg"
thumbnail = "/article_images/kanban-principles-metrics-littles-law-scrum-thumbnail.jpg"
tags = []
draft = false
categories = ["Professional growth"]
+++


Kanban is a methodology focused on visualizing workflows, continuous and predictable delivery, and constant optimization.

Learning about Kanban approaches and metrics is advantageous, whether you’re going to set up a Kanban flow in [Trello](/articles/free-trello-account-setup-personal-productivity/), [Notion](/articles/notion-certified-exam-preparation/) or [another project management tool](/articles/workflow-setup-principles-trello-asana-clickup-notion/), or just want to improve your processes by removing bottlenecks and speeding up the delivery time.

We will also talk about the ways of getting Kanban-certified – even if you won’t go through with it, [getting ready for a certification exam](/articles/how-pass-certification-exam-test-first-try-tips-techniques/) helps with understanding the subject better and gives new insights.

If you need practical help with [setting up or optimizing your workspace and processes](/workflow-setup-automation-expert-specialist-hire/), feel free to [contact me](/contact/).

{{< figure src="/article_images/kanban-principles-metrics-littles-law-scrum-hero.jpg" alt="Little's Law explained from an Agile Kanban perspective" caption="photo by \@ds-stories on Pexels">}}

{{< table_of_contents >}}


## Key concepts and terms to understand about Kanban

Whether you’re aiming to take a Kanban certification exam or just want to make the most out of your system, I advise having a solid understanding of the following:



* Kanban Pull system vs. push systems
* Little’s Law formula – understanding its logic and conditions
* [Key Flow Metrics](https://www.scrum.org/resources/blog/4-key-flow-metrics-and-how-use-them-scrums-events) (WIP, Throughput, Cycle Time, Work Item Aging)
* Implementing WIP limits
* Lagging vs. Leading indicators
* Service Level Expectations (SLE)
* Definition of Workflow
* Classes of service (CoS)
* Charts: [Cumulative Flow Diagram](https://monday.com/blog/project-management/cumulative-flow-diagrams/) (CFD), [Work Item Aging Chart](https://www.55degrees.se/post/managing-work-item-age-in-actionableagile)

In this article, I’ll mostly focus on Little’s Law and its implications, but will also give links to further study materials for the other points on the list.


## Little’s Law explained and applied


### The original formula by John Little

Little’s Law is a [theorem in queueing theory](https://en.wikipedia.org/wiki/Little%27s_law) that dictates the relationship between the number of customers, arrival rate, and time from entry to exit. It is expressed with a formula:

**L = λ * W**

**L** – Average number of customers

**λ** – average arrival rate

**W** – average wait time, or customer total service time

Other variables, like the order customers are served in, don’t play much role. The biggest culprit for causing bottlenecks and creating queues is the time it takes for the customer to be served.

As an example of application, here’s a [visualization of Little's Law formula funnel](https://www.pokutta.com/blog/littles-law-for-conference-review-backlogs/#littles-law-in-action) for reviewing academic papers for conferences.


### Little’s Law version used in Kanban and Agile

Little’s theorem originated from Operation Research, but quickly [found its way into Operations Management](https://www.55degrees.se/post/a-very-brief-history-of-little-s-law). In practice, the focus is more on an output – the items being produced – than on the input. So the perspective shifted from arrivals to departures, and the formula was written in different terms.

**WIP = TH * CT**

**WIP** – Work in Progress, average number of items that are worked on at a given moment.

**TH** – Throughput, average rate at which items are Done and leave the system.

**CT** – Cycle time, average time from the moment a task gets the “in progress” status till it’s Done.

Contrast to **Lead time** – the time it takes from when the work was first requested till it’s completed.

Lead time starts when a principal decision to do a task is made (when the customer steps into a store), and Cycle time starts when some action is taken towards completing it (when the cashier starts serving the customer) – and they both end when the task is finalized.


### Issues with the throughput perspective

Moving from arrivals to departures, or throughput, in the formula seems like a minor change, and in a perfect world it wouldn’t make a difference. Items rarely go missing from a conveyor belt in a factory.

But not all customers leave the store with a purchase. And in the actual projects, not all tasks reach the Done state – they could be abandoned, canceled, or take so long to complete that the number of items in progress considerably exceeds the number of completed items.

That leads us to the **key conditions of system stability**, as well as the importance of **WIP limits**.

{{< ebook-subscribe >}}


## Key Assumptions for applying the Little's Law formula

There's no singular list to be cited, but in his works, John Little describes conditions under which applying his formula makes sense. In modern discourse, they're often called “assumptions”.

For meaningful application of Little's Law formula, especially if we focus on throughput, the system must have the following properties:



1. Steady flow at the gates. On average, the number of items that enter the system has to equal the number that exit it on the other end.
2. All items that enter the system will exit it. Everything that is started gets Done, and nothing is lost or stuck indefinitely.
3. The number of WIP items in the system should be constant over the period of observation.
4. Consistent units of measurement. Apples to apples – whether you compare throughput over weeks, days, or hours, the same unit has to be used in all calculations.


## What is the practical application of Little’s formula?

Knowing the interdependency between work in progress, throughput and cycle time, and having stabilized the system, we could reasonably expect that modifying one of those parameters will influence the others.

So, if we reduce work in progress while keeping throughput the same and maintaining the average size of the items, each item will end up being delivered faster – thus the cycle time would also be reduced.

Understanding the principles of Little’s Law helps us see where the bottlenecks are, tune the systems to be more efficient, and have a degree of certainty when estimating when the work will be delivered (Service Level Expectations).


## Could Little's Law be used for prediction and forecasting?

John Little’s theorem isn’t meant to be a forecasting tool. But building a system that gets close to the conditions that make the formula work, and measuring certain key indicators over time, would allow using the dependencies that the formula describes to predictive advantage.

“When will it be done?” is the question in the title of Daniel Vacanti’s [book on Lean-Agile Forecasting](https://www.amazon.com/When-Will-Done-Lean-Agile-Forecasting/dp/0986436372) (2020), and at the core of his [book on metrics for predictability](https://www.amazon.com/gp/product/B0F388DZ5T) (2nd edition, 2025).

Daniel is the co-author of The Kanban Guide and the most recognized name associated with “Kanban plus Scrum”.

Watch Daniel explaining the principles of Little’s Law formula in a webinar. See other insightful webinars in my [list of free webinars to prepare for Scrum and Agile exams](/articles/free-scrum-agile-webinars-prepare-certification-exam/).

{{< vimeo 52683659 >}}


## Classes of service in Kanban methodology

Classes of Service (CoS) are used to categorize tasks based on their level of risk and the cost of *not* doing the task right now (cost of delay).

4 main classes of service are: Standard, Fixed date, Expedite, and Intangible. [Read more about the classes](https://teamhood.com/kanban-resources/kanban-classes-of-service/) and examples of their tasks in different types of teams. Each of the classes has its own number of percentage within the WIP limit, with the recommended limit for Expedites being 1 item.


## Getting a Kanban certification

[Obtaining a professional certification is worth it](/articles/are-certifications-worth-it/) not only because it enhances your profile, but mainly because of all the knowledge and insights you get along the way. Tackling the challenge makes you grow, and getting a badge is a nice bonus.


## Professional Scrum with Kanban certification (PSK I)

Scrum is a sprint-based Agile framework that could integrate Kanban principles in day-to-day work.

[Professional Scrum with Kanban](https://www.scrum.org/assessments/professional-scrum-with-kanban-certification) exam costs $200 per attempt. You need to answer 45 questions in 1 hour, and the passing score is 85%. The exam is [not proctored](/articles/online-proctored-testing-pros-cons/).

Once you get your PSK1 certification and a Credly badge, it’s good for life – [no need for regular renewal](/articles/renew-certification-or-let-it-expire/).


### Preparing for the Scrum with Kanban exam

First and foremost, you need to be well-versed in the principles of Scrum and have an [Agile mindset](/articles/develop-agile-mindset-guide/). Preparing for the PSK exam has a lot in common with [PSM I exam preparation](/articles/psm-1-certification-exam-preparation/), but with an additional layer of Kanban-specific concepts.



* Go through [blogs and articles suggested by Scrum.org](https://www.scrum.org/resources/suggested-reading-professional-scrum-kanban) as exam study materials.
* Read the Kanban Guide for Scrum Teams, which is [available for free download here](https://www.scrum.org/resources/kanban-guide-scrum-teams).
* Read the free and comprehensive book on [Flow Metrics for Scrum teams](https://prokanban.org/scrum-flow-metrics).
* Take [Scrum with Kanban open assessment](https://www.scrum.org/open-assessments/scrum-kanban-open) until you are 100% on all questions and make sure you have a solid understanding of all concepts you encounter and the logic of the answers.


### Will there be a PSK II certification?

[Scrum.org](Scrum.org) has three levels of their Professional Scrum Master certification – [PSM I](/articles/psm-1-certification-exam-preparation/), [PSM II](/articles/psm-2-certification-exam-preparation/), and [PSM III](/articles/psm-3-certification-exam-preparation/), as well as [three levels of Professional Scrum Product Owner](/articles/pspo-certification-exam-preparation/) (follow the links for the guides to those exams). But [other certifications are standalone](https://www.scrum.org/professional-scrum-certifications), even if they have “one” in the title.


## Professional Kanban certification by ProKanban

Another major certifying body is ProKanban. For more Kanban-related resources – free blogs and webinars, as well as book recommendations – [check out their study guide](https://www.prokanban.org/product/pk2) on the Professional Kanban II assessment page.

ProKanban also offers [free Kanban open assessments](https://www.prokanban.org/certifications). Taking them would let you gauge how well you understand the Kanban principles and metrics.


## Other frameworks you might find interesting

Here are more concepts and methodologies that you could look into:



* [Cynefin framework](/articles/cynefin-framework-decision-making-explained/) – risk framework for decision-making.
* [Product operating model](/articles/product-operating-model-non-tech-personal/) – a framework to deliver value-driven products.
