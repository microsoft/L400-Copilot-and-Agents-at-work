---
title: 'Exercise 05: Implement governance'
layout: default
nav_order: 6
has_children: true
---

# Exercise 05: Implement governance

## Introduction
Zava Retail Group's AI Center of Excellence is moving from prototypes to production-ready Copilot Studio agents that connect to Microsoft 365 data sources like SharePoint and Teams. During UAT, a prototype agent returned confidential program details to a user without the right clearance, and the investigation traced the issue back to inaccurate or missing sensitivity labeling in SharePoint. The incident reduced leadership confidence and triggered a firm directive from the CIO:

"We will not deploy any AI agent to production unless it meets enterprise-grade safety, governance, and lifecycle requirements."

## Description
In this exercise, you'll treat governance and observability as production gates. You will use Power Platform Admin Center to tighten sharing and access controls, validate that authentication and guardrails are working, and enable auditing for accountability. Then you will use Microsoft Purview DSPM for AI to assess oversharing risk, apply protections such as sensitivity labels, DLP, and encryption, and verify outcomes using telemetry. By the end, you will have the evidence and documentation needed to support lifecycle approval for a controlled rollout.


Here's what you can expect to accomplish in this exercise as you apply governance, security, and observability controls to your Copilot Studio agent.

- Task 01: Use Power Platform Admin Center (PPAC) governance controls to identify oversharing risks and enforce sharing/permission restrictions on Copilot Studio agents.

- Task 02: Test the agent to verify PPAC guardrails are working and identify any remaining sensitive‑data exposure.

- Task 03: Use Microsoft Purview DSPM for AI to detect oversharing risks and analyze sensitive data exposure from the agent.

- Task 04: Apply Purview protections (sensitivity labels, DLP, encryption, and policy controls) to the Microsoft 365 data tied to the agent, then retest to ensure issues are resolved.

- Task 05: Review compliance posture and telemetry in Purview and PPAC, then document governance settings and protection outcomes for lifecycle approval.
