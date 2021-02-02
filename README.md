<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
  <title>Мой сайт – Новости про космос</title>
</head>
<body class="page">
  <header class="page-header">
    <div class="container">
      <h1 class="page-title">Мой сайт</h1>
      <p><i>По всем вопросам пишите:</i><br><a href="mail to:newnews-cosmos@gmail.com">mailto:newnews-cosmos@gmail.com</a></p>
    </div>
  </header>
  <main>
    <section class="about container">
      <h2 class="section-title">Привет, я ищу новости про космос</h2>
      <!-- <img class="about-image" src="img/cosmoman.jpg" width="147" height="147" alt="Неопознанный енот"> -->
      <div class="about-content">
        <p>Товарищи! Постоянное информационно-пропагандистское обеспечение нашей деятельности обеспечивает широкому кругу людей участие в формировании понятия о космосе.</p>
        <p>Это очень интересная и в обозримом будущем очень важная задача! Сделаем же маленький шаг на встречу великому космосу и познаем его тайны!</p>
      </div>
    </section>
    <section class="status container">
      <h2 class="section-title">Мой статус</h2>
      <p>#гдетодалеко!</p>
    </section>
    <section class="contacts container">
      <h2 class="section-title">Контакты для связи</h2>
        <p class="contacts-name">Cosmoman</p>
        <p><i>email:</i> <a href="mailto:newnews-cosmos@gmail.com">newnews-cosmos@gmail.com</a></p>
        <p><i>телефон:</i> <a href="tel: Вне зоны досягаемости">Вне зоны досягаемости</a></p>
    </section>
  </main>
  <footer class="page-footer">
    <div class="container">
      <p>© Cosmoman</p>
      <p>2021</p>
    </div>
  </footer>
</body>
</html>
* {
  box-sizing: border-box;
}

.container {
  width: 580px;
  margin: 0 auto;
}

.page {
  display: flex;
  flex-direction: column;
  min-width: 640px;
  min-height: 100vh;
  margin: 0;
  font-family: "Verdana", "Tahoma", sans-serif;
  font-size: 14px;
  line-height: 18px;
  color: #333333;
  background-color: #eae9f2;
}

.section-title {
  width: 100%;
  margin: 0;
  margin-bottom: 20px;
  padding: 0;
  font-weight: bold;
  font-size: 18px;
  line-height: 24px;
}

a {
  color: #6653d9;
}

a:focus {
  outline-color: #b6aaff;
}

.page-header {
  margin-bottom: 40px;
  color: #333333;
  background-color: #ffffff;
  box-shadow: 0 2px 2px rgba(0, 0, 0, 0.2);
}

.page-header .container {
  padding-top: 40px;
  padding-bottom: 40px;
  background-image: url("img/cosmoman.jpg");
  background-repeat: no-repeat;
  background-position: bottom right;
  background-size: 290px 200px;
}

.page-header a {
  font-size: 16px;
  line-height: 24px;
}

.page-title {
  margin: 0;
  margin-bottom: 4px;
  padding: 0;
  font-weight: bold;
  font-size: 36px;
  line-height: 48px;
}

.about {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  margin-bottom: 32px;
 }

.about-image {
   width: 147px;
   height: 147px;
   // border-radius: 50%;
 }

.about-content {
   width: 410px;
   font-size: 14px;
   line-height: 24px;
 }

.about-content p {
   margin: 0;
   margin-bottom: 12px;
   padding: 0;
 }

.status {
  margin-bottom: 32px;
}

.status p {
  margin: 0;
  padding-top: 12px;
  padding-right: 32px;
  padding-bottom: 16px;
  padding-left: 32px;
  border-radius: 32px 0;
  font-size: 16px;
  line-height: 24px;
  font-style: italic;
  color: #333333;
  background-color: #ffffff;
}

.contacts {
  margin-bottom: 82px;
}

.contacts img {
  width: 146px;
  height: 146px;
  margin-right: 24px;
}

.contacts p {
  margin: 0;
  margin-bottom: 12px;
  padding: 0;
  font-size: 14px;
  line-height: 24px;
}

p.contacts-name {
  margin-top: 20px;
  margin-bottom: 16px;
  font-weight: bold;
  line-height: 20px;
}

.contacts a {
  font-size: 16px;
  line-height: 24px;
}

.page-footer {
  margin-top: auto;
  color: #ffffff;
  background-color: #6653d9;
}

.page-footer .container {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding-top: 12px;
  padding-bottom: 14px;
}

.page-footer p {
  margin: 0;
  padding: 0;
}
© 2021 GitHub, Inc.
