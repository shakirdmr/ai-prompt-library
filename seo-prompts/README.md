# SEO Prompts — 10 Deep Structured Prompts

## What is this?

This is a collection of 10 structured prompts for doing professional SEO work with **ChatGPT** or **Claude** — from keyword research to content strategy, page audits, and building your first 6-month plan.

Every prompt in this file follows the same five-part structure used by professional prompt engineers:

| Part | What it does |
|---|---|
| **ROLE** | Tells the AI who to be — a specific expert, not just "an assistant" |
| **CONTEXT** | Your situation — fill in the brackets with your real details |
| **TASK** | Numbered steps — exactly what you want the AI to do |
| **CONSTRAINTS** | Rules the AI must follow — keeps output focused and useful |
| **OUTPUT FORMAT** | Tells the AI exactly what the response should look like |

Plus every prompt ends with a **power line** that triggers three advanced techniques automatically: asking for missing info before starting, thinking step by step, and suggesting what to do next.

**You don't need to understand any of this.** Just copy, fill in your details, and paste. The structure does the work.

> Want AI to build prompts like these for you automatically? Try **[PromptIt](https://promptitin.com)** — free prompt enhancer that applies this structure to any rough idea.

## How to use this

1. Open [ChatGPT](https://chat.openai.com) or [Claude](https://claude.ai) — both free
2. Copy the full prompt including every section
3. Replace everything inside `[brackets]` with your real information
4. Paste and send

---

&nbsp;

**1. Keyword Research Strategy**

```
ROLE: You are a senior SEO strategist with 10+ years of experience growing organic traffic for small and medium businesses. You specialise in identifying low-competition, high-intent keywords that new websites can realistically rank for — not just the obvious ones that billion-dollar brands dominate.

CONTEXT:
- My website: [URL or brief description of what it does]
- My audience: [who you are trying to reach — their job, problem, or goal]
- My niche/topic: [what your site covers]
- Current traffic: [rough monthly visitors, or "almost none / just launched"]
- Tools I have access to: [Google Search Console / Ahrefs / Ubersuggest / none]

TASK:
1. Identify 5 high-intent, low-competition keywords I can realistically rank for within 3–6 months
2. For each keyword: explain the search intent, why it's achievable for my site, and what content format would rank (blog post, comparison page, guide, etc.)
3. Identify 3 long-tail variations of your top recommended keyword
4. Tell me which 1–2 keywords to target first and exactly why
5. Flag any keywords I should avoid — ones that look good but are actually traps for new sites

CONSTRAINTS:
- Do not suggest head terms dominated by Wikipedia, Reddit, or major brands
- Every keyword must match a realistic content piece I could publish this month
- Prioritise buyer-intent and problem-aware keywords over pure informational ones
- Base your reasoning on what is realistic for a new or small site, not an established domain

OUTPUT FORMAT:
- A numbered list of 5 keywords, each with: keyword, monthly search estimate, difficulty (low/medium/high), intent, content type, and a one-sentence "why this works for you"
- Below that: the 3 long-tail variations
- Below that: a "Start here" recommendation with 2–3 sentences of reasoning
- Keep the full response under 600 words

> Before you start: If anything in my context is missing or would significantly change your recommendations, ask me one specific question first. Then work through your answer step by step. When done, tell me: (1) one piece of information that would make your keyword list even more accurate, and (2) the best next prompt I should run after this one.
```
*Builds your entire keyword strategy from scratch — gives you a prioritised list of keywords you can actually rank for, not just popular ones dominated by major sites.*

&nbsp;

**2. SEO Content Brief**

```
ROLE: You are an SEO content strategist who writes briefs used by professional writers to produce articles that rank on page 1 of Google. You understand both what Google's algorithm rewards and what human readers actually want to finish reading.

CONTEXT:
- Target keyword: [the exact keyword phrase you want to rank for]
- My website topic: [what your site is about]
- My audience: [who is reading this — their experience level and what they want]
- Competitors I want to outrank: [paste 1–3 competitor URLs that currently rank for this keyword, or leave blank]
- Content goal: [rank on Google / drive sign-ups / educate readers / all of the above]

TASK:
1. Write a compelling H1 title — keyword included naturally, click-worthy, under 65 characters
2. Write a meta description — 150–160 characters, keyword included, gives a clear reason to click
3. Suggest the ideal URL slug — short, keyword-focused, no stop words
4. Create a full content outline — H2 and H3 headings that cover the topic completely and match search intent
5. Recommend a word count range and explain why
6. List 3–5 semantic/related keywords to include naturally throughout the article
7. Identify the top 2–3 things the best-ranking articles cover that I must also cover
8. Suggest one original angle or data point I could include that competitors are missing

CONSTRAINTS:
- Every H2 must address a real question or need the reader has — not just a topic label
- The outline must answer search intent fully, not just mention the subject
- No filler sections ("Introduction", "Conclusion") — every heading must earn its place
- The meta description must not start with the keyword — lead with the benefit

OUTPUT FORMAT:
- Title (H1)
- Meta description
- URL slug
- Full outline (H2s and H3s, indented)
- Word count recommendation with reasoning
- Semantic keywords list
- "Must cover" checklist
- "Original angle" suggestion
- Total response under 500 words

> Before you start: If my context is missing details that would significantly change the brief, ask me one question first. Work through the outline step by step, starting from what the reader is actually trying to accomplish. When done, flag: (1) the one section most likely to determine whether this article ranks or not, and (2) the next prompt I should run to begin writing the article.
```
*A full SEO blueprint before you write a single word — so the article is built for ranking from the start, not patched afterwards.*

&nbsp;

**3. On-Page SEO Audit**

```
ROLE: You are a technical and on-page SEO auditor who has audited thousands of pages. You identify exactly what is stopping a specific page from ranking higher and give a prioritised, actionable fix list — not a generic checklist.

CONTEXT:
- Page URL: [your page URL]
- Target keyword: [the keyword you want this page to rank for]
- Current Google position: [position number, or "not ranking / not sure"]
- Current title tag: [paste your current title]
- Current meta description: [paste your current meta description]
- Current H1: [paste your H1]
- First 150 words of the page: [paste your opening paragraph(s)]
- Monthly impressions in Google Search Console (if known): [number or "unknown"]

TASK:
1. Audit the title tag — is the keyword placed correctly? Rewrite it (max 60 characters, keyword near the front, click-worthy)
2. Audit the meta description — rewrite it (150–160 chars, keyword included, benefit-led hook)
3. Audit the H1 — does it match search intent? Suggest an improvement if needed
4. Assess the opening 150 words — what is missing? What should be restructured?
5. List 3 quick wins I can implement today with the highest ranking impact
6. Name the single most likely reason this page is underperforming
7. If impressions are high but clicks are low — diagnose the CTR problem specifically

CONSTRAINTS:
- Be specific: tell me exactly what to change and what to change it to — not what category of change to make
- Do not give general SEO advice — every point must be specific to the content I pasted
- Prioritise by impact: highest-leverage fixes first

OUTPUT FORMAT:
- Title tag: [current] → [rewritten]
- Meta description: [current] → [rewritten]
- H1: [current] → [rewritten or confirmed]
- Content assessment: 3–5 bullet points on what to add or restructure
- Quick wins: numbered list of 3 specific actions
- Root cause: one sentence — the main reason this page isn't ranking
- Response under 400 words

> Before you start: If any of my context is missing or unclear, ask me one specific question. Then audit section by section, in order. When done, tell me: (1) which fix is most urgent and why, and (2) the next prompt I should run to improve this page further.
```
*A professional SEO audit of one specific page — exact rewrites included, not vague recommendations.*

&nbsp;

**4. Title Tags & Meta Descriptions**

```
ROLE: You are an SEO copywriter who specialises in writing title tags and meta descriptions that achieve high click-through rates from Google search results. You treat every meta description like a paid ad — one shot to earn the click.

CONTEXT:
- Page topic: [what this page is about]
- Target keyword: [exact keyword phrase]
- Page type: [blog post / product page / landing page / guide / comparison]
- Unique value this page offers: [what makes your page worth clicking — your angle, data, or promise]
- Current title tag (if you have one): [paste or write "none"]
- Current click-through rate (if known): [%  or "unknown"]

TASK:
1. Write 5 title tag variations (max 60 characters each, keyword included, varied structure)
2. Write a matching meta description for each title (150–160 characters, keyword included, ends with a reason to click)
3. For each pair: give a one-line explanation of the CTR strategy behind it
4. Tell me which pair you recommend and the specific reason why — based on likely CTR, keyword placement, and search intent match

CONSTRAINTS:
- No two titles should start with the same word or use the same structure
- No clickbait — every description must accurately reflect the page content
- Do not start the meta description with the keyword itself — lead with the benefit or hook
- Keyword must appear in every title, but naturally — not forced

OUTPUT FORMAT:
- 5 numbered pairs, each formatted as:
  Title: [text] ([character count])
  Meta: [text] ([character count])
  Strategy: [one line]
- Recommendation: [pair number] — [2–3 sentences explaining why]

> Before you start: If my context is missing information that would affect the copy, ask me one question. Write each variation with a genuinely different angle — not just word swaps. When done, tell me: (1) how to test which title performs best, and (2) the next SEO action I should take after optimising this page's metadata.
```
*5 ready-to-use title and meta description pairs — the fastest way to improve your Google click-through rate without changing a word of your content.*

&nbsp;

**5. Google Search Console Analysis**

```
ROLE: You are a Google Search Console data analyst who helps small website owners understand what their performance data actually means — and translate it into a specific, prioritised action plan. You speak in plain English, not SEO jargon.

CONTEXT:
- My website: [brief description of what it does]
- Data I'm sharing: [paste your top 10–20 queries with impressions, clicks, CTR, and average position — or describe what you see: "5,000 impressions, 18 clicks, avg position 14"]
- Date range: [last 28 days / 3 months / 6 months]
- My main goal: [rank higher / get more clicks / understand what's happening / all three]
- Biggest frustration: [what confuses or concerns you most about the data]

TASK:
1. Explain what my overall data tells me in 2–3 plain sentences — no jargon
2. Identify my single biggest opportunity — the query or page closest to a breakthrough
3. Diagnose any high impressions / low clicks situations — what's likely wrong and how to fix it
4. Tell me which 3 pages or queries to focus on first, and why, in priority order
5. Give me a 3-step action plan based specifically on this data — not generic SEO advice

CONSTRAINTS:
- Explain every metric before telling me what to do about it
- Every recommendation must reference a specific query or number from my data — no generic advice
- Assume I am not an SEO expert and have never used Search Console before
- Do not recommend paid tools unless I specifically ask

OUTPUT FORMAT:
- Plain English summary: 2–3 sentences
- Biggest opportunity: [query/page] — [why it's the opportunity]
- CTR diagnosis (if applicable): [problem] → [fix]
- Priority list: 3 items, numbered, each with query/page + reason + one action
- 3-step action plan: numbered, each step under 40 words
- Response under 500 words

> Before you start: If my data is incomplete or ambiguous, ask me one clarifying question. Then analyse the data pattern before making recommendations. When done, tell me: (1) what to check again in 30 days to know if it worked, and (2) the best next prompt to run based on what you found.
```
*Turns confusing Search Console numbers into a clear action plan — so you know exactly what to fix and in what order.*

&nbsp;

**6. Internal Linking Plan**

```
ROLE: You are an internal linking strategist who understands that internal links are one of the most underused and highest-ROI SEO tactics available to small websites. You build linking structures that distribute authority efficiently and help every important page rank.

CONTEXT:
- My website pages (list as many as you have):
  [Page 1: title / topic — URL]
  [Page 2: title / topic — URL]
  [Page 3: title / topic — URL]
  [Add more as needed]
- My most important page (the one I most want to rank): [URL and target keyword]
- My second most important page (optional): [URL and keyword]
- Current internal linking (if known): [describe or paste "I have no structured linking"]

TASK:
1. Identify which existing pages should link to my most important page — and write the exact anchor text to use for each
2. Identify any pages that are likely orphaned (receiving no internal links) — list them and tell me how to fix each one
3. Describe the ideal hub-and-spoke linking structure for a site like mine
4. Write 5 actual sentences I can add to specific existing pages — each sentence naturally includes an internal link using keyword-rich anchor text. Write the full sentence, not a template.
5. Tell me what NOT to do — the most common internal linking mistakes that hurt rankings

CONSTRAINTS:
- All anchor text must be natural and keyword-relevant — never "click here" or "read more"
- Every suggested link must make sense to a human reader, not just an algorithm
- Do not suggest linking every page to every other page — be selective and strategic
- Prioritise links that pass authority to the pages that need it most

OUTPUT FORMAT:
- Link targets for main page: table with [source page] | [anchor text] | [where in content to add it]
- Orphaned pages: bulleted list with fix for each
- Hub-and-spoke structure: 3–5 sentence description with a simple text diagram
- 5 ready-to-use sentences with links: numbered, each on its own line
- Common mistakes: 3 bullet points
- Response under 600 words

> Before you start: If my page list is too vague to make specific recommendations, ask me one question. Map the linking structure before writing the sentences. When done, tell me: (1) which link will have the most immediate ranking impact, and (2) the next action I should take to build on this linking structure.
```
*A complete internal linking plan with ready-to-paste sentences — the highest-ROI SEO task most beginners never do.*

&nbsp;

**7. Competitor SEO Gap Analysis**

```
ROLE: You are a competitor SEO analyst who reverse-engineers ranking strategies and identifies the specific content gaps a new or growing site can exploit. You find opportunities, not just observations.

CONTEXT:
- My website: [URL or description of what it does]
- My target keyword: [the keyword I want to rank for]
- My current page for this keyword: [URL, or "I don't have one yet"]
- Competitors ranking above me:
  - [Competitor 1 URL]
  - [Competitor 2 URL]
  - [Competitor 3 URL — optional]
- My site's main advantage over competitors (if any): [speed, depth, niche focus, personal experience, etc. — or "I'm not sure yet"]

TASK:
1. Analyse what the ranking competitors are doing well — content depth, structure, authority signals, content format
2. Identify 3 specific gaps or weaknesses across all competitors that I could exploit
3. Recommend one content angle or format they are all missing that I could own
4. Tell me: how long, how detailed, and in what format does my content need to be to compete?
5. List the top 5 things my page must include that the competitors don't — to give Google a specific reason to rank mine higher

CONSTRAINTS:
- Focus only on actionable differentiation — what I can actually build, not what I'd need millions of backlinks for
- Every point must be specific to my niche and competitors — no generic SEO advice
- Be honest about difficulty: tell me which gaps are realistic and which are long-shots
- Do not recommend I compete on domain authority — focus on content quality and gap-filling

OUTPUT FORMAT:
- Competitor strengths: 3–5 bullet points (what they're doing right)
- Gaps I can exploit: numbered list of 3, each with: gap description + how to exploit it + estimated difficulty
- Missing angle: 1–2 sentences — the angle no one is covering
- Content spec: word count range, format, key sections to include
- Must-have list: 5 specific things my page needs that competitors lack
- Response under 500 words

> Before you start: If my competitor URLs or keyword are too vague for a specific analysis, ask me one question. Analyse the pattern across competitors before identifying gaps. When done, tell me: (1) which gap is most winnable in the next 60 days, and (2) the next prompt to run to turn this analysis into a content plan.
```
*Finds the specific content gaps in competitor pages you can exploit — so you build with a real ranking advantage from the start.*

&nbsp;

**8. SEO Blog Introduction Writer**

```
ROLE: You are an SEO content writer who specialises in writing blog introductions that both rank well on Google and make readers stay on the page. You understand that the first 150 words determine whether the reader continues — and whether Google considers the page high-quality.

CONTEXT:
- Article title: [your title]
- Target keyword: [the primary keyword this article targets]
- Reader profile: [who is reading this — their problem, what they have already tried, their experience level]
- What this article delivers: [the specific outcome or knowledge the reader will have after reading]
- Tone: [professional / conversational / authoritative / beginner-friendly]

TASK:
1. Write 3 versions of the blog post introduction (120–160 words each)
2. Each version must: include the keyword naturally in the first 2 sentences, hook the reader by addressing their problem directly, and preview the article's value clearly
3. Vary the opening style across versions: one starts with a question, one with a problem statement, one with a surprising fact or statistic
4. After the 3 versions, recommend which one is strongest — for both SEO performance and reader retention — and explain why in 2–3 sentences

CONSTRAINTS:
- No generic openers: "In today's digital world...", "Many people wonder...", "It goes without saying..."
- The keyword must appear naturally — never forced or repeated within the intro
- Every intro must make a clear implicit or explicit promise — what will the reader know by the end?
- Maximum 160 words per intro — tight writing only

OUTPUT FORMAT:
- Version 1 (Question hook): [intro text] — [word count]
- Version 2 (Problem statement hook): [intro text] — [word count]
- Version 3 (Fact/statistic hook): [intro text] — [word count]
- Recommendation: [which version + 2–3 sentence reasoning]

> Before you start: If my reader profile or article topic is too vague, ask me one specific question. Write each version as if you are the reader — would you keep reading? When done, tell me: (1) one addition that would make the strongest intro even better, and (2) the next section of the article I should ask you to write.
```
*3 ready-to-use blog introductions that hook readers and signal quality to Google — the first 150 words are the most important on any page.*

&nbsp;

**9. Local SEO Action Plan**

```
ROLE: You are a local SEO specialist who has helped hundreds of small businesses rank in Google Maps and appear in "near me" and "[service] in [city]" searches. You focus on practical, high-impact actions — not theory.

CONTEXT:
- Business name: [your business name]
- Business type: [what you do — e.g. "Italian restaurant", "personal trainer", "plumber", "accountant"]
- Location: [city, neighbourhood, and country]
- Target searches: [the specific phrases you want to appear for — e.g. "best pizza in Manchester" or "plumber near me in Brooklyn"]
- Google Business Profile status: [Do you have one? Is it verified? How complete is it? Any reviews?]
- Website: [URL, or "I don't have one"]
- Biggest local competitor: [a competitor that ranks above you, or "not sure"]

TASK:
1. List the 3 most impactful actions I should complete this week — in priority order
2. Audit my Google Business Profile: what specifically should I add, change, or optimise?
3. Write an optimised homepage title tag and meta description targeting my top local search phrase
4. Explain how Google reviews affect rankings and give me a script for asking customers for a review naturally
5. Explain what local citations are, which ones matter most for my business type, and name the top 5 I should be listed on

CONSTRAINTS:
- Assume I have 2–3 hours per week maximum — prioritise actions by impact per hour
- Explain every step as if I have never done SEO before
- Do not recommend expensive tools — free and low-cost solutions only unless I ask
- Every recommendation must be specific to my location and business type, not generic

OUTPUT FORMAT:
- This week's top 3 actions: numbered, each with: action + why it matters + estimated time
- GBP audit: bullet list of specific changes to make
- Title tag: [text] / Meta description: [text]
- Review strategy: 2–3 sentences on impact + the exact script
- Top 5 citations: table with [directory name] | [why it matters for your business type] | [how to submit]
- Response under 600 words

> Before you start: If my business type or location is too vague for specific recommendations, ask me one question. Prioritise by what moves the needle fastest for local rankings. When done, tell me: (1) the single action that will show results fastest, and (2) what I should check in 30 days to measure progress.
```
*A concrete local SEO plan for appearing in Google Maps and "near me" searches — the most important SEO channel for any local business.*

&nbsp;

**10. 6-Month SEO Roadmap from Zero**

```
ROLE: You are an SEO strategist who specialises in taking websites from zero organic traffic to their first meaningful rankings. You build realistic, compounding plans — not hype. You have done this for SaaS products, blogs, local businesses, and e-commerce stores.

CONTEXT:
- My website: [URL]
- What it does: [your product, service, or content topic — 1–2 sentences]
- My main goal: [specific target — e.g. "1,000 organic visitors/month", "rank for [keyword]", "generate 10 leads/month from Google"]
- Current status: [e.g. "just launched, zero traffic" / "3 months old, 50 visitors/month" / "have 8 blog posts but no rankings"]
- Resources: [time per week available + budget if any + whether I have a writer or do it myself]
- Biggest challenge: [what you think is holding you back, or "I don't know where to start"]

TASK:
1. Month 1–2: Technical and foundational setup — what to install, configure, and fix before publishing content
2. Month 2–4: Content strategy — how many pieces, which keyword types to target, what formats work best for a new site
3. Month 4–6: Authority building — how to earn backlinks as a small site with no existing connections or budget
4. Monthly metrics: what to track each month and what numbers indicate I'm on track vs. falling behind
5. The single biggest mistake new websites make with SEO — and the specific way I avoid it with my site

CONSTRAINTS:
- Be realistic: do not promise rankings or traffic numbers — describe what consistent effort typically produces
- Every recommendation must be appropriate for the current status I described — don't tell a day-1 site to focus on link building
- Prioritise actions that compound over time — not one-time fixes
- If my goal is unrealistic for 6 months, tell me honestly and adjust the target

OUTPUT FORMAT:
- Month 1–2: bullet list of 5–7 setup actions
- Month 2–4: content plan table — [week] | [content type] | [keyword target] | [goal]
- Month 4–6: 3 backlink strategies appropriate for my site, each with: tactic + realistic expectation + time cost
- Monthly metrics: table — [month] | [what to measure] | [on-track benchmark]
- Biggest mistake: 1 paragraph — what it is, why it happens, how I specifically avoid it
- Response under 700 words

> Before you start: If my current status or goal is too vague to build a specific plan, ask me one question. Build the plan month by month in sequence — each phase should set up the next one. When done, tell me: (1) which month will feel like "nothing is working" — and how to push through it, and (2) the first prompt I should run to begin executing month one.
```
*A full 6-month SEO roadmap from scratch — a specific, compounding sequence that builds momentum month by month.*

---

> **These prompts are built with the same structure used by professional prompt engineers.**
> If you want AI to build structured prompts like these automatically for any topic, try **[PromptIt](https://promptitin.com)** — free, no account needed.
