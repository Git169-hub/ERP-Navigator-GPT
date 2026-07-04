# ERP Navigator – ERP Functional Support Assistant

> A Custom GPT designed to provide ERP functional support by guiding users through business processes, ERP transactions, standard operating procedures (SOPs), and common error resolution using internal ERP documentation.

---

## Project Overview

ERP Navigator is a Custom GPT that assists business users, functional consultants, and support analysts with ERP-related questions.

Instead of accessing a live ERP environment, the assistant provides structured, documentation-based guidance for common ERP functional scenarios while maintaining strict compliance with organizational boundaries.

This project was developed as part of an AI Custom GPT assessment focused on designing a reliable ERP Functional Support Assistant.

---

## Key Features

- Explain ERP business processes
- Guide users through ERP transactions
- Explain Standard Operating Procedures (SOPs)
- Answer ERP functional questions
- Help troubleshoot common ERP errors
- Ask clarifying questions before answering
- Recommend escalation when administrator intervention is required
- Respond only from uploaded ERP documentation
- Refuse unsupported or out-of-scope requests
- Never access or modify live ERP systems

---

## Supported ERP Topics

### Business Processes

- Order-to-Cash (O2C)
- Procure-to-Pay (P2P)
- Record-to-Report (R2R)
- Inventory Management
- Master Data Management

### ERP Transactions

- Create Sales Order
- Create Purchase Order
- Goods Receipt
- Customer Invoice
- Vendor Payment

### Functional Support

- ERP terminology
- Approval workflows
- Master Data concepts
- Common ERP errors
- Standard operating procedures
- User guidance

---

## Project Structure

```
ERP-Navigator-GPT/
│
├── assets/
│
├── demo/
│   └── Loom_Script.md
│
├── docs/
│   ├── Assignment_Report.md
│   ├── Evaluation_Report.md
│   ├── Testing_Report.md
│   └── User_Guide.md
│
├── knowledge/
│   ├── ERP_Process_Guide.md
│   ├── SOP.md
│   ├── Transaction_Manual.md
│   ├── Error_Resolution_Guide.md
│   └── ERP_FAQ.md
│
├── prompts/
│   └── System_Prompt.md
│
├── testing/
│   ├── Screenshots/
│   └── Test_Cases.md
│
├── README.md
├── LICENSE
└── .gitignore
```

---

## Knowledge Base

The Custom GPT uses the following internal knowledge documents:

| Document | Purpose |
|----------|----------|
| ERP_Process_Guide.md | Explains ERP business processes |
| SOP.md | Standard Operating Procedures |
| Transaction_Manual.md | Step-by-step ERP transaction guidance |
| Error_Resolution_Guide.md | Common ERP issues and resolutions |
| ERP_FAQ.md | Frequently asked ERP questions |

---

## System Prompt Design

The assistant is guided by a structured system prompt that defines:

- Assistant identity
- Scope of support
- Conversation flow
- Clarifying questions
- Response structure
- ERP guardrails
- Escalation policy
- Refusal policy
- Safety constraints

---

## Conversation Flow

The assistant follows a structured workflow:

1. Identify the ERP module.
2. Understand the user's role.
3. Gather transaction or error context.
4. Provide documented guidance.
5. Recommend next steps or escalation if required.

---

## Safety & Guardrails

ERP Navigator is designed with strict operational boundaries.

The assistant **does not**:

- Access live ERP systems
- Execute ERP transactions
- Modify ERP configurations
- Change approval workflows
- Grant user permissions
- Retrieve organizational data
- Guess undocumented information

When documentation is unavailable, the assistant clearly states that the requested information is outside the available knowledge base.

---

## Functional Testing

The Custom GPT was validated using real functional test cases.

| Test Case | Status |
|-----------|--------|
| Explain Order-to-Cash | ✅ PASS |
| Create Purchase Order | ✅ PASS |
| Resolve Posting Period Closed | ✅ PASS |
| Clarifying Questions | ✅ PASS |
| Live ERP Transaction Request | ✅ PASS |
| Configuration Change Request | ✅ PASS |
| Out-of-Scope Question | ✅ PASS |
| Permission Denied Error | ✅ PASS |
| Unsupported ERP Configuration | ✅ PASS |
| Explain Master Data | ✅ PASS |

Overall Result:

**10 / 10 Test Cases Passed**

---

## Sample Questions

- Explain the Order-to-Cash process.
- How do I create a Purchase Order?
- What is Master Data?
- I'm getting a Posting Period Closed error.
- What should I do if I receive a Permission Denied error?
- What information do you need before troubleshooting an ERP issue?

---

## Technologies Used

- ChatGPT Custom GPT
- GPT-5.5
- Markdown
- Visual Studio Code
- PowerShell
- Git
- GitHub

---

## Limitations

ERP Navigator intentionally does not:

- Connect to live ERP environments
- Execute transactions
- Modify ERP configurations
- Provide undocumented ERP procedures
- Replace ERP administrators or functional consultants

Its responses are limited to the uploaded ERP documentation.

---

## Future Improvements

Potential enhancements include:

- Module-specific knowledge packs (SAP, Oracle, Dynamics 365, Odoo, Acumatica)
- Expanded ERP transaction library
- Interactive troubleshooting flows
- ERP workflow diagrams
- Role-based response customization
- Multilingual ERP support
- Integration with approved internal knowledge repositories

---

## Author

**Razak Shaik**

B.Tech – Computer Science & Engineering (Artificial Intelligence & Machine Learning)

---

## License

This project is provided for educational and demonstration purposes.
