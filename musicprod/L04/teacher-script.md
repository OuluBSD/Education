# L04 Teacher Script: Intro to Vocals and Pitch Correction

## Lesson Overview
- **Duration**: 90 minutes (suggested)
- **Topic**: Recording vocals and applying pitch correction in Cubase 5
- **Learning Objectives**: 
  - Students will record a vocal and apply pitch correction
  - Students will understand key/scale setup, retune speed, and formant settings
  - Students will create two versions: subtle vs. hard-tuned
- **Student Profile**: Strong pianist, beginner in DAWs/production

## Pre-Lesson Setup Checklist
- [ ] Ensure all laptops have Cubase 5 installed with VST pitch correction plugin
- [ ] Test microphone connections and audio interfaces
- [ ] Prepare sample vocal material for demo purposes
- [ ] Verify project file directory structure: `musicprod/L04/project_files/` and `musicprod/L04/exports/`

## Lesson Flow & Teacher Prompts

### Opening (5 minutes)
**Teacher Script**: "Today we'll be learning how to record vocals and apply pitch correction. Since you're a strong pianist, we'll connect this to your understanding of keys and scales. By the end of this lesson, you'll record your own vocal and create two versions - one subtly corrected and one with the more obvious pitch correction effect."

**Check**: Ask student to briefly describe what they remember about keys and scales from piano theory.

---

### Part 1: Project Setup in Cubase (15 minutes)

**Step 1**: Open Cubase 5
- **Teacher Prompt**: "Let's start a new project. Can you go to File > New Project > Empty?"
- **Student Response**: Should click File > New Project > Empty
- **Check**: Verify the new empty project opens successfully

**Step 2**: Save the project
- **Teacher Prompt**: "Now let's save this project. You should save it as `L04_VocalTuning_v01.cpr` in the `musicprod/L04/project_files/` folder."
- **Student Response**: Should navigate to `musicprod/L04/project_files/` and save with correct filename
- **Check**: Verify file path and name are correct

**Step 3**: Audio device setup
- **Teacher Prompt**: "We need to set up your audio interface. Go to Devices > Device Setup… > VST Audio System. Select your interface and set the buffer to 256–512 samples."
- **Student Response**: Should navigate to and configure audio device settings
- **Check**: Verify correct interface is selected and buffer size is within range

**Step 4**: Project settings
- **Teacher Prompt**: "Now set the project sample rate to 44.1 kHz and bit depth to 24-bit. Go to Project > Project Setup…"
- **Student Response**: Should open Project Setup and adjust settings
- **Check**: Confirm sample rate is 44.1 kHz and bit depth is 24-bit

---

### Part 2: Setting Up the Vocal Track (15 minutes)

**Step 5**: Add an audio track
- **Teacher Prompt**: "Let's add an audio track for your vocals. Go to Project > Add Track > Audio… Select Mono and name it `LeadVox`."
- **Student Response**: Should add a mono audio track named LeadVox
- **Check**: Verify track is created as mono and named "LeadVox"

**Step 6**: Check input routing
- **Teacher Prompt**: "Press F4 to open VST Connections. Make sure your microphone input is assigned to the `LeadVox` track."
- **Student Response**: Should open VST Connections and verify input routing
- **Check**: Confirm microphone is routed to LeadVox track

**Step 7**: Enable recording and monitoring
- **Teacher Prompt**: "Click the red 'R' button to enable recording. Also click the speaker icon to enable monitoring. When you speak, the level meter should move."
- **Student Response**: Should click R and speaker icon on LeadVox track, then test speaking
- **Check**: Verify both record and monitor are enabled, and meters move when speaking

**Step 8**: Set input level
- **Teacher Prompt**: "Let's set the input level. When you speak or sing normally, aim for peaks around -12 to -6 dBFS. If too loud (clipping red), lower the gain. If too quiet, increase the gain."
- **Student Response**: Should adjust input gain to achieve optimal levels
- **Check**: Confirm levels are within -12 to -6 dBFS range without clipping

---

### Part 3: Recording the Vocal (15 minutes)

**Step 9**: Prepare for recording
- **Teacher Prompt**: "Let's set the tempo to match your song. First, make sure the Click button is enabled so you can record to a metronome. Then set an appropriate tempo."
- **Student Response**: Should enable the Click and set tempo
- **Check**: Verify click track is enabled and tempo is set appropriately

**Step 10**: Record multiple takes
- **Teacher Prompt**: "Now let's record 2-3 takes of your vocal. Don't worry about perfection - we'll comp together the best parts afterward. Record your takes and listen back to each one."
- **Student Response**: Should record 2-3 takes and listen to each
- **Check**: Verify multiple takes exist in lanes and student has listened to them

**Step 11**: Enable comping
- **Teacher Prompt**: "Right-click the LeadVox track and select 'Show Lanes' to enable comping. This allows us to select the best phrases from different takes."
- **Student Response**: Should enable lanes for comping
- **Check**: Verify multiple lanes are visible with different takes

**Step 12**: Create comp
- **Teacher Prompt**: "Use the Comp tool to select the best phrases from different takes. You can make selections in the lanes, then crossfade between edits using the X key."
- **Student Response**: Should create a composite take with the best parts
- **Check**: Verify the composite take contains selected best parts from different takes

---

### Part 4: Applying Pitch Correction (20 minutes)

**Step 13**: Insert pitch correction plugin
- **Teacher Prompt**: "Open the MixConsole with F3. Select your LeadVox track, then go to Inserts and choose the `Pitch Correction` VST plugin. Place it in Insert Slot 1."
- **Student Response**: Should insert the Pitch Correction plugin on the LeadVox track
- **Check**: Verify pitch correction plugin is inserted and visible on the track

**Step 14**: Set key and scale
- **Teacher Prompt**: "In the pitch correction plugin, we need to set the key and scale of your song. Since you're a strong pianist, you should be able to identify this. If your song is in C Major, set those values in the plugin."
- **Student Response**: Should set the correct key and scale in the plugin
- **Check**: Verify key and scale match the song (can confirm by playing reference notes if needed)

**Step 15**: Adjust retune speed
- **Teacher Prompt**: "Now let's look at retune speed. This controls how quickly the correction happens. For natural-sounding results, start with 40-60ms. For the effect style (like AutoTune), use 0-10ms. Keep 'Formant' or 'Preserve Formants' enabled."
- **Student Response**: Should set retune speed to natural setting first (40-60ms)
- **Check**: Verify formant preservation is enabled and retune speed is set appropriately

**Step 16**: Check detection settings
- **Teacher Prompt**: "In the plugin, choose the appropriate input type that matches the voice - usually Alto, Tenor, or Soprano."
- **Student Response**: Should select the appropriate voice type
- **Check**: Verify detection setting matches the voice being corrected

---

### Part 5: Listening and Adjustment (10 minutes)

**Step 17**: A/B comparison
- **Teacher Prompt**: "Toggle the plugin's bypass button to compare the corrected vs. uncorrected vocal. Listen for artifacts like warbles or consonant distortion. If you hear problems, try slowing the retune speed or adjusting specific notes if the plugin allows."
- **Student Response**: Should toggle bypass and listen for differences and artifacts
- **Check**: Verify student can hear the difference between corrected and uncorrected, and identifies any issues

**Step 18**: Create hard-tuned version
- **Teacher Prompt**: "Now create the hard-tuned version by changing the retune speed to 0-10ms. This will give the more obvious pitch correction effect. Toggle between your subtle and hard-tuned settings."
- **Student Response**: Should adjust retune speed to create hard-tuned version
- **Check**: Verify the hard-tuned version sounds intentionally corrected

---

### Part 6: Exporting Both Versions (10 minutes)

**Step 19**: Export subtle version
- **Teacher Prompt**: "Let's export your subtle version first. Go to File > Export > Audio Mixdown. Save it as `L04_vox_subtle_v01.wav` in the `musicprod/L04/exports/` folder."
- **Student Response**: Should export the subtle version with correct name and location
- **Check**: Verify file is named correctly and saved in the exports folder

**Step 20**: Export hard-tuned version  
- **Teacher Prompt**: "Now switch your plugin settings back to hard-tuned (0-10ms retune speed) and export again. Save this one as `L04_vox_effect_v01.wav` in the same exports folder."
- **Student Response**: Should adjust settings and export the hard-tuned version
- **Check**: Verify both files exist in the exports folder with correct names

## Verification Checklist (Final Step)
Go through these with the student to confirm completion:

- [ ] Input routed correctly (meter moves; correct input bus)
- [ ] Peaks around -12 to -6 dBFS; no clipping on record or plugin input
- [ ] Plugin key/scale matches confirmed key (student verified with piano knowledge)
- [ ] Retune speed appropriate: subtle version transparent; effect version intentional
- [ ] Exports play back with expected correction; no missing audio
- [ ] Both versions exported: subtle and effect

## Quick Teacher Tips
- Prioritize musical key/scale selection - this affects results more than other settings
- Avoid overdriving inputs when setting gain levels
- Use conservative monitoring levels when working with vocals
- Encourage the student to use their piano knowledge to verify key detection is correct
- Have the student "teach back" one step about pitch correction at the end of the lesson

## Troubleshooting
- If no audio is being recorded: Check input routing and ensure track is record-enabled
- If plugin isn't installed: Verify Cubase 5 has a compatible pitch correction VST
- If levels are too loud: Remind to lower gain at the interface, not just in software
- If correction sounds robotic when not intended: Check if retune speed is set too fast