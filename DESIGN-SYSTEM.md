# CONNECTRA PROFESSIONAL DESIGN SYSTEM

## 🎨 Brand Color Palette (Extracted from Logo)

### Primary Colors
```css
--brand-burgundy: #6B1F3C;      /* Primary brand color - from logo */
--brand-navy: #2C3E5F;          /* Secondary brand color - from logo */
--brand-gold: #D4AF37;          /* Accent color - from logo */
--brand-copper: #B87333;        /* Supporting accent - from logo */
```

### Neutral Colors
```css
--white: #FFFFFF;
--gray-50: #F8F9FA;
--gray-100: #F1F3F5;
--gray-200: #E9ECEF;
--gray-300: #DEE2E6;
--gray-400: #CED4DA;
--gray-500: #ADB5BD;
--gray-600: #6C757D;
--gray-700: #495057;
--gray-800: #343A40;
--gray-900: #212529;
--black: #000000;
```

### Functional Colors
```css
--success: #28A745;
--info: #17A2B8;
--warning: #FFC107;
--error: #DC3545;
```

---

## 📐 Typography System

### Font Families
```css
--font-primary: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
--font-secondary: 'Poppins', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
--font-mono: 'Courier New', monospace;
```

### Font Sizes (Responsive)
```css
--font-xs: clamp(0.75rem, 0.7vw + 0.6rem, 0.875rem);     /* 12-14px */
--font-sm: clamp(0.875rem, 0.8vw + 0.7rem, 1rem);        /* 14-16px */
--font-base: clamp(1rem, 0.9vw + 0.8rem, 1.125rem);      /* 16-18px */
--font-lg: clamp(1.125rem, 1vw + 0.9rem, 1.25rem);       /* 18-20px */
--font-xl: clamp(1.25rem, 1.2vw + 1rem, 1.5rem);         /* 20-24px */
--font-2xl: clamp(1.5rem, 1.5vw + 1.2rem, 2rem);         /* 24-32px */
--font-3xl: clamp(2rem, 2vw + 1.5rem, 3rem);             /* 32-48px */
--font-4xl: clamp(2.5rem, 3vw + 2rem, 4rem);             /* 40-64px */
```

### Font Weights
```css
--font-light: 300;
--font-normal: 400;
--font-medium: 500;
--font-semibold: 600;
--font-bold: 700;
--font-extrabold: 800;
```

---

## 🎭 Spacing System

```css
--space-xs: 0.25rem;    /* 4px */
--space-sm: 0.5rem;     /* 8px */
--space-md: 1rem;       /* 16px */
--space-lg: 1.5rem;     /* 24px */
--space-xl: 2rem;       /* 32px */
--space-2xl: 3rem;      /* 48px */
--space-3xl: 4rem;      /* 64px */
--space-4xl: 6rem;      /* 96px */
--space-5xl: 8rem;      /* 128px */
```

---

## 📦 Layout System

### Container Widths
```css
--container-sm: 640px;
--container-md: 768px;
--container-lg: 1024px;
--container-xl: 1280px;
--container-2xl: 1536px;
--container-full: 100%;
```

### Breakpoints
```css
--screen-sm: 640px;
--screen-md: 768px;
--screen-lg: 1024px;
--screen-xl: 1280px;
--screen-2xl: 1536px;
```

---

## 🎨 Component Styles

### Shadows
```css
--shadow-sm: 0 1px 2px 0 rgba(0, 0, 0, 0.05);
--shadow-base: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
--shadow-md: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
--shadow-lg: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
--shadow-xl: 0 25px 50px -12px rgba(0, 0, 0, 0.25);
--shadow-gold: 0 10px 30px rgba(212, 175, 55, 0.2);
--shadow-burgundy: 0 10px 30px rgba(107, 31, 60, 0.2);
```

### Border Radius
```css
--radius-sm: 4px;
--radius-base: 8px;
--radius-md: 12px;
--radius-lg: 16px;
--radius-xl: 24px;
--radius-full: 9999px;
```

### Transitions
```css
--transition-fast: 150ms cubic-bezier(0.4, 0, 0.2, 1);
--transition-base: 300ms cubic-bezier(0.4, 0, 0.2, 1);
--transition-slow: 500ms cubic-bezier(0.4, 0, 0.2, 1);
```

---

## 🎯 UI Component Specifications

### Navigation Bar
```css
Background: White with subtle shadow
Text: Navy (#2C3E5F)
Active/Hover: Gold (#D4AF37)
Logo: Full color with no background
Height: 80px
Sticky: Yes
Backdrop: Blur(20px) with transparency
```

### Hero Section
```css
Background: Navy gradient with subtle pattern
Text: White
Accent: Gold
Height: Min 600px, Max 800px
Overlay: rgba(44, 62, 95, 0.95)
```

### Buttons

**Primary Button:**
```css
Background: Burgundy to Navy gradient
Border: 2px solid Gold
Color: White
Padding: 1rem 2.5rem
Border-radius: 8px
Hover: Lift 3px + subtle shadow
```

**Secondary Button:**
```css
Background: Transparent
Border: 2px solid Gold
Color: Navy
Padding: 1rem 2.5rem
Border-radius: 8px
Hover: Background gold (10% opacity)
```

**Text Button:**
```css
Background: None
Color: Gold
Underline: On hover (animated)
```

### Cards
```css
Background: White
Border: 1px solid rgba(212, 175, 55, 0.2)
Border-radius: 12px
Padding: 2rem
Shadow: var(--shadow-base)
Hover: Lift 5px + --shadow-md
Transition: 300ms ease
```

### Footer
```css
Background: Navy (#2C3E5F) gradient to darker
Text: White (90% opacity)
Headings: Gold (#D4AF37)
Links: White, hover Gold
Border-top: 1px solid Gold (20% opacity)
```

---

## 🎬 Animation Guidelines

### Hover Effects
- **Buttons:** 3px lift + subtle shadow
- **Cards:** 5px lift + enhanced shadow
- **Links:** Underline slide-in from left
- **Images:** Scale 1.05 + slight brightness

### Scroll Animations
- **Fade In:** Opacity 0 to 1, translateY(20px) to 0
- **Slide In:** translateX(-50px) to 0 (left) or (+50px) to 0 (right)
- **Scale In:** scale(0.9) to scale(1)
- **Duration:** 600ms
- **Easing:** cubic-bezier(0.4, 0, 0.2, 1)

### NO MORE:
- ❌ Neon glow effects
- ❌ 360° rotations
- ❌ Excessive transforms
- ❌ Pulsing animations
- ❌ Magnetic effects

---

## 🖼️ Imagery Guidelines

### Photos
- **Quality:** High resolution (min 1920x1080)
- **Style:** Professional, corporate
- **Filter:** Slight desaturation for consistency
- **Overlay:** Navy or Burgundy gradient (20-40% opacity)

### Videos
- **Container:** 16:9 aspect ratio
- **Controls:** Custom branded controls
- **Poster:** Professional thumbnail
- **Border-radius:** 12px
- **Shadow:** --shadow-lg

---

## 📱 Responsive Rules

### Mobile (< 768px)
- Font sizes: Minimum scale
- Padding: Reduced by 50%
- Cards: Single column
- Navigation: Hamburger menu
- Videos: Full width

### Tablet (768px - 1024px)
- Font sizes: Medium scale
- Cards: 2 columns
- Navigation: Partial menu

### Desktop (> 1024px)
- Font sizes: Maximum scale
- Cards: 3-4 columns
- Navigation: Full menu
- Max container: 1280px

---

## ♿ Accessibility Standards

### Contrast Ratios (WCAG AA)
- **Normal text:** Minimum 4.5:1
- **Large text:** Minimum 3:1
- **UI components:** Minimum 3:1

### Focus States
```css
Outline: 2px solid Gold
Outline-offset: 2px
Border-radius: 4px
```

### Interactive Elements
- Minimum touch target: 44x44px
- Keyboard navigation: Full support
- Screen reader: Proper ARIA labels

---

## 🎨 Section Backgrounds

### Alternating Pattern
```css
Section 1: White (#FFFFFF)
Section 2: Light Gray (#F8F9FA)
Section 3: White (#FFFFFF)
Section 4: Light Gray (#F8F9FA)
```

### Hero Sections
```css
Background: Navy gradient with pattern
Overlay: rgba(44, 62, 95, 0.95)
Text: White
```

### CTA Sections (REMOVED)
```css
Display: none !important;
/* Not needed for established 28-year company */
```

---

## 🎯 Interactive Elements Required Per Page

### Every Page Must Have:
1. **Hover states** on all interactive elements
2. **Smooth scroll** to sections
3. **Animated counters** for statistics
4. **Image lightbox** for galleries
5. **Video players** with custom controls
6. **Accordion or tabs** for content organization
7. **Form validation** with visual feedback
8. **Loading states** for async operations

---

## 📐 Layout Rules

### Full-Width Sections
```css
Section wrapper: 100vw
Content container: max-width 1280px, centered
Padding: 5rem 2rem (desktop), 3rem 1.5rem (mobile)
```

### Content Grid
```css
Default: repeat(auto-fit, minmax(300px, 1fr))
Gap: 2rem
Alignment: center
```

### NO MORE:
- ❌ Content stuck to left with empty right side
- ❌ Unbalanced layouts
- ❌ Excessive white space

---

## 🎨 Professional Color Usage

### Primary Usage (Navy #2C3E5F)
- Headings
- Body text
- Navigation text
- Footer background

### Secondary Usage (Burgundy #6B1F3C)
- Brand elements
- Gradient overlays
- Accent backgrounds

### Accent Usage (Gold #D4AF37)
- Interactive elements
- Hover states
- Icons
- Borders
- Underlines
- CTAs

### Supporting (Copper #B87333)
- Secondary accents
- Gradients
- Subtle highlights

---

## 🚫 What to REMOVE

1. **Neon Colors:** No cyan, purple, or green neons
2. **Excessive Animations:** No 360° spins, magnetic effects
3. **CTA Sections:** Remove all aggressive marketing
4. **Glitching Effects:** Smooth animations only
5. **Black Backgrounds:** Use Navy or White
6. **Low Contrast:** Ensure WCAG AA compliance
7. **Cramped Layouts:** Full-width, balanced designs

---

## ✅ Implementation Checklist

- [ ] Replace all neon colors with brand colors
- [ ] Fix navigation to white/light background
- [ ] Update footer to Navy with proper contrast
- [ ] Center all content sections (no empty right side)
- [ ] Add interactive elements to every page
- [ ] Implement video and photo sections
- [ ] Remove all CTA sections
- [ ] Fix Why Choose Connectra glitching
- [ ] Increase tech visual contrast
- [ ] Use real logo everywhere (no neon text)
- [ ] Ensure WCAG AA contrast ratios
- [ ] Test all animations are smooth
- [ ] Verify responsive on all devices

---

## 🎯 Design Principles

1. **Professional First:** Enterprise-grade design
2. **Brand Consistent:** Logo colors throughout
3. **User-Centric:** Interactive and engaging
4. **Accessible:** WCAG AA compliant
5. **Responsive:** Mobile-first approach
6. **Performant:** Fast loading, smooth animations
7. **Balanced:** No wasted space, full-width layouts
8. **Credible:** 28-year established company presence

---

This design system ensures consistency, professionalism, and user engagement across all pages while maintaining brand identity and accessibility standards.
