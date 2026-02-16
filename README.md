<!DOCTYPE html>
<html lang="uk">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Lushnja Auto Paint | Професійне фарбування авто в Люшні</title>
  <meta name="description" content="Професійне фарбування автомобілів у Люшні, Албанія. Ідеальний блиск, гарантія 2 роки, швидке виконання. Запишіться зараз!"/>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;500;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles.css" />
</head>
<body>

  <header>
    <div class="logo">Lushnja Auto Paint</div>
    <nav>
      <a href="#hero">Головна</a>
      <a href="#about">Про нас</a>
      <a href="#services">Послуги</a>
      <a href="#gallery">Галерея</a>
      <a href="#contact">Контакти</a>
    </nav>
    <button class="btn" onclick="document.getElementById('contact').scrollIntoView({behavior:'smooth'})">Записатися</button>
  </header>

  <section id="hero">
    <h1>Професійне фарбування авто</h1>
    <h2>у Люшні, Албанія</h2>
    <p class="subtitle">Ідеальний блиск за 1–3 дні • Гарантія 2 роки • Преміум матеріали • Безкоштовний огляд</p>
    <div class="cta-group">
      <button class="btn" style="font-size:1.2rem; padding:1rem 2.5rem;" onclick="document.getElementById('contact').scrollIntoView({behavior:'smooth'})">Розрахувати вартість</button>
      <button class="btn" style="background:transparent; border:2px solid var(--orange);" onclick="document.getElementById('gallery').scrollIntoView({behavior:'smooth'})">Подивитися роботи</button>
    </div>
  </section>

  <section id="about" style="background:var(--dark);">
    <h2>Чому обирають нас?</h2>
    <p style="max-width:800px; margin:0 auto 3rem; text-align:center; font-size:1.2rem;">Ми — спеціалісти з 10+ роками досвіду в Люшні. Використовуємо тільки найкращі фарби та обладнання, щоб ваш автомобіль виглядав як новий. Швидко, якісно, з гарантією.</p>
    <div class="services-grid">
      <div class="card"><div class="card-content"><h3>Швидкість</h3><p>Від 1 дня — повне фарбування</p></div></div>
      <div class="card"><div class="card-content"><h3>Якість</h3><p>Преміум матеріали + ідеальний блиск</p></div></div>
      <div class="card"><div class="card-content"><h3>Гарантія</h3><p>2 роки на всі роботи</p></div></div>
    </div>
  </section>

  <section id="services">
    <h2>Наші послуги</h2>
    <div class="services-grid">
      <div class="card">
        <img src="https://p1.hippopx.com/preview/782/145/149/lamborghini-automotive-wallpaper.jpg" alt="Повне фарбування">
        <div class="card-content">
          <h3>Повне фарбування кузова</h3>
          <p>Від 500 € • Ідеальний колір та захист</p>
          <button class="btn">Замовити</button>
        </div>
      </div>
      <div class="card">
        <img src="https://images.pexels.com/photos/4536406/pexels-photo-4536406.jpeg" alt="Локальне виправлення">
        <div class="card-content">
          <h3>Локальне виправлення подряпин</h3>
          <p>Від 80 € • Без слідів</p>
          <button class="btn">Замовити</button>
        </div>
      </div>
      <div class="card">
        <img src="https://p3.hippopx.com/preview/447/135/black-vintage-bmw-classic-black-car-sunny-city-street-luxury-style-vintage-bmw-classic-car-black-car-city-street-luxury-car-vintage-automobile.jpg" alt="Керамічне покриття">
        <div class="card-content">
          <h3>Керамічне покриття</h3>
          <p>Захист + блиск на роки</p>
          <button class="btn">Замовити</button>
        </div>
      </div>
    </div>
  </section>

  <section id="gallery" style="background:var(--dark);">
    <h2>Наші роботи — до та після</h2>
    <div class="gallery-grid">
      <img src="https://mycarwash2go.com/wp-content/uploads/2023/09/pexels-mihis-alex-21011-1024x710.jpg" alt="BMW після фарбування" style="border-radius:12px; width:100%;"/>
      <img src="https://masproject.com.au/wp-content/uploads/2025/09/car-wap-vs-paint-job.png" alt="До/Після приклад" style="border-radius:12px; width:100%;"/>
      <img src="https://www.sofreshsocleandetailers.com/wp-content/uploads/2025/08/Is-Paint-Correction-a-Necessary-Step-Before-Detailing-in-Naples-FL-768x432.jpg" alt="Блиск після обробки" style="border-radius:12px; width:100%;"/>
      <!-- Тут встав свої фото BMW, заміни src -->
    </div>
  </section>

  <section id="contact" style="background: linear-gradient(135deg, var(--orange), #cc3700); color:var(--black);">
    <h2 style="color:var(--black);">Запишіться зараз!</h2>
    <p style="text-align:center; margin-bottom:2rem;">Відповімо за 10 хвилин. Безкоштовний огляд авто.</p>
    <form>
      <input type="text" placeholder="Ваше ім'я" required/>
      <input type="tel" placeholder="Телефон (+355 ...)" required/>
      <input type="text" placeholder="Модель авто (наприклад, BMW 320i)"/>
      <select required>
        <option value="">Оберіть послугу</option>
        <option>Повне фарбування</option>
        <option>Локальне виправлення</option>
        <option>Керамічне покриття</option>
        <option>Інше</option>
      </select>
      <textarea placeholder="Опишіть проблему або побажання"></textarea>
      <button type="submit" class="btn" style="background:var(--black); color:var(--orange); font-size:1.3rem;">Відправити заявку</button>
    </form>
    <p style="text-align:center; margin-top:2rem;">📞 +355 (069 583 4486) • WhatsApp / Instagram: @lushnjaautopaint</p>
  </section>

  <footer>
    © 2026 Lushnja Auto Paint | Люшня, Албанія | Всі права захищено
  </footer>

  <script>
    // Простий скрол до секцій + можеш додати форму на backend пізніше (наприклад, Formspree)
  </script>
</body>
</html>
