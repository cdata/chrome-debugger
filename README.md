# Chrome Debugger Element

This element demonstrates one possible way to use the Chrome Remote Debugging
Protocol from client-side JavaScript. In this case, the demonstration shows
how Timeline allocation information can be accessed.

## Instructions

1. Launch an instance of Chrome with remote debugging enabled, and web security
disabled (**NOTE: do not browse the internet with web security disabled!**
You should only use this for testing locally). For example:

```sh
/Applications/Google\ Chrome\ Canary.app/Contents/MacOS/Google\ Chrome\ Canary --remote-debugging-port=9222 --disable-web-security
```

2. Run an HTTP server from the root of this repository. Let's assume you run it
on `http://localhost:8080`.

3. Open `http://localhost:8080/demo` - this page represents the debugger.

4. Open `http://localhost:8080/demo/debug-target.html` in another tab. This is
the page that will be debugged.

5. Go back to the debugger page. Toggle the button to record counters. Toggle
it again to end recording.


