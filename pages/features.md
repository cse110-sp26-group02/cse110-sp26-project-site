---
title: Features
nav_order: 3
layout: default
nav_enabled: true
permalink: /features/
---

# Overview

This page overviews all of the product's features and compares against alternatives. 

# Us

## Tracking (Data Retrieved Per Issue)

* input/output/total tokens used
* price of input/output/total tokens used
* size of Issue (relative to others in same repo)
* indication if Issue blocks or is blocked by another
* indication if an Issue is similar/duplicated another
* local Issue processing time

## Extra Automations

* automatic processing stoppage after set budget reached

## Aggregation

* total Issues still open
* total tokens used across Issues
* total cost of tokens used vs budget

## Configuration

* set a token cost budget across all Issues (in USD)
* authentication via fine-grained GitHub PAT to securely tune access to your repo (preventing catastrophic effects commonly made by LLMs)

# Compared to Current Agentic Industry

## A Big Difference in Feature Focus & Quality
* Yes, OpenAI, Anthropic, Google, and other providers do give you token counts in their isolated online dashboards - but are they at your fingertips as a SWE, right in your IDE?
* Not only do we allow you to see live usage from within your development workspace, but it offers:
    1. Far *more detailed* compute tracking (including tokens and compute time).
    2. Organization per-Issue instead of per-commit. If it wasn't, it would be very hard to aggregate afterwards - especially if you want to experiment with models and see which one performs better for certain tasks. Such a low-level resolution would also be very inconvenient because budgets cannot be controlled - so you'd end up with huge, un-payable bills that shut down your business! It is also the *most natural* way to track thought patterns as a product is built (ignoring simple commits that don't contribute to actual features that ship). 
    3. Ability to judge and assign size, blockage, duplication, and more by tracking the contents of the Issue (vs adjacent ones and even compared to the repo contents themselves).
    4. Strong auto-summarization capability for Issues themselves, which uses the most needed insights relevant to the Issue.
 
## A Precision Tool
* We are a tool specially-built for the next generation SWE development experience.
* Instead of offering yet another wrapper that duplicates functionality, we focused on crafting the most efficient engine for taking care of the most important data type that large tools like GitHub ignore - Issues. Issues are the most useful data object in the modern development process; they can be plugged into Jira or your favorite generic task tracker and help a team fully visualize their path - vs incremental commits.

## Ultimate Convenience
* Not only do we provide a combination of unique tracking capabilities, but we make it very convenient.
* Other options force you to have their website open, burden you with new CLI commands, or eat up your time by making you manually wrap your agent's trigger functions (e.g. in Codex or other frameworks).
* With IssueSight, you can just click to install the extension in VS Code and get started right away.
* If you are looking for true "plug-and-play", get this going for your agents today!
