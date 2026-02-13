---
title: 'Exercise 04: Evaluate Copilot Studio Agents'
layout: default
nav_order: 5
has_children: true
---

# Exercise 04: Evaluate Copilot Studio Agents

## Introduction

Zava’s CIO has made approval criteria explicit: no AI agent reaches production without evidence of groundedness, correct tool usage, boundary adherence, resilient error handling, and stable behavior. That means the COE needs more than ad-hoc testing, as they need a repeatable evaluation framework that can certify agents and diagnose failures before rollout.

In this exercise, you’ll evaluate agents using structured test sets, automated question generation, and a CSV-based evaluation framework for repeatable execution. You’ll analyze how the agent performs against quality and safety expectations, identify where responses drift or rely on the wrong knowledge sources, and capture results that support lifecycle decisions. By the end, you’ll have an evaluation approach that aligns with Zava’s requirement for enterprise-grade readiness.

**In this lab, you'll complete the following technical tasks:**

- Prepare the environment for evaluating an agent.
- Run evaluations by leveraging AI to generate questions based on existing tools and knowledge or manually add your own test sets.
- Provision and Configure a CSV‑Based Evaluation Framework for Test Execution.
- Discover how valuable the default option is may impact your accuracy.