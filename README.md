# Red Door Painting Pros — Landing Pages

Professional landing pages for Red Door Painting Pros (reddoorpaintingpros.com). Built for conversion, SEO-optimized, and ready for deployment.

## Pages Included

| Page | Purpose | Target Keywords |
|------|---------|-----------------|
| `commercial.html` | B2B/HOA lead gen | commercial painting Tucson, HOA painting contractor |
| `marana.html` | Local SEO | house painters Marana, painting contractors Marana |
| `oro-valley.html` | Local SEO + seniors | house painters Oro Valley, senior painting services |
| `vail.html` | Local SEO | house painters Vail AZ |
| `green-valley.html` | Local SEO + seniors | house painters Green Valley, senior discounts |
| `sahuarita.html` | Local SEO | house painters Sahuarita, Rancho Sahuarita |
| `cabinet-painting.html` | Niche service | kitchen cabinet painting Tucson, cabinet refinishing |

## Email Sequences

`email-sequences.md` contains:
- Estimate follow-up sequence (4 emails)
- Reactivation campaign (Day 14, 30, 90)
- Missed call auto-text template

## Deployment Options

### Option 1: WordPress Pages
1. Create new pages in WordPress
2. Copy HTML content (strip `<html>`, `<head>`, `<body>` tags)
3. Use full-width template, no sidebar
4. Add custom CSS to theme or page

### Option 2: Standalone Landing Pages
1. Upload HTML files to hosting
2. Point subdomains (e.g., `commercial.reddoorpaintingpros.com`)
3. Or use as page templates in existing site

### Option 3: Unbounce/Leadpages
1. Use HTML/CSS as reference
2. Recreate in landing page builder
3. Connect forms to GoHighLevel

## Form Integration

All CTA buttons should link to:
- Primary: GoHighLevel appointment scheduler
- Secondary: Contact form with UTM tracking

**UTM Parameters to Add:**
```
?utm_source=landing-page&utm_campaign=[page-name]&utm_content=cta-button
```

## Customization Needed

Before deploying:

1. **Replace placeholder images** with actual project photos
2. **Add license number** to footer (ROC # [License Number])
3. **Verify phone number** (currently 520-500-3791)
4. **Add scheduling link** to all CTA buttons
5. **Update testimonials** with real customer names/locations
6. **Add actual project photos** for before/after sections

## SEO Checklist

- [ ] Title tags optimized (under 60 chars)
- [ ] Meta descriptions added (under 160 chars)
- [ ] H1 tags present and unique per page
- [ ] Local keywords in content
- [ ] Phone number clickable (`tel:` link)
- [ ] Schema markup for LocalBusiness
- [ ] Google Analytics tracking
- [ ] Google Search Console verification

## Google Ads Integration

For landing pages used in Google Ads campaigns:

1. Ensure fast load times (< 3 seconds)
2. Add conversion tracking pixel
3. Match ad copy to landing page headline
4. Use consistent CTAs
5. Add trust signals (reviews, licenses, insurance)

## Analytics Tracking

Add to `<head>` of each page:
```html
<!-- Google Tag Manager -->
<!-- Google Analytics 4 -->
<!-- Facebook Pixel (if running FB ads) -->
```

## Contact

**Red Door Painting Pros**  
Joel  
📞 520-500-3791  
🌐 reddoorpaintingpros.com

---

*Built for Blaine Wilson / Overdrafter*  
*Repo: github.com/optomachina/reddoor-landing-pages*
