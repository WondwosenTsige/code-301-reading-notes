
### [Table of Contents](https://wondwosentsige.github.io/code-301-reading-notes/Home)

## Read 03

### Flexbox and Templating

- Javascript templating is a fast and efficient technique to render client-side view templates with Javascript by using a JSON data source. The template is HTML markup, with added templating tags that will either insert variables or run programming logic.

- __Mustache__ *is a logic-less template syntax. It can be used for HTML, config files, source code — anything. It works by expanding tags in a template using values provided in a hash or object.*


- Below, we see two braces around {{ name }}. This is Mustache syntax to show that it is a placeholder. When Mustache compiles this, it will look for the ‘name’ property in the object we pass in, and replace {{ name }} with the actual value, e,g, “Wondwosen”.

    Mustache.render(“Hello, {{name}}”, { name: “Wondwosen” });
    // returns: Hello, Wondwosen

- If you intend you use mustache with Node and Express, you can use mustache-express. Mustache Express lets you use Mustache and Express together easily.

- To install with NPM: $ npm install mustache --save



...................................................................................
__Attributions for the following Reference materials and their authors__


[Templating with Mustache](https://medium.com/@1sherlynn/javascript-templating-language-and-engine-mustache-js-with-node-and-express-f4c2530e73b2)

[A Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

[ Mustache.js Official Documentation](https://github.com/janl/mustache.js)

























[>> NEXT (Read-04)](https://wondwosentsige.github.io/code-301-reading-notes/class-04)


