---
title: Comparing Feature Ideas and Working Out the Core of the Platform
date: 2026-04-24
author: Xi Lin
summary: This post compares the major feature groups in EASY DIVE and identifies structured dive logging as the core of the prototype. 
tags:
  - Functional Requirements
  - Prototype Development
  - Platform Design
---
This post compares the current feature directions in EASY DIVE and examines which function should operate as the centre of the prototype.

The revised outline includes several feature groups: dive logging, site exploration, dive shop browsing, and profile-based identity. All of them are useful, but they do not contribute in the same way. A clearer prototype depends on identifying which function generates the main value and which functions work in support of it.

The strongest relationship in the current structure is between Log Dive and Explore Sites. Log Dive collects structured information about a single dive, including conditions, marine life, notes, and site details. Explore Sites uses that information as searchable material through filters such as state, site type, difficulty, and species. This makes dive logging more than a single feature. It is the feature that produces the content the rest of the platform depends on.

This distinction helps separate core and supporting features. Dive Shops adds useful local contact information, but it does not generate the community data that defines the platform. Profile gives context through certification, experience level, dive count, tags, and contact visibility, but again it supports interpretation rather than acting as the main activity. These pages are necessary, but their role becomes clearer when they are positioned around a central record system.

Treating dive logging as the core also helps the other pages make more sense. Explore Sites becomes the browsing and comparison layer. Dive Shops becomes a local service layer. Profile becomes a lightweight identity layer that helps users read records and identify other divers. If all of these were treated as equally central, the prototype would risk becoming a collection of unrelated pages rather than one connected system.

There is also a scope advantage in using this hierarchy. The assignment asks for a focused prototype, not a platform that attempts every possible function at the same depth. Defining structured dive records as the central feature allows the rest of the interface to remain aligned with that purpose. It also matches the stated aim of helping users record sites, compare real conditions, and discover local contacts.

The feature comparison therefore suggests a layered model. At the centre is the dive log. Around it sit search, profile context, and local shop information. This is more coherent than treating the platform as a general-purpose social site with multiple unrelated tools.