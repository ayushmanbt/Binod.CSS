# How to contribute

This whole library is written in two parts of SCSS. 

`dist/_variables.scss`: Here we define all the variables required for the library. It is a partial SCSS so it is not compiled.(& it should not be)

`dist/binod.scss`: This is the main file, which must be compiled to our `binod.css`. Make changes to `binod.scss` to add new classes and all. If you are using VScode, you can use [Live Sass Compiler](https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass) extension from Ritwik Dey to Compile this scss to css in that folder.

If you are adding a new class. Please mention it in the `index.html` in the `docs folder`, with proper example. 

`dist/binod.css`: Whatever you do, **DO NOT** change this file, or else none of your changes will be saved. `binod.css` is created by compiling `binod.scss`

`docs/index.html`: This is the showcase of binod.css. Whatever new style you add. Please add it here.