<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
  <title>Москва 24/7 | Проект Московского Политеха</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Inter', system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', sans-serif;
      /* Новый основной фон сайта - #9D2A2A (терракотово-красный) */
      background-color: #9D2A2A;
      color: #1a1a2e;
      line-height: 1.4;
    }

    /* Desktop fixed width container */
    .container {
      max-width: 1280px;
      margin: 0 auto;
      padding: 0 48px;
    }

    /* Header & navigation - фон верхней строки #F39B9B */
    header {
      background-color: #F39B9B;
      padding: 20px 0;
      border-bottom: 3px solid #ffcd3c;
      position: sticky;
      top: 0;
      z-index: 100;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
    }

    .nav-bar {
      display: flex;
      justify-content: center;
      gap: 2.8rem;
      flex-wrap: wrap;
      list-style: none;
    }

    .nav-btn {
      background: none;
      border: none;
      font-size: 1.2rem;
      font-weight: 600;
      color: #2c1a1a;     /* темный оттенок для контраста на розовом фоне */
      cursor: pointer;
      padding: 8px 4px;
      transition: all 0.2s ease;
      font-family: inherit;
      letter-spacing: 0.3px;
      position: relative;
    }

    /* hover effect: белый цвет */
    .nav-btn:hover {
      color: #ffffff;
    }

    /* active page underline — цвет подчеркивания оставляем золотистым как требовалось */
    .nav-btn.active {
      color: #ffffff;      /* активная кнопка — белая (усиление) */
    }

    .nav-btn.active::after {
      content: '';
      position: absolute;
      bottom: -2px;
      left: 0;
      width: 100%;
      height: 3px;
      background-color: #ffcd3c;
      border-radius: 2px;
    }

    /* main content area */
    .page {
      display: none;
      animation: fadeIn 0.3s ease;
      padding: 48px 0 80px;
    }

    .page.active-page {
      display: block;
    }

    @keyframes fadeIn {
      from {
        opacity: 0;
        transform: translateY(8px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    /* Все карточки, блоки с текстом — фон #F39B9B (как и верхняя панель) */
    .card-bg {
      background: #F39B9B;
      border-radius: 28px;
      box-shadow: 0 12px 28px rgba(0, 0, 0, 0.15);
      padding: 32px 36px;
      margin-top: 24px;
      color: #2c1a1a;     /* темный текст для читаемости */
    }

    /* дополнительные информационные блоки на главной — тоже в этом цвете */
    .info-block {
      background: #F39B9B;
      border-radius: 28px;
      padding: 20px;
      flex: 1;
      border: 1px solid rgba(255, 240, 210, 0.5);
      color: #2c1a1a;
    }

    /* достижения / карточки */
    .achievement-card {
      background: #e68484;
      border-radius: 28px;
      box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
      padding: 28px 24px;
      flex: 1 1 220px;
      text-align: center;
      transition: transform 0.2s, box-shadow 0.2s;
      border: 1px solid rgba(255, 220, 170, 0.6);
      color: #2c1a1a;
    }

    .achievement-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 24px 36px rgba(0, 0, 0, 0.2);
      background: #ffaeae;
    }

    /* ресурсы */
    .resource-item {
      background: #e68484;  /* чуть темнее для разнообразия, но в гамме */
      border-radius: 60px;
      padding: 14px 24px;
      display: flex;
      align-items: center;
      flex-wrap: wrap;
      gap: 16px;
      font-size: 1.1rem;
      font-weight: 500;
      transition: background 0.2s;
      color: #2c1a1a;
    }

    .resource-item:hover {
      background: #ffa5a5;
    }

    .resource-link {
      text-decoration: none;
      color: #2c1a1a;
      font-weight: 600;
      word-break: break-all;
      background: #fff0e0bb;
      padding: 6px 14px;
      border-radius: 40px;
      font-size: 0.9rem;
      transition: 0.2s;
    }

    .resource-link:hover {
      background: #ffcd3c;
      color: #1f1a2e;
    }

    /* team page — список участников скроллится */
    .team-list {
      display: flex;
      flex-direction: column;
      gap: 20px;
      max-height: 65vh;
      overflow-y: auto;
      padding-right: 12px;
      margin-top: 24px;
      border-radius: 28px;
    }

    .team-list::-webkit-scrollbar {
      width: 6px;
    }

    .team-list::-webkit-scrollbar-track {
      background: #c05353;
      border-radius: 10px;
    }

    .team-list::-webkit-scrollbar-thumb {
      background: #ffcd3c;
      border-radius: 10px;
    }

    .team-member-card {
      background: #F39B9B;
      border-radius: 24px;
      padding: 20px 28px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08);
      border: 1px solid #ffcdb0;
      transition: all 0.2s;
      display: flex;
      align-items: center;
      gap: 20px;
      flex-wrap: wrap;
      color: #2c1a1a;
    }

    .team-member-card:hover {
      background: #ffaaaa;
    }

    .member-avatar {
      width: 56px;
      height: 56px;
      background: linear-gradient(145deg, #ffcd3c, #ffb347);
      border-radius: 40px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 1.8rem;
      font-weight: bold;
      color: #1e1a2f;
    }

    .member-name {
      font-weight: 800;
      font-size: 1.25rem;
      color: #2c1a1a;
    }

    .member-role {
      color: #3f2a2a;
      margin-top: 4px;
      font-weight: 500;
    }

    /* typography */
    h1 {
      font-size: 3.2rem;
      font-weight: 800;
      margin-bottom: 16px;
      color: #2c1a1a;
      letter-spacing: -0.5px;
      text-shadow: 0 1px 2px rgba(255,205,60,0.3);
    }

    h2 {
      font-size: 2rem;
      font-weight: 700;
      margin-bottom: 24px;
      color: #2c1a1a;
      border-left: 6px solid #ffcd3c;
      padding-left: 20px;
    }

    h3 {
      font-size: 1.5rem;
      font-weight: 600;
      margin: 20px 0 12px 0;
      color: #2c1a1a;
    }

    .hero-text {
      font-size: 1.2rem;
      line-height: 1.5;
      color: #2c1a1a;
      background: rgba(0,0,0,0.02);
      border-radius: 32px;
    }

    .subhead {
      font-size: 1.15rem;
      color: #3f2a2a;
      margin-bottom: 16px;
      font-weight: 500;
    }

    footer {
      background: #b13e3e;
      color: #fff0d0;
      text-align: center;
      padding: 28px 16px;
      font-size: 0.85rem;
      border-top: 1px solid #ffcd7a;
      margin-top: 40px;
    }

    /* дополнительная кнопка/вспомогательные блоки */
    .btn-soft {
      background: #e27c7c;
      border-radius: 999px;
      padding: 8px 18px;
      font-size: 0.9rem;
    }

    @media (max-width: 800px) {
      .container {
        padding: 0 24px;
      }
      .nav-bar {
        gap: 1.2rem;
      }
      h1 {
        font-size: 2.4rem;
      }
      .card-bg {
        padding: 24px 20px;
      }
    }

    /* Блоки аналогичные главной */
    .flex-row {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
      justify-content: space-between;
      margin-top: 32px;
    }

    /* внутренние элементы о проекте */
    .about-highlight {
      background: #e27c7c;
      border-radius: 32px;
      padding: 24px;
      text-align: center;
    }

    /* ссылки в ресурсах */
    .resource-item span {
      font-weight: 700;
    }
  </style>
</head>
<body>

<header>
  <div class="container">
    <ul class="nav-bar">
      <li><button class="nav-btn" data-page="home">Главная</button></li>
      <li><button class="nav-btn" data-page="about">О проекте</button></li>
      <li><button class="nav-btn" data-page="members">Участники</button></li>
      <li><button class="nav-btn" data-page="journal">Журнал</button></li>
      <li><button class="nav-btn" data-page="resources">Ресурсы</button></li>
    </ul>
  </div>
</header>

<main class="container">
  <!-- ГЛАВНАЯ СТРАНИЦА -->
  <div id="home-page" class="page active-page">
    <div class="card-bg">
      <h1>Проект Москва 24/7</h1>
      <p class="subhead" style="font-size:1.2rem; margin-bottom: 20px;">Проект, вдохновляющий творить</p>
      <div class="hero-text">
        <p style="margin-bottom: 16px;">Проект Москва 24/7 - это уникальный проект в Московском Политехе, который вот уже на протяжении нескольких лет продвигает Московский Политехнический университет, чтобы о нём услышало как можно больше абитуриентов и студентов. Помимо этого мы рассказываем об интересных событиях и местах в Москве!</p>
        <p>Не знаешь, куда сходить вечером? Задаёшься вопросом, какое мероприятие стоит посетить? Тогда тебе точно к нам!</p>
      </div>
    </div>
    <div class="flex-row">
      <div class="info-block">
        <img src="images\Звезда.png" alt="Медиа-охват" style="width: 40px; height: auto; margin-bottom: 12px;">
        <h3 style="margin: 12px 0 8px;">Творческое сообщество</h3>
        <p>Вдохновляем студентов создавать уникальный контент о Москве и университете.</p>
      </div>
      <div class="info-block">
        <img src="images\Камера.png" alt="Медиа-охват" style="width: 40px; height: auto; margin-bottom: 12px;">
        <h3 style="margin: 12px 0 8px;">Видеопродакшн</h3>
        <p>Снимаем яркие ролики, интервью и репортажи о жизни в столице.</p>
      </div>
    </div>
  </div>

  <!-- О ПРОЕКТЕ -->
  <div id="about-page" class="page">
    <div class="card-bg">
      <h2>О проекте</h2>
      <div style="display: flex; flex-wrap: wrap; gap: 32px; align-items: start;">
        <div style="flex: 1.5;">
          <h3>Почему мы важны и чем занимаемся?</h3>
          <p style="font-size: 1.05rem; line-height: 1.5; margin-bottom: 24px;">Мы продвигаем Московский Политех через медиа пространство, в результате чего о нём узнаёт больше студентов и абитуриентов. Также наши ролики и посты доносят людям, каково это - жить в Москве. В результате этого всё больше людей узнают о нашем вузе, о жизни в столице, и число желающих поступить сюда растёт.</p>
          <p style="font-size: 1.05rem; line-height: 1.5;">Наша команда в основном занимается созданием видеоконтента, который выкладывается в социальные сети. Помимо этого мы пишем посты с новостями об инвентах и интересных приложениях.</p>
        </div>
		<div class="about-highlight" style="flex: 0.8;">
 	 	<img src="images\Громкоговоритель.png" alt="Медиа-охват" style="width: 200px; height: auto; margin-bottom: 12px;">
	</div>
      </div>
    </div>
  </div>

  <!-- УЧАСТНИКИ (СКРОЛЛЯЩАЯСЯ СТРАНИЦА) -->
  <div id="members-page" class="page">
    <div class="card-bg" style="padding-bottom: 32px;">
      <h2>Наша команда</h2>
      <p class="subhead" style="margin-bottom: 8px;">Активные участники и создатели проекта «Москва 24/7»</p>
      <!-- большой скроллящийся список: чтобы листалось, много участников -->
      <div class="team-list">
        <div class="team-member-card">
          <div class="member-avatar">И</div>
          <div class="member-info"><div class="member-name">Ирина Абрахманова</div><div class="member-role">ответственный за ВК</div></div>
        </div>
        <div class="team-member-card">
          <div class="member-avatar">Р</div>
          <div class="member-info"><div class="member-name">Роман Аксютичев</div><div class="member-role">контентмейкер</div></div>
        </div>
        <div class="team-member-card">
          <div class="member-avatar">Д</div>
          <div class="member-info"><div class="member-name">Данила Алексеев</div><div class="member-role">контентмейкер</div></div>
        </div>
        <div class="team-member-card">
          <div class="member-avatar">К</div>
          <div class="member-info"><div class="member-name">Кирилл Алексеев</div><div class="member-role">контентмейкер</div></div>
        </div>
        <div class="team-member-card">
          <div class="member-avatar">Д</div>
          <div class="member-info"><div class="member-name">Денис Алешин</div><div class="member-role">староста</div></div>
        </div>
        <div class="team-member-card">
          <div class="member-avatar">А</div>
          <div class="member-info"><div class="member-name">Александра Аржанухина</div><div class="member-role">контентмейкер</div></div>
        </div>
        <div class="team-member-card">
          <div class="member-avatar">В</div>
          <div class="member-info"><div class="member-name">Владислав Белобородько</div><div class="member-role">контентмейкер</div></div>
        </div>
        <div class="team-member-card">
          <div class="member-avatar">В</div>
          <div class="member-info"><div class="member-name">Владислава Бирюкова</div><div class="member-role">контентмейкер</div></div>
        </div>
        <div class="team-member-card">
          <div class="member-avatar">Е</div>
          <div class="member-info"><div class="member-name">Екатерина Благодарная</div><div class="member-role">контентмейкер</div></div>
        </div>
        <div class="team-member-card">
          <div class="member-avatar">Е</div>
          <div class="member-info"><div class="member-name">Ева Болтовская</div><div class="member-role">дизайнер</div></div>
        </div>
        <div class="team-member-card">
          <div class="member-avatar">Д</div>
          <div class="member-info"><div class="member-name">Дарья Васильева</div><div class="member-role">контентмейкер</div></div>
        </div>
        <div class="team-member-card">
          <div class="member-avatar">А</div>
          <div class="member-info"><div class="member-name">Александр Демшин</div><div class="member-role">контентмейкер</div></div>
        </div>
        <div class="team-member-card">
          <div class="member-avatar">Я</div>
          <div class="member-info"><div class="member-name">Яна Дудченко</div><div class="member-role">контентмейкер</div></div>
        </div>
        <div class="team-member-card">
          <div class="member-avatar">В</div>
          <div class="member-info"><div class="member-name">Владислав Дуев</div><div class="member-role">ответственный за Ютуб</div></div>
        </div>
        <div class="team-member-card">
          <div class="member-avatar">М</div>
          <div class="member-info"><div class="member-name">Милена Евлоева</div><div class="member-role">контентмейкер</div></div>
        </div>
        <div class="team-member-card">
          <div class="member-avatar">Е</div>
          <div class="member-info"><div class="member-name">Екатерина Ерохина</div><div class="member-role">ответственный за Телеграм</div></div>
        </div>
        <div class="team-member-card">
          <div class="member-avatar">Ж</div>
          <div class="member-info"><div class="member-name">Жасмин Жалилова</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">Т</div>
          <div class="member-info"><div class="member-name">Татьяна Зайцева</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">А</div>
          <div class="member-info"><div class="member-name">Алиса Иванченко</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">О</div>
          <div class="member-info"><div class="member-name">Ольга Илюшина</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">В</div>
          <div class="member-info"><div class="member-name">Виктория Капустина</div><div class="member-role">староста</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">Е</div>
          <div class="member-info"><div class="member-name">Екатерина Кириллова</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">Е</div>
          <div class="member-info"><div class="member-name">Егор Кирсанов</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">А</div>
          <div class="member-info"><div class="member-name">Анастасия Коробейникова</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">Ф</div>
          <div class="member-info"><div class="member-name">Фёдор Кузнецов</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">У</div>
          <div class="member-info"><div class="member-name">Ульяна Кулешова</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">Д</div>
          <div class="member-info"><div class="member-name">Денис Кучанов</div><div class="member-role">мониторит конкурсы</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">М</div>
          <div class="member-info"><div class="member-name">Михаил Кушевский</div><div class="member-role">ищет спонсора</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">А</div>
          <div class="member-info"><div class="member-name">Александр Ларин</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">В</div>
          <div class="member-info"><div class="member-name">Виктория Леонтьева</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">И</div>
          <div class="member-info"><div class="member-name">Ирина Любченко</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">Б</div>
          <div class="member-info"><div class="member-name">Богдан Масалов</div><div class="member-role">ответственный за Телеграм</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">Н</div>
          <div class="member-info"><div class="member-name">Нилуфар Махмудова</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">Н</div>
          <div class="member-info"><div class="member-name">Никита Минаев</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">М</div>
          <div class="member-info"><div class="member-name">Мария миталева</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">Э</div>
          <div class="member-info"><div class="member-name">Элина Митрофанова</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">Э</div>
          <div class="member-info"><div class="member-name">Эллина Мошкарёва</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">Г</div>
          <div class="member-info"><div class="member-name">Галина Найчук</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">К</div>
          <div class="member-info"><div class="member-name">Кирилл Никитин</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">З</div>
          <div class="member-info"><div class="member-name">Зарина Нургалиева</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">П</div>
          <div class="member-info"><div class="member-name">Полина Перевозчикова</div><div class="member-role">ответственный за ВК</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">В</div>
          <div class="member-info"><div class="member-name">Виктория Польникова</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">А</div>
          <div class="member-info"><div class="member-name">Анастасия Полякова</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">Я</div>
          <div class="member-info"><div class="member-name">Ярослав Попылев</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">С</div>
          <div class="member-info"><div class="member-name">София Ромадина</div><div class="member-role">ответственный за ТикТок</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">Г</div>
          <div class="member-info"><div class="member-name">Георгий Савиди</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">А</div>
          <div class="member-info"><div class="member-name">Арина Сазонова</div><div class="member-role">ответственный за Ютуб</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">Н</div>
          <div class="member-info"><div class="member-name">Наталья Смирнова</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">Ф</div>
          <div class="member-info"><div class="member-name">Фёдор Старобыкин</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">Е</div>
          <div class="member-info"><div class="member-name">Ержан Султангалиев</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">К</div>
          <div class="member-info"><div class="member-name">Карина Тимощенко</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">А</div>
          <div class="member-info"><div class="member-name">Анастасия Ткаченко</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">В</div>
          <div class="member-info"><div class="member-name">Владимир Турилкин</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">А</div>
          <div class="member-info"><div class="member-name">Анастасия Ульянова</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">И</div>
          <div class="member-info"><div class="member-name">Изабелла Хабибуллина</div><div class="member-role">ответственный за ВК</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">М</div>
          <div class="member-info"><div class="member-name">Мария Халепо</div><div class="member-role">ответственный за ТикТок</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">С</div>
          <div class="member-info"><div class="member-name">Светлана Ходакова</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">Д</div>
          <div class="member-info"><div class="member-name">Диана Холманских</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">Е</div>
          <div class="member-info"><div class="member-name">Егор Чубуков</div><div class="member-role">ответственный за Ютуб</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">А</div>
          <div class="member-info"><div class="member-name">Алексей Шубан</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">А</div>
          <div class="member-info"><div class="member-name">Анна Юрьева</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">А</div>
          <div class="member-info"><div class="member-name">Арсений Яковлев</div><div class="member-role">контентмейкер</div></div>
        </div>
	<div class="team-member-card">
          <div class="member-avatar">В</div>
          <div class="member-info"><div class="member-name">Виктория Яковлева</div><div class="member-role">контентмейкер</div></div>
        </div>
      </div>
      <p style="margin-top: 24px; font-size: 0.9rem; color: #2c1a1a; text-align: center; background: #ffc2a2; padding: 8px; border-radius: 48px;"> И это ещё не все! Наша дружная команда продолжает расти! </p>
    </div>
  </div>

  <!-- ЖУРНАЛ -->
  <div id="journal-page" class="page">
    <div class="card-bg">
      <h2>Журнал</h2>
      <p class="subhead">Наши последние достижения</p>
      <div class="grid-achievements" style="display: flex; flex-wrap: wrap; gap: 28px; margin-top: 28px;">
        <div class="achievement-card"><img src="images\Ютуб.png" style="width: 40px; height: auto; margin-bottom: 12px;"><h3>1000+ подписчиков</h3><p>Мы достигли отметки больше 1000 подписчиков на YouTube!</p></div>
        <div class="achievement-card"><img src="images\Кубок.png" style="width: 40px; height: auto; margin-bottom: 12px;"><h3>3 конкурса — 2 призовых места!</h3><p>Мы поучаствовали в 3-х конкурсах и заняли 2 призовых места!</p></div>
        <div class="achievement-card"><img src="images\Сердечко.png" style="width: 40px; height: auto; margin-bottom: 12px;"><h3>Новые площадки</h3><p>Мы появились в Pinterest и Дзен!</p></div>
      </div>
      <div style="margin-top: 40px; background: #e68484; border-radius: 28px; padding: 24px; color:#2c1a1a;">
        <h3 style="margin-top: 0;">✨ Что в планах?</h3>
        <p>Набрать 2000 подписчиков на YouTube и найти хорошего спонсора проекта!</p>
      </div>
    </div>
  </div>

  <!-- РЕСУРСЫ -->
  <div id="resources-page" class="page">
    <div class="card-bg">
      <h2>Ресурсы</h2>
      <p class="subhead">Где вы можете найти нас?</p>
      <div class="resources-links" style="display: flex; flex-direction: column; gap: 18px; margin-top: 16px;">
        <div class="resource-item"><span> YouTube:</span> <a class="resource-link" href="https://youtube.com/@moscowneverleepss" target="_blank" rel="noopener noreferrer">https://youtube.com/@moscowneverleepss</a></div>
        <div class="resource-item"><span> Telegram:</span> <a class="resource-link" href="https://t.me/+8GTw39-2KpFkMDVi" target="_blank" rel="noopener noreferrer">https://t.me/+8GTw39-2KpFkMDVi</a></div>
        <div class="resource-item"><span> VK:</span> <a class="resource-link" href="https://vk.com/club225243805" target="_blank" rel="noopener noreferrer">https://vk.com/club225243805</a></div>
        <div class="resource-item"><span> Дзен:</span> <a class="resource-link" href="https://dzen.ru/profile/editor/moscowneverleepss?noreload=1" target="_blank" rel="noopener noreferrer">https://dzen.ru/profile/editor/moscowneverleepss</a></div>
        <div class="resource-item"><span> Pinterest:</span> <a class="resource-link" href="https://pin.it/6syjxhgpb" target="_blank" rel="noopener noreferrer">https://pin.it/6syjxhgpb</a></div>
      </div>
      <div style="margin-top: 32px; padding: 20px; background: #ffbe8c; border-radius: 28px;">
        <p style="font-weight: 500; color:#2c1a1a;"> Присоединяйся к нашему сообществу — вступай в семью Московского Политеха!</p>
      </div>
    </div>
  </div>
</main>

<footer>
  <div class="container">
    <p>© 2026 Проект Москва 24/7 — Московский Политехнический университет. Вдохновляем творить и узнавать Москву.</p>
  </div>
</footer>

<script>
  // DOM элементы
  const pages = {
    home: document.getElementById('home-page'),
    about: document.getElementById('about-page'),
    members: document.getElementById('members-page'),
    journal: document.getElementById('journal-page'),
    resources: document.getElementById('resources-page')
  };

  const navButtons = document.querySelectorAll('.nav-btn');

  function setActivePage(pageId) {
    Object.values(pages).forEach(page => {
      if (page) page.classList.remove('active-page');
    });
    if (pages[pageId]) {
      pages[pageId].classList.add('active-page');
    }
    navButtons.forEach(btn => {
      const btnPage = btn.getAttribute('data-page');
      if (btnPage === pageId) {
        btn.classList.add('active');
      } else {
        btn.classList.remove('active');
      }
    });
    window.scrollTo({ top: 0, behavior: 'smooth' });
  }

  navButtons.forEach(btn => {
    btn.addEventListener('click', (e) => {
      const pageName = btn.getAttribute('data-page');
      if (pageName && pages[pageName]) {
        setActivePage(pageName);
        window.location.hash = pageName;
      }
    });
  });

  function handleHashChange() {
    const hash = window.location.hash.substring(1);
    if (hash && pages[hash]) {
      setActivePage(hash);
    } else if (!hash) {
      setActivePage('home');
    }
  }
  window.addEventListener('hashchange', handleHashChange);
  
  if (window.location.hash && window.location.hash.length > 1) {
    const initialHash = window.location.hash.substring(1);
    if (pages[initialHash]) setActivePage(initialHash);
    else setActivePage('home');
  } else {
    setActivePage('home');
  }
  window.addEventListener('popstate', () => {
    const hash = window.location.hash.substring(1);
    if (hash && pages[hash]) setActivePage(hash);
    else setActivePage('home');
  });
</script>
</body>
</html>
