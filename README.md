# RankRentBiz Skills Repository

A collection of 5 reusable Manus skills for building and scaling the RankRentBiz 30-site portfolio.

## Overview

These skills automate the core workflows for creating, optimizing, and monitoring Rank & Rent lead generation sites targeting the Greater Toronto Area (GTA) and surrounding Ontario cities.

## Skills Included

### 1. rankrentbiz-site-scaffold
Quickly scaffold new Astro 6 + Tailwind 4 sites with all standard components, pages, and configuration.

**Time saved:** 75 minutes per site  
**Use for:** Creating new RankRentBiz sites, setting up GitHub repos, deploying to Cloudflare Pages

**Deliverables:**
- Complete Astro 6 + Tailwind 4 project structure
- Standard components (Hero, FAQ, Pricing, ContactForm, Footer)
- All pages (homepage, locations, pricing, services)
- 4 sitemaps (pages, locations, blog, master)
- GitHub repository setup
- Cloudflare Pages deployment configuration

---

### 2. rankrentbiz-competitor-analysis
Analyze top competitors to identify ranking opportunities and content gaps.

**Time saved:** 105 minutes per site  
**Use for:** Competitive analysis, weakness identification, ranking opportunity mapping, content gap analysis

**Deliverables:**
- Competitor overview (DA, traffic, keywords)
- SEO metrics comparison
- Content analysis (pages, blog, schema markup)
- Weakness identification
- Ranking opportunities (quick wins, medium-term, long-term)
- Recommended outranking strategy

---

### 3. rankrentbiz-blog-calendar
Create strategic 24-article blog content calendars targeting long-tail keywords.

**Time saved:** 100 minutes per site  
**Use for:** Blog planning, keyword research, content calendar creation, internal linking strategy

**Deliverables:**
- 6 content pillars (4 articles each)
- 24 article topics with keyword research
- 6-month publishing schedule
- Internal linking strategy (3-5 links per article)
- SEO optimization checklist
- Traffic projections

---

### 4. rankrentbiz-citations-backlinks
Build local authority through strategic citations and backlinks.

**Time saved:** 90 minutes per site (planning phase)  
**Use for:** Citation directory identification, backlink opportunity mapping, outreach planning, 6-month authority building strategy

**Deliverables:**
- 50+ citation directories (Tier 1/2/3)
- 20+ backlink opportunities (Tier 1/2/3)
- Citation submission checklist
- 3 outreach email templates
- 6-month execution timeline
- Tracking spreadsheet

---

### 5. rankrentbiz-gsc-setup
Set up Google Search Console monitoring for rankings, impressions, and organic traffic.

**Time saved:** 60 minutes per site  
**Use for:** GSC verification, sitemap submission, ranking tracking, performance monitoring, monthly reporting

**Deliverables:**
- Domain verification instructions
- Sitemap submission checklist (4 sitemaps)
- Performance tracking spreadsheet
- Keyword ranking monitoring template
- Mobile usability check
- Core Web Vitals monitoring
- Monthly reporting checklist

---

## Installation

### Option 1: Import into Manus Skills Folder (Recommended)

```bash
# Clone this repository
git clone https://github.com/jaysonn47/rankrentbiz-skills.git

# Copy skills to your Manus skills directory
cp -r rankrentbiz-skills/* ~/.manus/skills/

# Verify installation
ls ~/.manus/skills/rankrentbiz-*
```

### Option 2: Copy to Project Folder

```bash
# Clone this repository
git clone https://github.com/jaysonn47/rankrentbiz-skills.git

# Copy to your project folder
cp -r rankrentbiz-skills/* /path/to/your/project/SKILLS/

# Update project instructions to reference the skills
```

### Option 3: Use as Git Submodule

```bash
# Add as submodule to your project
cd /path/to/your/project
git submodule add https://github.com/jaysonn47/rankrentbiz-skills.git SKILLS

# Update submodule
git submodule update --remote
```

---

## Usage

Each skill is self-contained and can be used independently or as part of a complete workflow.

### Typical Workflow for New Site

1. **rankrentbiz-site-scaffold** — Create new site structure (75 min)
2. **rankrentbiz-competitor-analysis** — Analyze competitors (105 min)
3. **rankrentbiz-blog-calendar** — Plan content strategy (100 min)
4. **rankrentbiz-citations-backlinks** — Plan authority building (90 min)
5. **rankrentbiz-gsc-setup** — Set up monitoring (60 min)

**Total planning time:** ~430 minutes (~7 hours) per site

---

## File Structure

```
rankrentbiz-skills/
├── rankrentbiz-site-scaffold/
│   ├── SKILL.md
│   ├── scripts/
│   ├── references/
│   └── templates/
├── rankrentbiz-competitor-analysis/
│   ├── SKILL.md
│   ├── scripts/
│   ├── references/
│   └── templates/
├── rankrentbiz-blog-calendar/
│   ├── SKILL.md
│   ├── scripts/
│   ├── references/
│   └── templates/
├── rankrentbiz-citations-backlinks/
│   ├── SKILL.md
│   ├── scripts/
│   ├── references/
│   └── templates/
├── rankrentbiz-gsc-setup/
│   ├── SKILL.md
│   ├── scripts/
│   ├── references/
│   └── templates/
└── README.md
```

---

## Requirements

- Manus account with skill support
- GitHub account (for version control)
- Cloudflare account (for hosting)
- Google account (for Search Console)
- Firecrawl MCP access (for competitor analysis)

---

## Integration with RankRentBiz Project

These skills are designed to work with the main RankRentBiz project. To integrate:

1. **Copy to project folder:**
   ```bash
   cp -r rankrentbiz-skills/* /home/ubuntu/projects/rankrentbiz-1951e3b6/SKILLS/
   ```

2. **Update project instructions:**
   Add to your project's README:
   ```markdown
   ## Available Skills
   - rankrentbiz-site-scaffold
   - rankrentbiz-competitor-analysis
   - rankrentbiz-blog-calendar
   - rankrentbiz-citations-backlinks
   - rankrentbiz-gsc-setup
   ```

3. **Reference in tasks:**
   When creating a new task, reference the skill:
   ```
   Use skill: rankrentbiz-site-scaffold
   Input: niche name, 16 target cities, color scheme
   ```

---

## Documentation

Each skill includes detailed instructions in its SKILL.md file:

- **Overview:** What the skill does and when to use it
- **Prerequisites:** What you need before starting
- **Step-by-step process:** Detailed instructions for each phase
- **Expected outputs:** What you'll have when complete
- **Quality checklist:** Verification steps
- **Common issues:** Troubleshooting guide
- **Time breakdown:** Effort estimation

---

## Contributing

To improve these skills:

1. Test the skill on a real project
2. Document any issues or improvements
3. Submit a pull request with changes
4. Update the SKILL.md with new insights

---

## License

These skills are part of the RankRentBiz project and follow the same license terms.

---

## Support

For questions or issues:

1. Check the skill's SKILL.md file for detailed instructions
2. Review the "Common Issues & Solutions" section
3. Refer to the main RankRentBiz project documentation
4. Open an issue on GitHub

---

## Related Resources

- **BLUEPRINT.md** — Master methodology and tech stack
- **NICHE_EVALUATION_FRAMEWORK.md** — Niche viability scoring
- **CLUSTER_STRATEGY.md** — 6-cluster portfolio strategy
- **GTM_STRATEGY.md** — Go-to-market and monetization
- **PRIORITY_FRAMEWORK.md** — Timeline and execution priorities

---

## Version History

- **v1.0** (May 8, 2026) — Initial release with 5 core skills
  - rankrentbiz-site-scaffold
  - rankrentbiz-competitor-analysis
  - rankrentbiz-blog-calendar
  - rankrentbiz-citations-backlinks
  - rankrentbiz-gsc-setup

---

## Quick Start

To get started immediately:

```bash
# 1. Clone the repository
git clone https://github.com/jaysonn47/rankrentbiz-skills.git
cd rankrentbiz-skills

# 2. Copy to your Manus skills folder
cp -r rankrentbiz-* ~/.manus/skills/

# 3. Verify installation
ls ~/.manus/skills/rankrentbiz-*

# 4. Start using the skills in your Manus tasks!
```

---

**Built with ❤️ for the RankRentBiz portfolio**
