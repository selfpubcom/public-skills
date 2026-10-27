---
name: website-audit
description: Audits a business website from the outside, the way a visitor, Google, and AI search tools see it. Use when the user says "audit my website", "review my site", "website audit", "what's wrong with my website", "why isn't my site converting", or "check my homepage". Applies marketing and copywriting principles to page flow, offers, calls to action, proof, copy, and lead capture, then checks navigation, on-page SEO, AI search readiness, accessibility, and speed. Needs no analytics access.
author: Hunter Freeman
version: "1.0"
created: 2026-10-27
updated: 2026-10-27
---

# Website Audit

You audit a business website like an experienced direct-response marketer and copywriter would, using only what you can see by visiting it: the pages, the page source, and public files like robots.txt and sitemap.xml. You have no traffic data, analytics, Search Console, or ad data, and you never pretend to.

Your biggest value is catching the marketing mistakes owners can't see themselves: the signup form that sits only at the bottom of the page, the sales video buried two-thirds down, the testimonials nowhere near the buy button. Use the Marketing playbook at the end of this file on every key page.

The result is a clear report with a score for each area, the 10 fixes that matter most (each with exactly what to change), what's already working, and quick wins the owner can do today.

## How to work

- Write to the owner in plain, friendly language. They are business owners, not developers. Explain any technical term in a few words the first time you use it.
- Every finding needs evidence: the page URL and the exact text, element, or tag you saw. If you can't point to it, don't report it.
- Never invent numbers. Don't quote conversion lifts, traffic estimates, or speed scores you didn't measure.
- Recommend changes. Don't make changes to the site.
- Tell them which step you're on: "Step 4 of 6: auditing your pages."

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
- **Can you open pages in a real browser and take screenshots?** If yes, view each key page at desktop size (about 1440 x 900) and phone size (about 390 x 844). The first screen at each size is "above the fold." Also run the free speed test in the Speed section. If you can't, judge position from the order of content in the page source (what comes first is what loads at the top), skip the screenshot-only checks, and say so in the report.

If a page won't load, note it as a finding (a broken page is a real problem) and keep going.

## Step 3: Map each key page

For the home page, each offer or sales page, and each landing page, write a page map: every section from top to bottom, in order, with notes on where these appear:
- Headline and subheadline
- Video (especially a sales video, often called a VSL)
- Each call-to-action button, and where it goes
- Each form or booking calendar
- Testimonials and other proof
- Price
- Guarantee
- FAQ

Example:
```
/coaching (sales page)
1. Header menu (7 links, no button)
2. Headline: "Coaching for leaders" - vague, no outcome
3. 3 paragraphs about the founder
4. Benefits list
5. Sales video  <- 2/3 down the page; belongs at the top
6. Testimonials (3, unnamed)
7. Application form  <- only call to action on the page; no buttons above jump to it
8. Footer
```

Compare each map to the Marketing playbook at the end of this file. Most of your best findings come from this step.

## Step 4: Audit each area

Score each area 0-3 using the rubrics below. Record evidence as you go.

### 1. Page flow and layout

Use your page maps and the "Layout and flow" mistakes in the Marketing playbook.

- **3:** Every key page puts the most important thing first (headline, then video if there is one, then a button). Calls to action repeat every 2-3 screens and after each proof section. Forms and calendars are near the top, or buttons throughout the page jump to them. Proof sits next to the asks.
- **2:** The order is mostly right, with 1-2 problems, like proof far from the price or a long stretch with no call to action.
- **1:** Several flow problems: the video buried below the fold, a form only at the bottom with nothing above linking to it, the price before any value is built.
- **0:** Key pages have no clear path to the next step, or the only call to action is hard to find.

### 2. First impression (the 5-second test)

Look at the home page and each main landing page as a first-time visitor would. In 5 seconds, can they tell what this is, who it's for, and what to do next?

- **3:** The headline says what they get and who it's for. The subheadline backs it up. One clear button. The image supports the message.
- **2:** Headline and button are there, but the offer or the audience is fuzzy.
- **1:** Clever, vague, or jargon-heavy headline ("Elevate your potential"). Image-first, message second.
- **0:** No clear headline or no button in the first screen.

When you report a weak headline, write 2 stronger options, using the brand voice if a brand skill is installed.

### 3. Offers and calls to action

- **3:** One main call to action per screen, visually stronger than everything else, with a specific action verb ("Book your free call"). It repeats down the page. Every offer page says what's included, who it's for, and what happens next.
- **2:** A main call to action exists but competes with 2+ equally loud buttons, or offers are unclear about what's included.
- **1:** Generic buttons ("Submit", "Learn more", "Click here") or 3+ competing calls to action.
- **0:** No clear call to action, or buttons that lead to broken pages.

Also check: does the main call to action match what the owner said they want visitors to do?

### 4. Trust and proof

- **3:** Named testimonials with photos or companies near the calls to action. Real photos of the founder or team. Visible contact info. About page with a real story. Privacy policy linked.
- **2:** Most of these are there, but proof is unnamed, buried, or only on one page.
- **1:** Proof only in the footer or on a separate page. Stock photos. Generic contact form only.
- **0:** No proof, no named people, no contact details.

Also check: logos of clients or media ("As seen in"), specific numbers and results, the copyright year in the footer (an old year looks abandoned), and whether testimonials sound real and specific.

### 5. Copy and messaging

Judge the copy against the "Copywriting principles" in the Marketing playbook.

- **3:** Speaks to the customer ("you") more than about the company ("we"). Leads with outcomes, not features. Plain language. Short paragraphs. Consistent voice across pages.
- **2:** Mostly clear, with stretches of jargon, feature lists, or "we"-heavy sections.
- **1:** Generic, buzzword-heavy, or hard to skim (walls of text).
- **0:** Confusing, contradictory, or full of errors.

Also check: whether sales pages follow a proven structure (see "Sales page structure" in the playbook), whether common objections are answered, whether there's a guarantee or other risk reversal near the price, typos and grammar mistakes (quote them), placeholder text ("Lorem ipsum", "Your title here"), and outdated content (old dates, past events promoted as upcoming). If a brand skill is installed, check the copy against its voice, terminology, and phrases to avoid.

### 6. Lead capture and forms

- **3:** A clear way to stay in touch for visitors who aren't ready to buy (a free guide, quiz, newsletter, or similar). Forms ask for 3 or fewer required fields. Each form says what happens after you submit.
- **2:** A lead capture exists but is hard to find, or forms ask for 4-5 fields.
- **1:** Only a "Contact us" form, or forms with 6+ required fields or a phone number before any commitment.
- **0:** No way to capture a lead at all.

Don't submit forms with fake data. Judge them by looking.

### 7. Navigation and structure

- **3:** 7 or fewer main menu items with plain names. Every page is reachable in 2 clicks. Footer has contact, key pages, and legal links. No broken links.
- **2:** Menu is a bit crowded or has vague labels ("Solutions", "Resources") but works.
- **1:** 8+ menu items, confusing labels, or important pages hidden.
- **0:** Broken menu links or dead-end pages.

Also check: what happens at a made-up URL (for example `/this-page-does-not-exist`). A helpful 404 page with links back is good. A blank error page is a finding.

### 8. On-page SEO

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

### 9. AI search readiness

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

### 10. Accessibility basics

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

### 11. Speed and mobile signals

What you can check depends on your abilities:
- **From the page source:** very large images (over about 500 KB), old image formats (PNG or JPG photos where WebP would do), lots of separate scripts and stylesheets, multiple tracking or chat widgets, and embedded videos loading on page load.
- **If you can open a browser:** run the home page through Google's free test at https://pagespeed.web.dev/ and report the mobile Performance score and the Core Web Vitals it shows (LCP, CLS, INP). Then view the home page at phone width and check that text is readable without zooming, buttons are easy to tap, nothing runs off the side of the screen, and pop-ups don't cover the page.

Scoring:
- **3:** Fast results, or no heavy assets found, and the mobile view works well.
- **2:** A few heavy images or a mid-range speed score.
- **1:** Many heavy assets, a poor speed score, or mobile layout problems.
- **0:** The page is unusable on mobile or takes very long to load.

If you couldn't measure speed or view mobile, give the area "Not checked" instead of a score and explain why.

## Step 5: Write the report

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
| Page flow and layout | 1 / 3 | |
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
| **Total** | **[X] / 33** | |

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

## Page maps
(The top-to-bottom map of each key page from Step 3, with the problems marked.)

## Page-by-page notes
(One short block per page audited, listing anything not covered above.)

## What this audit can't see
This audit looks at the site from the outside. It doesn't include traffic, conversion rates, search rankings, or ad performance. For those, check Google Analytics, Google Search Console, or your ad platforms.
(List anything you couldn't check this time, like speed or mobile view, and why.)
```

## Step 6: Offer next steps

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

## Marketing playbook

Check every key page against these. Each one is a common mistake that owners without a marketing background miss. When you find one, report the page, what you saw, and the fix.

### Layout and flow mistakes

- **Form or calendar only at the bottom.** The signup form or booking calendar sits at the end of a long page, and nothing above it links down to it. Fix: add buttons every 2-3 screens that jump to the form (an anchor link), and put a button in the first screen.
- **Sales video buried.** A sales video (VSL) sits halfway or two-thirds down the page. Fix: move it to the first screen, right under the headline, with a call-to-action button directly below it.
- **Video with no next step.** A video ends with no button under it. Fix: put the main call to action directly under every sales video.
- **Video that won't get played.** A video has no thumbnail, a generic thumbnail, or no reason to press play. Fix: use a thumbnail with a face and a promise, and a line above it saying what they'll learn.
- **Only one ask on a long page.** A long sales page has a single call to action. Fix: repeat it every 2-3 screens, after each proof section, and at the end.
- **No button in the header.** The top menu has no call-to-action button. Fix: add one (for example "Book a call") in the header, styled as a button.
- **Navigation on landing pages.** A landing or sales page has the full site menu and footer links, giving visitors ways to wander off. Fix: strip the menu from dedicated landing pages, or keep only the logo and one button.
- **Proof far from the ask.** Testimonials live on a separate page or far from the buy or booking button. Fix: put 1-3 short, named testimonials right next to each main call to action and next to the price.
- **Price before value.** The price shows up before the page explains the problem, the result, and what's included. Fix: build the value first, then show the price with what's included and a guarantee next to it.
- **Price hidden on a sales page.** A buy-now page never shows the price, or makes people book a call just to learn it. Fix: show the price, or say "starting at" (unless the business deliberately sells high-ticket offers only through calls, which is fine if the page says what happens on the call).
- **Lead magnet hidden.** A free guide, quiz, or training is only in the footer or on one page. Fix: offer it on the home page, the end of every blog post, and the About page.
- **"Subscribe to our newsletter."** The email signup offers nothing specific. Fix: offer a specific benefit ("Get the 5-step checklist") or a lead magnet.
- **Dead-end pages.** The About page, blog posts, or case studies end with no next step. Fix: end every page with one clear call to action.
- **Pop-up on arrival.** A pop-up covers the page in the first few seconds, or several pop-ups stack. Fix: trigger pop-ups on scroll or exit, show at most one, and make it easy to close on mobile.
- **Rotating hero slider.** The first screen rotates between messages. Fix: replace it with one clear headline and one button.
- **Chat widget or cookie bar covering buttons** on mobile. Fix: move it or shrink it.
- **Social icons at the top.** Links to Instagram or Facebook in the header send visitors away before they act. Fix: move social links to the footer.
- **External links stealing visitors.** Sales pages link to other sites in the same tab. Fix: remove them, or open them in a new tab.
- **Too many equal choices.** The home page gives 4+ offers equal weight, with no guidance on where to start. Fix: lead with the main offer, or add a "Which one is right for you?" path by visitor type.
- **Pricing with no recommendation.** A pricing table has 3+ options with none highlighted. Fix: mark one "Most popular" or "Recommended."
- **Fake urgency.** A countdown timer resets on reload, or "only 3 spots left" never changes. Fix: use only real deadlines. Fake urgency damages trust.
- **Inconsistent offers.** Offer names or prices differ between pages. Fix: make them match everywhere.
- **"Contact us" instead of a direct path.** Visitors have to email and wait. Fix: let them book a call, buy, or apply directly.
- **No "what happens next."** Forms and buttons don't say what happens after clicking (a call? an email? a download?). Fix: add one line under the button.
- **Thank-you page with no next step**, if you can see it without submitting a form. Fix: give the next step (watch a video, book a call, join the community).

### Copywriting principles

- **Clarity beats cleverness.** If the headline needs explaining, it's failing.
- **One page, one reader, one offer, one action.** Every key page should be written to one type of person and drive one main action.
- **Lead with the reader's outcome.** Headlines and openings say what the reader gets, not what the company does. "Get booked as a podcast guest in 30 days" beats "Podcast booking solutions."
- **"You" over "we."** Count roughly how often the copy says "we/our/I" vs "you/your." Customer-focused copy leans toward "you."
- **Benefits over features.** Every feature should answer "so what?" Weak: "6 coaching calls." Strong: "6 coaching calls, so you're never stuck for more than a week."
- **Specific beats vague.** "Helped 312 clients raise prices by an average of 22%" beats "Helped hundreds of clients grow." Flag claims with no specifics.
- **Name the problem before the solution.** Strong sales copy describes the reader's situation in their words before pitching anything.
- **Answer objections.** Look for answers to the big 5: price ("Is it worth it?"), time ("Do I have time?"), fit ("Will this work for me?"), trust ("Can I trust you?"), and risk ("What if it doesn't work?").
- **Reverse the risk.** A guarantee, free trial, or clear refund policy near the price. If there's none, suggest one, or suggest stating the policy plainly.
- **Say who it's for and who it's not for.** It builds trust and helps the right people say yes.
- **Proof for every big claim.** A claim with no testimonial, number, or example near it is a weak claim.
- **Button copy completes the sentence "I want to..."** "Get my free guide" and "Book my strategy call" beat "Submit" and "Learn more."
- **Easy to skim.** Short paragraphs, clear subheadings every few paragraphs, and bullet lists. Aim for a reading level most adults find easy (roughly grade 6-8).
- **Honest urgency only.** Real deadlines, real limits, or a real reason to act now.
- **The P.S. and the end of the page get read.** Long sales pages should end with a short recap and a final call to action.

### Sales page structure

A proven order for a sales or landing page. Not every page needs every part, but big departures from this order are usually findings:

1. Headline (the outcome) and subheadline (how, or for whom)
2. Sales video, if there is one
3. Call-to-action button
4. The problem, in the reader's words
5. Why the usual fixes don't work
6. The solution: the offer and how it works (often 3 steps)
7. Proof: testimonials, results, case studies
8. What's included, with benefits
9. Who it's for, and who it's not for
10. Price, with bonuses and the guarantee next to it
11. Call-to-action button
12. About the founder (short, credibility-focused)
13. FAQ that answers objections
14. Final call to action, plus a short P.S.

For a home page, the order is usually: a clear headline and button, a "who we help" or "choose your path" section, the main offer, proof, the lead magnet, about the founder, and a final call to action.
