# Happy Birthday Website - Specification

## Project Overview

- **Project Name**: Happy Birthday Website
- **Type**: Single Page Interactive Website
- **Core Functionality**: A beautiful, interactive birthday greeting website with animations, slideshow, and surprises
- **Target Users**: Anyone who wants to create a special birthday greeting

## UI/UX Specification

### Layout Structure

1. **Landing Section** (Initial View)
   - Centered "Happy Birthday [Name]" animated text
   - Decorative elements (stars, sparkles, hearts)
   - Music control button
   - "Klik untuk membuka kejutan 🎁" button
   - Confetti animation background

2. **Surprise Section** (After clicking button)
   - Photo slideshow with smooth transitions
   - Long birthday message with typing effect
   - Floating balloon animations
   - Additional decorative elements

### Responsive Breakpoints

- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

### Visual Design

#### Color Palette

- **Primary Background**: Linear gradient from #FFD1DC (pastel pink) to #FFF5E1 (cream) to #E6E6FA (soft lavender)
- **Accent Pink**: #FFB6C1 (Light Pink)
- **Accent Purple**: #DDA0DD (Plum)
- **Accent Gold**: #FFD700 (Gold for stars)
- **Text Primary**: #5D4E6D (Dark Purple)
- **Text Secondary**: #8B7B8B (Muted Purple)
- **Card Background**: rgba(255, 255, 255, 0.85)
- **Button Primary**: #FF69B4 (Hot Pink)
- **Button Hover**: #FF1493 (Deep Pink)

#### Typography

- **Main Title Font**: 'Pacifico', cursive (for "Happy Birthday")
- **Body Font**: 'Poppins', sans-serif
- **Title Size**: 3.5rem (desktop), 2.5rem (mobile)
- **Body Size**: 1.1rem
- **Message Size**: 1.3rem

#### Spacing System

- Section padding: 60px 20px
- Card padding: 30px
- Element margins: 20px
- Border radius: 20px (cards), 50px (buttons)

#### Visual Effects

- **Confetti**: Multi-colored particles falling with physics
- **Balloons**: 3D-looking balloons floating upward with slight sway
- **Sparkles**: Animated twinkling stars
- **Floating hearts**: Gentle floating animation
- **Card shadow**: 0 10px 40px rgba(255, 105, 180, 0.2)
- **Glass morphism**: Frosted glass effect on cards

### Components

1. **Title Banner**
   - Pacifico font with gradient text
   - Bounce animation on load
   - Decorative underline with hearts

2. **Music Control Button**
   - Circular button with musical note icon
   - Pulse animation when playing
   - Smooth play/pause toggle

3. **Surprise Button**
   - Large, prominent button
   - Gradient background
   - Bounce animation
   - Hover: scale up, glow effect
   - Click: ripple effect

4. **Photo Slideshow**
   - Smooth fade transitions
   - Auto-advance every 3 seconds
   - Manual navigation dots
   - Placeholder images (using picsum for demo)

5. **Message Card**
   - Glass morphism effect
   - Typing cursor animation
   - Fade in effect

6. **Decorative Elements**
   - Floating hearts (various sizes)
   - Twinkling stars
   - Sparkle particles
   - Balloons (multiple colors)

## Functionality Specification

### Core Features

1. **Confetti Animation**: Triggers on page load, runs for 5 seconds
2. **Music Player**:
   - Autoplay blocked by browser (requires user interaction)
   - Play/Pause toggle button
   - Uses embedded audio or generated tone
3. **Typing Effect**:
   - Types message character by character
   - 50ms delay between characters
   - Cursor blink animation
4. **Photo Slideshow**:
   - 5 placeholder images
   - 3 second interval
   - Smooth crossfade transition
5. **Balloon Animation**:
   - 10-15 balloons
   - Random sizes and speeds
   - Continuous loop

### User Interactions

- Click music button → Toggle audio play/pause
- Click surprise button → Reveal surprise section with animations
- Hover buttons → Scale and glow effect
- Scroll → Smooth scroll to sections

### Edge Cases

- Music autoplay blocked: Show play button, user must click
- Slow network: Placeholder colors for images
- Mobile: Simplified animations for performance

## Acceptance Criteria

### Visual Checkpoints

- [ ] Pastel gradient background visible
- [ ] "Happy Birthday" title with Pacifico font displays
- [ ] Confetti animation plays on load
- [ ] Music button is visible and interactive
- [ ] Surprise button has bounce animation
- [ ] Clicking surprise reveals slideshow
- [ ] Message appears with typing effect
- [ ] Balloons float upward
- [ ] All elements are responsive
- [ ] Hover effects work on buttons

### Functional Checkpoints

- [ ] Page loads without errors
- [ ] Music can be played/paused
- [ ] Surprise section reveals smoothly
- [ ] Slideshow advances automatically
- [ ] Typing animation completes
- [ ] Mobile layout is usable
- [ ] No console errors
