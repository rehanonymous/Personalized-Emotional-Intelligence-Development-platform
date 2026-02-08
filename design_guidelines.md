# Vivi Emotional Wellness Platform - Design Guidelines

## Design Approach: Reference-Based (Mental Health/Wellness Category)
**Primary References**: Headspace, Calm, BetterHelp  
**Justification**: Experience-focused platform requiring emotional connection, trust-building, and visual comfort for mental wellness content.

## Core Design Principles
- **Emotional Safety**: Calming, non-threatening visual environment
- **Professional Trust**: Clean, credible design for counselor/mentor interactions
- **Gentle Hierarchy**: Soft visual distinctions without aggressive contrasts
- **Accessibility-First**: High readability and inclusive design patterns

## Color Palette

### Light Mode
- **Primary**: 200 15% 45% (Soft teal-blue for trust and calm)
- **Secondary**: 280 20% 35% (Muted purple for wisdom/insight)
- **Success**: 140 25% 40% (Gentle green for positive progress)
- **Background**: 210 15% 98% (Warm near-white)
- **Surface**: 210 10% 95% (Subtle card backgrounds)

### Dark Mode
- **Primary**: 200 25% 65% (Lighter teal for visibility)
- **Secondary**: 280 30% 70% (Lighter purple)
- **Success**: 140 30% 60% (Accessible green)
- **Background**: 220 15% 8% (Deep blue-gray)
- **Surface**: 220 10% 12% (Elevated surfaces)

## Typography
- **Primary**: Inter (Google Fonts) - Clean, highly readable
- **Secondary**: Merriweather (Google Fonts) - For longer content, journal entries
- **Scale**: text-sm, text-base, text-lg, text-xl, text-2xl, text-3xl

## Layout System
**Spacing Primitives**: 2, 4, 6, 8, 12, 16 (p-2, m-4, gap-6, etc.)
- Generous whitespace for breathing room
- Consistent 8-unit grid system
- Maximum content width: max-w-4xl for readability

## Component Library

### Navigation
- **Header**: Minimal top nav with role indicator badge
- **Sidebar**: Collapsible role-based navigation with gentle hover states
- **Breadcrumbs**: Soft text-sm navigation for deep pages

### Core Components
- **Cards**: Subtle shadows (shadow-sm), rounded corners (rounded-lg)
- **Buttons**: Primary (solid), Secondary (outline with blur when over images), Ghost (text-only)
- **Forms**: Soft focus rings, gentle validation states
- **Modals**: Backdrop blur with centered, non-threatening positioning

### Data Visualization
- **Charts**: Soft gradients using Chart.js with brand colors
- **Progress**: Gentle progress bars with rounded ends
- **Avatars**: Circular with soft fallback colors

### Role-Specific Elements
- **Individual**: Personal dashboard with mood tracking widgets
- **Mentor**: Mentee cards with connection status indicators
- **Counselor**: Professional session scheduling interface
- **Coordinator**: Team analytics with aggregated wellness metrics

## Wellness-Specific Design Elements

### Emotional States
- Color-coded mood indicators using HSL variations of primary colors
- Gentle emoji alternatives for accessibility
- Soft data visualizations for mood trends

### Crisis Support
- Clear, accessible emergency contact buttons
- Non-alarming but prominent placement
- Calm color treatment even for urgent elements

## Images
- **Hero Image**: None - Focus on clean, welcoming dashboard entry
- **Illustrations**: Soft, abstract wellness imagery for empty states
- **Avatars**: Default to initials with calming background colors
- **Icons**: Heroicons for consistency, mental health-appropriate iconography

## Animations
**Minimal Use**: Subtle fade-ins for content loading, gentle hover states on interactive elements. Avoid jarring transitions that might trigger anxiety.

## Accessibility
- WCAG 2.1 AA compliance
- Consistent dark mode across all inputs and surfaces
- High contrast ratios for text readability
- Screen reader optimized content structure
- Keyboard navigation support for all interactive elements