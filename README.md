# postMessage-test

Quick demo of postMessage API for communicating between frames on different origins (https://developer.mozilla.org/en/DOM/window.postMessage). Allows you to modify the `#fixture` element within the frame by sending messages to it.

Serve `index.html` on any port and `frame.html` on port `8080`.