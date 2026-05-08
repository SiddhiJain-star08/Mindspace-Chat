<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MindSpace Chat</title>

  <style>

    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family:Arial, sans-serif;
    }

    body{
      background:linear-gradient(135deg,#4c1d95,#312e81,#be185d);
      color:white;
    }

    .hero{
      height:100vh;
      display:flex;
      flex-direction:column;
      justify-content:center;
      align-items:center;
      text-align:center;
      padding:20px;
    }

    .hero h1{
      font-size:70px;
      margin-bottom:20px;
    }

    .hero p{
      font-size:24px;
      color:#e5e7eb;
      margin-bottom:30px;
    }

    .btn{
      background:#ec4899;
      color:white;
      padding:15px 35px;
      border:none;
      border-radius:50px;
      text-decoration:none;
      font-size:18px;
      transition:0.3s;
    }

    .btn:hover{
      background:#db2777;
    }

    section{
      padding:80px 20px;
    }

    .container{
      max-width:1000px;
      margin:auto;
    }

    .card{
      background:rgba(255,255,255,0.1);
      padding:30px;
      border-radius:25px;
      backdrop-filter:blur(10px);
      margin-top:20px;
    }

    h2{
      font-size:42px;
      margin-bottom:20px;
      color:#f9a8d4;
    }

    .cards{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
      gap:20px;
      margin-top:40px;
    }

    .work-card{
      background:rgba(255,255,255,0.1);
      padding:30px;
      border-radius:25px;
      text-align:center;
      transition:0.3s;
    }

    .work-card:hover{
      transform:translateY(-10px);
    }

    .work-card h3{
      margin:15px 0;
      font-size:28px;
    }

    .contact{
      text-align:center;
    }

    .email-btn{
      display:inline-block;
      margin-top:20px;
      background:#3b82f6;
      color:white;
      padding:15px 35px;
      border-radius:50px;
      text-decoration:none;
      font-size:18px;
    }

    footer{
      text-align:center;
      padding:30px;
      border-top:1px solid rgba(255,255,255,0.2);
      color:#d1d5db;
    }

  </style>

</head>

<body>

  <div class="hero">

    <h1>MindSpace Chat 💜</h1>

    <p>Your Safe Space To Talk.</p>

    <a href="#contact" class="btn">Contact Us</a>

  </div>

  <section>

    <div class="container card">

      <h2>Our Story</h2>

      <p style="font-size:20px; line-height:35px; color:#e5e7eb;">
        I am Siddhi Jain, a Class 8 student of Indira National School, Pune.
        I created MindSpace Chat to give teenagers a safe and supportive space
        where they can express feelings, connect with others, and feel emotionally
        supported without fear of judgement.
      </p>

    </div>

  </section>

  <section>

    <div class="container">

      <h2 style="text-align:center;">How It Works</h2>

      <div class="cards">

        <div class="work-card">
          <div style="font-size:50px;">💬</div>
          <h3>Join</h3>
          <p>Become part of a positive and supportive student community.</p>
        </div>

        <div class="work-card">
          <div style="font-size:50px;">🌸</div>
          <h3>Chat Safely</h3>
          <p>Share thoughts anonymously in a judgement-free space.</p>
        </div>

        <div class="work-card">
          <div style="font-size:50px;">💜</div>
          <h3>Feel Supported</h3>
          <p>Connect with people who understand and support you emotionally.</p>
        </div>

      </div>

    </div>

  </section>

  <section id="contact">

    <div class="container card contact">

      <h2>Contact Us</h2>

      <p style="font-size:20px; color:#e5e7eb;">
        We'd love to hear your ideas and feedback.
      </p>

      <a href="mailto:siddhijainy@gmail.com" class="email-btn">
        siddhijainy@gmail.com
      </a>

    </div>

  </section>

  <footer>

    Made By Students, For Students 💜

  </footer>

</body>

</html>
