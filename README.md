\# Frontend Mentor - Social proof section solution



This is a custom solution to the \[Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv\_bA)\[cite: 6]. 



\## Table of contents



\- \[Overview](#overview)

&#x20; - \[The challenge](#the-challenge)

&#x20; - \[Screenshot](#screenshot)

&#x20; - \[Links](#links)

\- \[My process](#my-process)

&#x20; - \[Built with](#built-with)

&#x20; - \[What I learned](#what-i-learned)

&#x20; - \[Continued development](#continued-development)

\- \[Author](#author)



\---



\## Overview



\### The challenge



Users should be able to:

\* View the optimal layout for the section depending on their device's screen size\[cite: 5, 6].



\### Screenshot



!\[](./screenshot.jpg)



\*Note: Replace this placeholder with a screenshot of your finished project page once it's live!\*



\### Links



\* \*\*Solution URL:\*\* \[Add your Frontend Mentor solution URL here](https://your-solution-url.com)\[cite: 6]

\* \*\*Live Site URL:\*\* \[Add your live site URL here](https://your-live-site-url.com)\[cite: 6]



\---



\## My process



\### Built with



\* \*\*Semantic HTML5 markup\*\* – Structured layout utilizing `<main>` and meaningful content containers\[cite: 4, 6].

\* \*\*CSS Flexbox\*\* – Heavily used to manage alignment, direction shifting, and card layouts smoothly\[cite: 6, 7].

\* \*\*Desktop-first workflow\*\* – Styled the large-screen experience initially, followed by fine-tuned media queries for mobile optimization.

\* \*\*Google Fonts\*\* – Loaded and applied the `League Spartan` typography profile\[cite: 4, 7, 8].



\### What I learned



During this project, I strengthened my understanding of layout control and responsiveness. Specifically, I learned how to create a "staggered" appearance using CSS margins on individual elements, which creates a highly dynamic layout on desktop viewports but neatly collapses on mobile screen configurations\[cite: 7].



Here is a snippet of the CSS stagger effect I used for the rating blocks\[cite: 7]:



```css

/\* Stagger effect: each row shifts right on desktop \*/

.row-1 {

&#x20; margin-left: 0;

}

.row-2 {

&#x20; margin-left: 3rem;

}

.row-3 {

&#x20; margin-left: 6rem;

}

