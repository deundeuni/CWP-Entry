> **Bilingual Disclosure Notice:** This is a bilingual disclosure - same content in KR/EN, v3.4 2026-09-13 (Korean version: [README.ko.md](README.ko.md))  
> **Original Authority Notice:** This English version was drafted and translated with the assistance of AI tools, so phrasing and expressions may not be perfectly smooth or fully precise. The authoritative original for all legal, technical, and engineering interpretations belongs exclusively to the Korean document (`README.ko.md`). (PHILOSOPHY.ko.md is authoritative original)

# CWP-Entry v3.4 - Entry Guidance & Position Alignment System (Universal Off-Rail & Railless Mobility Integrated Extension)

* **Official Document Classification:** Defensive Publication / Prior Art White Paper
* **Date:** 2026-09-13 (first draft 2026-08-20, v0.2.1 2026-08-22, v3.0 2026-08-22, v3.3 2026-08-23, v3.4 2026-09-13)
* **Author:** deundeuni (System Architect / Natural Person Inventor)
* **License:** CERN-OHL-S v2 (Hardware/CAD/Schematics) | CC BY-SA 4.0 (Documentation/Diagrams)
* **Purpose:** Defensive Publication / Prior Art Registration - To prevent exclusive patenting and mitigate infringement risks
* **Keywords:** CWP, CWP-Entry, EV battery swap, railway bogie alignment, tunnel mobility guidance, entry guidance, position alignment, V-rail, U-rail, guide groove, railless wheel guide, roller guide, line laser, 0.1ms HW Intercept, minimal retrofitting infrastructure integration, Quiet Assist, fail-safe, selective pass-through, rail and railless mobility alignment, Prior Art

---

## 0. Designer's Philosophical Declaration (Designer's Independent Conception & Prior Art Respect)

1. **Architectural Conception & Prior Art Respect:**  
   This system is grounded in publicly known car wash and railway V/U-rail chain conveyor mechanisms, roller guides, and optical/line laser position alignment prior art. This white paper originated from the **designer's (deundeuni) independent philosophy and problem-solving framework**: aiming to overcome the economic constraints of expensive dedicated robotic infrastructure, interface with the existing technical capabilities of skilled field engineers, and achieve low-impact docking and 0.1ms Hardware Intercept (0.1ms HW Intercept) fail-safe guidance even under harsh field environments (unpaved outdoor terrain, power outages, enclosed railway/tunnel spaces). Establishing the direction of 'integrating car wash, railway, and tunnel rail public domain technologies + entry guidance alignment systems' and selecting/combining optimal parametric specifications belong solely to the natural person designer. This system respects the engineering achievements of prior researchers and patent holders who pioneered conveyor and alignment infrastructure technology, and explicitly discloses the application of known principles as specific embodiment parameter combinations.

2. **Limitation on Software Utility Usage:**  
   * **System Architect (deundeuni):** Responsible for the overall system conception, architectural structure design, core requirements, and integration direction definition (Conception & Structural Design).
   * **Software and AI Utilities:** Limited strictly to **Passive Execution Utilities** that executed drafting, document organization, technical phrasing refinement, formatting, and review based on the conception and design direction provided by the designer. (No independent inventorship or design authority).  
   All design intent, structural combination rights, and prior art disclosure authority for this infrastructure belong entirely to the natural person designer.

---

## 1. Overview & Application Scope

### 1.1 Overview
CWP-Entry is a universal entry guidance and position alignment system intended for EV battery swapping, as well as **railway vehicles, large mobility in tunnels, logistics track systems, and railless ground-guided environments**.  
**Unlike conventional overhead descending structures and large vehicle lifts, it adopts a bottom V/U-rail and guide groove-based ascending docking method, aiming to implement infrastructure without deep ground excavation.**  
It is configured to facilitate precision alignment guidance at the ±2mm level even under multi-mobility load conditions through 3-stage alignment (Guide -> Entry -> V-Home) and organic combination of overhead line lasers and bottom rail/guide grooves.

### 1.2 Application Scope
This structure is not limited to passenger EV battery swapping, but is universally applicable to mitigating physical entry errors and aligning precision docking velocity for railway electric cars/locomotive bogies, special underground tunnel transporters, Urban Air Mobility (UAM) landing skids, Automated Guided Vehicles (AGV/AMR), agricultural machinery, drones, and open-field heavy module payloads.

---

## 2. Background & Infrastructure Economics

* **Minimal Retrofitting Infrastructure Integration:** Reusing existing V-rail, chain transfer, and guide rail mechanisms of gas stations, parking lots, automatic car washes, **railway maintenance depots, underground tunnels, and logistics road surfaces** as upper concepts, rather than building new expensive dedicated robotic facilities or excavating floors extensively. Interfacing 5cm (SLIM) or 8cm (SHUTTLE) and heavy-duty modules onto existing infrastructure surfaces via minimal retrofitting reduces initial construction costs and fosters hub deployment.
* **Skilled Field Engineer Centric Integration:** Rather than an AI monitoring or replacing field engineers, the system operates as an assistant structure that directly interfaces with the existing maintenance skills and field know-how of skilled engineers via Quiet Assist haptic signals (1 pulse / 2 pulses), prioritizing practical field experience.
* **Combination of Public Technologies:** Excluding proprietary corporate solutions and combining standard mechanical elements (seesaws, differential gears, V/U/C/T grooves, etc.) to alleviate royalty burdens and mitigate exclusive patent monopoly risks.

---

## 3. Limitation, Disclaimer of Warranties & Liability

This document is a technical concept disclosure published for defensive purposes and is provided strictly "AS-IS" without warranty of any kind.

1. **Disclaimer of Warranties:** No warranty of any kind, express or implied, is given regarding fitness for a particular purpose, merchantability, completeness, commercial feasibility, or non-infringement of third-party patents.
2. **Limitation of Liability:** The author (deundeuni) shall not be held legally liable for any direct, indirect, incidental, special, exemplary, or consequential damages, accidents, or losses resulting from the use, implementation, or application of this document.
3. **Disclaimer of Willful Intent & Defensive Publication Declaration (Non-willful Infringement Notice):** This disclosure constitutes a defensive publication intended to establish a defensive legal foothold against allegations of willful infringement under U.S. patent law (35 U.S.C. §284 and relevant case law doctrines) and to disclose prior art to the public domain to mitigate third-party attempts to obtain exclusive patents, with no intent to willfully infringe upon the rights of others.
4. **Compliance & Safety Responsibility:** Compliance with national regulations, electrical/fire/noise/vibration safety standards, certification acquisition, and field safety verification remains fully the responsibility of the implementer and commercializing entity.

---

## 3.5 CWP 4-Hardware Mechanisms & Survival Architecture (CWP 4-Hardware & System Integration)

This CWP-Entry system does not function in isolation; it operates organically in combination with core CWP hardware mechanisms and upper survival architectures to form a zero-downtime survival-oriented infrastructure.  
**The 4 CWP hardware mechanisms including CWP-Entry are not standalone technologies, but an integrated system designed alongside soma-moa Human-Centered Physical AI & Spatial Governance Protocol, chiplet-apu-multi-system-survival-architecture, and ARCHITECTURE_STRATEGY to cover entry guidance, alignment, docking, clamping, and computational survival.**  
**CWP-Entry and CWP-Battery-Swap are designed as an integrated continuous process from entry guidance (Guide -> Entry -> V-Home) to differential speed low-impact docking.**

* **Entry Guidance & Primary Alignment (`CWP-Entry` - This Technology):** Reusing car wash, railway, and tunnel V/U-rail infrastructure and ground guide grooves alongside line laser guides to mitigate vehicle entry errors and guide the vehicle into servicing/inspection zones.
* **Mechanical Secondary Alignment (`CWP-Rolling-Self-Align-Battery-Swap-System`):** Interfacing with V-groove and caster manual/self-alignment mechanisms (Types A/B/C/S) to physically absorb entry tolerance errors and guide the pack into the precise docking zone.
* **Differential Speed Low-Impact Docking (`CWP-Battery-Swap`):** Utilizing N/(N+1) differential gear ratios and a rotary stage to slow down relative engagement speed to extremely low levels aiming for cushioned docking.
* **Electromagnetic Clamping & Secure Latching (`CWP-Clamping-Battery-Swap-System`):** Utilizing EPM magnetic clamping, dual locking pins, and 3-layer cushion structures to achieve unpowered permanent magnetic holding and emergency release capability.
* **Physical Emergency Detachment & Release (0.1ms HW Intercept / LAST-LIGHT Integration):** Upon emergency events such as fire, power outage, or tunnel emergencies, a Hardware Intercept signal releases chains, pneumatics, and EPM clamps, supporting unpowered mechanical detachment.
* **Computational Control Survival (`chiplet-apu-multi-system-survival-architecture`):** Interfacing with distributed control systems and multi-chiplet control architecture to ensure entry and swapping control logic continues operating even if a control chiplet fails.

---

## 4. Brief Description of Drawings & AI Visualization Disclaimer

* **FIG. 1:** Overall isometric view of CWP-Entry autonomous guidance and alignment system
  * Overhead ceiling mount and line laser primary optical guidance
  * Bottom V/U-rail guide channel, ground-embedded groove, and chain/towing mechanism secondary alignment (encompassing railway bogie, tunnel transport, and railless wheel guide structures)
  * Battery swap and mobility stage engagement structure
* **FIG. 2:** Top view of CWP-Entry [SLIM] type (5cm embedded/overlay, single-chain towing)
* **FIG. 3:** Top view of CWP-Entry [SHUTTLE] type (8cm pallet, 4-point pneumatic air-lift)
* **FIG. 4:** Top view of CWP-Entry [FREE] type (internal pallet, integrated single motor, dual-stage torque sensor, composite laser guidance)

<img width="4000" height="8238" alt="CWP-Entry_BOX_TYPE_PREVIEW_4K" src="https://github.com/user-attachments/assets/b1003f07-ba00-408d-96b0-d0667c3fd0d4" />

[CWP-Entry-BOX-TYPE-UNIFIED-DEFENSIVE-PUBLICATION.pdf](https://github.com/user-attachments/files/32428605/CWP-Entry-BOX-TYPE-UNIFIED-DEFENSIVE-PUBLICATION.pdf)

* **Note (AI Visualization Disclaimer):** The mechanism concept in this specification was independently conceived by the author (deundeuni). Attached figures or conceptual drawings are visual examples generated using generic generative AI visualization tools for explanatory purposes only and are not copied from any existing product or registered patent of others.
* **Note on Drawings:** All dimensions, angles, and quantities in these drawings are non-limiting illustrative examples. Only functional structures (rail/groove guide, laser guidance, transport integration, heavy mobility scalability) constitute the core of this disclosure.

---

## 5. Product Lineup

* **SLIM (Infrastructure Retrofit):** 5cm embedded/overlay structure, single chain pull, compatible with existing car washes and small rail infrastructure retrofits.
* **SHUTTLE:** 8cm pallet structure, 4-point pneumatic lift integration (compatible with railway depots and heavy AGVs).
* **FREE:** Integrated single motor, dual-stage torque sensor, internal pallet, LED and line laser guide integration.

---

## 6. Universal Scalability, Control Modes, Selective Pass-Through & Licensing

### 6.1 Dual Protection & Transfer Control Modes
The system physically separates emergency shutoff response speed from normal transfer mechanisms during operation.

* **Mode A (Emergency Shutoff Response Speed - 0.1ms HW Fail-Safe):** Upon emergency events such as fire, power outage, or tunnel emergencies, a Hardware Intercept signal switches chain and pneumatic release drive signals toward shutoff/release within 0.1ms. This refers to control signal shutoff and unpowered mechanical release response time, not physical transfer speed.
* **Mode B (Normal Entry Alignment Transfer - Quiet Transfer Control):** In the Guide -> Entry -> V-Home alignment section, the system executes smooth transfer over seconds, applying soft torque smoothing protection logic to prevent motor overload and mechanical impact.

### 6.2 Omnidirectional Mobility & Off-Rail / Railless Extension
* **Form-Factor Agnostic:** Scalable beyond passenger EVs to **railway vehicles (electric car/locomotive bogie alignment), special tunnel transport mobility, Urban Air Mobility (UAM)/drone landing skids, Automated Guided Vehicles (AGV) and Autonomous Mobile Robots (AMR), micro-mobility, special exploration rovers, orbital modules, and heavy payload alignment structures**.
* **Physical Track Medium Agnosticism:** The guidance mechanism is not limited to protruding metal rail structures, but applies generically to all entry guidance structures where physical or optical trajectory guidance exists, including ground-embedded V/U guide grooves, unpowered roller guides, railless road wheel guide curbs, and autonomous wide-area guide lines.
* **Rescue Clearance:** Securing side door opening clearance (up to 850mm) and supporting automatic switching of overhead line lasers to emergency guidance lights (30-minute battery backup) during tunnel/depot power outages.

### 6.3 Selective Pass-Through System & Scope Expansion
* **Selective Pass-Through Integration (Rail & Railless Common Usage):** Following the minimal retrofitting infrastructure principle, entry/exit traffic lines are implemented by reusing existing automatic car washes, railway sidings, tunnel driving rails, and logistics guide infrastructure without adding new dedicated robotic infrastructure.
  * **Swapping/Servicing Vehicles:** Naturally entering existing rail/guide lines after work completion to execute subsequent processes.
  * **Non-Utilizing Pass-Through Vehicles:** Simple pass-through and exit are enabled using standard branching guide structures without complex variable switching mechanisms.
* **Existing Infrastructure & Fleet Integration:** Identically deployable at gas stations, charging stations, railway depots, underground tunnel management hubs, and logistics pallet transfer hubs.
* **Declaration on Application Field Differentiation:** Beyond simple towing in car wash V-rails, this system is a high-precision docking system applying railway V-groove self-centering and bogie alignment principles; novelty cannot be denied merely due to differences in application fields.

### 6.4 Licensing & Commercial Usage Guidelines

> CERN Open Hardware Licence Version 2 - Strongly Reciprocal (CERN-OHL-S v2)  
> Copyright (c) 2026 deundeuni  
>  
> This hardware design is licensed under CERN-OHL-S v2.  
> You may manufacture and distribute it, even commercially,  
> but if you distribute products based on it, you must also  
> make the modified design files available under the same license.  
>  
> Full text: https://ohwr.org/cern_ohl_s_v2.pdf  
>  
> Documentation and figures: CC BY-SA 4.0  
> https://creativecommons.org/licenses/by-sa/4.0/  

* **Commercial Usage Guidelines:** Both commercial manufacturing and sales are permitted. You only need to make modified design files of the CWP portion available under the same license; you are not required to disclose other proprietary secrets of your company.

---

## 7. Practical Protection

* **Authoritative Original Principle:** The legal and technical interpretations of this specification strictly prioritize the Korean original document (`README.ko.md`), while English and other translations function solely for secondary reference.
* **Broad Scope Inclusion:** Rail specifications, sensor parameters, entry error figures, transfer modes, and lineups described herein apply generically as upper concepts to **protruding rails, embedded guide grooves, railless wheel guide curbs, unpowered rollers, and optical guide lines** to preempt prior art.
* **Non-Intentional Omission & Non-Exhaustive Disclaimer:** Technical standards, publicly known principles, statutes, and relevant specifications cited or enumerated in this specification serve solely as illustrative descriptions for ease of understanding and do not imply exhaustive or rigid limitations. Due to subjective limitations or cognitive oversights of the author, specific detailed specifications, relevant industrial standards, subsequent amendments, or equivalent prior art may have been omitted or cumulatively unstated; however, this does not constitute intentional concealment or exclusion. All derivative standards, revised specifications, equivalent mechanisms, and combinations of prior art connected to the disclosed core architectural concept are deemed included within the comprehensive prior art scope of this defensive publication white paper.
* **Defensive Publication & Prior Use Rights Combination:** This white paper primarily aims at defensive prior art publication, and maintains offline design drawings, prototypes, and development records concurrently to establish prior use rights under Article 103 of the Korean Patent Act and 35 U.S.C. §273 of the U.S. Patent Act.
* **Separation of Commercialization Content:** This white paper original contains strictly Pure Open Source and prior art disclosures, while proprietary revenue models and business execution details are managed separately as standalone technical documents.

---

## 8. Sources & Records

* **Foundational Entry Guidance & Conveyor Prior Art**
  * Car Wash V-Rail Conveyor & Chain Pusher Principles — Publicly known technology for mobility wheel manual centering and towing transfer using V/U guide rails and chain pusher rollers
  * Line Laser & Optical Alignment Guidance — Publicly known technology for vehicle/mobility precision entry alignment using overhead line laser projection and optical sensors
  * US Patent US3596606A — Vehicle conveyor system for automatic car washes (V-rail guide and roller pusher mechanism)
  * US Patent US5730061A — Automatic conveyor system with damage-free guide rails (Car wash guide rails and automated transfer assembly)
  * US Patent US9739844B2 — Guidance and alignment system and methods for electric vehicle wireless charging systems (Mobility sensor-based position alignment and guide system)
  * US Patent US9114720B2 — Vehicle positioning system for wireless charging stations (Precision vehicle/mobility position alignment system)

* **Specific Embodiment Feature**
  * Grounded in known car wash V-rails and optical alignment principles, featuring technical differentiation through the specific embodiment structure combining bottom V/U-rails/embedded guide grooves with overhead line lasers, 3-stage (Guide -> Entry -> V-Home) guidance mechanisms, 0.1ms HW Intercept emergency release, and integrated rail/railless expansion lineups (SLIM/SHUTTLE/FREE).

* **Ecosystem Repositories & Academic Identifiers**
  * Universal Survival Architecture & APU Controller (`chiplet-apu-multi-system-survival-architecture`) — GitHub: `deundeuni / chiplet-apu-multi-system-survival-architecture` | CERN Zenodo DOI: `10.5281/zenodo.22374987` (https://doi.org/10.5281/zenodo.22374987)
  * Disaster Evacuation & Auxiliary Infrastructure (`LAST-LIGHT`) — GitHub: `deundeuni / LAST-LIGHT` | CERN Zenodo DOI: `10.5281/zenodo.22373189` (https://doi.org/10.5281/zenodo.22373189)
  * CWP Entry Guidance & Alignment (`CWP-Entry`) — GitHub: `deundeuni / CWP-Entry`
  * CWP Battery Swap Docking (`CWP-Battery-Swap`) — CERN Zenodo DOI: `10.5281/zenodo.22373538` (https://doi.org/10.5281/zenodo.22373538)
  * CWP Electromagnetic Clamping (`CWP-Clamping-Battery-Swap-System`) — CERN Zenodo DOI: `10.5281/zenodo.22373722` (https://doi.org/10.5281/zenodo.22373722)
  * CWP Rolling Self-Align (`CWP-Rolling-Self-Align-Battery-Swap-System`) — CERN Zenodo DOI: `10.5281/zenodo.22373704` (https://doi.org/10.5281/zenodo.22373704)
  * Canonical Gateway & Main Repository (`soma-moa`) — GitHub: `deundeuni / soma-moa` | Gateway Domain: `somamoa.ai.kr`

* **Legal Statutes & Precedents**
  * Korean Patent Act Article 103 — Prior Use Rights (Non-exclusive License by Prior Use)
  * 35 U.S.C. §273 — Defense to Infringement Based on Prior Commercial Use
  * Defensive Disclosure & Disclaimer of Willful Intent Notice — This document is published as a defensive publication to establish proactive defense against willful infringement claims under U.S. patent law (35 U.S.C. §284 and relevant case law) and to explicitly disclose prior art in the public domain to prevent exclusive patenting by third parties.

---

## Appendix A. Inventorship & Attribution

* **deundeuni (System Architect & Natural Person Inventor):** General planner and original inventor of the CWP-Entry system architecture, V/U-rail alignment parameters, extension mechanisms to heavy rail infrastructure (railway/tunnel) and railless ground guides, 0.1ms HW Intercept, and minimal retrofitting structures (Conception & Structural Design).
* **Notice on Software & AI Utilities Usage:** Software and AI tools utilized in drafting this document are limited strictly to **Passive Execution Utilities** that executed drafting, document organization, formatting, and review based on the conception and design direction provided by the designer, independent of specific corporate names or AI model names, without impacting the original design know-how, core logic, or inventorship.

---

## Appendix B. Referenced Standards & Frameworks

* **[Standards-EV]** IEC 62840-1:2016 (Electric vehicle battery swap system — Part 1: General and guidance)
* **[Standards-Railway]** IEC 62278 / EN 50126 (Railway applications — Specification and demonstration of Reliability, Availability, Maintainability and Safety)
* **[Standards-Safety]** ISO 13849-1:2023 (Safety of machinery — Safety-related parts of control systems)
* **[Standards-Safety]** IEC 61508:2010 (Functional safety of electrical/electronic/programmable electronic safety-related systems)
* **[Standards-Design]** ISO 128 / USPTO MPEP 608.02 (Technical drawings and patent drawing specifications)
* **[Law-AI]** USPTO AI Inventorship Guidance 2024 (Principle 3: Refinement and Error Correction)
* **[Prior Art]** Car wash and railway bogie conveyor rail industry practice (V/U-rail + chain pusher mechanisms, Public Domain)
