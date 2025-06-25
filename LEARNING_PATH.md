# 🚧 Learning Path & Build Roadmap

I'm building an AI-powered faceless content engine from scratch using Python, OpenAI, and automation tools.  
This doc tracks what I'm learning, building, and prioritizing.

---

## ✅ Phase 1: Prompt Engineering + GPT-4o
- [x] Learn prompt chaining basics
- [ ] Create prompt for video script generation
- [ ] Create scene breakdown prompt (title + narration + visuals)
- [ ] Script to JSON structure

---

## 🔁 Phase 2: Visual Generation
- [ ] Use DALL·E or Canva API to create image assets
- [ ] Brand styling template (font, color, layout)
- [ ] Save image sets per scene

---

## 🔊 Phase 3: Voiceover + Captions
- [ ] Use ElevenLabs to generate voice audio
- [ ] Learn Whisper (local or API) to generate SRT captions
- [ ] Match scene timing with narration

---

## 🎬 Phase 4: Assemble Video
- [ ] Learn FFmpeg basics
- [ ] Build a script to combine slides + voice + captions
- [ ] Add transitions + overlays

---

## 🪄 Phase 5: Polish + Automation
- [ ] Add content title overlays
- [ ] Optimize for 9:16 format (IG/TikTok)
- [ ] Add CTA end slide

---

## 📣 Phase 6: Publish + Reflect
- [ ] Create first full demo video
- [ ] Upload to TikTok/IG manually
- [ ] Reflect in README or mini blog

---

## ✨ What I'm Using to Learn
- [OpenAI Cookbook](https://github.com/openai/openai-cookbook)
- [Learn Prompting](https://learnprompting.org)
- [FFmpeg Tutorials](https://ffmpeg.org/ffmpeg.html)
- [ElevenLabs Docs](https://docs.elevenlabs.io)

---
---

## 📆 Week 1: Prompt Engineering + GPT-4o Scripting

🎯 **Goal:**  
Design high-quality prompts that generate structured video content (e.g., scene breakdowns), and automate it using Python + OpenAI GPT-4o API.

---

### 🧠 What I'm Learning

#### ✅ Day 1–2: Prompt Engineering Basics
- [ ] Learn role prompting (e.g. “You are a TikTok scriptwriter...”)
- [ ] Practice output formatting: bullet lists, JSON, markdown
- [ ] Experiment with tone (friendly, expert, playful)
- [ ] Try few-shot prompting with examples

#### ✅ Day 3–4: OpenAI GPT-4o API Integration
- [ ] Set up OpenAI Python SDK
- [ ] Make basic API calls with topics as input
- [ ] Receive structured outputs (JSON)
- [ ] Handle simple errors and retries

#### ✅ Day 5–6: Scene Breakdown Generator
- [ ] Build a `script_generator.py` or notebook
- [ ] Input: Topic (e.g., “What is Cloud Computing?”)
- [ ] Output: JSON with scene breakdowns (scene, title, narration, visuals)
- [ ] Save response to `assets/output/scene_data.json`

#### ✅ Day 7: Test + Tune
- [ ] Test with 3–5 different tech topics
- [ ] Refine prompt wording for consistency
- [ ] Try different tones or formats (e.g., “educational”, “playful”)
- [ ] Document learnings in `NOTES.md`

---

### ✅ Success Criteria
- [ ] Prompts return consistent, clean JSON
- [ ] Generator script works with multiple topics
- [ ] Reusable prompt template saved to `prompts/script_generator.md`
- [ ] JSON output saved and readable
- [ ] This checklist updated ✔️ in `LEARNING_PATH.md`
