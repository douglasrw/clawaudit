# ClawAudit Marketing & Traction Playbook

A comprehensive, actionable guide for launching and growing ClawAudit - the security audit service for ClawHub skills (AI agent plugins).

---

## Table of Contents
1. [Market Context](#market-context)
2. [Community Channels](#1-community-channels)
3. [Influencer Outreach](#2-influencer-outreach)
4. [Content Marketing](#3-content-marketing)
5. [Cold Outreach](#4-cold-outreach)
6. [Partnerships](#5-partnerships)
7. [Launch Sequence](#6-launch-sequence)
8. [Growth Loops](#7-growth-loops)
9. [Metrics & KPIs](#8-metrics--kpis)

---

## Market Context

### Why Now is the Perfect Time

The AI agent security landscape is at a critical inflection point:

- **AI CVEs jumped 70% YoY** - from ~450 in 2024 to over 1,000 in 2025 ([eSecurity Planet](https://www.esecurityplanet.com/artificial-intelligence/ai-agent-attacks-in-q4-2025-signal-new-risks-for-2026/))
- **94.4% of LLM agents are vulnerable to prompt injection** according to security research ([arXiv](https://arxiv.org/html/2510.23883v1))
- **MCP plugins grew 50% in 2025** alone, with security practices lagging far behind ([ScienceDirect](https://www.sciencedirect.com/science/article/pii/S2405959525001997))
- **Only 24% of generative AI projects are currently secured** according to IBM's 2025 X-Force report
- **Real exploits are happening** - The September 2025 Chinese espionage campaign using Claude Code against 30 global targets proved AI agent attacks are not theoretical ([The Hacker News](https://thehackernews.com/2025/11/chinese-hackers-use-anthropics-ai-to.html))

Simon Willison's "Lethal Trifecta" concept has become the definitive framework for understanding AI agent risk:
1. Access to private data
2. Exposure to untrusted content
3. Ability to externally communicate

**ClawHub skills that combine all three are critically vulnerable.** This is the core message for all marketing.

---

## 1. Community Channels

### Moltbook Submolts (Primary Channel)

**Known Submolts:**
- **m/skillaudits** - Direct target audience, post audit results and case studies
- **m/clawdbot** - General ClawHub discussion, engage on security topics
- **m/security** - Broader security community, establish expertise

**Strategy for Moltbook:**
1. Post a weekly "Security Spotlight" analyzing a (consented) skill's security posture
2. Create a series: "Common Vulnerabilities in Popular Skills"
3. Engage in comments with actionable security advice, not sales pitches
4. Host AMAs about AI agent security after building reputation (month 2+)

### Reddit Communities

**Tier 1 - High Relevance:**

| Subreddit | Members | Why Target | Content Approach |
|-----------|---------|------------|------------------|
| r/LocalLLaMA | 603K | Runs local AI agents, security-conscious | Technical deep-dives on agent security |
| r/AI_Agents | 212K | Building agent frameworks | Security best practices, case studies |
| r/ChatGPT | 8M+ | Mainstream AI users | Accessible security warnings |
| r/artificial | 1.6M | Broad AI community | Industry news, security incidents |
| r/MachineLearning | 3.2M | Technical ML practitioners | Research-grade security analysis |

**Tier 2 - Niche Relevance:**

| Subreddit | Why Target |
|-----------|------------|
| r/netsec | Professional security practitioners |
| r/cybersecurity | Infosec professionals who may be evaluating AI tools |
| r/selfhosted | Users running their own AI infrastructure |
| r/SideProject | Indie developers building AI tools |
| r/startups | Founders who need to secure their AI features |

**Reddit Strategy:**
1. **Never post links directly** - Reddit buries promotional content
2. Provide value in comments first (3-4 weeks minimum)
3. Use the "educational post" format: "I audited 50 AI agent plugins, here's what I found"
4. Post findings as text posts with methodology, then mention ClawAudit only in comments when asked

### Discord Servers

**High-Priority Servers:**

| Server | Focus | Link | Strategy |
|--------|-------|------|----------|
| **Claude Developers** | Official Anthropic community | [discord.com/invite/6PPFFzqPDZ](https://discord.com/invite/6PPFFzqPDZ) | Engage in #security channels, help with MCP questions |
| **OpenAI** | ChatGPT builders, plugin devs | Search "OpenAI Discord" | Share security insights in plugin channels |
| **Hugging Face** | Open-source AI community | [huggingface.co/discord](https://huggingface.co/discord) | Technical content, model security |
| **LangChain** | Agent framework users | [langchain.dev Discord] | Security best practices for agents |
| **CrewAI** | Multi-agent builders | Search "CrewAI Discord" | Agent communication security |

**Discord Engagement Rules:**
1. Introduce yourself genuinely - "I do security audits for AI agent plugins"
2. Answer questions before promoting anything
3. Create value with free mini-audits in appropriate channels
4. Don't DM spam - build relationships publicly first

### Hacker News Strategy

**HN is high-risk, high-reward.** One front-page post can generate 50K+ views and establish credibility.

**What Works on HN:**
1. **Technical deep-dives** - "How I found 23 vulnerabilities in popular MCP servers"
2. **Show HN** - "Show HN: I built a security audit service for AI agent plugins"
3. **Research releases** - "We analyzed 100 ClawHub skills and here's the security landscape"
4. **Incident analysis** - Post-mortem breakdowns of AI agent security failures

**What Fails on HN:**
- Landing page links without substance
- Marketing-speak or buzzwords
- Anything that feels like an ad

**Optimal Posting:**
- Time: Tuesday-Thursday, 8-10 AM EST
- Title: Factual, no clickbait ("Security Audit Results for 100 AI Agent Plugins")
- Be ready to engage in comments for 2-3 hours after posting

### Twitter/X Hashtags & Engagement

**Primary Hashtags:**
- #AIAgents
- #LLMSecurity
- #AITools
- #MCPProtocol
- #PromptInjection
- #AISafety
- #AgenticAI

**Secondary Hashtags:**
- #BuildInPublic
- #IndieHackers
- #DevTools
- #InfoSec
- #AppSec

**Engagement Strategy:**
1. Quote-tweet security incidents with analysis
2. Reply to AI tool announcements with security perspective
3. Create threads breaking down vulnerabilities (redacted/consented)
4. Engage with researchers when they post security findings

---

## 2. Influencer Outreach

### AI Security Thought Leaders

**Tier 1 - Must Engage:**

| Name | Platform | Followers | Why | Approach |
|------|----------|-----------|-----|----------|
| **Simon Willison** | [@simonw](https://twitter.com/simonw) / [simonwillison.net](https://simonwillison.net) | 90K+ | Coined "Lethal Trifecta", MCP security authority | Comment on his posts, offer data for his research |
| **Daniel Miessler** | [@DanielMiessler](https://twitter.com/DanielMiessler) | 139K | AI + Security focus, creator of Fabric | Align with his "Unsupervised Learning" newsletter topics |
| **Shira Rubinoff** | [@shirastweet](https://twitter.com/shirastweet) | 57K | Top AI/cybersecurity influencer | Guest post opportunities |

**Tier 2 - Valuable Connections:**

| Name | Focus | Approach |
|------|-------|----------|
| **Tal Eliyahu** | AI Security Hub on Medium | Contribute to his AI Security Startups coverage |
| **Adversa AI Team** | MCP security research | Cross-reference their MCP Security Digest |
| **SlowMist Team** | Created MCP Security Checklist on GitHub | Collaborate on standards |

### AI Tool Reviewers & Content Creators

**YouTube Channels:**

| Channel | Focus | Collab Idea |
|---------|-------|-------------|
| **Matt Wolfe (Future Tools)** | AI tool reviews | Offer to security-audit tools he reviews |
| **All About AI** | Developer AI tools | Security considerations video |
| **Two Minute Papers** | Research breakdowns | If we publish research, pitch for coverage |

**Newsletter Writers:**

| Newsletter | Subscribers | Contact Strategy |
|------------|-------------|------------------|
| **There's An AI for That** | 2.5M | Pitch security-focused tool roundup |
| **Ben's Bites** | 120K+ | Submit security findings as news |
| **Superhuman (Zain Kahn)** | 1M+ | Security angle for AI tools coverage |
| **SemiAnalysis (Dylan Patel)** | 100K+ | Infrastructure security tie-in |

**Outreach Template for Influencers:**

```
Subject: Security data for your AI tool coverage

Hi [Name],

I run ClawAudit - we security audit AI agent plugins (ClawHub skills).

I noticed you cover [specific topic they wrote about]. We have data on
security patterns across [X] audited skills that might interest your audience:

- [Specific finding 1]
- [Specific finding 2]

Happy to share the raw data or collaborate on a piece. No expectation
of promotion - just think it'd be valuable for [their audience].

[Your name]
```

### Podcast Outreach

**Target Podcasts:**

| Podcast | Host | Pitch Angle |
|---------|------|-------------|
| Latent Space | swyx & Alessio | Technical AI security deep-dive |
| Practical AI | Chris Benson | Enterprise AI agent security |
| Last Week in AI | Andrey Kurenkov | News angle on agent vulnerabilities |
| Darknet Diaries | Jack Rhysider | AI agent exploitation stories |
| Risky Business | Patrick Gray | Enterprise security angle |

---

## 3. Content Marketing

### Blog Post Ideas (SEO + Shareability)

**Pillar Content (Long-form, linkable):**

1. **"The Complete Guide to AI Agent Security in 2025"**
   - Target keywords: AI agent security, LLM tool security, MCP security
   - 5,000+ words, comprehensive, link-worthy

2. **"Understanding the Lethal Trifecta: When AI Agents Become Attack Vectors"**
   - Credit Simon Willison, expand with ClawHub-specific examples
   - Share with Simon for potential amplification

3. **"MCP Security Checklist: 47 Things to Check Before Publishing Your Skill"**
   - Practical, actionable, highly shareable
   - Create PDF download for lead generation

4. **"Anatomy of an AI Agent Attack: Real-World Case Studies"**
   - Redacted examples from real audits (with permission)
   - Technical depth that establishes expertise

**Reactive Content (News-Driven):**

5. **"[Breaking Security Incident] - What Went Wrong and How to Prevent It"**
   - Have a template ready to publish within 24 hours of major incidents
   - E.g., analyzing the Chinese Claude Code espionage campaign

6. **"We Audited the Top 10 ClawHub Skills - Here's What We Found"**
   - Benchmark report, publish quarterly
   - Create controversy/conversation

**Comparison/Alternative Content:**

7. **"ClawAudit vs. Manual Security Review: Time and Cost Comparison"**
   - Address objection: "I can just review it myself"

8. **"What SOC 2 Doesn't Cover: Why AI Agents Need Specialized Security"**
   - For enterprise buyers who already have compliance

### Twitter Thread Topics

**Thread Format:** 10-15 tweets, end with call-to-action

1. **"I reviewed 50 AI agent plugins for security vulnerabilities. Here's what I learned (thread)"**

2. **"The 7 most common security mistakes in ClawHub skills (and how to fix each)"**

3. **"Why prompt injection is the #1 risk for AI agents in 2025 - explained simply"**

4. **"How attackers can steal your data through your AI assistant (technical breakdown)"**

5. **"The 'Verified Secure' badge process - what we actually check and why"**

6. **"From $0 to first customer: Building ClawAudit in public (ongoing series)"**

7. **"Security audit teardown: [consented skill] - what we found and recommended"**

### YouTube Video Concepts

**Short-form (YouTube Shorts / TikTok / Reels):**

1. "This AI plugin can leak your files in 30 seconds" (demo attack)
2. "3 red flags in AI agent plugins" (quick tips)
3. "What 'Verified Secure' actually means" (explainer)

**Long-form:**

1. **"Live Security Audit: Reviewing a ClawHub Skill in Real-Time"** (30-45 min)
   - Screen share, think aloud, educational

2. **"The Biggest AI Agent Security Mistakes (2025 Report)"** (15 min)
   - Annual/quarterly research presentation

3. **"How I Built a Security Audit Business for AI Agents"** (Build in public)
   - Story format, indie hacker audience

4. **"Interview: [Skill Creator] on Building Secure AI Plugins"** (Guest content)

---

## 4. Cold Outreach

### Finding Skill Creators

**Sources:**
1. ClawHub marketplace/registry - scrape creator profiles
2. GitHub - search for ClawHub skill repositories
3. MCP Registry ([registry.modelcontextprotocol.io](https://registry.modelcontextprotocol.io)) - identify MCP server creators
4. Twitter - search for people announcing skill releases
5. Discord announcements in AI communities

### DM Templates

**Template 1: Direct Value Offer**

```
Hey [Name],

Saw your [Skill Name] on ClawHub - really clever approach to [specific feature].

I run security audits for ClawHub skills. Would love to do a complimentary
quick review (15 min) and share 3-5 actionable findings.

No pitch, just want to help the ecosystem get more secure. Interested?
```

**Template 2: After Security Incident (News Hook)**

```
Hey [Name],

With the recent [security incident], a lot of skill creators are
thinking about security. I put together a quick checklist based on
auditing 50+ skills.

Want me to send it over? Also happy to do a 10-min sanity check
on [Skill Name] - no charge.
```

**Template 3: Badge Positioning**

```
Hey [Name],

Quick question - have you considered getting a "Verified Secure" badge
for [Skill Name]?

We've seen skills with the badge get 40% more installs (users trust them more).

Takes about a week. Want me to explain the process?
```

### Email Outreach (If Email Available)

**Subject Lines (A/B Test):**
- "Quick security question about [Skill Name]"
- "Free security review for [Skill Name]"
- "3 vulnerabilities I noticed in [Skill Name]"
- "[Competitor Skill] just got security certified - should you?"

**Email Template:**

```
Subject: Quick security question about [Skill Name]

Hi [Name],

I found [Skill Name] on ClawHub while researching [category] tools.
Impressive work on [specific feature].

I run ClawAudit - we security audit ClawHub skills and help creators
get the "Verified Secure" badge.

Noticed a few things while looking at your skill that I'd love to
share - nothing alarming, just optimization opportunities:

1. [Redacted specific finding]
2. [Permission scope observation]
3. [Data handling note]

Would you have 15 minutes this week for a quick call? I can walk
through these and answer any questions. No obligation - I genuinely
want to help make the ecosystem more secure.

Best,
[Name]

P.S. - If you're not the right person, mind forwarding this to
whoever handles security for your skill?
```

### Cold Outreach Best Practices

Based on [indie hacker research](https://www.indiehackers.com/post/cold-email-hacking-my-journey-in-cold-outreach-and-what-i-learned-d8085b12cb):

1. **Send 3-email sequences** with 3 days between each
2. **Personalize the first line** - reference their specific skill
3. **Keep it short** - 5-7 seconds to decide, under 100 words ideal
4. **Sound human** - avoid corporate speak, write like a real person
5. **71% ignore irrelevant emails** - specificity is everything
6. **Follow up** - most conversions happen on email 2 or 3

---

## 5. Partnerships

### ClawHub Platform Partnership

**Why This Matters:** Direct integration with the marketplace would be transformative.

**Partnership Pitch Points:**

1. **Trust & Safety** - "Verified Secure" badge increases user confidence in the entire platform
2. **Differentiation** - No other AI agent marketplace has security certification
3. **Liability Reduction** - Pre-screened skills reduce platform risk
4. **Revenue Share** - Offer ClawHub a % of audit fees for referrals

**Proposed Integration:**

1. "Verified Secure" badge displayed on skill listings
2. Optional security score visible to users
3. "Get Audited" button in skill creator dashboard
4. Security requirements for featured/promoted skills

**Outreach Strategy:**

1. First, build reputation with 20-30 successful audits
2. Document: "X skills audited, Y vulnerabilities found and fixed"
3. Reach out to ClawHub team with data and proposal
4. Offer to audit their top 10 skills for free as proof of value

### Security Service Cross-Promotion

**Complementary Services:**

| Company | What They Do | Partnership Angle |
|---------|--------------|-------------------|
| **SlowMist** | Blockchain security, [MCP Security Checklist](https://github.com/slowmist/MCP-Security-Checklist) | Co-develop standards, cross-reference |
| **Pillar Security** | LLM lifecycle security | Refer enterprise customers both ways |
| **Mindgard AI** | AI red-teaming | Technical collaboration on testing methods |
| **Invariant Labs** | Tool poisoning research | Research partnership, citation exchange |
| **Casco Security** | Autonomous security testing (YC-backed) | Referral partnership for API/infra audits |

**Partnership Outreach Template:**

```
Subject: Partnership between [Your Company] and ClawAudit?

Hi [Name],

I run ClawAudit - we do security audits specifically for AI agent
plugins (ClawHub skills).

I've been following [their work] and think there's natural overlap:

- You handle [their focus]
- We handle [our focus]
- Together we could [specific joint value]

Would you be open to a 20-minute call to explore referral partnership
or collaboration opportunities?

Best,
[Name]
```

### AI Agent Platforms

**Platforms That Might Recommend Audits:**

| Platform | Why They'd Care | Approach |
|----------|-----------------|----------|
| **Anthropic** (Claude) | Safety reputation, MCP ecosystem | Through developer relations team |
| **OpenAI** | Plugin security concerns | Developer ecosystem team |
| **LangChain** | Agent security is a known issue | Technical partnership |
| **CrewAI** | Multi-agent trust | Security certification program |
| **Dust.tt** | Enterprise AI agents | Compliance requirements |

---

## 6. Launch Sequence

### Pre-Launch (Week -2 to -1)

**Day -14 to -7:**
- [ ] Finalize landing page with clear value proposition
- [ ] Set up email capture for waitlist
- [ ] Create "Coming Soon" posts for social channels
- [ ] Draft all launch content (blog post, threads, emails)
- [ ] Identify 10 beta customers for case studies

**Day -7 to -1:**
- [ ] Do 3-5 free audits for testimonials
- [ ] Get written permission to share findings
- [ ] Create one detailed case study
- [ ] Schedule all social posts
- [ ] Prepare Product Hunt listing (if using)
- [ ] Reach out to 5 influencers with advance notice

### Launch Week Day-by-Day

#### Day 1 (Monday) - Soft Launch

**Morning:**
- Post announcement on Twitter/X with thread
- Share in Claude Developers Discord (#announcements or #showcase)
- Email existing network personally

**Afternoon:**
- Engage with every comment/reply
- Share in 2-3 relevant Discord servers
- Post to Indie Hackers

**Content to Post:**
```
Launching ClawAudit today.

We security audit ClawHub skills so users know they're safe.

Why this matters:
- 94% of AI agents are vulnerable to prompt injection
- MCP plugins grew 50% this year with no security standards
- Real attacks are happening (see: September Claude Code incident)

Skill creators: Get the "Verified Secure" badge.
Users: Only trust audited skills.

Link in bio.
```

#### Day 2 (Tuesday) - Content Push

**Morning:**
- Publish pillar blog post: "The Complete Guide to AI Agent Security"
- Share on Twitter with pull quotes
- Submit to Hacker News (technical angle)

**Afternoon:**
- Post Twitter thread: "7 most common security mistakes in ClawHub skills"
- Cross-post blog to relevant subreddits (r/LocalLLaMA, r/AI_Agents)

**Evening:**
- Engage with all HN comments
- Respond to Reddit discussions

#### Day 3 (Wednesday) - Social Proof

**Morning:**
- Share first case study: "[Skill Name] security audit results"
- Get testimonial quote from skill creator
- Post to LinkedIn (if B2B relevant)

**Afternoon:**
- Cold DM 20 skill creators with personalized messages
- Engage in Discord security discussions
- Quote-tweet any AI security news with analysis

#### Day 4 (Thursday) - Moltbook Focus

**Morning:**
- Post detailed write-up on m/skillaudits
- Cross-post to m/security and m/clawdbot
- Engage heavily in Moltbook comments

**Afternoon:**
- Respond to every Moltbook question
- Identify potential customers from discussions
- Send personalized DMs to interested users

#### Day 5 (Friday) - Influencer & PR

**Morning:**
- Follow up with influencers who didn't respond
- Pitch story to AI newsletters (Ben's Bites, etc.)
- Share "week 1 learnings" thread

**Afternoon:**
- Compile all feedback received
- Thank everyone publicly who shared/engaged
- Plan Week 2 based on what worked

### Week 2+ Sustained Activity

**Weekly Rhythm:**
- Monday: New content piece (blog or thread)
- Tuesday: Cold outreach to 20 skill creators
- Wednesday: Engage in communities, answer questions
- Thursday: Case study or customer highlight
- Friday: Review metrics, plan next week

---

## 7. Growth Loops

### Loop 1: Badge-Driven Referrals

**Mechanism:**
```
Skill creator gets audited → Gets "Verified Secure" badge →
Badge visible on their skill page → Other creators ask "how do I get that?" →
New audit customers
```

**How to Amplify:**
1. Make the badge visually prominent and appealing
2. Create a public directory of verified skills
3. Celebrate new badges publicly on social media
4. Badge includes subtle "Audited by ClawAudit" text

### Loop 2: Public Audit Reports

**Mechanism:**
```
Complete audit → Creator opts to publish report →
Report shows expertise → Other creators want same credibility →
New audit customers
```

**How to Amplify:**
1. Offer discount for permission to publish
2. Create template that makes creator look good
3. Include "Share your audit" one-click button
4. Feature reports on ClawAudit blog

### Loop 3: Security Incident Response

**Mechanism:**
```
Security incident occurs in AI agent space →
ClawAudit publishes analysis → Analysis gets shared widely →
People learn about ClawAudit → New customers
```

**How to Amplify:**
1. Set up Google Alerts for AI agent security incidents
2. Have template ready for rapid response posts
3. Be first with technical analysis
4. Include "we can help you avoid this" CTA

### Loop 4: Community Expert Status

**Mechanism:**
```
Answer security questions in communities →
Build reputation as expert → People recommend ClawAudit →
New customers → Continue answering questions
```

**How to Amplify:**
1. Dedicate 30 min/day to community engagement
2. Never pitch directly, just help
3. Signature or profile links to ClawAudit
4. Track which communities drive traffic

### Loop 5: Customer Referral Program

**Structure:**
- Referrer gets: 20% off next audit OR $50 credit
- Referee gets: 10% off first audit
- Double-sided incentive increases conversion

**How to Implement:**
1. Email customers post-audit asking for referrals
2. Provide unique referral link
3. Track in simple spreadsheet initially
4. Automate with tool like [Cello](https://cello.so) when at scale

### Loop 6: Content Syndication

**Mechanism:**
```
Publish original research/content →
Others cite/link to it → SEO improves →
Organic traffic increases → New customers →
More content → More citations
```

**High-Link-Potential Content:**
1. Security checklists (others will reference)
2. Vulnerability statistics/research
3. Framework comparisons
4. Industry reports with data

---

## 8. Metrics & KPIs

### North Star Metric
**Monthly Recurring Audits** - Number of audits completed per month

### Leading Indicators

| Metric | Target (Month 1) | Target (Month 3) | Target (Month 6) |
|--------|------------------|------------------|------------------|
| Website visitors | 500 | 2,000 | 10,000 |
| Email list signups | 50 | 200 | 1,000 |
| Audits completed | 5 | 15 | 40 |
| Verified badges issued | 3 | 10 | 30 |
| Twitter followers | 200 | 1,000 | 5,000 |
| Community mentions | 10 | 50 | 200 |

### Channel Performance Tracking

Track for each channel:
1. Visitors driven
2. Signups driven
3. Conversions to paying customer
4. Time invested
5. ROI calculation

### Weekly Review Questions

1. Which channel drove the most qualified traffic?
2. What content performed best?
3. What objections did we hear most?
4. Which cold outreach templates got responses?
5. What should we double down on vs. stop?

---

## Quick Reference: First 30 Days Checklist

### Week 1
- [ ] Post launch announcement on Twitter
- [ ] Join Claude Developers Discord, introduce yourself
- [ ] Publish first blog post
- [ ] Complete first 3 free audits for testimonials
- [ ] Cold DM 30 skill creators
- [ ] Post to m/skillaudits on Moltbook

### Week 2
- [ ] Submit to Hacker News (when you have good content)
- [ ] Post to r/LocalLLaMA and r/AI_Agents
- [ ] Publish first case study
- [ ] Send follow-up emails to non-responders
- [ ] Engage 30 min/day in Discord communities
- [ ] First Twitter thread

### Week 3
- [ ] Reach out to 3 newsletter writers
- [ ] Second blog post published
- [ ] First paying customer(?)
- [ ] Post "what I learned in 2 weeks" thread
- [ ] Identify partnership opportunities
- [ ] Cold DM 30 more skill creators

### Week 4
- [ ] Publish first "Audit Report" publicly
- [ ] Reach out to potential podcast guests
- [ ] Monthly retrospective
- [ ] Plan Month 2 based on learnings
- [ ] Set up referral tracking
- [ ] First influencer engagement

---

## Resources & Links

### Communities
- Claude Developers Discord: https://discord.com/invite/6PPFFzqPDZ
- MCP Registry: https://registry.modelcontextprotocol.io
- SlowMist MCP Checklist: https://github.com/slowmist/MCP-Security-Checklist

### Reference Material
- Simon Willison's Lethal Trifecta: https://simonwillison.net/2025/Jun/16/the-lethal-trifecta/
- MCP Safety Audit Research: https://arxiv.org/html/2504.03767v2
- Red Hat MCP Security Guide: https://www.redhat.com/en/blog/model-context-protocol-mcp-understanding-security-risks-and-controls

### Tools
- Cold Email: Apollo, Instantly, or Lemlist
- Community Management: Orbit, Common Room
- Social Scheduling: Buffer, Hypefury
- Referral Program: Cello, GrowSurf
- Analytics: PostHog, Mixpanel

---

*This playbook was compiled January 2026. Update quarterly as the landscape evolves.*
