# Lab1 Portfolio Site — Design Rationale

Name:
Date:

## 1. Grid vs. Flexbox

Where did you use CSS Grid or Flexbox? Why was that the right choice for that particular layout problem?

I used both CSS Grid and Flexbox for different layout problems. I used Flexbox for the navigation bar because the  navigation links needed to be arranged horizontally with space between them. I also used Flexbox for the checkbox area in the contact form so the checkbox and its label could be aligned neatly.
I used CSS Grid for the About section and the Projects section. The About section uses two columns for the image and text, while the Projects section uses three columns on larger screens. Grid was a good choice because it made it easy to control the columns and gaps between the content. I also changed the grid layouts with media queries so the content becomes one column on smaller screens

## 2. Accessibility Verification

2. Accessibility Verification
I used Google Lighthouse to test the accessibility of my portfolio site. The site received a 100% Accessibility score, meaning Lighthouse did not identify any accessibility issues that needed to be fixed. I also made sure my images included descriptive alt text and that my form inputs had associated <label> elements. I added a visible focus indicator using CSS so that keyboard users can see which form field is selected. These features helped make the site more accessible and contributed to the successful Lighthouse accessibility result.

## 3. Hardest Layout Problem

What was the trickiest layout or interaction problem you ran into, and how did
you solve it using CSS alone?

The hardest layout problem was making the page work across different screen sizes without using JavaScript. The navigation, About section, and project cards all needed to adjust when the screen became smaller.
I solved this using CSS media queries combined with Flexbox and Grid. At tablet sizes, the About section changes from two columns to one, and the project grid changes from three columns to two. At mobile sizes, the navigation becomes a vertical layout and the project cards become a single column. This allowed the same page to remain organized and readable on desktop, tablet, and mobile screens using CSS alone.
