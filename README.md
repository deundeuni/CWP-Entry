> **Multilingual Publication Notice:** This document is dual-published in Korean and English. (Korean Version: [README.ko.md](README.ko.md))  
> **Original Authority Notice:** The authoritative legal and engineering standard for this technical specification belongs to the Korean original (`README.ko.md`), while English and other translations function solely for secondary reference.

# CWP-Entry - Guidance and Position Alignment System (Railway & Tunnel Integrated Expansion)

* **Official Document Classification:** Defensive Publication / Prior Art White Paper
* **Initial Publication Date:** 2026-08-20 / **Latest Revision Date:** 2026-09-06
* **Author:** deundeuni (System Architect / Natural Person Inventor)
* **License:** CERN-OHL-S v2 (Hardware/CAD/Drawings) | CC BY-SA 4.0 (Documents/Descriptions)
* **Purpose:** Defensive Publication / Prior Art Registration - Preventing Monopolistic Patenting and Mitigating Infringement Risks
* **Search Keywords:** CWP, CWP-Entry, EV Battery Swap, Railway Bogie Alignment, Tunnel Mobility Guidance, Entry Guidance, Position Alignment, V-Rail, U-Rail, Line Laser, 0.1ms HW Intercept, Minimal Infra Retrofit, Quiet Assist, Fail-Safe, Selective Passage, Rail-Based Mobility Alignment, Guidance System, Prior Art

---

## 0. Designer's Philosophical Declaration & Prior Art Publication Notice

1. **Architectural Conception & Technical Synergy:**  
   This system originated from the **designer's (deundeuni) independent philosophy and problem awareness** aiming to overcome the economic limitations of existing expensive proprietary robotic infrastructure, integrate and leverage the practical technical skills of on-site engineers, and enable low-impact docking and 0.1ms HW Intercept-based fail-safe guidance across diverse environments (outdoor open-air lots, power outages, confined spaces like railways and tunnels). The architecting right to establish the direction of "Car wash, railway, and tunnel rail public technology integrated adoption + entry guidance alignment system" and select and combine optimal parameter specifications belongs solely to the natural person designer.

2. **Role Division Notice between Human Designer and Software Utility:**  
   * **System Architect (deundeuni):** Responsible for overall system conception, architectural structure design, core requirements, and integration direction definition (Conception & Structural Design).
   * **Software and AI Utility:** Limited to a **Passive Execution Utility** role performing drafting, document organization, technical expression refinement, formatting, and review based on the conception and design direction provided by the designer. (Restricted strictly to documentation and formatting tools, not performing direct numerical calculations or physical simulations).  
   All design intent, structural combination rights, and prior art publication rights for this infrastructure remain exclusively vested in the designer.

---

## 1. Overview
CWP-Entry is a universal system for entry guidance and position alignment across rail-based transport environments, including EV battery swapping as well as **railway rolling stock, large-scale mobility inside tunnels, and logistics track systems**.  
**Unlike conventional top-down descending or large vehicle lift systems, this system adopts a bottom-up V/U-rail-based ascending docking approach, enabling infrastructure implementation without demolishing existing floors or conducting massive excavation work.**  
It is configured to achieve precision alignment guidance within ±2mm through a 3-stage alignment sequence (Guide -> Entry -> V-Home) combining upper line lasers and lower V/U-rail integration.

---

## 2. Background & Minimal Infra Retrofit

* **Minimal Infra Retrofit:** Instead of constructing expensive proprietary robotic facilities from scratch or completely excavating flooring, this system universally adopts and reuses existing V-rails, chain transport mechanisms, and guide rails from national gas stations, parking lots, automated car washes, **as well as railway maintenance depots and underground tunnels**. 5cm (SLIM), 8cm (SHUTTLE), and heavy-duty modular units are retrofitted onto existing infrastructure surfaces with minimal modifications to reduce initial setup costs and establish hubs.
* **High-Skill Human-Centric Integration:** Rather than a structure where AI monitors and replaces on-site engineers, it directly integrates the practical maintenance skills and field know-how of experienced engineers via Quiet Assist haptic signals (1x/2x). It is designed to operate as an assistive structure prioritizing the practical experience of field personnel.
* **Public Domain Synergy:** By eliminating monopolistic technologies of specific corporations and combining standard mechanical elements (seesaws, differential gears, V/U/C/T grooves, etc.), royalty burdens are mitigated and potential patent monopolization by specific entities is defended.

---

## 3. Limitation, Disclaimer of Warranties & Liability

This document is a technical concept disclosure for defensive publication and is provided AS-IS without any warranties.

1. **Disclaimer of Warranties:** No warranty is provided regarding fitness for a particular purpose, merchantability, safety, or commercialization.
2. **Limitation of Liability:** The author (deundeuni) bears no legal liability whatsoever for direct or indirect damages, accidents, or losses resulting from the use, implementation, or application of this document.
3. **No Guarantee of Third-Party Rights:** This document does not guarantee that it does not infringe upon third-party rights such as patents, trademarks, or copyrights; rights investigation is the responsibility of the implementer.
4. **Regulations, Safety & Certification Responsibility:** Compliance with national regulations, electrical/fire/safety standards, acquisition of certifications, and safety verification rest entirely with the implementer.

---

## 3.5 CWP 4-Hardware & System Integration

The CWP-Entry system does not operate in isolation; it organically integrates with CWP core hardware mechanisms and upper survival architectures to form a zero-downtime, survival-oriented infrastructure.  
**The CWP 4 units, including this CWP-Entry, are not standalone technologies; together with the soma-moa Human-Centered Physical AI & Spatial Governance Protocol, chiplet-apu-multi-system-survival-architecture, and ARCHITECTURE_STRATEGY, they form an integrated system designed from conception as a unified survival-type infrastructure covering everything from entry guidance to alignment, docking, clamping, and computational survival.**  
**The CWP-Entry and CWP-Battery-Swap are not separate independent technologies; they are designed as an integrated system where entry guidance (Guide->Entry->V-Home) and differential deceleration low-impact docking are organically connected as a single continuous process from inception.**

* **Entry Guidance & Primary Alignment (`CWP-Entry` - This Technology):** Mitigates mobility entry errors and precisely guides vehicles/mobility to maintenance/inspection zones via car wash and railway/tunnel common V/U-rail infrastructure adoption and line laser guides.
* **Mechanical Secondary Alignment (`CWP-Rolling-Self-Align-Battery-Swap-System`):** Physically absorbs dimensional errors post-entry and guides units to the precision docking zone using V-groove and caster manual/autonomous alignment mechanisms (Types A/B/C/S).
* **Differential Deceleration Low-Impact Docking (`CWP-Battery-Swap`):** Aims for cushioned docking by reducing docking relative speed to ultra-low speeds utilizing N/(N+1) differential gear ratios and rotating stages.
* **Electromagnetic Clamping & Safety Fastening (`CWP-Clamping-Battery-Swap-System`):** Aims for non-powered permanent magnet fixation and emergency safety release following precision alignment, combined with general-purpose EPM magnetic clamping modules, dual-pin fixation, and triple-cushion structures.
* **Physical Emergency Interlock/Release (Linked with `0.1ms HW Intercept` / `LAST-LIGHT`):** In emergencies such as fire or power outages, chain, pneumatic, and EPM clamps are released via Hardware Intercept signals, aiming for power-free mechanical escape and evacuation.
* **Computational Control Survival (`chiplet-apu-multi-system-survival-architecture`):** Combined with distributed control (CCS) and multi-chiplet control architectures to ensure entry and exchange logic continues to operate even if a control chiplet fails.

---

## 4. Brief Description of Drawings

* **FIG. 1**: Overall isometric view of the CWP-Entry autonomous guidance and alignment system
  * Upper primary guidance via ceiling mount and line lasers
  * Lower secondary alignment via V/U-rail guide channels and chain/traction mechanisms (covering railway bogie and tunnel transport structures)
  * Battery swap and mobility stage integration structure
* **FIG. 2**: CWP-Entry [SLIM] type top view (5cm embedded/surface-mounted, single-chain traction method)
* **FIG. 3**: CWP-Entry [SHUTTLE] type top view (8cm pallet, 4-point pneumatic air-lift method)
* **FIG. 4**: CWP-Entry [FREE] type top view (built-in pallet, combined single motor, dual-stage torque sensor, hybrid laser guide method)

* **Drawing Note:** All dimensions, angles, and quantities in the drawings are non-limiting examples. Only the functional structures (rail guides, laser guidance, transport linkage, large-scale mobility scalability) constitute the core of this disclosure.

---

## 5. Lineup

* **SLIM (Infra-Transition Type):** 5cm embedded/surface-mounted structure, single chain pull, retrofit-compatible with existing car wash and small rail infrastructure.
* **SHUTTLE:** 8cm pallet structure, 4-point pneumatic lift integrated type (compatible with railway inspection depots and large logistics AGVs).
* **FREE:** Combined single motor, dual-stage torque sensor, built-in pallet, LED guide and line laser guide integrated type.

---

## 6. Universal Mobility, Control Modes & Selective Passage

### 6.1 Dual Protection Mode
The system physically separates and operates the cutoff response speed during emergencies and the transport mechanism under normal states.

* **Mode A - 0.1ms HW Fail-Safe (Emergency Cutoff & Release Response Speed):** In the event of a fire, power outage, or signal anomaly, Hardware Intercept cuts off/switches chain and pneumatic release signal drives to release direction within 0.1ms or less. This refers to control signal cutoff and power-free mechanical release response time, not physical transport velocity.
* **Mode B - Normal Entry Alignment Transport (Quiet Transport Control):** Performs smooth, low-noise transport across the Guide -> Entry -> V-Home sections, applying soft torque-smoothing protection logic to prevent motor overload and mechanical shocks.

### 6.2 Universal Mobility & Safety Escape
* **Form-Factor Agnostic:** Scalable beyond passenger EVs to **railway rolling stock (electric train/locomotive bogie alignment), special transport mobility inside tunnels, UAM/drone landing sites, logistics AGVs/AMRs, micro-mobility, special exploration rovers, and in-orbit module alignment structures**.
* **Rescue Clearance:** Secures lateral door clearance (up to 850mm) and supports automatic switching of upper line lasers to emergency guidance lights during power outages in tunnels/depots (30-min battery backup).

### 6.3 Selective Passage & Extended Scope
* **Selective Passage Linkage:** Implements entry/exit traffic flows by reusing existing automated car wash, railway shunting line, and tunnel running rail infrastructure without adding new dedicated robotic infrastructure, adhering to the Minimal Infra Retrofit principle.
  * **Swap/Maintenance-Utilizing Mobility:** Naturally enters existing rail lines after task completion to perform subsequent processes.
  * **Non-Utilizing Passing Mobility:** Allows simple passage and exit using existing standard branching guide structures without complex variable branching mechanical devices.
* **Existing Infrastructure & Fleet Linkage:** Can be deployed identically in ground transport infrastructure of liquid fuel distribution hubs (gas stations, charging stations), railway depots, and underground tunnel management posts.
* **Declaration on Application Differentiation:** This system goes beyond the simple traction method of car wash V-rails, applying railway track-style V-groove autonomous centering and bogie alignment principles as a high-precision docking system; novelty cannot be denied merely because the application field differs.

---

## 7. Practical & Legal Protection

* **Original Authority Principle:** Legal and technical interpretations of this specification apply the Korean original (`README.ko.md`) as the highest standard, while English and other translations function solely for secondary reference.
* **Scope Comprehensiveness:** Rail specifications, sensor parameters, entry error figures, transport modes, and lineups described in this document are not limited to car wash rails but comprehensively apply to **all rail-based guidance and transport infrastructures such as railways, tunnels, and logistics tracks** as superior concepts to preempt prior art.
* **Commercialization Separation:** This white paper original contains only pure open source and prior art disclosure contents, while independent business models and detailed commercialization execution plans are managed separately as standalone technical documents.

---

## 8. Sources

* **Official Repository:** GitHub Repository (`deundeuni/CWP-Entry`)
* **Linked CWP Repository 1:** GitHub Repository (`deundeuni/CWP-Rolling-Self-Align-Battery-Swap-System`)
* **Linked CWP Repository 2:** GitHub Repository (`deundeuni/CWP-Battery-Swap`)
* **Linked CWP Repository 3:** GitHub Repository (`deundeuni/CWP-Clamping-Battery-Swap-System`)
* **Linked Architecture Repository:** GitHub Repository (`deundeuni/chiplet-apu-multi-system-survival-architecture`)
* **Canonical Gateway:** `somamoa.ai.kr` (Canonical Gateway)

---

## Appendix A. Inventorship & Attribution

* **deundeuni (System Architect & Sole Inventor):** General planner and sole inventor of the CWP-Entry system architecture, V/U-rail alignment parameters, extension mechanisms for large-scale rail infrastructure (railways, tunnels), 0.1ms HW Intercept, and Minimal Retrofit structures described in this specification (Conception & Structural Design).
* **Software Utility Notice:** Software and AI tools used during the preparation of this document were limited to **Passive Execution Utilities** performing drafting, document organization, formatting, and review based on the conception and design direction provided by the designer, and do not affect the proprietary design know-how, core logic, or inventorship of this system.

---

## Appendix B. Standards & References

* **[Standard-EV]** IEC 62840-1:2016 (EV Battery Swap Infrastructure Safety)
* **[Standard-Rail]** IEC 62278 / EN 50126 (Railway applications — Specification and demonstration of reliability, availability, maintainability and safety)
* **[Standard-Safety]** ISO 13849-1:2023 (Safety of machinery — Safety-related parts of control systems / Cat 4, PL e)
* **[Standard-Safety]** IEC 61508:2010 (Functional Safety of E/E/PE Safety-related Systems / SIL3)
* **[Standard-Design]** ISO 128 / USPTO MPEP 608.02 (Technical Drawings & Patent Drawing Standards)
* **[Legal-AI]** USPTO AI Inventorship Guidance 2024 (Principle 3: Refinement & Error Correction)
* **[Prior Art]** Car wash and railway bogie transport rail industry practice (V/U-rail + chain traction mechanism, Public Domain)
