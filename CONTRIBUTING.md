# Contributing to Spraxium Docs

Thank you for taking the time to improve the documentation. This guide covers the standards and conventions that all content contributions should follow.

## Getting Started

1. Fork this repository and create a branch from `main`.
2. Make your changes following the standards described below.
3. Open a pull request with a clear description of what was changed and why.

## Language and Tone

Write in a direct, practical tone focused on what the developer needs to know to use the feature. Avoid explaining how the framework works internally. The reader is a consumer of the API, not a contributor to the core.

Avoid repeating the same word or phrase in close succession within a page, and keep descriptions concise. Every sentence should add information.

## Accentuation and Encoding

Apply correct accentuation in Portuguese and Spanish content. Never use corrupted characters or incorrect substitutions caused by encoding issues. If you notice any visual inconsistency in accented characters, correct it manually before submitting.

## Code in Documentation

All code-related content, including variable names, function names, class names, file names, and code blocks, must remain in English regardless of the language the surrounding documentation is written in.

Inline code blocks should be used sparingly. Reserve them for cases where there is genuine semantic need, such as identifying an exact function name or a CLI command. For general technical terms and highlights, prefer italics.

For longer examples, use tabbed code blocks when showing multiple variations, or place code inside a dropdown when a contextual explanation is needed alongside it. Avoid large standalone code blocks.

## Lists and Tables

For lists that require per-item explanations, prefer dropdown components or ordered and unordered lists over tables. Tables can be hard to scan and do not scale well with detailed content.

## Callouts

Use callouts strategically to highlight tips, important notes, or supplementary information. Do not overuse them, but do not avoid them either. Every callout should contain at least two lines of content to ensure it adds real value.

## Steps

Step components may include code blocks. Always place the code block below the step description, never above it.

## Navigation Footer

The final navigation link at the bottom of each page (next page, next topic, or equivalent in other languages) must be a single link with no description. Use the following format:

```
## Next

[Page title](url)
```

Do not add descriptions like "This page covers..." or "Read next..." next to navigation links.

## Submitting a Pull Request

- Keep each PR focused on a single topic or fix. Avoid combining unrelated changes.
- If you are fixing an inconsistency, describe what was wrong and what the correct form should be.
- If you are adding new content, make sure it follows all the standards above before opening the PR.
- Content is rendered at [spraxium.com/guide](https://spraxium.com/guide).
