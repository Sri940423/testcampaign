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
      background: linear-gradient(to right, #e0f7fa, #f1f8e9);
      color: #333;
    }

    h1 {
      margin-bottom: 2rem;
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
      padding: 2rem 1.5rem;
      width: 280px;
      box-shadow: 0 10px 20px rgba(0,0,0,0.1);
      transition: transform 0.2s;
    }

    .plan:hover {
      transform: translateY(-5px);
    }

    .price {
      font-size: 2rem;
      color: #007bff;
      margin: 1rem 0;
    }

    .btn {
      display: block;
      width: 100%;
      padding: 0.8rem;
      margin-top: 1.2rem;
      background: #007bff;
      color: white;
      border: none;
      border-radius: 5px;
      font-size: 1rem;
      cursor: pointer;
      text-decoration: none;
      box-shadow: 0 5px 10px rgba(0,0,0,0.1);
      transition: background 0.3s ease;
    }

    .btn:hover {
      background: #0056b3;
    }

    .footer-btn {
      max-width: 280px;
      margin: 3rem auto 0;
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

  <div class="footer-btn">
    <a href="https://www.cin7.com/start-a-free-trial/" target="_blank" class="btn" onclick="trackify.trackEvent('Free trial')">Sign Up for Free Trial</a>
  </div>
</body>
</html>
