<!DOCTYPE html><html lang="lv">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Stradnieks.lv — Atrodi speciālistu</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }
    body {
      background-color: #0d0d0d;
      color: #ffffff;
    }
    header {
      background-color: #00ff66;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      color: #000000;
      font-size: 2rem;
    }
    nav {
      background: #111;
      padding: 10px;
      display: flex;
      justify-content: center;
      gap: 20px;
    }
    nav a {
      color: #00ff66;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      background: #1a1a1a;
      padding: 60px 20px;
      text-align: center;
    }
    .hero h2 {
      font-size: 2rem;
      margin-bottom: 20px;
    }
    .hero input {
      padding: 10px;
      width: 80%;
      max-width: 500px;
      border: none;
      border-radius: 5px;
      outline: none;
    }
    .categories {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 20px;
      padding:
