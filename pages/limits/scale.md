---
title: Scale
parent: Limits & Warnings
nav_order: 4
layout: default
nav_enabled: true
permalink: /limits/scale/
---

# Overview

This section outlines scale limitations and work-arounds. 

# Insight Resolution

## Limitations

* Each repo contributor can have their own instance of the product but they can only track their own agent's work.
* We do not currently offer a server or GitHub Action Workflow to aggregate and process the tracking information stored in each Issue across the repo.

## Work-Arounds

* You can set up a custom GitHub Action Workflow - while on a paid plan that allows for faster computations and agentic summaries - to aggregate insights from Issues across the entire repo

# Amount of Agents

* any number of agents can be triggered in parallel via VS Code

# Amount of Issues

* our extension tries to handle as much data as possible (you are only limited by your system's RAM, since that is where it operates currently)
* we recommend at least 1.00gb of free RAM to handle upcoming agent-focused repos, which will likely contain a lot of auto-created Issues
