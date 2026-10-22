# Junyeong Song

B.S. Software & Communication Engineering, Hongik University (Sejong) · Undergraduate Researcher, VibeLab

> I build learning systems for music and audio: separating and analyzing the sources in recorded music, controlling audio under tight latency, and coordinating many agents with reinforcement learning.

---

## Research Interests

- **Music information retrieval**: source separation, beat and structure analysis, automatic transcription
- **Performance & singing voice**: pitch curves (F0), expressive timing, synthesis control
- **Low-latency audio**: real-time capture, streaming and separation within a latency budget
- **Multi-agent reinforcement learning**: cooperative control with centralized training, decentralized execution

---

## Highlights

| Year | | |
|---|---|---|
| 2026 | 🏆 **Excellence Award**, Product & Service Development Track: 2026 Sejong Data & AI Utilization Competition | [GreenWave](https://github.com/june2273/GreenWave) |
| 2025– | 🔬 **Undergraduate Researcher**, VibeLab, Hongik University | [Research](#research-vibelab) |

---

## Research (VibeLab)

| Project | What | Status |
|---|---|---|
| **Phantom Performer** | | 🔒 Ongoing |
| [**OrchestraMSS**](LINK) | Separates one orchestral recording with two systems, a SynthSOD baseline (X-UMX) and a 53-stem BS-RoFormer model, for per-instrument A/B listening in the browser. Inference adapted to a 16 GB Apple Silicon Mac (10 s chunks, only the selected stem heads computed). | ✅ Presented (Sep 2026) |
| [**LowLatencyMSS**](LINK) | Survey and experiment design for real-time music source separation: the quality–latency–compute trade-off, and whether spectrogram and hybrid models swap rank at monitoring-level latency (~5–10 ms). | 📚 Study & talk; implementation planned |
| **Distinguishing Professional and Amateur Piano Performances using 2D Audio Features and Convolutional Neural Networks** | Re-implemented the pipeline and added confound checks. A CNN that reaches ~99% on 1-second clips turns out to detect the recording, not the pianist: ablations trace the accuracy to room reverb and microphone noise floor. | 🔒 Private · seminar paper, PyGeek 2026 (co-author) |

---

## Projects

### Music AI
- [**Compose-AllinOne**](LINK): tempo, key, onset and note transcription written from scratch in TypeScript (own FFT) from published methods, plus a Python sidecar running Demucs, Beat This!, RMVPE and All-In-One for stems, beats, melody and song structure. [DEMO GIF]
- [**Chord-Tutor**](LINK): browser-based harmony and ear-training drills on rendered sheet music and a sampled piano, covering intervals (reading and building, up to doubly augmented/diminished), key signatures and the circle of fifths; diatonic chords next. [DEMO GIF]
- **vocal-to-synthv** 🔒: transfers a singer's expressive pitch curve (F0: note endings, vibrato, bends) from a vocal WAV onto Synthesizer V as a pitch-deviation curve. `in progress`

### Real-time Audio
- [**CRD-AUDIO**](https://github.com/june2273/CRD-AUDIO): system-audio sidecar for remote desktop. Core Audio tap → WebRTC/Opus to the browser in ~0.15 s, MP3 fallback, Chrome MV3 overlay.

### Multi-Agent RL
- [**GreenWave**](https://github.com/june2273/GreenWave): MAPPO with a centralized critic for traffic-signal control, modeled on Sejong's BRT corridor (SUMO, RLlib, PettingZoo). In a 2×2 BRT simulation vs. fixed-time signals: mean wait −36.7%, bus wait −52.0%. 🏆

### Tools & Concepts
- [**[ai-dev-harness]**](LINK): how I constrain and verify coding agents with CLAUDE.md rules, skills and hooks.
- **Pronunciation & fluency coach**: connected-speech scoring for Korean learners of English and Japanese. `design doc`
- **Lyric typography MV**: kinetic lyric typography timed from singing-synthesis project files, with LLM-chosen effects under intensity controls. `design doc`

---

## Coursework

<details>
<summary>Course projects (click to expand)</summary>

| Course | Project | Notes |
|---|---|---|
| Design Pattern Programming | [**BankingSystem**](https://github.com/june2273/BankingSystem) (team) | Java console banking system on H2. Four layers by SOLID; Template Method for transactions, Repository for persistence. Led the pattern, object-oriented and DB design |
| Data Science | [**Titanic**](LINK) | Exploratory analysis and visualization of survival by class, sex and family size |
| Communication Programming | [**CRC**](LINK) | CRC detection rates for single, double, odd and burst errors over 20,000 trials per generator |
| Database | [PROJECT] | In progress (Fall 2026) |
| Capstone Design | [PROJECT] | Planned (2027) |

</details>

---

📧 june227321@gmail.com · 📄 [CV (PDF)](LINK) · [LinkedIn](LINK)
**Stack:** Python · PyTorch · TypeScript · librosa · Ray RLlib · SUMO · WebRTC · Swift (Core Audio) · Java
