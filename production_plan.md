# Gemini Flow Production Plan: "De Caos a Cierre"

**Concept:** A Split-Screen comparison marketing video showing the transition from administrative chaos to automated order using the web app.
**Target Audience:** Real Estate Developers in Mexico.
**Total Duration:** 15 Seconds.
**Format:** 9:16 (Vertical) for Reels/TikTok.

## Phase 1: Preparation (Ingredients & Assets)

Before generating video, we need to create consistent character and UI assets to use as inputs for Image-to-Video. This ensures the "Manager" looks the same in the chaos and relief scenes.

### 1. The Manager (Character Asset)
*   **Role:** Real Estate Operations Manager (Male, 35-45, latino professional, wearing business casual/shirt).
*   **Image Prompt (Midjourney/Imagen):**
    > Portrait of a professional Mexican real estate manager, male, late 30s, wearing a crisp white dress shirt, sitting at a modern office desk. Neutral expression, soft cinematic lighting, shallow depth of field, modern glass office background. High resolution, 8k, photorealistic. --ar 9:16

![The Manager](/home/sebastian/vsc-workspace/marketing/manager_in_office.png)

### 2. The Dashboard (UI Asset)
*   **Role:** The "Hero" screen of the application.
*   **Image Prompt:**
    > Close-up of a modern, clean web application dashboard on a laptop screen. The interface is white and minimalist with green accent colors. The top left corner shows the 'ValiDocs' logo (white "v" in a red rounded square, followed by dark blue text "ValiDocs"). The screen displays a list of Mexican real estate documents in Spanish: 'Escritura Pública', 'INE / Pasaporte', 'Comprobante de Domicilio', 'RFC (Constancia de Situación Fiscal)'. Each document has a green badge next to it that says 'Validado'. Futuristic, high-tech, clean UI design, 'Proptech' style. 4k resolution. --ar 16:9

![The Dashboard](/home/sebastian/vsc-workspace/marketing/app_dashboard_mx.png)

---

## Phase 2: The Shot List (The Flow)

We will generate full-frame clips for maximum quality and assemble the split-screen effect in post-production (Scenebuilder).

### Clip 1: The Chaos (Left Side Content)
*   **Scene:** Manager overwhelmed by paperwork and notifications.
*   **Type:** **Text-to-Video** (To capture the frantic energy).
*   **Prompt (Veo 3):**
    > Medium shot of a stressed office manager buried under piles of paper on his desk. He is frantically looking for a document. Hundreds of floating WhatsApp notification icons hover in the air around him, glowing green and distracting him. The lighting is dim and moody, slightly blue/grey. Handheld camera movement, shaky and chaotic mood. High anxiety, overwhelming atmosphere. Photorealistic, 4k.
*   **Negative Prompt:** (text), (watermark), (distorted face)

### Clip 2: The Solution (Right Side & Full Screen)
*   **Scene:** The Dashboard working automatically.
*   **Type:** **Image-to-Video** (Input: *The Dashboard* asset).
*   **Prompt (Veo 3):**
    > Cinematic close-up of the laptop screen. The cursor clicks a "Validate All" button. Instantly, a column of grey status icons turns into bright green checkmarks one by one. The camera slowly zooms in on the word "Validated". Clean, bright, high-key lighting. Smooth, mechanical camera motion. Tech commercial style.
*   **Negative Prompt:** (blurry text), (glitch)

### Clip 3: The Relief (End Scene)
*   **Scene:** Manager relaxed and happy.
*   **Type:** **Image-to-Video** (Input: *The Manager* asset).
*   **Prompt (Veo 3):**
    > Medium shot of the same real estate manager leaning back in his chair, looking relieved and happy. He smiles confidently at the camera and closes his laptop. The background is a bright, sunlit modern office. Smooth slow-motion camera push-in. Peaceful, successful atmosphere. Golden hour lighting.
*   **Negative Prompt:** (bad teeth), (morphing hands)

---

## Phase 3: Assembly & Polish

### Assembly Instructions (Scenebuilder / Editor)
1.  **00:00 - 00:03 (Split Screen):**
    *   Create a 9:16 Canvas.
    *   Place **Clip 1 (Chaos)** on the Left/Top half. Color grade: Desaturate slightly, add blue tint.
    *   Place a **Black Background** with flashing text "¿Tu equipo vive así?" on the Right/Bottom half.
    *   *Audio:* Mix "Office noise" + "Notification spam sound effects".

2.  **00:03 - 00:08 (The Reveal):**
    *   Transition **Clip 2 (Dashboard)** to swipe over and fill the full screen.
    *   *Audio:* "Ding" sound effect + Upbeat synth music starts.

3.  **00:08 - 00:12 (Relief):**
    *   Cut to **Clip 3 (Relief)**.
    *   *Audio:* Sigh of relief + Music swells.

4.  **00:12 - 00:15 (CTA):**
    *   Static End Card graphics.

### Audio Cues
*   Search for: "Frantic Notification SFX", "Modern Tech Corporate Background Music", "Success Chime".
