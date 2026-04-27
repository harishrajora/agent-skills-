---
name: demo-test-2
description: A second demo skill created to test the Agent Skills for All installation flow. Use when verifying that npx agentskillsforall add correctly clones, installs, and reports telemetry to the website. Triggers on "demo test 2", "second test skill", "verify install loop".
category: testing
---

# Demo Test 2

This is the second demo skill created to verify end-to-end flow for the Agent Skills for All ecosystem with the new package name.

## When to Use

Use this skill when:
- Testing the published `agentskillsforall` package on npm
- Verifying telemetry from `npx agentskillsforall add` reaches the website
- Demonstrating that the new CLI name works identically to the old one

## Instructions

1. Confirm the skill was installed by checking the agent's skills directory (e.g., `.claude/skills/demo-test-2/`)
2. Confirm the install count appeared on the homepage at https://agentskillsforall-ui.vercel.app/
3. Confirm the skill is searchable via `npx agentskillsforall find demo-test-2`

## Notes

- This skill performs no real action when triggered.
- Created on 2026-04-27 to validate the renamed CLI package.
- Remove after testing if not needed.
