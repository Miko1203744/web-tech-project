# bootstrap

Date Created: May 19, 2023 11:54 AM
Status: To Do

# 

# What is Bootstrap?

- Bootstrap is a free front-end framework for faster and easier web development
- Bootstrap includes HTML and CSS based design templates for typography, forms, buttons, tables, navigation, modals, image carousels and many other, as well as optional JavaScript plugins
- Bootstrap also gives you the ability to easily create responsive designs

**What is Responsive Web Design?**

Responsive web design is about creating web sites which automatically adjust themselves to look good on all devices, from small phones to large desktops.

<!DOCTYPE html>
<html lang="en">
<head>
<title>Bootstrap Example</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="[https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css](https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css)">
<script src="[https://ajax.googleapis.com/ajax/libs/jquery/3.6.4/jquery.min.js](https://ajax.googleapis.com/ajax/libs/jquery/3.6.4/jquery.min.js)"></script>
<script src="[https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js](https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js)"></script>
</head>
<body>

<div class="jumbotron text-center">
<h1>My First Bootstrap Page</h1>
<p>Resize this responsive page to see the effect!</p>
</div>

<div class="container">
<div class="row">
<div class="col-sm-4">
<h3>Column 1</h3>
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit...</p>
<p>Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris...</p>
</div>
<div class="col-sm-4">
<h3>Column 2</h3>
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit...</p>
<p>Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris...</p>
</div>
<div class="col-sm-4">
<h3>Column 3</h3>

<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit...</p>
<p>Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris...</p>
</div>
</div>
</div>

</body>
</html>

# Why Use Bootstrap?

Advantages of Bootstrap:

- **Easy to use:** Anybody with just basic knowledge of HTML and CSS can start using Bootstrap
- **Responsive features:** Bootstrap's responsive CSS adjusts to phones, tablets, and desktops
- **Mobile-first approach:** In Bootstrap 3, mobile-first styles are part of the core framework
- **Browser compatibility:** Bootstrap is compatible with all modern browsers (Chrome, Firefox, Internet Explorer, Edge, Safari, and Opera)

# Where to Get Bootstrap?

There are two ways to start using Bootstrap on your own web site.

You can:

- Download Bootstrap from getbootstrap.com
- Include Bootstrap from a CDN

# Create First Web Page With Bootstrap

**1. Add the HTML5 doctype**

Bootstrap uses HTML elements and CSS properties that require the HTML5 doctype.

Always include the HTML5 doctype at the beginning of the page, along with the lang attribute and the correct character set:

**2. Bootstrap 3 is mobile-first**

Bootstrap 3 is designed to be responsive to mobile devices. Mobile-first styles are part of the core framework.

To ensure proper rendering and touch zooming, add the following `<meta>` tag inside the `<head>` element:

The `width=device-width` part sets the width of the page to follow the screen-width of the device (which will vary depending on the device).

The `initial-scale=1` part sets the initial zoom level when the page is first loaded by the browser.

**3. Containers**

Bootstrap also requires a containing element to wrap site contents.

There are two container classes to choose from:

1. The `.container` class provides a responsive **fixed width container**
2. The `.container-fluid` class provides a **full width container**, spanning the entire width of the viewport

.container
