## General

1. https://frontendmasters.com/courses/javascript-accessibility/
2. https://egghead.io/courses/develop-accessible-web-apps-with-react
2. MDN - Accessibility <https://developer.mozilla.org/en-US/docs/Web/Accessibility>
3. web.dev - Accessible to all <https://web.dev/accessible/>
4. Web Content Accessibility Guidelines (WCAG) Overview <https://www.w3.org/WAI/standards-guidelines/wcag/>
5. Accessibility <https://developers.google.com/web/fundamentals/accessibility>
6. A11ycasts with Rob Dodson <https://youtube.com/playlist?list=PLNYkxOF6rcICWx0C9LVWWVqvHlYJyqw7g>
7. WebAIM - Introduction to Web Accessibility <https://webaim.org/intro/>
8. Styling buttons, the right way <https://fvsch.com/styling-buttons>
9. Applied Accessibility <https://www.freecodecamp.org/learn/responsive-web-design/#applied-accessibility>
10. https://www.smashingmagazine.com/2022/11/guide-keyboard-accessibility-javascript-part2/

## Mobile navigation

1. https://www.smashingmagazine.com/2022/11/navigation-design-mobile-ux/

## Other

1.Building websites for Safari Reader Mode and other reading apps. <https://medium.com/@mandy.michael/building-websites-for-safari-reader-mode-and-other-reading-apps-1562913c86c9>
2. I Used The Web For A Day Using A Screen Reader <https://www.smashingmagazine.com/2018/12/voiceover-screen-reader-web-apps/>
3. I Used The Web For A Day With Just A Keyboard <https://www.smashingmagazine.com/2018/07/web-with-just-a-keyboard/>
4. A More Accessible Web <https://open.nytimes.com/a-more-accessible-web-fa87592da6d2>

## Semantic HTML
1. Semantic HTML: The Unbearable Rightness of Being <https://ux.shopify.com/semantic-html-the-unbearable-rightness-of-being-9b3c493e1791?gi=9f4671eb1680#.m5d0oty4r>
2. A Look Into Proper HTML5 Semantics <https://www.hongkiat.com/blog/html-5-semantics/>
3. Let’s Talk about Semantics <http://html5doctor.com/lets-talk-about-semantics/>
4. The practical value of semantic HTML <https://brucelawson.co.uk/2018/the-practical-value-of-semantic-html/>
5. Understanding semantics <https://tink.uk/understanding-semantics/>
6. Use semantic HTML for easy keyboard wins <https://web.dev/use-semantic-html/>
7. WTF, forms? - (styling form elements) <http://wtfforms.com/>

## Media Accessibility

1. https://web.dev/media-accessibility/

## React Accessibility

1. https://reactjs.org/docs/accessibility.html
2. https://www.freecodecamp.org/news/designing-keyboard-accessibility-for-complex-react-experiences/


## Golden Points

1. Accessibility tree
2. HTML elements in top to bottom of the page, regardless of CSS positioning(?)
3. Use native HTML elements
4. semantic HTML vs "Div Soup"
4. Use <a> for
   -  internal navigation
   -  outwards link
      Use custom style to make it look like a btn if needed by the design
5. Use button(s) for
        feature that require clicks within the page,
        eg widgets like collapse, accordion, tab widget etc..
        eg use custom style to make it look like a link if needed by the design
6. keyboard navigation
7. Keep and show focus
8. Tab navigation
9. tabindex="0"
10. When to use nav?
11. Link to go back to the top of page
12. alt attribute for non descriptive images
13. leave blank alt="" for decorative images
14. aria attributes
15. aria attribute to elements with description
16. aria attribute to exclude elements not relevant to screen reader (eg decorative images)
17. Media accessibility (eg audio, video - captions, transcripts etc..)
