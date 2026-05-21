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

### Step 4 — Select 2 Strongest Creative Routes
Think critically before deciding. Do not default to the first two ideas. Select the 2 strongest, most usable, most test-worthy creative routes for this specific product and angle.

**Option 1** = the strongest likely winner — clearest proof of the angle, most immediately readable, lowest AI-rendering risk.

**Option 2** = the strongest alternative route — must differ meaningfully from Option 1 on at least two of:
- Model age or build
- Setting type (indoor vs outdoor, or different location)
- Pose and emotional moment
- Composition or framing

Strong routes to consider:
- Home mirror selfie (bedroom or hallway, natural window light)
- Coffee at home (kitchen, morning light)
- Front doorway (about to head out)
- Quiet café seated (intimate, unhurried)
- Relaxed outdoor walk or errand moment

Do not default to all outdoor settings. Do not produce two versions of the same concept. The 2 options must be genuinely different visual routes.

### Step 5 — Build 2 Complete Prompts
For each of the 2 selected routes, write a full image generation prompt using:
- The product accuracy description from Step 1 (same in every prompt — do not change the garment)
- The specific setting, model, pose, and moment for that option
- Brand visual rules from brand-visual-rules.md
- Target customer rules from target-customer-rules.md
- Overlay and safe zone rules from overlay-and-safe-zone-rules.md
- Realism rules

Embed the most important negative instructions at the end of each prompt as natural language — do not write a separate negative prompt block.

Include at minimum:
- No plastic skin, no hyper-smooth AI surfaces
- No altered garment or product changes
- No editorial model energy, no catalogue posing
- No commercial fashion-shoot lighting, no studio lighting, no cinematic shallow depth of field used as a style choice
- No overly symmetrical or heavily art-directed composition
- No luxury campaign feel, no Gen Z styling
- No studio background, no fake logos, no cheap graphics

Each prompt should also include a positive realism anchor — a phrase that directs the generator toward capture realism, such as: "authentic smartphone-photo feel", "candid friend-shot quality", "natural household window light", "slightly imperfect framing", "captured moment, not staged shoot".

Each prompt must stand alone. A person should be able to copy any single prompt and paste it directly into an image generator without needing any other context.

### Step 6 — Output
Deliver the output using the compact structure in static-output-template.md.

Output should be compact: short product read, 5 ready-to-paste prompts, short recommendation.

---

## Output Format

Output should be compact: short product read, 2 ready-to-paste prompts, short recommendation.

Every output follows the structure in static-output-template.md:
1. Short product read — category, key details to protect, selected angle
2. Two ready-to-paste prompts — each with an overlay hook, the full prompt, and 1–2 sentence rationale
3. Recommended first test — one choice with a brief reason

Each prompt is copyable directly into Nano Banana, ChatGPT Images, Higgsfield, or any comparable image generator. Negative instructions are embedded inside each prompt — there is no separate negative prompt block.

---

## Core Priority Order

When any conflict exists, follow this priority:

1. Product accuracy — never change the garment
2. Target customer believability — real woman, not model
3. Scene realism — real Australian setting
4. Brand visual tone — calm, premium-lite, trustworthy
5. Overlay placement and safe zones

---

## Performance Rules

This system is not creating beautiful AI fashion art. It is creating testable Meta ad static prompts.

- Every option must test the same angle through a different believable customer moment
- Do not make the two options random — each must be a controlled variation with a clear visual hypothesis
- The image must stop the scroll AND communicate the buying reason in the same frame
- The viewer should feel: "I could wear that in real life" — not "that looks like an ad"
- Realism is a performance variable. Plastic skin, commercial lighting, polished composition, and editorial styling kill trust and conversion
- Capture realism is a performance variable. An image that feels captured in real life outperforms an image that looks produced, even when the produced image is technically better
- The target quality level is: a great candid photo taken by a friend with a good phone — not a professional shoot, not a bad selfie

---

## Model Variation Rules

Use these three age bands. Default to Band B for Option 1. Use a different band for Option 2.

| Band | Age appearance | Use for |
|---|---|---|
| A | 35–42 | Younger end of target — busy, active, family or career life |
| B | 43–49 | Core target — most relatable to the majority of the audience |
| C | 50–55 | Upper end — often underrepresented, high relatability for that segment |

Body type: vary between the 2 options — do not use identical builds for both. Use average, petite, fuller/curvier, or slightly taller.

Ethnicity: use a realistic Australian range — Anglo-Celtic, Southern European, East Asian, or mixed. Do not use the same background for both options.

---

## Creative Variation Rules

Across the 2 options, vary:
- Model age band (A, B, or C — default Band B for Option 1, different for Option 2)
- Body type (do not use the same build for both)
- Setting — include at least one indoor/domestic option across the 2 routes
- Pose and body language — candid, real-life moments preferred over catalogue poses
- Emotional moment (purposeful, relaxed, paused, self-checking in mirror, mid-movement)
- Overlay hook (optional — include when it strengthens the concept, omit when not needed)

Keep consistent across both options:
- Same product — same garment, same colour, same details
- Same buying reason — same angle
- Same Cavaro brand feel — calm, warm, real, premium-lite
- Same product accuracy rules
- Same Australian setting requirement

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
