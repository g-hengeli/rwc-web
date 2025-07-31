# Rough Water Cup V - Website Product Requirements Document (PRD)

## Overview

Create a modern, visually impactful promotional website for the Rough Water Cup V golf tournament. The website should focus on clarity, engagement, and ease of use, showcasing event details, history, photos, and sponsorship opportunities.

---

## Feature: Dynamic Landing Page

**Goal:** Eye-catching homepage with essential event info and strong branding.

**Details:**

* Event Name: **Rough Water Cup V**
* Date: **November 17, 2025**
* Location: **Flintrock Falls**
* Hero Image: Full-width, modern minimalist golf course image
* Branding: Use `rwc-logo_transparent.svg` and tagline: "Rough Water Cup V"
* Animation: Smooth load animation, responsive layout, optional parallax effects
* CTA Button: **"View Details"** (scroll to event section)

**User Stories:**

* As a first-time visitor, I want to see a striking image and clear event details.
* As a returning player/spectator, I want to quickly find the date and location.

---

## Feature: Event Details Section

**Goal:** Present key tournament details clearly.

**Details:**

* Show event name, date, and location
* Add "Add to Calendar" links (Google/Apple/iCal)
* Embed Google Map of Flintrock Falls
* Countdown timer to event date

**User Stories:**

* As a prospective attendee, I want to save the event to my calendar.
* As a sponsor or participant, I want the exact location and date easily accessible.

---

## Feature: Past Results Archive

**Goal:** Share history and credibility through past results.

**Details:**

* List tournaments RWC I–IV
* For each year:

  * Champion name(s)
  * Final scores
  * Trophy or player photo
  * Short summary/highlights
* Expand/collapse UI for each year

**User Stories:**

* As a visitor, I want to see past winners and scores to understand the event’s prestige.

---

## Feature: Photo Gallery

**Goal:** Provide a visual archive of the tournament’s highlights.

**Details:**

* Responsive grid layout
* Filter by year (RWC I–IV)
* Modal/lightbox for larger view
* Upload interface for admin

**User Stories:**

* As a past participant, I want to relive and share memories.
* As a sponsor, I want to see the event’s production quality.

---

## Feature: Sponsorship Page

**Goal:** Encourage and enable new sponsorships.

**Details:**

* Overview of tiers (Gold, Silver, Bronze)
* List benefits per tier (logo, hole sponsorship, marketing)
* Inquiry form or CTA button
* Carousel of existing/past sponsors with logos

**User Stories:**

* As a business owner, I want to evaluate sponsorship value and express interest easily.

---

## Feature: Navigation & Site Structure

**Goal:** Provide seamless access across sections.

**Details:**

* Sticky top nav bar
* Menu items: Home, Event Info, Past Results, Gallery, Sponsors, Contact
* Smooth scrolling to each section
* Mobile-responsive hamburger menu

---

## Feature: Admin Content Management (MVP+)

**Goal:** Allow simple updates for future tournaments.

**Details:**

* Admin interface to:

  * Upload results and photos
  * Edit sponsor info
  * Update dates and location

---

## Recommended Tech Stack

* **Framework:** Astro (Static Site Generator)
* **Styling:** Tailwind CSS v4
* **Animation:** Framer Motion or CSS transitions
* **Hosting:** Vercel or Netlify
* **Image Optimization:** Astro assets + image CDN

---

## Next Steps

1. Implement this structure in an Astro + Tailwind project.
2. Define dynamic components for sections like Results, Gallery, and Sponsors.
3. Add CMS integration or admin tools (optional post-MVP).

---
