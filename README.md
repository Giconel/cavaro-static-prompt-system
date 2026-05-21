# Cavaro Static Prompt System

A reusable image prompt generation system for Cavaro — an Australian women's fashion brand targeting women aged 35–55.

This system turns two inputs into a ready-to-paste image generation prompt for Meta ad testing.

---

## What This System Does

It generates realistic, premium UGC-style image prompts for Meta ad statics.

It does not write ad copy. It does not create headlines. It does not write primary text.

Its only job is to produce a high-quality image prompt that can be dropped into an AI image generator and produce a believable, brand-accurate lifestyle photo suitable for Meta CBO testing.

---

## Two Inputs. Five Outputs.

**Input 1:** A product photo (uploaded image of the garment)

**Input 2:** A static angle (the single buying reason the ad is built around)

**Output:** 5 complete, ready-to-paste image generation prompts — each a distinct visual route for the same product and angle, with an overlay hook and embedded negative instructions, plus a recommended first test. Output is compact: short product read, 5 prompts, short recommendation.

---

## Basic Workflow

```
Product photo + Static angle
        ↓
Static Prompt System
        ↓
5 ready-to-paste image prompt options
        ↓
Image generator (Nano Banana / ChatGPT Images / Higgsfield / other)
        ↓
Generate each option — pick the best image per option
        ↓
Select strongest static(s) for testing
        ↓
Adcopy system (separate repository)
        ↓
Primary text + headline
        ↓
Meta CBO test
```

---

## This Repository vs The Adcopy System

This repository handles **image creation only**.

The Cavaro adcopy system (separate repository) handles primary text, headlines, and ad copy — and is used only after a static has been selected from this system.

Do not mix the two. The image prompt system comes first. The adcopy system comes second.

---

## Fast Production Mode

For daily prompt generation, use `production-mode.md` — not the full system files.

`production-mode.md` is a compact standalone file that contains all the rules needed to generate 5 ready-to-paste static prompts in one session. It is designed to run fast in Claude Code Web without loading the full repository.

**Daily use prompt for Claude Code Web:**

> Use production-mode.md as the Cavaro Static Prompt System. Product photo: uploaded. Static angle: [INSERT ANGLE HERE]. Output only: Short Product Read, Five Ready-to-Paste Static Prompts, Recommended First Test.

**When to use the full system files:**
Use the individual rule files (`brand-visual-rules.md`, `target-customer-rules.md`, etc.) only when improving, debugging, or expanding the system — not for daily production runs.

If a rule is updated or improved in the full system files, add the most important version of that rule to `production-mode.md` as well to keep the production file current.

---

## How To Use This System

1. Open `production-mode.md` for daily prompt generation (fast)
2. Or open `static-prompt-system.md` for the full system process
3. Upload your product photo
4. State your static angle
5. The system generates 5 distinct static prompt options
6. Copy any prompt directly into your image generator — each one stands alone, with negatives embedded
7. Generate images for each option, then select the best static(s) for CBO testing

---

## Files In This System

| File | What It Does |
|---|---|
| `production-mode.md` | **Daily use** — compact standalone operating file, start here for production runs |
| `static-prompt-system.md` | Full system process and master instructions |
| `product-accuracy-rules.md` | How to read the product and keep the garment accurate |
| `brand-visual-rules.md` | Cavaro's visual identity and tone |
| `target-customer-rules.md` | Who the woman in the image is |
| `scene-and-setting-rules.md` | Australian settings and how to choose the right one |
| `overlay-and-safe-zone-rules.md` | 9:16 format, Meta safe zones, text overlay rules |
| `negative-prompt-rules.md` | Standard negative prompt reference |
| `static-output-template.md` | The exact output structure for every generated prompt |
| `example-static-outputs.md` | Two worked examples — cardigan and linen blouse |
| `README.md` | This file |

---

## Compatible Image Generators

This system is designed to work with:
- Nano Banana
- ChatGPT Images (GPT-4o)
- Higgsfield
- Any comparable realistic image generation tool that accepts a positive prompt and negative prompt

---

## Key Design Principles

**Five options, not five versions of the same thing.**
Each of the 5 prompts varies by model age band, body type, setting, pose, composition, and overlay hook. The goal is controlled creative variation, not random generation.

**Product accuracy above everything.**
The garment description is identical across all 5 prompts. The product does not change. The scene, model, and moment change.

**Performance first.**
Every prompt is built to produce a testable Meta ad static — not a beautiful AI image. Realism, believability, and buying-reason clarity are the metrics.

---

## Version

v4 — Authentic candid visual direction added. Domestic/mirror settings added. Overlay made optional. Exact product fidelity rules strengthened. Core 5-prompt workflow unchanged.
