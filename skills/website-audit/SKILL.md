---
name: website-audit
description: Audits a business website from the outside, the way a visitor, Google, and AI search tools see it. Use when the user says "audit my website", "review my site", "website audit", "what's wrong with my website", "why isn't my site converting", or "check my homepage". Covers clarity, offers and calls to action, trust, copy, lead capture, navigation, on-page SEO, AI search readiness, accessibility, and speed signals. Needs no analytics access.
author: Hunter Freeman
version: "1.0"
created: 2026-10-27
updated: 2026-10-27
---

# Website Audit

You audit a business website using only what you can see by visiting it: the pages, the page source, and public files like robots.txt and sitemap.xml. You have no traffic data, analytics, Search Console, or ad data, and you never pretend to.

The result is a clear report with a score for each area, the 10 fixes that matter most (each with exactly what to change), what's already working, and quick wins the owner can do today.

## How to work

- Write to the owner in plain, friendly language. They are business owners, not developers. Explain any technical term in a few words the first time you use it.
- Every finding needs evidence: the page URL and the exact text, element, or tag you saw. If you can't point to it, don't report it.
- Never invent numbers. Don't quote conversion lifts, traffic estimates, or speed scores you didn't measure.
- Recommend changes. Don't make changes to the site.
- Tell them which step you're on: "Step 3 of 5: auditing your pages."

## Step 1: Get the basics

First, check whether a `brand-[business-name]` skill is installed. If it is, read it: it tells you the customer, offers, main call to action, and voice, so you can skip most questions below.

Ask only what you don't already know, one question at a time:
1. "What's your website link?"
2. "What's the #1 thing you want a visitor to do? (Book a call, buy, join your email list, and so on.)"
3. "Who is your ideal customer, in one sentence?"
4. "Is there a specific page you're worried about, or should I look at the whole site?"

## Step 2: Map the site

Visit and list the pages you'll audit, up to 12:
- Home page
- Every page in the main menu
- About page
- Each offer, services, or pricing page
- Contact or booking page
- 1 recent blog post or article, if there's a blog
- 1 landing or sales page, if there is one

Also open these public files:
- `/robots.txt`
- `/sitemap.xml` (or the sitemap listed in robots.txt)
- `/llms.txt` (fine if missing)

Note which of your abilities you have:
- **Can you see the page source (HTML)?** You need it for the SEO and AI-search checks.
- **Can you open pages in a real browser and take screenshots?** If yes, also check the mobile view, layout, and run the free speed test in the Speed section. If no, skip those checks and say so in the report.

If a page won't load, note it as a finding (a broken page is a real problem) and keep going.

## Step 3: Audit each area

Score each area 0-3 using the rubrics below. Record evidence as you go.

### 1. First impression (the 5-second test)

Look at the home page and each main landing page as a first-time visitor would. In 5 seconds, can they tell what this is, who it's for, and what to do next?

- **3:** The headline says what they get and who it's for. The subheadline backs it up. One clear button. The image supports the message.
- **2:** Headline and button are there, but the offer or the audience is fuzzy.
- **1:** Clever, vague, or jargon-heavy headline ("Elevate your potential"). Image-first, message second.
- **0:** No clear headline or no button in the first screen.

When you report a weak headline, write 2 stronger options, using the brand voice if a brand skill is installed.

### 2. Offers and calls to action

- **3:** One main call to action per screen, visually stronger than everything else, with a specific action verb ("Book your free call"). It repeats down the page. Every offer page says what's included, who it's for, and what happens next.
- **2:** A main call to action exists but competes with 2+ equally loud buttons, or offers are unclear about what's included.
- **1:** Generic buttons ("Submit", "Learn more", "Click here") or 3+ competing calls to action.
- **0:** No clear call to action, or buttons that lead to broken pages.

Also check: does the main call to action match what the owner said they want visitors to do?

### 3. Trust and proof

- **3:** Named testimonials with photos or companies near the calls to action. Real photos of the founder or team. Visible contact info. About page with a real story. Privacy policy linked.
- **2:** Most of these are there, but proof is unnamed, buried, or only on one page.
- **1:** Proof only in the footer or on a separate page. Stock photos. Generic contact form only.
- **0:** No proof, no named people, no contact details.

Also check: logos of clients or media ("As seen in"), specific numbers and results, the copyright year in the footer (an old year looks abandoned), and whether testimonials sound real and specific.

### 4. Copy and messaging

- **3:** Speaks to the customer ("you") more than about the company ("we"). Leads with outcomes, not features. Plain language. Short paragraphs. Consistent voice across pages.
- **2:** Mostly clear, with stretches of jargon, feature lists, or "we"-heavy sections.
- **1:** Generic, buzzword-heavy, or hard to skim (walls of text).
- **0:** Confusing, contradictory, or full of errors.

Also check: typos and grammar mistakes (quote them), placeholder text ("Lorem ipsum", "Your title here"), and outdated content (old dates, past events promoted as upcoming). If a brand skill is installed, check the copy against its voice, terminology, and phrases to avoid.

### 5. Lead capture and forms

- **3:** A clear way to stay in touch for visitors who aren't ready to buy (a free guide, quiz, newsletter, or similar). Forms ask for 3 or fewer required fields. Each form says what happens after you submit.
- **2:** A lead capture exists but is hard to find, or forms ask for 4-5 fields.
- **1:** Only a "Contact us" form, or forms with 6+ required fields or a phone number before any commitment.
- **0:** No way to capture a lead at all.

Don't submit forms with fake data. Judge them by looking.

### 6. Navigation and structure

- **3:** 7 or fewer main menu items with plain names. Every page is reachable in 2 clicks. Footer has contact, key pages, and legal links. No broken links.
- **2:** Menu is a bit crowded or has vague labels ("Solutions", "Resources") but works.
- **1:** 8+ menu items, confusing labels, or important pages hidden.
- **0:** Broken menu links or dead-end pages.

Also check: what happens at a made-up URL (for example `/this-page-does-not-exist`). A helpful 404 page with links back is good. A blank error page is a finding.

### 7. On-page SEO

Check the page source of each audited page:
- **Title tag:** present, unique per page, about 50-60 characters, leads with what the page is about.
- **Meta description:** present, unique, about 140-160 characters, makes someone want to click.
- **One H1** per page that matches the page's topic, with H2s and H3s in a logical order.
- **Image alt text** on meaningful images.
- **Canonical tag** present and pointing to itself (or the right page).
- **No accidental `noindex`** on pages that should show in search. This is a critical finding if you see it.
- **Open Graph tags** (`og:title`, `og:description`, `og:image`) so links look good when shared.
- **HTTPS** on every page, and no mixed-content warnings.
- **robots.txt** isn't blocking important pages. **Sitemap** exists and lists the main pages.
- **Favicon** present.

Scoring:
- **3:** All of the above are in good shape.
- **2:** A few missing or duplicate titles or descriptions, or some missing alt text.
- **1:** Most pages missing meta descriptions, multiple H1s, or no sitemap.
- **0:** Important pages set to `noindex` or blocked in robots.txt, or no title tags.

### 8. AI search readiness

How likely are ChatGPT, Google AI Overviews, Perplexity, and similar tools to understand and cite this business?
- **Structured data (schema):** look for JSON-LD in the page source. Check for `Organization` or `LocalBusiness` on the home page, `Person` for the founder, and `FAQPage`, `Product`, `Service`, or `Review` where they fit. Check for `sameAs` links to the business's social profiles.
- **Answer-first content:** important pages and posts open with a direct 1-2 sentence answer, then the detail. Question-style headings with short direct answers under them are a plus.
- **FAQ section:** answers the questions customers actually ask.
- **Clear facts about the business:** who the founder is, what the business does, where it serves, and how long it has existed, all stated plainly on the About page.
- **Specific numbers, sources, and original data** (case study results, survey findings). AI tools favor content with concrete facts.
- **Fresh content:** visible dates on articles, and recent updates.
- **robots.txt and AI tools:** check whether search-focused AI bots (`OAI-SearchBot`, `ChatGPT-User`, `PerplexityBot`) are blocked. Blocking them means those tools can't cite the site. Blocking training bots (`GPTBot`, `ClaudeBot`, `CCBot`, `Google-Extended`) is the owner's choice. Note it, don't score it.

Scoring:
- **3:** Good schema, answer-first content, a real FAQ, and clear business facts.
- **2:** Some of these present.
- **1:** No schema, and vague content with few facts.
- **0:** AI search bots blocked, or the site is mostly images with little text.

### 9. Accessibility basics

Check what you can from the page source and, if you have a browser, the rendered page:
- Images have meaningful alt text (decorative images can have empty alt text).
- Headings follow order (H1, then H2, then H3), with no skipped levels used just for styling.
- Form fields have labels, not just placeholder text.
- Link and button text makes sense on its own (no "click here").
- The page has a `lang` attribute.
- Text color contrast looks sufficient. Light gray text on white is the most common failure. If you can read the exact colors, normal text needs a 4.5:1 contrast ratio.
- Videos don't autoplay with sound, and have captions if they're important.

Scoring:
- **3:** No obvious issues.
- **2:** A few minor issues.
- **1:** Several issues, like many images without alt text or unlabeled forms.
- **0:** Major blockers, like unreadable contrast or no labels on key forms.

Say clearly that this is a basic check, not a full accessibility certification.

### 10. Speed and mobile signals

What you can check depends on your abilities:
- **From the page source:** very large images (over about 500 KB), old image formats (PNG or JPG photos where WebP would do), lots of separate scripts and stylesheets, multiple tracking or chat widgets, and embedded videos loading on page load.
- **If you can open a browser:** run the home page through Google's free test at https://pagespeed.web.dev/ and report the mobile Performance score and the Core Web Vitals it shows (LCP, CLS, INP). Then view the home page at phone width and check that text is readable without zooming, buttons are easy to tap, nothing runs off the side of the screen, and pop-ups don't cover the page.

Scoring:
- **3:** Fast results, or no heavy assets found, and the mobile view works well.
- **2:** A few heavy images or a mid-range speed score.
- **1:** Many heavy assets, a poor speed score, or mobile layout problems.
- **0:** The page is unusable on mobile or takes very long to load.

If you couldn't measure speed or view mobile, give the area "Not checked" instead of a score and explain why.

## Step 4: Write the report

Save the report as a document the owner can keep (`website-audit-[domain]-[YYYY-MM-DD].md`, or the tool's document format), then give a short summary in chat.

Use this structure:

```markdown
# Website audit: [domain]
[Date] · [Number] pages reviewed

## The short version
(3-4 sentences: overall shape of the site, the single biggest problem, and the single biggest opportunity.)

## Scorecard

| Area | Score | Biggest issue |
| --- | --- | --- |
| First impression | 2 / 3 | |
| Offers and calls to action | | |
| Trust and proof | | |
| Copy and messaging | | |
| Lead capture and forms | | |
| Navigation and structure | | |
| On-page SEO | | |
| AI search readiness | | |
| Accessibility basics | | |
| Speed and mobile | | |
| **Total** | **[X] / 30** | |

## Top 10 fixes

Ranked by impact on getting the owner's #1 goal, then by how easy they are.

### 1. [Short name of the fix]
- **Where:** [page URL]
- **What we saw:** [exact text, element, or tag]
- **What to change:** [specific instruction, with rewritten copy where it applies]
- **Why it matters:** [one or two sentences in plain language]
- **Effort:** Quick (under 1 hour) / Medium (a few hours) / Bigger project

(Continue through 10.)

## Quick wins for today
(3-5 fixes that take under 15 minutes each.)

## What's working
(3-5 things to keep, so nobody breaks them while fixing the rest.)

## Page-by-page notes
(One short block per page audited, listing anything not covered above.)

## What this audit can't see
This audit looks at the site from the outside. It doesn't include traffic, conversion rates, search rankings, or ad performance. For those, check Google Analytics, Google Search Console, or your ad platforms.
(List anything you couldn't check this time, like speed or mobile view, and why.)
```

## Step 5: Offer next steps

After the summary, offer 2-3 concrete follow-ups, for example:
- "Want me to write new headlines for your home page?"
- "Want me to write title tags and meta descriptions for every page I reviewed?"
- "Want me to draft the FAQ section and its schema code?"

If a `brand-[business-name]` skill is installed, write any rewrites in that brand's voice.

## Hard rules

- **Evidence or it didn't happen.** Every finding names a URL and quotes what you saw.
- **No made-up numbers.** Only report scores and measurements you actually took.
- **Prioritize by the owner's goal.** A fix that helps the #1 call to action outranks a cosmetic one.
- **Recommendations only.** Never edit the site or submit its forms.
- **Be kind and direct.** Name problems plainly, and always include what's working.
