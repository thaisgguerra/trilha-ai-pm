# AI PM Path (Trilha AI PM)

A bilingual (Portuguese and English) learning platform to prepare for AI Product Manager roles.

Live site: https://thaisgguerra.github.io/trilha-ai-pm

## Problem

Content for aspiring AI PMs is scattered across courses, papers, blog posts and videos. Most of it covers either the technology or product management, not both. And reading alone does not prepare you for interviews: you need practice, feedback and a reason to come back every day.

## Target user

Product managers moving into AI products, especially those preparing for interviews at international tech companies.

## Solution

A single place that combines a structured learning path, active practice and interview preparation, with light gamification to build a daily habit.

## Key features

| Area | What it does |
|---|---|
| Learning path | 39 lessons in 10 modules, from AI fundamentals to evals, agents, RAG, metrics, experimentation, strategy and AI Centers of Excellence |
| Lesson quizzes | 5 questions per lesson with difficulty levels, points and explanations |
| Mock exam | Timed or study mode, filtered by module, with a history of results |
| Flashcards | AI and PM terms, interview questions and personal interview answers, with spaced repetition |
| Matching game | Match technical terms to their meanings, in flashcards and inside each lesson |
| Interview practice | Mock interviews by question type and company style, scored with a rubric (works when the app runs inside Claude) |
| AI tutor | Answers questions about each lesson (works when the app runs inside Claude) |
| Lab | Interactive tools: confusion matrix, sample size, unit economics and a SQL editor |
| Templates | PRD, eval plan, launch checklist, risk register, PR/FAQ and decision doc |
| Big tech guide | Real AI product cases and how leading companies approach AI PM interviews |
| Gamification | XP, daily goal, streak, combos, achievements and a celebration screen after each lesson |
| Glossary tooltips | Technical terms are underlined and explained on hover or tap |

## Product decisions

- **One file, no backend.** The whole app is a single `index.html`. It is easy to host, fast to load and simple to update.
- **Progress stays with the user.** Progress is saved in the browser and can be exported and imported as a backup.
- **Bilingual by default.** Lessons are in Portuguese, while interview practice focuses on English, the language of the target roles.
- **Practice over reading.** Every lesson ends with questions, a matching game and a link to the tutor, because retention comes from active recall.
- **Gamification supports learning.** XP rewards real study actions, such as answering questions and reviewing cards, not just page views.
- **No confidential data.** Examples use generic descriptions instead of client names.

## Success metrics

- **Habit:** days with activity per week and streak length
- **Learning:** first-try accuracy per module and mock exam scores over time
- **Interview readiness:** interview answers marked as ready and rubric scores in mock interviews
- **Coverage:** lessons completed out of 39

## How to use

1. Open the site and enter the access password.
2. Start with Module 1, or pick up where you left off on the home page.
3. Finish each lesson with the quiz and the matching game.
4. Review due flashcards every day to keep your streak.
5. Use the mock exam and interview practice to find gaps.

## How to update

1. Replace `index.html` in this repository with the new version, keeping the exact file name.
2. Commit the change. GitHub Pages publishes it within a few minutes.

## Roadmap

- Audio mode for lessons
- More cases and questions per module
- Shareable progress summary
- Optional sync of progress across devices

## Tech

HTML, CSS and JavaScript in a single file, hosted on GitHub Pages. The SQL editor loads AlaSQL on demand.
