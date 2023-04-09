# reference-website
1. Naming convention for all filenames, paths and folders
- Everything in lowercase
- No spaces
- Only letters, numbers, and dashes 
`index.html` coding sample 
2. Best practices for commit messages
- Correct spelling and grammer
- At least 3 words or 10 characters
- Start with a capital letter, and end without a period
- Start the message with an imperative verb, such as Add, Create, Fix, etc. 
- When writing the commit, think of it starting with, "This commit will..."
3. What is HTML?
- HTML stands for Hypertext Markup Language
- It is the coding language we use to describe the content of websites. 
4. Proper syntax for HTML tags
- The specific syntax should be something like this;
`<h1> This is a heading </h1>`
- the open tag is `<h1>`, the close tag is `</h1>`, with the content in between them. 
5. Explain or demonstrate commonly used html tags/elements:

    headings: h1-h6
    - These tags mark headings in order of their importance, with `<h1>` being the most important, and `<h6>` the least important. 
    p
    - This tag marks a paragraph of text, which operates as a block-level element that starts on a new line. 
    lists: ul, ol, dl
    - `<ul>` is the tag for an unordered list
    - `<ol>` is the tag for an ordered list (such as 1,2,3 or a,b,c)
    - within `<ul>` and `<ol>` tags are `<li>`s which are the individual list items 
    - `<dl>` is the tag for a descriptive list, within which there are `<dt>` (the term or name), and `<dd>` (the description of the term)
    a
    - anchor, is used for adding a hyperlink and link text - `<a href="hyperlink">Link Text</a>`
    - The open tag for a shows where the link should start, and the closing a tag shows where the link ends. 
    img
    - To link images in the HTML to be visible on the website.
    - Looks like, `<img src="image location" alt="alternative content"/>`
    figure (img & figcaption)
    - `<figure>` is the parent tag used for images, illustrations, etc. that are self-contained 
    - `<figcaption>` describes the contant of the `<figure>` tag
    - inside the `<img>` tag is where the image's source location goes 
    `<figure>`
        `<img src="image source" alt="alt text">`
        `<figcaption> Image description </figcaption>`
    `</figure>`
    q
    - tag used to mark a quote inside another element such as a paragraph
    blockquote
    - used for a large standalone quote (not embedded in a paragraph)
    cite
    - tag used around the quotes source/author
    em
    - tag used on text requiring greater emphasis - usually looks like italics 
    strong
    - tag used on text for lots of emphasis / importance / urgency - usually appears as bold text
    b
    - tag uses for keywords - looks bold without extra emphasis
    i
    - tag used for text in another laguage, for a title, or for a technical term - usually appears italic
    small
    - tag used to make small text such as copyrights or legal text - might be used in the footer for example
6. Explain block Elements and also explain the list of block elements and why they are used from below:
- Block level elements may only be used inside of the body element
- they are different from inline elements - starts on a new line, and automatically takes up the horizontal space of its parent container and the vertical space equal to its content's height 
- `<p>` and `<div>` are block elements for example

    html
    - all of the webpage html elements and content is inside this tag 
    head
    - Includes non-visible meta data info as well at the title of the webpage that comes up in the browser. 
    body
    - contains the actual content of the page, is placed below the head, inside html
    header
    - the introductory content you see at the top of a webpage, such as the company name or logo, and the navigation. 
    - headers are also within sections or articles, and include the title, subheading, or author, etc. 
    nav
    - used to navigate to below sections, usually inside header at the top of page 
    main
    - contains the main content of the page, and is only used once per page
    section
    - groups related pieces of content inside a main element 
    article
    - tag used to indicate a self-contained piece of content, such as a single entry in a blog or magazine
    - there could be multiple articles on a page
    - inside a section, inside of main
    div
    - div is a block-level element used to group content together 
    - does not affect content or layout until styled in CSS later
    aside
    - content indirectly related to the primary content 
    - may appear as a sidebar or call-out box
    footer
    - placed at the end of the webpage
    - includes information such as contact info, terms and services, copyright info, or other links. 
    span
    - inline element
    - when there is no other appropriate semantic element, used as an inline container that groups elements
    small
    - used for small print or side comments 
    - makes text one font size smaller by default 

7. Explain why accessibility is important and also explain the accessibility properties like:
- Accessibility is important when desiging a website because people use the web in different ways. Without considering accesiblity many peole with disabilities may not be able to access the info on your website or may have a bad user experience. It also is not very difficult to make a website accessible, and many accesibility features beneift everyone. 

    landmark roles
    - people using screen readers can jump directly to particular sections with landmark roles. There are <header role="banner">, <nav role="naviagtion">, <main role="main">, <aside role="complimentary">, and <footer role="contentinfo">
    aria labels
    - provided a label or description that only screen readers will read. For example, for a link, says where clicking the link will take you.
    image alternative texts
    - Descibes images, so they are accesible to people with visual impairments. Also useful for if the image does not download. 

8. What is CSS and how can we implement CSS to our html file (write a proper explanation with the code required to attach a CSS file inside html file)
- CSS stands for Cascading Style Sheets. It controls the appearance of HTML pages. 
- To implement CSS to an html file, first you need to create a css file (e.g. style.css) and place it in a css folder
- Then you need to link the css file to the html file. It is attached inside the `<head>` of the html using `<link>`, which looks like the following:
` <link rel="stylesheet" href="/css/style.css"> `

9. What is the difference between CSS property and value (write explanation and an example code)
- a css property is the type of change you want to make or design you want to add, such as colour, width, or border
- a css value is assigned to a css property. For example, if the property is colour, then the value is a specific colour, like red or black. 
- the change the appearance of a header for example, you could type, 
` h1 {color: black;} `

10. Why do we use border-box property in CSS?
- A border-box property may be used because it is better for more flexible layouts.
- Its padding and border are inside of the width, instead of the default box model, where the padding and border add onto the box's width. A border-box's total width is the same as the value width. 

11. Explain different type of ways we can add spacing to an element
- the padding could be increased, pushing content away from the border
- the margin could be increased , pushing other boxes away from the box

12. What is the main difference between margin and padding?
- The main difference is that padding adds spacing inside of the box, whereas margin adds spacing outside of the box. 

13. What are different types of display properties?
- inline: elements are on the same line, but height and width properties cannot be changed 
- block: forces element to be on its own line, regardless of width
- inline-block: element is like an inline element but height and width can be changed
- none: completely removes the element

14. Write a brief explanation of flexbox property
- the flexbox property controls the flow and alignment of elements. It allows for more complicated layouts. 
- there is a parent element (the flex container) the properties are applied to, and child elements (flex items) that are affected by them 
` display: flex;`

15. What are different types of flexbox properties and what is the major difference between them?
- There is justify-content, align-items, and align-content
- justify-content works on the main axis, while align-items works on the cross axis. Align content aligns a flex container within when there is extra room on the cross-axis. 
These properties have the following values:
justify-content: flex-end, center, space-between, space-around, space-evenly
align-items: stretch, flex-start, flex-end, center
align-content: normal, flex-start, flex-end, center, space-between, space-around, space-evenly, stretch

16. Explain with code the use of flexbox property on a parent element and also explain the sub properties you might need for the flexbox property
17. Write a code example on how you will use a flexbox property on a parent element with sub properties.
18. What is CSS grid property?
19. Write the parent and two sub-properties used for CSS Grid Property.
20. What is the difference between display: flex and display: grid?
21. What sub-property we use to divide elements in CSS Grid properties?
22. What unit we use to fractionally divide the element width in CSS Grid property and what are others unit we can use alternatively? (Write a code example)
23. What is the area property in CSS grid we use for the child elements?
24. Which sub-property of display grid you can use to prevent displaying empty columns. Write a code example of that property.
25. Explain the steps to add google fonts to your CSS file and how will you link it to the html file.