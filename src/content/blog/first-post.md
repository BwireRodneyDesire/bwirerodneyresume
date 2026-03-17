---
title: "Smart Water Monitoring System (Web Platform)"
description: "A web dashboard that turns live tank readings into clear, actionable water management insights."
pubDate: "Mar 17 2026"
heroImage: "/images/website.png"
---

## Overview

The Smart Water Monitoring System web platform is a lightweight dashboard I built to make day-to-day water management easier. Instead of physically checking the tank, users can open a browser and immediately see the current level, system condition, and whether attention is needed.

This website serves as the information layer of the full solution. The embedded hardware handles sensing and signal collection, while the web interface translates those readings into a format that is fast to understand.

![Smart water web dashboard](/images/website.png)

## What I Built

I designed and deployed a static web interface focused on clarity, speed, and practical usability.

- Displayed water level readings in a clear, visual format
- Added system status indicators for quick diagnostics
- Designed the layout for remote monitoring on desktop and mobile
- Kept interactions simple so non-technical users can understand the system instantly

The core design decision was to reduce friction. Every section of the page answers one question: What is the current level, and does the user need to act now?

## Technical Approach

The platform was built with lightweight web technologies and deployed on GitHub Pages for low-maintenance hosting. Since the monitoring stack includes an embedded system, the web layer was structured as a clean visualization endpoint that can be updated with sensor data streams.

Technical priorities during development:

- Responsive UI with minimal visual noise
- Structured presentation of sensor data and state transitions
- Easy deployment process and straightforward maintenance
- Reliable integration path between IoT/embedded output and web display

## Key Insight

The biggest lesson from this project was that data collection is only half the work. The second half is interface design. Raw numbers from sensors are not useful until they are presented in a way that supports quick, confident decisions.

Building this dashboard reinforced my product mindset: engineering quality and user clarity have to move together.
