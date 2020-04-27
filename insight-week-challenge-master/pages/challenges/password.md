---
layout: page
title: Password
permalink: /challenges/password
hide: true
---

I managed to set my password to be '`password`', but then the system changed
their rules. It is now impossible to get the system to accept my password.

See if you can manage to get my very important data back.

Click [here](https://PasswordIsPassword.jac0bwilson.repl.run) to attempt to
get into my computer.

Annoyingly, the login manager doesn't believe that it is possible for anyone to
have a password of just '`password`', so it will remove it from your input.

---
<form>
    <label for="answer">Answer:</label><br>
    <input type="text" id="submission" name="submission"><br><br>
    <input type="submit" value="Submit" onclick="javascript:checkAnswer('password', document.getElementById('submission').value)">
</form>
