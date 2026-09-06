# Changelog

## Unreleased

- Corrected two Stage 0 listening checks: one unsupported False answer now uses Not stated, and one ambiguous Lesson 008 statement now tests an explicitly audible event. Completed the sequential navigation by linking Lesson 007 back to Lesson 006.

- Completed Stage 0 with Lesson 008, Your Starting Point. The lesson combines a new reading text, an authentic VOA listening assignment, vocabulary retrieval, dictionary and pronunciation checks, short writing and optional recorded speaking; its nineteen tasks lead to evidence-based review routes without a single diagnostic score.

- Replaced the generated-audio approach for Listening with curated authentic or professionally published external recordings. Updated the canonical specification and templates to require exact source, publisher, segment, transcript or subtitle availability and recovery information, and redesigned Lesson 006 around two official VOA Learning English conversations without storing audio files or copied transcripts.

- Added Lesson 006, How to Practise Listening, with a complete main lesson, additional practice and answers. Its sixteen tasks establish the sequence from gist and selected details through official-transcript analysis and connected-speech noticing to a final transcript-free listen, response and independent practice.

- Added Lesson 005, IPA, Pronunciation, Stress and Your First Recording, with a complete main lesson, additional practice and answers. Its sixteen tasks introduce selective IPA use, four sound contrasts, word and contrastive sentence stress, dictionary pronunciation checks and a supported two-version recording process focused on intelligibility.

- Added Lesson 004, How to Use an English Dictionary, with a complete main lesson, additional practice and answers. Its twelve tasks teach goal-based lookup decisions, contextual sense selection, parts of speech and dictionary labels, grammatical patterns, example-based learning, pronunciation checks and focused vocabulary notes while retrieving material from Lesson 003.

- Reformatted Lesson 007 using the current learner-facing hierarchy and ten sequential tasks across the main and practice files. Rebuilt the answer headings to mirror every task, standardized visible blanks, and preserved the previously reviewed writing content.

- Standardized fill-in-the-blank prompts as five underscores inside inline code, with punctuation outside the code span. Applied the format to Lessons 001–003 and documented it in the canonical specification to ensure reliable rendering across Markdown readers.

- Established contemporary General American English as the default for course-written language and audio. British variants remain acceptable and are noted concisely only when common or pedagogically relevant; authentic material retains its original variety. Applied the policy to Lessons 001–003, templates and learner notation guidance.

- Reformatted Lesson 003 using descriptive sections, specific `####` content headings and eleven sequential learner-facing tasks across the main and practice files. Rebuilt the answer key to mirror every task title and item order while preserving the eight target expressions and delayed review.

- Reformatted Lesson 002 using the adopted learner-facing hierarchy: descriptive `##` sections, specific `####` content headings, eight sequential `###` tasks across the main and practice files, and matching answer sections. Removed the previous composite task codes without changing the lesson's learning content.

- Adopted the readable learner-facing Markdown format demonstrated in Lesson 001. Major sections use `##`, numbered tasks use `###`, and embedded learning content uses `####` with a specific heading such as Dialogue or Short Text. Removed generic Material headings and composite task codes from the canonical specification, templates and learner notation guide.

- Added a numbered learner-facing terminology reference covering the grammatical, lexical, skills-related and pronunciation terms used throughout the course, with Russian explanations and English examples.

- Added a Russian explanation of every stage in the Lesson 001 learning cycle and clarified that the sequence is a flexible model rather than a rigid structure for every task.

- Rewrote Lesson 001 as a concise Russian-guided demonstration of the course learning cycle: context, noticing, understanding, practice, recall, independent use and later return. Removed duplicated file-management instructions and the unnecessary separate practice file.

- Added Lesson 001, Course Orientation, with its main material, additional practice and complete answer guidance. The lesson introduces adaptive depth, ordered lesson files, recognition versus active use, skill-specific methods and built-in review without mandatory tracking.

- Numbered the files inside every lesson as `01-lesson.md`, `02-practice.md` and `03-answers.md` so Markdown readers display them in the intended order and do not expose the answer key first. Applied the same convention to templates, learner guidance and the canonical specification.

- Moved the prepared lessons into the permanent `00-stage-learning-to-learn-english/` directory and removed temporary prototype terminology from learner-facing material.

- Revised and numbered the learner guides in their recommended reading order. Aligned Reading, vocabulary selection and two-stage AI feedback with the reviewed initial lessons; removed editorial vocabulary labels, checkpoint tracking and any implication of a required permanent progress journal.

- Completed the content review of lessons 002, 003 and 007. Strengthened the goal-based reading strategy, criteria for selecting and storing vocabulary, situational lexical practice, the writing process, basic capitals and punctuation, and two-stage AI feedback. Removed remaining production notes and score tracking. Updated the lesson-type and practice templates to preserve the resulting design decisions.

- Aligned the learner guides, lesson templates and initial lessons 002, 003 and 007 with Course Design Specification 2.0 and Course Map 3.0. Removed required YAML, global exercise IDs, time estimates, CORE/EXTENDED terminology, production QA and progress tracking. Added simple local task numbering, the revised Lesson 007 content and a ready-to-use AI feedback prompt for writing. Removed the obsolete empty `progress/`, `indexes/` and `checkpoints/` directories.

- Revised Course Map as version 3.0 for Course Design Specification 2.0. Added a distinct Speaking track across all stages and a final Speaking Self-Assessment; replaced dynamic personal-error lessons with static diagnostic and remediation material; moved basic connectors earlier; added or clarified plurals, `was/were`, reflexive pronouns, subject–verb agreement, early `can` and requests, dependent prepositions, future in the past, noun clauses, emphatic `do`, basic punctuation and other foundation coverage. Kept lesson numbering 001–486.

- Completed the block-by-block review of Course Design Specification 2.0 and marked it canonical. Simplified the root structure, kept checkpoints inside stage directories, renamed Content Standards to Material Principles, removed the production workflow, and strengthened the final material-first principle.

- Revised Sections 24–32 of the 2.0 draft: required all review to be authored into the static course, removed interval and minimum-repetition tracking, added direct navigation to existing remediation, strengthened mixed Review lessons and diagnostic Checkpoints, and clarified Practice Bank and extensive-input roles.

- Revised Sections 20–23 and 33 of the 2.0 draft: retained the reading policy; defined course audio, authentic assignments and extensive listening; added self-directed pronunciation and speaking practice; and allowed AI feedback for free writing while keeping the prepared course static.

- Revised Sections 10–19 and the static-course assumptions: retained substantial grammar and vocabulary coverage, added an explicit requirement for varied exercise forms, simplified answer numbering, and required complete self-study answer material. Removed dynamic use of personal errors; all error recycling and review must be authored in advance.

- Revised Sections 6–9 of the 2.0 draft: defined the Course Map as an ordered catalogue with adaptive depth, made the three-file lesson layout optional, simplified the normal lesson structure to eight parts, replaced time-based CORE/EXTENDED terminology with Main lesson/Additional practice/Challenge, and added speaking guidance.

- Revised Sections 2, 3, 6 and 22 of the 2.0 draft: replaced the personal level profile with a universal adult Russian-speaking audience, added adaptive depth for uneven foundations, and introduced speaking gradually from optional early practice to later extended production. Full B2 speaking still requires separate interactive assessment.

- Reworked the course specification as a 2.0 draft focused on educational content, topic order, practice and spaced review. Removed required YAML metadata, global exercise IDs, time estimates, automated validation, publication states and formal production QA. Simplified lesson organisation and made progress records optional.

- Added the first working versions of mapped lessons L002, L003 and L007, with CORE, extended practice, answer keys, open-task criteria and delayed retrieval. Timing remained an editorial estimate pending learner trial; the full module was not yet produced.

- Added reusable lesson, practice, and answer templates, structures for all twelve lesson types, and a production checklist with delayed-review planning. Templates are editorial scaffolds, not generated lessons; the canonical specification is unchanged.

- Added five learner guides covering course use, study routine, notation, dictionary use, and progress decisions, based on Course Design Specification v1.0.
- Added empty progress-log, weak-area, and error-database templates and linked them from the project README. No lesson content or learner results were generated.

- Created the initial project structure.
- Added Course Design Specification v1.0 as the canonical design document.
- Added Course Map v2.0 with 486 numbered lessons across 15 stages.
- Verified continuous lesson numbering from 001 through 486 with no gaps or duplicates.
- Corrected lessons 451–486 and their module boundaries using the original text supplied by the learner. Removed the assistant-reconstructed ending, including unsupported CP-6/CP-7 labels and Module 14.1. The final B2 checkpoint is Lesson 485; Lesson 486 is Course Review.
- Restored Course Design Specification v1.0 verbatim from the learner-supplied original (82 sections). Replaced the incomplete transfer and assistant-authored continuation, and reverted the assistant's modification of Section 6. The original specification remains unchanged; the previous claim of reconciliation with a frozen lesson count is superseded by this correction.
