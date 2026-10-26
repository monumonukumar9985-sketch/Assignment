# Assignment 1.1 — How a Website Works

### 1. Explanation

When a user enters a URL in a browser, the browser sends an HTTP or HTTPS request to the server. The server processes the request, retrieves data from the database if needed, and sends a response containing HTML, CSS, JavaScript, and other resources. The browser displays the website on the screen. HTTP transfers data, while HTTPS encrypts communication for security. A static website displays mostly fixed content, whereas a dynamic website can change content based on user input or database information. This process is called the request-response cycle.

### 2. Static vs Dynamic Website

- **Static:** Fixed content, e.g., a basic portfolio.
- **Dynamic:** Changing content, e.g., an online shopping website.

### 3. Simple HTML Code

Save as `index.html`.

```html
<!DOCTYPE html>
<html>
<head>
    <title>My Website</title>
</head>
<body>
    <h1>How a Website Works</h1>
    <p>The browser requests data from a server.</p>
</body>
</html>
```

### 4. Network Tab Practical

1. Open Chrome and visit `https://example.com`.
2. Press **F12** and select **Network**.
3. Press **Ctrl + R**.
4. Take a screenshot showing the network requests and attach it to the assignment.

### Conclusion

Browsers, clients, servers, and databases work together to load websites. Chrome DevTools helps inspect network requests and responses.