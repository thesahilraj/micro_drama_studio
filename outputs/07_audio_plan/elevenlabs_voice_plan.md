# ELEVENLABS VOICE PLAN — SCENE-BY-SCENE VOICE DIRECTION

## 1. VOICE PROFILE MATRIX

| Character | Voice Actor / Archetype | ElevenLabs Settings | Primary Emotional Modulation | Key Dialogue Trigger Points |
|---|---|---|---|---|
| **Narrator** | Deep Cinematic Storyteller | Stability: 0.65, Similarity: 0.85, Style: 0.40 | Suspense, wonder, dramatic irony, rapid face-slap pacing | Every sequence transition, world description, internal stakes |
| **Lin Fan** | Youthful Razor-Sharp Protagonist | Stability: 0.70, Similarity: 0.80, Style: 0.20 | Calm, unbothered, commanding low-register authority | Seq 2 (fob surprise), Seq 3 (car check), Seq 6 (jade), Seq 11-12 (legal doom) |
| **Song Shuming**| Mature Corporate Executive | Stability: 0.50, Similarity: 0.75, Style: 0.50 | Booming rage to staff -> fawning humble respect to Lin Fan | Seq 4 (office alarm), Seq 6 (90-deg bow, firing Liao) |
| **Liao Yingying**| Arrogant Fashion Director | Stability: 0.45, Similarity: 0.80, Style: 0.65 | Venomous condescension -> shrill hysterical breakdown | Seq 5 (eviction threats), Seq 6 (pleading on knees) |
| **Li Moyu** | Sweet VIP Concierge | Stability: 0.75, Similarity: 0.85, Style: 0.15 | Polite, melodious, gentle, graceful reverence | Seq 4 (phone call), Seq 6 (deed handover) |
| **Heiress Miss X**| Aristocratic Cool Beauty | Stability: 0.80, Similarity: 0.85, Style: 0.25 | Velvety, deliberate, slow, mysterious intelligence | Seq 7 (observing Villa 1, Romanée-Conti order) |
| **Landlady Zhao**| Greedy Extortionist Landlady | Stability: 0.40, Similarity: 0.75, Style: 0.70 | Loud, abrasive, screeching arrogance -> paralyzed groveling | Seq 1 (door knocking), Seq 11 (smug eviction), Seq 12 (collapse) |
| **Zhou Wancai** | Shrewd Real Estate Broker | Stability: 0.60, Similarity: 0.80, Style: 0.45 | Energetic sales talk -> courtroom righteous thunder | Seq 7 (agency excitement), Seq 12 (exposing 120 suites) |
| **Miss Jiang** | Corporate Tenant | Stability: 0.70, Similarity: 0.80, Style: 0.20 | Polite professional -> starry-eyed awestruck whisper | Seq 11 (rental viewing), Seq 12 (astonished admiration) |

---

## 2. GENERATION WORKFLOW FOR AUDACITY ASSEMBLY
1. Export voice tracks character-by-character from ElevenLabs with clean silence margins.
2. Label voice audio files deterministically: `VOX_SEQ-001_NARRATOR_01.wav`, `VOX_SEQ-001_ZHAO_01.wav`, etc.
3. Import into Audacity at 48,000 Hz, 24-bit PCM.
4. Apply slight room reverb (0.3s decay) for palatial showroom scenes (Seq 5–6) and dry acoustic damping for small rented apartment scenes (Seq 1, 11–12).
