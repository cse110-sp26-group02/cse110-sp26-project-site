---
title: Development
parent: Limits & Warnings
nav_order: 3
layout: default
nav_enabled: true
permalink: /limits/development/
---

# Overview

This section outlines development limitations and work-arounds. 

# Insight Level

## Limitations

* Each repo contributor can have their own instance of the product but they can only track their own agent's work.
* We do not currently offer a server or GitHub Action Workflow to aggregate and process the tracking information stored in each Issue across the repo.

## Work-Arounds

* You can set up a custom GitHub Action Workflow - while on a paid plan that allows for faster computations and agentic summaries - to aggregate insights from Issues across the entire repo

# Tracking Timeline

## Limitations

* Past agent traces on commits cannot be tracked. Only live ones once you start using our product.

## Work-Arounds

* Use our product from the start on new repos you create.
* You can export our traces so that they can be analyzed by an alternative that can identify agents who committed in the past.
