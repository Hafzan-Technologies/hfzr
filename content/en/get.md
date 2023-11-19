---
title: Contact Us
description: Get connected.
---

<head>
  <style>
    body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
    form {
            max-width: 400px;
            margin: 20px auto;
            background-color: white;
            padding: 20px;
            border: 2px solid #000;
            border-radius: 8px;
            box-sizing: border-box;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        label {
            display: block;
            margin-bottom: 8px;
            border: 2px solid #000;
            background-color: white;
            padding: 5px;
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
            background-color: white;
            color: black;
            padding: 10px 15px;
            border: 2px solid #fff;
            border-radius: 4px;
            cursor: pointer;
        }
  </style>
</head>
<body>
  <form action="submit_form.php" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required>

  <label for="email">Email:</label>
    <input type="email" id="email" name="email" required>

  <label for="message">Message:</label>
    <textarea id="message" name="message" rows="4" required></textarea>

  <button type="submit">Submit</button>
</form>
</body>
