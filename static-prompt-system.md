# Cavaro Static Prompt System

## What This System Does

This system takes two inputs and produces 5 complete, ready-to-paste image generation prompts for Meta ad static testing.

It is built for real CBO ad testing — not creative exploration, not AI art, not editorial photography.

Every output should look like a premium UGC lifestyle photo that a real customer could have taken.

The 5 prompts test the same product and the same angle through 5 distinct visual routes. This gives you real creative options to generate, compare, and test — not 5 versions of the same idea.

---

## Required Inputs

1. **Product photo** — the uploaded image of the garment
2. **Static angle** — the single buying reason or ad angle to target

That is all. Do not ask for more information before generating the output.

---

## System Process

When given the two inputs, follow this process in order:

### Step 1 — Visual Product Read
Analyse the uploaded product photo. Identify and record:
- Product category (e.g. blouse, cardigan, dress, pants)
- Primary colour and any secondary colours
- Fabric type and visible texture
- Fit (e.g. relaxed, fitted, oversized)
- Silhouette
- Neckline
- Sleeve length and style
- Buttons, zips, or closures
- Length (e.g. hip, midi, full length)
- Pattern or print (if any)
- Any other visible and notable details

This read becomes the product accuracy anchor for the entire prompt.

### Step 2 — Angle Interpretation
Take the provided static angle and identify:
- The core emotion or buying reason it targets
- The type of woman and moment it speaks to
- What the image must communicate visually
- What the image must avoid

### Step 3 — Static Strategy
Define the creative hypothesis before writing any prompts:
- What must be proven in the image for this angle to work?
- What does the target customer need to feel when she sees it?
- What is the single most important visual element to get right?

### Step 4 — Plan 5 Distinct Creative Routes
Before writing any prompts, map out 5 meaningfully different approaches for the same product and angle. Each route must vary on at least three of:
- Model age (within 35–55)
- Model appearance and body type
- Setting and location
- Pose and body language
- Composition and framing
- Emotional moment
- Product framing (full body, three-quarter, close composition)
- Overlay hook

Do not create 5 versions of the same concept. Each option should be a genuinely different visual route.

### Step 5 — Build 5 Complete Prompts
For each of the 5 creative routes, write a full image generation prompt using:
- The product accuracy description from Step 1 (same in every prompt — do not change the garment)
- The specific setting, model, pose, and moment for that option
- Brand visual rules from brand-visual-rules.md
- Target customer rules from target-customer-rules.md
- Overlay and safe zone rules from overlay-and-safe-zone-rules.md
- Realism rules

Each prompt must stand alone. A person should be able to copy any single prompt and paste it directly into an image generator without needing any other context.

### Step 6 — Negative Prompt
Add the standard negative prompt from negative-prompt-rules.md to every option. Add any product-specific additions where relevant.

### Step 7 — Output
Deliver the full output using the structure in static-output-template.md.

---

## Output Format

Every output must follow the exact structure in static-output-template.md.

Each of the 5 ready-to-paste prompts must be copyable directly into Nano Banana, ChatGPT Images, Higgsfield, or any comparable image generation tool.

The output ends with a recommended first test — identifying which of the 5 options to generate first and why.

---

## Core Priority Order

When any conflict exists, follow this priority:

1. Product accuracy — never change the garment
2. Target customer believability — real woman, not model
3. Scene realism — real Australian setting
4. Brand visual tone — calm, premium-lite, trustworthy
5. Overlay placement and safe zones

---

## Files In This System

| File | Role |
|---|---|
| static-prompt-system.md | Master instructions (this file) |
| product-accuracy-rules.md | How to read and protect the product |
| brand-visual-rules.md | Cavaro visual identity rules |
| target-customer-rules.md | Who the woman in the image is |
| scene-and-setting-rules.md | How to choose settings |
| overlay-and-safe-zone-rules.md | Format, safe zones, typography |
| negative-prompt-rules.md | What to exclude from every prompt |
| static-output-template.md | The exact output structure |
| example-static-outputs.md | Two worked examples |
