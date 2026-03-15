# Claude Certified Architect — Exam Prep

A Claude Code plugin for studying the Claude Certified Architect — Foundations (CCA-F) certification exam.

Covers all 5 domains, 30 task statements, 6 exam scenarios, anti-patterns, and decision rules from the [official Anthropic exam guide](https://anthropic.skilljar.com/claude-certified-architect-foundations-access-request).

## Install

```
/plugin marketplace add carolinacherry/claude-certified-architect
/plugin install claude-certified-architect
```

Restart Claude Code after installation.

## Usage

```
/claude-certified-architect              # Exam overview, pick a domain
/claude-certified-architect 1            # Study Domain 1 (Agentic Architecture)
/claude-certified-architect quiz         # 10-question practice exam, all domains
/claude-certified-architect quiz 3       # Focused quiz on Domain 3
```

Practice questions use Claude Code's interactive selector for answer selection.

## Domains

| # | Domain | Weight |
|---|--------|--------|
| 1 | Agentic Architecture and Orchestration | 27% |
| 2 | Tool Design and MCP Integration | 18% |
| 3 | Claude Code Configuration and Workflows | 20% |
| 4 | Prompt Engineering and Structured Output | 20% |
| 5 | Context Management and Reliability | 15% |

## Exam Scenarios

Questions are framed within these production contexts (4 of 6 selected per exam):

1. Customer Support Resolution Agent
2. Code Generation with Claude Code
3. Multi-Agent Research System
4. Developer Productivity Tools
5. Claude Code for CI/CD
6. Structured Data Extraction

## Exam Format

- 60 scenario-based multiple-choice questions
- 120 minutes, proctored
- Passing score: 720 / 1000
- No penalty for guessing
- Currently available to Anthropic partners

The certification is partner-exclusive, but the knowledge tested applies to anyone building production applications with Claude Code, the Claude Agent SDK, or the Claude API.

## What This Plugin Teaches

- Agentic loop lifecycle and the three anti-patterns the exam tests
- Multi-agent orchestration with hub-and-spoke coordinator patterns
- When to use programmatic enforcement (hooks) vs prompt-based guidance
- Tool description design as the primary mechanism for tool selection
- Structured error responses with error categories and retry logic
- CLAUDE.md hierarchy, path-specific rules, and CI/CD integration
- Few-shot prompting, structured output with tool_use, and validation-retry loops
- Context preservation, escalation triggers, and information provenance

## Browser-Based Study Guide

For a visual, interactive experience with timed quizzes and progress tracking, see [CCA Prep](https://github.com/carolinacherry/cca-prep).

## Source

Based on the [Claude Certified Architect — Foundations Certification Exam Guide](https://anthropic.skilljar.com/claude-certified-architect-foundations-access-request) published by Anthropic.

## License

MIT
