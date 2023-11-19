---
title: Contact Us
description: Get connected.
---

<form action="submit_form.php" method="post" style="max-width: 400px; margin: 0 auto; text-align: left;">
    <label for="name" style="display: block; margin-bottom: 8px; border: 2px solid black; background-color: white; padding: 5px;">Name:</label>
    <input type="text" id="name" name="name" style="width: 100%; padding: 10px; margin-bottom: 16px; box-sizing: border-box; border-color: #000000;" required>

  <label for="email" style="display: block; margin-bottom: 8px; border: 2px solid black; background-color: white; padding: 5px;">Email:</label>
    <input type="email" id="email" name="email" style="width: 100%; padding: 10px; margin-bottom: 16px; box-sizing: border-box; border-color: #000000;" required>

  <label for="message" style="display: block; margin-bottom: 8px; border: 2px solid black; background-color: white; padding: 5px;">Message:</label>
    <textarea id="message" name="message" rows="4" style="width: 100%; padding: 10px; border: 2px solid black; margin-bottom: 16px; box-sizing: border-box;" required></textarea>

  <button type="submit" style="background-color: black; color: white; padding: 10px 15px; border: 4px solid white; border-radius: 4px; cursor: pointer;">Submit</button>
</form>
