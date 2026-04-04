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

A young Vietnamese woman, 18 years old.

Face (STRICT LOCK):
- youthful oval face
- soft V-line chin
- smooth fair glowing skin (natural dewy)
- almond-shaped dark brown eyes
- natural double eyelids
- soft long lashes
- natural brows with soft arch
- small delicate nose with rounded tip
- natural pink lips with glossy coral tint
- subtle rosy blush

Hair (LOCKED STYLE):
- long, voluminous
- wavy / curly
- chestnut brown
- very textured, fluffy, bouncy

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
Wide environmental portrait, rule of thirds composition. Subject positioned in the lower third of the frame, vast [ENVIRONMENT] occupying the upper two-thirds. Single subject, one Vietnamese woman only.

A young Vietnamese woman (18 years old) with a youthful oval face, soft V-line chin, smooth fair glowing skin with natural dewy finish. Almond-shaped dark brown eyes with natural double eyelids, soft long lashes, natural brows with soft arch. Small delicate nose with rounded tip, natural pink lips with glossy coral tint, subtle rosy blush. Long voluminous wavy curly chestnut brown hair, very textured fluffy bouncy.

[BODY/OUTFIT DESCRIPTION]

[POSE/ACTION], [GAZE - not looking at camera].

[ENVIRONMENT DETAILS]

Soft muted pastel tones, low saturation, gentle colors, clean sharp image quality, smooth skin texture, shallow depth of field 85mm lens f/2.8, cinematic lighting, photorealistic, ultra-detailed, 8K.
```

---

## ⚠️ RULES

1. **SINGLE PERSON** - Always include "single subject, one Vietnamese woman only"
2. **CONSISTENT FACE** - Use exact face description every time
3. **NO CAMERA LOOK** - Subject never looks directly at camera
4. **CLEAN QUALITY** - No heavy grain, sharp image
5. **MUTED COLORS** - Soft pastel, low saturation

---

## 🎬 GENERATION SETTINGS

- **Model:** gpt-image-1
- **Size:** 1024x1536 (portrait 2:3)
