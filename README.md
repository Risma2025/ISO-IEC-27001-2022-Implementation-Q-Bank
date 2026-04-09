# ISO-IEC-27001-2022-Implementation-Q-Bank

## 📘 ISO/IEC 27001 Framework
**ISO/IEC 27001** is the leading international standard for information security management systems (ISMS), providing a risk-based framework for organizations to protect the confidentiality, integrity, and availability of data. It helps businesses of any size identify risks, implement tailored security controls—covering people, processes, and technology—and foster a culture of continual improvement. Achieving ISO 27001 certification demonstrates a company’s commitment to security to customers and partners, reducing the likelihood of data breaches and supporting legal compliance. The current version, ISO/IEC 27001:2022, consists of 10 main clauses and a set of 93 controls in Annex A, which must be implemented based on risk assessment.


### ❓ The 5 W's of ISO 27001
* **WHAT is it?** A risk-based framework ensuring the **CIA Triad**:  
    * **Confidentiality:** Authorized access only.  
    * **Integrity:** Data accuracy and protection from tampering.  
    * **Availability:** Systems are reliable and accessible.
      
* **WHY is it needed?** it is a business necessity to:
    * Protect against cyber threats (Ransomware, Phishing).
    * Avoid legal consequences (GDPR, Banking Regulations).
    * Build trust with customers and partners.
      
* WHO uses it?
   * Management (Strategy).
   * Security Teams (Controls).
   * Employees (Best Practices).
     
* **WHEN is it used?** It is a **continuous cycle**, not a one-time project. It requires periodical audits to maintain certification. It follows the PDCA model:
   * Plan: Find your risks (Risk Assessment).
   * Do: Fix the risks (Implement controls).
   * Check: See if the fixes work (Internal Audit).
   * Act: Fix what didn't work and start over.

* **WHERE is it applied?**(The Scope)It is applied across the entire "Information Security Perimeter."
  * Physically: It covers headquarters, branch offices, and data centers.
  * Logically: It covers the cloud, internal networks, and mobile banking platforms.
  * Legally: It covers any location where customer data is processed or stored, ensuring compliance with local and international privacy laws.

---

## 🚀 Why I Built This Case Study
I created the **Q Bank** project to demonstrate how to translate theoretical ISO requirements into practical, high-quality documentation. This repository follows the journey from a "Gap Assessment" to a "Statement of Applicability," simulating a real-world GRC (Governance, Risk, and Compliance) workflow.

---

## 📂 ISMS Documentation Roadmap

### Phase 1: Context & Strategy (Setting the Foundation)
*Defining the "Why" and "What" of the ISMS.*

#### 1. SWOT Analysis
* **Purpose:** To identify internal/external factors affecting the bank's security.
* **Summary:** Analyzes Q Bank's **Strengths** (Infrastructure), **Weaknesses** (Legacy systems), **Opportunities** (Zero Trust), and **Threats** (Ransomware).
* **Key Concept:** Helps prioritize where security is most needed.
> **[View Document: 01_SWOT _Analysis_Q_Bank.pdf](./01_SWOT _Analysis_Q_Bank.pdf)**

#### 2. ISMS Scope Document
* **Purpose:** To draw a "boundary" around what the framework protects.
* **Summary:** Covers all banking operations (Retail, Corporate, ATMs) while excluding non-banking services like outsourced cafeteria maintenance.
* **Key Concept:** Prevents "Scope Creep" and defines auditor boundaries.
> **[View Document: 02_ISMS_Scope _Document-Q_Bank.pdf](./02_ISMS_Scope _Document-Q_Bank.pdf)**

#### 3. Information Security Policy (ISP)
* **Purpose:** The high-level "Law of the Bank" regarding security.
* **Summary:** Establishes management's commitment to the CIA triad and defines roles (CISO, Staff) in protecting assets.
* **Key Concept:** The foundational governance document required for enforcement.
> **[View Document: 03_Information_Security_Policy-Q_Bank.pdf](./03_Information_Security_Policy-Q_Bank.pdf)**

---

### Phase 2: Baseline Assessment (The "As-Is" State)
*Measuring the current security posture before implementation.*

#### 4. Current Practices Report
* **Purpose:** A realistic "snapshot" of existing security habits.
* **Summary:** Records current technical strengths (SIEM, EDR) and administrative weaknesses (informal training, ad-hoc audits).
* **Key Concept:** The "Honesty Phase"—you cannot improve what you haven't measured.
> **[View Document: current_practices_Q-Bank.pdf](./current_practices_Q-Bank.pdf)**

#### 5. ISO 27001 Gap Assessment
* **Purpose:** A formal audit against the 26 mandatory ISO 27001:2022 requirements.
* **Summary:** Revealed Q Bank is **23.1% compliant**, highlighting urgent needs for Internal Audit and Corrective Action (CAPA) processes.
* **Key Concept:** This gap acts as the "To-Do List" for certification.
> **[View Document: 03_Gap_Assessment_Q-Bank.pdf](./03_Gap_Assessment_Q-Bank.pdf)**

---

### Phase 3: Risk Management (The "Plan")
*Prioritizing spending based on threat likelihood and impact.*

#### 6. Risk Assessment & Treatment Plan
* **Purpose:** To identify threats and decide on mitigation strategies.
* **Summary:** Uses a **5x5 Risk Matrix**. Identified "Unauthorized access to Core Banking" as a High-Level risk (20/25), treated with MFA implementation.
* **Key Concept:** ISO 27001 is a **risk-based** standard; you apply controls based on specific threats.
> **[View Document: 05_Risk_Assessment_Q-Bank.pdf](./05_Risk_Assessment_Q-Bank.pdf)**

---

### Phase 4: Compliance Mapping (The "Final Framework")
*The final list of security controls selected for the organization.*

#### 7. Statement of Applicability (SoA)
* **Purpose:** The master checklist for auditors.
* **Summary:** Reviews all **93 Annex A controls**. Includes "Network Security" (A.13.1) and justifies the exclusion of irrelevant controls like A.5.6.
* **Key Concept:** The most requested document by auditors; it is the "Map" of your security infrastructure.
> **[View Document: Statement_of_Applicability_SoA.pdf](./Statement_of_Applicability_SoA.pdf)**

---

*Disclaimer: Q Bank is a fictional entity created for educational and portfolio purposes.*
