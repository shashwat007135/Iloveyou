<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Proposing Richa</title>
<style>
    body {
    width: 100%;
    height: 100%;
        font-family: Arial, sans-serif;
        text-align: center;
        margin: 0;
        padding: 0;
        background-color: #f7f7f7;
    }
    #content {
        margin-top: 50px;
        background-color: #fff;
        border-radius: 10px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        padding: 20px;
        max-width: 600px;
        margin-left: auto;
        margin-right: auto;
    }
    h1 {
        color: #333;
    }
    p {
        color: #666;
        line-height: 1.6;
    }
    button {
        background-color: #4CAF50;
        color: white;
        padding: 10px 20px;
        font-size: 16px;
        border: none;
        border-radius: 5px;
        cursor: pointer;
        margin: 10px;
        transition: transform 0.2s;
    }
    button:hover {
        transform: scale(1.05);
    }
    #no-button {
        position: relative;
    }
    #photo-section {
        margin-top: 50px;
    }
    .card {
        display: inline-block;
        background-color: #fff;
        border-radius: 10px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        padding: 20px;
        margin: 10px;
    }
    .card img {
        width: 200px;
        height: 200px;
        border-radius: 10px;
        margin-bottom: 10px;
    }
    #download-certificate {
        display: none;
        margin-top: 20px;
    }
</style>
</head>
<body>
    <div id="content">
        <h1>Proposing Richa</h1>
        <p>
            My lovely Richa,I know I didn’t ask you to be my Love in the traditional way, but I wanted to express my love and appreciation for you nonetheless. This past week, as we celebrated together, I couldn't help but feel overwhelmed by the depth of our connection. It's true that our relationship is unique, perhaps even unconventional, but that only makes it all the more special to me.
    
    As I look back on our journey together, I'm reminded of countless moments filled with laughter, joy, and love. Your infectious laughter brings warmth to my heart, and your mere presence is enough to ease any worries or doubts I may have. Your love has truly enriched my life in ways I could never have imagined.
    
    Tomorrow, as the world celebrates love on Valentine's Day, I find myself reflecting on just how lucky I am to have you in my life. You are the epitome of everything I could ever want in a partner - caring, compassionate, and endlessly supportive. There's no one else I would rather spend this special day with than you.
    
    So, my love, I'm reaching out to ask: Will you be my Girlfriend? Not just for this day, but for every day that follows, for the rest of our lives. I promise to cherish and love you with all my heart, today and always.
        </p>
        <button id="yes-button">Yes</button>
        <button id="no-button">No</button>
        <button id="download-certificate">Download Certificate</button>
    </div>



<div id="photo-section">
    <h2>Our Photos</h2>
    <div class="card">
        <img src="msg-1002117653614-179.jpg" alt="Photo 1">
        <p>Our special moments</p>
    </div>
    <div class="card">
        <img src="msg-1002117653614-175.jpg" alt="Photo 2">
        <p>Memories together</p>
    </div>
    <div class="card">
        <img src="msg-1002117653614-178.jpg" alt="Photo 1">
        <p>Our special moments</p>
    </div>
    <div class="card">
        <img src="msg-1002117653614-176.jpg" alt="Photo 1">
        <p>Our special moments</p>
    </div>
    <div class="card">
        <img src="msg-1002117653614-177.jpg" alt="Photo 1">
        <p>Our special moments</p>
    </div>
    
   
    <div id="reasons">
        <h2>5 Reasons I Choose You as My Valentine</h2>
        <p class="reason">1. Your laughter brings happiness to my heart every day.</p>
        <p class="reason">2. You're always kind and caring, making me feel loved and special.</p>
        <p class="reason">3. Your unwavering support inspires me to be my best self.</p>
        <p class="reason">4. Your presence brings comfort and warmth to my life.</p>
        <p class="reason">5. Your love is my strength, helping me overcome any challenge.</p>
        <p class="reason">Bonus Reason: You always prioritize our relationship and show how much you care for me.</p>
    </div>
    

  <script>
    document.getElementById('no-button').addEventListener('mouseover', function() {
        let button = document.getElementById('no-button');
        button.style.left = Math.random() * (window.innerWidth - button.offsetWidth) + 'px';
        button.style.top = Math.random() * (window.innerHeight - button.offsetHeight) + 'px';
    });

    document.getElementById('no-button').addEventListener('click', function(event) {
        event.preventDefault();
    });

    document.getElementById('yes-button').addEventListener('click', function() {
        document.getElementById('yes-button').style.display = 'none';
        document.getElementById('download-certificate').style.display = 'inline-block';
    });

    document.getElementById('download-certificate').addEventListener('click', function() {
        // This will open a new window with the PDF document
        window.open('certified.pdf');
    });
</script>

</body>
</html>
