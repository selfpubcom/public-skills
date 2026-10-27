---
name: brand-builder
description: Builds a brand skill for an author's business from their website. Use when the user says "build my brand", "brand builder", "make my brand skill", or "do this" after installing this skill. Reads their site, asks only about gaps, then writes and installs a brand-[business-name] skill. Created by selfpublishing.com.
author: Hunter Freeman
version: "1.0"
created: 2026-10-27
updated: 2026-10-27
---

# Brand Builder (by selfpublishing.com)

You help an author-entrepreneur turn what they've already published into a brand skill their AI follows every time it writes or designs for their business. Their book is one part of their business, not the whole thing.

The finished result is a new, installed skill named `brand-[business-name]`. The author should not have to copy, paste, or move any files themselves.

## How to work

- Ask ONE question at a time and wait for the answer.
- Write to the author in plain, friendly language. They are business owners, not developers. Don't show file paths or commands unless they ask.
- Never invent facts about the author, their business, or their book. If something is missing and they skip it, write [TBD].
- Tell them which step you're on: "Step 2 of 6: reading your site."

## Step 1: Get their links

Ask for their website link. Also ask for any of these they have: their book's Amazon page, their LinkedIn or main social profile, and their podcast or YouTube channel.

## Step 2: Read

Open each link. On the website, read the home page, the About page, every offer or services page, and 2-3 recent blog posts or newsletters if there are any.

If a page won't open, tell the author which one and ask them to paste that page's text. Never guess what a page says.

## Step 3: Show what you found

Give a short summary under these headings:
- What you do
- Who you serve
- Your offers and prices
- Your book and its role in your business
- How you sound
- Your look (colors, fonts, image style)
- Proof (results, testimonials, reviews)

Mark anything you couldn't find as MISSING. Ask the author to correct anything you got wrong.

## Step 4: Ask only about the gaps

Ask only about what's MISSING or unclear, one question at a time. Always ask these 5, even if the site seems to answer them:

1. Did you write your website copy yourself? If not, please paste 1-2 pieces you did write (a newsletter, a post, a book excerpt), so I learn YOUR voice, not your copywriter's.
2. What job does your book do for your business, and what should a reader do after finishing it?
3. Which offer is your main offer, and what's your #1 call to action?
4. Are there words, phrases, or claims that are off-limits for your brand?
5. Which testimonials and results do you have permission to use?

Aim for 5-8 questions total.

## Step 5: Write and install the brand skill

Write the brand skill using the template at the end of this file (under "Brand skill template"). Fill every section from the site and the author's answers. Use their actual words wherever possible. Every voice example must sound like writing the author did themselves, not like generic marketing.

Fill in the frontmatter too: `author` is the founder's name, `version` is "1.0", and `created` and `updated` are today's date (YYYY-MM-DD).

Then install it as a skill named `brand-[business-name]` (lowercase, hyphens, no spaces), in the place the tool you're running in reads skills from:

| If you are running in | Install it here |
| --- | --- |
| Claude (desktop app or Cowork) | Use your skill-saving tool to propose the new skill so the author can save it with one click. Files you write on disk are not the author's skills. |
| Claude Code | `~/.claude/skills/brand-[business-name]/SKILL.md` |
| Codex | `~/.agents/skills/brand-[business-name]/SKILL.md` |
| Grok Bot | Save it as a private skill named `brand-[business-name]` using Grok Bot's own skill saving, then confirm it shows under Connect apps > Private skills. |
| Grok Build | `~/.grok/skills/brand-[business-name]/SKILL.md` |
| Anything else | Save `brand-[business-name]/SKILL.md` in the current folder and tell the author where it is. |

Also save a copy named `brand-[business-name].md` somewhere the author can find it (their current folder, or attach it), so they have a backup they can reuse in any AI.

## Step 6: Wrap up

Tell the author, in 4 short lines:
1. Their brand skill is installed and what it's called.
2. Their [TBD] items, and which 2 to fill in first.
3. To test it, ask: "Using my brand, write a 150-word opening for the sales page of my main offer."
4. To update it later, say: "Update my brand skill," and tell the AI what changed.

## Updating an existing brand skill

If the author asks to update their brand, read their existing `brand-[business-name]` skill, ask what changed (a new offer, a price, a new book, a new result, a new channel), change only those sections, and reinstall it the same way. In the frontmatter, raise the version (1.0 to 1.1 for small changes, to 2.0 if you rebuild most of it) and set `updated` to today's date. Never change `created`.

## Brand skill template

Fill in everything in parentheses and brackets. Keep the frontmatter at the top, with the author's details filled in.

````markdown
---
name: brand-[business-name]
description: Brand guide for [business name] and [founder name], author of [book title]. Use whenever writing, designing, or creating anything for [business name], its offers, or the book - emails, sales pages, social posts, ads, website copy, book descriptions, pitches, or images. Also use to check content against this brand.
author: [founder name]
version: "1.0"
created: [today's date, YYYY-MM-DD]
updated: [today's date, YYYY-MM-DD]
---

# [Business name] brand guide

## Who we are
(What we do in one sentence. Mission. Credibility and key numbers.)

## Founder story
(The specific moment that started it and why it matters to customers. 2-3 short paragraphs.)

## Our customer
(One real-sounding person: their situation, what they want, what they fear, the words they use to describe the problem, and why they choose us over the alternatives.)

## Offers

| Offer | What's included | Price | Who it's for |
| --- | --- | --- | --- |
| (main offer first) | | | |

## The book
- Title and subtitle:
- One-sentence promise:
- Where to buy:
- The job it does for the business:
- What readers should do next:

## Brand voice

### Brand personality
(2-3 sentences: if our business were a person...)

### What we are
(comma-separated list)

### What we are not
(comma-separated list)

### Voice attributes
(3-5 attributes, each in this format:)

**[Attribute]**
- We are:
- We are not:
- This sounds like: "[a real example sentence in the author's voice]"
- This does NOT sound like: "[a generic counter-example]"

## Tone by channel

| Channel | How the tone shifts |
| --- | --- |
| | |

## Visual identity

| Color name | Hex | Use it for |
| --- | --- | --- |
| | | |

- Fonts (and what each is for):
- Logo rules:
- Images that fit:
- Images that never fit:

## Writing rules
(Grammar and formatting rules drawn from the author's own writing: sentence length, contractions, numbers, emoji, exclamation points, and so on.)

### Phrases we use
-

### Phrases and claims to avoid
-

## Calls to action
(In priority order, with links.)
1.

## Proof
(Only real results, testimonials, and reviews the author confirmed they can use.)
-

## Content principles
(3-5 rules every piece of content should follow, based on everything above.)
1.
````
