---
title: Planning User Testing and Identifying What the Prototype Needs to Prove
date: 2026-05-18
author: Xi Lin
summary: This post outlines a task-based testing approach for EASY DIVE.
tags:
  - User Testing
  - Task-based Testing
  - Prototype Evaluation
---
This post considers what user testing should focus on in EASY DIVE and which parts of the prototype most need evaluation.

User testing in this prototype should not be treated as a broad final-stage activity. It should be used to check whether the interface is understandable in the specific places where misunderstanding is most likely. Since EASY DIVE is meant to be simple and beginner-friendly, the main testing concern is clarity.

The Log Dive page is the first place where testing is necessary. It contains the largest number of fields and the highest chance of friction. Testing should therefore examine whether users understand labels such as current strength, surge, visibility, feeling tags, and marine life selections. It should also check whether the linked state-and-site behaviour is clear, whether the “Custom Site Name” logic is noticeable, and whether the live preview helps users understand the record they are creating.

The second major testing area is Explore Sites. This page depends on search and filtering, so the main question is whether users understand how to narrow results. Site name search, species search, state filtering, site type filtering, and difficulty filtering all need to feel predictable. The “no results” message should also be tested because it affects whether users can recover when a search fails.

Dive Shops should be tested for browsing logic. The region-first structure is a deliberate simplification, so testing should check whether users immediately understand that regions are the entry point for finding contact cards. The page does not need to support complex search if the browsing behaviour is already clear.

Profile requires a different kind of test. The issue here is whether users can distinguish between displayed identity information and editable fields. Certification, experience level, dive count, contact visibility, and interest tags are all simple enough in structure, but their arrangement still affects how easy the page is to interpret.

A task-based testing format is the most suitable approach. Example tasks could include recording a dive at Shelly Beach, searching for sites associated with turtle sightings, finding a Queensland dive shop, or updating the contact link in Profile. These tasks are concrete enough to expose hesitation, confusion, and navigation errors.

The testing focus should remain on whether the prototype is readable and usable at page level, not on proving technical sophistication.