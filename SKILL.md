---
name: ai-tiktok
description: Generate AI TikTok character images with consistent identity. Only for #ai-tiktok-project channel.
metadata:
  openclaw:
    emoji: "🎬"
    channels:
      - "1489469764857233542"
---

# AI TIKTOK CHARACTER SKILL (CONSISTENT IDENTITY VERSION)

## 🎯 GOAL
Generate cinematic, photorealistic images of ONE consistent Vietnamese female character.
Every generation MUST keep the SAME face identity.

---

## 🔒 CORE RULE (VERY IMPORTANT)

The character MUST remain visually identical across all generations.

DO NOT:
- change face structure
- change skin tone
- change eye shape
- change hair identity drastically

This is ONE single person.

---

## 👤 CHARACTER IDENTITY (LOCKED - NEVER CHANGE)

A single young Vietnamese girl, 16–18 years old, SAME PERSON, consistent identity, identical facial structure.

**Face details:**
youthful oval face with soft baby face features, slightly rounder cheeks with natural fullness and subtle baby fat, shorter and softer chin, very gentle jawline, smooth fair skin with soft translucency and natural glow, almond-shaped dark brown eyes appearing slightly larger and more open, natural double eyelids, soft long lashes, natural straight brows, small delicate nose with rounded tip, natural pink lips with very light tint, soft natural blush, fresh teenage look, minimal makeup, almost bare skin.

**Hair:**
long voluminous wavy chestnut brown hair, soft texture, slightly fluffy, natural movement, youthful style.

👉 This description MUST appear in EVERY prompt

---

## 🧩 INPUT

```json
{
  "pose": "...",
  "action": "...",
  "outfit": "...",
  "environment": "..."
}
```

---

## 📸 OUTPUT PROMPT STRUCTURE

```
Wide environmental portrait, rule of thirds composition.

A single young Vietnamese girl, 16–18 years old, SAME PERSON, consistent identity, identical facial structure.

Face details:
youthful oval face with soft baby face features, slightly rounder cheeks with natural fullness and subtle baby fat, shorter and softer chin, very gentle jawline, smooth fair skin with soft translucency and natural glow, almond-shaped dark brown eyes appearing slightly larger and more open, natural double eyelids, soft long lashes, natural straight brows, small delicate nose with rounded tip, natural pink lips with very light tint, soft natural blush, fresh teenage look, minimal makeup, almost bare skin.

Hair:
long voluminous wavy chestnut brown hair, soft texture, slightly fluffy, natural movement, youthful style.

Pose & Action:
[POSE/ACTION DESCRIPTION]

Outfit:
[OUTFIT DESCRIPTION]

Environment:
[ENVIRONMENT DESCRIPTION]

Lighting:
soft natural daylight, diffused light, gentle highlights, soft shadows, bright and fresh atmosphere.

Camera:
85mm lens, f/2.8, shallow depth of field, subject sharp, soft creamy background blur.

Style:
natural lifestyle photography, soft pastel tones, low saturation, clean color grading, fresh and airy mood.

Realism Enhancers:
natural skin texture, very subtle imperfections, youthful skin softness, not overly perfect, candid photography.

Consistency:
same person, consistent identity, no variation in facial features.

Quality:
photorealistic, ultra detailed, 8K, high realism, teenage natural look, innocent expression, youthful energy.
```

---

## 📝 EXAMPLE PROMPT

```
Wide environmental portrait, rule of thirds composition.

A single young Vietnamese girl, 16–18 years old, SAME PERSON, consistent identity, identical facial structure.

Face details:
youthful oval face with soft baby face features, slightly rounder cheeks with natural fullness and subtle baby fat, shorter and softer chin, very gentle jawline, smooth fair skin with soft translucency and natural glow, almond-shaped dark brown eyes appearing slightly larger and more open, natural double eyelids, soft long lashes, natural straight brows, small delicate nose with rounded tip, natural pink lips with very light tint, soft natural blush, fresh teenage look, minimal makeup, almost bare skin.

Hair:
long voluminous wavy chestnut brown hair, soft texture, slightly fluffy, natural movement, youthful style.

Pose & Action:
She is holding a skincare product in one hand, standing naturally, relaxed posture, soft gentle expression, slightly smiling, candid moment.

Outfit:
light beige homewear robe, soft fabric, minimal, natural and youthful styling.

Environment:
bright modern indoor space with large window, soft daylight entering, clean minimal interior, airy feeling.

Lighting:
soft natural daylight, diffused light, gentle highlights, soft shadows, bright and fresh atmosphere.

Camera:
85mm lens, f/2.8, shallow depth of field, subject sharp, soft creamy background blur.

Style:
natural lifestyle photography, soft pastel tones, low saturation, clean color grading, fresh and airy mood.

Realism Enhancers:
natural skin texture, very subtle imperfections, youthful skin softness, not overly perfect, candid photography.

Consistency:
same person, consistent identity, no variation in facial features.

Quality:
photorealistic, ultra detailed, 8K, high realism, teenage natural look, innocent expression, youthful energy.
```

---

## ⚠️ RULES

1. **SINGLE PERSON** - Always "single young Vietnamese girl, SAME PERSON"
2. **CONSISTENT FACE** - Use exact face description every time
3. **BABY FACE** - Rounder cheeks, softer chin, teenage look
4. **CLEAN QUALITY** - No heavy grain, sharp image
5. **MUTED COLORS** - Soft pastel, low saturation

---

## 🎬 GENERATION SETTINGS

- **Model:** gpt-image-1
- **Size:** 1024x1536 (portrait, closest to 9:16)
