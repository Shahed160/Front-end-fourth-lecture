# Front end fourth lecture
 
HTML:

 • <!DOCTYPE html>: This declaration defines the document type and version of HTML. Here it specifies that the document is an HTML5 document.
 • <html lang="en">: This tag starts the HTML document and sets the language of the document to English.


 • <head>: This section contains meta-information about the document.
 • <meta charset="UTF-8">: This meta tag sets the character encoding of the document to UTF-8, which supports all characters and symbols in the Unicode standard.
 • <meta name="viewport" content="width=device-width, initial-scale=1.0">: This meta tag ensures the webpage is responsive by setting the viewport to match the device’s width and scale it accordingly.
 • <title>this is a home page</title>: This tag sets the title of the webpage, which appears in the browser tab.
 • <link rel="stylesheet" href="/CSS/index.css">: This link tag includes an external CSS file (index.css) from the /CSS/ directory to style the HTML document.

 • <body>: This tag represents the main content of the HTML document, which is displayed in the web browser.

Navbar


 • <div id="navbar">: This div contains the navigation bar with an id of navbar.
 • <img src="">: This img tag displays an image in the navbar.
 • <ul class="navlist">: This unordered list (ul) contains the navigation links and is styled with the class navlist.
 • <li>: Each list item (li) contains a link and button.
 • <a href="/pages/index1.html"><button class="navbutton">page 1</button></a>: This is a link (a) that wraps a button element (button) with the class navbutton, linking to index1.html.

Grid Container

 • <div class="gridcontainer">: This div contains a grid layout with the class gridcontainer.
 <div class="hoverclass"></div>: Each grid item (griditem) contains an image with the class hoverClass for hover effects.
 • <button class="buttons1">click here</button>: These button elements have the class buttons1 for styling and functionality.

Footer

 • <div id="footer">: This div contains the footer section with an id of footer.
 • <ul class="footer1">: This unordered list contains the footer buttons and is styled with the class footer1.
 • <li><button class="footerbutton1">contact us</button></li>: Each list item (li) contains a button element with the class footerbutton1.


 • #navbar: Targets the element with the ID navbar.
 • background-color: black;: Sets the background color of the navbar to black.

 • #navbar img: Targets all img elements inside the element with the ID navbar.
 • width: 110px;: Sets the width of the image to 110 pixels.
 • border-radius: 50px;: Rounds the corners of the image to create a circular effect.
 • margin-left: 50px;: Adds a left margin of 50 pixels.
 • margin-top: 20px;: Adds a top margin of 20 pixels.


 • .navlist: Targets elements with the class navlist.
 • list-style: none;: Removes bullet points from the list items.
 • display: inline-flex;: Makes the list items display inline as a flex container.
 • float: right;: Aligns the list to the right.
 • margin-top: 50px;: Adds a top margin of 50 pixels.

 • .navlist li: Targets li elements within elements with the class navlist.
 • margin-right: 50px;: Adds a right margin of 50 pixels to each list item.

 • .navbutton: Targets elements with the class navbutton.
 • font-size: 20px;: Sets the font size to 20 pixels.
 • padding: 5px;: Adds 5 pixels of padding.
 • border-radius: 20px;: Rounds the corners of the button.

 • .gridcontainer img: Targets img elements inside elements with the class gridcontainer.
 • width: auto;: Sets the width to adjust automatically.
 • height: auto;: Sets the height to adjust automatically.
 • max-width: 200px;: Sets the maximum width to 200 pixels.
 • border-radius: 10px;: Rounds the corners of the image.
 • margin-left: 30px;: Adds a left margin of 30 pixels.
 
 • .gridcontainer: Targets elements with the class gridcontainer.
 • display: grid;: Makes the container a grid container.
 • grid-template-columns: auto auto auto;: Creates three columns that automatically adjust in size.
 • grid-gap: 10px;: Sets a 10-pixel gap between grid items.
 • text-align: center;: Centers the text inside the grid items.

 • .griditem: Targets elements with the class griditem.
 • margin: auto;: Automatically adjusts the margins to center the grid item.
 • text-align: center;: Centers the text inside the grid item.
 • margin-bottom: 5px;: Adds a bottom margin of 5 pixels.

 background-color: black;
    color: white;
    text-align: center;
}

 • .footer1: Targets elements with the class footer1.
 • margin-right: 0px;: Sets the right margin to 0 pixels.
 • right: 0;: Positions the element at the right edge.
 • bottom: 0;: Positions the element at the bottom edge.
 • top: auto;: Automatically adjusts the top position.
 • padding: 40px;: Adds 40 pixels of padding.
 • display: flex;: Makes the container a flex container.
 • margin-top: 25px;: Adds a top margin of 25 pixels.
 • list-style: none;: Removes bullet points from the list items.
 • position: relative;: Positions the element relative to its normal position.
 • width: auto;: Automatically adjusts the width.
 • background-color: black;: Sets the background color to black.
 • color: white;: Sets the text color to white.
 • text-align: center;: Centers the text inside the footer.

 • .footerbutton1: Targets elements with the class footerbutton1.
 • border: 5.6em;: Sets the border width to 5.6 em units.
 • margin-left: 30px;: Adds a left margin of 30 pixels.
 • font-size: 20px;: Sets the font size to 20 pixels.
 • max-width: max-content;: Sets the maximum width to the content’s width.
 • border-radius: 50px;: Rounds the corners of the button.
 • float: left;: Aligns the button to the left.

 • .userInformation: Targets elements with the class userInformation.
 • background-color: red;: Sets the background color to red.


 • #tableDesign: Targets the element with the ID tableDesign.
 • background-color: yellow;: Sets the background color to yellow.

 • .hoverClass:hover: Targets elements with the class hoverClass when they are hovered over.
 • width: 400px;: Sets the width to 400 pixels.
 • border: 5px solid black;: Sets a solid black border with a width of 5 pixels.
 • padding: 40px;: Adds 40 pixels of padding.
 • background-color: blue;: Sets the background color to blue.

Media Queries

@media screen and (max-width: 600px) to make web page fit on mobile or tablet or whatever 
    
