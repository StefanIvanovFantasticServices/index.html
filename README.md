 <!DOCTYPE html>
<html>
<head>
<script src="https://wchat.freshchat.com/js/widget.js"></script>
</head>
<body>
<h1>A super-special-mega-awesome site for testing purposes</h1>
<p>Copyright Shawn 2018</p>
<script>
  window.fcWidget.init({
    token: "5fb3aa44-f7a9-4758-8806-f1acfa3e6009",
    host: "https://wchat.freshchat.com"
  });
</script>
<script>
  // Make sure fcWidget.init is included before setting these values
  // To set unique user id in your system when it is available
  window.fcWidget.setExternalId("john.doe1987");
  // To set user name
  window.fcWidget.user.setFirstName("John");
  // To set user email
  window.fcWidget.user.setEmail("john.doe@gmail.com");
  // To set user properties
  window.fcWidget.user.setProperties({
    plan: "Estate",                 // meta property 1
    status: "Active"                // meta property 2
  });
</script>

</body>
</html>
