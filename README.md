# Frontend Mentor Challenge - Bookmark landing page

This is my solution to the [Bookmark Landing Page Challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bookmark-landing-page-5d0b588a9edda32581d29158).

## The challenge

Your users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

## My personal project goals

Creating this project I wanted to focus on _Web Accessibility_, to learn and implement some basics of it, as well as trying to make that the website looks good on any device.

## Built with

- [Astro](https://astro.build/) - Static Site Generator
- S(CSS)
- CSS Grid & Flex
- Vanilla JavaScript

## What I learned

Web Accessibility is a very broad topic and can be really overwhelming for a beginner. Some of the important things for accessible websites that I learned are:

- using semantic HTML
- checking color contrast,
- making skip navigation link that takes the user to the main content
- keep in mind keyboard accessibility. With JavaScript I improved keyboard accessibility by allowing users to move between items using arrow keys (main navigation, features section, footer navigation, accordion) and using Esc key to always navigate back to the first item.
- focus is very important for keyboard accessibility, and I created a custom focus style by following some guidelines,
- ARIA attributes are used to improve web accessibility but it's important to be careful when using them. Some of the attributes that I used in this project are: aria-label, aria-labeledby, aria-hidden, aria-controls, aria-pressed,
- it's important that every image have alt text. If the purpose of the image is descriptive, we should use empty alt text so that they can be ignored by assistive technologies.

## Useful resources

- [Accessible Astro Components by Mark Teekman](https://github.com/markteekman/accessible-astro-components)
- [Decorative Images](https://www.w3.org/WAI/tutorials/images/decorative/)
- [Using aria-pressed](https://www.accessibility-developer-guide.com/examples/sensible-aria-usage/pressed/)
