---
layout: post
title: Event-driven thinking
description: >
  How I got hooked into the event-driven mindset
sitemap: false
hide_last_modified: true
---

This is something I should have done a long time ago, creating a place to write down my thoughts and 
experiences with building event driven systems.

Like many, I started my career in the software engineering space, building and maintaining ERP systems in my father's
company. I started from the trenches, all the way at the bottom, slowly working my way up to a place I felt I could
contribute the most. I was lucky enough to be able to work on a lot of different projects, from building a data 
replication engine to building applications to be ran on mobile devices.

It was during this time that I started to get interested in data. I was fascinated by the amount of data that was
flowing through our systems and the way it was structured, or not structured. Many years later, a close friend 
introduced me to the world of big data and I was hooked. At that time, it was still early days for big data and there
was only a handful of people around who were working on it, especially within Belgium. A few of us got together to
discuss these new papers being released and the new technologies that were being developed. It was a great time to
learn and an even better time to make close friends.

Soon after, I started guiding companies in their endeavors to build big data systems. Telco's, banks and airports 
were all looking to build systems that would allow them to make better decisions based on the data they were 
collecting. 

But there was an itch that would not go away. Something seemed "off" about the way we were building these systems. Yes,
we had access to huge amounts of data, but they were mostly snapshots without much context. It showed the consequence
or result of something that happened. It was a huge effort to interpret these consequences to try and understand what
caused them. Why weren't we tracking the causes instead of the results?

Through the years, I got more and more convinced that organisations needed to evolve past this consequence-driven 
approach into a cause-driven one. Truly, it was only a matter of time before I stumbled upon Apache Kafka and found
a technological foundation that could support this cause-driven approach. Back then, Apache Kafka was far from what 
it has become today, but the building blocks were available; a persisted distributed log of messages.

Using Apache Kafka, we were able to build a system that would track events and allow different business domains to
interpret these events into the state that makes sense for them. This was quite a different approach from trying to
come up with a company-wide master data model. Instead we allowed each business unit to build their own data model,
tailored to their needs. The only thing they needed to do was interpret the events that were flowing around into what
it meant for their data model.

Technically it all worked, but soon we discovered a hurdle that would take all our efforts to overcome. Business owners,
Architects and even developers struggled with this different way of thinking. It had a impact on how they would write
applications, design architectures and position product features. 

This is still one of the biggest problems today and for me the main reason for sharing my experiences thinking about, 
implementing and evangelizing this approach. I am planning to write some posts with thoughts and approaches as well as
some code projects to help anyone willing to dive into the event-driven endeavor.

