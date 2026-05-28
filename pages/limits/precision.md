---
title: Precision
parent: Limits & Warnings
nav_order: 3
layout: default
nav_enabled: true
permalink: /limits/precision/
---

# Overview

This section outlines precision limitations in cost tracking, authentication, Issue styling, syncing, and more.

# Features

## Cost Tracking

* prices can only be set and displayed in USD (United States Dollars)

# Styling

* details about Issues in their description – as seen on GitHub after an update – cannot be re-formatted/configured (they have only one style to allow for easy parsing by the product)

# Syncing

* Issues are pulled from the target GitHub repository every 2.00 seconds (to avoid hitting the rate limit while still allowing for remote pushes to the repo)
