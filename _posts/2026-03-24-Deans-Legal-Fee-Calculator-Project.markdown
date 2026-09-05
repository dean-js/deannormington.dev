---
layout: post
title: Dean's Legal Fee Calculator v1.00 - Project Overview
date: 2026-03-24 17:05:00 +0000
description: A personal insight and reflection on creating Dean's Legal Fee Calculator - a simple but efficient calculator application for legal industry accounting and invoicing.
img: # Add image post (optional)
fig-caption: # Add figcaption (optional)
categories: [Legal Tech, Portfolio Posts]
tags: [projects, law, application, legal, portfolio, legal-tech]
---

## Why Did I Create Dean's Legal Fee Calculator?

While studying law at university in my first year, I found my interest and desire to learn software development reignited once and for all - creating applications and building foundational knowledge through hands-on projects alongside my studies. After a meeting with the university's careers department, and talking about a legal tech event held annually, I wanted to build something small as a networking point to showcase other skills I had.

As someone who didn't have much understanding of general finances, let alone accounting and legal finances, this was interesting to research - I found it genuinely insightful learning about different rates, how billing for time is processed, and the types of disbursements involved. I made sure disbursements were an adjustable option within the calculator rather than a fixed fee the user had to input, which helps split out the different types of disbursements. I also made sure the project included a disclaimer following SRA and standard firm practices within the UK legal sector, while keeping the application flexible enough to be tweaked and set up for private small-firm use on basic billing and invoicing.

From a different perspective, as a first-year law student, not many others would have given this type of project much thought - understanding how the internals of a firm are broken down gives a bigger advantage, since most students have their sights set on becoming barristers or solicitors and just stick to the curriculum and other more typical types of experience. So this was definitely a good way to also showcase commercial awareness. However, my interest in learning software development outweighed my passion for the subject of studying law, so this is more of a testimony to a failed interest in "practising" law, but a sparked interest in legal tech.

In future, this could be a potential project route, so it doesn't feel like my time studying law was a complete loss or wasted - it could open doors to other legal tech projects down the line.

Looking back, this project was more significant than it seemed at the time. I built it partly to keep the spark of my degree alive while I was still studying, using legal knowledge I already had rather than starting from nothing. Without quite realising it then, it acted as the first real step in pivoting back to tech - the start of building a portfolio around knowledge I already had, while picking up new knowledge through hands-on learning rather than a classroom.

## What Is Dean's Legal Fee Calculator?

The app lets the user calculate an invoice of costs within a legal case. Depending on the type of case, features such as disbursements make it easier to add and calculate the overall cost to invoice a client, whether that's over email as a PDF or in print. The application lets the user add the type of legal personnel involved and any court costs or other costs, then automatically adds VAT at the end of the calculation in a total summary. It also implements the 6-minute billing rule, which splits each hour into 10 six-minute units:

Total Cost = (Total Units × (Hourly Rate ÷ 10)) + VAT

To break this down more simply, here's an example of how this calculation works within the calculator:

If a solicitor's hourly rate is £200 per hour:

- **Unit cost:** £20 per 6-minute unit
- **Apply to time:** A 5-minute email is billed as 1 unit (£20 + VAT)
- **Round up:** A 7-minute call is billed as 2 units (£40 + VAT)

## To Note

- **Minimum unit:** Even a 2-minute phone call is usually recorded as a full 6-minute unit.
- **VAT:** 20% VAT is typically added to these charges, changing a £200/hr rate to £240/hr for non-VAT-registered clients.
- **Purpose:** This method is used for transparency and to ensure compensation for small, frequent tasks like reviewing short emails or taking quick calls.
- **Non-billable vs. billable:** 6-minute units only apply to client-facing work (billable time).

## Key Features of Dean's Legal Fee Calculator v1.00 (Early Build)

- Disbursement calculation
- VAT implementation
- Types of legal personnel - showing a different rate, for example a senior earning more than a junior
- Calculation for the 6-minute billing rule

## What Did I Learn Building This Project?

What I learned while creating this project:

- CSS styling
- Data input handling
- Exporting calculations

## What I Want to Improve for Dean's Legal Fee Calculator v1.10

The features I want to improve and add in future for Dean's Legal Fee Calculator v1.10:

- VAT toggle - small patch fix
- Adding different types of legal personnel - for example, a senior adding a junior's rates within a caseload - major update (v1.10)
- Changing disbursements - adding stamp duty tax and more options in the disbursement section
- A more professional but minimal user interface, maintaining functionality and ease of use

## Conclusion

To conclude this post, my aim is to build a minimalist but efficient legal fee calculator for small, private, basic use with the current features implemented in v1.00.

However, I plan to keep updating and adding features in small patches over my spare time, working towards the next major update, Dean's Legal Fee Calculator v1.10, while keeping up my interest in legal tech and future projects within that space.
