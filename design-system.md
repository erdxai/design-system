# ERDx Design System

**Professional Database Design Interface** | 2025

---

## Design Philosophy

A refined, professional design system for database architects and developers. Emphasizing clarity, precision, and sophisticated minimalism.

### Core Principles

1. **Clarity Over Decoration** - Every element serves a functional purpose
2. **Precision** - Exact alignment, consistent spacing, deliberate choices
3. **Sophistication** - Restrained color, subtle shadows, refined typography
4. **Professional** - Enterprise-grade aesthetic that inspires confidence
5. **Timeless** - Avoid trends, focus on enduring design patterns

---

## Color System

### Neutral Foundation

A refined grayscale palette forms the foundation of the interface.

```css
/* Light Mode */
--gray-50: #fafafa;
--gray-100: #f5f5f5;
--gray-200: #e5e5e5;
--gray-300: #d4d4d4;
--gray-400: #a3a3a3;
--gray-500: #737373;
--gray-600: #525252;
--gray-700: #404040;
--gray-800: #262626;
--gray-900: #171717;
--gray-950: #0a0a0a;

/* Dark Mode */
--dark-50: #18181b;
--dark-100: #27272a;
--dark-200: #3f3f46;
--dark-300: #52525b;
--dark-400: #71717a;
--dark-500: #a1a1aa;
--dark-600: #d4d4d8;
--dark-700: #e4e4e7;
--dark-800: #f4f4f5;
--dark-900: #fafafa;
```

### Accent Colors

Minimal, purposeful use of color for emphasis.

```css
/* Primary - Refined Blue */
--primary-50: #eff6ff;
--primary-100: #dbeafe;
--primary-200: #bfdbfe;
--primary-300: #93c5fd;
--primary-400: #60a5fa;
--primary-500: #3b82f6;    /* Primary action color */
--primary-600: #2563eb;
--primary-700: #1d4ed8;
--primary-800: #1e40af;
--primary-900: #1e3a8a;

/* Semantic Colors */
--success: #10b981;
--warning: #f59e0b;
--error: #ef4444;
--info: #3b82f6;
```

### Entity Colors

Muted, professional colors for table differentiation.

```css
--entity-slate: #64748b;
--entity-blue: #3b82f6;
--entity-indigo: #6366f1;
--entity-violet: #8b5cf6;
--entity-purple: #a855f7;
--entity-pink: #ec4899;
--entity-rose: #f43f5e;
--entity-orange: #f97316;
--entity-amber: #f59e0b;
--entity-yellow: #eab308;
--entity-lime: #84cc16;
--entity-green: #10b981;
--entity-emerald: #059669;
--entity-teal: #14b8a6;
--entity-cyan: #06b6d4;
--entity-sky: #0ea5e9;
```

---

## Typography

### Font Family

```css
--font-sans: "Inter", -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
--font-mono: "JetBrains Mono", "Fira Code", Consolas, monospace;
```

### Type Scale

```css
--text-xs: 0.75rem;      /* 12px */
--text-sm: 0.875rem;     /* 14px */
--text-base: 1rem;       /* 16px */
--text-lg: 1.125rem;     /* 18px */
--text-xl: 1.25rem;      /* 20px */
--text-2xl: 1.5rem;      /* 24px */
--text-3xl: 1.875rem;    /* 30px */
--text-4xl: 2.25rem;     /* 36px */
```

### Font Weights

```css
--font-normal: 400;
--font-medium: 500;
--font-semibold: 600;
--font-bold: 700;
```

### Line Height

```css
--leading-tight: 1.25;
--leading-snug: 1.375;
--leading-normal: 1.5;
--leading-relaxed: 1.625;
```

---

## Spacing

Consistent 4px-based spacing scale.

```css
--space-0: 0;
--space-1: 0.25rem;   /* 4px */
--space-2: 0.5rem;    /* 8px */
--space-3: 0.75rem;   /* 12px */
--space-4: 1rem;      /* 16px */
--space-5: 1.25rem;   /* 20px */
--space-6: 1.5rem;    /* 24px */
--space-8: 2rem;      /* 32px */
--space-10: 2.5rem;   /* 40px */
--space-12: 3rem;     /* 48px */
--space-16: 4rem;     /* 64px */
--space-20: 5rem;     /* 80px */
--space-24: 6rem;     /* 96px */
```

---

## Border Radius

Subtle, modern radius values.

```css
--radius-none: 0;
--radius-sm: 0.125rem;    /* 2px */
--radius-base: 0.25rem;   /* 4px */
--radius-md: 0.375rem;    /* 6px */
--radius-lg: 0.5rem;      /* 8px */
--radius-xl: 0.75rem;     /* 12px */
--radius-2xl: 1rem;       /* 16px */
--radius-full: 9999px;
```

---

## Shadows

Refined shadow system for subtle depth.

```css
/* Light Mode */
--shadow-xs: 0 1px 2px 0 rgba(0, 0, 0, 0.05);
--shadow-sm: 0 1px 3px 0 rgba(0, 0, 0, 0.1), 0 1px 2px -1px rgba(0, 0, 0, 0.1);
--shadow-base: 0 1px 3px 0 rgba(0, 0, 0, 0.1), 0 1px 2px -1px rgba(0, 0, 0, 0.1);
--shadow-md: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -2px rgba(0, 0, 0, 0.1);
--shadow-lg: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -4px rgba(0, 0, 0, 0.1);
--shadow-xl: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 8px 10px -6px rgba(0, 0, 0, 0.1);

/* Dark Mode */
--shadow-dark-sm: 0 1px 3px 0 rgba(0, 0, 0, 0.3);
--shadow-dark-md: 0 4px 6px -1px rgba(0, 0, 0, 0.4);
--shadow-dark-lg: 0 10px 15px -3px rgba(0, 0, 0, 0.5);
```

---

## Components

### Buttons

#### Primary Button
```css
Background: var(--primary-600)
Color: white
Padding: 0.5rem 1rem
Border-radius: var(--radius-lg)
Font-weight: 500
Font-size: var(--text-sm)
Border: none
Transition: all 150ms ease

Hover:
  Background: var(--primary-700)

Active:
  Background: var(--primary-800)

Focus:
  Outline: 2px solid var(--primary-500)
  Outline-offset: 2px
```

#### Secondary Button
```css
Background: transparent
Color: var(--gray-700)
Padding: 0.5rem 1rem
Border: 1px solid var(--gray-300)
Border-radius: var(--radius-lg)
Font-weight: 500

Hover:
  Background: var(--gray-50)
  Border-color: var(--gray-400)
```

#### Ghost Button
```css
Background: transparent
Color: var(--gray-600)
Padding: 0.5rem 1rem
Border: none

Hover:
  Background: var(--gray-100)
  Color: var(--gray-900)
```

### Cards

#### Entity Card
```css
Background: white
Border: 1px solid var(--gray-200)
Border-radius: var(--radius-xl)
Box-shadow: var(--shadow-sm)
Min-width: 280px
Max-width: 320px

Header:
  Background: var(--entity-color)
  Padding: 0.875rem 1rem
  Border-radius: var(--radius-xl) var(--radius-xl) 0 0
  Color: white
  Font-weight: 600
  Font-size: var(--text-sm)

Body:
  Padding: 0
  Background: white

Field Row:
  Padding: 0.75rem 1rem
  Border-bottom: 1px solid var(--gray-100)
  Font-size: var(--text-sm)

  Hover:
    Background: var(--gray-50)

Hover State:
  Border-color: var(--gray-300)
  Shadow: var(--shadow-md)
  Transform: translateY(-1px)
```

### Inputs

#### Text Input
```css
Background: white
Border: 1px solid var(--gray-300)
Border-radius: var(--radius-lg)
Padding: 0.5rem 0.75rem
Font-size: var(--text-sm)
Color: var(--gray-900)

Placeholder:
  Color: var(--gray-400)

Focus:
  Border-color: var(--primary-500)
  Outline: 2px solid var(--primary-100)
  Outline-offset: 0

Disabled:
  Background: var(--gray-50)
  Color: var(--gray-400)
  Cursor: not-allowed
```

### Toolbar

```css
Background: white
Border-bottom: 1px solid var(--gray-200)
Height: 56px
Padding: 0 1.5rem
Display: flex
Align-items: center

Button:
  Width: 32px
  Height: 32px
  Border-radius: var(--radius-md)
  Border: none
  Background: transparent
  Color: var(--gray-600)

  Hover:
    Background: var(--gray-100)
    Color: var(--gray-900)

Divider:
  Width: 1px
  Height: 20px
  Background: var(--gray-200)
  Margin: 0 0.75rem
```

### Sidebar

```css
Width: 360px
Background: white
Border-left: 1px solid var(--gray-200)
Display: flex
Flex-direction: column

Header:
  Padding: 1rem 1.25rem
  Border-bottom: 1px solid var(--gray-200)
  Font-weight: 600
  Font-size: var(--text-sm)

Content:
  Padding: 1.25rem
  Flex: 1
  Overflow-y: auto
```

### Canvas

```css
Background: var(--gray-50)
Background-pattern:
  linear-gradient(var(--gray-200) 1px, transparent 1px),
  linear-gradient(90deg, var(--gray-200) 1px, transparent 1px);
Background-size: 20px 20px;
```

---

## Interactions

### Transitions

```css
--transition-fast: 100ms;
--transition-base: 150ms;
--transition-slow: 200ms;

--ease-in-out: cubic-bezier(0.4, 0, 0.2, 1);
--ease-out: cubic-bezier(0, 0, 0.2, 1);
--ease-in: cubic-bezier(0.4, 0, 1, 1);
```

### Hover States

- Buttons: Background color change + subtle transform
- Cards: Border color + shadow elevation + 1px lift
- Inputs: Border color change only
- Icons: Color change only

### Focus States

All interactive elements must have visible focus rings:
```css
outline: 2px solid var(--primary-500);
outline-offset: 2px;
```

---

## Icons

- **Library**: Lucide Icons (16px or 20px)
- **Style**: 2px stroke, rounded caps
- **Color**: Inherit from parent, typically gray-600
- **Hover**: Transition color to gray-900

---

## Dark Mode

### Implementation

```css
[data-theme="dark"] {
  --bg-primary: var(--dark-50);
  --bg-secondary: var(--dark-100);
  --bg-tertiary: var(--dark-200);

  --text-primary: var(--dark-900);
  --text-secondary: var(--dark-700);
  --text-tertiary: var(--dark-600);

  --border-primary: var(--dark-200);
  --border-secondary: var(--dark-300);
}
```

### Color Adjustments

- Reduce opacity of shadows
- Increase border contrast slightly
- Use darker entity colors
- Soften white text to off-white (gray-50)

---

## Accessibility

### Contrast

- Text: Minimum 4.5:1 (WCAG AA)
- UI Elements: Minimum 3:1
- Large text: Minimum 3:1

### Focus Management

- Visible focus indicators on all interactive elements
- Keyboard navigation support
- Skip links for main content areas

### Reduced Motion

```css
@media (prefers-reduced-motion: reduce) {
  * {
    animation-duration: 0.01ms !important;
    transition-duration: 0.01ms !important;
  }
}
```

---

## Layout

### Grid System

```css
/* Main Layout */
display: grid;
grid-template-columns: auto 1fr auto;
grid-template-rows: auto 1fr;

/* Sidebar */
width: 360px;

/* Toolbar */
height: 56px;

/* Canvas */
flex: 1;
overflow: auto;
```

### Breakpoints

```css
--breakpoint-sm: 640px;
--breakpoint-md: 768px;
--breakpoint-lg: 1024px;
--breakpoint-xl: 1280px;
--breakpoint-2xl: 1536px;
```

---

## Data Visualization

### Relationship Lines

```css
Stroke: var(--gray-400)
Stroke-width: 2px
Stroke-linecap: round

Hover:
  Stroke: var(--primary-500)
  Stroke-width: 2px

Selected:
  Stroke: var(--primary-600)
  Stroke-width: 3px
```

### Cardinality Labels

```css
Background: white
Border: 1px solid var(--gray-300)
Border-radius: var(--radius-base)
Padding: 0.125rem 0.375rem
Font-size: var(--text-xs)
Font-weight: 600
Color: var(--gray-700)
Font-family: var(--font-mono)
```

### Field Indicators

```css
Primary Key:
  Icon: key (16px)
  Color: var(--amber-600)
  Background: var(--amber-50)

Foreign Key:
  Icon: link (16px)
  Color: var(--blue-600)
  Background: var(--blue-50)

Unique:
  Icon: fingerprint (16px)
  Color: var(--purple-600)

Nullable:
  Icon: circle-dashed (16px)
  Color: var(--gray-400)
```

---

## Best Practices

### Do's
- Use consistent spacing from the scale
- Maintain visual hierarchy through size and weight
- Use color purposefully, not decoratively
- Ensure sufficient contrast for all text
- Keep animations subtle and functional
- Test in both light and dark modes

### Don'ts
- Avoid excessive shadows or depth
- Don't use color as the only indicator
- Avoid unnecessary animations
- Don't mix different button styles in the same context
- Avoid inconsistent spacing or alignment

---

## Implementation Notes

### CSS Custom Properties

All design tokens should be defined as CSS custom properties for easy theming and consistency.

### Component Library

Build reusable components for:
- Buttons (primary, secondary, ghost, icon)
- Cards (entity, standard)
- Inputs (text, textarea, select, checkbox)
- Modals
- Dropdowns
- Tooltips

### Naming Convention

Use BEM (Block Element Modifier) for CSS classes:
```
.entity-card
.entity-card__header
.entity-card__field
.entity-card--selected
```

---

## Version History

**v4.0** (Current - 2025)
- Professional, minimal redesign
- Refined color palette
- Simplified component system
- Enhanced accessibility
- Enterprise-grade aesthetic

---

**Maintained by ERDx Design Team** | Last Updated: 2025
