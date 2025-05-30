**<p align="right">Node.js Unleashed: Full-Stack Server Solutions That Shine</p>**

[[Start]](../Introduction.md) → **[ Node Fundamentals ]** → [[Express Mastery]](../chapter-02/2-1.md) → [[MongoDB Power]](../chapter-03/3-1.md) → [[Secure, Smart & Scalable]](../chapter-04/4-1.md) → [[YourDreamProject LIVE]](../chapter-05/5-1.md)

## Hints for "Simple Personal Portfolio Server" Challenge

1. Use the http Module<br />
   The `http` module is built into Node.js. Use `http.createServer()` to create your server.
2. Respond with a Simple Message<br />
   Use `res.end()` to send a response back to the user. Customize the message to say something like: "Welcome to [Your Name]'s Portfolio".
3. Logging Requests<br />
   Use `req.url` to get the URL of the incoming request, `Date().toISOString()` to log the current time when a request is received.
4. Handle Different Routes<br />
   Check `req.url` to determine which page the user is visiting (e.g., /about, /projects, etc.). Use `if` or `switch` statements to differentiate between pages and send the correct message.
5. HTTP Status Codes<br />
   For a successful request, use `res.writeHead(200)`. For an unknown route, use `res.writeHead(404)` to indicate "Page Not Found."
6. Keep It Simple<br />
   Start by handling the homepage (`/`) and expand to other pages (`/about`, `/projects`, `/contact`) as you go.

[Back to Challenge 1](1-5SB.md)
