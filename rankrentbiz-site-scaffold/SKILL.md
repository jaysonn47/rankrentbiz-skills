---
name: rankrentbiz-site-scaffold
description: "Quickly scaffold new Astro 6 + Tailwind 4 sites with all standard components, pages, and configuration. Use for creating new RankRentBiz sites, setting up GitHub repos, deploying to Cloudflare Pages."
---

---

---

---
name: rankrentbiz-site-scaffold
description: Quickly scaffold new Astro 6 + Tailwind 4 sites with all standard components, pages, and configuration. Use for: creating new RankRentBiz sites, setting up GitHub repos, deploying to Cloudflare Pages.
---

# Skill: rankrentbiz-site-scaffold

## Overview
Quickly scaffold a new RankRentBiz site (Astro 6 + Tailwind 4) with all standard components, pages, and configuration ready for customization.

**Time Saved:** 2-3 hours per site
**Complexity:** Medium
**Repeatable:** Yes (for all 30 sites)

---

## What This Skill Does

Creates a production-ready Astro project with:
- ✅ Astro 6 + Tailwind 4 setup
- ✅ Standard page structure (homepage, locations hub, pricing, services)
- ✅ Standard components (Hero, FAQ, Pricing, ContactForm, Footer)
- ✅ Comprehensive schema markup (LocalBusiness, FAQPage, BreadcrumbList)
- ✅ 4 sitemaps (pages, locations, blog, master)
- ✅ robots.txt
- ✅ GitHub repo creation
- ✅ Cloudflare Pages deployment config

---

## Prerequisites

Before using this skill, you need:
- [ ] Niche name (e.g., "Backflow Prevention Testing")
- [ ] 16 target cities (e.g., Toronto, Mississauga, Brampton, etc.)
- [ ] Color scheme (use COLOR_SCHEMES.md for pre-designed options)
- [ ] GitHub account (jaysonn47)
- [ ] Cloudflare account

---

## Step-by-Step Process

### Step 1: Prepare Inputs (5 minutes)

**Gather the following information:**

```
Niche Name: [e.g., "Backflow Prevention Testing"]
Niche Description: [e.g., "Annual mandatory compliance testing for commercial properties"]
Service Areas: [16 cities, comma-separated]
Primary Color: [Hex code, e.g., #003d82]
Secondary Color: [Hex code, e.g., #2196f3]
Accent Color: [Hex code, e.g., #fbbf24]
Phone Number: [Format: (XXX) XXX-XXXX]
Domain: [e.g., lintguard.ca]
GitHub Repo Name: [Format: [niche]-gta, e.g., backflow-gta]
```

**Example:**
```
Niche Name: Backflow Prevention Testing
Niche Description: Annual mandatory compliance testing for commercial properties
Service Areas: Toronto, Mississauga, Brampton, Markham, Vaughan, Whitby, Ajax, Pickering, Oshawa, Milton, Oakville, Burlington, Newmarket, Barrie, Cambridge, Guelph
Primary Color: #003d82
Secondary Color: #2196f3
Accent Color: #fbbf24
Phone Number: (647) 555-0182
Domain: backflow-gta.ca
GitHub Repo Name: backflow-gta
```

---

### Step 2: Create GitHub Repository (10 minutes)

**Request to Manus Agent:**
"Create a private GitHub repository named `[repo-name]` under jaysonn47"

**What happens:**
- GitHub repo created (private)
- README.md initialized
- .gitignore configured

---

### Step 3: Scaffold Astro Project (15 minutes)

**Request to Manus Agent:**
"Scaffold an Astro 6 + Tailwind 4 project with the following structure:
- astro.config.mjs (with Tailwind integration)
- tailwind.config.mjs (with custom color scheme)
- package.json (with dependencies)
- src/layouts/BaseLayout.astro
- src/components/ (Hero, FAQ, Pricing, ContactForm, Footer, etc.)
- src/pages/index.astro (homepage template)
- public/robots.txt
- public/sitemap.xml (master sitemap)"

**What you'll receive:**
- Complete Astro project structure
- All components scaffolded
- Tailwind configured with your colors
- Ready to customize

---

### Step 4: Create Location Pages Template (10 minutes)

**Request to Manus Agent:**
"Create a dynamic location page template (src/pages/locations/[city].astro) that generates pages for all 16 cities with:
- City-specific H1 and title tags
- LocalBusiness schema per city
- Unique local content
- Internal linking to homepage and pricing"

**What you'll receive:**
- Dynamic location page template
- 16 city pages generated automatically
- Schema markup per city
- Ready for customization

---

### Step 5: Create Additional Pages (10 minutes)

**Request to Manus Agent:**
"Create the following pages:
- src/pages/pricing.astro (transparent pricing with 3 tiers)
- src/pages/services/[service].astro (service detail pages)
- src/pages/locations.astro (locations hub)
- src/pages/thank-you.astro (form submission thank you)"

**What you'll receive:**
- All pages scaffolded
- Pricing page with schema markup
- Service pages template
- Thank you page

---

### Step 6: Create Sitemaps (10 minutes)

**Request to Manus Agent:**
"Create 4 sitemaps:
- public/sitemap.xml (master, lists all other sitemaps)
- public/sitemap-pages.xml (static pages)
- public/sitemap-locations.xml (all 16 city pages)
- public/sitemap-blog.xml (template for future blog articles)"

**What you'll receive:**
- All 4 sitemaps created
- Proper XML structure
- Ready for Google Search Console

---

### Step 7: Configure Cloudflare Pages (5 minutes)

**Request to Manus Agent:**
"Configure for Cloudflare Pages deployment:
- Set build command: pnpm run build
- Set output directory: dist
- Create wrangler.toml (if needed)
- Verify build succeeds locally"

**What you'll receive:**
- Build configuration ready
- Deployment checklist
- Local build verification

---

### Step 8: Push to GitHub & Deploy (10 minutes)

**Request to Manus Agent:**
"Push the project to GitHub and deploy to Cloudflare Pages:
- git add -A
- git commit -m 'Initial: Astro 6 + Tailwind 4 scaffold'
- git push origin main
- Connect GitHub repo to Cloudflare Pages
- Verify live deployment"

**What you'll receive:**
- Project on GitHub
- Site deployed to Cloudflare Pages
- Live URL (https://[repo-name].pages.dev)

---

## Expected Outputs

After completing this skill, you'll have:

### GitHub Repository
- ✅ Private repo with full project code
- ✅ All components scaffolded
- ✅ All pages created
- ✅ Sitemaps configured
- ✅ Ready for customization

### Live Site
- ✅ Deployed to Cloudflare Pages
- ✅ Live URL (https://[repo-name].pages.dev)
- ✅ Custom domain ready (configure in Cloudflare)
- ✅ SSL certificate auto-enabled

### Documentation
- ✅ README.md with setup instructions
- ✅ Component documentation
- ✅ Deployment checklist

---

## Customization Checklist

After scaffolding, customize:

- [ ] Homepage copy (H1, subheading, CTA)
- [ ] Color scheme (verify in all components)
- [ ] Phone number (verify in all CTAs)
- [ ] Service descriptions
- [ ] FAQ questions (expand from template)
- [ ] Pricing details
- [ ] Location page content (add local details)
- [ ] Hero image (generate or upload)
- [ ] Schema markup (verify all pages)

---

## Quality Checklist

Before moving to next skill:

- [ ] All pages load without errors
- [ ] Responsive design works on mobile/tablet/desktop
- [ ] All links work (internal and external)
- [ ] Schema markup validates (use schema.org validator)
- [ ] Sitemaps are valid XML
- [ ] robots.txt is correct
- [ ] Build completes without warnings
- [ ] Site is live on Cloudflare Pages

---

## Common Issues & Solutions

### Issue: Build fails with Tailwind errors
**Solution:** Verify tailwind.config.mjs is correctly configured with @theme block

### Issue: Schema markup not showing
**Solution:** Verify schema is in <head> section and uses proper JSON-LD format

### Issue: Location pages not generating
**Solution:** Verify [city].astro uses getStaticPaths() for dynamic routing

### Issue: Sitemaps not found
**Solution:** Verify sitemaps are in public/ directory and robots.txt points to correct URL

---

## Time Breakdown

| Step | Time | Notes |
|------|------|-------|
| Prepare inputs | 5 min | Gather niche info, colors, cities |
| Create GitHub repo | 10 min | Private repo setup |
| Scaffold Astro | 15 min | Project structure + components |
| Location pages | 10 min | Dynamic template for 16 cities |
| Additional pages | 10 min | Pricing, services, thank you |
| Sitemaps | 10 min | 4 sitemaps created |
| Cloudflare config | 5 min | Build settings configured |
| Push & deploy | 10 min | GitHub + Cloudflare deployment |
| **TOTAL** | **75 min** | **~1.25 hours** |

---

## Next Skills in Workflow

After completing this skill, proceed to:
1. **rankrentbiz-competitor-analysis** — Analyze top competitors
2. **rankrentbiz-blog-calendar** — Create 24-article content calendar
3. **rankrentbiz-citations-backlinks** — Build authority strategy
4. **rankrentbiz-gsc-setup** — Set up monitoring

---

## Success Metrics

After this skill:
- ✅ GitHub repo created and code pushed
- ✅ Site live on Cloudflare Pages
- ✅ All pages loading correctly
- ✅ Schema markup valid
- ✅ Sitemaps created
- ✅ Ready for content customization

---

## Notes

- This skill creates the **foundation** for all other skills
- Customization happens **after** scaffolding
- Each site uses the **same stack** (Astro 6 + Tailwind 4)
- Consistency across all 30 sites is maintained
- This skill is **repeatable** for every new site

---

## Questions?

Refer to:
- BLUEPRINT.md (master methodology)
- CLUSTER_STRATEGY.md (cluster building)
- COLOR_SCHEMES.md (color palette options)
