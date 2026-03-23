## static chaptered text template

This template makes it easier to host text files with chapters (such as novels) to a HTML website. The entire site is static without a database, so it can be run on static website hosts such as Neocities, Nekoweb, Netlify, Github Pages, and the like. It is designed for non-coders to focus on writing and requires minimal modifications or coding.

> Each chapter must be an HTML file in the directory

# Setup:
1. Download the repository.
2. Use a text editor such as Notepad++ or VSCode.
3. Open index.html using the text editor
4. Find comments. These comments will indicate which parts to modify.
> Comments start with `<!--` and end with `-->`**or** start with `//`. However, on styles.css it starts with `/*` and ends with `*/`.
5. Once setup, you can paste each chapter as HTML file with images in the folder.

# Preparing chapters
The easiest way to do this is through Google Docs. 
1. Go to File > Download > Web page (.html,zipped)
2. Unzip the file.
3. Move the folder into your project folder.
4. Modify index.html.

# Optional:
If you want your text to be unselectable, open Chapter_1.html, find `<body` and paste` styles="-webkit-touch-callout: none;-webkit-user-select: none; -khtml-user-select: none;-moz-user-select: none; -ms-user-select: none; user-select: none;"` after.

To center the content, open Chapter_1.html, find `<body` and paste `styles="margin:auto;"` after. 


> Known Issues
Google Fonts won't render.