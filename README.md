<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Шынгысхан & Мадина — Свадебное приглашение</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #fff8f2;
      margin: 0;
      padding: 0;
      color: #3b3b3b;
    }
    header, section {
      padding: 60px 20px;
      text-align: center;
    }
    h1 {
      font-size: 2.5em;
      margin-bottom: 0.3em;
    }
    h2 {
      font-size: 2em;
      margin: 20px 0;
    }
    p {
      font-size: 1.1em;
      line-height: 1.6;
    }
    .map iframe {
      width: 100%;
      height: 400px;
      border: none;
    }
    form {
      max-width: 500px;
      margin: auto;
      display: flex;
      flex-direction: column;
      gap: 15px;
    }
    input, select, button {
      padding: 12px;
      font-size: 1em;
      border-radius: 8px;
      border: 1px solid #ccc;
    }
    button {
      background-color: #e2b4a8;
      color: white;
      border: none;
      cursor: pointer;
    }
    footer {
      text-align: center;
      font-size: 0.9em;
      padding: 30px 10px;
      color: #888;
    }
  </style>
</head>
<body>
  <header>
    <h1>Шынгысхан & Мадина</h1>
    <p>С любовью приглашаем вас отпраздновать наш особенный день</p>
    <h2>18 августа 2025</h2>
  </header>

  <section>
    <h2>Место проведения</h2>
    <p>г. Тараз, ул. Каратая Турысова, 13<br>
    Ресторан <strong>Хан Сарай</strong></p>
    <p><a href="https://www.instagram.com/khansaray_taraz?igsh=MWZ6ZnFrcDc1bjY2cQ" target="_blank">Instagram ресторана</a></p>
  </section>

  <section class="map">
    <h2>Как нас найти</h2>
    <iframe src="https://2gis.kz/taraz/geo/70000001090131741/center/71.36494731903078,42.90241508877975/zoom/17" allowfullscreen></iframe>
  </section>

  <section>
    <h2>RSVP</h2>
    <form>
      <input type="text" name="name" placeholder="Ваше имя" required>
      <select name="guests">
        <option value="1">Я приду один(а)</option>
        <option value="2">Я приду с супругом(ой)</option>
      </select>
      <input type="text" name="contact" placeholder="Ваш телефон или email">
      <button type="submit">Подтвердить участие</button>
    </form>
  </section>

  <footer>
    С любовью, Шынгысхан и Мадина 💕
  </footer>
</body>
</html>
