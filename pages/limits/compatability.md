---
title: Compatability
parent: Limits & Warnings
nav_order: 5
layout: default
nav_enabled: true
permalink: /limits/compatability/
---

# Overview

This section outlines limitations in compatability.

# Agent Models

## General 

* Any model is compatible (as long as it is launched and used through VS Code).

## Full Tracking

* Token and cost tracking is included for the product's native Gemini agent calls (models cannot be switched out currently).
* Token and cost tracking for agents you assign to Issues (through VS Code) is only available for models built by Google, OpenAI, or Anthropic.
* Token counts and costs constantly change, so we cannot deliver a very reliable product if we try to cover all providers, which constantly expand and change their tokenizations/prices.
* We do not plan on supporting another cloud model provider beyond those because it is unlikely that these giants will be beaten and people mostly converge to always choose the best model available when using the cloud.

# Tracking Timeline

## Limitations

* Past agent traces on commits cannot be tracked. Only live ones once you start using our product.

## Work-Arounds

* Use our product from the start on new repos you create.
* You can export our traces so that they can be analyzed by an alternative that can identify agents who committed in the past.

# Authentication

## Allowed Types

* only API key for Gemini 
* only PAT (Personal Authentication Token) for GitHub
* no SSO for either

## Signing Out

* you can only sign out of each service by deleting your API key and/or PAT and then pressing the “action” button that confirms your configurations

