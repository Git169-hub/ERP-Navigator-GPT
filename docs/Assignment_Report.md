# Assignment Report

# ERP Navigator – ERP Functional Support Assistant

---

## Student Information

**Project Title:** ERP Navigator – ERP Functional Support Assistant

**Project Type:** Custom GPT

**Development Environment:**

- Windows 11
- Visual Studio Code
- PowerShell
- ChatGPT Custom GPT
- Git & GitHub

---

# 1. Introduction

Enterprise Resource Planning (ERP) systems are widely used to manage business operations such as sales, procurement, inventory, finance, and reporting. Business users frequently require assistance in understanding ERP processes, transactions, and common system issues.

To reduce dependency on ERP functional consultants for routine guidance, this project introduces **ERP Navigator**, a documentation-driven Custom GPT that provides structured ERP functional support using uploaded knowledge documents.

The assistant operates strictly within predefined boundaries and does not access live ERP systems or perform administrative actions.

---

# 2. Problem Statement

Employees often require quick answers to ERP-related questions, including:

- Understanding business processes
- Performing ERP transactions
- Following Standard Operating Procedures
- Resolving common ERP errors
- Understanding ERP terminology

Without centralized guidance, users depend heavily on functional consultants, resulting in delays and inconsistent support.

---

# 3. Project Objectives

The objectives of this project were to:

- Develop a Custom GPT for ERP functional support.
- Answer questions using uploaded ERP documentation.
- Explain ERP business processes and transaction workflows.
- Guide users through standard operating procedures.
- Resolve common ERP functional issues.
- Ask clarifying questions when necessary.
- Prevent unsupported or unsafe operations.
- Recommend escalation when administrator support is required.

---

# 4. Solution Overview

ERP Navigator is a Custom GPT designed to act as an ERP Functional Support Assistant.

The solution combines:

- ERP knowledge documents
- Structured system instructions
- Conversation flow
- Guardrails
- Functional testing

to provide consistent, reliable, and documentation-based guidance.

---

# 5. Knowledge Base

The assistant uses the following knowledge documents:

| Document | Purpose |
|----------|----------|
| ERP_Process_Guide.md | ERP business processes |
| SOP.md | Standard Operating Procedures |
| Transaction_Manual.md | ERP transaction guidance |
| Error_Resolution_Guide.md | Common ERP errors |
| ERP_FAQ.md | Frequently asked questions |

---

# 6. System Prompt Design

A comprehensive system prompt was developed to define:

- Assistant identity
- Scope of support
- Conversation flow
- Clarifying question strategy
- Response structure
- Safety guardrails
- Refusal policy
- Escalation policy

The assistant was instructed to respond only from the uploaded ERP documentation.

---

# 7. Functional Testing

The Custom GPT was tested using real user scenarios.

| Test Case | Result |
|-----------|--------|
| ERP Process Explanation | PASS |
| Transaction Guidance | PASS |
| Error Resolution | PASS |
| Clarifying Questions | PASS |
| Live ERP Action Refusal | PASS |
| Configuration Change Refusal | PASS |
| Out-of-Scope Request | PASS |
| Permission Guidance | PASS |
| Unsupported ERP Topic | PASS |
| ERP FAQ Response | PASS |

Overall Result:

**10 / 10 Test Cases Passed**

---

# 8. Project Outcomes

The completed solution successfully:

- Provides ERP functional guidance.
- Explains ERP processes clearly.
- Guides ERP transactions step-by-step.
- Uses uploaded documentation consistently.
- Prevents unsupported requests.
- Recommends escalation where appropriate.

---

# 9. Challenges Encountered

During development, several improvements were made:

- Strengthened scope limitation for non-ERP questions.
- Improved refusal handling for unsupported requests.
- Enhanced consistency of guidance notices.
- Refined response formatting for better readability.

These improvements increased the reliability and professionalism of the assistant.

---

# 10. Lessons Learned

This project provided practical experience in:

- Designing Custom GPT instructions
- Creating structured knowledge bases
- Developing effective AI guardrails
- Writing documentation-driven prompts
- Functional testing and validation
- Improving GPT reliability through iterative refinement

---

# 11. Future Enhancements

Potential future improvements include:

- SAP-specific documentation
- Oracle ERP guidance
- Microsoft Dynamics 365 support
- Odoo knowledge packs
- Interactive workflow diagrams
- Organization-specific ERP documentation
- Role-based response customization

---

# 12. Conclusion

ERP Navigator successfully meets the objectives of the assignment by providing reliable ERP functional guidance using uploaded documentation while maintaining clear operational boundaries.

The assistant demonstrates strong documentation adherence, structured responses, effective guardrails, and consistent user guidance.

It is suitable for educational demonstrations and documentation-driven ERP support scenarios.