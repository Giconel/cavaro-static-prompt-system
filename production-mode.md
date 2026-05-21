# Cavaro Static Prompt System — Production Mode

Compact daily-use operating file. Use this instead of reading the full system for every production run.

---

## Inputs

1. Uploaded product photo
2. Static angle in text

Do not ask for anything else before generating the output.

---

## Output Format

Always produce exactly this structure. Nothing more.

**1. Short Product Read**
- Product: category — colour — fabric — key details to protect
- Protect: 2–3 details most likely to be misrendered
- Angle: the selected buying reason in plain language

**2. Five Ready-to-Paste Static Prompts**

For each option include only:
- Option name
- Overlay hook
- Ready-to-paste prompt
- Why this option (1–2 sentences)

**3. Recommended First Test**
One option choice with 2–3 sentence explanation.

---

## Rules

### 1. Product Accuracy
Use the uploaded product photo as the ONLY source for the garment. Do not change colour, fabric, texture, fit, neckline, sleeves, buttons, silhouette, length, proportions, pattern, or any visible details. Product accuracy is more important than image beauty.

Read the product carefully before writing any prompt. Identify: category, colour, fabric, fit, silhouette, neckline, sleeves, closures (number, size, colour), length, pattern or print, and all other visible details.

Do not guess unclear details. Do not simplify to make the prompt shorter. Do not change the colour because it is hard to render.

### 2. Brand Direction
Cavaro should feel calm, trustworthy, feminine, polished, realistic, and premium-lite.

It must not feel like: fast fashion, Gen Z styling, AliExpress, Shein, cheap dropshipping, influencer glam, luxury campaign, or editorial fashion photography.

### 3. Target Customer
Realistic Australian women aged 35–55. She looks like a real customer, not a professional model.

- Natural skin texture — pores, fine lines, subtle imperfections are correct
- Normal body proportions — not model-thin, not exaggerated
- Relaxed expression — candid, not posed
- Minimal makeup — no full glam, no contouring
- Believable hair — natural, not editorial
- Approachable presence — not aspirational fantasy

### 4. Creative Style
UGC-style but premium and ad-worthy. The image should feel like a natural phone photo taken by a friend, not a studio shoot.

- Realistic smartphone perspective
- Natural daylight with slight imperfections
- Subtle motion and believable shadows
- Authentic lifestyle setting
- The final image must look like an original lifestyle photo, not an AI render

### 5. Setting
Use believable Australian outdoor or everyday lifestyle settings. Choose one that fits the angle and product.

Approved settings:
- Inner-city café strip
- Suburban high street
- Weekend farmers market
- Beachside esplanade
- Residential street with established gardens
- Local shopping village
- Calm city laneway

Background must feel real and lived-in: natural depth, imperfect textures, real pavement, Australian architecture, native greenery, parked cars, shopfronts, or subtle passers-by in the distance.

Avoid: fake studio, empty showroom, luxury hotel, overly aesthetic influencer backgrounds, tropical or overseas locations.

### 6. Composition
- Vertical 9:16, 1080×1920
- Subject clearly visible, product is the visual focus
- Natural candid crop, slightly imperfect framing
- Enough background context to make the scene believable
- Keep outfit easy to see — do not crop important product details

### 7. Safe Zones
- Top 400px — no text
- Bottom 400px — no text
- Left and right 150px — no text
- All overlay text must stay inside the centre safe area only

### 8. Text Overlay
Each option must include one short hook-style overlay matching the selected angle. Usually 4–6 words maximum. It must communicate one clear buying reason.

- Premium, clean typography — elegant serif or clean modern sans
- Soft neutral colours: cream, warm white, charcoal, or muted beige
- Never use loud sale graphics, emojis, stickers, Canva effects, or discount-banner styling
- Write a real hook for every option — do not use placeholders
- Each of the 5 options should test a different hook

Good hook tone: "Dressed in under five minutes." / "The layer that goes with everything." / "Still wearing this at 4pm."

Wrong hook tone: "Shop our new arrivals!" / "Feel amazing today!" / "Limited stock!"

### 9. Ad Psychology
Each image must communicate one clear buying reason: comfort, flattering fit, easy styling, confidence, everyday polish, warmth, or getting dressed made easier.

The emotion must be subtle and believable. The viewer should feel: "I could wear that in real life."

### 10. Realism Rules
- Natural skin texture must remain visible
- Fabric must show realistic folds, weight, and movement
- Lighting must be imperfect but flattering
- Background must be realistic and continuous
- No plastic skin
- No hyper-smooth AI surfaces
- No distorted hands — choose poses that reduce hand complexity
- No fake logos, supplier branding, or watermarks
- No random accessories unless they fit the setting naturally
- No product changes of any kind

### 11. Five-Option Variation Rules
The 5 options test the same product and same angle through 5 different realistic customer moments.

Vary across the 5 options:
- Model age (within 35–55)
- Body type (average, petite, fuller/curvier, slightly taller)
- Setting
- Pose and body language
- Composition (full body, three-quarter, close crop)
- Camera feel and emotional moment
- Product framing
- Overlay hook

Keep the same across all 5 options:
- Product — same garment, same colour, same details
- Angle — same buying reason
- Cavaro brand feel — calm, warm, real, premium-lite
- Australian setting requirement

Do not make the options random. Each must be a controlled variation of the same buying reason.

### 12. Model Variation
Distribute across these three age bands across the 5 options. Cover all three bands. Band B (43–49) should appear at least twice.

| Band | Age | Notes |
|---|---|---|
| A | 35–42 | Younger end — busy, active, family or career |
| B | 43–49 | Core target — most commercially important |
| C | 50–55 | Upper end — underrepresented, high relatability |

Body types across 5 options: average (×2 minimum), petite (×1), fuller/curvier (×1), slightly taller (×1).

Ethnicity: rotate across a realistic Australian range — Anglo-Celtic, Southern European, East Asian, or mixed. Do not use the same background in every option.

Avoid: overly young faces, heavy makeup, influencer glam, editorial posing, unrealistic bodies.

### 13. Recommended First Test
After the 5 options, choose the strongest one for first Meta CBO testing.

Choose based on:
- Product visibility and angle clarity
- Believable Australian 35–55 customer moment
- Product accuracy risk (choose the lowest-risk prompt first)
- Realistic UGC feel over editorial feel
- Likelihood of a real-looking result from an image generator

Explain in 2–3 sentences only.

### 14. Compact Output Rules
- Do not explain the repository
- Do not summarise the system
- Do not include strategy sections or long visual reads
- Do not include long final checklists
- Do not include separate long negative prompts under every option
- Integrate only the most important negative instructions naturally inside each ready-to-paste prompt
- Do not mention which system files were used
- Only generate the final output in the required compact format

The most important negative instructions to embed in every prompt:
No plastic skin. No altered garment. No editorial model energy. No Gen Z styling. No studio background. No fake logos or watermarks. No cheap graphics.

Add product-specific negatives where the garment has high-risk details (e.g. button count, print, sleeve style, open front, length).

---

## Daily Use Prompt

Copy this prompt when starting a new production session in Claude Code Web.

```
Use production-mode.md as the Cavaro Static Prompt System.

Production mode:
Do not summarize the repository.
Do not explain the system.
Do not rewrite the rules.
Only generate the final output.

Input:
Product photo: uploaded
Static angle: [INSERT ANGLE HERE]

Output only:
1. Short Product Read
2. Five Ready-to-Paste Static Prompts
3. Recommended First Test

Each of the 5 static prompt options must include only:
- Option name
- Overlay hook
- Ready-to-paste prompt
- Why this option

Rules:
Use the uploaded product photo as the only source for the clothing product.
Keep the product completely accurate.
Adapt model, styling, and setting to Australian women aged 35–55.
Do not keep the original PDP model styling if it does not fit the target customer.
The five options should test the same buying reason through different realistic customer moments.
Keep the output practical and compact.
Do not include long strategy sections, long checklists, or separate long negative prompts.
Integrate only the most important negative instructions naturally inside each ready-to-paste prompt.
```
