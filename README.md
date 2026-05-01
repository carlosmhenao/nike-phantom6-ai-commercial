# Nike Phantom 6 Elite — AI Commercial Case Study

> A 60-second commercial produced entirely with AI tools by a single operator. 
> Zero traditional production budget. Built using systematic methodology adapted from data analytics workflows.

[![Watch the full commercial](./assets/thumbnail.png)](https://youtu.be/LIjcOK5gR1o?feature=shared)

**▶ [Watch the full 60-second commercial here]([YOUR_YOUTUBE_LINK])**

---

## Project Summary

This project documents the production of a fully AI-generated commercial for Nike Phantom 6 Elite football boots, executed by a single operator over multiple iteration cycles. The objective was to test whether the analytical mindset of a data analyst — defining variables, iterating systematically, validating against measurable standards — could produce broadcast-quality commercial output without traditional production resources.

**Result:** A 60-second cinematic commercial with consistent brand identity, professional color grading, layered sound design, and continuous narrative across 11 distinct AI-generated clips.

---

## Technical Stack

| Tool | Purpose |
|------|---------|
| **Kling AI 3.0** | Video generation (11 clips iterated) |
| **Nano Banana / Gemini 2.5 Flash Image** | Frame generation and storyboarding |
| **ElevenLabs Sound Effects** | Custom sound design generation |
| **DaVinci Resolve 19** | Color grading, sound mixing, finishing |
| **Custom prompt engineering** | Cross-scene consistency and AI bias mitigation |

---

## Methodology

The production followed a structured iteration cycle inspired by analytics workflows:

1. **Brief decomposition** — Translating creative direction into measurable specifications (frame composition, color values, audio layers)
2. **Systematic generation** — Producing each clip independently with locked variables (character consistency, wardrobe, lighting)
3. **Validation against scopes** — Using DaVinci waveform and vectorscope readings to ensure exposure and color continuity
4. **Iteration on failures** — Identifying AI model biases and pivoting strategy (e.g., splitting scenes when the model overrode prompt instructions)
5. **Layered finishing** — Applying multi-track sound design, color grade, and tempo adjustments in post-production

---

## Key Technical Challenges Solved

### Challenge 1 — Character Consistency Across 11 Clips
AI video models reinterpret character features between generations. Solution: built a locked character description with reference photo binding, repeated identity specifications across all prompts, validated facial features frame-by-frame.

### Challenge 2 — Color Continuity Between AI-Generated Clips
Each AI generation outputs slightly different exposure values that look correct in isolation but break continuity when sequenced. Solution: applied node-based color correction in DaVinci Resolve, reading waveform scopes to balance exposure across all clips against a single reference.

### Challenge 3 — Model Bias on Object-Subject Interaction
The video model consistently placed Nike boots on the character's feet despite explicit negative prompts (the model associated "person + boots in scene" with "person wearing boots"). Solution: split the problematic scene into two separate clips — one with character without boots in frame, one with boots without character body in frame — joined invisibly in post-production with a match cut.

### Challenge 4 — Sound Design Without Native Audio
Most AI-generated audio was unusable for premium commercial output. Solution: muted native audio across all clips and rebuilt the sound design from scratch using five layers — sub-bass spine, ambient textures, diegetic sound effects, strategic silences, and a single moment of expansion at the climax.

---

## What This Project Demonstrates

- **Systems thinking applied to creative work:** Treating creative briefs as measurable specifications rather than abstract inspiration
- **Tool-agnostic methodology:** The ability to operate multiple AI tools as components of a unified workflow
- **Failure recognition and pivot strategy:** Identifying when AI models are failing silently and adapting the production approach
- **Quality control through measurement:** Using technical scopes and metrics rather than subjective judgment alone
- **Multi-disciplinary execution:** Merging the analytical rigor of data work with the creative output of brand commercial production

---

## About the Author

**Carlos Moreno Henao**  
Data Analyst & Marketing Strategist | Business Intelligence & AI Automation  
Bilingual (English/Spanish) | NCAA D-II Student-Athlete | Quincy University

I bridge analytical rigor and creative execution. My background combines a Business Management & Marketing degree with technical expertise in SQL, Tableau, Python, and R — alongside production experience in sports media and digital content strategy.

This project represents my belief that the most valuable professionals in the next decade will be those who can apply systems thinking to creative output, not those who specialize in only one side of the equation.

**Currently OPT-eligible and based in Kansas City, MO. Open to data analyst and AI-driven marketing roles.**

---

## Connect

- **LinkedIn:** [linkedin.com/in/carlosmorenohenao](https://linkedin.com/in/carlosmorenohenao)
- **Portfolio:** [carlosmoreno-portafolio.netlify.app](https://carlosmoreno-portafolio.netlify.app)
- **Email:** carlosmhen@gmail.com

---

## License

This project is shared for portfolio and educational purposes. The Nike brand, Phantom 6 Elite product, and Nike trademarks shown in the commercial are property of Nike, Inc. This is a non-commercial speculative project (spec ad) and is not affiliated with, sponsored by, or endorsed by Nike, Inc.
