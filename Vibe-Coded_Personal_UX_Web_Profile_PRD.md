# Vibe-Coded Personal UX Web Profile

**Date:** 15.12.2025

**Version:** v1.0 - Draft

---

## Short Pitch

Based on the hackathon guide provided, here are a few options for a Short Pitch you can use for your PRD tool.

You can choose the one that best fits the specific "vibe" or focus of your project.
Option 1: The Direct & Functional Pitch (Recommended)

"A data-driven personal website and digital portfolio for a UX professional, built by customizing the 'Academic Pages' GitHub template. This web application transforms a standard academic layout into a personalized brand experience, featuring a fully accessible, tri-modal CV (text, visual, audio) and interactive project case studies. The goal is to deploy a live, professional digital presence using AI-assisted 'Vibe Coding' techniques.

## Problem

UX professionals and academics often rely on generic, static website templates that fail to effectively showcase their unique "personal UX brand" or technical expertise. They lack a digital presence that is both visually engaging and fully accessible to diverse users.

Specific Pain Points:
- Generic Identity: Users start with a "blank website template" that lacks personality and fails to reflect their specific "vibe" or professional brand.
- Inaccessibility: Standard digital CVs are typically text-heavy and static, failing to provide "tri-modal consumption" (Visual, Audio, Text) for broader accessibility.
- Static Engagement: Traditional portfolios present case studies as flat documents, missing the opportunity to demonstrate UX skills through "interactive experiences" like scroll-reveals or interactive visuals.

## Solution

The Solution: I will build a Data-Driven Personal Website hosted on GitHub Pages that transforms a standard academic template into a dynamic, "vibe-coded" digital product. This solution uses AI-assisted coding tools (like Cursor or Lovable) to rapidly deploy a site that is distinct, accessible, and interactive.

Key Features & Approach:
- Personalized "Vibe" Theme: To solve the "generic identity" problem, I will implement a custom theme with unique background colors, icons, and fonts that reflect a personal UX brand. This includes a Personalized Hero Landing Page featuring a custom profile image, welcome message, and tagline.

- Tri-Modal Accessible CV: To address "inaccessibility," I will create a resume that supports three distinct modes of consumption:
     > Text-based: Web-optimized for screen readers.
     > Visual-based: A timeline, infographic, or storyboard for visual learners.
     > Audio-based: An embedded audio introduction or podcast-style summary.

- Interactive Portfolio Experience: To solve "static engagement," we will convert standard project documentation into an Interactive Paper or Project. This includes interactive content reveals (e.g., scroll-based or flip cards) and dynamic visuals that change on hover, ensuring the user is actively engaged rather than passively reading.

## Target Users

Primary User: UX Designer (Owner)
Characteristics:
- UX/UI design student or junior professional
- Familiar with design thinking, less confident in coding
- Uses AI tools for coding and ideation
- Wants to express personal brand and emotion

Goals:
- Build a compelling digital presence quickly
- Showcase UX thinking and interaction skills
- Experiment creatively with vibe coding

Secondary Users: Visitors, Recruiters / Hiring Managers

Want fast signal on skills, personality, and UX maturity
Prefer scannable, interactive, memorable experiences

Professors / Academic Evaluators
Need structured academic content (papers, CV)
Value clarity, rigor, and documentation

Peers / Hackathon Jury
Evaluate creativity, execution, and emotional impact
Compare multiple projects quickly

## Use Cases

UC1 – First Impression / Hero Experience
A visitor lands on the website and immediately perceives:
- Emotional tone (calm, bold, playful, analytical, etc.)
- Personal identity (who this designer is)
- Clear entry points to CV, projects, or papers

UC2 – Recruiter Scan
A recruiter: Skims the hero section, Opens the CV, Reviews 1–2 projects, Forms an opinion within 2–3 minutes

UC3 – Deep Project Exploration
A visitor: 
- Scrolls through an interactive project
- Engages with hover states, reveals, or animations
- Understands problem → process → outcome

UC4 – Academic Validation
A professor:
- Opens an interactive paper
- Reviews abstract, method, results
- Downloads PDF for offline reading

UC5 – Accessibility Consumption
A user: 
Consumes CV as text, visuals, or audio
Navigates comfortably using keyboard or screen reader

## North-Star Metrics

✅ All hackathon features implemented
✅ Fully deployed, publicly accessible website
✅ Custom theme clearly reflecting personal UX brand
✅ Interactive elements functioning across devices
✅ Accessible CV with at least two consumption modes
✅ Positive peer / jury feedback during pitch or voting
✅ Clean Git commit history with milestone tags

## Feature Modules

1. Core Website Infrastructure
Static site generated from Academic Pages template. 
GitHub repository linked to hackathon dashboard
Automated deployment (e.g. GitHub Pages)

2. Custom Theme Module
Custom theme that reflects and my artsy personal UX brand
The color palette should be in a beautiful orange to yellow gradient.
Custom Typography selection, Iconography which is more artsy
Light / dark mode or vibe-based theme switch
Hovering over the theme icon should bring up 3 options (existing light / dark icons and my own)

3. Hero Landing Page
Personal tagline
Profile hero image
Short introduction of myself
Quick navigation to CV, projects, or papers

4. Accessible CV Module
Text-based, web-optimized CV
Visual timeline or infographic
Optional audio-based CV (podcast-style)
Interactive navigation and storytelling

5. Interactive Paper Module
Academic paper layout with:
Abstract, method, results
Visual diagrams or charts
Interactive reveals
PDF download

Media support (images, video, animation)

PDF report download

## Tech Overview

Frontend
Core Technologies
HTML5 (semantic markup for accessibility and structure)
CSS3 (layout, theming, animations, transitions)
JavaScript (minimal, vanilla JavaScript only)

Static Site Generator: Jekyll (Academic Pages)
I am working on a Jekyll site (Academic Pages). Do not introduce new frameworks or JavaScript libraries. Modify only existing layouts, includes, Markdown, or CSS.

Critical Constraint:
👉 Do not introduce new frameworks or external JavaScript libraries.
👉 Modify only existing layouts, includes, Markdown files, configuration, or CSS.

Technical Constraints & Design Implications

Why this constraint exists:
Maintains the integrity and stability of the Academic Pages theme
Ensures compatibility with GitHub Pages (which has limited build support)
Reduces cognitive and technical overhead during a time-boxed hackathon
Keeps the system maintainable, transparent, and auditable for academic evaluation

Implications for UI / UX Design:
All interaction design must be achievable using:
CSS animations and transitions
Pseudo-classes (hover, focus, active)
Progressive disclosure via CSS or minimal inline JavaScript
Complex behaviors such as:
Real-time data fetching
Complex form handling
User authentication
Client-side state management are explicitly out of scope

Designers must think in terms of expressive simplicity: how much emotional and experiential value can be achieved with minimal technical means

This constraint is intentional and educational: it forces UX decisions to be technically feasible and encourages creativity within real-world limitations.

