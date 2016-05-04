# react-webpack-wrapper-example

An example node project showing how you can use webpack and babel to convert a react component to a js file that can be consumed by non-react websites.

The example provided is for [Chat-Template](https://github.com/sevenleaps/chat-template), a React component that enables quick prototyping of bot conversations

### Usage

1. Clone the repo
2. Run ```npm install```
3. Run ```npm run bundle-js```
4. Run the example  ```npm run example```

Step 3 will generate two files in the build folder. A chat-template.js and chat-template-min.js.

See [index.html](https://github.com/sevenleaps/react-webpack-wrapper-example/blob/master/index.html) for an example how these files are consumed.

### Adapting for a different component

1. Replace references to chat-template and change the method name in wrapper.js
2. Update method name and the output file names in the two webpack config files.
3. Update index.html
3. Run the usage steps.
