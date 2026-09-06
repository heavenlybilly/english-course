# English Course — Course Design Specification

**Version:** 2.0  
**Status:** Canonical  
**Target:** learners with uneven English foundations → stable B2  
**Format:** Markdown  
**Course language:** English with Russian explanations where useful

---

# 1. Purpose

This specification defines the educational design of the course.

Its purpose is to ensure that:

- subjects appear in a sensible order;
- prerequisites are introduced before dependent material;
- new language is explained clearly and shown in natural English;
- practice is abundant and varied;
- older material returns regularly;
- reading, listening and writing develop throughout the course;
- the learner gradually becomes able to use English independently.

The specification does not define a production system. It does not require metadata, internal databases, automated validation, formal publication states or time estimates.

The exact sequence of lessons is maintained in `COURSE-MAP.md`.

The finished course must work as a static collection of Markdown files and supporting media. The learner should be able to study its explanations, prepared exercises and answer keys without AI, a teacher, adaptive software or newly generated exercises. AI may be used as an external source of feedback for free writing as described in Section 23.

---

# 2. Intended Learner and Entry Point

The course is designed for an adult Russian-speaking learner who has already studied some English but has uneven foundations and wants to progress systematically toward B2.

The learner is not assumed to be a complete beginner. They should normally be able to:

- understand common words and simple sentences;
- extract at least the general meaning from a short accessible text;
- express basic personal information in simple English;
- recognize some common grammar even when productive control is unstable.

The course does not depend on a precise starting CEFR label. Reading, listening, grammar, vocabulary, writing and speaking may be at different levels.

The course should provide a complete and well-ordered route through the necessary foundations. Early lessons should also allow different depths of study:

- a learner with a genuine gap studies the explanation and practice fully;
- a learner with partial but unstable knowledge focuses on contrast, mixed practice and production;
- a learner with secure control may use the checks and move forward;
- material is revisited if later work reveals that the knowledge was not stable.

This adaptation should happen through choices among material already included in the course. It must not depend on newly generated exercises, automatic tracking or a placement system.

The main curriculum should use varied adult topics and should not assume knowledge of one learner's biography, interests or previous mistakes.

Foundation gaps should be repaired with language and topics appropriate to an adult learner.

---

# 3. Target

The long-term target is a stable B2 foundation in:

- reading;
- listening;
- writing;
- progressively developed speaking;
- grammar and sentence control;
- active and passive vocabulary;
- chunks, collocations and phrasal verbs;
- paraphrasing;
- register awareness;
- independent use of English-language material.

Stable B2 means that the learner can work with unfamiliar material, express connected ideas and choose language with reasonable independence. It does not mean error-free English.

Speaking is introduced gradually:

- in the early stages, speaking is optional and mainly supports pronunciation, recall and automaticity;
- in the middle stages, the learner begins short spoken answers, descriptions, retelling and controlled simulations;
- in the later stages, spoken work expands to sustained monologues, argument, retelling and simulated interaction.

The course should build a substantial foundation for spoken B2. Full B2 speaking can only be claimed after separate oral practice and an assessment that includes real interaction.

Completion of the lesson list alone does not prove the target has been reached. Evidence should come from delayed recall, cumulative review, writing, reading and listening with unfamiliar material, paraphrasing, integrated tasks and later spoken production completed with limited support.

No single universal percentage defines B2.

---

# 4. Core Learning Cycle

New material should normally move through the following cycle:

```text
initial context
→ noticing
→ clear explanation
→ focused practice
→ contrast with related material
→ mixed practice
→ connected input
→ productive use
→ delayed retrieval
```

The entire cycle may extend across several lessons. It is not a mandatory heading structure for every lesson.

Reading, listening, writing, review, checkpoint and project lessons may use structures appropriate to their purpose.

English itself should occupy substantially more space than explanations about English. Quantity alone is not enough: examples and exercises must vary meaningfully.

---

# 5. English and Russian

English is the main language of texts, examples, practice and increasingly of instructions and definitions.

Russian may be used when it makes an important explanation substantially clearer, especially for:

- difficult grammar;
- subtle differences in meaning;
- comparison with Russian;
- common interference errors;
- instructions that would otherwise test the wrong skill;
- RU → EN practice.

As a broad editorial guide, meaningful learning material may be approximately:

- 70–80% English at A2+/early B1;
- 80–90% English around B1;
- 85–95% English toward B2.

These percentages are not calculated mechanically.

The course should not translate every sentence or every unknown word. English explanations should not be harder than the language they are meant to explain. Organizational guides may remain in Russian.

## Default Variety of English

Course-written explanations, instructions, examples, answer keys and audio should use contemporary General American English as the default model. This includes spelling, ordinary vocabulary, common grammatical choices and the main pronunciation reference.

British English should be introduced briefly when a difference is common, likely to cause confusion or important for understanding authentic material. Useful examples include `color/colour`, `apartment/flat`, `on the weekend/at the weekend`, `gotten/got` and notable pronunciation differences. Such notes should normally appear once at the first relevant point or in a reference page, not beside every example.

Standard British forms remain acceptable in open learner responses when they are correct and used consistently, unless a task specifically practices an American–British contrast. Authentic texts and recordings should retain their original variety rather than being rewritten to American English.

Course-created pronunciation models should normally use General American English. Exposure to British and other widely encountered accents should still appear gradually in listening material. The goal is comprehension and intelligibility, not imitation of a single accent.

Variant notes must remain concise and should not interrupt the main learning path when the difference is irrelevant to the lesson goal.

---

# 6. Course Architecture

The current Course Map contains 486 numbered lessons across 15 stages, from Stage 0 to Stage 14.

The Course Map is an ordered route and catalog of material, not a calendar or a requirement to give every lesson the same amount of attention.

The number of lessons is not a learning objective. The important requirement is complete, well-ordered coverage with enough practice and review.

The learner may use the route at different depths:

- study an unfamiliar or unstable subject fully;
- concentrate on contrasts, mixed practice and production when the basic rule is already familiar;
- use the checks and move forward when control is secure;
- return to material when later work reveals a gap.

Lessons that introduce essential prerequisites should not be skipped merely because their titles look familiar. Review lessons and checkpoints provide important evidence that earlier material remains available.

The following tracks run through the course:

- grammar;
- active and passive vocabulary;
- chunks and collocations;
- phrasal verbs;
- word formation;
- reading;
- listening;
- writing;
- speaking introduced gradually;
- pronunciation for listening and intelligibility;
- natural English and register;
- error correction;
- RU → EN;
- EN → EN;
- cumulative review;
- extensive input.

A topic may appear naturally before its dedicated systematisation lesson. In that case, the learner may receive a brief meaning-based explanation without being expected to master the full system.

---

# 7. Lesson Organization

A normal substantial lesson may use:

```text
lesson-NNN-title/
├── 01-lesson.md
├── 02-practice.md
└── 03-answers.md
```

`01-lesson.md` contains the main explanation, examples, texts and learning path.

`02-practice.md` contains additional practice for the same lesson.

`03-answers.md` contains answers, suggested answers and evaluation guidance. The numeric prefixes keep the files in their intended reading order and prevent the answer key from appearing first alphabetically.

A specialised lesson may use fewer files when that makes the material easier to use. An orientation, reading, review, project or extensive-input lesson may sometimes use only one or two files. Answers may appear at the end of a short file only when they cannot reveal later tasks prematurely.

Lessons do not require YAML metadata, global exercise IDs, estimated completion times or production comments.

The lesson number, directory name and title are sufficient to connect a lesson to the Course Map.

---

# 8. Lesson Structure

A normal lesson may include:

1. Goal
2. Review
3. Material in Context
4. Explanation
5. Examples
6. Practice
7. Use
8. Check and Takeaway

This is a flexible sequence rather than a compulsory set of headings. Sections may be renamed, combined, expanded, reordered or omitted when the lesson type requires it.

## Learner-Facing Presentation

The visual hierarchy must make explanations, source material and tasks easy to distinguish in a plain Markdown reader:

- `##` introduces a major lesson section with a specific, learner-friendly title;
- `###` introduces a numbered task and states what the learner should do;
- `####` introduces an embedded piece of learning material.

Material headings must name the actual type or purpose of the content, for example:

- Dialogue;
- Short Text;
- Examples;
- Useful Expressions;
- Grammar Pattern;
- Listening Transcript;
- Pronunciation Model.

Do not use a generic heading such as `Material` when a more informative description is available.

Learner-facing tasks should use simple sequential labels such as `Task 1`, `Task 2` and `Task 3`. Composite production codes such as `2A-1` should not appear in finished lessons. The task heading may add a brief purpose, for example `Task 2. Find the Evidence`.

Numbering should continue through `01-lesson.md` and `02-practice.md` when both files belong to one lesson. `03-answers.md` must repeat the task titles, numbers and item order. In the answer file, each task normally uses an `##` heading so the required answer section is easy to find.

The language of headings and instructions should be internally consistent. Russian is appropriate for early explanations and instructions when it materially improves comprehension. English should be retained for the language being studied, examples and established course terms. Do not alternate languages without a clear teaching reason.

## Fill-in-the-Blank Formatting

Every visible blank in a sentence or prompt must use exactly five underscore characters inside inline code formatting:

```markdown
Write it `_____`.
I'll look `_____` up.
```

Punctuation belongs outside the inline-code span. The blank should keep the same visual length regardless of the expected answer, so it does not reveal the number of letters or words.

Do not use raw underscore sequences such as `___` outside inline code. Markdown readers may interpret them as emphasis or hide them, especially near the end of a sentence. Escaped underscore sequences are also discouraged because they make the source file harder to read and edit.

Practice may contain focused exercises, contrasts, mixed practice, RU → EN, EN → EN, error correction, reading, listening, writing or speaking as appropriate.

The learner must always be able to see:

- what the current goal is;
- what should be done first;
- which material is additional;
- where the answers are;
- what should be reviewed later.

A large lesson may be completed over several study sessions. Useful material should not be removed or split artificially merely to fit a fixed time limit.

Where labels are useful, use:

- **Main lesson** for the intended learning path;
- **Additional practice** for extra work selected according to need;
- **Challenge** for optional material above the ordinary productive level.

These labels describe the role of material, not its duration.

---

# 9. Lesson Types

The course may contain:

- orientation;
- grammar;
- vocabulary;
- reading;
- listening;
- writing;
- speaking;
- pronunciation;
- error clinic;
- review;
- checkpoint;
- project;
- integrated lessons.

A lesson should have a clear purpose. It may combine several skills naturally and does not need a formal primary-type classification.

## Grammar

Context → noticing → explanation → examples → focused practice → contrast → mixed practice → connected input → production.

## Vocabulary

Context → meaning → pattern → collocations → examples → recognition → recall → connected input → production.

## Reading

Before reading → text → gist → detailed comprehension → vocabulary in context → inference → language noticing → paraphrasing → summary or response.

## Listening

First listen without transcript → gist → second listen for detail → transcript analysis → connected speech and vocabulary → final listen → response.

## Writing

Model or first attempt → analysis → useful language → planning → writing → self-editing → comparison or commentary.

## Speaking

Model or input → useful language → planning → short response → repetition or reformulation → longer response → feedback where available.

## Review

Little or no major new material. Previously studied material is mixed and retrieved with less support.

## Checkpoint

Cumulative work with minimal teaching support. It should reveal what can be used independently and what needs further practice.

## Orientation

Purpose → demonstration of a learning method → guided attempt → independent attempt → practical takeaway.

## Pronunciation

Listening context → noticing → explanation → discrimination → controlled production → connected speech → listening again.

## Error Clinic

Errors in context → independent correction → explanation and contrast → new examples → later retrieval.

## Project

Purpose and final product → source material → stages of work → intermediate reflection → final product.

## Integrated Lesson

A meaningful task combines two or more skills, such as reading followed by summary, listening followed by discussion, or comparing sources before writing.

---

# 10. Grammar Teaching

Important new grammar should normally include:

- natural context;
- a noticing task;
- core meaning;
- form;
- a useful mental model;
- contrasts with neighboring structures;
- common mistakes;
- varied natural examples;
- focused and mixed practice;
- later use in reading, listening or writing;
- delayed review.

Grammar should not be reduced to memorised formulas. The learner should understand why a speaker chooses a form.

Texts may contain grammar that has not yet been formally studied. Such grammar should not be artificially removed from natural English. A brief explanation may be supplied when needed, without turning it into an additional learning target.

---

# 11. Grammar Examples

An ordinary new construction should normally receive approximately 15 or more natural examples. Major central topics may require 20–30 or more.

Examples should vary across:

- meaning and situation;
- statements, negatives and questions;
- persons and subjects;
- vocabulary;
- contractions;
- spoken and written contexts where relevant;
- related and competing structures.

Changing only a name or noun does not create meaningful variety.

Example counts are guides to sufficient exposure, not quotas that justify repetitive material.

---

# 12. Grammar Practice

A major topic should receive substantial focused practice before freer use. Approximately 15–30 controlled items may be appropriate in the main lesson, with more available in additional practice.

A useful progression is:

```text
recognition
→ completion
→ sentence construction
→ contrast
→ translation
→ mixed context
→ independent production
```

Once the basic form is understood, exercises should increasingly require the learner to choose between related structures without relying on the exercise title.

New grammar must later appear together with older grammar, vocabulary and natural connected language.

A substantial lesson should normally use several forms of practice. Large sets of nearly identical items should not replace contrast, contextual choice, error correction, translation and independent production.

---

# 13. Vocabulary Unit

Vocabulary should normally be learned as a usable lexical unit rather than as an isolated translation.

Prefer:

- `depend on something`;
- `make a decision`;
- `end up doing something`;
- `I'm not sure whether...`.

A useful active vocabulary entry may include:

- meaning;
- grammatical pattern;
- pronunciation where useful;
- common collocations;
- several natural examples;
- contextual practice;
- later retrieval and productive use.

The learner should not be required to turn every unknown word in a text into active vocabulary.

---

# 14. Vocabulary Roles

Vocabulary may be treated as:

- **NEW ACTIVE** — intended for gradual productive use;
- **REVIEW** — previously introduced active material;
- **PASSIVE** — recognition is sufficient for now;
- **OPTIONAL** — useful but outside the current learning burden.

These labels may appear in the lesson where they help the learner. They do not require a separate database or metadata system.

A normal lesson may introduce about 5–8 active lexical units. A vocabulary-focused lesson may introduce about 8–15. These are workload guides; coherent groups and actual difficulty matter more than exact counts.

Passive vocabulary may be larger if it does not prevent comprehension.

---

# 15. Chunks, Collocations and Phrasal Verbs

Natural combinations should appear throughout the course rather than being postponed until dedicated modules.

The course should repeatedly show:

- which words commonly occur together;
- which preposition or verb pattern is required;
- whether an expression is formal, neutral, informal, spoken or written;
- whether a phrasal verb is separable;
- how meaning changes across contexts.

Dedicated lessons later organize and deepen material that may already have appeared in texts and exercises.

---

# 16. RU → EN

RU → EN is an intentional part of the course because it reveals productive gaps.

The vocabulary surrounding the target should remain reasonably familiar. A grammar exercise should not accidentally become a test of obscure vocabulary.

Tasks should progress from simple sentences to connected and nuanced meaning.

Normal alternative translations must be acknowledged. The objective is accurate, natural English rather than word-for-word replacement.

---

# 17. EN → EN

EN → EN should begin relatively early and become increasingly important toward B2.

Tasks may include:

- rewriting without changing meaning;
- explaining a word in English;
- replacing an unnatural expression;
- paraphrasing;
- changing register;
- summarising;
- reformulating an argument.

These tasks help the learner operate within English rather than passing through Russian for every idea.

---

# 18. Error Correction

Error material should come from:

1. common learner errors;
2. errors typical of Russian-speaking learners;
3. predictable confusions between subjects already taught in the course.

Exercises should contain plausible errors with enough context to determine the intended meaning.

The course should distinguish:

- a real grammatical or lexical error;
- a grammatical but less natural choice;
- a register or style issue;
- an optional advanced improvement.

Important error patterns should be built into later review in advance. The course must not assume that new exercises will be created from an individual learner's answers.

---

# 19. Answers

Every closed exercise must have an answer.

When several answers are possible, the key should use labels such as:

- Suggested answer;
- Also possible;
- Correct but less natural;
- More natural;
- Incorrect.

Obvious answers do not need long explanations. Confusing distinctions and important traps do.

Open tasks should receive useful criteria, a checklist, commentary or a model response. A model is an example, not the only correct answer.

Answers should follow the same simple sequential numbering, titles and item order as the tasks. Global or composite internal IDs are not required in learner-facing files.

A simple format is sufficient:

```markdown
### Task 3. Use the New Pattern

1. ...
2. ...
3. ...
```

The corresponding section in `03-answers.md` should use the same title, task number and item order:

```markdown
## Task 3. Use the New Pattern

1. ...
2. ...
3. ...
```

The answer material must be complete enough for independent study without AI or a teacher.

Multiple-choice distractors should represent realistic mistakes rather than obviously unrelated options.

---

# 20. Reading

Reading ability may remain ahead of productive grammar.

The learner should not be restricted to childish texts while repairing basic grammar. Course-created texts should have a real narrative, informational or communicative purpose.

Approximate reading lengths:

- early course: 300–600 words;
- B1: 500–900 words;
- B1+: 700–1200 words;
- B2: 1000–2000 words or more.

These ranges are flexible. Dedicated reading lessons and extensive input may be longer.

Reading tasks may address gist, detail, vocabulary in context, inference, attitude, language noticing, interpretation, paraphrasing, summary and personal response. Not every text needs every task type.

The course should train the learner to decide whether to ignore, guess, check later or look up an unknown word.

---

# 21. Listening

A normal listening sequence is:

1. listen without transcript or subtitles;
2. identify the main idea;
3. listen again for detail;
4. inspect the English transcript or subtitles;
5. analyze selected language and connected speech;
6. listen again without the transcript;
7. respond to the content.

Russian subtitles are not the default learning method.

Listening should gradually develop across speed, number of speakers, accent variation, connected speech, sentence complexity, lexical density, predictability, noise and duration. These dimensions should not all increase at once.

Listening material should use two complementary layers.

## Curated Authentic Listening

Prepared listening lessons should use selected authentic or professionally published recordings rather than course-generated audio files. Suitable material includes learner-oriented recordings with natural voices, films, series, videos, interviews, podcasts, audiobooks and other real spoken English.

An intensive assignment should identify the exact work, creator or publisher, recording or segment, approximate difficulty, accent where useful and availability of an official transcript or accurate English subtitles. It should include prepared gist, detail, language-noticing and response tasks with answers based on that exact material.

A link must be accompanied by a searchable title, creator or publisher and other identifying details so that the material can still be found if the URL changes. When the complete recording is used, state this explicitly; otherwise provide an exact time range or unambiguous start and end cues.

Do not store synthetic or AI-generated audio files in the course. Dictionary audio remains appropriate for checking individual words, and learner-made recordings remain appropriate for speaking and pronunciation self-checks; neither replaces authentic listening input.

## Extensive Listening

Some listening should be done for meaning or enjoyment without detailed analysis. Other sessions may examine a short segment intensively, use English subtitles, return to a transcript or include a brief spoken or written response.

Music may support exposure, rhythm, pronunciation and occasional language analysis. Because musical delivery and poetic language differ from ordinary speech, songs should not be the main measure of listening comprehension.

If a prepared external source disappears, provide search information, an official alternate location where known and a separate independent-listening route. Closed questions tied to one unavailable recording should be postponed rather than answered from its transcript alone.

---

# 22. Pronunciation

Pronunciation is primarily taught to improve listening comprehension and intelligibility.

Priority areas include:

- word stress;
- sentence stress;
- schwa and weak forms;
- contractions;
- linking;
- common reductions;
- connected speech.

IPA is a tool for checking pronunciation, not a separate memorisation subject.

Speaking should develop gradually across the course.

In the early stages, optional speaking aloud, repetition after audio and short self-directed responses help connect grammar, vocabulary, pronunciation and automaticity. Extensive conversation practice is not required.

In the middle stages, lessons should introduce short descriptions, retelling, prepared answers and controlled simulations.

In the later stages, the learner should practice longer monologues, explanation, argument, retelling and simulated interaction. Instructions, models and self-check criteria must support independent work.

Suitable independent activities include:

- listening discrimination;
- shadowing;
- recording and comparing speech with a model;
- reading aloud;
- retelling;
- prepared and unprepared monologues;
- answering both roles in a simulated dialogue;
- recording a second, improved version.

Self-check criteria should focus on completion of the task, clarity of the main idea, avoidable pauses, use of target language, understandable key words and improvement between attempts.

Real interaction with a conversation club, teacher or proficient speaker belongs to a later external stage. It may be recommended, but course lessons must remain usable without it.

Pronunciation work should support comprehensible speech rather than imitation of one native accent.

---

# 23. Writing

Writing should progress approximately from:

- controlled sentences;
- connected sentences;
- paragraphs;
- structured B1 texts;
- extended B1+/B2 texts;
- independent B2 writing.

Word counts may be supplied when they clarify the expected product, but they are not goals by themselves.

The course should include both guided writing with selected language targets and free writing that reveals what the learner chooses independently.

Feedback should prioritise errors that obstruct accuracy or meaning before naturalness, style and advanced refinements.

An answer that differs from a model is not automatically wrong.

Every substantial free-writing task should include:

- a clear prompt;
- content requirements;
- target language where relevant;
- a self-check list;
- a model response;
- brief commentary on the model;
- common problems to inspect.

The learner may use AI to obtain feedback on free writing. This is feedback on an answer, not a mechanism for generating the course.

The recommended sequence is:

1. write and self-check a first version;
2. request feedback without asking AI to replace the text immediately;
3. revise the text independently;
4. compare the revision with a corrected or improved version.

A reusable feedback prompt should ask AI to:

- identify actual grammar, vocabulary and punctuation errors;
- separate errors from optional improvements in naturalness or style;
- explain important corrections briefly;
- preserve the intended meaning;
- provide a corrected version;
- identify a small number of recurring problems for attention.

The prompt should include the writing task, approximate course stage and target language. AI feedback may contain mistakes, so a doubtful correction should be checked against reliable reference material rather than accepted automatically.

---

# 24. Spaced Review

New material should return after its introduction.

A useful pattern is:

```text
introduction
→ same-lesson practice
→ early review
→ short-term review
→ module review
→ checkpoint
→ long-term cumulative use
```

All required returns to earlier material must be written into later lessons in advance. The learner should not need a scheduler, tracking system or newly generated review set.

Most ordinary lessons should begin with a short retrieval set using previously studied material. It may combine the previous lesson, material from several lessons earlier, older high-priority material and a common error pattern planned in advance.

Review should require recall before the learner sees the answer.

---

# 25. Vocabulary Review

An important active lexical unit should return several times through:

- several examples at introduction;
- same-lesson use;
- later retrieval;
- productive use;
- appearance in connected input;
- later cumulative use.

Later encounters should vary between recognition, recall, contextual understanding and original use. The aim is to prevent one-time exposure from being mistaken for learning, without maintaining a separate repetition database.

---

# 26. Grammar Review and Interleaving

Important grammar should receive:

- substantial initial examples and practice;
- early retrieval;
- contrast with neighboring structures;
- mixed practice;
- connected reading or listening;
- productive use;
- module review;
- checkpoint use;
- later recycling.

Spacing and interleaving are different. Spacing returns to material later; interleaving makes related structures compete.

Important contrasts include:

- Past Simple vs Present Perfect;
- Present Perfect Simple vs Continuous;
- few vs a few;
- little vs a little;
- mustn't vs don't have to;
- used to vs be used to;
- First vs Second Conditional;
- say vs tell;
- borrow vs lend.

The learner must practice choosing rather than only reproducing a named form.

---

# 27. Difficulty Progression

Difficulty should be considered separately across grammar, vocabulary, reading, listening, writing, task complexity, support, independence and naturalness.

A learner may simultaneously have stronger reading and weaker productive grammar. This unevenness is expected.

Progression should generally move:

- from supported to independent;
- from short to long;
- from controlled to free;
- from familiar to unfamiliar;
- from slow and clear to natural;
- from isolated to mixed;
- from Russian-supported to increasingly English-supported;
- from course-created to more authentic material;
- from identifying a form to choosing and using it.

Not all difficulty dimensions should increase at the same time.

---

# 28. Moving Forward and Remediation

Ordinary lessons do not require perfect performance.

The learner may normally continue when:

- the core distinction is understood;
- focused practice is mostly successful;
- a basic original example can be produced;
- prerequisite problems do not make the new material unusable.

If the core idea remains unclear or simple production is not possible, use targeted additional practice and try again. Repeating an entire lesson is not always necessary.

Lessons and checkpoints should point to suitable material already present in the course. A simple direction such as “Return to Lesson 148, Practice 2” is sufficient.

A difficult optional challenge does not determine whether the main lesson has been learned.

These principles guide the choice of practice; lessons do not need formal scores or time records.

---

# 29. Review Lessons

Review lessons should contain little or no major new content.

Earlier reviews may focus more heavily on the current module while retaining older material. Later reviews should become increasingly cumulative and hide topic labels more often.

Review should combine recent material, earlier grammar, active vocabulary, chunks or collocations and, where appropriate, connected reading, listening, writing or speaking.

Review should include varied tasks, connected input and productive use rather than only another set of identical form exercises.

---

# 30. Checkpoints

Checkpoints are cumulative. They should not test only the latest module.

A checkpoint may combine:

- grammar;
- vocabulary, chunks and collocations;
- reading;
- listening;
- RU → EN;
- EN → EN;
- error correction;
- writing;
- integrated use.

It should reveal strong and weak areas and direct the learner to suitable practice already included in the course. A checkpoint should not introduce substantial new teaching inside the assessment.

Criteria should suit the skill being assessed. Open writing and listening comprehension should not be reduced to a single invented universal percentage.

Scores may be supplied for closed sections when they help interpretation. The checkpoint should not combine all skills into one universal pass mark.

---

# 31. Additional Practice

Each lesson may have a `02-practice.md` with extra work such as:

- foundation repair;
- standard practice;
- mixed grammar;
- RU → EN;
- EN → EN;
- error correction;
- vocabulary and chunks;
- cumulative review;
- extra reading or listening;
- challenge material.

The global `practice-bank/` may contain larger cumulative sets crossing several lessons and modules.

Useful global sets may include tense mixing, articles, prepositions, translation, paraphrasing, error correction, mixed B1 and mixed B2 practice.

Additional material should be abundant enough that the learner does not need to search elsewhere simply because the course provides too little practice.

The learner should be able to distinguish the main path from optional additional work.

---

# 32. Challenge and Extensive Input

Optional challenge material may be somewhat above the current productive level. It may include harder vocabulary or preview grammar, but should remain explainable and useful.

Challenge material does not determine ordinary lesson mastery.

Some English should be consumed without exercises or detailed analysis. Free reading, films, books, podcasts, audiobooks, videos and series help English become a medium rather than only an object of study.

Not every sentence, word or paragraph needs a question.

Extensive-input recommendations may range from a structured assignment to a simple suggestion with a reason for choosing the material. The course should distinguish intensive study of a short segment from ordinary reading, viewing or listening for meaning and enjoyment.

---

# 33. External Materials

The course should remain substantially self-contained.

External materials are appropriate for audio, video, films, books, podcasts, authentic articles and other sources that should not be reproduced inside the course.

An external assignment should provide:

- exact title;
- author, channel or publisher where relevant;
- a link where a useful stable link is available;
- exact segment where relevant;
- approximate difficulty;
- accent where useful;
- availability of subtitles or transcript;
- a clear task.

A critical lesson should not become unusable because a single link disappears. It should provide enough search information to relocate the same official material and, where appropriate, a separate authentic source or independent-listening route that still practices the method.

Listening lessons do not store synthetic or AI-generated audio files. Link to authentic or professionally published recordings at their legitimate source. Use an official transcript or accurate English subtitles after the initial listening tasks; do not reproduce a copyrighted transcript in full merely to make the lesson self-contained.

Course-created material used once normally belongs in its lesson. A shared resource is useful only when several lessons actually use it.

---

# 34. File Structure and Naming

The project may use:

```text
english/
├── README.md
├── COURSE-MAP.md
├── COURSE-DESIGN-SPEC.md
├── CHANGELOG.md
├── 00-guide/
├── 00-stage-learning-to-learn/
├── 01-stage-sentence-foundations/
├── ...
├── 14-stage-final-assessment/
├── practice-bank/
└── reference/
```

Directories and files should use clear lowercase names with hyphens and lesson numbers where useful.

A normal location may look like:

```text
01-stage-sentence-foundations/
└── 01-01-building-a-sentence/
    └── lesson-009-subject-verb-object/
        ├── 01-lesson.md
        ├── 02-practice.md
        └── 03-answers.md
```

Markdown is the source format because it is readable and easy to edit. This does not require machine-readable lesson metadata.

Reference pages explain reusable topics. Checkpoints remain numbered lessons inside the appropriate stage rather than using a separate root directory.

---

# 35. Material Principles

Course material should avoid:

- artificial texts written only to repeat one form;
- meaningless examples;
- large groups of mechanically identical exercises;
- vocabulary dumps of isolated translations;
- unnecessarily long grammar lectures;
- difficult English explanations when concise Russian would be clearer;
- trick questions;
- fake single answers to genuinely ambiguous questions;
- obscure vocabulary that interferes with the actual target;
- automatic translation of every unknown word;
- repetitive themes;
- fake natural dialogue overloaded with slang;
- unsupported claims about what native speakers “never” say.

When useful, prefer an abundance of good examples, exercises and texts over scarcity.

The learner should always be able to identify the main learning goal and the optional extra material.

Materials should be created and considered in coherent modules so that prerequisites, progression and repetition can be judged across several lessons rather than one file at a time.

---

# 36. Governing Principle

The course is a well-ordered, extensive collection of explanations, examples, texts, exercises, answers and authentic-material assignments.

Its organization exists to support learning. Its value comes from the material itself: clear teaching, natural English, abundant practice, deliberate repetition and progression toward independent use.

The learner should move from understanding rules to recognizing patterns, choosing language, using English independently and eventually using English without the course as the primary environment.
