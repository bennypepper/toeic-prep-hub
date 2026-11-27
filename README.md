# TOEIC Prep Hub

Interactive TOEIC Listening & Reading mock exams with local multi-speaker audio, EN/ID interface switching, dark/light mode, and an AI-tutor-ready Markdown study library.

**Live Mock Exam Hub (GitHub Pages):** https://bennypepper.github.io/toeic-prep-hub/

---

## What Is Included

### 1. Interactive Mock Exam Center (`index.html`)

Open the live GitHub Pages link (or open `index.html` locally after cloning) to practice **1,100 curated questions** across 6 exams with **296 Supertonic-3 ONNX AAC-LC (`.m4a`) audio tracks** and **WebP** photographs:

| Exam | Questions | Time | Audio Tracks | Format |
| :--- | :---: | :---: | :---: | :--- |
| **Half-Length Mock Exam** | 100 (50 L / 50 R) | 60 min | 26 tracks | Warm-up diagnostic covering Parts 1 to 7 |
| **TOEIC Full Mock Exam 1** | 200 (100 L / 100 R) | 120 min | 54 tracks | Post-2016 format (Barron's New TOEIC Exam A) |
| **TOEIC Full Mock Exam 2** | 200 (100 L / 100 R) | 120 min | 54 tracks | Post-2016 format (Barron's New TOEIC Exam B) |
| **TOEIC Full Mock Exam 3** | 200 (100 L / 100 R) | 120 min | 54 tracks | Post-2016 format (Barron's Practice Exam 1 & 2) |
| **TOEIC Full Mock Exam 4** | 200 (100 L / 100 R) | 120 min | 54 tracks | Post-2016 format (Barron's Practice Exam 3 & 4) |
| **TOEIC Full Mock Exam 5** | 200 (100 L / 100 R) | 120 min | 54 tracks | Post-2016 format (Barron's Practice Exam 2 & 4) |

Features:
- **Homepage Dashboard:** Track exam status (Not Started, In Progress, Completed), answered counts (`X / 1100`), best scaled scores (10 to 990), and aggregated Part 1 to 7 accuracy.
- **EN / ID Toggle & Dark / Light Mode:** Switch the UI cleanly between English and Bahasa Indonesia (while keeping TOEIC test questions in English) and choose between warm-paper Light Mode or comfortable warm-charcoal Dark Mode.
- **Exam Mode & Practice Mode:** Play tracks once with Pause/Resume in Exam Mode, or replay and seek freely in Practice Mode. Playback speed supports 0.9x, 1.0x, and 1.1x.
- **Automatic Local Autosave:** Answers, remaining time, and graded results persist in browser `localStorage` so you can pause a 2-hour session and resume later.
- **Full Review Mode & AI Tutor Export:** Unlock official explanations and complete audio transcripts on submission, and click **Copy Results for AI Tutor** to log mistakes and drill weak topics.

### 2. AI Tutor & Study Library (`AGENTS.md`, `study/`, `markdown/`)

Clone this repo and open it in any agentic platform (Antigravity, Claude Code, Codex, Cursor, Gemini CLI). `AGENTS.md` automatically configures the agent as a TOEIC tutor that quizzes you without spoiling answers, verifies keys against source files, teaches distractor traps, and maintains `study/mistake_log.md`.

| Path | Description |
| :--- | :--- |
| [`AGENTS.md`](./AGENTS.md) | AI Tutor instructions and drill workflows |
| [`study/4_day_plan.md`](./study/4_day_plan.md) | 4-day intensive prep schedule (adaptable to any timeline) |
| [`study/mistake_log.md`](./study/mistake_log.md) | Clean score tracker and error log template |
| [`markdown/01_barrons_practice_exams/`](./markdown/01_barrons_practice_exams/INDEX.md) | 6 practice exams (Exams 1 to 4 + New TOEIC Exams A & B) with explanations and scripts |
| [`markdown/02_collins_skills_toeic/`](./markdown/02_collins_skills_toeic/INDEX.md) | Part 1 to 7 strategy guides, common distractor traps (*Get It Right*), and drills |
| [`markdown/03_vocabulary_2020/`](./markdown/03_vocabulary_2020/INDEX.md) | High-utility business and exam vocabulary reference |
| [`markdown/04_barrons_toeic_test/`](./markdown/04_barrons_toeic_test/INDEX.md) | Targeted grammar, vocabulary, and reading drills plus 4 extra Model Tests |

---

## Quick Start

### Option A: Practice Immediately in Your Browser
1. Open **https://bennypepper.github.io/toeic-prep-hub/**.
2. Click **Test Audio** in the top bar to check your headphones or speakers.
3. Start with the **Half-Length Mock Exam** (60 min) as a diagnostic, then work through **Full Mock Exams 1 to 5**.

### Option B: Clone Locally + Study With an AI Agent
```bash
git clone https://github.com/bennypepper/toeic-prep-hub.git
cd toeic-prep-hub
```
1. Open `index.html` directly in your browser (or run `python -m http.server 8000` and open `http://localhost:8000`).
2. Open the folder in your AI agent platform and paste the output of **Copy Results for AI Tutor** from any completed mock exam.

---

## Repository Layout

```text
toeic-prep-hub/
├── index.html          # Unified 6-exam web app (1,100 Qs, WebP images, EN/ID, Dark/Light)
├── audio/
│   ├── half_100q/      # 26 AAC-LC .m4a tracks (Half-Length Mock Exam)
│   ├── exam_1/         # 54 AAC-LC .m4a tracks (Full Mock Exam 1)
│   ├── exam_2/         # 54 AAC-LC .m4a tracks (Full Mock Exam 2)
│   ├── exam_3/         # 54 AAC-LC .m4a tracks (Full Mock Exam 3)
│   ├── exam_4/         # 54 AAC-LC .m4a tracks (Full Mock Exam 4)
│   └── exam_5/         # 54 AAC-LC .m4a tracks (Full Mock Exam 5)
├── study/
│   ├── 4_day_plan.md   # Intensive prep schedule
│   └── mistake_log.md  # Personal score & error tracker template
├── markdown/           # 46 chapter-split Markdown reference files
├── AGENTS.md           # AI Tutor system instructions
└── README.md
```
