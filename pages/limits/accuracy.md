---
title: Accuracy
parent: Limits & Warnings
nav_order: 2
layout: default
nav_enabled: true
permalink: /limits/accuracy/
---

# Overview

This section outlines limitations in cost tracking, authentication, Issue styling, and more.

# Features

## Cost Tracking

* prices can only be set and displayed in USD (United States Dollars)
* prices can be manually or automatically set
    * input manually for 3 favorite Gemini models chosen from fetched list
    * auto-fetched from the Gemini API pricing page via URL tool-call with each detected operation (likely incurs an extra fee and accuracy is not guaranteed)

## Summarization

* summarization quality is inversely proportional to size of repo (due to current universal LLM architecture limitations)

## Agent Detection

* repo commits with co-authors (including agents) will not be detected as agent-based
* ensure that you disable CoPilot and co-authoring on your repo to prevent this (see GitHub's Settings page)

# Authentication

## Allowed Types

* only API key for Gemini 
* only PAT (Personal Authentication Token) for GitHub
* no SSO for either

## Signing Out

* you can only sign out of each service by deleting your API key and/or PAT and then pressing the “action” button that confirms your configurations

# Styling

* details about Issues in their description – as seen on GitHub after an update – cannot be re-formatted/configured (they have only one style to allow for easy parsing by the product)
