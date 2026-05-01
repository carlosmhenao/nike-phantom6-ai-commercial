<div align="center">

![Nike Phantom 6 — AI Commercial Case Study](./assets/banner.png)

# Nike Phantom 6 Elite — AI Commercial Case Study

#### A 60-second cinematic commercial produced entirely with AI tools by a single operator. Zero traditional production budget. Built using systematic methodology adapted from data analytics workflows.

[![Watch the Video](https://img.shields.io/badge/▶_Watch_the_Commercial-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtu.be/LIjcOK5gR1o?feature=shared)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Carlos_Moreno-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/carlosmorenohenao)
[![Portfolio](https://img.shields.io/badge/Portfolio-carlosmoreno.dev-000000?style=for-the-badge&logo=netlify&logoColor=white)](https://carlosmoreno-portafolio.netlify.app)

<br>

![Status](https://img.shields.io/badge/status-completed-success?style=flat-square)
![Project Type](https://img.shields.io/badge/type-spec_commercial-blue?style=flat-square)
![Duration](https://img.shields.io/badge/duration-60_seconds-lightgrey?style=flat-square)
![Production](https://img.shields.io/badge/production-AI_native-purple?style=flat-square)
![Tools](https://img.shields.io/badge/tools-5_AI_platforms-orange?style=flat-square)

</div>

---

## Table of Contents

- [Overview](#overview)
- [The Final Commercial](#the-final-commercial)
- [Technical Stack](#technical-stack)
- [Methodology](#methodology)
- [Production Pipeline](#production-pipeline)
- [Key Technical Challenges Solved](#key-technical-challenges-solved)
- [What This Project Demonstrates](#what-this-project-demonstrates)
- [Performance Metrics](#performance-metrics)
- [Author](#author)
- [License & Disclaimer](#license--disclaimer)

---

## Overview

This project documents the production of a fully AI-generated commercial for the **Nike Phantom 6 Elite** football boot, executed by a single operator over multiple iteration cycles. The objective was to test whether the analytical mindset of a data analyst — defining variables, iterating systematically, validating against measurable standards — could produce broadcast-quality commercial output without traditional production resources.

> **Hypothesis:** The bottleneck in modern advertising is not access to creative production. It is the ability to operate AI tools at a professional level while applying systems thinking to creative output.

> **Result:** A 60-second cinematic commercial with consistent brand identity, professional color grading, layered sound design, and continuous narrative across 11 distinct AI-generated clips — produced for a total cost of $0 in traditional production resources.

---

## Technical Stack

| Tool | Category | Purpose |
|------|----------|---------|
| **Kling AI 3.0** | Video Generation | Core video production — 11 clips iterated |
| **Nano Banana / Gemini 2.5 Flash Image** | Image Generation | Frame generation, storyboarding, transition assets |
| **ElevenLabs Sound Effects** | Audio Generation | Custom sound design — footsteps, ambient layers |
| **DaVinci Resolve 19** | Post-Production | Color grading, sound mixing, finishing, export |
| **Custom Prompt Engineering** | Methodology | Cross-scene consistency, AI bias mitigation |

---

## Methodology

The production followed a structured iteration cycle inspired by analytics workflows. Each phase mirrors the discipline applied to dataset cleaning and dashboard design:

### Phase 1 — Brief Decomposition
Translating creative direction into measurable specifications. Each clip received a locked specification document covering frame composition, color values, audio layers, character consistency, and atmospheric details.

### Phase 2 — Systematic Generation
Producing each clip independently with locked variables. Character description, wardrobe, lighting setup, and color grade specifications repeated across all 11 prompts to maintain identity continuity.

### Phase 3 — Validation Against Scopes
Using DaVinci Resolve waveform and vectorscope readings to ensure exposure and color continuity. Every clip validated against a single reference standard rather than subjective visual judgment.

### Phase 4 — Iteration on Failures
Identifying AI model biases and pivoting strategy. When a model failed silently or overrode prompt instructions, the production approach was adapted rather than continuing to iterate the same failed prompt.

### Phase 5 — Layered Finishing
Applying multi-track sound design, color grading nodes, and tempo adjustments in post-production. Five distinct audio layers + six color grade nodes per clip + manual cut point adjustments per transition.

---

## Production Pipeline


### Per-Clip Workflow

| Step | Tool | Output |
|------|------|--------|
| 1 | Nano Banana | Storyboard frame (start frame + end frame) |
| 2 | Kling AI 3.0 | Video clip generation (multiple iterations until validated) |
| 3 | DaVinci Resolve | Color grading (6-node structure per clip) |
| 4 | DaVinci Fairlight | Sound layer integration (5-track architecture) |
| 5 | DaVinci Master | Final export with broadcast-spec settings |

---

## Key Technical Challenges Solved

### Challenge 1 — Character Consistency Across 11 Clips

**Problem:** AI video models reinterpret character features between generations, producing inconsistent identity across clips.

**Solution:** Built a locked character specification document repeated verbatim across all 11 prompts, combined with reference photo binding in Kling's character feature. Validated facial features frame-by-frame against the reference set. When inconsistencies appeared, regenerated rather than accepted.

**Result:** Consistent character identity across all 11 clips despite different scenarios, lighting conditions, and camera angles.

---

### Challenge 2 — Color Continuity Between AI-Generated Clips

**Problem:** Each AI generation outputs slightly different exposure values that look correct in isolation but break continuity when sequenced.

**Solution:** Applied a 6-node color correction structure in DaVinci Resolve to every clip — Normalize, Exposure, Contrast, Color Balance, Saturation, and Final Look. Used waveform scopes to balance exposure against a single reference clip rather than relying on visual judgment.

**Result:** Uniform Nike commercial color identity across the entire 60-second sequence with neutral grade integrity.

---

### Challenge 3 — Model Bias on Object-Subject Interaction

**Problem:** The video model consistently placed Nike boots on the character's feet despite explicit negative prompts. The model associated "person + boots in scene" with "person wearing boots" regardless of instruction wording.

**Solution:** Recognized the model bias as insurmountable through prompt engineering alone. Pivoted strategy: split the problematic scene into two separate clips — one with character without boots in frame, one with boots without character body in frame — joined invisibly in post-production using a match cut technique.

**Result:** Successful execution of the intended narrative without fighting the model's inherent training bias.

---

### Challenge 4 — Sound Design Without Usable Native Audio

**Problem:** Most AI-generated audio was unusable for premium commercial output. Native audio contained inconsistencies, phantom sounds, and inappropriate background music despite negative prompts.

**Solution:** Muted native audio across all clips and rebuilt the sound design from scratch using a 5-layer architecture:

1. **Spine sub-bass** — continuous tension layer ascending across the full 60s
2. **Ambient textures** — three connective atmospheres (interior, primal, stadium)
3. **Diegetic SFX** — footsteps, fabric friction, hand-on-leather, jaguar paws
4. **Strategic silences** — three intentional silence moments as dramatic punctuation
5. **Expansion moment** — single reverb swell at the climax reveal

**Result:** Cohesive premium sound design matching the visual quality, with intentional sonic identity rather than AI-generated default audio.

---

## What This Project Demonstrates

| Skill | Application |
|-------|-------------|
| **Systems Thinking** | Treating creative briefs as measurable specifications rather than abstract inspiration |
| **Tool-Agnostic Methodology** | Operating multiple AI tools as components of a unified workflow |
| **Failure Recognition** | Identifying when AI models fail silently and adapting production approach accordingly |
| **Quality Control** | Using technical scopes and metrics rather than subjective judgment alone |
| **Multi-Disciplinary Execution** | Merging analytical rigor of data work with creative output of brand commercial production |
| **Resource Optimization** | Producing broadcast-quality output without traditional production budget |

---

## Performance Metrics

| Metric | Value |
|--------|-------|
| **Total Production Cost** | $0 (in traditional production resources) |
| **Final Output Duration** | 60 seconds |
| **Total Clips Generated** | 11 distinct AI clips |
| **Iteration Cycles per Clip** | 4-12 iterations |
| **Total Production Time** | ~80 hours across 14 days |
| **Color Grade Nodes Applied** | 6 per clip × 11 clips = 66 grading operations |
| **Sound Design Layers** | 5 simultaneous layers across full timeline |
| **Final Delivery** | 1080p HD, broadcast-spec audio mastering |

---

## Author

<div align="center">

### Carlos Moreno Henao

**Data Analyst & Marketing Strategist** | Business Intelligence & AI Automation

</div>

I bridge analytical rigor and creative execution. My background combines a Business Management & Marketing degree from Quincy University with technical expertise in SQL, Tableau, Python, and R — alongside production experience in sports media and digital content strategy.

This project represents my belief that the most valuable professionals in the next decade will be those who can apply systems thinking to creative output, not those who specialize in only one side of the equation.

**Currently OPT-eligible and based in Kansas City, MO. Open to data analyst and AI-driven marketing roles.**

<div align="center">

[![Email](https://img.shields.io/badge/Email-carlosmhen@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:carlosmhen@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-carlosmorenohenao-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/carlosmorenohenao)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit_Site-000000?style=flat-square&logo=netlify&logoColor=white)](https://carlosmoreno-portafolio.netlify.app)
[![Location](https://img.shields.io/badge/Kansas_City-MO-blue?style=flat-square&logo=googlemaps&logoColor=white)](https://maps.google.com/?q=Kansas+City+MO)

</div>

---

## License & Disclaimer

This project is shared for portfolio and educational purposes only.

The Nike brand, Phantom 6 Elite product, and Nike trademarks shown in the commercial are property of **Nike, Inc.** This is a non-commercial **speculative project (spec ad)** produced as a personal portfolio piece and is not affiliated with, sponsored by, or endorsed by Nike, Inc. in any capacity.

All AI-generated content in this project is produced using publicly available tools under their respective terms of service.

<div align="center">

---

⭐ **If this case study was valuable or interesting, consider starring the repository.** ⭐

*Built with systems thinking, executed with creative discipline.*

</div>
