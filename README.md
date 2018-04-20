# node_notes

Node.js

In software development, Node.js is an open-source, cross-platform runtime environment for developing server-side Web applications. 
Although Node.js is not a JavaScript framework, many of its basic modules are written in JavaScript, and developers can write new modules in JavaScript. The runtime environment interprets JavaScript using Google's V8 JavaScript engine.

Node.js is not a framework, it is an environment in which you can run JavaScript. This is a common misconception with Node.js. 
Because Node.js is executed outside of the context of the web browser it does not have access to APIs that you're used to working with in the browser (BOM).


YARN

Yarn is a new package manager that replaces the existing workflow for the npm client or other package managers while remaining compatible with the npm registry. It has the same feature set as existing workflows while operating faster, more securely, and more reliably.

ReactDOM.render takes two arguments. The first argument is the UI object, which is <VariableName />. The second argument is the DOM object (in this case, document.getElementById("container")). Put together, the above code renders the TweetBox UI inside <div id="container">.

In rare cases, you may run into issues with Yarn, specifically with yarn global add. If you happen to run into any problems, substitute with npm install -g.

create-react-app is a command-line tool built by bright people at Facebook, and it’s amazing. It abstracts away all the complexity and difficulty of implementing Webpack, Babel, a dev server, a production build process, and a thousand other tedious-but-critical things.

Yarn comes with a built-in helper for using create-react-app:

yarn create react-app [your-app-name]
