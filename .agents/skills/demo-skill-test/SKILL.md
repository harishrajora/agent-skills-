---
name: demo-skill-test
description: A demo skill created to test the full Agent Skills for All installation flow. Use when verifying that npx agentskillshub-cli add correctly clones, installs, and reports telemetry to the website. Triggers on "demo", "test skill", "verify install".
category: testing
---

# Demo Skill Test

This is a demo skill created to verify end-to-end flow for the Agent Skills for All ecosystem.

## When to Use

Use this skill when:
- Testing the CLI installation pipeline
- Verifying telemetry from `npx agentskillshub-cli add` reaches the website
- Demonstrating how skills are discovered, installed, and tracked

## Instructions

1. Confirm the skill was installed by checking the agent's skills directory (e.g., `.claude/skills/demo-skill-test/`)
2. Confirm the install count incremented on the homepage at https://agentskillsforall-ui.vercel.app/
3. Confirm the skill appears in search results when querying for "demo-skill-test"

## Notes

- This skill performs no real action when triggered.
- It exists purely to validate the install + telemetry pipeline.
- Remove after testing if not needed.
