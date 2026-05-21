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

**2. Two Ready-to-Paste Static Prompts**

Option 1 = strongest likely winner for this product and angle.
Option 2 = strongest alternative route, meaningfully different from Option 1.

For each option include only:
- Option name
- Overlay hook (optional — omit if the concept is stronger without text)
- Ready-to-paste prompt
- Why this option (1–2 sentences)

**3. Recommended First Test**
One option choice with 2–3 sentence explanation.

---

## Rules

### 1. Product Accuracy
Use the uploaded product photo as the ONLY source for the garment. Do not change colour, fabric, texture, fit, neckline, sleeves, buttons, silhouette, length, proportions, pattern, or any visible details. Product accuracy is more important than image beauty.

Read the product carefully before writing any prompt. Identify and describe: category, colour, fabric and texture, fit, silhouette, neckline/collar/turtleneck shape, sleeve shape, cuff shape, hem shape, side vents or splits, length (in body terms), proportions, drop shoulder or shoulder line, oversized vs fitted level, closures (number, size, colour), pattern/cable knit/ribbing/weave details, overall garment structure.

**Exact product fidelity rules:**
- Reproduce the exact product — not a similar version, not a restyled interpretation, not a "close enough" knit
- Do not simplify the product into a more generic sweater, cardigan, knit, fleece, or top
- Do not normalize unusual features — if the product has an exaggerated silhouette, high-low hem, side split, chunky knit, cable pattern, or wide sleeve, those must remain clearly visible
- Do not make an oversized garment look fitted or tailored
- Do not remove or soften distinctive details because they are hard to render

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
More authentic, more candid, more believable — less catalogue, less polished, less generic lifestyle.

The preferred direction is mature-woman iPhone-style fashion content. The image should feel like a natural phone photo taken by herself or a friend — not a studio shoot, not a lookbook, not a lifestyle catalogue.

The default starting point is home. Consider home mirror selfies, kitchen coffee moments, window-light home candids, and entryway shots before outdoor options. Outdoor walking shots are not a default — they must be clearly the strongest route for the angle to be used.

- Realistic smartphone perspective, natural and slightly imperfect
- Natural and flattering but imperfect light — window light, soft morning light, open outdoor shade
- Believable everyday environment — home, local street, doorstep, quiet café
- Casual self-shot or friend-shot energy — not art directed
- Subtle motion, realistic shadows, authentic moment
- The final image must look like an original photo, not an AI render
- More direct-response energy — the product and buying reason are immediately visible
- The viewer should feel: "she's just like me" — not "that's aspirational"

**Actively avoid:**
- Generic catalogue lifestyle poses
- Full-body outdoor walking shots used as a default route
- Model striding down a pavement with fashion-walk energy — "walking to brunch" imagery
- Polished outdoor commercial lifestyle framing
- Overly polished commercial fashion energy
- Overly clean or art-directed backgrounds
- "Pinterest pretty" images with no ad intent
- Images that feel more like a lookbook than a performance static

### 5. Setting
Use believable Australian everyday settings. Default strongly toward home and intimate settings before considering outdoor options.

**Priority 1 — Home and intimate settings (default first consideration)**
Start here. These produce the most believable, phone-captured, performance-static energy.
- Home mirror selfie — bedroom, hallway, or entryway mirror, natural window light from side
- Window-side home candid — standing or seated near natural light in a real, lived-in home
- Kitchen or home coffee moment — domestic, morning window light
- Seated home candid — relaxed, mid-moment in a real home setting
- Front doorway or porch — about to head out, natural outdoor light in front

**Priority 2 — Quiet everyday settings**
Use when genuinely stronger than a home option for the selected angle.
- Quiet seated café moment — intimate table, soft interior or window light
- Residential street with established gardens — still or near-still, not a walk
- Inner-city café strip

**Low priority / not a default**
High risk of producing polished catalogue imagery. Only use when clearly the strongest option.
- Full-body outdoor walking shots
- Striding lifestyle scenes — "walking to brunch," high-street fashion-walk energy
- Weekend farmers market
- Beachside esplanade
- Local shopping village
- Calm city laneway

Background must feel real and lived-in. For indoor settings: real home, natural light from windows, lived-in objects in background — not staged or showroom. For outdoor settings: natural depth, real pavement, Australian architecture, native greenery, parked cars, shopfronts, subtle passers-by.

Avoid: fake studio, empty showroom, luxury hotel, overly aesthetic influencer backgrounds, tropical or overseas locations, staged home interiors that look like a photoshoot.

### 6. Composition
- Vertical 9:16, 1080×1920
- Subject clearly visible, product is the visual focus
- Natural candid crop, slightly imperfect framing — she does not need to be dead-centre
- Real-camera or real-phone feeling — not a perfectly composed campaign shot
- Not overly symmetrical — slight subject offset, natural placement in frame
- Enough background context to make the scene believable
- Keep outfit easy to see — do not crop important product details
- The composition should feel like it was captured, not constructed

### 7. Safe Zones
- Top 400px — no text
- Bottom 400px — no text
- Left and right 150px — no text
- All overlay text must stay inside the centre safe area only

### 8. Text Overlay
Overlay is now optional. Prioritise image authenticity first. If a concept is stronger without text — especially home mirror or candid domestic options — omit the overlay.

When overlay is included:
- Short hook matching the selected angle — usually 4–6 words maximum
- Communicates one clear buying reason
- Premium, clean typography — elegant serif or clean modern sans
- Soft neutral colours: cream, warm white, charcoal, or muted beige
- Never use loud sale graphics, emojis, stickers, Canva effects, or discount-banner styling
- Each hook should be a different angle across the 5 options

Good hook tone: "Dressed in under five minutes." / "The layer that goes with everything." / "Still wearing this at 4pm."

Wrong hook tone: "Shop our new arrivals!" / "Feel amazing today!" / "Limited stock!"

Safe zone rule: if overlay is used, top 400px no text, bottom 400px no text, left and right 150px no text.

### 9. Ad Psychology
Each image must communicate one clear buying reason: comfort, flattering fit, easy styling, confidence, everyday polish, warmth, or getting dressed made easier.

The emotion must be subtle and believable. The viewer should feel: "I could wear that in real life."

### 10. Realism Rules
The target quality level: a great candid photo taken by a friend with a good phone. Not a professional fashion shoot. Not a bad selfie.

- Natural skin texture must remain visible — pores, fine lines, subtle imperfections are correct
- Fabric must show realistic folds, weight, and movement
- Lighting must be imperfect but flattering — natural daylight or household window light preferred
- Slightly uneven or imperfect lighting is acceptable — it adds authenticity
- Background must be realistic and continuous
- Capture feel: the image should feel captured in real life, not staged for a camera
- No plastic skin, no hyper-smooth AI surfaces
- No high-end commercial fashion lighting
- No cinematic shallow depth of field used as a stylistic choice
- No overly symmetrical or heavily art-directed composition
- No smooth polished AI sheen on any surface
- No luxury campaign or brand-shoot feel
- No distorted hands — choose poses that reduce hand complexity
- No fake logos, supplier branding, or watermarks
- No random accessories unless they fit the setting naturally
- No product changes of any kind

### 11. Two-Option Selection Rules
The 2 options test the same product and same angle through 2 meaningfully different realistic customer moments.

Think critically before deciding. Do not default to the first two ideas. Select the 2 strongest, most usable, most test-worthy creative routes for this specific product and angle.

**Option 1** is the strongest likely winner — the clearest proof of the angle, the most immediately readable, the lowest AI-rendering risk.

**Option 2** is the strongest alternative route — it must differ from Option 1 on at least two of:
- Model age or build
- Setting (indoor vs outdoor, or different location type)
- Pose and emotional moment
- Composition or framing
- Overlay hook

The 2 options must be meaningfully different creative routes, not minor variations of the same idea.

**Route selection — consider in this order:**

Priority 1 (default first consideration for most angles):
- Home mirror selfie — bedroom, hallway, or entryway, checking her look
- Kitchen or home coffee moment — relaxed domestic morning
- Window-light home candid — seated or standing near natural light at home
- Front doorway or entryway — about to head out, natural transition

Priority 2 (use when genuinely stronger for this angle):
- Quiet café seated — intimate, unhurried
- Still porch or veranda moment
- Close, believable local errand — still framing, not a fashion walk

Low priority / not a default:
- Full-body outdoor walking shots
- Striding or fashion-walk lifestyle scenes
- Polished outdoor commercial lifestyle imagery

At least one of the 2 options should come from Priority 1. A second outdoor option requires a clear reason why it outperforms a home concept for this specific angle.

Keep the same across both options:
- Product — same garment, same colour, same details (exact fidelity)
- Angle — same buying reason
- Cavaro brand feel — calm, warm, real, premium-lite
- Australian setting requirement
- Capture realism standard — candid, not staged

### 12. Model Selection
Choose the most appropriate age and build for each option. The 2 options should use different age or build profiles.

| Band | Age | Notes |
|---|---|---|
| A | 35–42 | Younger end — busy, active, family or career |
| B | 43–49 | Core target — most commercially important |
| C | 50–55 | Upper end — underrepresented, high relatability |

Default to Band B for Option 1. Use a different band or a different build type for Option 2.

Body types to use across the 2 options: vary between average, petite, fuller/curvier, or slightly taller — do not use identical builds for both.

Ethnicity: use a realistic Australian range — Anglo-Celtic, Southern European, East Asian, or mixed. Do not use the same background for both options.

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
No plastic skin. No hyper-smooth AI surfaces. No altered garment. No editorial model energy. No catalogue posing. No commercial fashion-shoot lighting. No cinematic shallow depth of field. No overly symmetrical or art-directed composition. No luxury campaign feel. No Gen Z styling. No studio background. No fake logos. No cheap graphics.

Add product-specific negatives where the garment has high-risk details (e.g. button count, print, sleeve style, open front, length).

Each prompt should also include a positive realism anchor such as: "authentic smartphone-photo feel", "candid friend-shot quality", "natural window light", "slightly imperfect framing", "captured moment not staged shoot".

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
Keep the product completely accurate — reproduce the exact product, not a similar or simplified version.
Adapt model, styling, and setting to Australian women aged 35–55.
Do not keep the original PDP model styling if it does not fit the target customer.
Generate only 2 options. Select the 2 strongest, most usable creative routes for this specific product and angle.
Option 1 = strongest likely winner. Option 2 = strongest alternative route, meaningfully different.
The 2 options should test the same buying reason through different realistic customer moments.
Default to home and intimate options first — mirror selfie, kitchen coffee moment, window-light home candid, doorway or entryway.
Only use an outdoor option if it is genuinely the strongest route for this angle. Outdoor walking shots are not a default.
Prefer authentic, phone-captured, real-life moments. Mirror-selfie and friend-shot energy is welcome.
Overlay is optional — omit it when the concept is stronger without text.
Keep the output practical and compact.
Do not include long strategy sections, long checklists, or separate long negative prompts.
Integrate only the most important negative instructions naturally inside each ready-to-paste prompt.
```
