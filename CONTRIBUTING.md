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
Your prompt goes here — be as specific as possible. Include [brackets] for parts the user should replace.
```
> What this does: One clear sentence explaining what output this prompt produces and when to use it.
````

5. Submit a pull request with a short description of what you added

### Adding a new category

If you have 20+ prompts for a topic that doesn't exist yet:

1. Create a new folder with a keyword-rich name (e.g. `email-writing-prompts/`)
2. Add a `README.md` inside it following the structure of existing category files
3. Update the root `README.md` to include the new category in the table
4. Submit a pull request

### Guidelines

- **Be specific.** Vague prompts give vague results. Every prompt should include context, a goal, a format, and constraints where relevant.
- **Use `[brackets]`** for any part the user needs to replace with their own information.
- **Add a "What this does:" line** beneath every prompt — one sentence, plain English, explaining the output and when to use it.
- **No duplicates.** Check if a similar prompt already exists before adding.
- **No self-promotion.** Prompts must be useful first. Links are only allowed in the footer section.
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

Open an issue or visit [PromptIt](https://promptitin.com) — a free tool that helps you build better prompts automatically.
