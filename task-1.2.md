# Task 1.2: DevTools Exploration 
# DevTools Inspection - Answer Sheet

## Website 1: example.com

### Question 1: What HTML tags are used on the page?

- `<!DOCTYPE html>`
- `<html>`
- `<head>`
- `<title>`
- `<meta>`
- `<body>`
- `<div>`
- `<h1>`
- `<p>`

### Question 2: What is the page title?

**Answer:** Example Domain

### Question 3: How many headings are there?

**Answer:** 1 heading (`<h1>`)

---

## Website 2: developer.mozilla.org
### Question 1: Find the navigation menu - what tag is it wrapped in?

**Answer:** `<nav>` tag

### Question 2: How is the search bar structured?

**Answer:** The search bar is structured with:

- `<form role="search">` - wraps the entire search component
- `<input type="search">` - the search input field with placeholder text "Search MDN"
- `<button type="submit">` - the submit button with a magnifying glass icon
- Autocomplete/dropdown suggestions that appear dynamically as you type
- ARIA labels for accessibility
- Behind the scenes uses JavaScript to provide live search with categorized results

### Question 3: What happens when you hover over links (check the styles)?

**Answer:**
 When you hover over links on MDN:

- **Color changes** - The link color shifts (typically from one shade to a brighter blue)
- **Underline appears** - An underline is added to the link text
- **Smooth transition** - The effect happens smoothly (transition: 0.2s ease)

---

## Website 3: github.com

### Question 1: Identify 5 different HTML elements

**Answer:** The 5 HTML elements found on github.com are:

- `<header>` - Contains the top navigation bar and GitHub logo
- `<nav>` - Wraps the main navigation menu (Home, Features, Sign in, Sign up)
- `<section>` - Used to organize different content areas on the page
- `<form>` - Used for the login/sign-in form
- `<svg>` - Vector graphics for icons throughout the interface (GitHub octocat logo, feature icons, etc.)

### Question 2: Find a form element and list its inputs
**Answer:** The Sign In / Login Form structure:
```html
<form action="/session" method="post">
  <label for="login_field">Username or email address</label>
  <input type="text" name="login" id="login_field" required>

  <label for="password">Password</label>
  <input type="password" name="password" id="password" required>

  <input type="submit" value="Sign in">
  
  <a href="/password_reset">Forgot password?</a>
  <a href="/signup">Create an account</a>
</form>
```
**Form Inputs:**
- `<input type="text">` - Username or email address field
- `<input type="password">` - Password field
- `<input type="submit">` - Sign in button
- Hidden CSRF token field (for security)


### Question 3: Elements Panel Screenshot

Here's what you would see in the DevTools **Elements Panel**:

```html
<html>
  <head>
    <title>GitHub: Let's build from here</title>
    <meta charset="utf-8">
    <meta name="viewport">
    <link rel="stylesheet" href="...">
  </head>
  <body>
    <header>...</header>
    <nav>...</nav>
    <main>
      <section>...</section>
      <section>...</section>
    </main>
    <footer>...</footer>
  </body>
</html>
```
   
   
   
   
   
   
   
   
   
   
   

   






























