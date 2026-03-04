# Copilot Instructions for Site Samy

## Project Overview
This is a personal HTML love letter project - a simple, single-page HTML document (`site_samy.html`) containing a styled welcome message in Portuguese. The project emphasizes simplicity and personal sentiment.

## Architecture & File Structure
- **`site_samy.html`** - The sole project file containing HTML markup, embedded CSS, and metadata
- **No external dependencies** - Pure HTML/CSS, no frameworks or build processes
- **Single responsibility** - Display a centered, attractively styled welcome message

## Styling Conventions
The project uses **embedded CSS within `<style>` tags** in the document head:

```css
.caixa {
  width: 500px;
  margin: 0 auto;  /* Center container */
}
```

**Patterns:**
- Containers use the `.caixa` class for width/centering (Spanish/Portuguese for "box")
- Inline `style` attributes on `<body>` for global styling (`background-color: plum;`)
- Colors use hex codes (`#FF00FF`) or named colors (`plum`)

## Important Guidelines for Future Changes

### ✅ DO
- Use CSS classes for layout and reusable styles (like `.caixa`)
- Use semantic HTML5 elements (`<header>`, `<section>`, `<footer>`)
- Define fonts and colors in `<style>` tags rather than inline attributes
- Test color combinations for emotional impact (the plum/magenta palette is intentional)

### ❌ DON'T
- Use deprecated `<font>` tags (current code uses these - prefer CSS instead)
- Mix inline styles with embedded CSS - consolidate styling approach
- Break the centered layout with floats or absolute positioning

## Content & Messaging
- **Language**: Portuguese (Brazilian Portuguese based on "Bem vinda")
- **Tone**: Warm, personal, romantic
- **Audience**: Directed to "Samy"
- **Preserve sentiment**: Maintain the heartfelt tone in any textual modifications

## When Modifying This Project
1. Keep changes minimal and focused on visual/textual improvements
2. Maintain the centered, simple aesthetic
3. Test color/styling changes to preserve the intended emotional effect
4. Consider accessibility (contrast ratios for text colors)
