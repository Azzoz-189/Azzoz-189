## 2024-03-21 - Mailto links target blank
**Learning:** Opening `mailto:` links in a new tab (`target="_blank"`) creates a poor user experience, as it often opens a blank tab in the user's browser before launching their email client. This leaves an orphaned blank tab that the user must manually close.
**Action:** Never use `target="_blank"` on `mailto:` links. Just use a regular link and let the browser/OS handle the email client launch.

## 2024-03-21 - Missing Aria-labels on Icon links
**Learning:** Links that only contain images/icons (like social media badges) often lack context for screen readers if the `aria-label` is missing. While `alt` text on the image helps, an `aria-label` on the anchor tag itself provides a clearer, unified interaction description for assistive technologies.
**Action:** Always add descriptive `aria-label` attributes to icon-only buttons and links.