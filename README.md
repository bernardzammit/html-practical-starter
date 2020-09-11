# html-practical-starter
# HTML Practical - Build a Product Responsive Landing Page

HTML means **Hyper Text Mark-up Language** and it is a special kind of text document
that is interpreted by Web-browsers to present text and graphics. 

One can use several software to create web pages such as Visual Studio Code, and Sublime.
Even the most basic text editor such as Notepad or Notepad ++ can be used. 

## Getting Started

### Prerequisites

1. Install Visual Studio Code Community Edition from https://code.visualstudio.com/
2. Refer to: https://www.w3schools.com/html/default.asp 
3. For [CSS](https://github.com/Year-11-2020/html-practical-starter/blob/master/styles.css) you can use the file provided, however you are free to modify as per your preference.

## Task 1 - Page Title

Every HTML page needs a title. The syntax for a title is 
```html
<title>Page Title</title>
```
* Open Visual Studio Code
* Add the *html* and *title* tags to the page.
* Save the file as product.html in your folder.

## Task 2 - Page Header

A header is usually located at the top of the website or right below a navigation menu. 
It often contains a logo or the website name. 

```html
<div class="header">
  <h1>My Website</h1>
  <p>A website created by me.</p>
</div>
```
The *header* is a class used to style it in the css file. 

* Open the product.html file.
* Add the  above section inside the *body* tags to the page, renaming it accordingly. 
* Optional: Add a logo instead of the *p* tag.
* Save the file.

## Task 3 - Page Navigation

A navigation bar consists of links to help visitors navigating through your website

```html
<div class="navbar">
  <a href="#">Link 1</a>
  <a href="#">Link 2</a>
  <a href="#">Link 3</a>
  <a href="#" class="right">Link 4</a>
</div>
```

* Continue editing product.html file.
* Add the  above section inside the *body* tags to the page, renaming it accordingly.
    * Link 1 - Features
    * Link 2 - How it Works
    * Link 3 - Pricing
    * Link 4 - About Us
* Optional: Add an icon along with the text for links.
* Save the file.

## Task 4 - Page Content

A column layout is a great way of grouping sections and displaying information in a web page.

```html
<div class="row">
  <div class="side">...</div>
  <div class="main">...</div>
</div>
```

If you have a look at the CSS sections for this task, you notice that there are media queries in order to make the layout responsive. Resize the browser window to see the result.

* Continue editing product.html file.
* Create a 2-column layout divded into a "side content" and a "main content"
    * Side content - list three features of the product with appropriate use of headings and bullet points
    * Main content - 
        * Add an image or video of what the product does
        * Below add the pricing options using table or divs. Using divs will allow the page to
        remain responsive.
* Optional: Experiment with various layout i.e. 1 column or 3 column etc..
* Save the file.

## Task 5 - Page Footer

At last we will add a footer

```html
<div class="footer">
  <h2>Footer</h2>
</div>
```

* Continue editing product.html file.
* Add © [Your Name] [Current Year]

## Final Notes

Good luck with your website, if you feel like, you can upload everything to a free web hosting server.

Try https://www.freehosting.com/, https://www.000webhost.com/ 

