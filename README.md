<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Subscription Plans</title>
  
  <!-- 📊 ChannelBoost Tracking Snippet -->
  <script>
    (function(w,d,s,u){
      let j=d.createElement(s);
      j.async=true;
      j.src="https://assets.channelboost.com/scripts/cts.js?uid=" + u;
      let f=d.getElementsByTagName(s)[0];
      f.parentNode.insertBefore(j,f);
    })(window,document,"script","139c1320-164e-42c4-9769-9e21765192c6");
  </script>

  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      padding: 2rem;
      background: #f5f5f5;
    }

    h1 {
      color: #333;
    }

    .plans {
      display: flex;
      justify-content: center;
      gap: 2rem;
      flex-wrap: wrap;
    }

    .plan {
      background: white;
      border-radius: 10px;
      padding: 1.5rem;
      width: 250px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    .price {
      font-size: 2rem;
      color: #007bff;
    }

    .btn {
      display: inline-block;
      margin: 1rem 0.5rem;
      padding: 0.7rem 1.2rem;
      border: none;
      background: #007bff;
      color: white;
      border-radius: 5px;
      cursor: pointer;
      text-decoration: none;
    }

    .btn:hover {
      background: #0056b3;
    }
  </style>
</head>
<body>
  <h1>Choose Your Plan</h1>

  <div class="plans">
    <div class="plan">
      <h2>Basic</h2>
      <p class="price">$9/mo</p>
      <p>Good for personal use</p>
      <a href="#" class="btn" onclick="trackify.trackEvent('Purchase')">Subscribe</a>
    </div>
    <div class="plan">
      <h2>Pro</h2>
      <p class="price">$29/mo</p>
      <p>Best for small teams</p>
      <a href="#" class="btn" onclick="trackify.trackEvent('Purchase')">Subscribe</a>
    </div>
    <div class="plan">
      <h2>Enterprise</h2>
      <p class="price">Contact Us</p>
      <p>Custom solutions</p>
      <a href="https://www.cin7.com/request-a-demo/" target="_blank" class="btn" onclick="trackify.trackEvent('Demo')">Book a Demo</a>
    </div>
  </div>

  <br>
  <a href="https://www.cin7.com/start-a-free-trial/" target="_blank" class="btn" onclick="trackify.trackEvent('Free trial')">Sign Up for Free Trial</a>
</body>
</html>
