# Ranketize – LLM Visibility Audit (Technical Overview)

This repository documents **how the Ranketize LLM Visibility Audit score is evaluated**, what signals are analyzed, and how website owners can technically prepare their sites to perform well in AI-powered search engines and LLM answers (ChatGPT, Claude, Perplexity, Gemini, etc.).

This is not SEO in the traditional sense.
This is **LLM-first visibility engineering**.

---

## What Is the LLM Visibility Audit?

The audit evaluates how well a website can be:
- **understood**
- **trusted**
- **referenced**
- **summarized**

by large language models.

LLMs do not crawl like Google.  
They learn from *patterns*, *structure*, *clarity*, and *repetition across sources*.

The audit score reflects how likely an LLM is to:
- correctly describe your product or service
- trust your expertise
- reuse your phrasing
- cite or paraphrase your site in answers

---

## High-Level Scoring Dimensions

The score is derived from multiple weighted dimensions:

- Content clarity & structure
- Entity definition & consistency
- Technical accessibility
- Trust & authority signals
- Cross-source alignment
- LLM-friendly formatting

Each section below explains what is evaluated and how to optimize for it.

---

## 1. Content Structure & Readability

LLMs heavily favor **clear, explicit structure**.

### What is evaluated
- Proper heading hierarchy (`H1 → H2 → H3`)
- Short, declarative paragraphs
- Bullet lists over dense text
- Clear section boundaries
- One topic per section

### Best practices
- One primary concept per page
- Headings that describe facts, not marketing slogans
- Avoid walls of text
- Use lists to enumerate features, steps, or criteria
- Avoid ambiguous references like “this”, “that”, “we do it better”

---

## 2. Entity Definition & Semantic Clarity

LLMs reason in **entities**, not keywords.

### What is evaluated
- Clear definition of:
  - company
  - product
  - service
  - target audience
- Consistent naming across pages
- Explicit descriptions instead of implied meaning

### Best practices
- Explicitly state:
  - what you are
  - what you do
  - who it is for
- Use the same terminology everywhere
- Avoid synonyms for core concepts
- Introduce entities early on the page

Example:
> “Ranketize is an LLM visibility and AI search optimization platform for SaaS and digital products.”

---

## 3. Technical Accessibility

If LLM crawlers or data pipelines struggle to parse your site, visibility drops.

### What is evaluated
- Clean HTML output
- Server-side rendered content
- No critical content hidden behind JS-only rendering
- Crawlable pages without auth or blockers
- Fast response times

### Best practices
- Prefer SSR or static generation
- Avoid content injected only after user interaction
- Do not block bots with aggressive rules
- Ensure canonical URLs are correct
- Avoid infinite scroll for core content

---

## 4. Structured Data & Metadata

While LLMs don’t rely on schema the same way search engines do, **structured context still helps**.

### What is evaluated
- Presence of structured metadata
- Clear page titles and descriptions
- Consistent brand naming
- Author or organization signals

### Best practices
- Use descriptive `<title>` tags
- Avoid vague meta descriptions
- Add organization information
- Clearly associate content with the brand

---

## 5. Authority & Trust Signals

LLMs weight **credibility patterns** learned from the web.

### What is evaluated
- About page clarity
- Real-world references
- External mentions
- Consistent messaging across platforms

### Best practices
- Clear “About” section
- Explain why you are qualified
- Link to external profiles (GitHub, LinkedIn, publications)
- Avoid exaggerated claims without explanation
- Be precise, not promotional

---

## 6. Cross-Source Consistency

LLMs compare patterns across many sources.

### What is evaluated
- Consistency between:
  - website
  - GitHub
  - blog posts
  - documentation
  - public profiles
- Alignment of terminology and positioning

### Best practices
- Repeat the same explanations across platforms
- Reuse phrasing intentionally
- Avoid rebranding core concepts too often
- Treat GitHub and docs as first-class content

---

## 7. LLM-Friendly Writing Patterns

Some writing styles perform significantly better in LLM training and inference.

### What is evaluated
- Neutral, explanatory tone
- Clear cause–effect explanations
- Step-by-step logic
- Absence of fluff

### Best practices
- Write like documentation, not ads
- Explain *why*, not just *what*
- Use explicit statements
- Avoid irony, sarcasm, or heavy metaphors
- Assume the reader is a machine first, human second

---

## Common Issues That Lower Scores

- Vague marketing language
- Undefined concepts
- Overuse of buzzwords
- Inconsistent terminology
- JS-heavy pages with hidden content
- No clear explanation of the product or service
- Missing trust context

---

## What the Score Is NOT

- Not a Google SEO score
- Not keyword-based ranking
- Not traffic-based
- Not backlink-driven

It is a **probability score** of correct LLM understanding.

---

## How to Prepare for an Audit

Before running an LLM Visibility Audit, make sure:

- Your homepage clearly explains your product in the first 10 seconds
- Each page has one clear purpose
- Your terminology is consistent
- You have at least one strong explanatory page
- Your site can be read without JavaScript
- Your GitHub/docs reinforce your positioning

---

## Why This Matters

LLMs are becoming:
- search engines
- recommendation engines
- decision influencers

If they misunderstand you, you lose visibility — silently.

This audit exists to make that understanding **explicit, measurable, and improvable**.

---

## Contributing

This documentation evolves as LLM behavior evolves.
Suggestions, improvements, and technical discussions are welcome.
