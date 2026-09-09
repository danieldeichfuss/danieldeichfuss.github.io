# STYLE.md

This guide describes what posts on Daniel's blog should do, contain, and prove. It is provisional and based on the two published examples in `src/content/posts/` plus the repository's publishing conventions.

## Writing identity

- **What it is:** Short personal notes about software engineering, AI agents, and how the work is changing.
- **What it is for:** To turn an observation from actual work into a useful question, distinction, or reframe.
- **What makes it distinct:** The post earns the broader idea through a concrete engineering experience instead of presenting a generic AI trend.

## Audience

- **Primary reader:** Technically literate people working with software and AI agents.
- **What they already know:** Basic software-development and agent terminology.
- **What they should leave with:** A sharper way to recognize or think about something they may also be experiencing.
- **What must not be assumed:** That every reader uses the same agent harness, team setup, or workflow.

## Reader promise

A post should usually give the reader:

- One clear observation from real work.
- One concrete example, analogy, or consequence that makes it legible.
- One useful reframe or open question rather than a complete system presented as universal.

## Intellectual posture

- Ground claims in Daniel's experience before generalizing.
- Distinguish “this is happening in my work” from “this is true of software development.”
- Preserve genuine uncertainty when the practice or idea is still developing.
- Prefer one earned insight over several adjacent lessons.
- Do not turn an early personal habit into a polished methodology without evidence.

## Evidence and provenance

- Personal observations may stand as personal observations; make their scope clear.
- Use a concrete work example when it is the basis for the post's claim.
- Link an external concept when the post relies materially on its definition or authority.
- Do not add statistics, industry-wide claims, or causal claims without a source.
- Mention tools and internal workflows only to the level needed for the idea; explain the relevant behavior without assuming the reader shares the setup.

## Primary structure: short technical observation

1. Open with the live observation or question.
2. Name the tension or change it exposed.
3. Ground it in one concrete example or analogy.
4. Broaden carefully to the useful implication.
5. End with a concise turn, question, or consequence that extends the idea.

**Use when:** One experience has produced one clear insight.

**Do not force it when:** The reader needs a tutorial, several examples, substantial evidence, or a step-by-step method.

## Openings

Strong openings tend to:

- Begin with the actual question or current observation.
- Establish the tension within the first paragraph.
- Avoid scene-setting that delays the point.

Avoid:

- Generic declarations about the age of AI.
- Definitions before the reader knows why they matter.
- Announcing that the post will explain something.

## Development and movement

- Keep each paragraph responsible for one turn in the thought.
- Introduce a concrete example early enough to prevent abstraction.
- Explain technical setup only when it changes the argument.
- Let the post remain short when the insight is short.
- Avoid section headings unless the piece becomes long enough to require them.

## Endings

Strong endings tend to:

- Extend or twist the central idea.
- Leave a useful question open.
- Land on a concrete implication rather than a recap.

Avoid:

- Summary-only conclusions.
- Generic encouragement.
- A call to action that the post has not earned.

## Writing anti-patterns

| Pattern | Why it does not belong | Better move |
|---|---|---|
| Universalizing one workflow | Readers use different tools and setups | Extract the portable habit and keep implementation personal |
| Several examples with the same lesson | Dilutes a short post | Choose the clearest example |
| Turning a habit into a named framework too early | Makes exploration sound like marketing | Use a modest working name or no coined term |
| Explaining every implementation detail | Hides the reframe inside tooling | Include only the detail that makes the consequence concrete |
| Ending with advice already implied | Weakens the final line | End on the sharper consequence or question |

## Publication format

Posts live in `src/content/posts/` as Markdown. Every post requires:

- `title`
- `description`
- `published` in `YYYY-MM-DD` format
- a suitable `category` and tags

Use `draft: true` while a post is still being developed. Titles and descriptions in the existing posts are lowercase and compact; treat this as a current pattern, not yet an immutable rule.

## Positive examples

### `src/content/posts/onboarding.md`

- Moves from a personal observation to a specific E2E-testing example and then to a broader implication for documentation and agent skills.
- Demonstrates how a technical example can carry the argument without extensive setup.

### `src/content/posts/understanding.md`

- Holds one question throughout a very short post.
- Uses the car analogy to complicate rather than merely illustrate the question.
- Ends by pushing the analogy into a concise unresolved joke.

## Pre-publication checklist

- [ ] Is there exactly one central observation or question?
- [ ] Is it grounded in a concrete experience, example, or analogy?
- [ ] Are claims scoped to what the evidence supports?
- [ ] Can workflow-specific detail be removed without losing the insight?
- [ ] Does each paragraph advance or complicate the idea?
- [ ] Does the ending extend rather than summarize?
- [ ] Does the draft satisfy `VOICE.md`?
- [ ] Does the frontmatter satisfy the blog's content schema?
