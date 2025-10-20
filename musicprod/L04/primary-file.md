# Lesson 4: Intro to Vocals and Pitch Correction

Summary
- Record/import a vocal and apply pitch correction (early). Use Cubase 5 for VST pitch tools.

Objectives
- Mic setup, gain staging, simple comping.
- Pitch correction: key/scale, retune speed, formant.
- Gentle correction vs. effect style; export A/B.

Outputs
- Two vocal versions (subtle vs. hard-tuned) with notes on settings.

Instruction-Based Walkthrough (Cubase 5)
- Open: File > New Project > Empty. Save as `L04_VocalTuning_v01.cpr` in `musicprod/L04/project_files/`.
- Audio device: Devices > Device Setup… > VST Audio System. Select your interface. Set buffer 256–512 samples.
- Project setup: Project > Project Setup… Set sample rate 44.1 kHz, bit depth 24-bit.
- Add track: Project > Add Track > Audio… Mono > Name: `LeadVox`.
- Input check: Press F4 (VST Connections). Ensure mic input is assigned to `LeadVox`.
- Record enable + monitor: Click the red ‘R’ and speaker icon. Verify meter moves when speaking.
- Set level: Aim peaks at -12 to -6 dBFS while test speaking/singing.
- Record: Enable Click (C). Set tempo to match song. Record 2–3 takes.
- Comping: Enable lanes (right-click track > Show Lanes). Use the Comp tool to select best phrases. Crossfade (X) between edits.
- Insert pitch plugin: MixConsole (F3) > Select `LeadVox` > Inserts > choose `Pitch Correction` VST (generic). Place in Insert Slot 1.
- Key/scale: In plugin, set song Key and Scale (e.g., C Major). If unsure, play piano with vocal and find tonic; confirm with student.
- Retune speed: Start with 40–60 ms for natural. For effect, 0–10 ms. Keep Formant/Preserve Formants enabled.
- Detection: Choose appropriate input type (Alto/Tenor/Soprano) matching voice.
- Bypass check: Toggle plugin bypass to A/B. Listen for artifacts (warbles, consonant lisping). If present, slow retune or adjust notes by hand if plugin allows.
- Render two passes: File > Export > Audio Mixdown. Name `L04_vox_subtle_v01.wav` and `L04_vox_effect_v01.wav` into `musicprod/L04/exports/`.

Verification Checklist
- Input routed correctly (meter moves; correct input bus).
- Peaks around -12 to -6 dBFS; no clipping on record or plugin input.
- Plugin key/scale matches piano-confirmed key.
- Retune speed appropriate: subtle version transparent; effect version intentional.
- Exports play back with expected correction; no missing audio.
