# Product Accuracy Rules

## Core Rule

The uploaded product photo is the only source for the garment. Do not redesign it. Do not improve it. Do not approximate it. Reproduce it exactly.

Product accuracy is more important than a beautiful image.

---

## Exact Product Fidelity

The system must reproduce the exact product shown in the uploaded image — not a similar version, not a restyled interpretation, not a close-enough substitute.

Preserve every one of the following exactly as shown:

- **Colour** — exact colour, not a more photogenic approximation
- **Knit / fabric texture** — cable knit, ribbing, boucle, linen crinkle, woven texture, etc.
- **Neckline / collar / turtleneck shape** — the exact neckline, including height of a turtleneck or funnel
- **Sleeve shape** — straight, puff, flutter, balloon, dropped, wide — exactly as shown
- **Cuff shape** — ribbed, folded, wide, tapered, raw hem
- **Hem shape** — straight, curved, high-low, stepped, raw, ribbed
- **Side vents or splits** — if present, they must remain visible
- **Silhouette** — oversized, boxy, fitted, A-line, cocoon, wrap — as shown
- **Length** — described in body terms (hip, below hip, knee, midi, ankle, full length)
- **Proportions** — if the garment is exaggerated (very oversized, very cropped), keep that exaggeration
- **Drop shoulder / shoulder line** — if the garment has a drop shoulder or extended shoulder, preserve it
- **Oversized or fitted level** — do not normalize an oversized garment into a standard fit
- **Buttons / zip / hardware** — exact count, size, colour, and placement
- **Pattern / cable knit / ribbing / weave details** — describe precisely, do not smooth or simplify
- **Overall garment structure** — the weight, construction, and silhouette logic of the product

**The generator must not:**
- Simplify the product into a more generic sweater, cardigan, knit, fleece, or top
- Normalize unusual product features into conventional garment shapes
- Smooth out a distinctive texture into a plain knit
- Remove a high-low hem, side split, or exaggerated sleeve because it is hard to render
- Make an oversized garment look fitted or tailored
- Change the shoulder drop because it looks awkward in the scene

If the product has a distinctive feature — exaggerated proportions, unusual hem, chunky knit, cable pattern, wide sleeve, high turtleneck — that feature must be clearly visible in the final image. Do not hide it or soften it.

---

## Product Visibility

Product fidelity alone is not enough — the garment must also be clearly visible and readable in the final image.

**The product is the hero of every static.** The viewer must be able to read the garment at a glance. If the product is blocked, cropped, or hidden, the static fails regardless of how realistic the scene is.

**Visibility rules:**
- The garment should be visible from neckline to hem whenever the composition allows
- Neckline/collar shape, sleeve style, body width, and hem must be readable in the frame
- Do not let props, furniture, handbags, crossed arms, or tight crops block too much of the garment
- Mirror scenes must show the garment clearly — not just a partial or sliver reflection
- Seated compositions are acceptable when the garment is still readable — avoid desk or table setups that block the torso
- Props (cups, bags, phones) should appear naturally but must not cover key garment areas

**Preferred framing:**
- Medium-full: mid-thigh to head, or full body when the setting allows
- Front-facing or slightly angled — both preserve garment readability
- Three-quarter crop is acceptable only when it includes neckline through hem

**What to avoid:**
- Tight mid-body crops that cut off the neckline or hem
- Seated scenes where a laptop, table, or prop hides the lower half of the garment
- Hand or arm placement that covers a button placket, pattern, or neckline detail
- Compositions where the scene is engaging but the garment is not readable

UGC lifestyle realism and product visibility are not opposites. A candid home moment can still show the garment clearly.

---

## What To Identify From The Product Photo

Read the product carefully before writing any prompt. Record every visible detail.

**Colour**
- Primary colour (be specific — not just "blue", say "dusty navy" or "warm sage")
- Any secondary colours, panels, or contrast details

**Fabric and Texture**
- Visible fabric type (e.g. linen, ribbed knit, satin, cotton poplin, woven, jersey)
- How the fabric falls — stiff, draped, flowing, structured
- Visible texture detail (e.g. ribbing, woven pattern, embroidery, broderie anglaise)

**Fit**
- Relaxed / fitted / oversized / tailored
- Where the garment sits on the body

**Silhouette**
- Overall shape (e.g. A-line, straight, wrap, shift, boxy)

**Neckline**
- Exact neckline (e.g. V-neck, round neck, square neck, collared, scoop, boat neck)

**Sleeves**
- Sleeve length (sleeveless, short, elbow, three-quarter, long)
- Sleeve style (puff, straight, rolled, balloon, flutter)

**Closures**
- Buttons — number, size, colour, placement
- Zips — visible or concealed
- Ties, drawstrings, or belts included

**Length**
- Where the garment ends on the body (hip, below hip, knee, midi, ankle, full length)

**Pattern or Print**
- Solid colour, stripe, floral, abstract print — describe it precisely
- Scale of the pattern (small, medium, large)
- Colour combination in the print

**Other Visible Details**
- Pockets, slits, pleats, ruching, smocking, cut-outs, lace trim, collar, cuffs

---

## Rules To Follow When Writing The Prompt

- Describe the garment in exact detail in the prompt using every relevant attribute above
- Use specific descriptive language — not "nice blouse", but "relaxed-fit linen blouse in dusty sage with a V-neck, three-quarter sleeves, and small ceramic buttons"
- Never let the image generator decide what the garment looks like
- If a detail is unclear in the photo, do not guess — omit that attribute
- Do not add details that are not in the product photo
- Do not change the colour to something that photographs better
- Do not simplify the garment to make the prompt shorter

---

## Common Mistakes To Avoid

- Describing a garment in generic terms (e.g. "a top" instead of the specific product)
- Changing the colour because the original is hard to render
- Simplifying a pattern into a solid colour
- Adding accessories or layering pieces that are not in the product image
- Describing how you think the garment should look instead of how it actually looks
- Losing button or closure details because they seem minor

---

## Common AI Generator Errors By Garment Type

Know what image generators tend to get wrong before writing the prompt. Describe these details with extra precision when they apply.

**Knit and textured fabrics**
- Generators often smooth out ribbing, cable knit, or boucle texture — describe the texture explicitly and include it in the negative prompt
- Open-front cardigans often get rendered as closed or buttoned — state "open front, no closure" clearly

**Button-front garments**
- Generators frequently change button count, size, and colour — always specify exact number, size description, and colour
- Pearl, ceramic, or contrast buttons are high risk — name them clearly every time

**Printed or patterned garments**
- Generators often simplify prints into generic versions — describe the print in detail: scale, colour combination, repeat style
- Stripes often change direction or width — state horizontal/vertical and scale

**Sleeve styles**
- Flutter sleeves, puff sleeves, and balloon sleeves are frequently misrendered — name the style and add it to the negative prompt
- Three-quarter sleeves often become full-length or short — state the length precisely

**Length**
- Midi and maxi lengths are frequently shortened — state the length in body terms (e.g. "falls to mid-calf" or "below the knee") not just "midi"
- Where the hem lands should be described relative to the body

**Wrap or tie garments**
- Wrap necklines and tie-waist details are often lost — describe them explicitly and add to negative prompt

---

## Product Accuracy Check

Before finalising any prompt, ask:

- Have I described the exact colour?
- Have I described the fabric and texture?
- Have I described the fit and silhouette?
- Have I described the neckline?
- Have I described the sleeves?
- Have I described any closures or buttons?
- Have I described the length?
- Have I described any patterns or prints?
- Have I included all visible notable details?

If any answer is no, add the missing detail before proceeding.
