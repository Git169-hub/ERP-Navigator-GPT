# ERP Navigator

<p align="center">

<img src="assets/banner.png" alt="ERP Navigator Banner" width="100%">

</p>

<h1 align="center">ERP Navigator</h1>

<p align="center">
<b>AI-Powered ERP Functional Support Assistant</b><br>
Built using <b>ChatGPT Custom GPT</b>
</p>

<p align="center">

![Custom GPT](https://img.shields.io/badge/Custom-GPT-10A37F?style=for-the-badge)
![GPT-5.5](https://img.shields.io/badge/GPT-5.5-blue?style=for-the-badge)
![ERP](https://img.shields.io/badge/ERP-Functional%20Support-orange?style=for-the-badge)
![Knowledge Base](https://img.shields.io/badge/Knowledge-Documentation%20Driven-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

</p>

---

# 📖 Project Overview

ERP Navigator is a documentation-driven **ERP Functional Support Assistant** built using **ChatGPT Custom GPT**.

The assistant helps business users understand ERP business processes, transaction workflows, Standard Operating Procedures (SOPs), ERP terminology, and common functional issues using uploaded ERP documentation.

Unlike traditional chatbots, ERP Navigator is designed with **strict operational guardrails**. It does **not** access live ERP systems, execute transactions, modify configurations, or retrieve organizational data.

Its primary goal is to provide reliable, structured, and documentation-based ERP functional guidance.

---

# 🎯 Project Highlights

- 🤖 Built using ChatGPT Custom GPT
- 📚 Documentation-driven knowledge base
- 🧠 Professional system prompt engineering
- 📋 ERP business process guidance
- 🔄 Transaction walkthroughs
- 🛠 Functional error resolution
- ❓ Clarifying question workflow
- 🛡 Strong safety guardrails
- 📈 Functional testing (10/10 Passed)
- 📖 Comprehensive project documentation

---

# 📑 Table of Contents

- [Project Overview](#-project-overview)
- [Project Highlights](#-project-highlights)
- [Key Features](#-key-features)
- [Architecture](#-architecture)
- [Project Structure](#-project-structure)
- [Knowledge Base](#-knowledge-base)
- [System Prompt Design](#-system-prompt-design)
- [Conversation Flow](#-conversation-flow)
- [Screenshots](#-screenshots)
- [Functional Testing](#-functional-testing)
- [Example Questions](#-example-questions)
- [Safety & Guardrails](#-safety--guardrails)
- [Technologies Used](#-technologies-used)
- [Skills Demonstrated](#-skills-demonstrated)
- [Documentation](#-documentation)
- [Future Improvements](#-future-improvements)
- [Author](#-author)
- [License](#-license)

---

# ✨ Key Features

ERP Navigator provides structured ERP functional support through documentation-driven responses.

### Business Process Guidance

- Order-to-Cash (O2C)
- Procure-to-Pay (P2P)
- Record-to-Report (R2R)
- Inventory Management
- Master Data Management

### Transaction Assistance

- Create Sales Order
- Create Purchase Order
- Goods Receipt
- Customer Invoice
- Vendor Payment

### Functional Support

- ERP terminology
- Standard Operating Procedures (SOPs)
- Functional troubleshooting
- Error resolution
- User guidance
- Escalation recommendations

### AI Capabilities

- Documentation-based responses
- Clarifying questions
- Structured response format
- Context-aware guidance
- Scope limitation
- Safety guardrails
- Refusal of unsupported requests

---

# 🏗️ Architecture

ERP Navigator follows a **documentation-driven architecture**. Every user request is processed through a structured system prompt, validated against uploaded ERP documentation, and filtered through safety guardrails before generating a response.

<p align="center">
<img src="assets/architecture.png" alt="Architecture Diagram" width="900">
</p>

## Architecture Flow

```text
User
   │
   ▼
ChatGPT Custom GPT
   │
   ├── System Prompt
   ├── Knowledge Base
   ├── Safety Guardrails
   │
   ▼
Response Generation
   │
   ▼
Structured ERP Functional Guidance
```

### Components

| Component | Purpose |
|-----------|---------|
| **User** | Submits ERP-related questions. |
| **ChatGPT Custom GPT** | Interprets requests and manages conversations. |
| **System Prompt** | Defines assistant behavior, scope, response format, and safety rules. |
| **Knowledge Base** | Supplies ERP documentation used to answer questions. |
| **Safety Guardrails** | Prevents unsupported or unsafe actions. |
| **Response Generator** | Produces structured ERP guidance. |

---

# 📂 Project Structure

```text
ERP-Navigator-GPT/
│
├── assets/
│   ├── banner.png
│   ├── architecture.png
│   ├── order-to-cash.png
│   ├── purchase-order.png
│   ├── posting-period-closed.png
│   ├── permission-denied.png
│   ├── master-data.png
│   └── unsupported-configuration.png
│
├── demo/
│   └── Loom_Script.md
│
├── docs/
│   ├── Architecture.md
│   ├── Architecture_Diagram.md
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
├── CHANGELOG.md
├── CONTRIBUTING.md
├── SECURITY.md
├── README.md
├── LICENSE
└── .gitignore
```

---

# 📚 Knowledge Base

ERP Navigator answers questions **only** from the uploaded ERP documentation.

| Knowledge Document | Description |
|--------------------|-------------|
| **ERP_Process_Guide.md** | Business processes such as Order-to-Cash, Procure-to-Pay, and Record-to-Report. |
| **SOP.md** | Standard Operating Procedures for common ERP activities. |
| **Transaction_Manual.md** | Step-by-step transaction guidance. |
| **Error_Resolution_Guide.md** | Common ERP errors, troubleshooting, and escalation guidance. |
| **ERP_FAQ.md** | Frequently asked ERP concepts and definitions. |

### Knowledge Philosophy

ERP Navigator is intentionally **documentation-driven**.

If information is **not available** in the uploaded documentation, the assistant:

- Clearly states that the information is unavailable.
- Does not fabricate ERP procedures.
- Does not invent configuration details.
- Recommends consulting an ERP Administrator or Functional Consultant when appropriate.

---

# 🧠 System Prompt Design

The Custom GPT is controlled by a structured system prompt that defines:

- Assistant identity
- Supported scope
- Response format
- Clarifying question strategy
- Refusal policy
- Escalation policy
- Safety guardrails
- Documentation boundaries

The prompt ensures that every response remains consistent, professional, and aligned with the uploaded ERP documentation.

---

# 🔄 Conversation Flow

ERP Navigator follows a structured workflow for every request.

```text
Receive User Question
        │
        ▼
Identify ERP Module
        │
        ▼
Determine User Role
        │
        ▼
Ask Clarifying Questions (if needed)
        │
        ▼
Search Uploaded Documentation
        │
        ▼
Generate Structured Guidance
        │
        ▼
Recommend Next Steps or Escalation
```

### Response Structure

Each response is organized into the following sections whenever applicable:

- **Summary**
- **Guidance**
- **Common Issues**
- **Recommended Next Step**
- **Important Notice**

This structure helps users quickly understand both the immediate answer and the recommended course of action.

---

# 📸 Screenshots

The following screenshots demonstrate ERP Navigator responding to real functional support scenarios.

---

## Explain Order-to-Cash Process

<p align="center">
<img src="assets/order-to-cash.png" width="900" alt="Order-to-Cash">
</p>

ERP Navigator explains the complete Order-to-Cash (O2C) process with structured guidance, process steps, common issues, and recommendations.

---

## Purchase Order Guidance

<p align="center">
<img src="assets/purchase-order.png" width="900" alt="Purchase Order">
</p>

Provides step-by-step instructions for creating a Purchase Order while highlighting prerequisites and common mistakes.

---

## Posting Period Closed Error

<p align="center">
<img src="assets/posting-period-closed.png" width="900" alt="Posting Period Closed">
</p>

Explains the cause of the error, recommended resolution, and when escalation to the Finance team is appropriate.

---

## Permission Denied

<p align="center">
<img src="assets/permission-denied.png" width="900" alt="Permission Denied">
</p>

Recommends verifying user roles and contacting the ERP Administrator when authorization changes are required.

---

## Unsupported ERP Configuration

<p align="center">
<img src="assets/unsupported-configuration.png" width="900" alt="Unsupported Configuration">
</p>

Demonstrates how ERP Navigator refuses to invent undocumented configuration procedures and remains within the uploaded knowledge base.

---

## Master Data

<p align="center">
<img src="assets/master-data.png" width="900" alt="Master Data">
</p>

Provides a documentation-based explanation of ERP Master Data and its role in business processes.

---

# 🧪 Functional Testing

ERP Navigator was validated using real user scenarios to verify functional behavior, safety guardrails, and documentation adherence.

| Test Case | Objective | Status |
|-----------|-----------|:------:|
| TC-01 | Explain Order-to-Cash | ✅ PASS |
| TC-02 | Create Purchase Order | ✅ PASS |
| TC-03 | Resolve Posting Period Closed Error | ✅ PASS |
| TC-04 | Ask Clarifying Questions | ✅ PASS |
| TC-05 | Refuse Live ERP Transaction | ✅ PASS |
| TC-06 | Refuse Configuration Changes | ✅ PASS |
| TC-07 | Reject Out-of-Scope Question | ✅ PASS |
| TC-08 | Resolve Permission Denied | ✅ PASS |
| TC-09 | Handle Unsupported ERP Configuration | ✅ PASS |
| TC-10 | Explain Master Data | ✅ PASS |

---

## 📊 Testing Summary

| Metric | Result |
|--------|:------:|
| Total Test Cases | 10 |
| Passed | 10 |
| Failed | 0 |
| Success Rate | **100%** |

---

# 💬 Example Questions

ERP Navigator supports questions such as:

### Business Processes

- Explain the Order-to-Cash process.
- Explain the Procure-to-Pay process.
- Explain the Record-to-Report process.

### ERP Transactions

- How do I create a Purchase Order?
- How do I create a Sales Order?
- How do I post a Goods Receipt?
- How do I create a Customer Invoice?

### Functional Support

- What is Master Data?
- What is Transaction Data?
- What is an SOP?
- Why is my Purchase Order pending approval?

### Error Resolution

- I'm getting a Posting Period Closed error.
- I received a Permission Denied error.
- Why can't I create a Vendor Payment?
- What should I do if my transaction failed?

---

# 🛡️ Safety & Guardrails

ERP Navigator is intentionally designed with strict operational boundaries.

## The assistant **CAN**

- Explain ERP business processes
- Guide ERP transactions
- Explain SOPs
- Interpret common ERP errors
- Recommend next steps
- Ask clarifying questions
- Recommend escalation

---

## The assistant **CANNOT**

- Access live ERP systems
- Execute ERP transactions
- Modify ERP configurations
- Approve Purchase Orders
- Change approval workflows
- Grant permissions
- Retrieve organizational ERP data
- Invent undocumented ERP functionality

---

## Escalation Policy

ERP Navigator recommends contacting an ERP Administrator or Functional Consultant when requests involve:

- User permissions
- Security roles
- Configuration changes
- Database modifications
- Integration issues
- Production incidents
- Unknown system errors

---

## Documentation Boundary

ERP Navigator answers questions **only** from the uploaded ERP documentation.

If information is unavailable, the assistant clearly communicates that the requested guidance is outside the available knowledge base rather than generating unsupported answers.

---

# ⚙️ Technologies Used

The project was developed using the following technologies and tools.

| Category | Technologies |
|----------|--------------|
| AI Platform | ChatGPT Custom GPT |
| Language | Markdown |
| Model | GPT-5.5 |
| Development | Visual Studio Code |
| Terminal | PowerShell |
| Version Control | Git |
| Repository Hosting | GitHub |

---

# 💼 Skills Demonstrated

This project demonstrates practical experience in the following areas:

### Artificial Intelligence

- Prompt Engineering
- Custom GPT Development
- Knowledge-Based AI Assistants
- Documentation-Driven AI
- AI Safety & Guardrails

### ERP Functional Support

- ERP Business Processes
- Standard Operating Procedures (SOPs)
- ERP Functional Analysis
- Transaction Guidance
- Error Resolution
- Escalation Planning

### Software Engineering

- Technical Documentation
- Functional Testing
- Project Structuring
- Git & GitHub
- Markdown Documentation

---

# 📂 Documentation

The repository contains comprehensive documentation for development, testing, evaluation, and user guidance.

| Document | Purpose |
|----------|---------|
| `README.md` | Project overview |
| `docs/Architecture.md` | System architecture |
| `docs/Architecture_Diagram.md` | Architecture flow |
| `docs/User_Guide.md` | End-user instructions |
| `docs/Testing_Report.md` | Functional testing summary |
| `docs/Evaluation_Report.md` | Project evaluation |
| `docs/Assignment_Report.md` | Assignment documentation |
| `testing/Test_Cases.md` | Executed test cases |
| `prompts/System_Prompt.md` | GPT system instructions |

---

# 🚀 Future Roadmap

Potential enhancements for ERP Navigator include:

### ERP Platforms

- SAP S/4HANA
- Oracle ERP Cloud
- Microsoft Dynamics 365
- Odoo ERP
- Acumatica ERP

### AI Improvements

- Retrieval-Augmented Generation (RAG)
- Role-based responses
- Context-aware conversations
- Multi-document retrieval
- Better clarification strategies

### User Experience

- Interactive troubleshooting
- ERP workflow diagrams
- Multi-language support
- Organization-specific documentation packs
- Voice-enabled assistance

---

# 📈 Project Status

| Item | Status |
|------|:------:|
| Knowledge Base | ✅ Complete |
| System Prompt | ✅ Complete |
| Custom GPT | ✅ Complete |
| Functional Testing | ✅ Complete |
| Documentation | ✅ Complete |
| GitHub Repository | ✅ Complete |
| Portfolio Ready | ✅ Yes |

---

# 🤝 Contributing

This repository was created as an educational and portfolio project.

Suggestions, improvements, and constructive feedback are welcome.

If you would like to contribute:

1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Open a Pull Request.

---

# 🙏 Acknowledgements

Special thanks to:

- OpenAI for the ChatGPT Custom GPT platform.
- ERP learning resources that inspired the functional documentation used in this educational project.
- The AI engineering community for sharing prompt engineering and documentation best practices.

---

# 👨‍💻 Author

**Razak Shaik**

**B.Tech – Computer Science & Engineering**  
**Specialization:** Artificial Intelligence & Machine Learning

### Connect with Me

- GitHub: https://github.com/Git169-hub

---

# 📄 License

This project is licensed under the **MIT License**.

See the `LICENSE` file for additional details.

---

# ⭐ Repository Highlights

✔ Documentation-Driven AI Assistant

✔ ERP Functional Support

✔ Prompt Engineering

✔ Custom GPT Development

✔ Functional Testing (10/10 Passed)

✔ Professional Technical Documentation

✔ Portfolio-Ready Project

---

<p align="center">

### ⭐ If you found this project helpful, consider giving it a Star!

**Thank you for visiting ERP Navigator.**

</p>