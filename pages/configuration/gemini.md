---
title: Gemini Settings
parent: Configuration
nav_order: 2
layout: default
nav_enabled: true
permalink: /configuration/gemini/
---

# Overview

This section outlines steps for setting up Gemini (our product's native cloud LLM provider for analysis) - more specific than "QuickStart". 

## Guidance

Once you get on the "Configuration" page by clicking the rightmost icon in the top navigation menu of the extension...

### Authentication

1. Find the text input space that is labelled with "API Key" under the "Google Gemini" section.
2. Enter your Gemini API Key. You can click on the link provided at the bottom of the "Google Gemini" section to learn how to obtain it from Google AI Studio.
3. Press the "Accept Changes" button at the end of the page. If nothing lights up in a "red" color, then you are authenticated.

### Model Preference

1. Find the text input space that is labelled with "Preferred Model" under the "Google Gemini" section.
2. Enter a value in USD that you want to set as a budget for the Gemini CLI agent that commits code to your local repo.
3. Press the "Accept Changes" button at the end of the page. If nothing lights up in a "red" color, then your budget is confirmed.

### Budget

1. Find the text input space that is labelled with "Budget" under the "Google Gemini" section.
2. Enter a numeric value (automatically considered in US Dollars) that you want to set as a budget (applied as aggregate between the Gemini CLI agent that commits code to your local repo and the generations the extension uses in the background for analysis)
3. Press the "Accept Changes" button at the end of the page. If nothing lights up in a "red" color, then your budget is confirmed.
