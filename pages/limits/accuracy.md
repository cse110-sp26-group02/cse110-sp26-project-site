---
title: Accuracy
parent: Limits & Warnings
nav_order: 2
layout: default
nav_enabled: true
permalink: /limits/accuracy/
---

# Overview

This section outlines limitations in cost tracking, authentication.

# Costs Tracking

* can only be set in USD
* prices can be manually or automatically set
    * input manually for 3 favorite Gemini models chosen from fetched list
    * auto-fetched from the Gemini API pricing page via URL tool-call with each detected operation (likely incurs an extra fee and accuracy is not guaranteed)

# Authentication

## Allowed Types

* only API key for Gemini 
* only PAT for GitHub
* no SSO for either

## Signing Out

* you can only sign out of each service by deleting your API key and/or PAT and then pressing the “action” button that confirms your configurations

# Styling

* details about Issues in their description – as seen on GitHub after an update – cannot be re-formatted/configured (they have only one style to allow for easy parsing by the product)
