# Contributing to AI Prompt Library

Thank you for helping make this the best free prompt library on the internet.

## How to contribute

### Adding new prompts

1. Fork this repository
2. Find the right category folder (`ai-image-prompts/`, `resume-prompts/`, etc.)
3. Open the `README.md` inside that folder
4. Add your prompt inside a code block, following the existing format:

````
```
ROLE: ...
CONTEXT: ... [brackets] for anything the reader replaces
TASK: ...
CONSTRAINTS: ...
OUTPUT FORMAT: ...

> Before you start: ...
```

*One sentence: what this prompt produces and when to use it.*
````

5. Submit a pull request with a short description of what you added

### Adding a new category

If you have 20+ prompts for a topic that doesn't exist yet:

1. Create a new folder with a keyword-rich name (e.g. `email-writing-prompts/`)
2. Add a `README.md` inside it following the structure of existing category files
3. Update the root `README.md` table and the category list in `index.html`
4. Submit a pull request

### Guidelines

- **Be specific.** Vague prompts give vague results. Every prompt should include context, a goal, a format, and constraints where relevant.
- **Use `[brackets]`** for any part the user needs to replace with their own information.
- **Add an italic description** beneath every prompt — one sentence, plain English, explaining the output and when to use it.
- **Write for 2027 models.** End structured prompts with a footer that asks the AI to ask before guessing, check the latest data when it can search, and suggest a next step. Don't add "think step by step"; reasoning models already do.
- **No duplicates.** Check if a similar prompt already exists before adding.
- **No self-promotion.** Prompts must be useful first. No links inside prompts. The PromptIt links under each prompt are added by the maintainer, so leave them out of your PR.
- **Test your prompts.** Paste it into ChatGPT or the relevant AI tool before submitting to confirm it works.

## What makes a great prompt

A great prompt has five things:

| Element | Example |
|---|---|
| **Role** | "You are a professional resume writer..." |
| **Context** | "I have 5 years of experience in marketing..." |
| **Task** | "Write 3 achievement-focused bullet points..." |
| **Format** | "Keep each bullet under 20 words..." |
| **Constraints** | "Do not use the words 'responsible for' or 'helped'..." |

The more of these you include, the better the AI output.

## Questions?

Open an issue or visit [PromptIt](https://promptitin.com/?utm_source=github&utm_medium=prompt-library&utm_campaign=contributing) — a free tool that helps you build better prompts automatically.
