## validateCookies Middleware

### General information

We have created a middleware function that validates incoming cookies and sends a 400 response if cookies are invalid. We use the cookie-parser middleware to parse incoming cookies off the req object and pass them to our cookieValidator function. The validateCookies middleware returns a Promise that upon rejection will automatically trigger our error handler.

