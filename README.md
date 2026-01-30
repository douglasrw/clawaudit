# ClawAudit - Security Audits for ClawHub Skills

## Status: READY TO LAUNCH

Professional security audit service for ClawHub skills.

---

## Quick Start Checklist

- [ ] Set up PayPal.me link (or Stripe/Gumroad)
- [ ] Update payment links in `landing-page.html`
- [ ] Deploy landing page (GitHub Pages, Carrd, or Vercel)
- [ ] Post to m/skillaudits (Post 1 in moltbook-posts.md)
- [ ] Wait 30-60 min cooldown
- [ ] Post to m/clawdbot (Post 2)
- [ ] Wait 30-60 min cooldown
- [ ] Post to m/security (Post 3)
- [ ] Monitor for DMs and comments

---

## Files

| File | Purpose |
|------|---------|
| `audit-checklist.md` | Standard checklist for performing audits |
| `audit-report-template.md` | Template for customer reports |
| `moltbook-posts.md` | Pre-written launch posts |
| `landing-page.html` | Sales page (deploy to hosting) |

---

## Pricing

| Tier | Price | Launch Price (50% off) |
|------|-------|------------------------|
| Basic | $49 | $25 |
| Standard | $99 | $50 |
| Premium | $199 | $100 |

---

## Workflow

### New Customer
1. Receive PayPal payment notification
2. Email customer asking for skill name/URL
3. Perform audit using `audit-checklist.md`
4. Generate report from `audit-report-template.md`
5. Email report to customer
6. Post summary to m/skillaudits (builds reputation)

### Turnaround Times
- Basic: 24-48 hours
- Standard: 24-48 hours
- Premium: 72 hours (includes re-audit)

---

## Revenue Targets

**Week 1:** 5-10 audits = $250-1,000
**Month 1:** 20-40 audits = $1,000-4,000

---

## Deployment Options

### GitHub Pages (Free)
```bash
# Create repo, push landing-page.html as index.html
git init clawhub-audit-site
cp landing-page.html clawhub-audit-site/index.html
cd clawhub-audit-site
git add . && git commit -m "Initial landing page"
gh repo create clawhub-audit --public --push
# Enable Pages in repo settings
```

### Carrd.co (Free tier)
1. Go to carrd.co
2. Create new site
3. Copy content structure from landing-page.html
4. Add payment links

### Vercel (Free)
```bash
cd products/clawhub-audit
vercel deploy
```

---

## Next Actions

1. **Now:** Set up PayPal.me at paypal.me
2. **Now:** Update payment links in landing-page.html
3. **Now:** Deploy landing page
4. **Now:** Post first Moltbook post
5. **Today:** Engage with responses
6. **Optional:** Do one free audit for social proof
