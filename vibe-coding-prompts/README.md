# Vibe Coding Prompts — 25 Prompts for Lovable, Bolt, v0, Cursor & Claude Code (2027)

<p>
  <a href="https://chromewebstore.google.com/detail/promptit/dcnofbodfdmkljndkfnldlllclggnnbd?utm_source=github&utm_campaign=vibe-coding"><img src="https://img.shields.io/badge/Chrome_Extension-Enhance_prompts_inside_ChatGPT_%26_Claude-1A73E8?style=for-the-badge&logo=googlechrome&logoColor=white" alt="PromptIt Chrome extension"></a>
  <a href="https://promptitin.com/vibe?utm_source=github&utm_medium=prompt-library&utm_campaign=vibe-coding&utm_content=top"><img src="https://img.shields.io/badge/promptitin.com-Write_my_prompt_for_me-7C3AED?style=for-the-badge" alt="PromptIt"></a>
</p>

> ⚡ **Don't want to fill in the `[brackets]` yourself?** [PromptIt](https://promptitin.com/vibe?utm_source=github&utm_medium=prompt-library&utm_campaign=vibe-coding&utm_content=top) writes the full prompt for your exact situation in seconds.
> Using ChatGPT, Claude or Lovable? The **[free Chrome extension](https://chromewebstore.google.com/detail/promptit/dcnofbodfdmkljndkfnldlllclggnnbd?utm_source=github&utm_campaign=vibe-coding)** adds a one-click **Enhance** button right inside the chat box.

**[⭐ Star the repo](https://github.com/shakirdmr/ai-prompt-library)** so you can find it again — new prompts are added every month.


## What is this?

25 structured prompts for building real apps with AI app builders and coding agents: **Lovable**, **Bolt**, **v0**, **Replit Agent**, **Cursor**, **Claude Code**, **Codex** and **Windsurf**.

Most vibe-coded apps stall at the same point. The first screen looks great, then every new feature breaks two old ones. That happens because the AI was never told what the whole app is, which rules it must keep, or how to check its own work. These prompts fix that. They follow the order you actually build in: plan, scaffold, add features, connect the backend, fix bugs, ship.

## The 5-Part Prompt Structure

| Part | What it does |
|---|---|
| **ROLE** | Tells the AI which kind of engineer to be |
| **CONTEXT** | Your app, your stack, what already exists |
| **TASK** | Numbered steps, in the order the AI should do them |
| **CONSTRAINTS** | What it must not touch, break or invent |
| **OUTPUT FORMAT** | What you get back, so you can check it before accepting |

**Plus a 2027 footer** on every prompt: plan before coding, change the smallest amount possible, and prove the change works.

## How to use this

1. Pick the prompt for the stage you're at
2. Replace everything in `[brackets]`
3. Paste it into your builder's chat (Lovable, Bolt, v0, Replit) or your coding agent (Cursor, Claude Code, Codex)
4. In agent tools, use **plan mode** first for anything bigger than one file, then let it build
5. Commit or create a checkpoint after every prompt that works, so you can roll back

> **Works with:** Lovable, Bolt.new, v0, Replit Agent, Cursor, Claude Code, OpenAI Codex, Windsurf, GitHub Copilot agent mode.

---

## Plan Before You Build

*Spend 10 minutes here and you'll save a week of "fix this, now that's broken" loops.*

&nbsp;

**1. Turn an idea into a one-page PRD**

```
ROLE: You are a senior product manager who writes specs that AI coding tools can build from without guessing.

CONTEXT:
- App idea: [one or two sentences]
- Who it's for: [the specific user]
- The one problem it solves: [problem]
- Tool I'll build with: [Lovable / Bolt / v0 / Replit / Cursor / Claude Code]
- Deadline: [e.g. working MVP in 7 days]

TASK:
1. Write a one-page PRD: problem, target user, core user journey, and success metric
2. List the MVP features. Maximum 5. Move everything else to a "Later" list
3. Define every screen with its purpose and main elements
4. Define the data model: each table, its fields and how tables relate
5. List the edge cases the MVP must handle (empty states, errors, logged-out users)

CONSTRAINTS:
- If a feature doesn't serve the core journey, it goes to "Later"
- Use plain language. No buzzwords
- Do not choose libraries unless I asked

OUTPUT FORMAT:
- PRD in Markdown with headings: Problem, User, Journey, MVP Features, Later, Screens, Data Model, Edge Cases
- Under 700 words, so I can paste it as the first message in my builder

> Before you start: If my idea is too vague to pick 5 features, ask me up to 3 questions first. When done, tell me the riskiest assumption in this PRD and the cheapest way to test it before building.
```

*Gives your AI builder a spec it can follow, instead of a vibe it has to guess.*

<sub>⚡ [Get this prompt written for your app →](https://promptitin.com/vibe?utm_source=github&utm_medium=prompt-library&utm_campaign=vibe-coding&utm_content=p1) · [Do it inside ChatGPT with the Chrome extension](https://chromewebstore.google.com/detail/promptit/dcnofbodfdmkljndkfnldlllclggnnbd?utm_source=github&utm_campaign=vibe-coding)</sub>

&nbsp;

**2. Pick the right stack for a non-technical founder**

```
ROLE: You are a pragmatic CTO who advises non-technical founders and cares more about shipping than about trends.

CONTEXT:
- What I'm building: [short description or paste PRD]
- My skill level: [no code / some code / developer]
- Must-haves: [e.g. login, payments, file uploads, AI features, mobile]
- Budget per month: [$]
- Expected users in the first 6 months: [number]

TASK:
1. Recommend one builder or agent tool and explain why it fits me
2. Recommend the stack: frontend, backend/database, auth, payments, hosting
3. Estimate monthly cost at 100, 1,000 and 10,000 users
4. Name the 3 decisions that are hard to change later, and what to choose for each
5. Tell me what I'll need a developer for, and when

CONSTRAINTS:
- Prefer boring, well-documented tools that AI models already know well
- No more than one paid service I don't strictly need
- Be honest about lock-in

OUTPUT FORMAT:
- Recommendation table: layer, choice, why, cost
- Cost table by user count
- "Hard to change later" list
- "When you'll need a developer" in 3 bullets

> Before you start: If my must-haves conflict with my budget, say so first. If you can search the web, check current pricing and cite it; if you can't, flag prices that may be out of date. When done, tell me the one thing founders on this stack most often regret.
```

*Stops you picking a stack because a YouTuber did, and shows the real cost before you're locked in.*

<sub>⚡ [Get this prompt written for your app →](https://promptitin.com/vibe?utm_source=github&utm_medium=prompt-library&utm_campaign=vibe-coding&utm_content=p2) · [Do it inside ChatGPT with the Chrome extension](https://chromewebstore.google.com/detail/promptit/dcnofbodfdmkljndkfnldlllclggnnbd?utm_source=github&utm_campaign=vibe-coding)</sub>

&nbsp;

**3. Write the rules file for your AI agent (CLAUDE.md / AGENTS.md / .cursorrules)**

```
ROLE: You are a staff engineer who sets up repositories so AI coding agents produce consistent, safe changes.

CONTEXT:
- Project: [what it is]
- Stack: [framework, language, database, styling, hosting]
- Folder structure: [paste `tree -L 2` or describe it]
- Commands: [dev, build, test, lint]
- Things the AI keeps getting wrong: [e.g. creates duplicate components, uses old API, edits env files]

TASK:
1. Write a rules file for [CLAUDE.md / AGENTS.md / .cursor/rules]
2. Include: project summary, stack, commands, folder conventions, coding style, and how to verify a change
3. Add a "Never do" section based on the mistakes I listed, plus common ones for this stack
4. Add a "Before you finish" checklist the agent must run every time

CONSTRAINTS:
- Under 120 lines. Agents ignore long rules files
- Every rule must be specific and checkable. No "write clean code"
- Do not invent commands or folders I didn't give you

OUTPUT FORMAT:
- The file, ready to save, in one code block
- Then 3 bullets on what to add once the project grows

> Before you start: If I didn't give you the commands, ask for them instead of guessing. When done, tell me which rule will save me the most broken builds.
```

*The single highest-leverage file in an AI-built project. Write it once and every later prompt gets better.*

<sub>⚡ [Get this prompt written for your app →](https://promptitin.com/vibe?utm_source=github&utm_medium=prompt-library&utm_campaign=vibe-coding&utm_content=p3) · [Do it inside ChatGPT with the Chrome extension](https://chromewebstore.google.com/detail/promptit/dcnofbodfdmkljndkfnldlllclggnnbd?utm_source=github&utm_campaign=vibe-coding)</sub>

&nbsp;

**4. Break the PRD into build steps**

```
ROLE: You are a tech lead who breaks projects into small, testable steps an AI agent can finish one at a time.

CONTEXT:
- PRD: [paste]
- Tool: [Lovable / Bolt / v0 / Replit / Cursor / Claude Code]
- What already exists: [nothing / list of done features]

TASK:
1. Split the build into 8–15 steps, each finishable in one prompt
2. Order them so the app runs after every step
3. For each step, write the exact prompt I should paste into my tool
4. For each step, write a 1–3 line check I can do by clicking around to confirm it worked

CONSTRAINTS:
- Auth and data model come before features that depend on them
- No step touches more than about 5 files
- Design polish comes last

OUTPUT FORMAT:
- Numbered table: step, goal, prompt to paste, how to check

> Before you start: If the PRD is missing a data model, write one first and show it to me. When done, tell me which step is most likely to go wrong and how to recover if it does.
```

*Turns "build my app" into a checklist of small prompts that each leave the app working.*

<sub>⚡ [Get this prompt written for your app →](https://promptitin.com/vibe?utm_source=github&utm_medium=prompt-library&utm_campaign=vibe-coding&utm_content=p4) · [Do it inside ChatGPT with the Chrome extension](https://chromewebstore.google.com/detail/promptit/dcnofbodfdmkljndkfnldlllclggnnbd?utm_source=github&utm_campaign=vibe-coding)</sub>

---

## Scaffold & Design

*Getting the first version right so you're not fighting the layout for the rest of the project.*

&nbsp;

**5. First prompt for Lovable, Bolt or v0**

```
ROLE: You are a senior full-stack engineer and product designer building an MVP that must look credible on day one.

CONTEXT:
- App: [name and one-line description]
- User: [who]
- PRD: [paste, or the MVP feature list]
- Style: [e.g. calm and minimal like Linear / friendly like Notion / bold like Stripe]
- Brand colour: [hex, or "pick one"]

TASK:
1. Build the app shell: navigation, the main screens from the PRD, and routing between them
2. Use realistic sample data so every screen looks real
3. Include empty, loading and error states for every list and form
4. Make every screen work on a 375px phone and a desktop
5. Stop there. Do not add a backend, auth or payments yet

CONSTRAINTS:
- One design system: consistent spacing, type scale and component styles
- Accessible: real labels, visible focus states, colour contrast that passes WCAG AA
- No lorem ipsum. No features outside the PRD

OUTPUT FORMAT:
- The working app
- A short list of the screens you built and what's still placeholder

> Before you start: Plan the screens and components and show me the plan in under 10 lines before writing code. When done, list anything you assumed so I can correct it.
```

*The first message sets the quality bar for everything after it. This one sets it high.*

<sub>⚡ [Get this prompt written for your app →](https://promptitin.com/vibe?utm_source=github&utm_medium=prompt-library&utm_campaign=vibe-coding&utm_content=p5) · [Do it inside ChatGPT with the Chrome extension](https://chromewebstore.google.com/detail/promptit/dcnofbodfdmkljndkfnldlllclggnnbd?utm_source=github&utm_campaign=vibe-coding)</sub>

&nbsp;

**6. Turn a screenshot into a component**

```
ROLE: You are a front-end engineer who recreates designs pixel-close using the project's existing components.

CONTEXT:
- Screenshot: [attach]
- Where it goes: [page / route]
- Stack: [e.g. React + Tailwind + shadcn/ui]
- Existing components to reuse: [list, or "check the components folder"]

TASK:
1. Describe the layout you see in 5 bullets before building
2. Build it using existing components first; only create new ones when nothing fits
3. Make it responsive. Explain what changes on mobile
4. Wire up hover, focus and disabled states

CONSTRAINTS:
- Do not copy logos, brand names or copyrighted images from the screenshot; use placeholders
- Match spacing and type to our design system, not exact pixels, if they conflict

OUTPUT FORMAT:
- The component
- A list of new components you created, with a reason for each

> Before you start: If the screenshot is ambiguous on mobile, ask me one question. When done, point out one part of the design that will be hard to maintain.
```

*Gets you the look you want without five rounds of "no, move it left".*

<sub>⚡ [Get this prompt written for your app →](https://promptitin.com/vibe?utm_source=github&utm_medium=prompt-library&utm_campaign=vibe-coding&utm_content=p6) · [Do it inside ChatGPT with the Chrome extension](https://chromewebstore.google.com/detail/promptit/dcnofbodfdmkljndkfnldlllclggnnbd?utm_source=github&utm_campaign=vibe-coding)</sub>

&nbsp;

**7. Make my app look less AI-generated**

```
ROLE: You are a product designer who has shipped interfaces at top SaaS companies and can spot a template from across the room.

CONTEXT:
- App: [what it does, who it's for]
- Screenshots or page code: [attach]
- What feels off: [e.g. generic, too many gradients, looks like every other AI app]

TASK:
1. List the 10 things that make it look generic, most visible first
2. Fix the top 5: typography, spacing, colour, hierarchy, copy
3. Replace generic copy ("Unlock your potential") with specific copy for my user
4. Suggest one distinctive detail that fits the brand

CONSTRAINTS:
- Keep the layout and functionality as is. Change style and words only
- Fewer colours, not more. No new gradients, glows or emojis unless I ask
- Keep it accessible

OUTPUT FORMAT:
- The list of 10 issues
- The changes, file by file
- Before/after for every copy change

> Before you start: If you can't see the design, ask for screenshots. When done, tell me the one change that made the biggest difference.
```

*The difference between "made with AI" and "made by a team that cares".*

<sub>⚡ [Get this prompt written for your app →](https://promptitin.com/vibe?utm_source=github&utm_medium=prompt-library&utm_campaign=vibe-coding&utm_content=p7) · [Do it inside ChatGPT with the Chrome extension](https://chromewebstore.google.com/detail/promptit/dcnofbodfdmkljndkfnldlllclggnnbd?utm_source=github&utm_campaign=vibe-coding)</sub>

&nbsp;

**8. Build a landing page that converts**

```
ROLE: You are a conversion copywriter and designer who writes SaaS landing pages that turn visitors into sign-ups.

CONTEXT:
- Product: [what it does]
- Customer: [who, and the moment they need it]
- Main benefit: [the outcome, not the feature]
- Proof I have: [testimonials, numbers, logos, or "none yet"]
- Call to action: [e.g. "Start free", "Join waitlist"]

TASK:
1. Write the page: hero, problem, how it works (3 steps), features as benefits, proof, FAQ, final CTA
2. Build it as one responsive page
3. Add title, meta description and Open Graph tags
4. Make it load fast: no heavy libraries, optimised images

CONSTRAINTS:
- Headline under 10 words and specific to my customer
- Never invent testimonials, user counts or logos. Leave a clear placeholder instead
- One primary CTA, repeated; no competing buttons

OUTPUT FORMAT:
- The page
- A copy doc listing every headline and 2 alternatives for A/B testing

> Before you start: If my main benefit is really a feature, rewrite it as an outcome and show me. When done, tell me which section to cut if visitors don't scroll.
```

*A landing page with honest proof and one clear action, built in one prompt.*

<sub>⚡ [Get this prompt written for your app →](https://promptitin.com/vibe?utm_source=github&utm_medium=prompt-library&utm_campaign=vibe-coding&utm_content=p8) · [Do it inside ChatGPT with the Chrome extension](https://chromewebstore.google.com/detail/promptit/dcnofbodfdmkljndkfnldlllclggnnbd?utm_source=github&utm_campaign=vibe-coding)</sub>

---

## Backend, Auth & Data

*Where most vibe-coded apps break. Go slow here.*

&nbsp;

**9. Design the database schema**

```
ROLE: You are a database engineer who designs schemas that stay simple as an app grows.

CONTEXT:
- PRD or feature list: [paste]
- Database: [Supabase Postgres / Firebase / Convex / other]
- Multi-user? [yes, each user sees only their data / teams share data / public data]

TASK:
1. Design the tables, fields, types and relationships
2. Add indexes for the queries the app will run most
3. Write the migration SQL (or schema file for my database)
4. Write row-level security rules so users can only reach their own data
5. Add seed data for testing

CONSTRAINTS:
- Use timestamps and soft deletes only where needed
- No table without a clear owner rule
- Explain every security rule in one plain sentence

OUTPUT FORMAT:
- Diagram in Mermaid
- Migration in one code block
- Security rules in one code block
- Table: query the app runs → index that serves it

> Before you start: If teams or sharing are unclear, ask before designing, because it changes everything. When done, tell me which table will need changing first as the app grows.
```

*A schema with security built in, instead of bolted on after a data leak.*

<sub>⚡ [Get this prompt written for your app →](https://promptitin.com/vibe?utm_source=github&utm_medium=prompt-library&utm_campaign=vibe-coding&utm_content=p9) · [Do it inside ChatGPT with the Chrome extension](https://chromewebstore.google.com/detail/promptit/dcnofbodfdmkljndkfnldlllclggnnbd?utm_source=github&utm_campaign=vibe-coding)</sub>

&nbsp;

**10. Add login and sign-up properly**

```
ROLE: You are a security-minded full-stack engineer adding authentication to an existing app.

CONTEXT:
- Stack: [e.g. Next.js + Supabase Auth / Clerk / Firebase Auth]
- Sign-in methods: [email + password / magic link / Google / GitHub]
- Pages that need login: [list]
- Pages that stay public: [list]

TASK:
1. Add sign-up, sign-in, sign-out and password reset
2. Protect private pages on the server, not just by hiding buttons
3. Create a user profile row on first sign-in
4. Handle every error with a clear message (wrong password, unconfirmed email, expired link)
5. Redirect users back to the page they wanted after signing in

CONSTRAINTS:
- Never store passwords or tokens yourself
- Never expose service or secret keys to the browser
- Don't change pages unrelated to auth

OUTPUT FORMAT:
- Files changed, with a one-line reason each
- A manual test checklist with 8 cases to click through

> Before you start: Show me the plan and list every file you'll touch. When done, tell me the one auth bug most AI-built apps ship with and confirm we don't have it.
```

*Auth that actually protects pages, not just hides the button.*

<sub>⚡ [Get this prompt written for your app →](https://promptitin.com/vibe?utm_source=github&utm_medium=prompt-library&utm_campaign=vibe-coding&utm_content=p10) · [Do it inside ChatGPT with the Chrome extension](https://chromewebstore.google.com/detail/promptit/dcnofbodfdmkljndkfnldlllclggnnbd?utm_source=github&utm_campaign=vibe-coding)</sub>

&nbsp;

**11. Add Stripe payments and subscriptions**

```
ROLE: You are a payments engineer who has integrated Stripe into dozens of SaaS apps.

CONTEXT:
- Stack: [framework + database]
- Plans: [e.g. Free, Pro $12/mo, Team $49/mo]
- What each plan unlocks: [list]
- Payment provider: [Stripe / Lemon Squeezy / Paddle / Dodo]

TASK:
1. Add a pricing page with checkout for each paid plan
2. Handle webhooks: payment succeeded, subscription updated, cancelled, payment failed
3. Store the user's plan in the database from the webhook, never from the browser
4. Gate features by plan on the server
5. Add a "Manage billing" link to the customer portal

CONSTRAINTS:
- Verify webhook signatures
- Webhook handlers must be safe to run twice
- Test mode first; list exactly what changes for live mode

OUTPUT FORMAT:
- Files changed
- Environment variables needed (names only, no values)
- Test plan using test cards, including a failed payment

> Before you start: Confirm the plan names and prices with me. When done, tell me how to check that a cancelled user really loses access.
```

*Payments where the database, not the browser, decides who has paid.*

<sub>⚡ [Get this prompt written for your app →](https://promptitin.com/vibe?utm_source=github&utm_medium=prompt-library&utm_campaign=vibe-coding&utm_content=p11) · [Do it inside ChatGPT with the Chrome extension](https://chromewebstore.google.com/detail/promptit/dcnofbodfdmkljndkfnldlllclggnnbd?utm_source=github&utm_campaign=vibe-coding)</sub>

&nbsp;

**12. Add an AI feature to my app**

```
ROLE: You are an AI engineer who ships LLM features that are fast, cheap and hard to abuse.

CONTEXT:
- Feature: [e.g. summarise uploaded PDFs / write product descriptions / chat with your data]
- Model provider: [OpenAI / Anthropic / Google / OpenRouter]
- Expected usage: [requests per user per day]
- Stack: [framework]

TASK:
1. Build the API route that calls the model on the server
2. Write the system prompt for this feature, using role, context, task, constraints and output format
3. Stream the response to the UI
4. Add per-user rate limits and a usage counter
5. Handle failures: timeouts, refusals, empty output

CONSTRAINTS:
- API keys stay on the server
- Treat user input and uploaded files as untrusted; they must not override the system prompt
- Use structured output (JSON schema) where the UI needs fields

OUTPUT FORMAT:
- Files changed
- The system prompt in its own block
- Cost estimate per 1,000 requests

> Before you start: Ask which model I'm using if I didn't say. If you can search the web, check current model pricing and cite it. When done, tell me how a user could misuse this feature and how we've limited it.
```

*An AI feature with limits, streaming and a real system prompt, not a raw API call in the browser.*

<sub>⚡ [Get this prompt written for your app →](https://promptitin.com/vibe?utm_source=github&utm_medium=prompt-library&utm_campaign=vibe-coding&utm_content=p12) · [Do it inside ChatGPT with the Chrome extension](https://chromewebstore.google.com/detail/promptit/dcnofbodfdmkljndkfnldlllclggnnbd?utm_source=github&utm_campaign=vibe-coding)</sub>

&nbsp;

**13. Connect a third-party API**

```
ROLE: You are a backend engineer who integrates external APIs defensively.

CONTEXT:
- API: [name + docs link]
- What I need from it: [data or action]
- Where it's used in my app: [page / feature]

TASK:
1. Read the docs and summarise the endpoints, auth method and rate limits I need
2. Write a small server-side client for just those endpoints
3. Cache responses where it's safe
4. Handle errors, timeouts and rate-limit responses with retries and clear UI messages

CONSTRAINTS:
- Use only endpoints that exist in the docs. If you're unsure, say so instead of guessing
- Keys from environment variables only

OUTPUT FORMAT:
- Summary of the API in 5 bullets
- The client code and where it's used
- What happens in the UI when the API is down

> Before you start: If you can browse, read the current docs before writing code and link the pages you used. When done, tell me the most likely way this integration breaks in 6 months.
```

*Stops the AI inventing endpoints that don't exist.*

<sub>⚡ [Get this prompt written for your app →](https://promptitin.com/vibe?utm_source=github&utm_medium=prompt-library&utm_campaign=vibe-coding&utm_content=p13) · [Do it inside ChatGPT with the Chrome extension](https://chromewebstore.google.com/detail/promptit/dcnofbodfdmkljndkfnldlllclggnnbd?utm_source=github&utm_campaign=vibe-coding)</sub>

---

## Features & Changes

*Adding things without breaking what works.*

&nbsp;

**14. Add a feature without breaking anything**

```
ROLE: You are a careful senior engineer working in a codebase you didn't write.

CONTEXT:
- Feature: [describe what the user should be able to do]
- Where: [page / area]
- What must keep working: [list the flows that matter most]

TASK:
1. Read the relevant files and summarise how this area works now
2. Propose the smallest change that delivers the feature
3. Build it, reusing existing components, styles and helpers
4. Check the flows I listed still work

CONSTRAINTS:
- Do not refactor, rename or reformat code unrelated to this feature
- No new dependencies without asking
- If the change needs more than [5] files, stop and explain why first

OUTPUT FORMAT:
- Plan (before coding)
- Files changed with a reason each
- How to test it in 3 steps

> Before you start: Show me the plan and wait for my OK before writing code. When done, list anything you noticed but deliberately didn't change.
```

*The everyday prompt. Use it for every feature and your app stays stable.*

<sub>⚡ [Get this prompt written for your app →](https://promptitin.com/vibe?utm_source=github&utm_medium=prompt-library&utm_campaign=vibe-coding&utm_content=p14) · [Do it inside ChatGPT with the Chrome extension](https://chromewebstore.google.com/detail/promptit/dcnofbodfdmkljndkfnldlllclggnnbd?utm_source=github&utm_campaign=vibe-coding)</sub>

&nbsp;

**15. Refactor a messy file**

```
ROLE: You are a senior engineer who refactors for readability without changing behaviour.

CONTEXT:
- File: [path]
- Problem: [too long / duplicated logic / hard to change]

TASK:
1. Explain what the file does in 5 bullets
2. Propose a refactor plan in small steps
3. Apply it one step at a time, keeping behaviour identical
4. Run the build and tests after each step

CONSTRAINTS:
- No behaviour changes. If you find a bug, report it, don't fix it in this change
- No new abstractions unless they remove real duplication

OUTPUT FORMAT:
- Plan
- Diff summary per step
- Line count before and after

> Before you start: If there are no tests for this file, write a few that pin the current behaviour first. When done, tell me the next file most worth cleaning.
```

*Cleaner code with tests that prove nothing changed.*

<sub>⚡ [Get this prompt written for your app →](https://promptitin.com/vibe?utm_source=github&utm_medium=prompt-library&utm_campaign=vibe-coding&utm_content=p15) · [Do it inside ChatGPT with the Chrome extension](https://chromewebstore.google.com/detail/promptit/dcnofbodfdmkljndkfnldlllclggnnbd?utm_source=github&utm_campaign=vibe-coding)</sub>

&nbsp;

**16. Make the app work on mobile**

```
ROLE: You are a front-end engineer who specialises in responsive layouts.

CONTEXT:
- Pages: [list, or "all"]
- Problems I see on my phone: [e.g. text overflows, buttons off screen, horizontal scroll]

TASK:
1. Check every listed page at 375px, 768px and 1280px widths
2. Fix overflow, tap targets under 44px, fixed widths and tables
3. Make navigation work with one thumb
4. Keep the desktop layout unchanged

CONSTRAINTS:
- Fix with layout, not by hiding content
- No horizontal scrolling at any width

OUTPUT FORMAT:
- Table: page, issue, fix
- Files changed

> Before you start: If you can take screenshots, check each page before and after. When done, tell me which page still feels worst on mobile.
```

*Most of your users are on a phone. This makes the app work for them.*

<sub>⚡ [Get this prompt written for your app →](https://promptitin.com/vibe?utm_source=github&utm_medium=prompt-library&utm_campaign=vibe-coding&utm_content=p16) · [Do it inside ChatGPT with the Chrome extension](https://chromewebstore.google.com/detail/promptit/dcnofbodfdmkljndkfnldlllclggnnbd?utm_source=github&utm_campaign=vibe-coding)</sub>

&nbsp;

**17. Add analytics and events**

```
ROLE: You are a growth engineer who instruments products so founders can see what users actually do.

CONTEXT:
- Analytics tool: [PostHog / Plausible / GA4 / Umami]
- Key journey: [e.g. land → sign up → create first project → invite teammate → pay]

TASK:
1. Define 8–12 events covering the journey, with clear names and properties
2. Add the tracking code
3. Identify users on sign-in and reset on sign-out
4. Describe the funnel and the 3 charts I should build

CONSTRAINTS:
- No personal data (emails, names) in event properties
- Respect cookie consent where the law requires it

OUTPUT FORMAT:
- Event table: name, when it fires, properties
- Files changed
- The 3 charts to build

> Before you start: Confirm my key journey. When done, tell me the one number I should check every morning.
```

*Know where users drop off instead of guessing.*

<sub>⚡ [Get this prompt written for your app →](https://promptitin.com/vibe?utm_source=github&utm_medium=prompt-library&utm_campaign=vibe-coding&utm_content=p17) · [Do it inside ChatGPT with the Chrome extension](https://chromewebstore.google.com/detail/promptit/dcnofbodfdmkljndkfnldlllclggnnbd?utm_source=github&utm_campaign=vibe-coding)</sub>

---

## Debug & Fix

*When the AI broke it, or you can't tell what's wrong.*

&nbsp;

**18. Fix a bug the right way**

```
ROLE: You are a senior debugging engineer who finds root causes instead of patching symptoms.

CONTEXT:
- What should happen: [expected]
- What happens: [actual]
- Steps to reproduce: [1, 2, 3]
- Error message: [paste the full error and stack trace]
- What changed recently: [last prompt or commit]

TASK:
1. List 3 possible causes, most likely first
2. Check each one by reading the code or adding a log, and say what you found
3. Fix the root cause with the smallest change
4. Explain why the bug happened in two sentences

CONSTRAINTS:
- Do not rewrite working code to "be safe"
- Do not hide the error with try/catch or by removing checks
- If you can't reproduce it, say so and tell me what you need

OUTPUT FORMAT:
- Hypotheses and what you found
- The fix
- How to confirm it's fixed

> Before you start: Reproduce the bug before changing anything. When done, tell me how to stop this kind of bug happening again.
```

*Breaks the "AI fixes one thing, breaks another" loop.*

<sub>⚡ [Get this prompt written for your app →](https://promptitin.com/vibe?utm_source=github&utm_medium=prompt-library&utm_campaign=vibe-coding&utm_content=p18) · [Do it inside ChatGPT with the Chrome extension](https://chromewebstore.google.com/detail/promptit/dcnofbodfdmkljndkfnldlllclggnnbd?utm_source=github&utm_campaign=vibe-coding)</sub>

&nbsp;

**19. The AI is going in circles**

```
ROLE: You are a staff engineer called in after an AI agent tried to fix the same problem several times and failed.

CONTEXT:
- The original goal: [what I wanted]
- What the AI tried: [summary of the attempts]
- Current state: [what works, what's broken]

TASK:
1. Stop and list everything that has been changed for this problem
2. Decide whether to keep going or roll back to the last working version, and explain why
3. If rolling back: write the exact steps
4. Write a fresh, smaller plan that approaches the goal differently

CONSTRAINTS:
- Do not try the same fix again
- Prefer fewer moving parts over a clever fix

OUTPUT FORMAT:
- Change list
- Keep or roll back, with the reason
- New plan in 5 steps or fewer

> Before you start: Read the current code again; don't trust what earlier attempts said they did. When done, tell me what to put in my rules file so this doesn't happen again.
```

*The reset button for when you've sent "still broken" five times.*

<sub>⚡ [Get this prompt written for your app →](https://promptitin.com/vibe?utm_source=github&utm_medium=prompt-library&utm_campaign=vibe-coding&utm_content=p19) · [Do it inside ChatGPT with the Chrome extension](https://chromewebstore.google.com/detail/promptit/dcnofbodfdmkljndkfnldlllclggnnbd?utm_source=github&utm_campaign=vibe-coding)</sub>

&nbsp;

**20. Explain this codebase to me**

```
ROLE: You are a patient senior engineer onboarding a non-technical founder to their own codebase.

CONTEXT:
- Repo or project: [attached / open in the tool]
- What I want to be able to do: [e.g. change copy, add a page, understand costs]

TASK:
1. Explain what the app does and how it's built, in plain words
2. Map the important folders and files: what each does
3. Trace one full user action from button click to database and back
4. List the 5 files I'm most likely to need to edit, and what for
5. List anything that looks risky: secrets, missing checks, dead code

CONSTRAINTS:
- No jargon without a one-line explanation
- Don't change any code

OUTPUT FORMAT:
- Overview (5 sentences)
- Folder map
- Request trace as numbered steps
- "Files you'll edit" table
- Risks list

> Before you start: If the repo is large, ask which area matters most. When done, suggest 3 questions I should ask next.
```

*Understand what you own before you pay someone else to understand it.*

<sub>⚡ [Get this prompt written for your app →](https://promptitin.com/vibe?utm_source=github&utm_medium=prompt-library&utm_campaign=vibe-coding&utm_content=p20) · [Do it inside ChatGPT with the Chrome extension](https://chromewebstore.google.com/detail/promptit/dcnofbodfdmkljndkfnldlllclggnnbd?utm_source=github&utm_campaign=vibe-coding)</sub>

---

## Ship & Grow

*Getting from "works on my screen" to live and safe.*

&nbsp;

**21. Security review before launch**

```
ROLE: You are an application security engineer reviewing an AI-built app before it goes live.

CONTEXT:
- Stack: [framework, database, auth, hosting]
- Sensitive data: [e.g. emails, payments, uploaded files]

TASK:
1. Check for exposed secrets in the code and the browser bundle
2. Check that every API route and database query enforces who can access what
3. Check inputs for injection, file uploads for type and size limits
4. Check rate limits on sign-up, login and any paid or AI endpoints
5. Rank every issue: critical, high, medium, low

CONSTRAINTS:
- Report only issues you can point to in the code, with file and line
- Give the fix for each, but don't apply fixes until I approve

OUTPUT FORMAT:
- Table: severity, issue, file:line, fix
- "Fix before launch" list

> Before you start: If you can't see the database rules, ask for them; they're where most leaks happen. When done, tell me the one issue an attacker would find first.
```

*The 30-minute check that stops your launch becoming a data-leak post.*

<sub>⚡ [Get this prompt written for your app →](https://promptitin.com/vibe?utm_source=github&utm_medium=prompt-library&utm_campaign=vibe-coding&utm_content=p21) · [Do it inside ChatGPT with the Chrome extension](https://chromewebstore.google.com/detail/promptit/dcnofbodfdmkljndkfnldlllclggnnbd?utm_source=github&utm_campaign=vibe-coding)</sub>

&nbsp;

**22. Speed up a slow app**

```
ROLE: You are a performance engineer who makes web apps feel instant.

CONTEXT:
- Slow pages or actions: [list]
- Lighthouse or Web Vitals scores: [paste, or "not measured"]

TASK:
1. Find the causes: large bundles, slow queries, waterfalls, unoptimised images
2. Rank fixes by impact versus effort
3. Apply the top 3
4. Measure before and after

CONSTRAINTS:
- No behaviour changes
- No caching that could show one user another user's data

OUTPUT FORMAT:
- Table: cause, fix, impact, effort
- Before/after numbers

> Before you start: Measure first; don't guess. When done, tell me what will get slow next as users grow.
```

*Faster pages, with numbers to prove it.*

<sub>⚡ [Get this prompt written for your app →](https://promptitin.com/vibe?utm_source=github&utm_medium=prompt-library&utm_campaign=vibe-coding&utm_content=p22) · [Do it inside ChatGPT with the Chrome extension](https://chromewebstore.google.com/detail/promptit/dcnofbodfdmkljndkfnldlllclggnnbd?utm_source=github&utm_campaign=vibe-coding)</sub>

&nbsp;

**23. Write tests for the parts that matter**

```
ROLE: You are a test engineer who writes the fewest tests that catch the most real bugs.

CONTEXT:
- Critical flows: [e.g. sign up, checkout, create project]
- Test tools: [Vitest / Jest / Playwright / none yet]

TASK:
1. Set up the test tool if needed
2. Write one end-to-end test per critical flow
3. Write unit tests for the riskiest logic (money, permissions, dates)
4. Add a single command that runs everything

CONSTRAINTS:
- Tests must fail if the feature breaks. No tests that only check the code runs
- No real payments or emails in tests

OUTPUT FORMAT:
- Files added
- The command to run them
- What each test protects

> Before you start: Ask which flows lose me money or users if they break. When done, tell me how to run these automatically on every push.
```

*A safety net, so the next AI change can't silently break checkout.*

<sub>⚡ [Get this prompt written for your app →](https://promptitin.com/vibe?utm_source=github&utm_medium=prompt-library&utm_campaign=vibe-coding&utm_content=p23) · [Do it inside ChatGPT with the Chrome extension](https://chromewebstore.google.com/detail/promptit/dcnofbodfdmkljndkfnldlllclggnnbd?utm_source=github&utm_campaign=vibe-coding)</sub>

&nbsp;

**24. Deploy to production**

```
ROLE: You are a DevOps engineer who deploys small SaaS apps safely.

CONTEXT:
- Host: [Vercel / Netlify / Railway / Render / Cloudflare]
- Database: [provider]
- Domain: [domain]

TASK:
1. List every environment variable needed in production
2. Set up the production build and deploy
3. Connect the domain with HTTPS
4. Set up error tracking and uptime monitoring
5. Write a rollback plan

CONSTRAINTS:
- Separate production and development databases and keys
- No secrets in the repo

OUTPUT FORMAT:
- Step-by-step checklist I can tick off
- Rollback steps

> Before you start: If you can search the web, check the host's current docs and link them. When done, tell me what to check in the first hour after launch.
```

*Launch day as a checklist, not a panic.*

<sub>⚡ [Get this prompt written for your app →](https://promptitin.com/vibe?utm_source=github&utm_medium=prompt-library&utm_campaign=vibe-coding&utm_content=p24) · [Do it inside ChatGPT with the Chrome extension](https://chromewebstore.google.com/detail/promptit/dcnofbodfdmkljndkfnldlllclggnnbd?utm_source=github&utm_campaign=vibe-coding)</sub>

&nbsp;

**25. Plan my launch**

```
ROLE: You are an indie launch strategist who has helped dozens of small SaaS products get their first 100 users.

CONTEXT:
- Product: [what it does, link]
- Customer: [who]
- Where they hang out: [communities, platforms]
- Assets I have: [demo video, screenshots, founder story]

TASK:
1. Write a 14-day launch plan, day by day
2. Write the Product Hunt tagline and description, a Show HN post, and a Reddit post that follows community rules
3. List 10 directories to submit to, most relevant first
4. Write 3 cold DMs to potential users that ask for feedback, not sales

CONSTRAINTS:
- No fake reviews, sock-puppet accounts or vote trading
- Every post must give value on its own, not just a link

OUTPUT FORMAT:
- Day-by-day table
- Copy for each post in its own block
- Directory list with links

> Before you start: Ask for my product link if I didn't give it. If you can search the web, check each community's current self-promotion rules. When done, tell me the one channel to focus on if I only have 2 hours a day.
```

*Your first 100 users, without spamming anyone.*

<sub>⚡ [Get this prompt written for your app →](https://promptitin.com/vibe?utm_source=github&utm_medium=prompt-library&utm_campaign=vibe-coding&utm_content=p25) · [Do it inside ChatGPT with the Chrome extension](https://chromewebstore.google.com/detail/promptit/dcnofbodfdmkljndkfnldlllclggnnbd?utm_source=github&utm_campaign=vibe-coding)</sub>

---

## Get better results from every prompt

| | |
|---|---|
| ⚡ **[PromptIt](https://promptitin.com/vibe?utm_source=github&utm_medium=prompt-library&utm_campaign=vibe-coding&utm_content=footer)** | Type a rough idea, get a structured, expert-level prompt back. Free to start. |
| 🧩 **[Chrome extension](https://chromewebstore.google.com/detail/promptit/dcnofbodfdmkljndkfnldlllclggnnbd?utm_source=github&utm_campaign=vibe-coding)** | Improve prompts without leaving ChatGPT, Claude, Lovable, Bolt, Replit or v0. |
| 📘 **[Prompt engineering guide](https://promptitin.com/guides/what-is-prompt-engineering?utm_source=github&utm_medium=prompt-library&utm_campaign=vibe-coding)** | Why these prompts work, and how to write your own. |

**If this saved you time, [⭐ star the repo](https://github.com/shakirdmr/ai-prompt-library)** — it's the only way others find it. Want to say thanks? [☕ Buy me a coffee](https://buymeacoffee.com/shakirdmr).

[← Back to all categories](../README.md)
