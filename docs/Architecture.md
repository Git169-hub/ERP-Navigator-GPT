# ERP Navigator Architecture

## Overview

ERP Navigator follows a documentation-driven architecture using ChatGPT Custom GPT.

Instead of connecting to a live ERP environment, the assistant answers user queries exclusively from uploaded ERP documentation while enforcing strict operational guardrails.

---

## Components

### User

The user asks ERP-related questions.

Examples:

- Explain Order-to-Cash
- Create Purchase Order
- Permission Denied error
- Posting Period Closed

---

### ChatGPT Custom GPT

Receives the request and manages the conversation.

Responsibilities:

- Understand user intent
- Ask clarifying questions
- Retrieve relevant documentation
- Generate structured responses
- Apply safety guardrails

---

### System Prompt

Defines the assistant's behavior.

Responsibilities:

- Assistant identity
- Scope
- Response format
- Safety policies
- Escalation rules
- Refusal policy

---

### Knowledge Base

The assistant searches only the uploaded documentation.

Files:

- ERP_Process_Guide.md
- SOP.md
- Transaction_Manual.md
- Error_Resolution_Guide.md
- ERP_FAQ.md

---

### Response Generator

Creates professional ERP guidance.

Response format:

- Summary
- Guidance
- Common Issues
- Recommended Next Step
- Important Notice

---

## Safety Layer

ERP Navigator never:

- Accesses live ERP systems
- Executes ERP transactions
- Changes workflows
- Modifies configurations
- Grants permissions
- Invents undocumented procedures

---

## Architecture Flow

User

↓

ChatGPT Custom GPT

↓

System Prompt

↓

Knowledge Base Search

↓

Relevant ERP Documentation

↓

Structured Response

↓

ERP Functional Guidance