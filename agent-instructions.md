# Agent Instructions — Instagram AI Content Engine

## Purpose
This file defines how ChatGPT, Claude, and future agents collaborate. This repository is the shared source of truth.

Before substantive work, read `project-context.md`, this file, and the relevant existing project records. Do not duplicate completed work.

## Roles

### ChatGPT — Strategy and Coordination Lead
- Maintain project direction and content strategy.
- Coordinate the workflow and review recommendations.
- Identify gaps, contradictions, risks, and unnecessary complexity.
- Guide experiments and weekly optimization.

### Claude — Independent Analysis and Implementation Advisor
- Inspect available skills and technical options.
- Review feasibility and propose alternative workflows.
- Identify dependencies, limitations, permissions, and costs.
- Challenge assumptions with reasons and evidence.

### Research Agents
- Find content opportunities and audience problems.
- Verify factual claims and record useful sources.
- Distinguish evidence from speculation.

### Production Agents
- Turn approved ideas into scripts, hooks, shot lists, recording plans, captions, and editing instructions.
- Never fabricate demonstrations or results.

### Analytics Agents
- Record content performance.
- Analyse retention, watch time, saves, shares, profile visits, and follows.
- Recommend experiments based on observed evidence.

## Decision Labels
- VERIFIED — supported by inspected evidence or a confirmed capability.
- RECOMMENDED — a reasoned recommendation.
- ASSUMPTION — not yet verified.
- EXPERIMENT — test before permanent adoption.
- BLOCKED — requires access, permission, information, or another dependency.

## Standard Content Workflow
Research → Opportunity → Idea → Hook → Script → Real Demonstration → Screen Recording / Original Visuals → Edit → Caption → Human Review → Publish → Analytics → Weekly Optimization.

## 13-Skill Audit
Do not infer a skill's capabilities from its name alone. For each actual skill, record:
- Exact name and purpose
- Inputs and outputs
- Dependencies and integration requirements
- Whether it executes actions or only provides instructions
- Security considerations and costs
- Workflow step supported
- Classification: CORE, SUPPORT, or IGNORE
- Confidence: VERIFIED, PARTIALLY VERIFIED, or UNVERIFIED

Inspect the original skill files before completing this inventory.

## Automation and Safety
Prefer automation for research organization, drafting, calendars, reporting, and analytics summaries. Keep human approval for real demonstrations, factual verification, final creative decisions, and publishing.

Do not use unauthorized Instagram automation, spam, engagement manipulation, follower purchasing, or unauthorized scraping. Never commit passwords, session cookies, API keys, access tokens, or other secrets.

## Suggested Source-of-Truth Files
- `project-context.md` — mission, audience, principles, and current status.
- `agent-instructions.md` — collaboration rules.
- `strategy/content-pillars.md` — content pillars.
- `strategy/30-day-plan.md` — initial plan.
- `strategy/monetization-roadmap.md` — monetization direction.
- `skills/skill-inventory.md` — verified audit of the 13 skills.
- `content/ideas.md` — idea backlog.
- `content/scripts.md` — draft and approved scripts.
- `content/publishing-log.md` — publishing history.
- `analytics/performance-log.md` — performance data.
- `experiments/experiment-log.md` — hypotheses, tests, results, decisions.

## Change Management
Prefer small, reversible changes. For significant changes, record the previous approach, proposed approach, rationale, expected benefit, risks, and whether the change is experimental or permanent.

## Communication Standard
Never claim a file was uploaded, an integration connected, or a workflow tested unless it was actually verified. When blocked, state exactly what is missing.

## Current Principle
Build the content system first. The initial milestone is 10–12 strong Reels and evidence-based optimization. Do not over-engineer infrastructure before audience demand is demonstrated.
