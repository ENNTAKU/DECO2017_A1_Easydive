---
title: Considering Login, Active Sessions, and Cookie-Based User Identity
date: 2026-05-11
author: Xi Lin
summary: This post evaluates the proposed login model in EASY DIVE as a lightweight session tool.
tags:
  - Login
  - Prototype Authentication
  - Scope Control
---
This post examines the proposed login model for EASY DIVE and evaluates it as a prototype-level session system rather than a full authentication feature.

Login can easily become more complex than the rest of a prototype if it is treated as a full security problem. In EASY DIVE, that would be unnecessary. The platform is not being designed to demonstrate production-level authentication. It is being designed to support logging, browsing, profile display, and continuity of user identity during testing.

The current proposal assumes that all users are logged in and that guest sessions are not supported. This simplifies the entire site structure. Pages do not need separate guest and user states, and records can be associated with a known user context from the beginning. A simple login page can therefore serve a narrower purpose: selecting or creating the active user rather than verifying credentials in a secure way.

This makes the cookie-based session idea more appropriate. If the active user ID or username is stored in the browser, pages can reuse that information without repeatedly fetching it from a database. That is especially helpful in a prototype where the emphasis is on interface flow rather than backend authentication design. It also aligns with the simplified data approach used elsewhere in the project.

The proposed login page is also useful for testing. Being able to create a new user or select from a small list of existing users makes it easier to move between profile states and check how records appear under different identities. In this context, logout does not need to mean ending a secure authenticated session. It only needs to clear the active user state and return the interface to the login page.

This model does have limits. It is not secure enough for a real deployed system. Cookies storing simple user identity should not be confused with full account protection. For the current prototype, however, that is acceptable because the purpose of login is continuity, not security demonstration.

A full authentication system would shift too much complexity into an area that is not central to the prototype’s main value. The simplified model keeps the login feature aligned with the rest of the project.