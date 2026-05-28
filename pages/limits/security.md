---
title: Security
parent: Limits & Warnings
nav_order: 1
layout: default
nav_enabled: true
permalink: /limits/security/
---

# Overview

This section outlines security limitations and pre-cautions. 

# Encryption

## Limitations

* None of the extension's data is encrypted at rest. 
* Only packets sent to cloud services are protected by HTTPS.

## Pre-Cautions

* If your machine is compromised, your keys and PAT could be stolen and used for malicious purposes.
* To counter the effects of this potential problem, ensure that you granularly select only the privileges needed by this extension.
