##Babel
Babel transforms the ES6 JS into ES5 so that the browsers can understand it.
An essential package because I'm using JSX in React.

##Webpack
Bundles all JS into a single file, not only the ones I wrote but also the NPM
packages. Works together with Babel to convert ES6 to ES5.
###Six configuration options
    - context: The path to my client-side JS folder
    - entry: The entry point for my application
    - module.loaders: Specifies how each file should be processed before adding
        it to the bundle. Only one, Babel. Tells it to convert it to ES5, before
        being added to my bundle. Only one, Babel. Tells it to convert it to
        ES5, before merging it to my bundle.
    - resolveLoader: Where Webpack should look for loaders.
    - resolve: Where Webpack should look for files referenced by import() or
        require(). Import npm packages.

###"npm run compile"
Lets you see the boilerplate that webpack creates along with my code. Run only
for demonstration purposes.
