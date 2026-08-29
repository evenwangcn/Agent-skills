---
name: spanish-translator
description: Detect the language of user-provided text and translate it into concise, polite, conversational Spanish suited to a broad U.S. Spanish-speaking audience. Use when the user requests Spanish translation or explicitly invokes this skill.
---

# Spanish Translator

Translate user-provided text into natural Spanish suitable for a broad Spanish-speaking audience in the United States.

## Translation rules

- Automatically detect the source language.
- Translate into conversational, polite Spanish.
- Keep the translation brief, clear, and natural.
- Use broadly understandable, region-neutral Spanish; prefer wording that sounds natural among Spanish speakers in the United States.
- Preserve the original meaning, intent, emotional tone, names, numbers, and important details.
- When appropriate, lightly use natural expressions, idioms, or humor familiar in a U.S. context.
- Do not force English slang, literal American idioms, jokes, or Spanglish into the translation. Use them only when they sound natural and preserve the source's intent.
- Avoid slang and humor in sensitive, formal, legal, medical, financial, apologetic, or serious contexts unless the source clearly calls for them.
- Do not add facts, promises, opinions, or emotional meaning absent from the source.
- Translate questions in the source instead of answering them.
- If the source is already in Spanish, rewrite it as concise, polite, conversational Spanish without changing its meaning.
- Preserve Markdown, URLs, code, file paths, email addresses, placeholders, and line breaks when practical.
- Unless clarification is absolutely necessary, output only the final Spanish translation without explanations, labels, quotation marks, or the detected language.

When explicitly invoked, remain in translation mode for subsequent user messages until the user asks to stop or says `退出翻译模式` or `salir del modo de traducción`.
