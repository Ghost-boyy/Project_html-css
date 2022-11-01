
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maxmum-scale=1, user-scalable=no">
  <title>contact</title>
  <link rel="stylesheet" href="css/styles.css">
</head>
<body>
  <div id="main-container">
    <!-- Informações de endereço -->
    <div id="address-container">
      <div class="fade"></div>
      <div id="address-content">
        <h2><ion-icon name="navigate-outline"></ion-icon>Anddress</h2>
        <p>Crystal street</p>
        <h2><ion-icon name="call-outline"></ion-icon> Phone</h2>
        <p>(+1)555-1452</p>
        <h2><ion-icon name="mail-outline"></ion-icon> E-mail</h2>
        <p>Beatiz@email.com</p>
      </div>
    </div>
    <!-- Formulário para contato -->
    <div id="form-container">
      <h2>Send us a message!</h2>
      <form id="contact-form">
        <label for="name">Name:</label>
        <input type="text" name="name" placeholder="Your name">
        <label for="email">E-mail:</label>
        <input type="email" name="email" placeholder="Your  e-mail">
        <label for="phone">Phone:</label>
        <input type="text" name="phone" placeholder="Your phone">
        <label for="msg">Your message:</label>
        <textarea name="msg" placeholder="How can we help you?"></textarea>
        <input type="submit" value="Send Message">
      </form>
    </div>
  </div>

  <script src="https://unpkg.com/ionicons@5.1.2/dist/ionicons.js"></script>
</body>
</html>
