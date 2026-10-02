---
layout: default
title: Proposal to Final Report Writing Guide
description: A practical guide to developing an IQP research proposal and final report.
---

# Proposal to Final Report Writing Guide

Use this guide throughout ID2050 and your Interactive Qualifying Project (IQP). It helps your team develop a research proposal, carry that plan into the field, and shape what you learned into a clear final report.

The proposal is a starting plan, not a script. Return to it as your research evolves, update your understanding, and make sure the final report reflects the work you actually completed.

## Explore the guide

{% assign chapters = site.pages | where_exp: "item", "item.nav_order" | sort: "nav_order" %}
<div class="chapter-grid">
{% for chapter in chapters %}
  <a class="chapter-card" href="{{ chapter.url | relative_url }}">
    <span class="chapter-number">Section {{ chapter.nav_order }}</span>
    <strong>{{ chapter.title | escape }}</strong>
    <span>{{ chapter.description | escape }}</span>
    <span>Read section</span>
  </a>
{% endfor %}
</div>

## A guide to use as a team

The chapters are organized to help you move from project context and research design to findings, recommendations, and a polished report. You can read them in order or return to the sections that fit the work your team is doing now.

As you work, keep the central research story visible: what you needed to understand, how you investigated it, what the evidence shows, and what you can reasonably recommend.
