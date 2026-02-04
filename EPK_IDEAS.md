# Jared Eisenhauer EPK - Improvement Ideas

A prioritized list of enhancement ideas for the Electronic Press Kit website.

---

## HIGH PRIORITY - Features That Will Directly Help Get Bookings

### 1. Upcoming Shows / Events Calendar
**Impact: High | Effort: Medium**

Add a section displaying upcoming performances. This shows bookers that Jared is actively performing and creates urgency for fans.

- Display next 3-5 upcoming shows with date, venue, and ticket links
- Include a "No shows scheduled? Book me!" call-to-action when calendar is empty
- Consider integrating with Bandsintown or Songkick API for automatic updates

### 2. Audio Player / Music Samples
**Impact: High | Effort: Medium**

Venue bookers want to hear the music quickly without navigating to external sites.

- Embed a Spotify player with top tracks
- Or create a custom audio player with 30-60 second samples of original songs
- Include a mix of styles to showcase versatility (ballad, upbeat, etc.)
- Add a "Listen on Spotify/Apple Music" prominent button in the hero or about section

### 3. Testimonials Section
**Impact: High | Effort: Low**

Social proof is critical for booking decisions.

- Collect quotes from venue owners, event planners, and wedding clients
- Display 3-5 rotating testimonials with names, roles, and photos if available
- Include star ratings if applicable
- Place strategically after the About section to build credibility early

### 4. Downloadable Press Kit / One-Sheet
**Impact: High | Effort: Low**

Many bookers need materials for their own promotional purposes.

- Create a downloadable PDF one-sheet with:
  - Professional headshot
  - Bio (short and long versions)
  - Genre/style description
  - Technical requirements
  - Contact information
  - Social media stats
- Add prominent "Download Press Kit" button in hero or about section

### 5. Performance Configuration Options
**Impact: High | Effort: Low**

The Services section shows event types but not performance formats.

- Add a section showing available configurations:
  - Solo acoustic
  - Duo (guitar + vocals, or with another musician)
  - Full band (specify instruments)
- Include pricing tiers or "starting at" ranges (optional but helpful)
- Specify typical set lengths (1 hour, 2 hours, full evening, etc.)

---

## MEDIUM PRIORITY - Visual & UX Enhancements

### 6. Hero Section Video Background
**Impact: Medium | Effort: Medium**

Replace static hero image with a subtle looping video clip of a live performance.

- Muted by default, short loop (10-15 seconds)
- Falls back to static image on mobile for performance
- Creates immediate emotional impact and shows Jared in action

### 7. Lightbox Gallery with Captions
**Impact: Medium | Effort: Low**

Clicking gallery photos should open a full-screen lightbox.

- Add high-resolution viewing capability
- Include captions with venue names and dates
- Add download buttons for press use
- Implement keyboard navigation (arrows, escape)

### 8. Parallax Scrolling Effects
**Impact: Medium | Effort: Medium**

Add subtle parallax effects to create depth and visual interest.

- Hero background subtle parallax
- Section backgrounds with slight movement
- Keep effects subtle to avoid motion sickness issues

### 9. Animated Statistics Counter
**Impact: Medium | Effort: Low**

Add an impressive "by the numbers" section with animated counters.

- Years performing
- Number of shows played
- Songs written
- Happy clients/events
- Social media followers combined

### 10. Improved Video Section
**Impact: Medium | Effort: Low**

The current video carousel could be enhanced.

- Add video titles/descriptions to all thumbnails (currently some just say "Video")
- Include a "Featured" or latest video that auto-displays larger
- Add category filters (Live performances, Music videos, Covers)
- Consider adding audio waveform visualizations

### 11. Dark Mode Toggle
**Impact: Low | Effort: Medium**

Some users prefer dark interfaces, especially at night.

- Add a subtle toggle in the navigation
- Remember preference in localStorage
- Dark theme already partially implemented in some sections

---

## CONTENT & COPY IMPROVEMENTS

### 12. Expanded About Section
**Impact: Medium | Effort: Low**

The bio is good but could be more compelling for bookers.

- Add a separate "For Event Planners" paragraph addressing their needs directly
- Mention reliability, professionalism, punctuality
- Include a line about being easy to work with
- Add genres covered for covers/requests

### 13. FAQ Section
**Impact: Medium | Effort: Low**

Answer common questions before they're asked.

- How far in advance should I book?
- What equipment do you bring vs. what do I need to provide?
- Do you learn special requests/first dance songs?
- What's your cancellation policy?
- Do you MC or make announcements?

### 14. Stage Plot / Technical Requirements
**Impact: Medium | Effort: Low**

Professional venues need this information.

- Visual stage plot diagram
- Input list
- Power requirements
- Minimum stage size
- Sound system requirements or "can provide own PA"

### 15. Song List / Repertoire
**Impact: Medium | Effort: Low**

Especially important for weddings and corporate events.

- List of original songs
- Cover song repertoire organized by decade/genre
- Note about learning special requests
- Could be a downloadable PDF or accordion-style section

---

## TECHNICAL & PERFORMANCE

### 16. Form Validation & UX
**Impact: Medium | Effort: Low**

The contact form needs attention.

- Replace "YOUR_FORM_ID" placeholder with actual Formspree ID
- Add client-side validation with helpful error messages
- Add success message/confirmation page after submission
- Add loading state to submit button
- Consider adding CAPTCHA to prevent spam

### 17. SEO Enhancements
**Impact: Medium | Effort: Low**

Improve discoverability in search results.

- Add structured data (Schema.org MusicGroup markup)
- Add more specific meta descriptions per section
- Add alt text to all images (some are generic)
- Create a sitemap.xml
- Add canonical URLs

### 18. Performance Optimization
**Impact: Medium | Effort: Medium**

Ensure fast loading especially on mobile.

- Lazy load images below the fold
- Optimize image sizes and use WebP format
- Preload hero image
- Minify CSS and inline critical styles
- Add service worker for offline capability

### 19. Analytics Integration
**Impact: Medium | Effort: Low**

Track what's working and what isn't.

- Add Google Analytics or privacy-friendly alternative (Plausible, Fathom)
- Set up conversion tracking on form submissions
- Track outbound clicks to streaming platforms
- Use UTM parameters for marketing campaigns

---

## NICE-TO-HAVE / FUTURE ENHANCEMENTS

### 20. Blog / News Section
**Impact: Low | Effort: High**

Keep the site fresh and improve SEO.

- Announce new music releases
- Share behind-the-scenes content
- Post show recaps with photos

### 21. Newsletter Signup
**Impact: Low | Effort: Low**

Build a direct audience.

- Simple email capture in footer or as a popup
- Offer incentive (free download, exclusive content)
- Integrate with Mailchimp or similar

### 22. Merch Store Integration
**Impact: Low | Effort: Medium**

If merchandise is available, add a link or embedded store.

- Link to Bandcamp for music/merch
- Or embed a simple Shopify/BigCommerce widget

### 23. Social Media Feed
**Impact: Low | Effort: Medium**

Show recent activity and keep content fresh.

- Embed Instagram feed in footer or dedicated section
- Shows visitors the artist is active and engaged

### 24. Multi-language Support
**Impact: Low | Effort: High**

If targeting international markets or diverse local communities.

- Add language toggle
- Translate key content to Spanish or other relevant languages

### 25. Accessibility Improvements
**Impact: Medium | Effort: Medium**

Ensure everyone can access the content.

- Add skip-to-content link
- Ensure all interactive elements are keyboard accessible
- Add ARIA labels where needed
- Test with screen reader
- Ensure sufficient color contrast ratios
- Add focus indicators for keyboard navigation

---

## QUICK WINS (Can Be Done Immediately)

1. **Add actual titles to all video thumbnails** - Some just say "Video"
2. **Fix the Formspree form ID placeholder** - Currently non-functional
3. **Add more descriptive alt text to gallery images**
4. **Update copyright year to be dynamic** - Currently hardcoded to 2025
5. **Add a favicon** - Already referenced but verify it exists
6. **Add Open Graph image** - For better social media sharing
7. **Add phone number to contact page** - Currently only email
8. **Social links in footer on contact page are incomplete** - Missing some platforms compared to index.html

---

## DESIGN REFINEMENTS

### Color & Typography
- The gold accent color (#d4af37) works well but could use a secondary accent for variety
- Consider adding subtle gradient text effects for headings
- The noise overlay is a nice touch - could be slightly more pronounced

### Layout
- Add more whitespace between sections on mobile
- Consider a sticky "Book Now" button on mobile that appears after scrolling past hero
- The influences section could be interactive - clicking an artist could show how they influenced Jared's sound

### Micro-interactions
- Add hover state sound preview on audio player (when implemented)
- Add subtle loading animations between page transitions
- Add cursor effects on hover (subtle glow or custom cursor)

---

## SUMMARY - TOP 5 PRIORITIES

1. **Testimonials Section** - Quick to implement, high impact for building trust
2. **Audio Player** - Critical for bookers who want to hear the music immediately
3. **Downloadable Press Kit PDF** - Professional expectation, easy to create
4. **Fix Contact Form** - Currently broken (placeholder Formspree ID)
5. **Upcoming Shows Calendar** - Shows activity and creates booking urgency

---

*Document created: February 2026*
*Last updated: February 4, 2026*
