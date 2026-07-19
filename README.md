# Third-Party-vendor-Risk-Assessment
# Third-Party Vendor Security Assessment Report

## 1. Executive Summary
Following a thorough third-party risk evaluation of CloudLedger Technologies Ltd and their cloud-based loan platform, OriginateCloud, the engagement has been tiered as a **CRITICAL** inherent risk profile[cite: 3, 4]. Due diligence auditing identified **2 Critical**, **2 High**, and **3 Medium** control deficiencies across their security framework. 

**Recommendation: CONDITIONAL APPROVAL BLOCKED.** Meridian Trust Bank cannot authorize production data onboarding under its current state[cite: 4]. Onboarding is officially blocked until the two Critical findings (F1: Public Admin MFA and F2: Evidenced DR Testing) are fully remediated and re-audited[cite: 4].

---

## 2. Full Scope of Engagement
*   **Target Vendor Asset:** CloudLedger Technologies Ltd | **Platform:** OriginateCloud v1.3[cite: 3, 4]
*   **Data Classifications:** Non-public personal info (NPI), customer banking transactions, and physical passport scans[cite: 4].
*   **Business Impact:** Supports the primary retail mortgage and personal loan origination workflow pipeline[cite: 4].
*   **Evaluation Baseline:** SOC 2 Type II (Security Criteria, period ending March 2025), ISO/IEC 27001:2022 Certification, Redcliff Penetration Test Summary (May 2025), and Corporate Data Processing Agreements (DPA)[cite: 4].

---

## 3. Residual Risk & Appetite Analysis
Meridian Trust Bank’s formal Board-approved Risk Appetite Policy states: *"The bank will not accept any open Critical finding on a vendor supporting a critical or important function."*[cite: 4]

Because Finding **F1** (MFA absence on exposed core consoles) and Finding **F2** (lack of verifiable disaster backup testing) directly affect a critical banking utility, the vendor sits **completely outside our risk appetite profile**[cite: 4]. Merely passing this vendor based on questionnaire checklist ticks introduces severe supply-chain liability[cite: 4].

---

## 4. Binding Remediation Plan (Contractual Conditions)
To align this engagement with corporate compliance bounds, CloudLedger must execute the following remediation roadmap before any live customer records are synchronized[cite: 4]:

### Phase 1: Pre-Sign Off Requirements (Must resolve within 30 days to clear the go-live block)[cite: 3]
1.  **Remediation of F1 (Access Control Security):** CloudLedger must enforce mandatory Multi-Factor Authentication (MFA) across the entire internal administrative console footprint and restrict access permissions exclusively to corporate IP addresses or secure VPN gateways[cite: 4]. Proof of configuration changes and a clean validation scan must be provided to Meridian[cite: 4].
2.  **Remediation of F2 (Resilience Security):** The vendor must coordinate and document a full disaster-recovery and database restoration exercise[cite: 4]. A certified copy of the recovery log detailing RTO/RPO metrics must be submitted to our GRC team for review[cite: 4].

### Phase 2: Post-Contract Sign Off Requirements (Must resolve within 60 days of onboarding)
1.  **Legal Framework Correction (Data Sovereignty):** The draft Data Processing Agreement (DPA) must be updated to explicitly attach the missing Standard Contractual Clauses (SCCs) and include an official, fully documented Transfer Risk Assessment (TRA) covering the offshore support operation[cite: 4].
2.  **Audit Scope Extension (Assurance Hardening):** CloudLedger must issue a formal legal commitment stating that their next scheduled SOC 2 Type II audit period and ISO 27001 surveillance review will expand their assessment boundaries to explicitly include the offshore customer support delivery center[cite: 4].

---

## 5. Reassessment Strategy
This vendor will be subjected to an annual comprehensive audit review[cite: 4]. A continuous monitoring alert will be mapped to track the vendor's domain perimeter via automated open-source intelligence tools[cite: 4]. Any secondary high-severity penetration test flags or missed remediation dates will instantly trigger a full reassessment and escalate the engagement to the Head of Risk[cite: 4].
