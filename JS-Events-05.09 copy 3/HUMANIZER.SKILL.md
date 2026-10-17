---
name: humanizer
description: >-
  Revises prose to sound clear, natural, specific, and consistent with the author's
  intended voice while preserving meaning and factual integrity. Use for requests to
  humanize text, reduce generic AI-sounding language, or edit prose for voice and clarity.
metadata:
  version: "3.0.0"
  portability: "model-agnostic"
---

# Humanizer

## Purpose

Edit prose so it reads naturally and specifically, without changing what the author means. Use the guidance below as a flexible editorial checklist, not as a formula or an AI-detection score.

## Use this skill when

- The user asks to humanize text, make it sound less robotic, or remove generic AI-style phrasing.
- A draft is repetitive, inflated, overly promotional, vague, or mechanically structured.
- The user asks to polish prose while keeping its original message and voice.

## Do not use this skill to

- Rewrite source code, configuration files, structured data, commands, or machine-readable formats.
- Fabricate citations, evidence, examples, personal experiences, opinions, or emotional reactions.
- Make a text more persuasive than requested or change its intended meaning.
- Claim that text is or is not AI-generated. Stylistic patterns alone cannot establish authorship.
- Alter UI themes, CSS, icons, fonts, logos, or binary assets as part of a prose-editing task.

## Workflow

1. **Identify the purpose and audience.** Preserve the intended register: technical, academic, professional, conversational, creative, or another style specified by the user.
2. **Read for meaning before style.** Identify the main claim, supporting points, names, dates, numbers, citations, quotations, terminology, and any deliberate voice.
3. **Find patterns, not keywords alone.** Check the catalog below for inflated significance, promotional phrasing, vague attribution, formulaic transitions, repeated sentence structures, filler, and other habits. A listed word is not automatically wrong; retain it when it is precise or natural in context.
4. **Revise selectively.** Prefer concrete claims, direct verbs, natural sentence variation, and wording suited to the author. Remove only material that is redundant or unsupported. Do not add a personal voice unless the context or user requests it.
5. **Protect factual integrity.** Keep facts, names, numbers, dates, quotations, links, citations, and levels of certainty unchanged unless the user explicitly asks for fact-checking or correction. If a claim needs evidence and none is supplied, do not invent it.
6. **Verify current facts when relevant.** When answering factual questions about current products, APIs, libraries, versions, regulations, standards, or official documentation, use available web search and prefer current primary sources. If browsing is unavailable, state that current verification could not be performed. Do not browse merely to justify a stylistic preference.
7. **Review the result.** Check that the rewrite still means the same thing, sounds natural aloud, fits the audience, preserves formatting where useful, and introduces no unsupported detail.
8. **Return the deliverable.** By default, provide the revised text. Add a brief change note only when requested or when it materially clarifies the result. Do not expose private reasoning or internal analysis.

## Editorial principles

- Preserve the author's meaning, intent, factual claims, terminology, and appropriate level of certainty.
- Prefer precise language over grand claims or decorative wording.
- Vary sentence length when the content benefits from it; do not manufacture variation just to satisfy a metric.
- Use first person, humor, fragments, contractions, emotion, or strong opinions only when supported by the author's voice, source material, or explicit instructions.
- Keep purposeful repetition when it helps comprehension or emphasis.
- Do not force every draft into headings, bullets, tables, or a particular format. Preserve the original format unless changing it improves readability or the user requests a different format.
- Do not add emojis or decorative icons by default. Preserve them only when they serve the author's intent or the user asks for them.
- When giving technical explanations, favor concise Markdown, current documentation, established industry practices, and clean-code principles where relevant.

## Pattern catalog

Treat these as review prompts, not a blacklist. Do not remove a phrase solely because it appears below; consider context and whether it adds useful information.

### 1. Inflated significance or historical importance

Watch for phrases such as "a pivotal moment," "a testament to," "plays a crucial role," "marks a turning point," "underscores its importance," or claims that a small detail reflects a broad trend.

**Edit:** State what happened and why it matters only when the reason is supported. Remove grand framing that adds no information.

### 2. Unnecessary claims of notability

Watch for name-dropping outlets, awards, prominent people, or social-media reach without explaining how that information is relevant.

**Edit:** Keep a reference when it supports the point. Describe the actual statement or evidence rather than implying importance through a list of names.

### 3. Superficial participle phrases

Watch for trailing phrases such as "highlighting," "underscoring," "showcasing," "reflecting," "contributing to," or "ensuring" that merely restate the preceding sentence.

**Edit:** Remove the trailing phrase or replace it with a separate, concrete fact when the source supports one.

### 4. Promotional language

Watch for unsupported adjectives such as "groundbreaking," "breathtaking," "seamless," "world-class," "vibrant," "renowned," or "revolutionary."

**Edit:** Describe observable features, outcomes, or evidence. Retain promotional wording only when the genre requires it or it is a substantiated quotation.

### 5. Vague attribution

Watch for "experts say," "observers believe," "industry reports show," or "critics argue" when the source is unclear.

**Edit:** Name the source if it is known and relevant. Otherwise qualify or remove the attribution; never invent an expert or source.

### 6. Formulaic challenge-and-outlook framing

Watch for generic structures like "Despite these challenges, the future remains bright" or headings such as "Challenges and Future Prospects" that add no concrete information.

**Edit:** State the actual obstacle, action, result, or plan. Remove empty optimism.

### 7. Repeated high-frequency AI-style vocabulary

Review repeated or ornamental uses of words such as "additionally," "delve," "crucial," "landscape," "pivotal," "showcase," "tapestry," "underscore," "foster," "leverage," and "valuable."

**Edit:** Replace them only when a simpler or more exact phrase fits. These words are not forbidden and may be appropriate in context.

### 8. Avoiding simple forms of “be”

Watch for elaborate substitutes such as "serves as," "stands as," or "functions as" when "is" or "are" is clearer.

**Edit:** Use the simplest accurate construction. Retain the longer verb when it expresses a distinct function or relationship.

### 9. Forced negative parallelism

Watch for repeated constructions such as "It's not just X; it's Y" or "not only X but also Y" when they add drama without improving meaning.

**Edit:** State the substantive point directly. Keep contrast when it is logically important.

### 10. Automatic groups of three

Watch for lists or slogans that appear to force every idea into three items.

**Edit:** Use the number of examples the material supports. Do not shorten or expand a list just to create a rhetorical pattern.

### 11. Unnecessary synonym cycling

Watch for multiple labels for the same person, product, concept, or process in adjacent sentences.

**Edit:** Repeat the clearest term when consistency helps comprehension. Use synonyms only when they add precision or avoid genuine ambiguity.

### 12. False “from X to Y” ranges

Watch for ranges that join unrelated examples to sound comprehensive, such as "from innovation to transformation" without a meaningful scale.

**Edit:** Name the actual topics or use a range only when its endpoints define a meaningful continuum.

### 13. Excessive em dashes

Watch for repeated em dashes used in place of normal punctuation or to create manufactured drama.

**Edit:** Use commas, parentheses, colons, semicolons, or full stops where they fit the syntax. Do not ban em dashes when they suit the author's style or locale.

### 14. Mechanical bold formatting

Watch for bold text applied to many ordinary terms or entire phrases without a clear information hierarchy.

**Edit:** Keep emphasis sparse and meaningful. Preserve formatting required by the original document or user.

### 15. Repeated bold-label lists

Watch for sections where every bullet begins with a bold label followed by a generic explanation.

**Edit:** Use a direct paragraph, a compact list, or labels only when they help readers scan the content. Do not remove useful structure merely to avoid a pattern.

### 16. Over-capitalized headings

Watch for Title Case headings where sentence case is the convention for the target language or document.

**Edit:** Follow the requested style guide, publication convention, or existing document. Do not impose one capitalization convention universally.

### 17. Unnecessary emojis and decorative symbols

Watch for emojis used as decoration in technical, formal, or professional prose.

**Edit:** Remove them when they distract or conflict with the context. Preserve them in content where they convey intended tone or meaning. Do not replace them with icons or assets unless the user requests a UI/design task.

### 18. Curly versus straight quotation marks

Quotation-mark conventions vary by language, publisher, and format.

**Edit:** Follow the user's or publication's style guide. Do not convert quotation marks mechanically. Preserve exact quotations when required.

### 19. Chatbot preambles and sign-offs

Watch for generic openings such as "Great question!" and endings such as "I hope this helps" or "Let me know if you need anything else" when they add no value.

**Edit:** Begin with the answer or deliverable. Keep a greeting or sign-off when the communication context calls for one.

### 20. Unhelpful knowledge disclaimers

Watch for vague phrases such as "based on available information" or "as of my last update" that replace a useful answer without explaining a real limitation.

**Edit:** State the specific limitation. When current verification matters, check current sources if tools permit; otherwise say plainly that it was not verified.

### 21. Excessive agreement or flattery

Watch for repeated praise of the user's question or assumptions before answering.

**Edit:** Acknowledge relevant points neutrally and proceed to the substance. Do not remove sincere appreciation when it is appropriate to the conversation.

### 22. Filler phrases

Examples include "in order to," "due to the fact that," "at this point in time," and "has the ability to."

**Edit:** Prefer shorter equivalents such as "to," "because," "now," and "can" when the meaning remains the same.

### 23. Excessive hedging

Watch for stacks of qualifiers such as "could potentially possibly" or repeated "may/might/could" without a reason.

**Edit:** Use a confidence level justified by the evidence. Do not remove necessary uncertainty from claims that are genuinely uncertain.

### 24. Generic conclusions

Watch for empty endings such as "the future looks bright," "exciting times lie ahead," or "this is a step in the right direction."

**Edit:** End with the actual result, decision, next action, or implication. If none is needed, stop when the answer is complete.

## Fact and source integrity

- Never turn an illustrative example into a claim about the real world without evidence.
- Never add names, studies, statistics, interviews, quotations, URLs, or citations that were not supplied or verified.
- Do not silently correct a factual assertion during a style edit. Preserve it, or clearly distinguish a requested fact-check from the rewrite.
- When the user requests factual verification, use current reliable sources where available and cite the supporting sources in the answer.
- If source material does not support a point, state that limitation instead of filling the gap with a plausible-sounding detail.

## Tool, package, and asset independence

This skill is for prose editing and has no mandatory runtime, model provider, API, external package, icon set, font, or UI dependency. Do not install libraries or download assets to perform ordinary humanization.

If the user explicitly combines prose work with a separate software/UI cleanup task:

1. Inspect the project's existing structure, dependencies, design tokens, and asset usage before proposing changes.
2. Remove stale model-generated styles or icons only after identifying where they are used and confirming they are not required.
3. Prefer the project's existing design system and icon package. If none exists, select a maintained library compatible with the project's framework and bundle requirements; for example, Lucide may suit a React project, but verify the current official documentation before choosing it.
4. Install packages through the project's package manager and use official package documentation. Download standalone assets only from trusted official sources, check licensing, and avoid hotlinking or copying unverified assets.
5. Do not add a dependency or replace an asset when it is unrelated to the requested task.

## Portability rules

- Do not assume a particular model, vendor, agent runtime, shell, editor, filesystem API, or tool name.
- Use the capabilities available in the active environment. For example, if file read/write tools exist, use them; if not, return the revised text in the conversation.
- Never claim to have read, changed, searched, downloaded, or validated something unless the relevant action was actually performed.
- If a required capability is unavailable, explain the limitation briefly and complete the parts that can be completed.
- The frontmatter intentionally omits `allowed-tools`, because tool names and permission syntax vary between agent implementations.

## Reference

The pattern catalog is informed by Wikipedia's "Signs of AI writing" guide, maintained by WikiProject AI Cleanup:
https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing

The catalog is a heuristic editorial checklist. It is not a universal writing standard, and it should never override factual accuracy, the author's intent, or a requested style guide.
