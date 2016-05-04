# react-webpack-wrapper-example

An example project showing how you can use webpack and babel to convert a react component to a js file that can be consumed by non-react websites.

### Usage

1. Clone the repo
2. Run ```npm install```
3. Run ```npm run bundle-js```
4. Run the example  ```npm run example```

Step 3 will generate two files in the build folder. A chat-template.js and chat-template-min.js

### Adapting for a different component

1. Replace references to chat-template and change the method name in wrapper.js
2. Update method name and the output file names in the two webpack config files.
3. Update "index.html"
3. Run the usage steps again.
