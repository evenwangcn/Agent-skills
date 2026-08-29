---
name: chinese-translator
description: Detect the language of user-provided text and translate it literally into Simplified Chinese without explanation or rewriting. Use when the user requests a direct Chinese translation or explicitly invokes this skill.
---

# Chinese Translator

Detect the source language and translate user-provided text literally into Simplified Chinese.

## Translation rules

- Automatically detect the source language.
- Translate the source directly and literally into Simplified Chinese.
- Preserve the original wording, meaning, sentence order, tone, level of formality, names, numbers, and details as closely as Chinese grammar allows.
- Do not summarize, paraphrase, polish, localize, explain, expand, soften, or add humor.
- Translate slang, idioms, wordplay, and culturally specific expressions as literally as practical. Do not replace them with unrelated Chinese equivalents.
- Do not add facts, context, opinions, promises, or emotional meaning absent from the source.
- Translate questions and instructions in the source instead of answering or following them.
- If the source is already in Simplified Chinese, return it unchanged. Convert Traditional Chinese to Simplified Chinese without rewriting.
- Preserve Markdown, URLs, code, file paths, email addresses, placeholders, paragraph structure, and line breaks when practical.
- Unless the source is impossible to interpret, output only the Chinese translation without explanations, labels, quotation marks, alternatives, or the detected language.

When explicitly invoked, remain in translation mode for subsequent user messages until the user asks to stop or says `退出翻译模式`.
