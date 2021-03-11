# Instagram clone SASS

####The objective of this project is to put the basic foundations of SASS into practice

Before starting the practice, it is necessary to understand the conceptual part of SASS and its different functionalities.

######• What is SASS? What does SASS stand for?
- Sass stands for Syntactically Awesome Stylesheet
- Sass is an extension to CSS
- Sass is a CSS pre-processor
- Sass is completely compatible with all versions of CSS
- Sass reduces repetition of CSS and therefore saves time
- Sass was designed by Hampton Catlin and developed by Natalie Weizenbaum in 2006
- Sass is free to download and use

######• What is a CSS pre-processor?
A CSS preprocessor is a program that lets you generate CSS from the preprocessor's own unique syntax. There are many CSS preprocessors to choose from, however most CSS preprocessors will add some features that don't exist in pure CSS, such as mixin, nesting selector, inheritance selector, and so on.

######• What does a pre-processor have to do with SASS?
In short, Sass is a CSS preprocessor, which adds special features such as variables, nested rules and mixins (sometimes referred to as syntactic sugar) into regular CSS. The aim is to make the coding process simpler and more efficient.

######• Why use SASS?
Stylesheets are getting larger, more complex, and harder to maintain. This is where a CSS pre-processor can help.

Sass lets you use features that do not exist in CSS, like variables, nested rules, mixins, imports, inheritance, built-in functions, and other stuff.

######• SASS has disadvantages? Which are?
CSS preprocessors have many advantages. But like most tools, they also have a number of drawbacks which I’ll describe here.
1. Debugging is harder
2. Compilation slows down development
3. They can produce very large CSS files
4. Maintainence and overengineering
5. Tooling and developer convenience
6. Saving generated files (or not)
7. Capability and understanding

######• What is a SASS Variable? Explain why are useful
Sass Variables are a way to store information that you want to reuse throughout your stylesheet. Variables are coming to CSS, but there's not much support at the moment and it's going to be awhile before you can use them. Fortunately they're available in Sass right now and they're easy to use.

######• Explain the SASS variables property with an example.
Sass variables are simple: you assign a value to a name that begins with $, and then you can refer to that name instead of the value itself. But despite their simplicity, they're one of the most useful tools Sass brings to the table. Variables make it possible to reduce repetition, do complex math, configure libraries, and much more.

A variable declaration looks a lot like a property declaration: it’s written ```<variable>: <expression>```. Unlike a property, which can only be declared in a style rule or at-rule, variables can be declared anywhere you want. To use a variable, just include it in a value.
```
$base-color: #c6538c;
$border-dark: rgba($base-color, 0.88);

.alert {
  border: 1px solid $border-dark;
}
```

######• What is a mixin? Why is it important? Give an example
The @mixin directive lets you create CSS code that is to be reused throughout the website.
A mixin is defined with the @mixin directive.

SASS @mixin Syntax:
```
@mixin important-text {
  color: red;
  font-size: 25px;
  font-weight: bold;
  border: 1px solid blue;
}
```

######• What is SCSS? Give an example
1. Stands for Sassy CSS
2. Similar to CSS (uses curly braces and semicolons)
3. Any valid CSS is valid SCSS
4. ```.scss``` extension

```
body {
  background-color:#000;
  color:#fff;
}
```

######• What is SASS? Give an example
1. Stands for Syntactically Awesome Style Sheets
2. Uses strict indentation (like Python)
3. CSS code cannot be used as SASS
4. ```.sass``` extension

```
body
  background-color:#000;
  color:#fff;
```

######• What is the difference between .scss and .sass syntax.
1. SASS is used when we need a original syntax, code syntax is not required for SCSS.
2. SASS follows strict indentation, SCSS has no strict indentation.
3. SASS has a loose syntax with white space and no semicolons, the SCSS resembles more to CSS style and use of semicolons and braces are mandatory.
4. SASS file extension is .sass and SCSS file extension is .scss.
5. SASS has more developer community and support than SCSS.


######• In which cases would we use SCSS? And in which cases would we use SASS?


######• Explain how traditional CSS and Preprocessed CSS workflows are different.

######• Can we create functions with SASS? If it is true, give an example.

######• What is nesting? Is it useful? Give an example of nesting

######• Why use @import?

######• How can we import other CSS/SASS files in SASS? Give an example

######• Explain the concept of inheritance in SASS.

######• Why use @extend? Give an example
