# Alpha Cricket Academy Website Specification

## Project Overview
- **Project Name**: Alpha Cricket Academy Website
- **Type**: Single-page marketing website
- **Core Functionality**: Showcase cricket academy services, facilities, programs, and contact information
- **Target Users**: Parents looking for cricket coaching for kids (8-16) and adults seeking professional training

## UI/UX Specification

### Layout Structure
- **Header**: Fixed navigation bar with logo and menu links
- **Hero Section**: Full-screen hero with cricket ground background
- **About Us**: Two-column layout with text and coach images
- **Programs**: Three-column card layout for Beginner/Intermediate/Advanced
- **Facilities**: Grid layout with icons and descriptions
- **Gallery**: Image grid with hover effects
- **Testimonials**: Card carousel/slider
- **Contact**: Two-column layout with form and map
- **Footer**: Contact info, social links, copyright

### Responsive Breakpoints
- Desktop: 1200px+
- Tablet: 768px - 1199px
- Mobile: < 768px

### Visual Design

#### Color Palette
- **Primary Green**: #1B5E20 (Dark green)
- **Secondary Green**: #4CAF50 (Medium green)
- **Accent Green**: #8BC34A (Light green)
- **White**: #FFFFFF
- **Off-White**: #F5F5F5
- **Dark Text**: #212121
- **Light Text**: #757575

#### Typography
- **Headings**: 'Poppins', sans-serif (Bold, 700)
- **Body**: 'Open Sans', sans-serif (Regular, 400)
- **Hero Title**: 64px (desktop), 40px (mobile)
- **Section Titles**: 42px (desktop), 32px (mobile)
- **Body Text**: 16px
- **Small Text**: 14px

#### Spacing System
- Section Padding: 80px vertical (desktop), 50px (mobile)
- Container Max Width: 1200px
- Card Padding: 30px
- Element Gaps: 20px - 40px

#### Visual Effects
- Box shadows on cards: 0 4px 20px rgba(0,0,0,0.1)
- Hover transitions: 0.3s ease
- Subtle animations on scroll
- Gradient overlays on hero

### Components

#### Navigation
- Logo (left): "Alpha Cricket Academy" with cricket icon
- Menu (right): Home, About, Programs, Facilities, Gallery, Testimonials, Contact
- Mobile: Hamburger menu
- Sticky on scroll with background change

#### Hero Section
- Full viewport height background
- Cricket ground image with dark gradient overlay
- Centered content: Title, Slogan, CTA button
- Animation: Fade in on load

#### About Section
- Section title with underline accent
- Vision & Mission statements
- Coach profiles with photos and credentials

#### Programs Cards
- Icon at top
- Program title
- Description
- Age group tag
- Hover: lift effect with shadow

#### Facilities Grid
- Icon + Title + Description format
- 2x2 grid on desktop, single column mobile

#### Gallery
- Image grid with 3-4 columns
- Hover: zoom effect with overlay

#### Testimonials
- Quote cards with student/parent photo
- Name and relation
- Star rating

#### Contact Section
- Contact form (name, email, phone, message)
- Contact info cards (phone, email, address)
- Embedded Google Map

#### Footer
- Dark green background
- Quick links
- Social media icons
- Copyright text

## Functionality Specification

### Core Features
- Smooth scroll navigation
- Mobile responsive menu
- Scroll-triggered animations
- Form validation (basic)
- Interactive hover effects
- Image gallery with hover states

### User Interactions
- Click navigation links → smooth scroll to section
- Hover on cards → lift and shadow effect
- Click CTA → scroll to contact section
- Mobile menu toggle

### Edge Cases
- Long content handling
- Image loading fallback
- Form submission prevention (demo)

## Acceptance Criteria
1. All 7 sections are present and properly styled
2. Green and white theme is consistently applied
3. Website is fully responsive
4. Smooth scroll works for all navigation links
5. All hover effects function properly
6. Hero has cricket ground background with "Train Like a Champion" slogan
7. Contact section includes phone, email, address, and Google Map placeholder
8. Professional and energetic appearance
