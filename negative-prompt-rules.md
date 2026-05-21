# Negative Prompt Rules

## Purpose

The negative prompt tells the image generator what to exclude. Always include a negative prompt with every static output. Copy it directly into the tool.

---

## Standard Negative Prompt

Use this as the base negative prompt for every output. Adjust only if a specific product or angle requires it.

```
plastic skin, hyper-smooth skin, airbrushed skin, over-retouched, porcelain skin, fake skin texture, distorted hands, extra fingers, missing fingers, deformed hands, deformed body, unnatural pose, mannequin pose, fashion model pose, hands on hips editorial pose, exaggerated posture, heavy makeup, full glam makeup, dramatic eye makeup, smoky eye, contouring, fake eyelashes, influencer styling, Gen Z styling, young woman, teenager, girl, overly thin body, sample size model, runway model, editorial fashion photography, Vogue-style shoot, luxury hotel background, studio background, seamless backdrop, white background, blank background, fake background, CGI background, over-saturated colours, moody cinematic filter, HDR, lens flare, creative filters, Instagram filter effect, changed garment colour, wrong garment colour, changed garment style, altered neckline, altered sleeves, altered fit, redesigned garment, generic clothing, different product, wrong product, added accessories, extra jewellery, extra accessories not in product, fake logo, brand logo, watermark, supplier branding, unreadable text, bad typography, cheap graphic design, sale banner graphic, sticker effect, Canva graphic, emoji on image, discount graphic, extra text elements, text in exclusion zones, text over the face, text over the garment, blurry background detail, fake depth of field, AI render look, CGI render, illustration, over-sharpened, noise filter, film grain effect, missing background, cut-off feet, cut-off arms where product detail is important, product cropped incorrectly
```

---

## Category-Specific Additions

Add these to the negative prompt when relevant:

**For patterned or printed garments:**
```
changed pattern, solid colour instead of print, wrong print scale, wrong print colours, simplified pattern
```

**For textured knits or structured fabrics:**
```
smooth fabric instead of textured, wrong fabric weight, wrong drape, flat fabric
```

**For button-front or detailed closure garments:**
```
missing buttons, wrong button colour, wrong number of buttons, missing closure detail
```

**For maxi or midi length garments:**
```
shortened garment, wrong length, knee length instead of midi, cropped incorrectly
```

---

## Rules for Using the Negative Prompt

- Always paste it in full — do not summarise it
- Add category-specific additions at the end when they apply
- Do not remove lines from the standard prompt unless a specific tool does not support it
- The negative prompt is as important as the positive prompt for product accuracy
