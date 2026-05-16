---
title: Analysing User Flow, Wireframes, and Interaction Structure
date: 2026-05-01
author: Xi Lin
summary: This post analyses EASY DIVE through user flow and interaction structure. 
tags:
  - User Flow
  - Wireframing
  - Interaction Design
---
This post considers how the revised EASY DIVE structure translates into user flow and page-level interaction.

The current version of EASY DIVE has five pages and a top navigation bar. That structure is simple enough to remain readable, but it still depends on each page having a distinct role. If the pages overlap too much, the site becomes harder to understand. For that reason, user flow needs to be considered alongside the feature list.

The Home page has the clearest job. It introduces EASY DIVE and directs users to the two key actions: “Record a Dive” and “Search Dive Sites.” This is an effective interaction decision because it stops the homepage from becoming a crowded dashboard. It tells users what the platform is for and gives them an immediate route into either contributing or browsing.

The Log Dive page is more complex because it is form-based. Its main challenge is not just the number of fields, but how those fields behave together. State and dive site are linked. “Custom Site Name” appears only in one condition. The live preview updates while the user fills in the form. A page like this needs sectioning and spacing in the wireframe, otherwise it risks looking like one long block of input. The live preview is also part of the interaction structure rather than just decoration, because it provides immediate feedback about what kind of record is being created.

Explore Sites works differently. It is based on filters and card browsing rather than form completion. The search bar, state filter, site type filter, and difficulty filter all narrow a card-based result set. This layout suits the task because users are not only retrieving one result; they are comparing options. A card structure makes it easier to scan visibility, current, temperature, species, and description side by side. The “no results” message is also part of the interaction logic because it helps the user recover from failed searches.

Dive Shops uses a more controlled browsing pattern. Instead of open search, it starts with region buttons and then displays dive shop cards. That reduces visual overload and fits the page’s narrower purpose. The same principle appears in the Profile page, which combines a visible profile card with an edit form. This split works well because it separates viewing identity from changing it.

The current user flow is therefore relatively direct: enter through Home, move to Log Dive or Explore Sites, browse Dive Shops when local support is needed, and manage personal information through Profile. The wireframing challenge is not adding more steps. It is keeping each page focused enough that the site remains easy to move through.