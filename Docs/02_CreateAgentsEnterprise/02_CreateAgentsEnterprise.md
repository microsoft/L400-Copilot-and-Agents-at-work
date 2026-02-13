---
title: 'Exercise 02: Create agents for enterprise integrations'
layout: default
nav_order: 4
has_children: true
---

# Exercise 02: Create agents for enterprise integrations

## Introduction
Zava’s most valuable agent opportunities depend on connecting to real enterprise systems across a hybrid landscape. Inventory accuracy, store operations, and workforce workflows all require agents that can retrieve data from external services, apply context, and enforce domain boundaries, all without exposing sensitive data or bypassing governance.

In this exercise, you’ll build an enterprise integration pattern using a parent agent that routes requests to specialized child agents. You’ll extend Copilot Studio with a custom OpenAPI connector and an MCP server to demonstrate how agents can securely call business tools and access scoped data sources. This is the core capability Zava expects from a strategic AI partner: connectors, extensibility, and safe orchestration across domains.

This exercise includes the following tasks: 

- Create a parent agent to manage two child agents.
- Create a custom OpenAPI connector to connect to external marketing systems by using a custom OpenAPI connector.
- Deploy an MCP Server to access human resources (HR) data.
- Create a child agent to handle all marketing inquiries.
- Create a child agent to handle all HR inquiries.