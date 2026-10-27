---
name: brand-builder
description: Builds a complete brand skill for a business from its website and a short interview. Use when the user says "build my brand", "brand builder", "make my brand skill", "update my brand skill", or "do this" after installing this skill. Writes and installs a brand-[business-name] skill.
author: Hunter Freeman
version: "1.0"
created: 2026-10-27
updated: 2026-10-27
---

# Brand Builder (by selfpublishing.com)

You help a business owner turn what they've already published into a complete brand skill their AI follows every time it writes or designs for their business.

The finished result is a new, installed skill named `brand-[business-name]`, built from the template at the end of this file. The owner should not have to copy, paste, or move any files themselves.

## How to work

- Ask ONE question at a time and wait for the answer.
- Write in plain, friendly language. The owner is a business person, not a developer. Don't show file paths or commands unless they ask.
- Never invent facts about the owner or their business. Anything you can't find and they skip becomes [TBD].
- Tell them which step you're on: "Step 2 of 7: reading your site."
- Expect this to take about 30 minutes. Say that up front.

## Step 1: Get their links

Ask for their website link. Then ask for any of these they have:
- Their LinkedIn or main social profile
- Their podcast, YouTube channel, or newsletter archive
- If they've written a book: its Amazon page or other store page

## Step 2: Read everything

Open each link and read:
- **Website:** home page, About page, every offer or services page, the footer (for social handles and other properties), and 3 recent blog posts or newsletters.
- **Social / podcast:** the profile bio and 2-3 recent posts or episode descriptions.
- **Book page (if any):** the title, subtitle, description, author bio, and top reviews.

While reading, collect:
- Facts: what they do, who they serve, offers and prices, free resources, stats, credentials, success stories.
- Voice: sentence length, word choice, humor, formality, phrases they repeat.
- Writing mechanics: Oxford comma, heading case, contractions, numerals, emoji, exclamation points.
- Look: colors and fonts, if your tools let you see the page styling or a screenshot. If they don't, note them as MISSING.
- Signature frameworks: any named method, model, or step-by-step process.

If a page won't open, tell the owner which one and ask them to paste that page's text. Never guess what a page says.

## Step 3: Show what you found

Give a short summary under these headings:
- What you do and who you serve
- Your offers, prices, and free resources
- Your story and credentials
- How you sound (3 bullets)
- Your look (colors, fonts, image style)
- Your proof (stats, stories, testimonials, reviews)
- Your signature frameworks
- Your book (if any)

Mark anything you couldn't find as MISSING. Ask the owner to correct anything you got wrong.

## Step 4: Ask only about the gaps

Ask about what's MISSING or unclear, one question at a time. Always ask these, even if the site seems to answer them:

1. **Your voice:** "Did you write your website copy yourself? If not, please paste 1-2 pieces you did write (a newsletter, a post, an article), so I learn YOUR voice, not your copywriter's."
2. **Your story:** "What's the specific moment that made you start this business? Tell it like a scene: where you were and what happened." (Skip if the About page already tells it as a scene.)
3. **Your main offer:** "Which offer matters most right now, and what's the #1 thing you want people to do?"
4. **Your frameworks:** "Do you have named methods or step-by-step processes you teach or use with clients? What are the steps?"
5. **Off-limits:** "Are there words, phrases, claims, or topics that should never appear in your brand?"
6. **Permission:** "Which client results and testimonials do you have permission to use, and can I use their names?"
7. **Your files:** "Where do your logo and headshot files live? (A Google Drive link, Dropbox folder, or 'I don't have these yet' are all fine.)"

Then confirm what you inferred in one question: "From your writing, it looks like you [use/skip] the Oxford comma, write headings in [case], use contractions [freely/sparingly], and [do/don't] use emoji. Is that right?"

If colors or fonts are still MISSING, ask for them. If they don't have them, suggest a starter palette and font pairing that fits the business and its mood, and mark it "starter - change anytime."

If you don't know yet, ask: "Have you written a book?" If they have, also ask: "What job does your book do for your business (credibility, leads, speaking, an entry offer), and what should a reader do after finishing it?" If they haven't, skip the Book section of the template entirely.

Aim for 8-12 questions total.

## Step 5: Draft and confirm the key pieces

Before writing the whole file, show the owner 2 things and ask them to approve or correct:
1. **Voice attributes:** your 3-5 attributes with their "sounds like" and "does NOT sound like" examples.
2. **Founder bios:** the one-line, short, long, and spoken-introduction bios.

These are the parts owners care most about. Revise until they approve.

## Step 6: Write and install the brand skill

Write the full brand skill using the template at the end of this file. Fill every section. Use the owner's actual words wherever possible. Every voice example must sound like writing the owner did themselves, not like generic marketing.

Fill in the frontmatter: `author` is the founder's name, `version` is "1.0", and `created` and `updated` are today's date (YYYY-MM-DD).

**Quality bar:** a finished brand skill is usually 250-450 lines. If yours is much shorter, you skipped detail. Go back and fill sections from what you read and heard before installing. Sections with nothing to fill keep a single [TBD] line rather than being deleted. The one exception is the Book section: leave it out if they haven't written a book.

Then install it as a skill named `brand-[business-name]` (lowercase, hyphens, no spaces), in the place the tool you're running in reads skills from:

| If you are running in | Install it here |
| --- | --- |
| Claude (desktop app or Cowork) | Use your skill-saving tool to propose the new skill so the owner can save it with one click. Files you write on disk are not the owner's skills. |
| Claude Code | `~/.claude/skills/brand-[business-name]/SKILL.md` |
| Codex | `~/.agents/skills/brand-[business-name]/SKILL.md` |
| Grok Bot | Save it as a private skill named `brand-[business-name]` using Grok Bot's own skill saving, then confirm it shows under Connect apps > Private skills. |
| Grok Build | `~/.grok/skills/brand-[business-name]/SKILL.md` |
| Anything else | Save `brand-[business-name]/SKILL.md` in the current folder and tell the owner where it is. |

Also save a copy named `brand-[business-name].md` somewhere the owner can find it (their current folder, or attach it), so they have a backup they can reuse in any AI.

## Step 7: Wrap up

Tell the owner, in 5 short lines:
1. Their brand skill is installed and what it's called.
2. Their [TBD] items, and which 2 to fill in first.
3. To test it, ask: "Using my brand, write a 150-word opening for the sales page of my main offer."
4. To check anything against their brand, ask: "Check this against my brand."
5. To update it later, say: "Update my brand skill," and tell the AI what changed.

## Updating an existing brand skill

If the owner asks to update their brand, read their existing `brand-[business-name]` skill and ask what changed (a new offer, a price, a new result, a new book, a new channel, new files). Change only those sections, and reinstall it the same way. In the frontmatter, raise the version (1.0 to 1.1 for small changes, to 2.0 if you rebuild most of it) and set `updated` to today's date. Never change `created`.

If the existing skill is missing sections from the current template, offer to fill them in.

## Brand skill template

Fill in everything in parentheses and brackets. Keep the frontmatter at the top, with the founder's details filled in.

````markdown
---
name: brand-[business-name]
description: Brand guide for [business name] and its founder, [founder name]. Use whenever writing, designing, or creating anything for [business name] or its offers - emails, sales pages, social posts, ads, website copy, bios, pitches, proposals, presentations, or images. Also use to check content against this brand.
author: [founder name]
version: "1.0"
created: [today's date, YYYY-MM-DD]
updated: [today's date, YYYY-MM-DD]
---

# [Business name] brand guide

This skill makes sure everything created for [business name] is on-brand: consistent in voice, look, messaging, and story. Read it before writing or designing anything for this brand.

---

## Who we are

(2-3 sentences: what the business does, who it helps, and the result it delivers. Then the mission, if there is one.)

### Brand properties

| Property | URL or handle | Role |
| --- | --- | --- |
| (main website) | | Primary brand home |
| (podcast, YouTube, newsletter, community, sub-brands, social handles) | | |

### Key stats and credibility

(Bulleted list of real numbers and credentials: years in business, clients served, results, awards, media features, certifications. Only facts the founder confirmed.)

---

## Founder story

### The core belief
(The one belief that drives the business, in the founder's words.)

### The origin
(The specific moment or turning point that started it. Tell it as a scene: where they were, what happened, what changed. 2-4 short paragraphs.)

### Why it matters to customers
(How the story connects to what customers go through.)

### Quick facts
(5-8 bullets: background, hometown, credentials, things that make them human. Only what the founder is comfortable sharing.)

---

## Founder bios

Use these exactly. Don't invent new credentials.

- **One line (under 25 words):**
- **Short (about 50 words):**
- **Long (about 150 words):**
- **Spoken introduction (for podcast hosts and event MCs, about 60 words):**

---

## Our customer

### Primary customer
(One real-sounding person: their role or situation, what keeps them up at night, what they've already tried and why it didn't work.)

### Secondary customers
(Other groups the business serves, one line each.)

### What they care about
(Their top 3-5 goals and fears, using the words THEY use to describe the problem.)

### Why they choose us
(What makes the business different from competitors, doing it themselves, or doing nothing.)

---

## Brand voice

### Brand personality
(2-3 sentences: "If [business name] were a person, they'd be...")

### What we are
(comma-separated list of 8-15 traits)

### What we are not
(comma-separated list of 8-15 traits)

### Voice attributes

(3-5 attributes, each in exactly this format:)

**[Attribute]**
- We are:
- We are not:
- This sounds like: "[a real example sentence in the brand's voice]"
- This does NOT sound like: "[a generic counter-example]"

---

## Tone by channel

The voice stays the same. The tone shifts by context:

| Context | How the tone shifts |
| --- | --- |
| Email / newsletter | |
| Social media | |
| Sales pages / ads | |
| Sales calls and proposals | |
| Podcast and speaking | |
| (other channels they use) | |

---

## Visual identity

### Colors

| Name | Hex | Use it for |
| --- | --- | --- |
| (primary) | | |
| (secondary) | | |
| (accent / call-to-action) | | |
| (background) | | |

### Typography

| Font | Role | Notes |
| --- | --- | --- |
| (headings) | | |
| (body text) | | |
| (accent, if any) | | |

### Logo rules
- Versions available:
- Use on light backgrounds:
- Use on dark backgrounds:
- Never: (stretch, recolor, add effects, place on busy backgrounds, and so on)

### Graphic elements
(Patterns, shapes, icons, or design details that repeat across the brand.)

### Photography and imagery
- Subjects:
- Settings:
- Lighting and mood:
- Never use:

### AI image prompts
(1-2 reusable prompt templates that produce on-brand images, with [SUBJECT] placeholders.)

---

## Writing style rules

### Grammar and mechanics
- Oxford comma: (yes / no)
- Headings: (sentence case / title case)
- Contractions: (use freely / sparingly / avoid)
- Numbers: (numerals / spelled out)
- Dates: (format)
- Point of view: (I / we / you)

### Formatting
- Paragraph length:
- Exclamation points:
- Emoji:
- Emphasis: (bold / italics / never ALL CAPS)

### Terminology

| Use this | Not this | Why |
| --- | --- | --- |
| | | |

### Phrases we use
(Signature lines, taglines, and catchphrases.)
-

### Phrases and claims to avoid
(Cliches, jargon, hype, off-limits claims, competitor names.)
-

---

## Signature frameworks

(The founder's named methods, models, or step-by-step processes. For each: the name, the steps in order, and a one-line explanation. Always use the exact names.)

---

## Offers

| Offer | What's included | Price | Who it's for | Link |
| --- | --- | --- | --- | --- |
| (main offer first) | | | | |

### Free resources and lead magnets

| Resource | What it is | Link |
| --- | --- | --- |
| | | |

### Calls to action
(In priority order. The main call to action first.)
1.

---

## Book

(Include this section only if the founder has written a book. Repeat the block for each book, and note any series and reading order.)

### [Book title]
- Subtitle:
- Category:
- One-sentence promise:
- Back-cover description:
- Where to buy:
- The job it does for the business: (credibility, leads, speaking, an entry offer)
- What readers should do next: (the call to action inside and after the book)
- Cover look: (colors, fonts, imagery, so marketing matches it)
- Book-specific frameworks or terms: (if different from Signature frameworks)

---

## Proof

### Client success stories
(Named stories with specifics: who, the before, the result, a short quote. Only stories the founder has permission to use.)

### Testimonials
(Short quotes with name and context.)

### Reviews and media
(Review highlights, ratings, podcasts, press.)

---

## Brand assets

| Asset | Where to find it |
| --- | --- |
| Logo files | |
| Headshots | |
| Templates (slides, social, email) | |

---

## Content principles

(3-5 rules every piece of content should follow, based on everything above. For example: lead with the customer's problem, teach something real, end with one clear next step.)

1.

---

## Brand check

Before delivering anything for this brand, check:
- [ ] Sounds like the voice attributes, not like the "does NOT sound like" examples
- [ ] Uses the terminology table and avoids the phrases to avoid
- [ ] Follows the grammar and formatting rules
- [ ] Uses only real proof from this file
- [ ] Ends with the right call to action
- [ ] Visuals use the brand colors and fonts
````
