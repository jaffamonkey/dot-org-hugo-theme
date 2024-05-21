---
title: Accessbility and SDLC
description: Accessbility and SDLC
---

# Phases of SDLC and Accessibility

To effectively integrate accessibility into the SDLC, it is essential to consider it at every phase of development.

## Planning
* Define accessibility goals and requirements at the outset. This includes understanding legal obligations and setting clear objectives for compliance with standards like WCAG.
* Engage with users with disabilities, to gather insights and requirements (suprisingly few do)

## Analysis
* Conduct research to understand the needs of users with disabilities. This involves creating personas and user stories that reflect their requirements.
* Assess existing systems and content for accessibility issues to identify areas needing improvement, and generate an Accessibility Statement.

## UI/UX Design
* Apply inclusive design principles following POUR) to create wireframes and prototypes. Ensure that design elements such as color contrast, font sizes, and navigation structures are accessible.
* Design forms, buttons, and other interactive elements to be easily usable by all users, including those relying on assistive technologies.

## Development
* Use semantic HTML to ensure that content is structured in a way that is easily interpretable by screen readers and other assistive technologies.
* Implement ARIA roles and attributes to enhance the accessibility of dynamic content.
* Ensure that all functionality is accessible via keyboard, providing logical tab order and focus indicators.

## Testing
* Utilize automated tools like Axe, WAVE, and Lighthouse to identify accessibility issues early in the development process.
* Conduct manual testing with assistive technologies such as screen readers (e.g., JAWS, NVDA) and voice recognition software.
* Involve users with disabilities in usability testing to identify practical issues and gather feedback.

## Deployment
* Provide an accessibility statement that outlines the accessibility features of the product and offers contact information for reporting issues.
* Monitor accessibility post-deployment to ensure ongoing compliance and address new issues as they arise.

## Maintenance
* Perform regular accessibility audits to ensure that updates and new features continue to meet accessibility standards.
* Encourage feedback from users with disabilities to continuously improve accessibility.

## Tools and Resources
* The Web Content Accessibility Guidelines (WCAG) provide comprehensive standards for web and mobile app accessibility.
* For mobile apps, [Apple's Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/accessibility) and [Android's Accessibility Principles](https://developer.android.com/guide/topics/ui/accessibility), should also be taken into consideration.
* Tools such as Axe, WAVE, and Lighthouse help automate the detection of accessibility issues.
* Use frameworks and libraries that support accessibility.
