# AI-Governance-Portfolio
## Automated Loan Underwriting System - Meridian Financial Services

## Executive Summary

The project documents an assessment of an AI governance automated loan underwriting system at Meridian Financial Serivices, a mid-sized financial services company. I served as the **AI Governance Lead** for this fictional high-risk AI governance assessment for the company.

The loan underwriting system uses a third-party AI model, **CrediSure Credit Decision Engine v2.3** to evaluate small business loan applications and produce one of three outcomes:

- Auto-approve
- Auto-deny
- Route to manual review

Since **94% of applications are processed automatically** and the system affects access to credit, I classified the AI system as a **high-risk AI use case** requiring governance review before production deployment.

My final recommendation was:

> ***Proceed with conditions. Meridian should not approve unrestricted production deployment until fairness testing, proxy-bias review, reason code validation, human oversight triggers, appeal procedures, vendor evidence review, monitoring thresholds, and governance committee approval are completed.***

<img width="1375" height="879" alt="Meridian_FRIA" src="https://github.com/user-attachments/assets/1af5b89e-adc1-4b30-8956-407fedceb31b" />


> **Caption:** This screenshot shows the EU AI Act FRIA summary for the Meridian Automated Loan Underwriting System, including stakeholder consultation status, flagged rights, risk score, and conditional approval recommendation.

## VerifyWise Dashboard

<img width="1707" height="986" alt="Meridian_Dashboard" src="https://github.com/user-attachments/assets/ca1670fb-f34e-424e-aa12-42b76a944c89" />

> **Caption:** *Governance dashboard in VerifyWise showing the use case registration, model inventory, vendor management, risk management, policy documentation, and evidence of the Automated Loan Underwriting System.*


## Frameworks Applied

| EU AI Act | NIST AI Risk Management Framework | ISO/IEC 42001 |
|---|---|---|
| High-risk AI classification | Governance roles and responsibilities | AI management system scope |
| Fundamental Rights Impact Assessment | System context and intended use | Organizational roles and responsibilities |
| Human oversight| Risk measurement and testing evidence | AI risk assessment |
| Logging | Risk prioritization and treatment | AI risk treatment |
| Explanation to affected persons | Human-AI oversight | Management review |
| Fundamental Rights Impact Assessment |  | AI system lifecycle management |
| Appeal and contestability|  | Third-party AI risk management |
| Deployment conditions |  | |


This portfolio demonstrates my ability to perform practical AI governance work for a high-risk AI system.

Specifically, this project shows that I can:

- Lead an AI governance review for a high-risk AI use case
- Document an AI system profile and governance intake record
- Identify and assess AI risks related to fairness, explainability, automation, vendor risk, and human oversight
- Apply EU AI Act, NIST AI RMF, and ISO/IEC 42001 concepts in a practical way
- Review third-party AI model and vendor governance concerns
- Design human oversight, exception review, and appeal procedures
- Prepare an executive-ready production readiness recommendation
- Use AI governance tooling to organize evidence, risks, policies, and framework assessments

---

## Central Governance Question

This portfolio answers one central question:

> **Should Meridian Financial Services approve production deployment of a 94% automated AI loan underwriting system?**

My answer:

> ***Not for unrestricted production deployment. The system may proceed only with conditions because the current governance evidence does not fully support safe, fair, explainable, accountable, and well-monitored deployment.***

## Portfolio Artifacts

| Artifact | Purpose | Link |
|---|---|---|
| AI System Profile and Intake Record | Documents system purpose, users, affected groups, data, vendor, and risk classification. | [View Artifact](https://drive.google.com/file/d/11a8ttivAkVdimteX-t7Fk8jBh4huvHH7/view?usp=sharing) |
| AI Risk Register and Mitigation Summary | Documents key AI risks, severity, controls, residual risk, and recommendations. | [View Artifact](https://drive.google.com/file/d/1CmOnYcGEMuFEs1Uzm9q0GGX6cFXS5iLD/view?usp=sharing) |
| Human Oversight and Appeal Procedure | Defines human review triggers, override authority, escalation, and applicant appeal process. | [View Artifact](https://drive.google.com/file/d/1Ms5Wyy6jiEWvakn2CsHHgikQBx0NT_0G/view?usp=sharing) |
| Third-Party Vendor and Model Review | Evaluates CrediSure AI vendor risk, model limitations, and required evidence. | [View Artifact](https://drive.google.com/file/d/14LGwWAouVM3AeCrwa4LMMjJjjEoWWoCf/view?usp=sharing) |
| Production Readiness Decision Memo | Provides final executive recommendation. | [View Artifact](https://drive.google.com/file/d/1mk704SVAuqQbLhSKF8j6coJoYPIe8aVE/view?usp=share_link) |
| Final VerifyWise Portfolio Report | Consolidated portfolio report generated from VerifyWise. | [View Report](https://drive.google.com/file/d/1c0RC_VLJAzkSyvk-VWwSQFIr-b5amaCQ/view?usp=sharing) |

---

## Practical AI governance Skill Proof (Screenshots) 

### 1. Use Case Registration

<img width="906" height="795" alt="Meridian_UseCase" src="https://github.com/user-attachments/assets/0e40ec93-0085-4b68-a07e-cd8fa620a687" />



> **Caption:** This screenshot shows the Meridian Automated Loan Underwriting System registered as a high-risk AI use case in VerifyWise.

**Skill demonstrated:** AI use case intake, risk classification, and governance workflow setup.

---

### 2. Model Inventory

<img width="764" height="741" alt="Meridian_Inventory" src="https://github.com/user-attachments/assets/d764303b-7569-4337-989f-8cac0c365353" />


> **Caption:** *This screenshot shows the CrediSure Credit Decision Engine v2.3 documented in the model inventory.*

**Skill demonstrated:** Model inventory documentation, model limitation tracking, and third-party AI model governance.

---

### 3. Dataset Record

<img width="762" height="899" alt="Meridian_Dataset" src="https://github.com/user-attachments/assets/67a34d7d-7c01-4725-b81c-036b1bdd789e" />


> **Caption:** *This screenshot shows the Small Business Loan Underwriting Dataset documented with data purpose, source, PII status, known bias concerns, and mitigation approach.*

**Skill demonstrated:** Dataset governance, PII awareness, data source documentation, and bias mitigation planning.

---

### 4. AI Risk Register

<img width="1423" height="743" alt="Meridian_RiskManagement" src="https://github.com/user-attachments/assets/b96e99bf-b936-4f91-b46f-6f74628bb4e8" />
 

> **Caption:** *This screenshot shows the six priority AI risks documented for the Meridian Automated Loan Underwriting System.*

**Skill demonstrated:** AI risk identification, risk rating, mitigation planning, residual risk analysis, and approval workflow documentation.

## Key Risks Identified

| Risk | Why It Matters |
|---|---|
| Discriminatory lending outcomes | The system may unfairly approve or deny applicants based on biased data, proxy variables, or historical lending patterns. |
| Proxy bias through credit and business variables | Variables such as geography, business age, industry, credit history, thin credit files, or cash-flow volatility may create unfair outcomes. |
| Weak explainability and incomplete reason codes | Meridian may be unable to explain automated denials, support appeals, or demonstrate compliance during review. |
| Accountability gaps in third-party AI deployment | Meridian remains responsible for deployment even if the vendor controls key model details. |
| Inaccurate automated denials | Qualified applicants may be incorrectly denied credit due to model error, incomplete data, or overly strict thresholds. |
| Lack of meaningful human oversight | Routing only 6% of applications to human review may be insufficient for a high-risk credit decision system. |

---

### 5. Vendor Record

<img width="1422" height="542" alt="Meridian_Vendor" src="https://github.com/user-attachments/assets/2fd77652-c364-46dc-bf11-89083955d70e" />


> **Caption:** *This screenshot shows the CrediSure AI vendor record documenting the third-party provider responsible for the credit decisioning model.*

**Skill demonstrated:** Third-party AI vendor risk management and vendor governance documentation.

---

### 6. Framework Assessments

<img width="1370" height="721" alt="Meriadian_ISO" src="https://github.com/user-attachments/assets/e6626b18-99d2-43ae-86d5-b013d6d538b4" />
<img width="1361" height="972" alt="Meriadian_ISO_1" src="https://github.com/user-attachments/assets/6a45e097-6678-4324-9742-020b20b2e2e1" />
<img width="1361" height="972" alt="Meridian_NISTAI" src="https://github.com/user-attachments/assets/53a6b440-ba9e-42cd-b720-9ccdd0d934ce" />

> **Caption:** *This screenshot shows selected framework assessment progress for NIST AI RMF, ISO/IEC 42001, and EU AI Act governance requirements.*

**Skill demonstrated:** Practical framework application and evidence-based AI governance assessment.

---

### 7. Fundamental Rights Impact Assessment (FRIA) Summary

<img width="1375" height="879" alt="Meridian_FRIA" src="https://github.com/user-attachments/assets/5c5f65dc-82fc-49e7-a319-9f8f7732e408" />

> **Caption:** *This screenshot shows the EU AI Act Fundamental Rights Impact Assessment summary for the Meridian Automated Loan Underwriting System.*

**Skill demonstrated:** Fundamental rights risk assessment, high-risk AI review, human oversight analysis, and conditional deployment recommendation.

---

### 8. Final Report

[Derick_Ampadu_AI_Governance_Portfolio_Report.pdf](https://github.com/user-attachments/files/28240304/Derick_Ampadu_AI_Governance_Portfolio_Report.pdf)


<img width="911" height="788" alt="Meridian_PortfolioReport" src="https://github.com/user-attachments/assets/6fa6ef89-1763-4ba5-85de-80e27e967c4d" />


> **Caption:** *This screenshot shows the final VerifyWise portfolio report generated for the Meridian Automated Loan Underwriting System.*

**Skill demonstrated:** Governance evidence organization and final reporting.


## Final Recommendation

My final recommendation is:

> **Proceed with conditions.**

Meridian should not approve unrestricted production deployment at this time.

The system may move forward only if the following conditions are completed:

- Complete fairness testing and disparate impact analysis
- Complete proxy-bias review
- Validate denial reason codes
- Define mandatory human review triggers
- Establish appeal and reconsideration procedures
- Complete vendor documentation review
- Complete security and privacy review
- Define model and outcome monitoring thresholds
- Implement decision-level audit logging
- Establish incident escalation procedures
- Obtain governance committee approval

---

## Portfolio Conclusion

This project demonstrates my ability to evaluate a high-risk AI system from an AI governance, risk, and compliance perspective.

The Meridian Automated Loan Underwriting System offers business benefits, including faster decisions, improved consistency, and operational efficiency. However, because it affects access to credit and automates most decisions, it requires strong governance before deployment.

As AI Governance Lead, my assessment found that the system should not receive unrestricted production approval until Meridian completes required fairness, explainability, human oversight, vendor, monitoring, privacy, and governance controls.

This project reflects how I would support responsible AI deployment in a real organization.

---

## Disclaimer

*This is a fictional educational portfolio project created for AI governance, risk, and compliance training. It does not represent legal advice, regulatory certification, credit decisioning advice, or an actual assessment of a real financial institution.*

