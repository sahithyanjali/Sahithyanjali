# Enterprise Banking Decision Architecture

A multi-layered AI-powered banking transaction governance system that combines deterministic rules, anomaly detection, compliance screening, and audit-ready decision intelligence to support enterprise-grade fraud prevention and risk management.

## Overview

Enterprise Banking Decision Architecture simulates how modern financial institutions evaluate transactions through multiple governance layers rather than relying on a single AI model. The system integrates rule-based validation, machine learning anomaly detection, AML compliance checks, velocity monitoring, and audit lineage generation to ensure secure and explainable transaction processing.

## Key Features

### Layer 1: Deterministic Rules Engine

* Trusted device verification
* User profile validation
* Structural transaction checks
* Instant rule-based decision making

### Layer 2: Machine Learning Anomaly Detection

* Historical transaction behavior analysis
* Transaction deviation scoring
* Adaptive risk thresholding
* High-value transaction monitoring

### Layer 3: AML Compliance Engine

* Anti-Money Laundering screening
* Suspicious keyword detection
* Compliance policy enforcement
* Automated regulatory flagging

### Velocity Monitoring

* Sliding window transaction analysis
* Rapid transaction detection
* Transaction throttling controls
* Fraud pattern prevention

### Adaptive Risk Assessment

* VIP customer threshold management
* High-risk transaction hour monitoring
* New-user risk controls
* Dynamic anomaly sensitivity adjustment

### Governance & Audit Framework

* Complete audit lineage generation
* Decision traceability
* Compliance-ready manifests
* Human review escalation workflows

## Architecture

```text
Transaction Input
        │
        ▼
┌─────────────────────┐
│ Velocity Filter     │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│ Layer 1: Rules      │
│ Device Validation   │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│ Layer 2: ML Engine  │
│ Anomaly Detection   │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│ Layer 3: AML Engine │
│ Compliance Checks   │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│ Consensus Matrix    │
│ Final Decision      │
└──────────┬──────────┘
           │
           ▼
 Governance Manifest
```

## Technology Stack

### Programming Language

* Python

### Core Libraries

* json
* time
* collections
* datetime

### AI & Risk Intelligence

* Rule-Based Decision Systems
* Behavioral Anomaly Detection
* AML Compliance Screening
* Transaction Governance Logic

## Decision Outcomes

| Decision                            | Description                        |
| ----------------------------------- | ---------------------------------- |
| COMPLETED_SUCCESSFULLY              | Transaction approved               |
| SUSPENDED_STEP_UP_AUTH_REQUIRED     | Additional authentication required |
| REJECTED_AND_ROUTED_TO_HUMAN_REVIEW | Escalated for manual investigation |

## Sample Risk Controls

### Trusted Device Validation

* Validates device against historical user profile.
* Flags unknown devices for review.

### Transaction Anomaly Detection

* Compares transaction value against historical average.
* Detects abnormal spending behavior.

### AML Compliance Screening

* Scans transaction metadata and memos.
* Identifies sanctioned or suspicious terms.

### Velocity Throttling

* Limits excessive transactions within a short time window.
* Prevents bot-driven fraud attempts.

## Example Governance Output

```json
{
  "transaction_id": "TX-99103",
  "verdict": "REJECTED_AND_ROUTED_TO_HUMAN_REVIEW",
  "audit_lineage": {
    "Layer_1_Rules_Decision": "FAIL",
    "Layer_2_ML_Decision": "FAIL",
    "Layer_3_AML_Decision": "FAIL"
  }
}
```

## Business Impact

* Reduced fraud investigation workload through automated risk scoring.
* Improved transaction governance using layered decision intelligence.
* Enhanced AML compliance and regulatory monitoring.
* Enabled explainable AI decision-making through audit-ready manifests.
* Strengthened enterprise transaction security and operational resilience.

## Learning Objectives

This project demonstrates:

* Enterprise banking decision systems
* Multi-layer risk assessment architecture
* Fraud detection workflows
* AML compliance automation
* Velocity-based transaction monitoring
* Explainable AI governance
* Human-in-the-loop escalation frameworks

## Future Enhancements

* Real-time Kafka transaction streaming
* SnapML fraud prediction models
* Graph-based fraud network analysis
* LLM-powered compliance investigation assistant
* Case management dashboard
* Risk scoring visualization portal

## Author

**P. Sahithyanjali**

Aspiring AI & Machine Learning Engineer

### Program

GenAI Pioneer Summer Training

### Instructor

Uma Desu
