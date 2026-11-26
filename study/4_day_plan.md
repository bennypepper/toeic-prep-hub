# 4-Day TOEIC Listening & Reading Study Plan

This plan pairs the built-in **Interactive Mock Exam Hub** (`index.html`, featuring 3 audio-enabled exams) with the **Markdown study library** (`markdown/`) for fast strategy resets, grammar/vocab drills, and error review.

---

## Test Format Quick Reference (Current "New TOEIC" Format)

- **Total Time:** 120 minutes | **Total Questions:** 200 | **Score Range:** 10 to 990
- **Section 1: Listening (45 min, 100 Qs):**
  - Part 1: Photographs (6 Qs)
  - Part 2: Question-Response (25 Qs)
  - Part 3: Conversations (39 Qs: 13 sets x 3, incl. 3-speaker & graphic questions)
  - Part 4: Talks (30 Qs: 10 sets x 3, incl. graphic & speaker-intent questions)
- **Section 2: Reading (75 min, 100 Qs):**
  - Part 5: Incomplete Sentences (30 Qs) -> **Target: <= 12 min** (~24 sec/Q)
  - Part 6: Text Completion (16 Qs: 4 passages x 4) -> **Target: <= 8 min** (~30 sec/Q)
  - Part 7: Reading Comprehension (54 Qs: single, double, triple passages) -> **Target: 55 min** (~1 min/Q)

> **Golden Rule of TOEIC Reading:** Most test-takers lose points not because Part 7 is hard, but because they spend 25+ minutes on Parts 5 & 6 and run out of time on the last 15 questions. **Never spend >30 seconds on a Part 5 question.**

---

## Day 1: Baseline Diagnostic + High-ROI Strategy Reset

**Goal:** Find your exact current score and weakest part immediately.

1. **Take the Half-Length Mock Exam (60 min)**
   - Open `index.html` (or the live GitHub Pages site) and run **Half-Length Mock Exam (100 Qs)** in Exam Mode.
   - Click **Copy Results for AI Tutor** after grading and record your score in [`mistake_log.md`](./mistake_log.md).
2. **Skim Core Trap Patterns (30 to 45 min)**
   - Read the *Quick Guide* and *Get It Right* tips from Collins:
     - [`02_listening_part2_question_response.md`](../markdown/02_collins_skills_toeic/02_listening_part2_question_response.md) (indirect answers & similar-sounding word traps)
     - [`07_reading_part5_incomplete_sentences.md`](../markdown/02_collins_skills_toeic/07_reading_part5_incomplete_sentences.md) (word-form shortcuts)
3. **Log Every Mistake (20 min)**
   - Categorize every missed question into [`mistake_log.md`](./mistake_log.md) (`Grammar`, `Vocab`, `Trap/Distractor`, or `Time`).

---

## Day 2: Full Mock Exam 1 + Targeted Weak-Part Drills

**Goal:** Experience full 2-hour endurance and fix your highest-frequency grammar and listening traps.

1. **Full Timed Simulation: TOEIC Full Mock Exam 1 (120 min)**
   - Open `index.html` and complete **TOEIC Full Mock Exam 1 (200 Qs)** in Exam Mode under the 120-minute clock.
   - Review all red questions in the Navigator (reading the official explanations and audio transcripts), then export results into [`mistake_log.md`](./mistake_log.md).
2. **Listening Strategy Reset (30 min)**
   - Read Collins strategies for your weaker listening parts:
     - [`03_listening_part3_conversations.md`](../markdown/02_collins_skills_toeic/03_listening_part3_conversations.md)
     - [`04_listening_part4_talks.md`](../markdown/02_collins_skills_toeic/04_listening_part4_talks.md)
   - Key habit: **Pre-read the 3 questions BEFORE the audio starts** and mark answers *during* the audio.
3. **Targeted Grammar Drills (30 to 45 min)**
   - For any weak grammar topic (verb tense, prepositions, clauses, word forms), drill the matching chapter in [`04_barrons_toeic_test/INDEX.md`](../markdown/04_barrons_toeic_test/INDEX.md) (*Analyzing Grammar*).

---

## Day 3: Part 7 Mastery + Full Mock Exam 2

**Goal:** Lock in Part 7 pacing (single, double, and triple passages) and confirm your score jump.

1. **Part 7 Strategy Review (20 min)**
   - Skim [`09_reading_part7_reading_comprehension.md`](../markdown/02_collins_skills_toeic/09_reading_part7_reading_comprehension.md):
     - Read the **question stem first**, scan for proper nouns, dates, prices, and keywords.
     - Save `"NOT mentioned"` and `"inferred"` questions for last within a set.
     - On double/triple passages, expect 1 to 2 **cross-reference questions** linking two documents.
2. **Full Timed Simulation: TOEIC Full Mock Exam 2 (120 min)**
   - Complete **TOEIC Full Mock Exam 2 (200 Qs)** in `index.html` under full Exam Mode conditions.
   - Check the **Part-by-Part Accuracy** panel on the homepage to confirm improvement across Parts 1 to 7.
3. **Update `mistake_log.md`** with remaining recurring mistakes.

---

## Day 4: Mistake Log Sweep, High-Frequency Vocab & Rest

**Goal:** Consolidate gains, review all mistakes, and arrive fresh. Do not cram a heavy new 2-hour mock late at night.

1. **Mistake Log Sweep (45 min)**
   - Re-attempt every question logged in [`mistake_log.md`](./mistake_log.md) without looking at the answer. Verify you can explain *why* the right answer works and *why* the distractor is wrong.
2. **Light Speed Warmup (20 to 30 min)**
   - Do 20 quick Part 5 questions from [`10_reading_practice_test.md`](../markdown/02_collins_skills_toeic/10_reading_practice_test.md) or Exams 1 to 4 in [`01_barrons_practice_exams/INDEX.md`](../markdown/01_barrons_practice_exams/INDEX.md).
3. **Business Vocabulary Skim (20 min)**
   - Review your saved words in `mistake_log.md` plus high-utility words from [`vocabulary_all.md`](../markdown/03_vocabulary_2020/vocabulary_all.md).
4. **Logistics & Sleep**
   - Prepare ID, test confirmation, and get a full night's sleep.

---

## Example Prompts for Your AI Agent

Paste any of these prompts in a chat session inside this repo:
- *"Here are my mock exam results from index.html. Analyze my weakest parts, explain my missed questions, and update `study/mistake_log.md`."*
- *"Quiz me on 15 timed Part 5 questions from Collins Reading Practice Test. Hide the answers until I submit."*
- *"Give me a Part 6 passage + 4 questions and explain any grammar traps I miss."*
- *"Drill me on 10 Part 5 questions focused on prepositions vs. conjunctions from Barron's Analyzing Grammar."*
