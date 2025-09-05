# Social & Companion Robotics for Ageing and Disability in Australia (2025–2028)
**A sceptical, evidence-led backgrounder for founders, providers and policymakers**  
**Date:** 5 September 2025

## Executive summary (1 page)

Social and companion robotics for older adults and people with disability has been studied for more than a decade. The most credible evidence shows **short-term benefits** on engagement, agitation, anxiety and mood in some settings, but **durability of effects, dose–response, and cost-effectiveness remain mixed or uncertain**. Australian providers face workforce pressure and digital maturity constraints, and funders (Aged Care, NDIS) increasingly demand **value for money**, **privacy**, and **interoperability**—not gadgets. The real opportunity is **agentic, embodiment-agnostic AI** that orchestrates data across the home and care ecosystem, with a **sovereign, standards-compliant** footprint. Competing head-on with Big Tech on generic “home AI” is a losing play; a viable wedge is **trusted clinical-adjacent workflows, AU-specific integration (FHIR/My Health Record), and rigorous evidence of measurable outcomes**.

**Top five findings**
1. **Efficacy is situational and mostly short-term.**
2. **Implementation beats invention.**
3. **Regulation/privacy/interoperability are now decisive.**
4. **Procurement is conservative.**
5. **Hardware-led robots are a commercial risk without an orchestration platform.**

**Top five risks**
- Evidence fails to replicate at scale; effects fade beyond novelty windows.  
- Device maintenance and infection control issues in residential settings.  
- Privacy/security non-compliance (APPs, Essential Eight) blocks adoption.  
- Interoperability debt (no FHIR/MyHR integration) undermines value.  
- Vendor viability (e.g., Big Tech service changes like Alexa Together withdrawal) destabilises care workflows.  

**Decision snapshot (traffic-light)**  
- **Go** if: agentic platform + AU-grade privacy/security + FHIR/MyHR integration + outcomes-linked pilot with credible endpoints.  
- **Caution** if: robot-only proposition, weak integration, thin evidence, or reliance on generic “companionship”.  
- **No-go** if: product is a “nice demo” without a path to reduced cost or improved quality metrics in a real service model.  

---

## Table of contents
1. Context: Ageing, disability & the longevity economy (AU)  
2. Evidence review: What social/companion robots actually do  
3. Regulatory, privacy & interoperability (AU)  
4. Market & competitive landscape  
5. Funding & procurement pathways (Aged Care, NDIS)  
6. Two strategic options for a founder with existing hardware  
7. Economic case & impact modelling  
8. Implementation frameworks & trial design  
9. Go/No-Go decision tree & 90-day plan  
10. Conclusion  
Appendices: Annotated bibliography; Standards checklist; Pilot artefacts; Interview guides; Glossary

---

## 1) Context: Ageing, disability & the longevity economy (AU)

Australia’s aged-care demand is growing rapidly, with strong shifts toward **home-based support** and a persistent workforce shortfall. In 2021–22, ~800,000 people aged 65+ used home support; home care users rose to ~213,000 by June 2022 (triple since 2017). Residential care remains significant, especially for the oldest cohorts. These system pressures create a receptive audience for technologies that **reduce carer burden** and **improve resident/client experience**—but solutions must fit real-world operations and budgets.

The **Royal Commission** catalysed reform, with strengthened Quality Standards and a new Aged Care Act rolling out; providers are now under tighter scrutiny to evidence safety, dignity and effectiveness, making procurement more evidence-driven.

---

## 2) Evidence review: Social/companion robotics—what we actually know

### Outcomes and effect sizes
- Systematic reviews/meta-analyses indicate **benefits for agitation, anxiety, depression, positive affect, and social participation** among people living with dementia in long-term care; however, **follow-up durability is limited**, and heterogeneity is high.  
- Randomised/cluster-randomised trials (e.g., PARO) show **improvements in BPSD** and sometimes reduced psychotropic use, but replication is uneven.  
- Emerging work on **ElliQ** and other conversational/social robots suggests promise on loneliness, though much is early-stage and US-centred.

### Implementation realities
Common barriers: staff training time; device cleaning/infection control; maintenance/repair logistics; network reliability; resident acceptance; and ethical concerns (deception, dignity, cultural safety, consent).

### What the evidence does **not** show
- That “companionship” robots reliably **reduce total cost of care** at scale.  
- That effects persist without ongoing facilitation (“dose”).  
- That generic, non-integrated robots can substitute for clinical workflows.

### Grey literature pulse (AU)
- **ARIIA** emphasises fit-for-purpose selection, testing and organisational readiness.  
- **HammondCare** positions robots as **adjuncts**, not stand-alone fixes.

---

## 3) Regulatory, privacy & interoperability (AU)

### When is a robot (or its software) a medical device?
If your solution **meets the definition of a medical device**, including **Software as a Medical Device (SaMD)**, it must comply with TGA classification rules and ARTG inclusion.

### Safety and standards
**ISO 13482** specifies safety requirements for personal care robots; aligning to it is prudent.

### Privacy and security baselines
Australian Privacy Principles (APPs) govern collection, use, disclosure. Cyber posture should align with **ASD Essential Eight** maturity.

### Interoperability expectations
Interfacing with **My Health Record** via the **ADHA FHIR Gateway** is becoming expected for credible digital health tools.

---

## 4) Market & competitive landscape

**Personas and Jobs-to-Be-Done**  
- **Resident/client & family:** safety, calm, connection.  
- **Care workers:** reduced agitation burden, meaningful activities.  
- **Facility managers/CIOs:** predictable TCO, compliance, minimal upkeep.  
- **Funders/planners:** value for money vs cheaper comparators.

**Competitors and substitutes**  
- **Social robots:** PARO, Pepper/NAO/QTrobot/Lovot, ElliQ.  
- **Ambient platforms:** Google/Amazon/Apple ecosystems.  
- **Telecare/sensors:** Tunstall, Care@Home, Telstra Health.

**Porter’s five forces:** High threat of substitutes; moderate buyer power; high rivalry; barriers to entry rising.

---

## 5) Funding & procurement pathways (AU)

- **Aged care:** Providers buy on TCO, safety, and alignment with Quality Standards.  
- **NDIS:** Uses low/mid/high cost AT bands with escalating evidence requirements.  
- **NDIS Evidence Advisory Committee (EAC):** Raises evidentiary bar for novel tech.

---

## 6) Two strategic options for a founder with existing hardware

### Option A — Hardware-led social robot (manufactured in Shenzhen)
Differentiate on: infection-control-aware design, on-device ASR/NLU, ISO 13482, repair/logistics, sovereign data flows.  
**Risk:** commoditisation vs smart displays; procurement friction.

### Option B — Agentic AI platform (embodiment-agnostic)
Provide an **orchestration layer** across in-home sensors, wearables, care CRMs/EMRs, and environment data; expose **FHIR-based adapters** and **privacy-preserving edge features**.  
**Risk:** integration lift; competing with platforms; evidence burden.

---

## 7) Economic case & impact modelling

- **Costs:** device amortisation, cleaning, training, replacements, integration.  
- **Offsets:** reduced BPSD incidents, fewer medications, improved staff retention.  
- **Sensitivity:** adherence, facilitation time, device failure rates.  
Evidence supports **case-by-case ROI**, not universal savings.

---

## 8) Implementation frameworks & trial design

Apply **NASSS**, **CFIR**, **RE-AIM**, and **MRC 2021**.  

**Pilot blueprint example:**  
- **Setting:** 3 dementia units + 1 home-care service.  
- **Population:** 120 residents/clients with moderate BPSD.  
- **Arms:** Robot endpoint vs tablet vs usual activities.  
- **Endpoints:** Agitation, staff facilitation time, psychotropic use, QoL, burnout.  
- **Governance:** Privacy impact assessment, Essential Eight security, TGA advice.

---

## 9) Go/No-Go decision tree

- **Gate 1 — Compliance & safety:** ISO 13482, APPs, Essential Eight, TGA.  
- **Gate 2 — Interoperability:** FHIR/MyHR adapter, CRM integration.  
- **Gate 3 — Outcomes & TCO:** Pilot must show meaningful reduction in agitation or staff time.  
- **Gate 4 — Procurement readiness:** Artefacts for BuyICT/NDIS evidence.

---

## 10) 90-day action plan

1. Regulatory & privacy position.  
2. Interoperability proof (FHIR/MyHR demo).  
3. Pilot MoUs with residential & home-care sites.  
4. Comparator parity (tablet/smart display endpoints).  
5. Ethics/acceptance safeguards.

---

## Appendices

### A) Annotated bibliography (selected)
- **Systematic reviews/meta-analyses:** QoL/BPSD improvements, limited durability.  
- **Trials:** Mixed results, context-dependent.  
- **Grey literature:** ARIIA, HammondCare.  
- **Regulatory/privacy:** TGA, APPs, Essential Eight, ADHA FHIR.

### B) Standards checklist
- **Safety:** ISO 13482.  
- **Privacy:** APPs, DPIA.  
- **Security:** Essential Eight.  
- **Interop:** FHIR/MyHR.  
- **Regulatory:** TGA.

### C) Pilot artefacts
- Consent forms, culturally safe language.  
- Data governance plan.  
- Security plan.

### D) Interview guides
- **Care workers:** agitation peaks, facilitation time.  
- **Managers:** procurement artefacts, maintenance burden.  
- **Families:** supportive vs intrusive, data use.

### E) Glossary
- **BPSD:** Behaviours and psychological symptoms of dementia.  
- **CFIR, NASSS, RE-AIM, MRC:** Implementation/evaluation frameworks.

---

