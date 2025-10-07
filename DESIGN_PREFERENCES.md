# Design Preferences & UI/UX Guidelines

This document tracks design preferences and patterns learned during the OmutimaOmugabi project development.

## Core Design Philosophy

**"Small things matter"** - Every micro-animation and detail should be purposeful and elegant, creating a vivid impression through polished execution.

---

## Animation Preferences

### Micro-Animations
- **Purposeful movement**: Animations should have clear intent - elements should reveal, guide, or enhance understanding
- **Smooth & elegant**: Prefer smooth, professional transitions over flashy or jarring effects
- **Fast & refined**: Animations should be quick but not rushed - elegant execution is key
  - Typing speed: 60ms per character
  - Deleting speed: 30ms per character
  - Transition timing: 300-600ms for reveals

### Text Animation Patterns

#### ❌ Avoid
- Static blinking cursors that serve no purpose
- Pulsating/flashing effects that are "disturbing" or "too fast"
- Simple fade-in/fade-out without purpose
- Rapid shimmer effects that feel aggressive

#### ✅ Prefer
- **Lower thirds effects** - Broadcast-quality animations with:
  - Sliding reveal bars (gradient overlays)
  - Gradient underline wipes
  - Smooth fade-out transitions
  - Professional timing (3s display, 400ms fade)
- **Cursor with purpose** - Cursor movement should directly reveal/hide content as it moves
- **Subtle glows** - Soft, gentle pulsing (4s ease-in-out) over fast shimmer

### Border & Glow Effects
- **Elegant over flashy**: Softer glows with reduced opacity (0.3-0.5 range)
- **Slower timing**: 4s ease-in-out for glow transitions
- **Unified effects**: Smooth color transitions between brand colors without directional movement
- **Brand color integration**: Use primary purple (#6852a2) and orange (#faa92b) in glows

---

## Video & Media

### Background Videos
- **Blur for context**: Background videos should be slightly blurred (4px) to avoid competing with foreground content
- **Purpose**: Video provides atmospheric context, not the main focus
- **Text readability**: Always ensure sufficient contrast with overlays (purple gradient overlay 70-80% opacity)

### Hero Sections
- **Clean composition**: Remove elements that block important visuals
- **Video prominence**: Let background video shine when it's the feature
- **Minimal text**: Keep hero sections uncluttered - move descriptive content to subsequent sections

---

## Typography & Text Effects

### Gradient Text
- Prefer **135deg angle** for diagonal gradients
- Use brand colors in gradients:
  - Orange: #faa92b → Lighter orange: #ffb84d
  - Purple: #6852a2
- Apply `-webkit-background-clip: text` for gradient fills

### Text Animation Timing
- Display duration: 3000ms (3 seconds)
- Fade transitions: 400ms
- Pause before next: 300ms
- Character typing: 60ms
- Character deletion: 30ms

---

## Brand Colors

### Primary Colors
- **Purple**: #6852a2, RGB(100,89,167), CMYK(40,47,0,35)
- **Orange**: #faa92b, RGB(250,169,59), CMYK(0,34,76,2)

### Application
- Use in gradients for premium feel
- Apply to borders, glows, and accent elements
- Combine in animations (purple → orange transitions)

---

## UI Components

### Badge/Tag Elements
- Elegant border glow animations (orange ↔ purple)
- Soft backdrop blur effects
- Border color transitions synchronized with glow

### Lower Thirds Style
- Sliding gradient reveal bars
- Animated gradient underlines (orange → purple)
- Professional timing and pacing
- Smooth entry and exit animations

---

## Performance & Optimization

### Animation Performance
- Use CSS transforms (translateX, translateY) over position changes
- Leverage GPU acceleration with `transform` properties
- Keep animation durations between 300ms - 4s
- Use `ease-in-out` or `ease-out` for natural motion

---

## Key Learnings

1. **Micro-animations create vivid impressions** - Every small detail matters in creating a polished, professional feel

2. **Purposeful motion** - Animations should guide the eye and enhance understanding, not just decorate

3. **Broadcast-quality patterns** - Lower thirds and professional motion graphics techniques elevate the design

4. **Speed & elegance balance** - Fast enough to feel responsive, slow enough to feel intentional

5. **Brand integration** - Use brand colors consistently across all interactive elements

6. **Context over competition** - Background elements (like videos) should support, not compete with content

---

## Future Considerations

- Continue exploring broadcast-style animations
- Maintain focus on purposeful micro-interactions
- Keep refining timing for optimal elegance
- Ensure all animations serve a clear UX purpose

---

*Last updated: 2025-10-07*
*Project: OmutimaOmugabi Platform Design Showcase*
