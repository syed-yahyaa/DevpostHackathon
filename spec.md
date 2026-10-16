#SUMMARY
Every one of us has been there. You’re stuck on a bug at 2 AM, the error message might as well be written in another language,
and you finally copy a fix from the internet.It works. But you have no idea why.That’s the real problem.
Most tools hand you the answer, not the understanding. So the same bug comes back next week.
And for many learners here in Pakistan, it’s harder still: we think in Urdu, but we learn in English.So we built Bug Autopsy.
You paste your broken code,and instead of a wall of red text, you get a case file.The crime scene. The suspects. 
The exact line that did it.And the fix, explained in English or Roman Urdu, whichever clicks for you.
Then a short quiz checks whether you really got it, because fixing a bug once is good, but never making that mistake again is better.
Bug Autopsy doesn’t just fix your code. It teaches you to think like a debugger.



# Bug Autopsy 🔬

> A detective-style AI that investigates code bugs like a crime scene, explaining them in plain English or Roman Urdu.

## Problem
Beginners are intimidated by error messages and struggle to understand why their code breaks.
Existing tools give a fix but don't teach the cause.

## Solution
The user pastes buggy code. The app generates an investigation report:
Crime Scene, Suspects, Culprit line, Fix, and a short quiz to check understanding.
Everything explained, not copy-pasted. (Even option of roman urdu)

## Target Users
- CS/IT students and beginners
- Self-taught developers
- Roman Urdu-speaking learners

## Key Features
1. Code input with multi-language support
2. Detective-style report (Crime Scene → Suspects → Culprit → Fix)
3. English / Roman Urdu toggle
4. Mini quiz (3 questions) to confirm understanding
5. Copy and share the report

## User Flow
1. Paste code
2. Click "Investigate"
3. Read the report
4. Take the quiz
5. Copy the fixed code

## Tech Stack
- Frontend: React + Tailwind
- AI: Claude API
- Hosting: Vercel / GitHub Pages

## Architecture
Browser UI → Claude API (structured JSON response) → Report renderer

## Scope
**In scope:** bug analysis, report, quiz, language toggle
**Out of scope:** IDE plugin, user accounts, code execution

## Milestones
- [ ] UI skeleton
- [ ] API integration
- [ ] Report rendering
- [ ] Quiz and language toggle
- [ ] Polish and demo

## Risks
- AI may misdiagnose a bug → show a confidence label
- Long code may be slow → input size limit and loading state

## Success Criteria
- Report generated in under 30 seconds
- A beginner understands the bug after one read
- Smooth 60-second demo

## Team
- Zohaib (Killer), builder is tarhan ki spec.md ki file banani hai
- Yahya
- Rafay
- Ibtisam
