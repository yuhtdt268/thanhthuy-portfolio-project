# AI Search Crawlability and Why Your Site's Tech Foundations Decide Visibility

* **Expert:** Aleyda Solís
* **Interviewed by:** Pipeline Podcast (Phil & John Taylor)
* **URL:** [https://www.youtube.com/watch?v=pqrwpXpMM6s](https://www.youtube.com/watch?v=pqrwpXpMM6s)  
* **Why this video:** Aleyda Solís is one of the most respected international SEO consultants in the world, founder of Orainti, author of the SEO FOMO newsletter (40k+ subscribers), and frequent speaker at major marketing conferences. This episode covers the technical and strategic gaps between traditional SEO and AI search visibility, with specific guidance on crawlability, content strategy, and how to audit your LLM presence.

---

## Key Themes

- Why SEO fundamentals carry over to AI search — and what's genuinely new
- The technical crawlability gap between Google and AI crawlers
- How to think about LLMs as a new channel, not a new discipline
- Content strategy for AI search: what to create and what to stop creating
- How to track and measure AI search visibility by topic (not by prompt)
- Why community signals and mentions matter more than ever

---

## Part 1: SEO Fundamentals Still Apply — With Important Differences

Aleyda's core position: **Good SEO is good GEO.** The principles of SEO remain valid and relevant for AI search. But whether your current SEO work translates depends heavily on your level of maturity and what you've already been doing.

The pillars that carry over directly:

- Crawlability and indexability
- Content relevance and topical authority
- Brand authority and trust signals
- Technical site foundations

The areas that are genuinely different:

- **Which crawlers you need to allow** — AI crawlers use different user agents than Google. You might be allowing traditional search engine crawlers while unknowingly blocking AI crawlers. This is an extra validation step most sites haven't taken.
- **JavaScript rendering** — Google is sophisticated at rendering JavaScript (with some limitations at scale). AI crawlers don't render JavaScript at all. If you rely on client-side JavaScript for critical content or navigation, AI crawlers won't see it.
- **Mentions vs. links** — Traditional SEO was heavily focused on backlinks. AI search gives significantly more weight to mentions (even without a link). The shift in importance of unlinked brand mentions is real.
- **AI search as a branding channel** — Traditional search has always been treated as a performance channel (rankings, clicks, traffic, conversions). Treating AI search the same way is too narrow. Share of voice, sentiment, and brand visibility in AI answers matter even when they don't drive a direct click.

---

## Part 2: The Crawlability Problem Most Sites Don't Know They Have

One of the most actionable insights from this episode: **many hosting companies proactively block AI crawlers by default.**

Aleyda discovered this firsthand — her hosting platform was blocking AI bots from accessing some of her own sites without her knowledge. She only found out when she noticed her share of voice in LLM answers was much lower than expected and dug deeper to investigate.

Her recommendation: **validate that AI crawlers can actually access your site.** This should be treated as an opt-in decision you make consciously — not something your hosting company decides for you without disclosure.

Steps to take:

1. Check your `robots.txt` file — are AI crawler user agents explicitly blocked?
2. Check your hosting provider's default settings for AI bot access
3. Check your CDN configuration — blocking may be happening at the CDN level, not just on your server
4. If you're blocked, contact your hosting company and opt out of the blocking

The broader technical implication: if your site relies heavily on client-side JavaScript rendering for content, navigation, or internal links, AI crawlers are not seeing that content. Server-side rendering is significantly more compatible with AI crawl infrastructure.

---

## Part 3: LLMs Are a New Channel, Not a New Discipline

Aleyda's framing: **LLMs are to SEO what TikTok is to YouTube** — a new channel within a broader medium, not an entirely new field.

The "SEO is dead" reaction happens because people have historically conflated SEO with Google. When the Google SERP changes or new platforms emerge, it feels like SEO is dying — when really SEO is evolving to cover additional platforms where audiences search for information.

Evidence this is already happening globally: Aleyda was at an event in Shenzhen, China, where Baidu doesn't have the same dominance that Google has in the Western world. Chinese marketers already optimize across Baidu, Xiaohongshu (China's Instagram-like platform), TikTok, and other channels simultaneously — because no single platform dominates. The Western world is moving toward that same multi-platform reality.

**Practical implication for teams:** You don't need a separate GEO function or a dedicated LLM specialist right now. Your existing SEO team (in-house, agency, or consultant) already has the skills to extend their work to cover AI search. The ROI on creating a separate function isn't there yet. Use what you have, extend the mandate.

In the future — if LLM platforms become as differentiated as YouTube vs. TikTok in terms of algorithm behavior — specialization may make sense. But that's not today.

---

## Part 4: How to Assess Your AI Search Visibility

Rather than obsessing over specific prompts, Aleyda recommends thinking at the **topic level**.

Her process:

**Step 1 — Understand your current AI traffic baseline**

- How much traffic is currently coming from LLMs to your site?
- What is the current revenue impact of LLM mentions?
- Use third-party tools to look at traffic drivers for your site and your competitors' sites

**Step 2 — Assess visibility by topic, not by brand overall**

- Don't just check "is my brand mentioned in ChatGPT?" — check visibility by specific topic areas relevant to your business
- Example for a sports retailer: check visibility for "women's sneakers," "men's jackets," "children's golf wear" separately — not just "our brand vs. Adidas" broadly
- Compare your share of voice and sentiment against competitors within each topic

**Step 3 — Audit the sources of your citations**

- Where are the citations in LLM answers coming from?
- Are they from platforms you've actively optimized and where you have presence?
- Or are they from platforms where you have no presence and no control?
- Are you being cited with positive or negative sentiment? (Reddit threads that rank poorly in Google but get picked up by LLMs can surface negative mentions you've ignored)

**Step 4 — Track a sample of prompts over time, per topic**

- Use prompt trackers to monitor a representative set of prompts within each topic area
- Goal: track *evolution over time* within a topic, not whether you appear in any specific prompt
- Don't optimize for individual prompts — too long-tail, too personalized, too variable

**On prompt obsession:** Aleyda is clear — don't make the same mistake with LLM prompts that bad SEO made with keywords. Don't rank-track specific prompts the same way people obsessively tracked exact-match keyword positions. The same problem, phrased differently by two different users, will produce different answers due to personalization, location, history, and context.

---

## Part 5: Content Strategy for AI Search

### Stop creating low-value informational content just for traffic

Top-of-funnel, generic informational content ("what is X") has been declining in value since AI overviews arrived — AI can easily summarize basic definitions, and users are satisfied without clicking. LLMs accelerate this further.

But the answer isn't to eliminate informational content. The answer is to be more strategic about what kind of informational content you create.

### Create on-brand, persona-driven content that would be valuable even without SEO

The right informational content for AI search is content that:

- Is deeply on brand (tied to your specific product, service, or area of expertise)
- Is useful to your actual customers — not just optimized for search volume
- Establishes topical authority and earns citations
- Provides context for decision-making across the full customer journey
- Would be worth creating even if there were no SEO benefit

Specific content types that work well:

- Industry research, original data, and statistics
- Trend analysis and forward-looking insights
- Case studies and customer stories
- Thought leadership with a clear point of view
- Competitor comparisons (from your perspective)
- FAQs built from real customer questions
- Help centers and forums that address pre-sales questions, not just post-purchase support
- Community-sourced content published on your site

### The brand authority lesson from the Google HCU

Aleyda references a major site (not named) that lost roughly 25% of its traffic in a Google Helpful Content Update. The pages that dropped were high-volume but off-topic — covering broad search terms tangentially related to the site's core offering. These pages drove enormous traffic but had almost no connection to what the company actually sold.

Her takeaway: creating content that's off-brand just because it has high search volume was always a mistake — it's just becoming more visibly punished. This applies equally to AI search: LLMs favor genuine topical authority from sources that are clearly expert in a specific area. A site that covers everything weakly loses to a site that covers its niche comprehensively.

### The persona-first approach

One of the consistent themes: the best SEO teams talk to sales, customer support, and product — not just pull keyword lists from tools. Customer conversations reveal pain points and language that often doesn't show up in keyword research, especially for newer topics. Kevin Indig made the same point (see his transcript). This approach produces content that converts better because it addresses real customer concerns.

---

## Part 6: Community Signals Are Now Core SEO Infrastructure

A key shift Aleyda highlights: **LLMs pull heavily from community platforms** — Reddit, YouTube, forums, review sites like G2 and Trustpilot — when forming answers.

This means:

- What people say about you on Reddit, even in threads you've never seen, may be shaping how LLMs describe your brand
- Review platforms (G2, Trustpilot, Google Maps) feed directly into LLM training and grounding
- Community management is no longer separate from SEO — it's part of the same visibility ecosystem

If you discover your LLM mentions are negative, the fix likely isn't more content on your website. The fix is in your community — engaging with Reddit threads, responding to reviews, building genuine product advocates who talk about you positively in public.

**New platform mix by LLM:** Different LLMs pull from different source distributions. Google/Gemini has a noted bias toward Reddit. ChatGPT leans more heavily on Wikipedia. Knowing which platforms your target LLMs favor should inform where you invest in community presence.

---

## Part 7: Will AI Search Reward Quality Over Quantity?

Aleyda's answer: **it's already happening.**

She's seeing early-stage startups with limited SEO infrastructure — few backlinks, no optimized landing page taxonomy, no structured keyword targeting — getting cited heavily in ChatGPT and generating significant revenue from it. Why? Because they had genuine community traction: YouTube mentions, social media discussions, positive brand sentiment in the places LLMs pull from.

These startups wouldn't have appeared in traditional Google search for competitive keywords. But in LLMs, authentic community signals and clear expertise in a specific niche are weighted more directly — and they're winning.

Her prediction: this dynamic will grow over time. AI search is not a zero-sum game — new queries and new topics emerge constantly. The brands with genuine authority in specific niches will continue to benefit as LLM usage grows.

---

## Part 8: The Future of LLM Search Consoles

Aleyda expects transparency tools (equivalent to Google Search Console) to eventually emerge for LLMs — but only once:

1. These platforms start selling ads consistently across AI surfaces (which creates commercial incentive to provide data)
2. The market settles enough that LLMs can demonstrate meaningful traffic referral volume

ChatGPT's shopping integration may be an early signal — when e-commerce integrations scale, data transparency will likely follow.

---

## Key Takeaways

- **Validate crawlability first.** Many hosting providers block AI crawlers by default. Check your `robots.txt` and CDN settings immediately. This is table stakes before any other AI search work.
- **JavaScript dependency is a real risk.** AI crawlers don't render JavaScript. If your critical content or navigation depends on client-side JS, AI crawlers won't see it.
- **LLMs are a channel, not a new discipline.** Extend your SEO team's mandate rather than creating a separate GEO function.
- **Think topics, not prompts.** Assess and track your AI visibility at the topic level, across specific product/service areas. Don't obsess over individual prompt rankings.
- **Mentions matter as much as links now.** Unlinked brand mentions in community platforms feed directly into LLM visibility. Community management is now SEO infrastructure.
- **On-brand content outperforms volume.** Off-topic, high-volume content is increasingly punished by both Google and LLMs. The shift toward persona-driven, expertise-based content is not optional.
- **Community signals are already driving real results.** Startups with strong community presence but limited traditional SEO are winning in LLMs. Authentic brand mentions in Reddit, YouTube, and forums are high-value signals.

---

## Resources Mentioned

- **learninggeo.io** — Free aggregated resources for AI search learning and execution (Aleyda's site)
- **learningSEO.io** — Her SEO learning counterpart (free)
- **SEO FOMO newsletter** — Her main newsletter, ~40k subscribers, covers SEO + AI search
- **AIMarketers.com** — Her AI marketing newsletter, covers broader AI marketing trends

