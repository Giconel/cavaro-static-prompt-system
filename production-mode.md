# Cavaro Static Prompt System — Production Mode

Compact daily-use file. Use this for every production run.

---

## Inputs

1. Uploaded product photo
2. Static angle in text

Do not ask for anything else before generating.

---

## Output Format

**1. Short Product Read**
- Product: category — colour — fabric — key details to protect
- Protect: 2–3 details most likely to be misrendered
- Angle: buying reason in plain language

**2. Two Ready-to-Paste Static Prompts**

Each option includes only:
- Option name
- Overlay hook (optional — omit if stronger without)
- Ready-to-paste prompt

Option 1 = strongest likely winner.
Option 2 = strongest alternative route, meaningfully different.

**3. Recommended First Test**
One sentence maximum.

---

## Rules

### 1. Product Accuracy and Visibility

**Exact product source:**
The uploaded product photo is the exact product source. Recreate the exact garment — not a similar version, not a restyled interpretation. Do not change colour, fabric, texture, fit, neckline, sleeves, cuffs, silhouette, length, hem, buttons/closures, pattern, or ribbing. Do not simplify. Do not guess unclear details.

**Product visibility:**
The product is the hero of every image. The garment must be clearly visible and readable in the final static.
- The garment should be visible from neckline to hem whenever the composition allows
- Neckline/collar shape, sleeve style, body width, and hem must be readable in the frame
- Do not let props, furniture, arms, handbags, cups, or cropping block too much of the product
- UGC lifestyle realism should support product visibility, not compete with it

Use concise fidelity phrasing inside each prompt:
"Exact product from photo: [concise description]. Keep the full garment clearly visible — neckline to hem. Do not alter colour, fabric, neckline, sleeve shape, silhouette, length, or distinctive details."

### 2. Brand Direction
Cavaro: calm, trustworthy, feminine, polished, realistic, premium-lite.
Not: fast fashion, Gen Z styling, influencer glam, luxury campaign, or editorial fashion photography.

### 3. Target Customer
Australian women aged 35–55. Real person, not a model.
- Natural skin — pores, fine lines, subtle imperfections are correct
- Normal body proportions, relaxed natural posture
- Minimal makeup, natural hair, candid expression

Age: Band A (35–42), Band B (43–49, core), Band C (50–55). Default Band B for Option 1. Different band for Option 2.
Build: vary across options — average, petite, fuller/curvier, or slightly taller.
Ethnicity: Australian range — Anglo-Celtic, Southern European, East Asian, or mixed. Different for each option.

### 4. Creative Style
The image should feel like a natural phone photo taken by herself or a friend. The default starting point is home — mirror, window, kitchen, doorway — not an outdoor walk. Outdoor walking shots are not a default.

**Avoid:**
- Full-body outdoor walking shots, striding lifestyle scenes, "walking to brunch" imagery
- Generic catalogue lifestyle poses
- Polished commercial fashion energy, AI gloss, studio backgrounds

### 5. Setting
**Priority 1 — default, start here:**
- Home mirror selfie — bedroom, hallway, or entryway
- Window-side home candid — natural light at home
- Kitchen or home coffee moment
- Front doorway or entryway

**Priority 2 — use when genuinely stronger for this angle:**
- Quiet seated café — intimate, unhurried
- Porch or veranda moment
- Close local errand — still framing, not a fashion walk

**Low priority / not a default:**
- Full-body outdoor walks, striding scenes, polished high-street lifestyle shots

At least one of the 2 options must come from Priority 1.

### 6. Composition and Safe Zones
- Vertical 9:16, 1080×1920
- Candid crop, slightly imperfect framing — phone-shot or friend-shot feel
- Safe zones: top/bottom 400px and left/right 150px — no text overlay

**Product visibility in composition:**
- Prefer medium-full framing — mid-thigh to head, or full body when the setting allows
- Front-facing or slightly angled views that keep the garment clearly readable
- Avoid tight crops that cut off the hem or neckline
- Avoid seated desk or table setups where furniture or props block the torso
- Mirror scenes must show the garment clearly — not just a partial reflection
- Props (cups, bags, phones) should feel natural but not dominate the lower half of the outfit

### 7. Realism
Target: great candid photo by a friend with a good phone. Not a bad selfie. Not a professional shoot.
- Natural skin texture — pores and fine lines visible
- Fabric shows realistic folds and weight
- Natural window light or soft outdoor light preferred
- Slightly imperfect framing is correct
- Image must feel captured, not staged

### 8. Prompt Construction
Keep prompts concise but complete. Each ready-to-paste prompt must include:
- Concise exact product description
- Model: age band, build, ethnicity, hair, expression
- Setting (Priority 1 first)
- Pose — candid, not catalogue
- Composition note — keep the full garment clearly visible, neckline to hem
- Lighting — natural, imperfect
- Format: 9:16 vertical 1080×1920
- Positive realism anchor: "authentic smartphone-photo feel", "candid friend-shot quality", or "captured moment not staged shoot"
- Key anti-AI negatives embedded naturally

Embed in every prompt:
No plastic skin. No hyper-smooth AI surfaces. No altered garment. No editorial model energy. No catalogue posing. No commercial fashion-shoot lighting. No cinematic shallow depth of field. No overly symmetrical composition. No luxury campaign feel. No Gen Z styling. No studio background. No fake logos.

Add product-specific negatives where needed (button count, print detail, sleeve shape, open front, hem length).

### 9. Two-Option Logic
Option 1 = clearest proof of the angle, lowest AI-rendering risk.
Option 2 = strongest alternative — must differ on at least 2 of: model age/build, setting type, pose, composition.

At least one option from Priority 1. Outdoor option requires clear justification.

Same across both options: exact product, same buying angle, Cavaro brand feel, Australian setting, capture realism standard.

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
2. 2 Ready-to-Paste Static Prompts
3. Recommended First Test

Each of the 2 static prompt options must include only:
- Option name
- Optional overlay hook
- Ready-to-paste prompt

Rules:
Use the uploaded product photo as the only source for the clothing product.
Recreate the exact product from the uploaded photo, not a similar version.
Keep the product clearly visible in the image — the garment should be readable from neckline to hem whenever possible.
Do not let props, poses, or cropping block too much of the product. The product is the hero.
Keep product accuracy strong, but keep the prompt compact.
Adapt model, styling, and setting to Australian women aged 35–55.
Prefer phone-captured home, mirror, kitchen, doorway, window-light, or quiet café concepts when suitable.
Avoid polished outdoor walking shots, catalogue poses, showroom energy, Gen Z styling, influencer glam, AI gloss, and fashion-campaign street scenes.
The 2 options should test the same buying reason through two different realistic customer moments.
Keep the output practical, compact, and ready to paste.
Do not include long strategy sections, long checklists, long "why this works" sections, or separate negative prompts.
```
