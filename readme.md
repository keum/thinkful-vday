1. Intro - Why should you care/ do this
2. Example of what we're building
3. Basic Overview of Codepen (a few sentences). Create an account in code pen.
4. The entire coding session should take place in codepen
5. Make user create 1 element, explain what happened (this work well for the jQuery guide)
	1. Description of HTML elements
	2. CSS selectors, etc.
	3. Assets (pictures, etc.)
	4. Encourage users to make changes
	5. add your own assets
	6. update headers, picture, css styles
6. How to share with your lover
7. Users can share full-screen links if they have an account example
8. Next steps / stretch goals

<hr>

Valentine’s Day is just around the corner, and there's no better way to someone's heart than a handmade card - which is exactly what we're making in this tutorial. Using the power of HTML and CSS, you'll learn how to develop a website that doubles as a v-day card to wow that special someone in your life.

### HTML and CSS

Websites are made up of many things, but HTML (Hyper Text Markup Language) and CSS (Cascading Style Sheets) are the two main components. Together, they are the building blocks for every single webpage on the Internet.

Think of a greeting card. It's made up of many attributes, like text, an image, and perhaps a poem of sorts. In the world of HTML, such attributes are the elements of a webpage. Meanwhile, each of the card's attributes are usually different. Perhaps they differ by size. Or shape. Or color. Back in the web world, CSS is used to define the look and feel of a webpage. 

> Remember: HTML provides structure, while the CSS is used for styling, making websites look pretty.

Now let's turn to an actual web page ..

IMAGE

The image above is an example of what you're going to be creating. As you probably have already guessed you will be customizing this using HTML and CSS. 

Let's begin.

### Development Environment 

For this tutorial we will be using an online HTML, CSS, and JavaScript code editor called [CSSDeck](http://cssdeck.com/). Sign up for a free plan [here](http://cssdeck.com/signup). After signing up, navigate to the homepage and click the "New" button to create a new development environment. 

You should see four panes. The three smaller panes on the left are for entering your HTML, CSS, and/or Javascript code, while the large pane displays a quick preview of the entered code.

Let's look at a quick example before building our card. 

#### HTML

The following HTML code displays the text, "Hello, World".

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Bootstrap 101 Template</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="http://netdna.bootstrapcdn.com/bootstrap/3.0.0/css/bootstrap.min.css" rel="stylesheet" media="screen">
  </head>
  <body>
    <div class="container">
      <h1>Hello, world</h1>
    </div>
  </body>
</html>
```

**What's going on?**

1. The first line, `<!DOCTYPE html>` is the document type declaration, which tells the browser the version of HTML the page is using (HTML5, in our case). Without this, browsers can get confused.
2. `<html>` informs the browser that all code between the opening and closing, `</html>`, tags is HTML.
3. The `<head>` tag contains links to CSS stylesheets and Javascript files that we wish to use in our web page, as well as meta information used by search engines for classification.
4. All code that falls within the `<body>` tags are part of the main content of the page, which will appear in the browser to the end user.

This is how a standard HTML page is structured.

Copy this code in the HTML pane on CSSDeck. You should see the text "Hello, World" in the preview pane.

Next, let's add some styles.

#### CSS

The following is a what a standard CSS stylesheet looks like:

```css
.container {
  padding-top: 50px;
}

body {
  background-color: yellow;
}
```

**What's going on?**

1. The `.container` selector is associated with the same selector in our HTML document (check it out), followed by curly braces.
2. Inside the curly braces, we have a properties, which are descriptive words, like font-weight, font-size, or background color. In our case, we have `padding-top`.
3. Values are then assigned to each property, which are preceded by a colon and followed by a semi-colon. 

> http://cssvalues.com/ is an excellent resource for finding the acceptable values given a CSS property. 

Can you figure out what's going on with the body tag?

Copy and paste this code into the CSS pane of CSSDeck. Check out the preview.

Congrats! You just made your first webpage!

### V-Day Card




