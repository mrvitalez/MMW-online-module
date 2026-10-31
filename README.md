# GE04 Online Modules

Self-paced online modules for **Mathematics in the Modern World**
(Instr. Ryan M. Vitalez, LPT, Rizal Technological University). Students use them on days when class cannot meet in
person.

**Entry point:** https://mrvitalez.github.io/MMW-online-module/ sends students to the student site, which is a
Google Apps Script web app open only to **@rtu.edu.ph** accounts. The instructor has a separate admin site on the
same deployment (`?page=admin`). Setup: [INSTRUCTOR-SETUP.md](INSTRUCTOR-SETUP.md).
Course syllabus: [GE04-Mathematics-in-the-Modern-World-Syllabus.pdf](syllabus/GE04-Mathematics-in-the-Modern-World-Syllabus.pdf).

Each module follows one chapter of the course:

1. **Discussion**: one part per topic of the chapter, with definitions, key formulas, original figures and common
   mistakes.
2. **Worked examples**: solved problems, solutions hidden until opened.
3. **Video**: one free video (cited on the page) that pauses for three multiple-choice questions; answers are
   recorded.
4. **Activity**: 10 graded items plus a reflection. Answers are numbers (decimals or exact values such as `3/8`),
   multiple choice, or a short formula. The student's RTU email is detected automatically; they enter their name,
   student number and block and section, write solutions with a symbol/LaTeX toolbar and live preview, and see their
   score and per-item results on submit.

| # | Module | Topics | Video |
|---|--------|--------|-------|
| 1 | The Nature of Mathematics | Patterns and numbers in nature and the world; the Fibonacci sequence; patterns and regularities organized by mathematics; phenomena predicted by mathematics; nature and occurrences controlled by mathematics for human ends; applications of mathematics | The magic of Fibonacci numbers (Arthur Benjamin, TED) |
| 2 | Mathematical Language and Symbols | Characteristics of mathematical language; expressions vs. sentences; conventions; sets, functions, relations, binary operations; elementary logic; formality | Math isn't hard, it's a language (Randy Palisoc, TEDx) |
| 3 | Problem Solving and Reasoning | Inductive and deductive reasoning; intuition, proof and certainty; Polya's four steps; problem-solving strategies; problems involving patterns; recreational problems | How to Argue - Induction & Abduction (CrashCourse Philosophy #3) |
| 4 | Statistics | Gathering, organizing, representing, analyzing and interpreting data; central tendency; dispersion; relative position; probability and the normal distribution; correlation and regression | Mean, Median, and Mode (CrashCourse Statistics #3) |
| 5 | Logic | Statements and quantifiers; truth tables and tautologies; the conditional and the biconditional; related statements; symbolic arguments; Euler diagrams | How to Argue - Philosophical Reasoning (CrashCourse Philosophy #2) |
| 6 | The Mathematics of Graphs | Graphs and Euler circuits; weighted graphs; planarity and Euler's formula; graph coloring | How the Königsberg bridge problem changed mathematics (TED-Ed) |

Problem sets (answered in the notebook, linked from the home page):

- Problem Set 1: Mathematics in Our World (modules 1, 2; preliminary period)
- Problem Set 2: Reasoning and Statistics (modules 3, 4; midterm period)
- Problem Set 3: Logic and Graphs (modules 5, 6; final period)

The discussions, examples, figures and problems are original and follow the course syllabus and the instructor's
presentations; no text or figures are copied from the reference books. Videos: TED, TEDx and TED-Ed
(CC BY-NC-ND 4.0) and CrashCourse (CC BY 4.0). Videos can be changed in the admin site.

## Files

```
index.html, modules/      Entry pages that send visitors to the RTU-only student site
assets/config.js          The student site URL (set once by the instructor)
assets/style.css          Shared styles (Indigo with Golden Yellow theme)
content/                  Lessons, activities, problem sets, manifest and syllabus (no answers)
img/                      Figures and the university seal
syllabus/                 The course syllabus (PDF), opened by the Syllabus button
apps-script/              Code for the Apps Script project: Code.gs, Student.html, Admin.html, Styles.html
```

The answer key and the video question answers are **not** in this repository. They are seeded from a private
`Seed.gs` file and then kept only in the instructor's Google Sheet.
