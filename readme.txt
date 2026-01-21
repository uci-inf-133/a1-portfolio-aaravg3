--Readme document for *Aarav Garg*, *aaravg3@uci.edu*--

A reminder on academic integrity, as described in the syllabus.

In general, the course staff expects that you will look at code and examples from many online resources as part of the assignments, particularly to resolve syntax and understand frameworks. We expect that you'll use other libraries you find, and will even require it in some assignments. These practices are often critical to the work of developers today. The best developers are adept at interpreting the examples they see, customizing them to their specific situation, and citing their sources so they can find them later. We expect you to do the same.

While learning from examples is encouraged, attempting to pass an existing project or example from the web as your own is not allowed. If you ever have a question about what is or is not appropriate, feel free to ask the course staff!

Talking to classmates about class material, assignment requirements, etc. is a great way to verify ideas and get feedback. But this distinctly does *not* permit attempting to pass off someone else’s code as your own. Talking over ideas and approaches is allowed, but the work that you produce and submit must be your own.

1. How many assignment points do you believe you completed (replace the *'s with your numbers)?

10/10
- 1/1 Readme
- 2/2 Basic HTML content
- 1/1 Basic CSS styling
- 1/1 Advanced feature
- 2/2 Responsive layout
- 1/1 Passes validation checks
- 2/2 Embraces spirit of the assignment

2. What (a) basic features, (b) CSS features, and (c) advanced features did you include in your portfolio?

(a) Basic features
- Images with alt text (profile picture on index.html)
- Headings (h1, h2, h3) and paragraphs throughout all three pages
- Links to email and LinkedIn
- Multiple pages (index.html, projects.html, experience.html) with navigation between them
- Semantic HTML tags: nav, main, aside, footer, table

(b) CSS features
- Custom colors (purple, gold, green color scheme)
- Padding and margins for spacing and readability
- Bootstrap table (table-striped) for certifications
- Google Fonts (Roboto) with fallback fonts

(c) Advanced features
- Table with multiple columns and rows for certifications (screen reader accessible)
- Navigation bar for site navigation

3. Did you ignore any of the warnings or errors presented by the accessibility checker? If so, why does this not seem like an accessibility concern? If it's useful, you can consolidate your thoughts on multiple warnings/errors if the rationale is similar.

I received 'Potential Problems' warnings but no actual errors.

Common warnings across all pages:

- My site is in English with left to right text direction, which is the default. The lang="en" attribute 
  is on the html tag. The warnings about language and direction apply mainly to sites in other languages.

- Links like "Home", "Projects", and "Experience" were flagged as unclear. These are standard navigation 
  labels that clearly indicate their purpose.

- The checker suggested headings might be used for styling. However, I used them semantically. H1 for page 
  titles, H2 for sections, H3 for subsections.

- The checker flagged the Bootstrap script. This is the official Bootstrap library that follows accessibility 
  standards.

- The checker suggested adding a skip to content link. This is typically for large sites with complex navigation. 
  My 3 page portfolio does not require it in my opinion.

- A sitemap warning appeared but a sitemap is unnecessary for a small 3 page portfolio with clear navigation.

Page specific warnings:

- Index.html: The profile image has alt="Aarav Garg profile" which describes the image.

- Projects.html: The certifications table received warnings about needing a caption. The heading "Certifications" 
  above the table already describes it. The table also has proper thead and tbody structure for screen readers.

- Experience.html: Same common warnings as other pages.

These warnings are suggestions for edge cases or larger websites in my opinion. My portfolio uses proper semantic 
HTML, descriptive alt text, clear heading hierarchy, and meaningful link text.

4. How long, in hours, did it take you to complete this assignment?

About 1-2 days in total (around 6-8 hours spread across two days). Day 1 was setting up the HTML structure and basic CSS. 
Day 2 was making it responsive, styling, and validation.

5. What online resources did you consult when completing this assignment? (list specific URLs, describe queries to Generative AI, or use of AI-based code completion)

- Bootstrap 5.3 Documentation: https://getbootstrap.com/docs/5.3/getting-started/introduction/
- Google Fonts: https://fonts.google.com/specimen/Roboto
- W3Schools HTML Tutorial: https://www.w3schools.com/html/
- W3Schools CSS Tutorial: https://www.w3schools.com/css/
- ChatGPT: Asked for color scheme suggestions for a student portfolio. Got recommendation for purple, gold, and green 
  color palette which I used in my CSS.
- ChatGPT: Asked to learn flexbox properties and syntax for navbar layout. Got explanations of display flex, justify content, 
  and align items properties which I applied to my navigation bar.
- ChatGPT: Asked to understand what some of the accessibility warnings meant since the technical terms were confusing. 
  Got general explanations of what warnings like skip to content links and table captions are used for.

6. What classmates or other individuals did you consult as part of this assignment? What did you discuss?

None. I completed this assignment independently.

7. Is there anything special we need to know in order to run your code?

No special requirements. Just open index.html in a web browser and everything should work.
