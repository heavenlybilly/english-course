# Instructions for Working on the English Course

This repository contains a static, self-study English course for adult Russian-speaking learners with uneven foundations and a target of stable B2.

## Read Before Making Changes

Before changing course content, read:

1. `README.md` — project entry point;
2. `COURSE-DESIGN-SPEC.md` — canonical educational and formatting rules;
3. `COURSE-MAP.md` — canonical lesson sequence;
4. `PROJECT-STATUS.md` — current progress and next work;
5. the relevant guide, template and existing lesson files for the area being edited.

Do not duplicate or replace the canonical specification in this file. If these instructions conflict with `COURSE-DESIGN-SPEC.md`, follow the specification and point out the conflict.

## Collaboration Language

- Explain the section under review and propose decisions to the learner in Russian.
- Keep English examples, words and phrases in English where appropriate.
- Record the final course specification and reusable editorial rules in English.
- Do not silently make a substantial pedagogical decision when the learner asked to review it first.

## Course Principles

- The course is a sequential catalog of prepared explanations, exercises, texts, answer keys and supporting material.
- It must remain usable in an ordinary Markdown reader without AI, adaptive software or a teacher during normal lessons.
- AI may be used externally to check free writing, but lesson completion must not depend on newly generated content.
- Prioritize the learning material itself. Do not add YAML metadata, time estimates, formal production states, mandatory tracking or elaborate quality-control machinery.
- Use contemporary General American English by default. Mention a common British alternative briefly only when it is useful or likely to prevent confusion. Preserve the original variety in authentic material.
- Introduce new material in a sensible order and deliberately bring earlier material back in later practice.
- Do not generate many new lessons at once unless the learner explicitly asks for that scope.

## Lesson Files and Presentation

A normal substantial lesson uses this reading order:

1. `01-lesson.md`
2. `02-practice.md`
3. `03-answers.md`

Specialized lessons may use fewer files when justified by the content.

In learner-facing lesson files:

- use `##` for major sections with clear, specific titles;
- use `###` for sequential tasks such as `Task 1`, `Task 2` and so on;
- use `####` for embedded material such as `Dialogue`, `Short Text`, `Examples`, `Useful Expressions` or `Grammar Pattern`;
- do not use the generic heading `Material`;
- continue task numbering from `01-lesson.md` into `02-practice.md`;
- mirror task numbers, titles and item order in `03-answers.md`;
- write every visible fill-in blank as exactly five underscores inside inline code: `_____`;
- keep punctuation outside the inline-code blank;
- keep explanations, source material and instructions visually easy to distinguish.

Use `templates/` as editorial guidance, not as a rigid form. Preserve unrelated learner changes. The learner prefers Vim rather than Nano when an interactive editor is needed.

## Scope and Progress

- Update `PROJECT-STATUS.md` when completed work materially changes the next step.
- Update `CHANGELOG.md` for meaningful changes to course content, structure or canonical rules.
- Do not mark a lesson complete merely because files exist; check its content and consistency with the current specification and templates.

