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
- the open tag is <h1>, the close tag is </h1>, with the content in between them. 
5. Explain or demonstrate commonly used html tags/elements:

    headings: h1-h6
    - These tags mark headings in order of their importance, with <h1> being the most important, and <h6> the least important. 
    p
    - This tag marks a paragraph of text, which operates as a block-level element that starts on a new line. 
    lists: ul, ol, dl
    - <ul> is the tag for an unordered list
    - <ol> is the tag for an ordered list (such as 1,2,3 or a,b,c)
    - within <ul> and <ol> tags are <li>s which are the individual list items 
    - <dl> is the tag for a descriptive list, within which there are <dt> (the term or name), and <dd> (the description of the term)
    a
    - anchor, is used for adding a hyperlink and link text - `<a href="hyperlink">Link Text</a>`
    - The open tag for a shows where the link should start, and the closing a tag shows where the link ends. 
    img
    - To link images in the HTML to be visible on the website.
    - Looks like, `<img src="image location" alt="alternative content"/>`
    figure (img & figcaption)
    - <figure> is the parent tag used for images, illustrations, etc. that are self-contained 
    - <figcaption> describes the contant of the <figure> tag
    - inside the <img> tag is where the image's source location goes 
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

    html
    head
    body
    header
    nav
    main
    section
    article
    div
    aside
    footer
    span
    small
