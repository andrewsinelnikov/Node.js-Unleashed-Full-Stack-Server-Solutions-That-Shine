**<p align="right">Node.js Unleashed: Full-Stack Server Solutions That Shine</p>**

[[Start]](../Introduction.md) → **[ Node Fundamentals ]** → [[Express Mastery]](#express) → [[MongoDB Power]](#mongodb) → [[YourDreamProject LIVE]](#project)

## Hints for "Simple Personal Portfolio Server" Challenge

1. Use the http Module<br />
   The `http` module is built into Node.js. Use `http.createServer()` to create your server.
2. Respond with a Simple Message<br />
   Use `res.end()` to send a response back to the user. Customize the message to say something like: "Welcome to [Your Name]'s Portfolio".

    Logging Requests:

        Use req.url to get the URL of the incoming request.

        Use new Date().toISOString() to log the current time when a request is received.

    Handle Different Routes:

        Check req.url to determine which page the user is visiting (e.g., /about, /projects, etc.).

        Use if or switch statements to differentiate between pages and send the correct message.

    HTTP Status Codes:

        For a successful request, use res.writeHead(200).

        For an unknown route, use res.writeHead(404) to indicate "Page Not Found."

    Keep It Simple:

        Start by handling the homepage (/) and expand to other pages (/about, /projects, /contact) as you go.

    Test It Locally:

        Run the server with node server.js, then open your browser at http://localhost:3000 to see the result.

        Test other routes like http://localhost:3000/about to see if they work as expected.



[Back to Challenge 1](1-5SB.md)
