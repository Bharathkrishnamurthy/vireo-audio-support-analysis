
# Vireo Audio — Support Ticket Analysis

## AI-Assisted Customer Support Analytics

This project was built as part of the **Vireo Audio Support Tickets — Set B** assignment.

The goal was to turn 18 months of customer support data into a practical view of:

- Customer satisfaction
- Low-CSAT concentration
- Agent-level review priority
- Handle time
- SLA breaches
- Potential financial exposure
- Training priorities
- AI-assisted ticket review

The focus was not just on creating charts, but on connecting the analysis to a real customer-experience decision: **where should Vireo Audio focus its next training effort?**

---

# 1. Business Problem

Vireo Audio's Customer Experience team wanted to understand why customer satisfaction has been declining and identify where training resources should be focused.

The main business questions were:

1. How is overall customer satisfaction performing?
2. Where are low-CSAT responses concentrated?
3. Which Tier 1 agents should be reviewed first?
4. What does handle time look like across teams?
5. How much financial exposure comes from SLA breaches?
6. Which customer-support areas should receive attention during training?
7. Can AI-assisted analysis help review individual support cases?

---

# 2. Dataset

The analysis uses the support-ticket dataset covering:

- **11,750 support tickets**
- **44 agents**
- **18 months of data**
- **January 2025 – June 2026**
- 4 support channels:
  - Chat
  - Email
  - Voice
  - Social

The available data includes ticket information, agent information, customer/order references, CSAT scores, response and resolution timestamps, refund information, transfers, and support notes.

---

# 3. What I Built

The analysis was developed as a reproducible Google Colab notebook.

The workflow covers:

```text
Raw Support Data
       ↓
Data Quality Checks
       ↓
Timestamp Validation
       ↓
CSAT Analysis
       ↓
SLA Analysis
       ↓
Agent-Level Metrics
       ↓
Bottom-10 Review Priority
       ↓
Category Analysis
       ↓
Handle-Time Analysis
       ↓
Business Impact
       ↓
AI-Assisted Ticket Review
       ↓
Validation & Recommendations
