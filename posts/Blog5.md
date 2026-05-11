---
title: Thinking About Whether We Actually Need an API
date: 2026-05-11
author: Xi Lin
summary: In this post, I reflected on whether our platform should use an API and where APIs might seem useful
tags:
  - API
  - Technical Feasibility
  - Scope Control
---
This week, I started thinking about a question that feels quite important for the technical direction of the project: do we actually need to use an API? At first, using an API sounded like a good way to make the platform feel more powerful, but the more I thought about it, the more I realised that it also raises a lot of practical issues for a project at our current stage.

When I first heard “API,” my immediate reaction was that it sounded useful. It made me think of live information, external data, and features that could make the platform feel more complete. For a diving community platform, there are definitely places where an API could seem relevant. For example, local dive shop information might be connected to map or location services. Dive site information could potentially be linked to external databases. Even marine life information or environmental conditions could sound like areas where outside data might help.

However, once I stopped thinking about APIs as a general idea and started thinking about what we are actually trying to build, I became less convinced that they are necessary right now. A lot of the value of our platform comes from community-submitted records, browsing useful local information, and helping users connect through structured content. Those things do not automatically require outside data. In fact, for the parts I am mainly responsible for, such as profile information, dive-site browsing, and dive shop display, the main challenge is already making our own data flow work clearly. Before adding external systems, I think it makes more sense to build a stable version of the core platform itself.

I also started thinking more honestly about the technical side. Since my current skill level is still based mainly on HTML and Java backend development, I know I can understand form input, backend handling, and displaying structured information on pages much better than I can handle more advanced integration. If we use an API, that means I would also need to think about sending requests, handling responses, possible errors, formatting returned data, and depending on an outside service that may not always behave the way I expect. That adds another layer of complexity, and right now I am not sure that complexity would actually improve the prototype enough to justify it.

There is also the issue of project scope. This assignment is asking us to develop a focused and technically sound prototype, not the most feature-heavy system possible. If we try to include APIs just because they seem impressive, there is a risk that the project becomes harder to manage without actually becoming more useful. For example, local dive shop information could still be presented well through manually structured content rather than external data fetching. That approach may be less dynamic, but it is much easier for me to control, style, and explain.

At this stage, I do think APIs are still worth discussing, because they help reveal what kind of data our platform might eventually grow into using. But for the current prototype, my conclusion is that they are not necessary. Right now, it feels more responsible to focus on building our own core features clearly and reliably rather than introducing technical complexity that we are not yet fully prepared to handle. For me, this has been a useful reminder that a stronger project is not always the one with more technologies. Sometimes it is the one that stays within a scope we can actually build well.
