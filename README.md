# DSGN 105 — Digital Imaging

The student site. **Nothing in `docs/` is edited by hand.**

The source of truth is the course design folder:

```
_0 2026/DSGN Program/program-graphic-design/03_courses/DSGN-105/
  01_design/   glossary · rubrics · assessments
  02_source/   week-01 … week-08
```

Change the markdown, then:

```bash
python3 build.py
```

`docs/` is regenerated and GitHub Pages serves it.

## What is published, and what is not

**Published** — `01-lesson`, `04-lab`, `05-assignment`, the ON SCREEN layer of
`02-slides`, and the reference set: glossary, competency rubric, campaign brief,
campaign rubric, critique rubric, review list.

**Withheld** — `00-week-outline`, `03-demo`, `06-instructor-guide`, and
`02a-interactive-*`, which is a build spec carrying the answer key and the
feedback for every wrong answer.

Also withheld: course specification, course outline, assessment evidence, module
plans, readings-and-viewings (its selection briefs are instructor-facing), the
summative design, and the assessment instructor guide.

Every link is resolved against the published set. A link to a withheld file is
unwrapped to plain text rather than left dangling, and Trello links are dropped —
so nothing in `docs/` points at material students should not have.
