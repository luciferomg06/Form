# Form
Login or Register?
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Button</title>
  </head>
  <link rel="stylesheet" href="style1.css">
  <body>
  <div class="hero">
    <div class="form-box">
<div class="button-box">
  <div id="btn">
  </div>
  <button type="button" class="toggle-btn" onclick="login()">Log In</button>
  <button type="button" class="toggle-btn" onclick="register()">Register</button>
</div>
<div class="smedia">
  <img src="fb.jpg">
  <img src="tw.jpg">
  <img src="gp.jpg">
</div>
<form id="login" class="input-group">
  <input type="text" class="input-field" placeholder="User ID" required>
  <input type="password" class="input-field" placeholder="Enter Password" required>
  <input type="checkbox" class="checkbox"><span>Remember Password.</span>
  <button type="submit" class="submit-btn">Log In</button>
</form>
<form id="register"class="input-group">
  <input type="text" class="input-field" placeholder="User ID" required>
  <input type="email" class="input-field" placeholder="Email ID" required>
  <input type="password" class="input-field" placeholder="Enter Password" required>
  <input type="checkbox" class="checkbox"><span>I Agree to the Terms & Conditions.</span>
  <button type="submit" class="submit-btn">Register</button>
</form>

    </div>
      </div>
      <script>
        var x = document.getElementById("login")
        var y = document.getElementById("register")
        var z = document.getElementById("btn")

        function register(){
          x.style.left="-400px"
          y.style.left="50px"
          z.style.left="110px"
         }
         function login(){
           x.style.left="50px"
           y.style.left="450px"
           z.style.left="0px"
          }
        </script>
  </body>
</html>
