# note

Date Created: May 20, 2023 12:33 AM

# **What Is SCSS? Learn How To Use SCSS To Style HTML**

**SCSS (Sassy Cascading Style Sheets) is one of [two syntaxes available](https://www.upwork.com/resources/scss-vs-sass) for the popular CSS preprocessor Sass (Syntactically Awesome Stylesheets). It can be used to style the visual elements of a webpage, including buttons, sliders, images, color schemes, fonts, themes, and layouts. As a true superset of CSS, all valid CSS is also valid SCSS.**

# How does SCSS work?

**SCSS is simply one of two syntaxes available for the CSS preprocessor Sass. Like any preprocessor, Sass works by being compiled into native CSS code that will work across any browser.**

**The real time-saving magic comes into play on the developer’s end when they can write concise SCSS code that will compile into longer CSS code. In this way, SCSS empowers developers to do more with less, without compromising on compatibility with the web.**

# **How to compile SCSS into CSS**

**The simplest way to get started with SCSS is to download a Sass compiler plugin with your preferred code editor. Your SCSS will be compiled into CSS as you code. For example, Visual Studio has a plugin called [Live Sass Compiler](https://marketplace.visualstudio.com/items?itemName=glenn2223.live-sass) which will compile anything you write into your .scss file into vanilla CSS within a corresponding .css file with the same name every time you save.**

# The advantages of using SCSS

**SCSS is a great way to improve your CSS workflow. It can help you keep your code clean and organized, and make it easier to maintain your stylesheets over time.**

**Here is a quick overview of the benefits of SCSS:**

**Increased productivityBetter code organizationImproved maintainability and readabilityMore powerful than CSS alone**

**Of course the biggest advantage of SCSS is that it adds features to CSS code that are not available in the CSS standard. In the next section we will look at how these new SCSS features make it easier to style HTML.**

# How to use SCSS to style HTML

**Programming features like variables, nesting, and mixins reduce the need for code reuse. They give you the ability to declare something once, and invoke it throughout your stylesheets without having to repeat yourself for each element on a page. Let’s take a closer look at each of those features:**

# **Nesting**

**One of the most notable advantages SCSS has over CSS is the ability to use nested syntax. In SCSS, nesting allows you to group code within other code. This can be used to create cleaner and more efficient stylesheets.**

**For example, the following CSS code requires us to define style rules for our body one by one like so:**

**‍**

**SCSS gives us the ability to nest the CSS selectors targeting various sub elements under the “body” section of the page under the main “body” selector  like so:**

**‍**

**Not only does nesting make it easier for developers to target specific elements of a page, it makes the code easier to read too.**

# **Variables**

**SCSS also supports variables. Variables can be used to store values that will be used throughout the stylesheet. This can be helpful when working with colors, sizes, and other values that might need to be changed frequently.**

**The following example shows how to create and use a variable in SCSS:**

**‍**

**In this example, the $primary-color variable is used to set the background color of all .button elements. If the primary color needs to be changed, it can be updated in one place (the variable declaration) instead of throughout the entire stylesheet.**

# **Mixins**

**In SCSS, mixins allow you to create groups of CSS declarations that can be reused throughout the stylesheet. This can be helpful when working with vendor prefixes, complex animations, and other code that might need to be used in multiple places.**

**The following example shows how to create and use a mixin in SCSS:**

**‍**

**In this example, the border-radius mixin is used to add a border radius to all .button elements. This is more efficient than adding the code for each browser prefix separately.**

# SCSS vs CSS: The differences

**The main difference between SCSS and CSS is that SCSS is a syntax for the Sass preprocessor while CSS is a style sheet language for describing how HTML elements should be displayed by a browser. Below is a quick summary of their differences:**

**SCSSCSSSyntax for the CSS preprocessor SassStyle sheet languageLong history of supporting variables which can be used anywhere in the stylesheet.Native support for CSS variables is relatively recent, and can only be used to store values and UI tokens.Nested syntax which can seamlessly nest both properties and other selectors.A single selector can nest properties, but not other selectorsSupports mixinsDoes not support mixins**
