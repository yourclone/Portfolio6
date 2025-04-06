---
layout: page
title: Secret Project
permalink: /secret-project/
---
<script>
  var password = prompt("Enter password to view this page:");
  if (password !== "yourpassword") {
    document.body.innerHTML = "<h2>Access Denied</h2>";
  }
</script>

This is a protected project. Replace this text with the actual content.
