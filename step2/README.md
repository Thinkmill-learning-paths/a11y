# A11y

## Step 2 - Make accessible

Make the following code accessible

### Semantic HTML

Have a look at the below HTML code and see what you can improve.
Since you don't have a design, look at the code from a semantic perspective.

```html
<!DOCTYPE html>
<html>
<head>
  <title>A11y</title>
</head>
<body>
  <div class="header">
    <span class="headline--SM">Welcome to my blog</span>
    <img class="logo" src="assets/logo.svg">
    <div class="intro">
      Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
      nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore
      eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
    </div>
  </div>

  <div class="navigation">
    <a href="/">Home</a>
    <a href="/blog">Posts</a>
    <a href="/about">About</a>
    <a href="#" onClick="login()">Login</a>
  </div>

  <a class="back-to-top" href="#" id="backToTop">⬆</a>

  <div>
    <span class="headline--XL">Sign up for the Newsletter</span>
    <form>
      Name: <input type="text" name="name">
      eMail: <input type="text" name="email">
      <a href="#" id="signup">Signup</a>
    </form>
  </div>

  <div class="footer">
    <a href="/about">About</a>
    <a href="/about">Disclaimer</a>
  </div>
</body>
</html>
```

### Dropdown

First focus on the HTML only and improve it.
Next add the javascript (use vanilla js (or jQuery if you prefer)).
You can ignore CSS as long as the dropdown functions properly.

```html
<div class="dropdown">
  <div class="btn dropdown-toggle">
    My account
    <div class="caret"></div>
  </div>
  <div class="dropdown-menu">
    <a class="dropdown-item" href="/cart">My cart</a>
    <a class="dropdown-item" href="/orders">My orders</a>
    <a class="dropdown-item" href="/details">My details</a>
    <div class="dropdown-divider"></div>
    <a class="dropdown-item" href="#">Log out</a>
  </div>
</div>
```

### Dialog

Same task as above. HTML first then js.

```html
<div class="dialog">
  <div class="dialog-inner">
    <button>X</button>
    <h1>Warning</h1>
    <p>I am a modal dialog. I am accessible to mouse, keyboard and screen reader users.</p>
    <button>OK</button>
    <button>Cancel</button>
  </div>
</div>
```
