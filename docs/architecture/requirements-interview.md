# Requirements Interview: Local-First AI Music Coach

This document captures the current product direction and the open questions that must be answered before application source code is scaffolded.

## Current product intent

The project is a local-first Progressive Web App for mobile music education. It must be installable from a browser, continue working offline, and begin with an ear-training module focused on practical musicianship rather than academic interval drills.

The long-term direction is an AI-powered music coach that helps the learner develop real-world accompaniment skills, functional hearing, audiation, key-center recognition, and confidence playing by ear.

## Development posture

The project should be developed through small, reviewable Codex tasks and pull requests. Architecture documentation should precede application scaffolding, and implementation should not begin until the architecture is explicitly approved.

## Known user profile

- Experienced software developer learning modern AI-assisted development workflows.
- Plays some guitar, a little piano, and a little harmonica.
- Understands music theory.
- Wants better accompaniment skills, key identification, chord-progression recognition, functional harmony, and audiation.
- Prefers practical musicianship outcomes over isolated interval naming.

## Educational priorities

The initial learning design should emphasize:

- Tonic and key-center recognition.
- Scale degree recognition.
- Functional ear training.
- I, IV, V, and vi recognition.
- Common folk, pop, rock, and campfire-song progressions.
- Audiation and musical intuition.
- Practical accompaniment skills.

Isolated interval work may be used as supporting material, but it should not be the central product experience.

## Proposed primary mode

**Campfire Musician Mode** should train the learner to:

- Find tonic and hear home.
- Recognize key center.
- Hear movement among I, IV, V, and vi.
- Recognize common progressions.
- Predict likely next chords.
- Support singing or group playing on guitar, piano, harmonica, ukulele, or voice.

## Initial curriculum direction

1. Tonic recognition, scale degree recognition, and hearing home.
2. I, IV, and V recognition.
3. Distinguishing I, IV, and V.
4. Adding vi.
5. Common progressions such as I-IV-V, I-V-vi-IV, vi-IV-I-V, and I-IV-I-V.
6. Melody and chord relationship recognition.
7. Practical accompaniment exercises.

## Architectural decision areas still open

The architecture proposal should not be finalized until the following areas are clarified:

- Target mobile devices and browser support.
- Offline install and update expectations.
- Audio-engine requirements and acceptable synthesized sound quality.
- AI-coach scope, latency, download-size, and privacy expectations.
- Exercise authoring model and curriculum adaptability.
- Data model for attempts, mastery, mistakes, and practice history.
- Accessibility and usability requirements for airplane/offline practice.
- Deployment and release workflow.
- Testing expectations for music logic, audio scheduling, storage, and PWA behavior.

## Interview questions

### 1. Target platform and constraints

1. What exact devices should Phase 1 support first: iPhone, iPad, Android phone, Android tablet, desktop browser, or all of these?
2. Which browser is the primary target for installability: Safari on iOS/iPadOS, Chrome on Android, desktop Chrome, or another browser?
3. What is the oldest device you realistically want to support?
4. Should the app be usable with the phone speaker, wired headphones, Bluetooth headphones, or all three?
5. Is Bluetooth audio latency acceptable for exercises, or should the app warn users when timing accuracy matters?

### 2. Offline and installation expectations

1. Should the first visit download everything needed for offline use, or is it acceptable to download optional lesson/model packs later?
2. What is the maximum acceptable initial download size for Phase 1?
3. What is the maximum acceptable optional AI model download size for Phase 2?
4. Should users be able to explicitly manage downloaded content, such as deleting AI models or lesson packs?
5. Should progress sync ever be supported later, or should the product remain strictly local-only?

### 3. AI-coach expectations

1. In Phase 2, should the local AI generate free-form conversational responses, or should it mostly choose from structured coaching templates?
2. Is it acceptable for the first AI coach to be optional and disabled by default until a model is downloaded?
3. Should the coach ever accept typed questions from the learner, or should it behave only as a guided teacher inside lessons?
4. What is more important for the coach: fast short feedback, richer explanations, or Socratic questioning?
5. Should the coach persona be warm and encouraging, direct and concise, humorous, or configurable?

### 4. Music pedagogy and curriculum

1. Should Phase 1 assume equal-tempered Western harmony only?
2. Which major keys should appear first: all 12, guitar-friendly keys, harmonica-friendly keys, or a small rotating subset?
3. Should solfege be used, scale-degree numbers, Nashville numbers, Roman numerals, chord names, or a combination?
4. For Campfire Musician Mode, should answers be framed primarily as functions like I/IV/V/vi or as playable chord names like G/C/D/Em?
5. Should exercises include singing/humming prompts even if the app cannot yet evaluate sung input?
6. Should the app teach one concept at a time, or mix concepts once the learner has basic proficiency?

### 5. Audio design

1. Is a clean synthesized piano sufficient for Phase 1?
2. Should guitar-like strums be included early, or can they wait until after the harmonic curriculum works?
3. Should the app use metronomic timing from the beginning?
4. Should chord progressions be block chords, arpeggios, strums, bass-plus-chord patterns, or selectable styles?
5. Should generated examples include simple melodies over chords in Phase 1, or should that wait until later levels?

### 6. Practice experience and UX

1. What should a typical airplane practice session length be: 2 minutes, 5 minutes, 10 minutes, or open-ended?
2. Should the app feel more like flashcards, a lesson path, a game, a practice journal, or a private teacher?
3. How much explanation should appear during practice versus after a session?
4. Should the app support one-handed mobile use as a hard requirement?
5. Should mistakes immediately reveal the answer, replay the exercise, provide a hint, or ask the learner to try again?

### 7. Progress tracking and adaptation

1. What outcomes matter most: accuracy, streaks, confidence ratings, speed of recognition, consistency over days, or ability to transfer across keys?
2. Should users self-rate confidence after each answer?
3. Should the system track mistakes by function, key, progression, direction of movement, register, timbre, or exercise type?
4. Should spaced repetition be part of Phase 1?
5. Should progress be visible as levels, skills, charts, narrative feedback, or a simple practice log?

### 8. Future harmonica module

1. Should harmonica support assume a 10-hole diatonic C harmonica first?
2. Is second position blues/cross-harp a major goal, or should the first harmonica module stay with simple first-position melody discovery?
3. Should harmonica exercises show hole numbers and blow/draw notation?
4. Should bending be out of scope initially?
5. Should the ear trainer share the same curriculum engine with harmonica-specific presentation layers?

### 9. Technical preferences and maintainability

1. Are Vue 3, TypeScript, Vite, PWA, and IndexedDB confirmed preferences unless research finds a strong reason to differ?
2. Do you prefer minimal dependencies, or is a well-supported library acceptable when it reduces custom code?
3. Should the architecture favor handwritten music theory utilities or a music-theory library?
4. Should Tone.js be considered acceptable if it simplifies scheduling and synthesis, or do you prefer direct Web Audio API for learning and footprint?
5. Do you want unit tests from the first code PR, even if that slows initial scaffolding?

### 10. Development workflow and mentoring

1. Should each Codex task include a teaching note explaining one modern AI-assisted development technique?
2. Do you prefer architecture decision records for significant choices?
3. Should the project maintain a task backlog in Markdown, GitHub Issues, or both?
4. Should pull requests be intentionally small even if that means more PRs?
5. Do you want explicit checkpoints where implementation pauses for approval before moving to the next phase?

## Next documentation deliverables after interview answers

After these questions are answered, the next documentation-only tasks should be:

1. A complete architecture proposal.
2. An architecture decision record for the chosen frontend, storage, PWA, audio, and local-AI strategy.
3. A phased implementation roadmap.
4. A small-task backlog suitable for Codex-driven pull requests.
5. A test strategy covering curriculum logic, audio generation, storage, offline behavior, and later local-model integration.
