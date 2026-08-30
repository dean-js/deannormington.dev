---
layout: post
title: "Building My Personal Portfolio with Jekyll"
date: 2026-06-05
description: "A comprehensive overview of building my personal portfolio website from start to present, documenting the project evolution, design decisions, and current state."
categories: [Software Development, Portfolio Posts]
tags:
  [
    jekyll,
    portfolio,
    web-development,
    static-site,
    design,
    project-overview,
    in-progress,
  ]
published: true
---

## Introduction

This post is a summary of my personal portfolio project journey. From initial conception through design iterations to the current state, I document the decisions made, technologies chosen, and the ongoing development of this Jekyll-based portfolio site.

## Project Genesis

I decided to build a small personal portfolio to begin with, when I was initially rediscovering my passion and moving towards making the full pivot. This was to showcase current and developing understanding, and completed functional websites or applications, across three main areas:

- Basic web development fundamentals - building a personal portfolio with a blog & other projects.
- Used legal knowledge to create a legal tech project - the Legal Fee Calculator.
- Software development learning - through building other demo websites and applications, showcasing my skillset in creating interactive, functional, and secure digital products that ensure company and user satisfaction.
- Cybersecurity studies in cybersecurity systems and practices - enhancing and refreshing knowledge across a variety of areas, deepening my understanding of networking and security frameworks, and building hands-on experience with various software, opening potential opportunities to break into entry-level cybersecurity roles.

Using Jekyll for this project initially made sense when starting out, as a way to understand tags, structure, and other basic HTML and CSS fundamentals. A static site generator made sense for simplicity, performance, and version-control-friendly content - this was also a bonus, being zero cost and linked to GitHub.

## Technology Stack

**Core Technology:**

- Jekyll for static site generation
- SCSS for styling and design system
- Gulp for build automation and asset compilation
- GitHub Pages for hosting and deployment

**Design Approach:**

- A proper brand kit: a light "paper and ink" palette with a teal accent (circuit) and a purple secondary accent (pulse), used sparingly
- Sora for headings and the wordmark, Inter for body copy, JetBrains Mono for labels and navigation
- Responsive, mobile-first design
- Clean, minimal typography with a clear content hierarchy
- Gives visitors a personal insight into who I am as a developer

## Site Structure

The portfolio is organized into several key sections:

1. **Homepage** - Hero section with tagline, learning card, featured projects
2. **About** - Personal background and career transition narrative
3. **Portfolio** - Showcase of completed projects and work samples
4. **Projects** - Detailed project pages with descriptions and outcomes
5. **Blog** - Posts organized by category (Legal Tech, Software Development, Cybersecurity, Tech Projects, Portfolio Posts)
6. **Contact** - Ways to get in touch and social links

## Current Version Status

### Completed Features

- Responsive homepage with hero section and learning card grid
- Project listing with card-based layout and detail pages
- Blog page with category-based filtering and jump links
- Footer with social media links
- A consistent brand kit palette across every page
- Mobile-friendly navigation and layout

### Recent Improvements

- Fixed blog category filtering to use post categories instead of tags
- Added new blog categories (Tech Projects, Portfolio Posts)
- Created project detail pages for the Private AI Workstation and other projects
- Unified typography and spacing across all pages
- Adopted a proper brand kit and rebuilt the site's colours, type, and layout around it (see the Brand Refresh section below)

### Known Upcoming Work

- Expand blog content with more posts in each category
- Add more project showcase pages
- Implement analytics and SEO optimization
- Create an automated deployment pipeline

## Design Decisions

**A light, paper-based theme:** Chosen for a calmer, more considered feel over the original dark theme, and because it reads as more "capable and calm" for a site clients might actually land on.

**Category-Based Blog:** Allows readers to filter content by their interest area (legal tech, coding, security).

**Project Cards:** Provides quick overview with links to detailed project pages.

**Static Generation:** Ensures fast load times, easy version control, and minimal hosting complexity.

## Brand Refresh (August 2026)

A few months into running the site, I put together a proper personal brand kit rather than continuing to tweak colours ad hoc. It covers identity, logo usage, colour palette, typography, voice, and do's and don'ts, and the whole site has since been rebuilt around it:

- **Palette:** Paper (background) and Ink (text) carry almost everything, with Circuit (a deep teal) as the main accent and Pulse (a muted purple) used sparingly for secondary highlights
- **Type:** Sora for headings and the wordmark, Inter for body copy, JetBrains Mono for labels, tags, and navigation
- **Logo:** A two-weight wordmark ("**Dean** Normington") as the primary mark, with a small "DN" monogram badge for the favicon and other small, round spaces
- **Positioning:** Reframed around what I actually do day to day: web development, Shopify and e-commerce, and a genuine customer service background, with cyber security as a clearly-labelled growing focus rather than the headline

It's a more deliberate, more "me" identity than the original dark theme, and one I plan to keep consistent across the site, LinkedIn, and anywhere else I show up.

## Lessons Learned

- Jekyll Liquid templating is powerful but requires careful attention to variable scope
- SCSS organization with partial imports keeps stylesheets maintainable
- Responsive design requires testing on multiple device sizes
- Clear front matter structure (categories, tags) is essential for content organization

## Next Steps

1. Continue expanding blog content with detailed posts
2. Add more project showcase pages as work progresses
3. Optimize images and assets for better performance
4. Implement comment system for blog posts (optional)
5. Create a projects archive or timeline view
6. Add search functionality for blog posts

## Reflection

Building this portfolio has been a valuable exercise in web development fundamentals. It serves as both a showcase of my work and a learning project where I can experiment with design and layout decisions. The modular structure makes it easy to add new content and iterate on the design as my skills grow.

This site is a living document of my transition from law to technology, and I plan to continue to evolve and update it continuously as my projects, portfolio, and skills develop.
