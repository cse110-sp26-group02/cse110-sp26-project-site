---
title: Accuracy & Reliability
parent: Limits & Warnings
nav_order: 2
layout: default
nav_enabled: true
permalink: /limits/accuracy-and-reliability/
---

# Overview

This section outlines accuracy and reliability limitations in cost tracking, authentication, Issue styling, and more.

# Features

## Cost Tracking

* prices can be manually or automatically set
    * input manually for 3 favorite Gemini models chosen from fetched list
    * auto-fetched from the Gemini API pricing page via URL tool-call with each detected operation (likely incurs an extra fee and accuracy is not guaranteed)

## Summarization

* summarization quality is inversely proportional to size of repo (due to current universal LLM architecture limitations)

## Agent Detection

* repo commits with co-authors (including agents) will not be detected as agent-based
* ensure that you disable CoPilot and co-authoring on your repo to prevent this (see GitHub's Settings page)
