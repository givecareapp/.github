<!-- Diátaxis: explanation -->

# 💙 GiveCare Open Source

<div align="center">

**Open tools and datasets for caregiver AI safety, assessment, and evaluation**<br>
*Building in public to help family caregivers and the systems that support them.*

[![Code License: MIT](https://img.shields.io/badge/code-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Data License: CC BY 4.0](https://img.shields.io/badge/data-CC--BY--4.0-blue.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Featured: Forbes](https://img.shields.io/badge/Featured-Forbes-blue)](https://www.forbes.com/sites/christinecarter/2025/08/12/12-startups-proving-motherhood-over-40-is-a-market-advantage/)

[🌐 givecareapp.com](https://givecareapp.com)

</div>

---

## GitHub homes

- ❤️ **GiveCare**: https://github.com/givecareapp
- 🧑‍🔬 **Ali Madad**: https://github.com/amadad
- 🏛️ **SCTY**: https://github.com/SCTY-Inc

---

## 👋 About

**[63 million Americans are family caregivers](https://wiki.givecareapp.com/sources/aarp-nac-2025/).** Caregiving can bring burnout, emotional strain, sleep disruption, financial stress, and long-term health effects.

GiveCare open source focuses on the public primitives needed to build safer caregiver-support systems:

- **Safety benchmarks** for AI agents in long-term caregiving relationships
- **Evaluation datasets** for crisis handling, boundaries, red-team prompts, and trauma-informed response
- **Caregiver SDOH tools** for measuring GC1–GC6 domains and wellbeing signals

The production GiveCare app is separate. These repos are the open evaluation, measurement, and research layer.

---

## Canonical public surfaces

- **Product:** [givecareapp.com](https://givecareapp.com)
- **Caregiver score:** [score.givecareapp.com](https://score.givecareapp.com)
- **Benefits database:** [benefits.givecareapp.com](https://benefits.givecareapp.com)
- **Care Policy Radar:** [givecareapp.com/policy](https://givecareapp.com/policy)
- **Care economy editorial:** [pulse.givecareapp.com](https://pulse.givecareapp.com)
- **Caregiver knowledge base:** [wiki.givecareapp.com](https://wiki.givecareapp.com)
- **InvisibleBench:** [bench.givecareapp.com](https://bench.givecareapp.com)
- **GC-SDOH-30:** [givecareapp.com/sdoh](https://givecareapp.com/sdoh)
- **Partner story:** [story.givecareapp.com](https://story.givecareapp.com)
- **Labs network:** [givecareapp.com/labs](https://givecareapp.com/labs)

Use these canonical domains when citing GiveCare public work. The GitHub organization hosts the open-source benchmark, evaluation dataset, and toolkit; product support, benefits discovery, and public research surfaces live on the domains above.

---

## 📂 Repositories

### 🔵 [givecare-bench](https://github.com/givecareapp/givecare-bench)

AI safety benchmark for long-term caregiving relationships.

Judge caregiver-support conversations and get a Jury Card with evidence per check. Safety and Care stay separate; there is no composite score or model rank. `uv run bench demo` runs with no keys. Paper on arXiv.

### 🟣 [givecare-evals](https://github.com/givecareapp/givecare-evals)

Public caregiver AI safety eval data.

Check any caregiver-facing assistant against SMS-style cases for crisis handling, boundaries, red-team prompts, realistic caregiver messages, and multi-turn continuity. Data only, CC-BY-4.0; the count lives in the repo.

### 🟢 [givecare-tools](https://github.com/givecareapp/givecare-tools)

Open-source caregiver SDOH assessment and scoring toolkit.

Score a caregiver's six SDOH domains in TypeScript and route to the one that needs attention. `npm install @givecare/tools`, no account, no network.

---

## 🤝 Get involved

We welcome collaboration from:

- **Researchers** working on evaluation, safety, measurement, and assessment science
- **Developers** building test harnesses, model adapters, and caregiver-support tools
- **Clinicians and social workers** with caregiving, aging, disability, and mental health expertise
- **Health systems and NGOs** exploring caregiver support workflows
- **Caregivers** willing to pressure-test whether these tools match lived experience

Contact: [info@givecareapp.com](mailto:info@givecareapp.com)

---

## 📄 Licenses

Code projects are MIT licensed unless noted otherwise. Dataset artifacts, including GiveCare Evals, are CC-BY-4.0 unless noted otherwise.

---

<div align="center">

**© 2026 GiveCare**<br>
*You've been carrying everyone else. Let us help carry you.*

</div>
