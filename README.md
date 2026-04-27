# Anbeeld's WRITING.md — AI Writing Rules

A prose ruleset that makes AI-assisted text sharper, not as generic, and less like default model output. It targets the patterns that make generated prose feel recognizable without breaking grammar, faking typos, or gutting useful structure. The result reads better than unguided output and avoids the most common tells.

The rules combine writing standards, web readability research, documentation guidance, detector-limit research, and direct observation of what LLMs produce when left to defaults.

[![Support my work!](https://anbeeld.com/images/support.jpg)](https://anbeeld.com/support)

## What it does

- Starts with context: medium, audience, reader need, and the job of the text.
- Calibrates voice to genre. Opinion pieces can sound like a person; summaries and docs stay neutral.
- Keeps the format appropriate. Docs stay scannable; casual replies do not get over-structured. Does not remove useful structure just to look less templated.
- Replaces polished generality with concrete anchors. If a paragraph has no checkable detail, it gets revised.
- Guards against fake specificity. Quotes, numbers, dates, causal claims, and named claims need support.
- Breaks the patterns that make model prose look templated: repeated cadence, hidden lists, generic signposts, and too-neat paragraph shapes.
- Prefers ordinary words over inflated phrasing. Allows repetition when the ordinary word is the right one.
- Cuts the staged parts: keynote cadence, service-desk tone, ceremonial openings, and filler closings.
- Does not fake humanity with some specific tricks. No invented typos, no forced slang, no programmatic sentence-length variation, no staged messiness. You can add it yourself, if needed.
- Revises by reading and cutting. Collapses restatements, drops announcement sentences, and replaces the most generic clause with something specific.

## How to use it

Give [the ruleset](https://github.com/Anbeeld/WRITING.md/blob/main/WRITING.md) to an AI and tell it to follow every rule strictly. The explicit instructions compensate for habits the model would otherwise default to: regular sentence structure, generic phrasing, parallel enumeration, and overly neat conclusions.

One pattern that works well: ask for a first draft with the rules applied, then request an audit of that draft against the required checks, and have the model rewrite based on what the audit caught. More rewrites after that usually circulate around the same model-level limitations rather than improving the text further.

This is meant for legitimate uses, like iterating on a human draft or turning loosely organized thinking into something you would actually publish. The output avoids the most common LLM tells and will read better than unguided model text, but it will not pass an experienced eye test or an advanced detector. Prompt-level instructions have a ceiling and can't overcome model-level defaults.

## Available versions

The repository includes the full ruleset and two compressed forms for different budgets.

**[WRITING.md](https://github.com/Anbeeld/WRITING.md/blob/main/WRITING.md)** — the full ruleset, ~3900 words. All 14 core rules, detector limits, required checks, long-form diagnostics, examples of useful corrections, optional audit reference, and provenance guidance. Load this when you want the complete instruction set and have the context window for it.

**[WRITING-compact.md](https://github.com/Anbeeld/WRITING.md/blob/main/WRITING-compact.md)** — the same rules at ~1000 words. Use as AGENTS.md or CLAUDE.md for writing agents, or as instructions in custom chats like GPTs and Gemini Gems. Cuts detector limits, examples, long-form diagnostics, and provenance; keeps every behavior-changing rule, required check, and the watchlist.

**[WRITING-mini.md](https://github.com/Anbeeld/WRITING.md/blob/main/WRITING-mini.md)** — ~155 words, fits on one screen. All ten concepts compressed to bullet-pointed aphorisms. Designed to embed as a persistent section in global AGENTS.md or CLAUDE.md so the rules are always in context without dominating it.

## See also

- [Anbeeld's Global AGENTS.md / CLAUDE.md](https://github.com/Anbeeld/AGENTS.md)

[![Support my work!](https://anbeeld.com/images/support.jpg)](https://anbeeld.com/support)