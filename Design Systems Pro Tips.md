## Transend Platforms
Your visual language can transcend platforms to create continuity across web, iOS, Android, and email. Document and display your visual language in a prominent place within your design system’s site. This will help inform system contributors about how components should look and behave.

## Building empowering style guides with practical research
Isaak Hayes and Donna Chan delivered an interesting talk titled, “Building Empowering Style Guides with Practical Research (https://dbtr.co/empowering-style-guides),” at Clarity Conference (https://dbtr.co/clarity-conf). The talk proposes a series of useful techniques that can help you conduct research effectively for your design system. After the interviews, they use the data to create design principles, metrics, and user stories.

## Programming Design Systems
The in-progress book, Programming Design Systems by Rune Madsen, has some great chapters on color available online to read, including “A short history of color theory”.

## Checking color contrast
There are a variety of color contrast checkers (https://dbtr.co/color-contrast) you can use to ensure your color palette works for everyone who will use your products. Be sure to check contrast ratios for background and text color pairings.

## Web Content Accessibility Guidelines (WCAG) 2.0
"Line spacing (leading) is at least space-and-a-half within paragraphs, and paragraph spacing is at least 1.5 times larger than the line spacing.”

## Understanding modular scale
Learn more about modular scales to create [more meaningful typography](https://dbtr.co/meaningful-typography).

## Front-end guidelines questionnaire
Unsure where to start making decisions about your technical approach? Brad Frost has written a handy Frontend Guidelines Questionnaire to guide you.

## A starting point for code style
Start with an open source code style guide — I prefer Airbnb’s “Mostly Reasonable” rules for CSS, JavaScript, and React—then modify it to fit your needs. Be sure to include your team’s code style rules in your design system’s documentation.

## Automagically pretty
You can stop worrying about writing your JavaScript according to code syntax rules entirely by using Prettier to automatically reformat code without changing the underlying functionality.

## Stay DRY
A fundamental best practice in software development is Don’t Repeat Yourself (DRY). When two different pieces of code perform the same function, you double the possibility of bugs, unintended side effects, and the amount of time spent maintaining functionality. The goal of your design system is to DRY up your development and reduce duplication by creating reusable patterns.

## Namespacing
Working with legacy code? Choose a unique, short, and simple namespace to prefix your classes, e.g. `.ds-[component name]`. This will avoid class collisions when mixing multiple libraries on a page, and ensure you know that your `.ds-btn` class is different from the `.btn` class from Bootstrap.