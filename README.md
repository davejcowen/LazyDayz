<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coastal Living Vacation Rental</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
</head>
<body>
    <header>
        <h1>Welcome to Coastal Living Vacation Rental</h1>
    </header>
    <section id="property-details">
        <h2>About the Property</h2>
        <p>Welcome to coastal living at its finest! This 2-bedroom home offers the ultimate blend of durability and location...</p>
        <img src="images/property1.jpg" alt="Waterfront View">
        <img src="images/property2.jpg" alt="Living Room View">
        <img src="images/property3.jpg" alt="Kitchen View">
        <img src="images/property4.jpg" alt="Interior View">
        <div class="video-container">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/owwUBLRpGVA" frameborder="0" allowfullscreen></iframe>
        </div>
    </section>
    <section id="booking">
        <h2>Book Your Stay</h2>
        <label for="date">Select Date:</label>
        <input type="date" id="date">
        <button onclick="reserveDate()">Reserve</button>
    </section>
    <script>
        function reserveDate() {
            const date = document.getElementById('date').value;
            alert(`Date Reserved: ${date}`);
        }
    </script>
</body>
</html>
