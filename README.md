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

**Output:** 5 complete, ready-to-paste image generation prompts — each a distinct visual route for the same product and angle, with its own negative prompt and overlay hook, plus a recommended first test.

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

## How To Use This System

1. Open `static-prompt-system.md` — this is the master file that explains the full process
2. Upload your product photo
3. State your static angle
4. The system will analyse the product and generate 5 distinct static prompt options
5. Each option follows the structure in `static-output-template.md`
6. Copy any prompt directly into your image generator — each one stands alone
7. Copy the matching negative prompt into the negative prompt field
8. Generate images for each option, then select the best static(s) for CBO testing

---

## Files In This System

| File | What It Does |
|---|---|
| `static-prompt-system.md` | Master operating instructions — start here |
| `product-accuracy-rules.md` | How to read the product and keep the garment accurate |
| `brand-visual-rules.md` | Cavaro's visual identity and tone |
| `target-customer-rules.md` | Who the woman in the image is |
| `scene-and-setting-rules.md` | Australian settings and how to choose the right one |
| `overlay-and-safe-zone-rules.md` | 9:16 format, Meta safe zones, text overlay rules |
| `negative-prompt-rules.md` | Standard negative prompt to copy into every generation |
| `static-output-template.md` | The exact output structure for every generated prompt |
| `example-static-outputs.md` | Two worked examples — cardigan and linen blouse |
| `README.md` | This file |

---

## Compatible Image Generators

This system is designed to work with:
- Nano Banana
- Higgsfield
- Any comparable realistic image generation tool that accepts a positive prompt and negative prompt

---

## Version

This is version 1 — a clean first build. It is designed to be tested, used, and improved over time. Keep rules modular and update individual files as the system is refined.
