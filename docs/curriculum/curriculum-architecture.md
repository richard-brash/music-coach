# Curriculum Architecture: Local-First Music Coach

## Purpose and learning stance

The Local-First Music Coach curriculum develops practical, functional musicianship in short daily sessions. The learner is not training to label isolated theory facts; the learner is training to hear where home is, predict what chord is likely, accompany songs by ear, and build enough confidence to join informal music-making.

The curriculum assumes:

- 5-minute practice sessions.
- iPhone/iPad Progressive Web App use.
- Offline-first practice contexts.
- Synthesized piano audio as the shared starting timbre.
- Functional hearing before instrument-specific mechanics.
- Practical accompaniment as the central outcome.
- A warm mentor voice: calm, specific, encouraging, and never shaming.

Software architecture is intentionally out of scope except where it supports learning needs: the learner needs quick offline access, consistent piano playback, durable practice history, and adaptive review based on past attempts.

## Core learning objectives

By the end of the initial Campfire Musician curriculum, the learner should be able to:

1. **Recognize tonic**
   - Hear the tonal home of a short musical example.
   - Sing or hum the likely tonic after a cadence or short progression.
   - Distinguish stable arrival from unstable continuation.

2. **Recognize scale-degree function**
   - Relate heard tones to movable Do.
   - Identify whether a tone sounds like Do, Re, Mi, Fa, Sol, La, or Ti in simple contexts.
   - Use scale degrees to describe what a melody is doing without depending on absolute pitch.

3. **Hear primary harmonic functions**
   - Identify I as home/rest.
   - Identify V as tension/return pull.
   - Identify IV as lift, openness, or broadening away from home.
   - Distinguish I, IV, and V in short progressions.

4. **Hear vi as a familiar minor-family color**
   - Recognize vi as related to I but emotionally darker or more reflective.
   - Distinguish vi from I in common pop and folk contexts.
   - Hear vi inside common four-chord progressions.

5. **Recognize common campfire progressions**
   - Identify and predict common loops such as I-IV-V, I-V-vi-IV, vi-IV-I-V, I-IV-I-V, I-vi-IV-V, and I-V-IV-I.
   - Hear likely next-chord choices in simple accompaniment patterns.

6. **Transfer across keys**
   - Understand that I, IV, V, and vi are roles, not fixed chord names.
   - Move between movable Do, Nashville numbers, Roman numerals, and playable chord names.
   - Apply the same functional pattern in guitar-friendly, piano-friendly, and voice-friendly keys.

7. **Build confident accompaniment habits**
   - Choose a likely chord during a simple song-like example.
   - Recover after mistakes without stopping.
   - Use limited harmonic vocabulary musically.
   - Trust functional hearing more than memorized chord-name lookup.

## Exact skills being developed

The curriculum tracks skills at a fine-grained level so practice can stay short and targeted.

### Aural orientation skills

- Finding tonic after a melody fragment.
- Finding tonic after a chord progression.
- Hearing whether an ending feels complete or unresolved.
- Singing or internally audiating Do after listening.
- Matching a heard tonal center to a displayed key only after the functional task is understood.

### Functional pitch skills

- Hearing Do as home.
- Hearing Sol as stable but not home.
- Hearing Mi as major-color identity.
- Hearing Fa as leaning toward Mi or supporting IV.
- Hearing Ti as leading toward Do.
- Hearing La as the melodic color connected to vi.
- Comparing two scale degrees by function rather than by interval name.

### Functional harmony skills

- Recognizing I in isolation and in context.
- Recognizing V as dominant pull toward I.
- Recognizing IV as predominant or open movement away from I.
- Distinguishing IV from V when both are non-tonic.
- Recognizing vi as relative minor color.
- Hearing chord roots as scale-degree functions.
- Recognizing cadences such as V-I and IV-I.
- Predicting next chords in common loops.

### Progression recognition skills

- Identifying two-chord loops: I-V, I-IV, I-vi, vi-IV.
- Identifying three-chord loops: I-IV-V, I-V-IV, I-vi-V.
- Identifying four-chord loops: I-V-vi-IV, vi-IV-I-V, I-vi-IV-V, I-IV-I-V.
- Recognizing the same progression in different keys, registers, and tempos.
- Recognizing progressions from block chords, broken chords, and simple accompaniment patterns.

### Practical accompaniment skills

- Choosing a functional chord for the next measure.
- Staying oriented to the current key center.
- Using I, IV, V, and vi to support singing.
- Translating a functional progression into playable chord names.
- Recovering gracefully when the wrong chord is chosen.
- Using confidence ratings to notice which skills feel solid versus guessed.

### Metacognitive skills

- Rating confidence honestly after an answer.
- Distinguishing “I knew it,” “I narrowed it down,” and “I guessed.”
- Reviewing mistakes with curiosity rather than frustration.
- Recognizing personal confusion patterns such as IV/V swaps or I/vi swaps.

## Progression map

The curriculum is organized as short learning loops. Each loop can fit inside a 5-minute session, and each stage can be revisited through spaced repetition.

| Stage | Focus | Primary question | New material | Review material | Mastery signal |
| --- | --- | --- | --- | --- | --- |
| 0 | Listening posture | “Where does home feel like?” | Complete vs incomplete endings | None | Learner can describe arrival vs tension. |
| 1 | Tonic recognition | “Can you find Do?” | Tonic after melodies and cadences | Arrival judgment | Learner finds tonic across several keys. |
| 2 | I and V | “Home or wants home?” | I, V, V-I | Tonic recognition | Learner separates rest from pull. |
| 3 | Add IV | “Home, lift, or pull?” | IV, IV-I, I-IV-V | I/V distinction | Learner distinguishes IV from V. |
| 4 | Campfire triads | “What chord role did you hear?” | I, IV, V in short loops | Tonic and cadence checks | Learner identifies I/IV/V in common patterns. |
| 5 | Add vi | “Major home or minor cousin?” | vi, I-vi, I-V-vi-IV | I/IV/V loops | Learner distinguishes I from vi in context. |
| 6 | Progression prediction | “What probably comes next?” | Common four-chord loops | All earlier functions | Learner predicts common next chords. |
| 7 | Key transfer | “Same role, new key?” | Function-to-chord-name mapping | Progression recognition | Learner maps patterns across keys. |
| 8 | Melody relationship | “What is the tune doing over the chords?” | Simple melodic scale degrees | Tonic, functions, progressions | Learner hears melody landing tones. |
| 9 | Instrument pathways | “How do I play this role?” | Guitar, piano, harmonica, voice views | Shared functional curriculum | Learner transfers the same role to an instrument. |

## The learner’s first session

The first session should feel like being welcomed by a patient mentor, not tested by a theory exam. It should last about 5 minutes and establish the central habit: listen for home first.

### First session objective

The learner learns that music has a felt center called **home**, and that the first job is to notice whether the sound has arrived home or is still asking for resolution.

### First session flow

1. **Warm welcome, 20 seconds**
   - “Let’s train your ear for campfire musicianship. Today, just listen for home. No theory quiz yet.”

2. **Guided listening, 60 seconds**
   - Play a short piano phrase ending on I.
   - Say: “That settled feeling is home.”
   - Play a similar phrase ending on V.
   - Say: “That one is still leaning forward. It wants to go home.”

3. **Arrival check, 90 seconds**
   - Present 6 examples.
   - Learner answers: “Home” or “Not home yet.”
   - After each response, replay the resolution so the body learns the sensation.

4. **Find Do, 90 seconds**
   - Play a tiny progression, then ask the learner to hum, imagine, or tap when they hear the home note.
   - Show the answer as “Do,” not as an absolute note name at first.

5. **Confidence check, 30 seconds**
   - Learner rates: “Sure,” “Maybe,” or “Guess.”
   - The coach normalizes uncertainty: “Guessing is useful data. We’ll make that sound familiar.”

6. **Tiny win summary, 30 seconds**
   - “Today you practiced hearing home. Next time we’ll compare home with the chord that wants to go home.”

### First session example exercises

- “Did that phrase land home?”
- “Which ending feels finished?” with A/B playback.
- “Hum the note that would make this feel complete.”
- “After the final chord, choose: settled / leaning.”

### First session mastery criteria

The first session does not require mastery. It requires orientation. A good first-session outcome is:

- At least 4 of 6 arrival checks correct, or
- Any accuracy level with improving confidence calibration and willingness to continue.

If the learner struggles, the next session repeats arrival judgment with more obvious examples, slower pacing, and immediate resolution playback.

## The learner’s first week

The first week builds a small, usable hearing vocabulary: home, wants home, lift away from home, and the beginning of chord-role labels.

### Day 1: Hear home

- Focus: complete vs incomplete endings.
- Labels: home, not home, Do.
- Exercises: arrival checks, hum Do, confidence rating.
- Mentor phrase: “You are learning the feeling of arrival.”

### Day 2: Meet I and V

- Focus: I as home chord; V as the chord that wants to return.
- Labels: I and V, with “home” and “wants home” always attached.
- Exercises: I/V identification, V-I resolution, predict whether the next chord is I.
- Mentor phrase: “V is not wrong or tense in a bad way. It is the sound of motion asking to resolve.”

### Day 3: Strengthen tonic in new keys

- Focus: same home-feeling in two or three keys.
- Labels: Do, I, key names as secondary information.
- Exercises: find Do after examples in C, G, D, or F; identify I vs V in each.
- Mentor phrase: “The chord names changed, but the job stayed the same.”

### Day 4: Meet IV

- Focus: IV as lift/opening/broadening; distinguish from V.
- Labels: I, IV, V with functional adjectives.
- Exercises: I-IV-I, I-V-I, IV vs V comparison, “which one pulls harder to I?”
- Mentor phrase: “IV often feels like stepping onto the porch; V feels like turning back toward the door.”

### Day 5: Campfire three-chord loop

- Focus: I, IV, and V in simple accompaniment.
- Labels: Roman numerals and Nashville numbers side by side.
- Exercises: identify the missing chord in I-?-V, choose next chord in I-IV-?, recognize I-IV-V vs I-V-IV.
- Mentor phrase: “With these three roles, you can already support many songs.”

### Day 6: Review and remediation day

- Focus: personalized review based on mistakes and low-confidence answers.
- Labels: only the functions already introduced.
- Exercises: contrast pairs from the learner’s confusion pattern, slower replays, reduced answer choices.
- Mentor phrase: “Review is not going backward. It is how your ear gets dependable.”

### Day 7: First mini jam

- Focus: use I, IV, and V in a musical-feeling loop.
- Labels: function first, chord names second.
- Exercises: listen to a four-measure loop, identify the progression, predict the last chord, map it to one friendly key.
- Mentor phrase: “You are starting to hear like an accompanist: where are we, where did we go, and where are we likely going next?”

### First-week mastery criteria

By the end of week one, the learner is ready to continue if they can:

- Find tonic or judge arrival with about 75% accuracy in supported examples.
- Identify I vs V with about 75% accuracy after hearing a reference I.
- Identify IV vs V above chance and show improving confidence calibration.
- Complete a short I/IV/V progression exercise with hints available.
- Explain in plain language that chord names change by key, but functional roles stay stable.

## Campfire Musician Mode

Campfire Musician Mode is the main practical curriculum mode. It trains the ear to support singing and informal group playing using a small set of high-value harmonic functions.

### Campfire Musician Mode learning goals

- Stay oriented to tonic.
- Hear I, IV, V, and vi as roles.
- Recognize common progressions.
- Predict likely next chords.
- Translate functions into chord names for an instrument.
- Recover from wrong guesses and keep musical time.

### Exercise families

#### 1. Home finder

The learner hears a short phrase or progression and chooses whether it landed home.

Example prompts:

- “Did that arrive home?”
- “Which ending feels more finished, A or B?”
- “Hum the note that would settle this.”

#### 2. Tonic anchor

The learner hears a key-establishing phrase, then identifies or imagines Do after intervening chords.

Example prompts:

- “Hold Do in your mind. Did the last chord return to it?”
- “Tap when the music gets back home.”
- “Sing Do before you reveal it.”

#### 3. Function contrast

The learner compares two functions in a controlled context.

Example prompts:

- “Was that I or V?”
- “Was that IV or V?”
- “Which chord sounds like lift, and which sounds like pull?”

#### 4. Missing chord

The learner hears a progression with one omitted or hidden answer.

Example prompts:

- “I - IV - ?”
- “I - ? - V - I”
- “Which chord completes the loop?”

#### 5. Progression ID

The learner chooses which functional progression was played.

Example prompts:

- “Did you hear I-IV-V or I-V-IV?”
- “Was that I-V-vi-IV or vi-IV-I-V?”
- “Which card matches the four-chord loop?”

#### 6. Next-chord prediction

The learner hears the beginning of a common progression and predicts the next likely chord.

Example prompts:

- “I - V - vi - what commonly comes next?”
- “vi - IV - I - what is likely next?”
- “We are on V. What chord would make this feel home?”

#### 7. Function-to-chord-name translation

After the functional answer, the learner maps it to chord names in a specific key.

Example prompts:

- “In G, I-IV-V is G-C-D.”
- “In C, I-V-vi-IV is C-G-Am-F.”
- “If Do is D, what is V?”

#### 8. Play-along readiness

The learner follows a simple loop visually and aurally, preparing for later instrument-specific playing.

Example prompts:

- “Count four beats on each chord.”
- “Say the functions while the loop plays.”
- “Now say the chord names in this key.”

#### 9. Confidence reflection

The learner marks how the answer felt.

Example prompts:

- “Was that sure, maybe, or a guess?”
- “Did you know it from the sound, or did you reason it out?”
- “Would you want this card again soon?”

## Teaching tonic recognition

Tonic recognition is taught as a felt musical orientation before it is named as theory.

### Sequence

1. **Arrival sensation**
   - The learner hears resolved and unresolved endings.
   - The language is physical and experiential: settled, home, resting, leaning, unfinished.

2. **Do as home note**
   - Once the learner feels arrival, the home note is named Do.
   - The app asks the learner to hum or imagine Do, even if sung input is not evaluated.

3. **I as home chord**
   - The tonic chord is introduced as the chord built around home.
   - The learner hears the relationship between Do in the melody and I in the harmony.

4. **Key names as later labels**
   - Absolute note names are introduced only after the function is clear.
   - The learner sees that Do can be C, G, D, F, or another pitch depending on the key.

5. **Transfer checks**
   - Tonic exercises rotate keys gradually.
   - The learner must recognize home without relying on pitch height or a memorized starting note.

### Example tonic exercises

- Resolved vs unresolved cadence.
- Same melody with two endings: one on Do, one on Re or Ti.
- Hum Do after a I-V-I progression.
- Hear a four-chord loop and tap when I returns.
- Choose which of two final notes is Do.

### Tonic mastery criteria

A learner shows tonic mastery when they can:

- Identify resolved endings with at least 80% accuracy across several keys.
- Hum or internally predict Do before reveal in supported examples.
- Reorient after a short modulation-free progression.
- Maintain confidence calibration: high-confidence answers are usually correct, and low-confidence answers are flagged for review.

## Introducing I, IV, and V

I, IV, and V are introduced as characters in a musical story, not as abstract Roman numerals.

### I: home

- Sound: settled, complete, resting.
- Body cue: “You could stop here.”
- Movable Do relation: I is built on Do.
- Nashville relation: 1 chord.
- Example in C: C.
- Example in G: G.

### V: wants home

- Sound: pull, expectation, almost finished.
- Body cue: “This wants to go back.”
- Movable Do relation: V is built on Sol and often contains Ti, which leans to Do.
- Nashville relation: 5 chord.
- Example in C: G.
- Example in G: D.

### IV: lift away from home

- Sound: open, broad, lifted, less tense than V.
- Body cue: “We stepped away from home, but not with the same pull as V.”
- Movable Do relation: IV is built on Fa.
- Nashville relation: 4 chord.
- Example in C: F.
- Example in G: C.

### Teaching order

1. I alone as home.
2. V compared to I.
3. V-I resolution.
4. IV compared to I.
5. IV-I plagal resolution.
6. IV compared directly to V.
7. I-IV-V loops.

### Example I/IV/V exercises

- “Was that home or wants home?”
- “Which chord pulls harder to I?”
- “Hear I-IV-I. Now hear I-V-I. Which middle chord was V?”
- “Complete the progression: I-IV-?”
- “Choose the chord that would support the singer returning to the chorus.”

### I/IV/V mastery criteria

The learner is ready for vi when they can:

- Identify I reliably after a key-establishing cue.
- Distinguish V from I with at least 80% accuracy in supported contexts.
- Distinguish IV from V with at least 70-75% accuracy and improving confidence.
- Recognize at least two common I/IV/V progressions.
- Explain the roles in plain language: home, lift, pull.

## Introducing vi

vi is introduced after I, IV, and V are musically familiar. It should feel like an expansion of the campfire palette, not a sudden theory jump.

### Core idea

vi is the relative minor-family chord: it shares some emotional and pitch material with I, but it does not feel like the same stable home in the major-key campfire context.

### Teaching sequence

1. **I vs vi color contrast**
   - Play I and vi in the same key.
   - Ask: “Which one feels like bright home, and which one feels like the thoughtful minor cousin?”

2. **I-vi motion**
   - Show that vi can follow I smoothly.
   - Emphasize color shift rather than tension.

3. **vi with IV and V**
   - Place vi inside familiar surroundings: I-V-vi-IV and vi-IV-I-V.
   - The learner hears vi as part of known song grammar.

4. **Common progression recognition**
   - Practice four-chord loops that include vi.
   - Ask for both recognition and prediction.

5. **Key transfer**
   - Map vi to Am in C, Em in G, Bm in D, Dm in F.
   - Keep function first: “vi in G is Em,” not “Em is always vi.”

### Example vi exercises

- “Was that I or vi?”
- “Which chord sounded like the minor cousin of home?”
- “I - V - ? - IV: choose vi or I.”
- “Did the loop start on I or vi?”
- “In G, what chord name is vi?”

### vi mastery criteria

The learner has working vi recognition when they can:

- Distinguish I and vi in the same key with about 75-80% accuracy.
- Identify vi inside I-V-vi-IV after repeated exposure.
- Avoid treating vi as the global tonic unless the exercise intentionally discusses relative minor.
- Map vi to chord names in practiced keys.

## Mistake remediation

Mistakes are treated as diagnostic information. The coach never says “wrong” as a dead end; it identifies the musical confusion and gives the ear a smaller contrast.

### Remediation principles

- **Name the confusion kindly.** “That was a common IV/V mix-up.”
- **Replay with contrast.** Let the learner hear the chosen answer and the correct answer back to back.
- **Reduce answer choices.** Move from four choices to two choices when needed.
- **Return to function.** Use sound words: home, lift, pull, minor cousin.
- **Slow down the context.** Use shorter progressions, clearer voicings, and more space.
- **End with success.** After a miss, give a nearby exercise the learner can answer correctly.

### Common mistake patterns and responses

| Mistake pattern | Likely cause | Remediation |
| --- | --- | --- |
| I mistaken for V | Learner hears stability but not resolution direction | Replay V-I, then I alone; ask which one can stop. |
| V mistaken for IV | Both are non-tonic | Compare IV-I and V-I; ask which middle chord pulls harder. |
| IV mistaken for I | IV feels consonant and broad | Play I-IV-I and ask where the true resting point is. |
| vi mistaken for I | Shared tones and smooth sound | Contrast bright home vs minor cousin; include melody landing on Do over I. |
| Key-specific memorization | Learner recognizes chord names, not roles | Change key immediately while keeping the same function pattern. |
| Low confidence despite accuracy | Learner is correct but unsure | Repeat similar examples and praise the hearing process. |
| High confidence wrong answers | Mislearned cue | Slow down, isolate the contrast, and require confidence reflection. |

### Example remediation script

“Good data. You chose IV, and the answer was V. Both are away from home, so that mix-up makes sense. Listen to IV-I: it relaxes home. Now listen to V-I: it points home more strongly. Try one more with just those two choices.”

## Spaced repetition

Spaced repetition keeps the curriculum dependable across days without turning practice into sterile flashcards.

### What gets scheduled

The review system schedules skills and exercise types, not just individual audio clips. For example:

- Tonic after cadence in G.
- IV vs V contrast in C.
- I vs vi contrast in D.
- I-V-vi-IV recognition in multiple keys.
- Mapping Nashville numbers to chord names in G.

### Review timing

A skill returns sooner when:

- The learner answered incorrectly.
- The learner marked “guess” or “maybe.”
- The learner took a long time to answer.
- The learner has not practiced the skill recently.
- The skill is a prerequisite for upcoming material.

A skill returns later when:

- The learner answered correctly.
- The learner marked high confidence.
- The learner has shown consistency across days.
- The learner has transferred the skill to more than one key.

### 5-minute session structure

A typical 5-minute adaptive session should include:

1. **Warm-up review, 60 seconds**
   - One or two easy wins from known material.

2. **Due review, 120 seconds**
   - Skills scheduled by spaced repetition.

3. **Current focus, 120 seconds**
   - The newest concept or the learner’s main growth edge.

4. **Confidence close, 30 seconds**
   - Quick reflection and encouraging summary.

### Mastery and spacing

Mastery is not a single high score. A skill becomes “durable” when it is demonstrated:

- Correctly.
- With reasonable confidence.
- Across multiple days.
- Across at least two keys.
- In more than one exercise format.

## Learner model adaptation

The learner model adapts future exercises by tracking what the learner can hear, where they hesitate, which confusions repeat, and whether confidence matches accuracy.

### Learner model inputs

- Skill attempted.
- Exercise family.
- Key.
- Chord function or scale degree.
- Progression pattern.
- Correct or incorrect response.
- Selected wrong answer.
- Confidence rating.
- Response time.
- Number of replays.
- Recent practice history.

### Adaptation behaviors

The curriculum adapts by changing:

- **Difficulty**: fewer or more answer choices, shorter or longer examples.
- **Contrast**: isolate the exact confusion pair, such as IV vs V.
- **Key selection**: repeat in a familiar key, then transfer to a new key.
- **Voicing and register**: begin with clear piano voicings, later vary register.
- **Exercise family**: move between recognition, prediction, mapping, and play-along readiness.
- **Review timing**: schedule uncertain skills sooner.
- **Coaching message**: respond to the learner’s pattern, not only to the last answer.

### Adaptation examples

- If the learner misses V as IV three times, the next session includes IV-I vs V-I contrast before full progression ID.
- If the learner gets I-V-vi-IV correct in C but misses it in G, the curriculum schedules key-transfer exercises rather than reteaching the progression from scratch.
- If the learner is accurate but always marks “guess,” the curriculum repeats similar examples with confidence coaching.
- If the learner is confident but wrong on vi, the curriculum returns to I vs vi color contrast and slows the reveal.

## Confidence tracking

Confidence tracking is part of the curriculum, not a vanity metric. It teaches the learner to notice the difference between recognition, reasoning, and guessing.

### Confidence choices

Use simple choices after selected answers:

- **Sure**: “I heard it clearly.”
- **Maybe**: “I had a reason, but I was not certain.”
- **Guess**: “I chose without really hearing it.”

### How confidence is used

- Correct + sure: space the skill farther, but test transfer later.
- Correct + maybe: repeat soon in a similar context to build trust.
- Correct + guess: treat as not yet mastered.
- Incorrect + sure: remediate because the learner may have learned a false cue.
- Incorrect + maybe: provide contrast and a near-repeat.
- Incorrect + guess: simplify and rebuild the sound category.

### Mentor tone

Confidence prompts should feel safe:

- “No penalty for guessing. That tells us what to practice.”
- “You were unsure but correct. Let’s give your ear two more chances to recognize that sound.”
- “High confidence misses are useful; they show us exactly which cue needs retuning.”

## Transfer across keys

Key transfer is introduced early and gently. The learner should not become dependent on one absolute pitch, one hand shape, or one favorite chord set.

### Transfer principles

- Function remains stable while chord names change.
- Start with friendly keys: C, G, D, F, and A as appropriate.
- Introduce new keys through familiar progressions.
- Keep Do movable.
- Use the same sound examples transposed to new keys.
- Ask for functional answers before chord-name answers.

### Transfer sequence

1. Hear I-V-I in C.
2. Hear the same I-V-I relationship in G.
3. Ask what stayed the same: home, pull, return.
4. Show chord names only after the learner identifies the function.
5. Practice I-IV-V in several keys.
6. Practice I-V-vi-IV in several keys.
7. Ask the learner to map a known progression into a requested key.

### Transfer mastery criteria

The learner shows transfer when they can:

- Recognize I, IV, V, and vi in at least three keys.
- Map a functional progression to chord names in practiced keys.
- Avoid calling a chord by the same function in every key.
- Recognize a familiar progression after transposition.

## Relating movable Do, Nashville numbers, Roman numerals, and chord names

The curriculum treats these as four views of the same musical function.

| Concept | Best use | Example in C | Example in G | Learner-facing explanation |
| --- | --- | --- | --- | --- |
| Movable Do | Hearing melody and tonal center | Do = C | Do = G | “Do is home in the current key.” |
| Nashville number | Practical accompaniment shorthand | 1-4-5 | 1-4-5 | “Numbers tell players the chord roles.” |
| Roman numeral | Theory and harmonic analysis | I-IV-V | I-IV-V | “Roman numerals name the same roles in theory language.” |
| Chord name | Instrument execution | C-F-G | G-C-D | “Chord names tell your hands what to play in this key.” |

### Teaching relationship

- Start with sound: home, lift, pull.
- Name the sound as I, IV, or V.
- Show the matching Nashville number: 1, 4, or 5.
- Connect melody using movable Do: Do, Fa, Sol as roots or tonal anchors.
- Translate to chord names only when a key is specified.

### Example explanation

“If the key is G, Do is G. The I chord is G, the IV chord is C, and the V chord is D. If the key changes to C, the roles stay I-IV-V, but the chord names become C-F-G.”

## Melodies

Melodies are introduced after the learner has a stable sense of tonic and a working I/IV/V vocabulary. They should support accompaniment hearing, not distract from it.

### When melodies are introduced

Melodies enter in Stage 8, after the learner can:

- Hear tonic reliably.
- Identify I, IV, and V in simple contexts.
- Recognize at least one common progression.
- Understand that Do moves by key.

Small melodic fragments may appear earlier for tonic recognition, but full melody-harmony relationship exercises wait until the harmonic foundation is stable.

### Melody learning objectives

- Hear whether a melody note feels like Do, Mi, Sol, La, Fa, or Ti.
- Notice when a melody strongly implies a chord function.
- Hear landing tones at phrase endings.
- Use melody to help predict chords.
- Sing or hum short scale-degree patterns.

### Example melody exercises

- “The melody ended on Do. Did the harmony also feel like I?”
- “Did the phrase lean on Ti before resolving to Do?”
- “Which chord best supports this melody note: I or V?”
- “Hum the last three notes as scale degrees: Sol-Mi-Do.”
- “Listen to the tune over I-V-vi-IV. Where did the melody feel most settled?”

### Melody mastery criteria

The learner is successful when they can:

- Identify simple melodic arrivals on Do.
- Use melody as a clue without ignoring harmonic context.
- Recognize common landing tones over I, IV, V, and vi.
- Sing or imagine short movable-Do patterns.

## Instrument pathways: guitar, piano, harmonica, and voice

Later instrument support should use the same underlying functional concepts. The learner should not feel like they are starting over when switching instruments.

### Shared conceptual spine

All instrument pathways share:

- Tonic recognition.
- Movable Do orientation.
- I, IV, V, and vi function.
- Common progression recognition.
- Next-chord prediction.
- Confidence tracking.
- Spaced review.
- Key transfer.

### Guitar pathway

Guitar adds:

- Open-chord mappings for friendly keys.
- Capo-aware transposition as a practical extension of movable Do.
- Strumming patterns for I/IV/V/vi loops.
- Recovery habits: keep the rhythm going even after a wrong chord.

Example: The learner hears I-V-vi-IV, identifies the functions, then sees G-D-Em-C for a guitar-friendly key.

### Piano pathway

Piano adds:

- Root-position and simple inverted triads.
- Left-hand roots with right-hand chord shells.
- Visual keyboard mapping of scale degrees.
- Voice-leading awareness between I, IV, V, and vi.

Example: The learner hears IV-I, identifies lift-to-home, then plays a simple F-to-C or C-to-G motion depending on the key.

### Harmonica pathway

Harmonica adds:

- Key-of-harmonica orientation connected to Do.
- Simple first-position melody discovery.
- Later cross-harp concepts only after tonic and function are secure.
- Hole/blow/draw notation as an instrument view of the same scale-degree map.

Example: The learner hears a melody ending on Do, then sees which hole/blow-draw location produces Do on the selected harmonica.

### Voice pathway

Voice adds:

- Humming Do.
- Singing call-and-response scale-degree fragments.
- Singing roots of I, IV, V, and vi.
- Matching sung phrases to functional harmony.
- Confidence building for informal group singing.

Example: The learner hears V-I, then sings Sol-Do or Ti-Do to feel the resolution.

## Mastery criteria by curriculum layer

| Layer | Emerging | Practicing | Mastered for current stage |
| --- | --- | --- | --- |
| Tonic | Notices some resolved endings | Finds Do with cues | Finds home across keys and contexts |
| I/V | Understands home vs pull | Identifies I and V with occasional misses | Reliably hears V resolving to I |
| IV | Hears IV as non-tonic | Sometimes confuses IV and V | Distinguishes lift from pull |
| vi | Notices minor color | Identifies vi in familiar loops | Distinguishes vi from I across keys |
| Progressions | Recognizes fragments | Identifies common loops with choices | Predicts likely next chords |
| Key transfer | Maps in one key | Transfers with support | Recognizes function before chord name |
| Melody | Hears Do endings | Names simple scale degrees | Uses melody to support accompaniment |
| Confidence | Rates randomly | Notices sure/maybe/guess | Confidence aligns with accuracy |

## Example 5-minute sessions after week one

### Session A: IV vs V repair

- 30 seconds: hear I in the current key.
- 60 seconds: compare IV-I and V-I.
- 90 seconds: choose IV or V in two-chord examples.
- 90 seconds: identify the middle chord in I-?-I.
- 30 seconds: confidence reflection.
- 30 seconds: mentor summary and one easy success.

### Session B: Add vi to a known loop

- 45 seconds: review I, IV, V.
- 60 seconds: hear I vs vi color contrast.
- 90 seconds: choose I or vi in context.
- 90 seconds: identify I-V-vi-IV with answer cards.
- 35 seconds: map the progression to one key.
- 25 seconds: confidence reflection.

### Session C: Key transfer mini-jam

- 45 seconds: hear I-IV-V in C.
- 45 seconds: hear the same functions in G.
- 90 seconds: identify functions in a new key.
- 90 seconds: map I-IV-V and I-V-vi-IV to chord names.
- 30 seconds: predict the next chord in a loop.
- 30 seconds: mentor summary.

## Remediation strategy catalog

### Contrast narrowing

If the learner misses a four-choice question, reduce to the two most confused options. For example, change I/IV/V/vi to IV/V only.

### Immediate replay

Replay the original example, then the correct answer, then the learner’s chosen answer if musically useful. Ask what changed in feeling.

### Function words

Return to plain-language roles:

- I: home.
- IV: lift.
- V: pull.
- vi: minor cousin.

### Tonic reset

Before retrying, replay I or a short I-V-I so the learner is reoriented.

### Slower context

Use slower tempo, simpler voicing, and shorter examples.

### Same pattern, new key

If a learner is relying on chord names, repeat the same functional progression in a different key.

### Same key, new pattern

If the learner is overwhelmed by transposition, keep the key stable and vary only the progression.

### Confidence repair

If the learner is accurate but unsure, repeat similar items and explicitly name the success: “Your ear heard the pull to home three times in a row.”

## Curriculum guardrails

- Do not center the early curriculum on isolated interval naming.
- Do not introduce too many labels before the learner has heard the function.
- Do not require instrument technique before functional hearing is established.
- Do not punish guessing; use it for scheduling and coaching.
- Do not equate one correct answer with mastery.
- Do not let chord names replace functional understanding.
- Do not introduce melodies so early that they obscure tonic and harmony.

## Definition of curriculum success

The curriculum succeeds when a learner can sit with a simple song, find home, hear the likely I/IV/V/vi movement, choose practical accompaniment chords in a friendly key, and recover from uncertainty with confidence. The desired outcome is not perfect theory labeling; it is becoming the kind of musician who can listen, join in, and support the song.
