# Anbeeld's WRITING.md — LLM Writing Rules

A prose ruleset that makes LLM-assisted text sharper, not as generic, and less like default model output. It targets the patterns that make generated prose feel recognizable without breaking grammar, faking typos, or gutting useful structure. The result reads better than unguided output and avoids the most common tells.

The rules combine writing standards, web readability research, documentation guidance, detector-limit research, and direct observation of what LLMs produce when left to defaults.

[![Support my work!](https://anbeeld.com/images/support.jpg)](https://anbeeld.com/support)

## How to use it

Give the ruleset to an LLM and tell it to follow every rule strictly. The explicit instructions compensate for habits the model would otherwise default to: regular sentence structure, generic phrasing, parallel enumeration, and overly neat conclusions.

One pattern that works well: ask for a first draft with the rules applied, then request an audit of that draft against the required checks, and have the model rewrite based on what the audit caught. More rewrites after that usually circulate around the same model-level limitations rather than improving the text further.

This is meant for legitimate uses, like iterating on a human draft or turning loosely organized thinking into something you would actually publish. The output avoids the most common AI tells and will read better than unguided model text, but it will not pass an experienced eye test or an advanced detector. Prompt-level instructions have a ceiling and can't overcome model-level defaults.

## What it does

- Starts with context: medium, audience, reader need, and the job of the text.
- Calibrates voice to genre. Opinion pieces can sound like a person; summaries and docs stay neutral.
- Keeps the format appropriate. Docs stay scannable; casual replies do not get over-structured. Does not remove useful structure just to look less templated.
- Replaces polished generality with concrete anchors. If a paragraph has no checkable detail, it gets revised or cut.
- Guards against fake specificity. Quotes, numbers, dates, causal claims, and named claims need support or they get cut.
- Breaks the patterns that make model prose look templated: repeated cadence, hidden lists, generic signposts, and too-neat paragraph shapes.
- Prefers plain verbs and ordinary words over inflated phrasing. Allows repetition when the ordinary word is the right one.
- Cuts the staged parts: keynote cadence, service-desk tone, ceremonial openings, and filler closings.
- Does not fake humanity. No invented typos, no forced slang, no programmatic sentence-length variation, no staged messiness.
- Revises by reading and cutting. Collapses restatements, drops announcement sentences, and replaces the most generic clause with something specific.

## See also

- [Anbeeld's Global AGENTS.md / CLAUDE.md](https://github.com/Anbeeld/AGENTS.md)

[![Support my work!](https://anbeeld.com/images/support.jpg)](https://anbeeld.com/support)