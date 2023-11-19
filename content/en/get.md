---
title: Contact Us
description: Get connected.
---

<head>
  <style>
    form {
            max-width: 400px;
            margin: 20px auto;
            background-color: white;
            padding: 20px;
            border: none;
        }
        input,
        textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 16px;
            box-sizing: border-box;
            border: 2px solid #000;
        }
        button {
            background-color: black;
            color: white;
            padding: 10px 15px;
            border: 2px solid #fff;
            border-radius: 4px;
            cursor: pointer;
        }
  </style>
</head>
<body>
  <form action="submit_form.php" method="post">
    <input type="text" placeholder="Name" id="name" name="name" required>
    <input type="email" id="email" placeholder="Email" name="email" required>
    <textarea id="message" name="message" placeholder="Message" rows="4" required></textarea>
  <button type="submit">Submit</button>
</form>
</body>
