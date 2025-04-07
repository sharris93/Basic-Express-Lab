# 🏃‍♂️ Express Basics Practice

This short exercise will help you get comfortable with the **core concepts of Express**—a minimal and flexible Node.js web application framework.

## 🧠 Objectives

By the end of this exercise, you should be able to:

- Set up a basic Express server
- Use middleware to log incoming requests
- Create multiple routes that send back simple HTML responses

## 🚀 Instructions

1. **Initialize your project**

   ```
   touch server.js
   npm init -y
   npm i express
   ```

2. **Create your Express app**

   In a file called `server.js`:

   - Set up an Express server that listens on port `3000`
   - Add middleware that logs the request method and URL to the console
   - Create the following routes:
     - `/` → returns an `<h1>Home Page</h1>`
     - `/about` → returns an `<h1>About Us</h1>`
     - `/contact` → returns an `<h1>Contact Page</h1>`
     - `/services` → returns an `<h1>Our Services</h1>`

3. **Run your server**

   ```
   nodemon
   ```

4. **Test it out in your browser or with Postman!**

---

## 💡 Bonus Challenge
- Create a 404 handler for any route that isn’t defined.

---

## ✅ Example Output (in browser)

Visiting `http://localhost:3000/about` should show:

```
<h1>About Us</h1>
```

And in your terminal, you should see something like:

```
GET /about
```

---

Happy coding! 🎉
