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
long voluminous wavy dark brown hair with highlights, soft texture, slightly fluffy, natural movement, youthful style.

👉 This description MUST appear in EVERY prompt

---

## 📐 COMPOSITION GRID (LOCKED - USE FOR ALL)

**3x3 Grid Rule:**
```
| 1 | 2 | 3 |   ← Environment/Sky (top row)
| 4 | 5 | 6 |   ← Subject in cell 5 (center)
| 7 | 8 | 9 |   ← Subject in cell 8 (bottom center)
```

- Subject MUST be positioned in **cell 5 and cell 8** (center column, middle + bottom)
- Small details (hair, accessories, dress edges) may extend into adjacent cells
- Top row (1, 2, 3) = environment, sky, background
- Use: `rule of thirds composition, subject centered in middle and lower third of frame`

👉 This grid MUST be applied in EVERY prompt

---

## 🎨 LIGHTING & STYLE (LOCKED - USE FOR ALL)

**Lighting:**
```
warm and diffused lighting, casting gentle shadows, highlighting hair and skin, creating a relaxed and elegant atmosphere
```

**Style:**
```
soft focus background, warm diffused tones, gentle shadows, relaxed elegant atmosphere, eye-level perspective
```

👉 This lighting/style MUST appear in EVERY prompt

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
Rule of thirds 3x3 grid composition, subject centered in middle and lower third of frame (cells 5 and 8), environment occupying top row.

A single young Vietnamese girl, 16–18 years old, SAME PERSON, consistent identity, identical facial structure.

Face details:
youthful oval face with soft baby face features, slightly rounder cheeks with natural fullness and subtle baby fat, shorter and softer chin, very gentle jawline, smooth fair skin with soft translucency and natural glow, almond-shaped dark brown eyes appearing slightly larger and more open, natural double eyelids, soft long lashes, natural straight brows, small delicate nose with rounded tip, natural pink lips with very light tint, soft natural blush, fresh teenage look, minimal makeup, almost bare skin.

Hair:
long voluminous wavy dark brown hair with highlights, soft texture, slightly fluffy, natural movement, youthful style.

Pose & Expression:
[POSE], [EXPRESSION - eyes closed/looking away/etc, NOT at camera]

Outfit:
[OUTFIT DESCRIPTION]

Environment:
[ENVIRONMENT with soft focus background]

Lighting:
warm and diffused lighting, casting gentle shadows, highlighting hair and skin, creating a relaxed and elegant atmosphere.

Camera:
85mm lens, f/2.8, shallow depth of field, subject sharp, soft creamy background blur, eye-level perspective.

Style:
soft focus background, warm diffused tones, gentle shadows, relaxed elegant atmosphere.

Quality:
photorealistic, ultra detailed, 8K.
```

---

## 📝 EXAMPLE PROMPT

```
Wide environmental portrait, rule of thirds composition. Subject positioned on the left side of the frame, facing towards viewer in three-quarter profile.

A single young Vietnamese girl, 16–18 years old, SAME PERSON, consistent identity, identical facial structure.

Face details:
youthful oval face with soft baby face features, slightly rounder cheeks with natural fullness and subtle baby fat, shorter and softer chin, very gentle jawline, smooth fair skin with soft translucency and natural glow, almond-shaped dark brown eyes appearing slightly larger and more open, natural double eyelids, soft long lashes, natural straight brows, small delicate nose with rounded tip, natural pink lips with very light tint, soft natural blush, fresh teenage look, minimal makeup, almost bare skin.

Hair:
long voluminous wavy dark brown hair with highlights, soft texture, slightly fluffy, natural movement, youthful style.

Pose & Expression:
reclining on a lounge chair, relaxed posture, head tilted slightly back, gentle serene expression with closed eyes and soft lips.

Outfit:
form-fitting black mini dress with thin spaghetti straps, accented by a delicate gold chain around waist.

Environment:
outdoor patio or garden with blurred greenery and sunlight, soft focus background.

Lighting:
warm and diffused lighting, casting gentle shadows, highlighting hair and skin, creating a relaxed and elegant atmosphere.

Camera:
85mm lens, f/2.8, shallow depth of field, subject sharp, soft creamy background blur, eye-level perspective.

Style:
soft focus background, warm diffused tones, gentle shadows, relaxed elegant atmosphere.

Quality:
photorealistic, ultra detailed, 8K.
```

---

## ⚠️ RULES

1. **SINGLE PERSON** - Always "single young Vietnamese girl, SAME PERSON"
2. **CONSISTENT FACE** - Use exact face description every time
3. **BABY FACE** - Rounder cheeks, softer chin, teenage look
4. **CLEAN QUALITY** - No heavy grain, sharp image
5. **WARM DIFFUSED** - Use locked lighting style (warm, gentle shadows)
6. **NEVER LOOK AT CAMERA** - Eyes closed, looking away, profile, etc.

## 👁️ GAZE RULE (MANDATORY)

**Subject must NEVER look directly at camera!**

Always add one of these:
- `closed eyes, serene expression`
- `looking away to the side`
- `looking down at [object]`
- `profile view, looking into distance`
- `head tilted back, eyes closed`

---

## 🎬 GENERATION SETTINGS

- **Model:** gpt-image-1
- **Size:** 1024x1536 (portrait, closest to 9:16)
