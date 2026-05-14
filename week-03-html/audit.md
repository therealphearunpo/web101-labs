# Accessibility Audit Report

Website: https://www.wikipedia.org/
Date: May 15, 2026
Tools used: Lighthouse, axe DevTools, and keyboard testing

## Overview
I checked the accessibility of Wikipedia.org by using Lighthouse, axe DevTools, and also testing the website with only a keyboard. Overall, the website is quite accessible, but I still found a few problems that could make it harder for some users.

## Lighthouse Results
Lighthouse gave the website an accessibility score of 91/100. This is a good score, but it also showed some issues. For example, some form elements do not have very clear labels, some text has low contrast, and the heading order is not always correct.

## axe DevTools Findings
axe DevTools found a few important accessibility problems. Some icons, such as flag icons, may not have clear text labels for screen readers. It also found that some buttons are missing accessible names. Another issue is that some gray text does not have enough contrast against the white background.

## Keyboard Test
When I used only the keyboard to move through the website, most links and buttons worked well. However, some language links were difficult to see when focused. I also noticed that the donation banner kept the keyboard focus inside it until it was closed.

## Top 3 Issues and Fixes
1. Low contrast
The gray text is difficult to read for some users. This can be improved by using darker text colors or changing the background.

2. Missing labels
Some icons and buttons may not have clear labels for screen readers. Adding `aria-label`s or visible text would help.

3. Heading order
Some headings are not in the correct order. This should be fixed by using heading levels properly, such as `h1`, `h2`, and `h3`.

## Conclusion
In conclusion, Wikipedia.org is already fairly accessible, but there are still some problems that should be improved. Fixing the contrast, labels, and heading structure would make the website easier to use for people with visual disabilities and screen reader users.
