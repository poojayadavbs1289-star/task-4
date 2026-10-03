# ⚠️ Severity & Case Classification — Task 4

> **Internship Task | Pharmacovigilance & Drug Safety**  
> Classify adverse drug reactions based on seriousness and expectedness. Evaluate multiple cases and determine their clinical impact using pharmacovigilance guidelines.

---

## 📋 Table of Contents

- [Objective](#objective)
- [Key Concepts](#key-concepts)
- [Seriousness Classification](#seriousness-classification)
- [Expectedness Classification](#expectedness-classification)
- [Case Studies — Analysis](#case-studies--analysis)
- [Summary of All Cases](#summary-of-all-cases)
- [Classification Framework](#classification-framework)
- [Clinical Impact & Regulatory Significance](#clinical-impact--regulatory-significance)
- [Key Learnings](#key-learnings)

---

## 🎯 Objective

- Classify ADRs based on **seriousness** (Serious vs Non-Serious)
- Classify ADRs based on **expectedness** (Expected vs Unexpected)
- Evaluate **5 real-world case studies** using pharmacovigilance guidelines
- Determine the **clinical impact** of each adverse reaction
- Apply **pharmacovigilance guidelines** to each case

---

## 🔬 Key Concepts

### What is Seriousness?

An ADR is classified as **Serious** if it meets **any one** of the following criteria (ICH E2A Guidelines):

| Seriousness Criterion | Description |
|----------------------|-------------|
| ☠️ **Death** | Results in death of the patient |
| 🏥 **Hospitalization** | Requires or prolongs inpatient hospitalization |
| ♿ **Disability** | Results in persistent or significant disability/incapacity |
| ⚠️ **Life-threatening** | Patient at immediate risk of death |
| 👶 **Congenital anomaly** | Birth defect in offspring |
| 🩺 **Medically important** | Requires medical/surgical intervention to prevent serious outcome |

> If **none** of the above apply → the ADR is **Non-Serious**

---

### What is Expectedness?

| Category | Definition |
|----------|-----------|
| **Expected** | Reaction is consistent with the drug's known safety profile (listed in SmPC/label/SPC) |
| **Unexpected** | Reaction is NOT consistent with known product information — nature, severity, or frequency differs |

> **Why it matters:** Unexpected serious ADRs require **expedited regulatory reporting** (within 7–15 days)

---

## 📊 Seriousness Classification

```
                    ADR Occurs
                       │
          ┌────────────┴────────────┐
          ▼                         ▼
    SERIOUS ADR               NON-SERIOUS ADR
  (meets ≥1 criterion)      (meets no criterion)
          │                         │
  • Death                   • Mild/moderate symptoms
  • Hospitalization          • No life threat
  • Life-threatening         • No hospitalization
  • Disability               • Self-limiting
  • Congenital anomaly       • Manageable
  • Medically important
```

---

## 📋 Expectedness Classification

```
              Is the reaction listed in the
              drug's approved label/SmPC?
                         │
           ┌─────────────┴─────────────┐
           ▼                           ▼
        EXPECTED                  UNEXPECTED
   (Known ADR profile)        (New/unlisted reaction)
           │                           │
   • Routine monitoring         • Expedited reporting
   • Periodic safety reports    • Signal detection
   • Standard management        • Regulatory review
```

---

## 🏥 Case Studies — Analysis

### Case 01 — Amoxicillin

| Field | Details |
|-------|---------|
| **Drug** | Amoxicillin |
| **Adverse Reaction** | Skin rash, Itching |
| **Seriousness** | ✅ **NON-SERIOUS** |
| **Expectedness** | ✅ **EXPECTED** |

**Reasoning:**
- Skin rash is a **well-known side effect** of Amoxicillin (penicillin-class antibiotics)
- Does not meet any serious criteria — no hospitalization, no life-threat, no disability
- Listed in Amoxicillin's product label → **Expected**
- Manageable with antihistamines; drug discontinuation resolves symptoms

**Clinical Impact:** Low — routine monitoring sufficient

---

### Case 02 — Ibuprofen

| Field | Details |
|-------|---------|
| **Drug** | Ibuprofen |
| **Adverse Reaction** | Gastrointestinal bleeding requiring hospitalization |
| **Seriousness** | 🔴 **SERIOUS** |
| **Expectedness** | ✅ **EXPECTED** |

**Reasoning:**
- GI bleeding **required hospitalization** → meets serious criterion
- GI bleeding is a **known risk** of NSAIDs (Non-Steroidal Anti-Inflammatory Drugs)
- Ibuprofen's label warns of GI hemorrhage risk → **Expected**
- Serious but known complication — requires urgent medical management

**Clinical Impact:** High — hospitalization required; potential for significant morbidity

---

### Case 03 — Metformin

| Field | Details |
|-------|---------|
| **Drug** | Metformin |
| **Adverse Reaction** | Lactic acidosis |
| **Seriousness** | 🔴 **SERIOUS** |
| **Expectedness** | ⚠️ **UNEXPECTED** |

**Reasoning:**
- Lactic acidosis is a **life-threatening** condition — meets serious criterion
- Although lactic acidosis is mentioned in Metformin's label, it is **rare and unexpected** in routine use
- Classified as **Unexpected** due to its rarity and severity beyond typical expectations
- Requires **expedited pharmacovigilance reporting**

**Clinical Impact:** Very High — life-threatening; immediate ICU intervention may be required

---

### Case 04 — Atorvastatin

| Field | Details |
|-------|---------|
| **Drug** | Atorvastatin |
| **Adverse Reaction** | Elevated liver enzymes (mild) |
| **Seriousness** | ✅ **NON-SERIOUS** |
| **Expectedness** | ✅ **EXPECTED** |

**Reasoning:**
- Mildly elevated liver enzymes do **not meet serious criteria** (no hospitalization, no liver failure)
- Hepatotoxicity (liver enzyme elevation) is a **known, listed effect** of statins
- Routine liver function monitoring is recommended during statin therapy → **Expected**
- Managed by dose adjustment or drug discontinuation if values rise further

**Clinical Impact:** Low-Moderate — requires liver function monitoring; usually self-limiting

---

### Case 05 — Levofloxacin

| Field | Details |
|-------|---------|
| **Drug** | Levofloxacin |
| **Adverse Reaction** | Tendon rupture |
| **Seriousness** | 🔴 **SERIOUS** |
| **Expectedness** | ✅ **EXPECTED** |

**Reasoning:**
- Tendon rupture causes **significant disability** → meets serious criterion
- Fluoroquinolone-associated tendinopathy and tendon rupture is a **Black Box Warning** in many countries
- Listed prominently in Levofloxacin's label → **Expected**
- Particularly risky in elderly patients and those on corticosteroids

**Clinical Impact:** High — permanent disability possible; surgical intervention may be needed

---

## 📊 Summary of All Cases

| Case | Drug | Adverse Reaction | Seriousness | Expectedness |
|------|------|-----------------|-------------|--------------|
| 01 | Amoxicillin | Skin rash, Itching | ✅ NON-SERIOUS | ✅ EXPECTED |
| 02 | Ibuprofen | GI bleeding (hospitalization) | 🔴 SERIOUS | ✅ EXPECTED |
| 03 | Metformin | Lactic acidosis | 🔴 SERIOUS | ⚠️ UNEXPECTED |
| 04 | Atorvastatin | Elevated liver enzymes (mild) | ✅ NON-SERIOUS | ✅ EXPECTED |
| 05 | Levofloxacin | Tendon rupture | 🔴 SERIOUS | ✅ EXPECTED |

### Summary Count (as shown in task):

| Category | Count |
|----------|-------|
| 🔴 **Serious** | **3** (Cases 02, 03, 05) |
| ✅ **Non-Serious** | **2** (Cases 01, 04) |
| ⚠️ **Unexpected** | **1** (Case 03 — Metformin) |
| ✅ **Expected** | **4** (Cases 01, 02, 04, 05) |

---

## 🗂️ Classification Framework

### 2×2 Classification Matrix

```
                    EXPECTEDNESS
                 Expected  │  Unexpected
               ────────────┼────────────
      Serious  │  Case 02  │   Case 03  │
S             │  Case 05  │            │
E             ├────────────┼────────────┤
R  Non-Serious │  Case 01  │     —      │
I             │  Case 04  │            │
O             └────────────┴────────────┘
U
S
N
E
S
S
```

### Reporting Priority

| Classification | Reporting Requirement |
|---------------|----------------------|
| Serious + Unexpected | 🚨 **Expedited — 7 days** (fatal/life-threatening) |
| Serious + Unexpected | ⚡ **Expedited — 15 days** (non-fatal serious) |
| Serious + Expected | 📋 Periodic Safety Update Reports (PSURs) |
| Non-Serious + Expected | 📊 Routine pharmacovigilance monitoring |
| Non-Serious + Unexpected | 📋 Include in periodic reports; monitor for signals |

---

## 🌍 Clinical Impact & Regulatory Significance

| Case | Drug | Reporting Timeline | Action Required |
|------|------|--------------------|----------------|
| 01 | Amoxicillin | Periodic (90 days) | Routine monitoring |
| 02 | Ibuprofen | 15 days (serious) | Expedited report |
| 03 | Metformin | 15 days (serious + unexpected) | Expedited + signal review |
| 04 | Atorvastatin | Periodic (90 days) | LFT monitoring |
| 05 | Levofloxacin | 15 days (serious) | Expedited report + Black Box review |

### Pharmacovigilance Guidelines Applied

| Guideline | Description | Applied To |
|-----------|-------------|------------|
| **ICH E2A** | Clinical safety data management — definitions of serious | All cases |
| **ICH E2D** | Post-approval safety data management | Cases 02, 03, 05 |
| **WHO-UMC** | Causality and classification standards | All cases |
| **CDSCO PvPI** | India's pharmacovigilance program | All cases |
| **FDA MedWatch** | US serious ADR reporting criteria | Reference standard |

---

## 📚 Key Learnings

- ✅ **Seriousness** is defined by clinical outcomes — not just symptom severity
- ✅ An ADR can be **serious but expected** (e.g., Ibuprofen GI bleeding, Levofloxacin tendon rupture)
- ✅ **Unexpected ADRs** are the most important for signal detection in pharmacovigilance
- ✅ **Metformin lactic acidosis** is the only Unexpected case — requiring expedited reporting
- ✅ **Serious + Unexpected** ADRs trigger the fastest regulatory reporting timelines (7–15 days)
- ✅ Classification guides **clinical management, monitoring, and regulatory reporting**
- ✅ Even **Non-Serious ADRs** must be documented for pattern recognition and signal detection
- ✅ **Black Box Warnings** (like Levofloxacin tendon rupture) are the highest level of drug safety alerts

---

## 👩‍💼 About This Task

| Field | Details |
|-------|---------|
| **Task ID** | task4 |
| **Task Name** | Severity & Case Classification |
| **Platform** | VirtualWorks Internship |
| **Domain** | Pharmacovigilance / Drug Safety |
| **Cases Analyzed** | 5 |
| **Serious Cases** | 3 |
| **Non-Serious Cases** | 2 |
| **Unexpected Cases** | 1 |
| **Status** | ✅ Completed |

---

*This report was prepared as part of an internship task focused on pharmacovigilance case classification using ICH E2A seriousness criteria and expectedness guidelines.*
