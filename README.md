<<!DOCTYPE html>
<html>
<head>
  <title>Bree Kitten and Cat Store</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      padding: 20px;
      background: #f7f7fa;
      color: #222;
    }
    .intro {
      margin-bottom: 30px;
    }
    ul {
      list-style: disc inside;
      text-align: left;
      display: inline-block;
      margin: 0 auto 30px auto;
      padding: 0 20px;
    }
    .cat-cards {
      display: flex;
      justify-content: center;
      gap: 30px;
      flex-wrap: wrap;
      margin-bottom: 30px;
    }
    .card {
      background: #fff;
      border: 1px solid #ddd;
      border-radius: 10px;
      padding: 15px;
      width: 200px;
      box-shadow: 0 2px 8px #0001;
      text-align: center;
      transition: box-shadow 0.2s;
    }
    .card:hover {
      box-shadow: 0 4px 16px #0002;
    }
    .card img {
      width: 100%;
      border-radius: 8px;
      margin-bottom: 10px;
    }
    footer {
      margin-top: 40px;
      color: #666;
      font-size: 0.9em;
    }
    iframe {
      margin: 30px auto;
      display: block;
    }
  </style>
</head>
<body>
  <h1>Bree Kitten & Cat Store</h1>
  <div class="intro">
    <p>Welcome to Bree Kitten Store — find all the cats and kittens you will love!</p>
    <p>We specialize in buying and selling cats and kittens of all kinds.</p>
  </div>

  <ul>
    <li>Small or big — maybe even black and gray</li>
    <li>We have kittens and cats that will make you fall in love!</li>
    <li>Any kitten you want — we got you!</li>
  </ul>

  <div class="cat-cards">
    <div class="card">
      <img src="https://placekitten.com/200/200" alt="Small kitten">
      <strong>Small Kittens</strong>
      <div>Price: $10–$15</div>
    </div>
    <div class="card">
      <img src="https://placekitten.com/201/200" alt="Big cat">
      <strong>Big Cats</strong>
      <div>Price: $30–$50</div>
    </div>
