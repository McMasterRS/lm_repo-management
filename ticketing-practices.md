---
layout: default
title: Best Practices For Ticket Formatting
parent: Issue Tracking
nav_order: 3
---

## Title & Description

Tickets should have a concise and descriptive title that captures the client's request or bug report. The description should be detailed and should state exactly how the customer expects the new feature to work or how they encountered a bug in the system. In case of a bug report, the description should also contain the "Steps to Reproduce" along with a brief description of the "Actual Behavior" and the "Expected Behavior" as detailed below. We cannot expect the clients to fully fill out these sections, so it is up to the developers to fill in any missing details.  

## Actual Behavior/Feature Description

This section should contain a brief description of the observed behavior of the bug/feature request. In the case of a bug, this section should clearly state which action cannot be performed due to the bug along with any relevant error messages. If the information provided by the client is insufficient, it is up to the developer to reproduce the bug and supplement this section with more details. In the case of a feature request, this section becomes the "Feature Description" and should include the current capabilities of the system and provide a brief overview of the area of the system that should be augmented with new capabilities. A detailed explanation of the requested feature(s) should be provided in the "Expected Behavior" section. This section should also clearly state the version number of the software in which the bug was encountered or that is missing the requested feature(s).  

## Steps to Reproduce

An effective bug report should clearly describe the steps that need to be taken to reproduce the bug in real-time. The steps should be thorough and easy to follow. Do not assume or skip any reproduction steps. Make sure to clearly describe where the bug is observed in the system (pages, buttons, URLs, etc.) as well as the steps that the user needs to take to observe the bug. If a bug only affects certain entities in the system (e.g., only certain instruments, users, etc.) make sure to list those entities in the bug report.  

For complex bugs that are not easily reproducible by the developers or for involved feature requests, it is best to meet one-on-one with the client and discuss further.  

## Expected Behavior

In the case of a bug report, this section should include a detailed description of how the system should behave to allow the user to complete the desired task. On the other hand, the "Expected Behavior" of a feature request should describe the new features or capabilities to be added to the system along with some surface-level implementation details that can be used to guide the developer working on this ticket. For more involved feature requests, make sure to describe what should happen in all possible scenarios so that the developer can account for these different conditions.  
