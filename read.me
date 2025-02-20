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
    <section id="payment">
        <h2>Secure Your Booking</h2>
        <button id="paypal-button">Pay Deposit via PayPal</button>
    </section>
    <script src="https://www.paypal.com/sdk/js?client-id=YOUR_PAYPAL_CLIENT_ID" defer></script>
    <script>
        function reserveDate() {
            const date = document.getElementById('date').value;
            alert(`Date Reserved: ${date}`);
        }
        
        document.addEventListener("DOMContentLoaded", function() {
            if (window.paypal) {
                paypal.Buttons({
                    createOrder: function(data, actions) {
                        return actions.order.create({
                            purchase_units: [{
                                amount: { value: '100.00' }
                            }]
                        });
                    },
                    onApprove: function(data, actions) {
                        return actions.order.capture().then(function(details) {
                            alert('Transaction completed by ' + details.payer.name.given_name);
                        });
                    }
                }).render('#paypal-button');
            } else {
                console.error("PayPal SDK failed to load.");
            }
        });
    </script>
</body>
</html>
