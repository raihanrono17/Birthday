<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday ❤️</title>

<style>
   body {
    margin: 0;
    font-family: 'Segoe UI', sans-serif;
    color: #333;
    text-align: center;
    min-height: 100vh;

    background:
        linear-gradient(rgba(255,255,255,0.55), rgba(255,255,255,0.55)),
        linear-gradient(
            to right,
            transparent 50%,
            transparent 50%
        ),
        url("B1.png") left center / cover no-repeat,
        url("B2.png") right center / cover no-repeat;
}


    .card {
        background: white;
        max-width: 600px;
        margin: 80px auto;
        padding: 40px;
        border-radius: 20px;
        box-shadow: 0 20px 40px rgba(0,0,0,0.2);
        animation: fadeIn 2s ease;
    }

    h1 {
        color: #ff4d6d;
        font-size: 2.5rem;
    }

    h2 {
        margin-top: 10px;
        font-weight: normal;
    }

    p {
        font-size: 1.1rem;
        line-height: 1.7;
        margin-top: 20px;
    }

    .heart {
        font-size: 3rem;
        animation: pulse 1.5s infinite;
    }

    button {
        margin-top: 30px;
        padding: 12px 25px;
        border: none;
        border-radius: 25px;
        background: #ff4d6d;
        color: white;
        font-size: 1rem;
        cursor: pointer;
    }

    button:hover {
        background: #e63956;
    }

    footer {
        margin-top: 30px;
        font-size: 0.9rem;
        opacity: 0.7;
    }

    @keyframes pulse {
        0% { transform: scale(1); }
        50% { transform: scale(1.2); }
        100% { transform: scale(1); }
    }

    @keyframes fadeIn {
        from { opacity: 0; transform: translateY(20px); }
        to { opacity: 1; transform: translateY(0); }
    }
</style>
</head>

<body>

<div class="card">
    <div class="heart">❤️</div>
    <h1>Happy Birthday,My Mumina!!</h1>
    <h2>Today is all about youuu ✨</h2>

    <p id="message">
        You might take my breath away with 18 letters. BUT I CAN DO YOU ONE BETTER WITH 18 WEBPAGES❤️
    </p>

    <button onclick="surprise()">Click for a surprise 🎁</button>

    <footer>
        Made with love by Rono 💕
    </footer>
</div>

<script>
    // CHANGE THESE
    const herName = "My Mumina";
    const secretMessage = "You might take my breath away with 18 letters. BUT I CAN DO YOU ONE BETTER WITH 18 WEBPAGES❤️";

    document.getElementById("name").innerText = herName;

    function surprise() {
        document.getElementById("message").innerText = secretMessage;
    }
</script>

</body>
</html>
