# RankRentBiz Skills — Manus Usage Guide

This guide explains how Manus should use these 5 reusable skills to build and scale the RankRentBiz 30-site portfolio.

---

## Overview

These skills automate the core workflows for creating, optimizing, and monitoring Rank & Rent lead generation sites targeting the Greater Toronto Area (GTA) and surrounding Ontario cities. Each skill is designed to be used independently or as part of a complete workflow.

**Total time to build one site:** ~7 hours (430 minutes)

---

## The 5 Skills

### 1. rankrentbiz-site-scaffold
**Purpose:** Quickly scaffold a new Astro 6 + Tailwind 4 site with all standard components, pages, and configuration.

**When to use:** At the start of every new site project

**Time:** 75 minutes per site

**Inputs Manus needs:**
- Niche name (e.g., "Backflow Prevention Testing")
- 16 target cities (comma-separated)
- Primary color (hex code)
- Secondary color (hex code)
- Accent color (hex code)
- Phone number (format: (XXX) XXX-XXXX)
- Domain name (e.g., backflow-gta.ca)
- GitHub repo name (format: [niche]-gta)

**What Manus should do:**
1. Create a private GitHub repository with the repo name
2. Scaffold an Astro 6 + Tailwind 4 project with:
   - Standard page structure (homepage, locations, pricing, services)
   - Standard components (Hero, FAQ, Pricing, ContactForm, Footer)
   - Tailwind configuration with custom color scheme
   - 4 sitemaps (pages, locations, blog, master)
   - robots.txt
3. Deploy to Cloudflare Pages
4. Verify the site is live at the domain or pages.dev URL

**Deliverables:**
- GitHub repository with full project code
- Live site on Cloudflare Pages
- All pages loading correctly
- Schema markup validated
- Sitemaps created and accessible

**Success metrics:**
- Site loads without errors
- All pages responsive (mobile/tablet/desktop)
- All links work (internal and external)
- Build completes without warnings
- Site is live on Cloudflare Pages

---

### 2. rankrentbiz-competitor-analysis
**Purpose:** Analyze top competitors to identify ranking opportunities and content gaps.

**When to use:** After scaffolding the site, before creating content

**Time:** 105 minutes per site

**Inputs Manus needs:**
- Niche name
- 3-5 competitor URLs (top organic results for "[niche] [city]")
- Target market understanding

**What Manus should do:**
1. Use Firecrawl MCP to scrape competitor websites
2. Extract:
   - All pages and URLs
   - Title tags and meta descriptions
   - H1 and H2 headings
   - Schema markup types
   - Blog articles (if any)
   - Service descriptions
   - Contact information
3. Analyze SEO metrics:
   - Domain Authority (estimate)
   - Monthly traffic (estimate)
   - Top 20 keywords they rank for
   - Backlink count (estimate)
   - Citation count (estimate)
4. Identify weaknesses:
   - Missing location pages
   - Missing schema markup
   - No FAQ section
   - No blog content
   - Poor mobile optimization
5. Identify ranking opportunities:
   - Long-tail keywords competitors don't rank for
   - City-specific keywords
   - Question-based keywords (FAQ targets)
   - Service-specific keywords
6. Create competitive analysis document with:
   - Competitor overview table
   - SEO metrics comparison
   - Content analysis
   - Weakness identification
   - Ranking opportunities (ranked by priority)
   - Recommended strategy to outrank them

**Deliverables:**
- Competitive analysis document (Markdown)
- Ranking opportunities list (prioritized)
- Strategy for outranking competitors
- Quick wins identified

**Success metrics:**
- 3-5 competitors analyzed
- All competitor content extracted
- SEO metrics documented
- Content gaps identified
- Ranking opportunities ranked by difficulty
- Clear strategy documented

---

### 3. rankrentbiz-blog-calendar
**Purpose:** Create a strategic 24-article blog content calendar targeting long-tail keywords.

**When to use:** After competitive analysis, to plan content strategy

**Time:** 100 minutes per site

**Inputs Manus needs:**
- Niche name
- 16 target cities
- Competitive analysis results (from skill #2)
- Ranking opportunities identified

**What Manus should do:**
1. Identify 6 content pillars (thematic areas):
   - Each pillar should cover a different angle of the niche
   - Example: "Fire Safety & Prevention," "Technical & How-To," "Maintenance & Costs," etc.
2. Generate 24 article topics (4 per pillar):
   - Each topic targets a specific keyword
   - Topics address user intent
   - Topics support ranking goals
3. Perform keyword research for each article:
   - Primary keyword
   - Search volume (monthly searches)
   - Ranking difficulty (low/medium/high)
   - Related keywords (3-5 variations)
   - User intent (informational/problem-solution/comparison)
4. Create 6-month publishing schedule:
   - Month 1-2: 4 articles (Pillar 1)
   - Month 3-4: 4 articles (Pillar 2)
   - Month 5-6: 4 articles (Pillar 3)
   - Month 7-8: 4 articles (Pillar 4)
   - Month 9-10: 4 articles (Pillar 5)
   - Month 11-12: 4 articles (Pillar 6)
5. Create internal linking strategy:
   - 3-5 internal links per article
   - Links to location pages, pricing, services, other articles
6. Create SEO optimization checklist for each article:
   - Title tag (50-60 characters, includes keyword)
   - Meta description (150-160 characters, includes keyword)
   - H1 tag (includes primary keyword)
   - H2/H3 tags (includes related keywords)
   - Internal links (3-5)
   - External links (1-2 authority sources)
   - FAQ section (3-5 questions)
   - Schema markup (FAQPage schema)
   - Image alt text (includes keyword)
   - Word count (1,500-2,500 words)
   - Call-to-action (link to pricing or contact form)
7. Create blog calendar document with:
   - Executive summary
   - Content pillars
   - Article topics with keywords
   - Keyword research table
   - 6-month publishing schedule
   - Internal linking strategy
   - SEO optimization checklist
   - Traffic projections

**Deliverables:**
- Blog content calendar document (Markdown)
- 24 article topics with keywords
- 6-month publishing schedule
- Internal linking strategy
- SEO optimization checklist
- Traffic projections (estimated monthly impressions/clicks)

**Success metrics:**
- 6 content pillars identified
- 24 article topics generated
- Keyword research completed
- 6-month calendar created
- Internal linking strategy defined
- SEO checklist created
- Traffic projections estimated

---

### 4. rankrentbiz-citations-backlinks
**Purpose:** Build local authority through strategic citations and backlinks.

**When to use:** After site launch, to establish authority

**Time:** 90 minutes per site (planning phase; execution is 6 months)

**Inputs Manus needs:**
- Niche name
- 16 target cities
- Domain name
- Phone number
- Business description
- Service areas

**What Manus should do:**
1. Identify 50+ citation directories (Tier 1/2/3):
   - Tier 1 (High Authority): Google My Business, Apple Maps, Bing Places, Yelp, BBB, HomeAdvisor, Angi, Thumbtack, Houzz
   - Tier 2 (Medium Authority): Industry-specific directories, local business directories, regional directories
   - Tier 3 (Local Authority): Local chamber of commerce, local business associations, local review sites
2. Identify 20+ backlink opportunities (Tier 1/2/3):
   - Tier 1 (High Authority): Government sites, industry authority sites, educational institutions
   - Tier 2 (Medium Authority): Local news outlets, local business blogs, industry blogs
   - Tier 3 (Local Mentions): Local chamber of commerce, local business directories, local forums
3. Create citation submission checklist:
   - Pre-filled with all 50+ directories
   - Fields for: business name, address, phone, website, description, service areas, hours, categories, photos
   - Tracking columns: submission date, verification status, notes
4. Create 3 outreach email templates:
   - Cold outreach (for industry blogs/sites)
   - Guest post pitch (for blogs)
   - Resource link request (for directories/guides)
   - All with customizable [PLACEHOLDER] fields
5. Create 6-month execution timeline:
   - Month 1-2: Tier 1 citations (10 directories) + Tier 1 backlinks (3-5 links)
   - Month 3-4: Tier 2 citations (20 directories) + Tier 2 backlinks (8-10 links)
   - Month 5-6: Tier 3 citations (20 directories) + Tier 3 backlinks (5-7 links)
   - Expected results per phase documented
6. Create tracking spreadsheet:
   - Pre-filled with all 50+ citations and 20+ backlinks
   - Columns: name, tier, type, URL, submission date, verification date, status, notes, authority, relevance
   - Summary statistics (total citations, total backlinks, success rate)
7. Create citations & backlinks strategy document with:
   - Executive summary
   - Citation strategy (Tier 1/2/3 breakdown)
   - Backlink strategy (Tier 1/2/3 breakdown)
   - 6-month timeline
   - Citation submission checklist
   - Backlink opportunities
   - Outreach email templates
   - Tracking spreadsheet
   - Success metrics
   - Expected results (traffic/ranking impact)

**Deliverables:**
- Citations & backlinks strategy document (Markdown)
- 50+ citation directories (Tier 1/2/3)
- 20+ backlink opportunities (Tier 1/2/3)
- 6-month execution timeline
- Citation submission checklist (spreadsheet)
- 3 outreach email templates
- Tracking spreadsheet
- Success metrics defined

**Success metrics:**
- 50+ citation directories identified
- 20+ backlink opportunities identified
- Citation submission checklist created
- Outreach templates created
- 6-month timeline defined
- Tracking spreadsheet ready
- Strategy document written

---

### 5. rankrentbiz-gsc-setup
**Purpose:** Set up Google Search Console monitoring for rankings, impressions, and organic traffic.

**When to use:** After site launch and sitemaps are accessible

**Time:** 60 minutes per site

**Inputs Manus needs:**
- Domain name (e.g., lintguard.ca)
- Site URLs (for sitemaps)
- Google account access

**What Manus should do:**
1. Verify domain in Google Search Console:
   - Use DNS verification method (preferred for domains)
   - Add TXT record to Cloudflare DNS
   - Verify ownership
2. Submit all 4 sitemaps:
   - https://www.[domain]/sitemap.xml (master)
   - https://www.[domain]/sitemap-pages.xml
   - https://www.[domain]/sitemap-locations.xml
   - https://www.[domain]/sitemap-blog.xml
   - Document submission dates and status
3. Monitor Coverage report:
   - Note total pages indexed
   - Identify any errors or warnings
   - Document baseline metrics
4. Set up Performance tracking:
   - Record baseline metrics: impressions, clicks, CTR, average position
   - Create tracking spreadsheet for weekly (first month) and monthly (ongoing) tracking
5. Monitor keyword rankings:
   - Document top 20 keywords
   - Record baseline positions
   - Create tracking spreadsheet for weekly (first month) and monthly (ongoing) tracking
6. Check mobile usability:
   - Verify no errors or warnings
   - Document mobile-friendly status
7. Monitor Core Web Vitals:
   - Check LCP, FID, CLS status
   - Identify any performance issues
   - Document baseline metrics
8. Create monthly reporting checklist:
   - Coverage report review
   - Performance metrics review
   - Top 20 keywords review
   - Mobile usability check
   - Core Web Vitals check
   - New keywords appearing
   - Keywords dropping
   - Sitemaps status
   - Crawl stats
   - Security issues
9. Create GSC setup document with:
   - Domain verification confirmation
   - Sitemaps submitted (all 4)
   - Coverage report baseline
   - Performance metrics baseline
   - Keyword rankings baseline
   - Mobile usability status
   - Core Web Vitals baseline
   - Tracking spreadsheets
   - Monthly reporting checklist

**Deliverables:**
- Domain verified in GSC
- All 4 sitemaps submitted
- Coverage report baseline
- Performance tracking spreadsheet
- Keyword ranking tracking spreadsheet
- Mobile usability checked
- Core Web Vitals baseline
- Monthly reporting checklist
- GSC setup documentation

**Success metrics:**
- Domain verified in GSC
- All 4 sitemaps submitted successfully
- Coverage report reviewed
- Performance metrics recorded
- Top 20 keywords documented
- Mobile usability checked
- Core Web Vitals checked
- Baseline metrics established
- Monitoring schedule established

---

## Typical Workflow for Building One Site

### Phase 1: Scaffolding (75 minutes)
Use **rankrentbiz-site-scaffold**
- Create GitHub repo
- Scaffold Astro 6 + Tailwind 4 project
- Deploy to Cloudflare Pages
- Verify site is live

### Phase 2: Competitive Analysis (105 minutes)
Use **rankrentbiz-competitor-analysis**
- Analyze 3-5 top competitors
- Identify weaknesses and opportunities
- Create competitive analysis document
- Identify quick wins and ranking targets

### Phase 3: Content Strategy (100 minutes)
Use **rankrentbiz-blog-calendar**
- Create 6 content pillars
- Generate 24 article topics
- Perform keyword research
- Create 6-month publishing schedule
- Plan internal linking strategy

### Phase 4: Authority Building (90 minutes)
Use **rankrentbiz-citations-backlinks**
- Identify 50+ citation directories
- Identify 20+ backlink opportunities
- Create submission checklist
- Create outreach templates
- Create 6-month execution timeline

### Phase 5: Monitoring Setup (60 minutes)
Use **rankrentbiz-gsc-setup**
- Verify domain in GSC
- Submit all 4 sitemaps
- Set up performance tracking
- Create monitoring checklist
- Establish baseline metrics

**Total time:** ~430 minutes (~7 hours) per site

---

## Integration with Manus Tasks

When creating a new task for a site build, Manus should:

1. **Read the project instructions** (BLUEPRINT.md, CLUSTER_STRATEGY.md, etc.)
2. **Identify which skill to use** based on the current phase
3. **Gather the required inputs** from the user or project context
4. **Execute the skill** step-by-step
5. **Deliver the outputs** (documents, spreadsheets, configurations)
6. **Update the project checkpoint** with completed work

### Example Task Structure

```markdown
## Task: Build Backflow Prevention Site (Phase 1: Scaffolding)

### Objective
Use rankrentbiz-site-scaffold to create a new Astro 6 + Tailwind 4 site for Backflow Prevention Testing.

### Inputs
- Niche: Backflow Prevention Testing
- Cities: Toronto, Mississauga, Brampton, Markham, Vaughan, Whitby, Ajax, Pickering, Oshawa, Milton, Oakville, Burlington, Newmarket, Barrie, Cambridge, Guelph
- Colors: Primary #003d82, Secondary #2196f3, Accent #fbbf24
- Phone: (647) 555-0182
- Domain: backflow-gta.ca
- GitHub: backflow-gta

### Deliverables
- GitHub repository created and code pushed
- Site live on Cloudflare Pages
- All pages loading correctly
- Sitemaps created and accessible

### Next Steps
After completion, proceed to Phase 2: rankrentbiz-competitor-analysis
```

---

## Key Principles

### 1. Sequential Execution
Skills should be used in order:
1. Scaffold → 2. Analyze → 3. Plan → 4. Build Authority → 5. Monitor

Skipping phases will result in incomplete or lower-quality work.

### 2. Standardized Inputs
Each skill requires specific inputs. Manus should:
- Gather all inputs before starting
- Validate inputs are correct format
- Ask user for clarification if inputs are missing

### 3. Quality Verification
After each skill, Manus should:
- Verify all deliverables are created
- Check quality against success metrics
- Document any issues or blockers
- Ask user for feedback before proceeding

### 4. Documentation
All outputs should be:
- Well-formatted (Markdown, spreadsheets, etc.)
- Professionally written
- Ready for reference during execution
- Saved to project folder or GitHub

### 5. Reusability
Each skill is designed to be:
- Independent (can be used standalone)
- Repeatable (same process for all sites)
- Customizable (adapt to specific niches)
- Scalable (same process for 30 sites)

---

## Troubleshooting

### Skill not producing expected output
- Re-read the skill's SKILL.md file
- Verify all inputs are provided
- Check the "Common Issues & Solutions" section in the skill
- Ask user for clarification on requirements

### Competitor analysis shows no opportunities
- Expand search to more competitors
- Look for different keyword angles
- Consider long-tail variations
- Check if niche is too saturated

### Blog calendar seems repetitive
- Vary content types (how-to, problem-solution, comparison, listicle)
- Use different angles for similar topics
- Include local variations for each city
- Add seasonal or trending topics

### Sitemaps not submitting to GSC
- Verify sitemaps are accessible at the URLs
- Check XML format is valid
- Ensure domain is verified first
- Try submitting one at a time
- Wait 24-48 hours for DNS propagation

---

## Success Metrics for Portfolio

After using all 5 skills for one site:

- ✅ Site scaffolded and live
- ✅ Competitive analysis completed
- ✅ Content strategy planned (24 articles)
- ✅ Authority building strategy created
- ✅ Monitoring setup and baseline metrics recorded

**Expected timeline:** 7 hours per site  
**Expected sites per week:** 1-2 sites (with execution time)  
**Expected portfolio completion:** 15-30 weeks for 30 sites

---

## Questions & Support

For questions about how to use these skills:
1. Check the skill's SKILL.md file
2. Review the "Common Issues & Solutions" section
3. Refer to the RankRentBiz BLUEPRINT.md
4. Check the project's TASK_ORGANIZATION_GUIDE.md

---

**Built with ❤️ for scaling the RankRentBiz portfolio**
