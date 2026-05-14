# Accessibility Audit Report

Website: https://www.wikipedia.org/
Date: May 15, 2026
Tools: Lighthouse, axe DevTools, keyboard test

## Lighthouse Results
- Accessibility score: 91/100
- Problems found:
  - Some form inputs no clear labels
  - Gray text too low contrast
  - Headings not in correct order

## axe DevTools Findings
- Critical:
  - Flag icons no text label
  - Some buttons missing aria-label
- Serious:
  - Color contrast fail (gray text on white)
  - Same links repeated many times
  
## Keyboard Test
- Tab focus works on most links
- Some language links hard to see focus
- Donation banner modal traps focus until closed

## Top 3 Issues + Fixes
1. **Low Contrast**
   - Issue: Gray text hard to read
   - Fix: Use darker text or stronger background

2. **Missing Labels for Icons**
   - Issue: Flags have no text for screen readers
   - Fix: Add `aria-label` or visible text

3. **Heading Order**
   - Issue: Headings skip levels
   - Fix: Use `h1` -> `h2` -> `h3` in order

## Conclusion
Wikipedia.org is mostly good but still has problems with contrast, missing labels, and heading order. Fixing these will make the site easier for people with low vision and screen readers.
