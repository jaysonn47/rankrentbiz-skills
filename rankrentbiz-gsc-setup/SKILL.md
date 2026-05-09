---
name: rankrentbiz-gsc-setup
description: "Set up Google Search Console monitoring for rankings, impressions, and organic traffic. Use for GSC verification, sitemap submission, ranking tracking, performance monitoring, monthly reporting."
---

---

---

---
name: rankrentbiz-gsc-setup
description: Set up Google Search Console monitoring for rankings, impressions, and organic traffic. Use for: GSC verification, sitemap submission, ranking tracking, performance monitoring, monthly reporting.
---

# Skill: rankrentbiz-gsc-setup

## Overview
Set up Google Search Console monitoring to track rankings, impressions, clicks, and organic traffic for your site.

**Time Saved:** 30 minutes per site
**Complexity:** Low
**Repeatable:** Yes (for all 30 sites)

---

## What This Skill Does

Provides:
- ✅ Domain verification in Google Search Console
- ✅ Sitemap submission (all 4 sitemaps)
- ✅ Coverage report monitoring
- ✅ Performance tracking setup
- ✅ Keyword ranking monitoring
- ✅ Mobile usability checks
- ✅ Core Web Vitals monitoring
- ✅ Monthly reporting checklist

---

## Prerequisites

Before using this skill, you need:
- [ ] Domain name (e.g., lintguard.ca)
- [ ] Cloudflare account (for DNS access)
- [ ] Google account (for GSC)
- [ ] Site deployed to Cloudflare Pages
- [ ] 4 sitemaps created (pages, locations, blog, master)

---

## Step-by-Step Process

### Step 1: Verify Domain in Google Search Console (10 minutes)

**Request to Manus Agent:**
"Verify [domain] in Google Search Console using DNS method:

1. Go to search.google.com/search-console
2. Click 'Add Property'
3. Select 'URL prefix'
4. Enter: https://www.[domain]
5. Click 'Continue'
6. Select 'DNS record' verification
7. Copy the TXT record value
8. Go to Cloudflare dashboard
9. Select [domain]
10. Go to DNS settings
11. Click 'Add record'
12. Type: TXT
13. Name: [domain]
14. Content: [paste TXT value from GSC]
15. Click 'Save'
16. Wait 24-48 hours for DNS propagation
17. Return to GSC
18. Click 'Verify'

Document:
- Verification date
- Verification method
- Verification status"

**What you'll receive:**
- Domain verified in GSC
- Ready for sitemap submission

---

### Step 2: Submit Sitemaps (10 minutes)

**Request to Manus Agent:**
"Submit all 4 sitemaps to Google Search Console:

1. Go to GSC
2. Select [domain]
3. Go to 'Sitemaps' section
4. Click 'Add/Test Sitemap'
5. Submit:
   - https://www.[domain]/sitemap.xml (master)
   - https://www.[domain]/sitemap-pages.xml
   - https://www.[domain]/sitemap-locations.xml
   - https://www.[domain]/sitemap-blog.xml

For each sitemap:
- Note submission date
- Check status (Submitted, Processing, Success)
- Note number of URLs indexed

Document:
- Submission dates
- Status for each sitemap
- URLs indexed per sitemap"

**What you'll receive:**
- All 4 sitemaps submitted
- Indexing status tracked

---

### Step 3: Monitor Coverage Report (5 minutes)

**Request to Manus Agent:**
"Set up Coverage report monitoring:

1. Go to GSC
2. Select [domain]
3. Go to 'Coverage' section
4. Note:
   - Valid (green) — pages indexed successfully
   - Excluded (gray) — pages not indexed (usually OK)
   - Error (red) — pages with errors
   - Valid with warnings (yellow) — pages indexed but with issues

Document:
- Total pages indexed
- Any errors or warnings
- Action items (if any)

Check weekly for first month, then monthly."

**What you'll receive:**
- Coverage report baseline
- Monitoring checklist

---

### Step 4: Set Up Performance Monitoring (10 minutes)

**Request to Manus Agent:**
"Set up Performance report monitoring:

1. Go to GSC
2. Select [domain]
3. Go to 'Performance' section
4. Note metrics:
   - Total Impressions (how many times your site appears in search)
   - Total Clicks (how many times users click your site)
   - Average CTR (click-through rate)
   - Average Position (where you rank)

Create a tracking spreadsheet with:
| Date | Impressions | Clicks | CTR | Avg Position |
|---|---|---|---|---|
| Week 1 | [data] | [data] | [data] | [data] |

Document:
- Baseline metrics (Week 1)
- Weekly tracking for first month
- Monthly tracking thereafter"

**What you'll receive:**
- Performance baseline
- Tracking spreadsheet
- Monitoring checklist

---

### Step 5: Monitor Keyword Rankings (10 minutes)

**Request to Manus Agent:**
"Set up keyword ranking monitoring:

1. Go to GSC
2. Select [domain]
3. Go to 'Performance' section
4. Click 'Queries' tab
5. Note top keywords:
   - Keyword
   - Impressions
   - Clicks
   - CTR
   - Average Position

Create a tracking spreadsheet with:
| Keyword | Impressions | Clicks | CTR | Position | Trend |
|---|---|---|---|---|---|
| [keyword] | [data] | [data] | [data] | [data] | [↑/↓/→] |

Document:
- Top 20 keywords
- Baseline positions (Week 1)
- Weekly tracking for first month
- Monthly tracking thereafter"

**What you'll receive:**
- Keyword ranking baseline
- Tracking spreadsheet
- Monitoring checklist

---

### Step 6: Check Mobile Usability (5 minutes)

**Request to Manus Agent:**
"Check mobile usability in GSC:

1. Go to GSC
2. Select [domain]
3. Go to 'Mobile Usability' section
4. Note:
   - Any errors
   - Any warnings
   - Mobile-friendly status

If errors found:
- Document error type
- Fix in site code
- Resubmit for crawling

Document:
- Mobile usability status
- Any errors/warnings
- Action items (if any)"

**What you'll receive:**
- Mobile usability baseline
- Error documentation
- Action items (if any)

---

### Step 7: Monitor Core Web Vitals (5 minutes)

**Request to Manus Agent:**
"Monitor Core Web Vitals in GSC:

1. Go to GSC
2. Select [domain]
3. Go to 'Core Web Vitals' section
4. Note:
   - Largest Contentful Paint (LCP) — page load speed
   - First Input Delay (FID) — interactivity
   - Cumulative Layout Shift (CLS) — visual stability

Document:
- LCP status (Good/Needs Improvement/Poor)
- FID status (Good/Needs Improvement/Poor)
- CLS status (Good/Needs Improvement/Poor)
- Any pages with issues

If issues found:
- Optimize images (for LCP)
- Optimize JavaScript (for FID)
- Fix layout shifts (for CLS)
- Resubmit for crawling"

**What you'll receive:**
- Core Web Vitals baseline
- Performance issues identified
- Optimization recommendations

---

### Step 8: Create Monthly Reporting Checklist (5 minutes)

**Request to Manus Agent:**
"Create a monthly GSC reporting checklist:

Every month, check:
- [ ] Coverage report (valid, excluded, errors)
- [ ] Performance metrics (impressions, clicks, CTR, position)
- [ ] Top 20 keywords (rankings, impressions, clicks)
- [ ] Mobile usability (any errors/warnings)
- [ ] Core Web Vitals (LCP, FID, CLS status)
- [ ] New keywords appearing (opportunities)
- [ ] Keywords dropping (issues)
- [ ] Sitemaps (any errors)
- [ ] Crawl stats (crawl budget usage)
- [ ] Security issues (any alerts)

Create a template document with:
- Checklist items
- Data fields for recording
- Trend analysis
- Action items

Document:
- Baseline metrics (Month 1)
- Monthly tracking thereafter"

**What you'll receive:**
- Monthly reporting checklist
- Template document
- Monitoring schedule

---

## Expected Outputs

After completing this skill, you'll have:

### Google Search Console Setup
- ✅ Domain verified
- ✅ All 4 sitemaps submitted
- ✅ Coverage report baseline
- ✅ Performance metrics baseline
- ✅ Keyword rankings baseline
- ✅ Mobile usability checked
- ✅ Core Web Vitals baseline

### Tracking Spreadsheets
- ✅ Performance tracking (weekly/monthly)
- ✅ Keyword ranking tracking (weekly/monthly)
- ✅ Core Web Vitals tracking (monthly)

### Monitoring Checklists
- ✅ Weekly monitoring checklist
- ✅ Monthly reporting checklist
- ✅ Action items documentation

---

## Example Output Structure

```markdown
# Google Search Console Setup: Backflow Prevention Testing

## Domain Verification
- Domain: backflow-gta.ca
- Verification method: DNS record
- Verification date: [Date]
- Status: ✅ Verified

## Sitemaps Submitted
| Sitemap | URL | Submission Date | Status | URLs Indexed |
|---|---|---|---|---|
| Master | /sitemap.xml | [Date] | Success | 50 |
| Pages | /sitemap-pages.xml | [Date] | Success | 8 |
| Locations | /sitemap-locations.xml | [Date] | Success | 16 |
| Blog | /sitemap-blog.xml | [Date] | Success | 0 |

## Performance Baseline (Week 1)
- Impressions: 50-100
- Clicks: 5-10
- CTR: 5-10%
- Avg Position: 15-20

## Top Keywords (Week 1)
| Keyword | Impressions | Clicks | CTR | Position |
|---|---|---|---|---|
| backflow testing | 20 | 2 | 10% | 18 |
| backflow prevention | 15 | 1 | 7% | 22 |

## Core Web Vitals Status
- LCP: Good
- FID: Good
- CLS: Good
```

---

## Quality Checklist

Before moving to next phase:

- [ ] Domain verified in GSC
- [ ] All 4 sitemaps submitted
- [ ] Coverage report reviewed
- [ ] Performance metrics recorded
- [ ] Top 20 keywords documented
- [ ] Mobile usability checked
- [ ] Core Web Vitals checked
- [ ] Tracking spreadsheets created
- [ ] Monthly checklist created
- [ ] Baseline metrics documented

---

## Common Issues & Solutions

### Issue: Domain won't verify
**Solution:** Check DNS record in Cloudflare, wait 24-48 hours for propagation

### Issue: Sitemaps show errors
**Solution:** Verify sitemap XML is valid, check robots.txt points to correct URL

### Issue: No impressions in first week
**Solution:** Normal — indexing takes 1-2 weeks, check again in Week 2-3

### Issue: Core Web Vitals show issues
**Solution:** Optimize images (LCP), reduce JavaScript (FID), fix layout shifts (CLS)

---

## Time Breakdown

| Step | Time | Notes |
|------|------|-------|
| Domain verification | 10 min | DNS method |
| Sitemap submission | 10 min | 4 sitemaps |
| Coverage monitoring | 5 min | Baseline check |
| Performance setup | 10 min | Metrics tracking |
| Keyword monitoring | 10 min | Top 20 keywords |
| Mobile usability | 5 min | Error check |
| Core Web Vitals | 5 min | Performance check |
| Reporting checklist | 5 min | Monthly template |
| **TOTAL** | **60 min** | **~1 hour** |

---

## Ongoing Monitoring (After Setup)

**Weekly (First Month):**
- Check Coverage report
- Check Performance metrics
- Check top keywords
- Document trends

**Monthly (Ongoing):**
- Full GSC audit (coverage, performance, keywords, mobile, CWV)
- Compare to previous month
- Identify trends (improving/declining)
- Document action items

**Quarterly:**
- Comprehensive review
- Identify patterns
- Plan optimizations
- Report to stakeholders

---

## Success Metrics

After this skill:
- ✅ GSC fully configured
- ✅ All sitemaps submitted
- ✅ Baseline metrics recorded
- ✅ Monitoring schedule established
- ✅ Ready for ongoing tracking

---

## Notes

- GSC is the **primary tool** for monitoring organic performance
- Baseline metrics are **critical** for measuring progress
- Weekly tracking helps identify **trends early**
- Monthly reporting provides **accountability**
- This skill is **repeatable** for every new site

---

## Questions?

Refer to:
- BLUEPRINT.md (master methodology)
- PRIORITY_FRAMEWORK.md (timeline expectations)
- LINTGUARD_GSC_STRATEGY.md (detailed GSC strategy)
