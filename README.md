# AI Agent PM Interviewer

AI Agent PM Interviewer is a portable Agent Skill designed to conduct adaptive mock interviews for senior AI Agent product managers.

It is especially designed for experienced commerce and e-commerce product managers transitioning into AI-native product and Agent roles.

## What it evaluates

The skill evaluates capabilities across:

- AI fundamentals
- Model capability and routing
- Prompt and context engineering
- RAG and retrieval
- Tool calling and MCP
- Agent architecture
- Agent production engineering
- Evaluation and observability
- Guardrails and permissions
- Agent UX
- Commerce Agent design
- GEO
- GTM, pricing, business, and brand

The interview is adaptive rather than based on a fixed question list.

It dynamically:

- selects interview domains
- changes difficulty
- asks follow-up questions
- detects weak areas
- tests knowledge transfer
- produces a structured review

## Skill structure

```text
skills/
└── ai-agent-pm-interviewer/
    └── SKILL.md
```

## Usage

Install or load:

```text
skills/ai-agent-pm-interviewer/SKILL.md
```

Then trigger the skill with prompts such as:

```text
启动 AI 面试
```

or:

```text
开始 Agent 面试
```

or:

```text
Start an AI Agent PM mock interview.
```

## Interview philosophy

The goal is not to test whether the candidate memorized AI terminology.

The goal is to determine whether the candidate can take a real business problem and design a complete AI Agent system including:

```text
Business Problem
↓
AI / Agent Fit
↓
Architecture
↓
Models
↓
Context
↓
RAG
↓
Tools
↓
Workflow
↓
State
↓
Evaluation
↓
Guardrails
↓
Cost
↓
UX
↓
GTM
↓
Commercialization
```

The final target capability is:

**Commerce Product Expert → AI Agent Product Expert**

## Compatibility

This skill is designed to be platform-independent.

Voice capability is optional.

Persistent memory is optional.

If voice is unavailable, the Agent should use concise text suitable for oral-style interviewing.

If persistent storage is unavailable, interview state should be maintained only within the current session.
