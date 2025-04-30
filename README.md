# Las-Teresitas-Apartment
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Las Teresitas Apartment</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f4f4f4; }
    header { background: #0077cc; color: white; padding: 1rem; text-align: center; }
    .gallery { display: flex; flex-wrap: wrap; justify-content: center; gap: 1rem; margin: 1rem; }
    .gallery img { max-width: 300px; height: auto; border-radius: 8px; box-shadow: 0 0 10px rgba(0,0,0,0.2); }
    .content { padding: 1rem; max-width: 800px; margin: auto; background: white; border-radius: 8px; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
    .booking { margin-top: 2rem; }
    .contact { background: #eee; padding: 1rem; border-radius: 8px; margin-top: 2rem; }
    footer { text-align: center; padding: 1rem; background: #0077cc; color: white; margin-top: 2rem; }
  </style>
</head>
<body>
  <header>
    <h1>Las Teresitas Apartment</h1>
    <p>San Andrés, Santa Cruz de Tenerife – Close to Las Teresitas Beach</p>
  </header>  <div class="gallery">
    <img src="/mnt/data/file-UduNK5T5qM9nJpTMwzReew" alt="Ocean View" />
    <img src="/mnt/data/file-YPtBV8HaSVzGQU1yZ8VT5h" alt="Bedroom" />
    <img src="/mnt/data/file-KKsan8BsmaSGukJsbYDXMV" alt="Room and Bathroom" />
  </div>  <div class="content">
    <h2>Welcome!</h2>
    <p>
      Enjoy your stay in this spacious and bright 3-bedroom, 2-bathroom apartment in San Andrés, just minutes away from the stunning Las Teresitas beach. The apartment includes a garage, elevator access, and accommodates up to 4 guests comfortably.
    </p>
    <p><strong>Price:</strong> €110 per night</p>
    <p><strong>Maximum guests:</strong> 4</p>
    <p><strong>Garage:</strong> Yes</p>
    <p><strong>Elevator:</strong> Yes</p><div class="booking">
  <h3>Book Your Stay</h3>
  <form action="mailto:MaximilianAlexander@hotmail.com" method="post" enctype="text/plain">
    <label for="name">Name:</label><br />
    <input type="text" id="name" name="name" required><br /><br />

    <label for="email">Email:</label><br />
    <input type="email" id="email" name="email" required><br /><br />

    <label for="dates">Preferred dates:</label><br />
    <input type="text" id="dates" name="dates" placeholder="e.g. July 10–15" required><br /><br />

    <label for="guests">Number of guests:</label><br />
    <input type="number" id="guests" name="guests" min="1" max="4" required><br /><br />

    <input type="submit" value="Send Booking Request">
  </form>
</div>

<div class="contact">
  <h3>Contact</h3>
  <p><strong>Phone:</strong> +34 641 259 978</p>
  <p><strong>Email:</strong> MaximilianAlexander@hotmail.com</p>
</div>

  </div>  <footer>
    <p>&copy; 2025 Las Teresitas Apartment. All rights reserved.</p>
  </footer>
</body>
</html>
