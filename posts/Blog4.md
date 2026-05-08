---
title: Thinking About Data Structure Based on What I Can Actually Build
date: 2026-05-04
author: Xi Lin
summary: In this post, I started connecting our feature ideas to the kind of web development I can currently build with HTML and Java.
tags:
  - Data Structure
  - Technical Feasibility
  - Web Development
---
This week, I started thinking less about features as ideas and more about what they would actually require if I had to build them. Since my current technical learning is still mainly based on HTML with Java backend development, this made me realise that some ideas feel much more realistic than others once I imagine how the data would be submitted, handled, and shown on a webpage.

Before this, I was mostly thinking about the platform from a user and design perspective. I was focusing on what information should be shown and how the pages might connect. But this week I started asking a more practical question: if I actually had to build these features with my current skills, what would that look like? Once I started thinking like that, the project immediately felt more specific.

For example, the user profile feature sounds simple at first, but it still needs a clear structure. If I were building it, I would probably make it as a form where users enter or select information like username, how long they have been diving, gender if they want to share it, a short self-introduction, and a few diving-related tags. At first I thought it might be nice to let users write anything they want for tags, but the more I thought about it, the less practical that felt. With my current skill level, preset options make much more sense. They are easier to handle in HTML forms, easier for Java to receive and process, and easier to display consistently later.

The same thing happened when I thought about dive-site records. I think this is one of the more realistic features for me to build because it fits a clear input-and-output structure. A user could choose a dive site and then submit information like current strength, visibility, marine life, personal reflections, and maybe an image reference. I can imagine this as a normal form submission: the user fills in the page, the backend receives the data, and then the record is displayed on another page for browsing. That feels achievable. What feels much less achievable is anything that depends on more advanced processing, like automatically analysing records or giving users smart recommendations based on past data.

I also realised this when thinking about buddy matching. As an idea, it sounds useful, but once I try to imagine how I would actually build it, it starts feeling too complicated. A real matching system would need a lot more logic, such as comparing user experience, preferences, and maybe availability. That is beyond what I feel confident doing right now. Because of that, I think a more realistic version is much simpler: users can look at profiles, see someone’s diving-related tags, and use a contact method to reach out by themselves. It is less advanced, but it is something I can actually build and explain.

For local dive shop information, the structure feels even more manageable. I can imagine a page where users choose a region first, then view dive shop cards with the name, image, address, contact details, and a short introduction. This feels suitable for my current level because the information is structured and the interaction is not too complicated.

My main takeaway this week is that technical feasibility becomes much clearer when I stop thinking in abstract terms and start imagining actual pages, forms, and backend handling. Right now, I think I can realistically build features based on structured input, simple storage, and clear display. What I cannot do well yet are features that depend on complex logic or highly dynamic systems. For me, this is a useful reminder that designing a good prototype is not only about choosing interesting features, but also about understanding what I can genuinely build with the skills I currently have.