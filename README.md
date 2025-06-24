
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OIT - Ваш путь к успеху</title>
    <style>
        :root {
            --primary: #2c3e50;
            --secondary: #3498db;
            --accent: #e74c3c;
            --light: #ecf0f1;
            --dark: #2c3e50;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        
        .header-logo {
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 1rem 0;
            background-color: white;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        
        .logo-container {
            display: flex;
            align-items: center;
            gap: 1rem;
        }
        
        .logo-img {
            height: 50px;
            width: auto;
        }
        
        .logo-text {
            font-size: 1.8rem;
            font-weight: bold;
            color: var(--primary);
        }
        
        header {
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            color: white;
            padding: 2rem 0;
            text-align: center;
        }
        
        .container {
            width: 85%;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }
        
        .btn {
            display: inline-block;
            background-color: var(--accent);
            color: white;
            padding: 0.8rem 1.5rem;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            margin-top: 1rem;
            transition: all 0.3s ease;
        }
        
        .btn:hover {
            background-color: #c0392b;
            transform: translateY(-2px);
        }
        
        section {
            padding: 3rem 0;
        }
        
        .features {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            gap: 2rem;
            margin-top: 2rem;
        }
        
        .feature-card {
            flex: 1 1 300px;
            background: white;
            border-radius: 8px;
            padding: 1.5rem;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }
        
        .feature-card:hover {
            transform: translateY(-5px);
        }
        
        .feature-card h3 {
            color: var(--secondary);
            margin-top: 0;
        }
        
        .universities {
            background-color: var(--light);
        }
        
        .university-cards {
            display: flex;
            flex-wrap: wrap;
            gap: 2rem;
            justify-content: center;
        }
        
        .university-card {
            flex: 1 1 350px;
            background: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        
        .university-content {
            padding: 1.5rem;
        }
        
        .university-card h2 {
            color: var(--primary);
            margin-top: 0;
        }
        
        .testimonials {
            background-color: var(--dark);
            color: white;
        }
        
        .testimonial-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }
        
        .testimonial {
            background: rgba(255,255,255,0.1);
            padding: 1.5rem;
            border-radius: 8px;
        }
        
        .testimonial-name {
            font-weight: bold;
            color: var(--secondary);
        }
        
        .advice {
            background-color: white;
        }
        
        .advice-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
        }
        
        .advice-item {
            background-color: var(--light);
            padding: 1.5rem;
            border-radius: 8px;
        }
        
        .advice-item h3 {
            color: var(--primary);
        }
        
        footer {
            background-color: var(--dark);
            color: white;
            text-align: center;
            padding: 2rem 0;
        }
        
        .cta-buttons {
            display: flex;
            justify-content: center;
            gap: 1rem;
            flex-wrap: wrap;
            margin-top: 1rem;
        }
        
        .cta-btn {
            background-color: var(--accent);
            color: white;
            padding: 0.8rem 1.5rem;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
        }
        
        @media (max-width: 768px) {
            .features, .university-cards {
                flex-direction: column;
            }
            
            .logo-container {
                flex-direction: column;
                text-align: center;
            }
            
            .logo-text {
                font-size: 1.5rem;
            }
        }
    </style>
</head>
<body>
    <div class="header-logo">
        <div class="logo-container">
            <img src="https://i.ibb.co/j9yXtRv5/logo.png" alt="OIT Logo" class="logo-img">
            <div class="logo-text">OIT</div>
        </div>
    </div>
    
    <header>
        <div class="container">
            <h1>Ваш Путь к Успеху: Откройте Новые Горизонты с Нами!</h1>
            <p>Приглашаем вас в мир ведущих учебных заведений России. Получите качественное образование и постройте успешное будущее вместе с нами!</p>
            <a href="#universities" class="btn">Начать обучение</a>
        </div>
    </header>
    
    <section class="container">
        <h2>Почему Выбирают Нас?</h2>
        <div class="features">
            <div class="feature-card">
                <h3>Актуальные Программы</h3>
                <p>Обучение по востребованным специальностям. Программы соответствуют современным требованиям рынка.</p>
            </div>
            <div class="feature-card">
                <h3>Опытные Преподаватели</h3>
                <p>Высококвалифицированные педагоги с большим стажем. Они готовы делиться знаниями и опытом.</p>
            </div>
            <div class="feature-card">
                <h3>Современные Технологии</h3>
                <p>Используем передовые методики обучения. Доступ к новейшим образовательным ресурсам.</p>
            </div>
        </div>
    </section>
    
    <section id="universities" class="universities">
        <div class="container">
            <h2>Наши Учебные Заведения</h2>
            <div class="university-cards">
                <div class="university-card">
                    <div class="university-content">
                        <h2>Международный университет психолого-педагогических инноваций (МУППИ)</h2>
                        <p>МУППИ – это центр передовых знаний. Университет готовит специалистов в области психологии и педагогики. Фокус на инновациях и практических навыках.</p>
                        <p>Студенты получают глубокие теоретические знания. Они также осваивают прикладные методы работы. Обучение включает современные исследования.</p>
                        <a href="https://muppi.ru/" class="btn">Перейти на сайт МУППИ</a>
                    </div>
                </div>
                
                <div class="university-card">
                    <div class="university-content">
                        <h2>Открытый университет экономики, управления и права (ОУЭУП)</h2>
                        <h3>Экономическое Образование</h3>
                        <p>ОУЭУП – лидер в области экономики. Здесь готовят высококлассных финансистов и аналитиков. Программы ориентированы на практику.</p>
                        <h3>Управление и Бизнес</h3>
                        <p>Развивайте лидерские качества в сфере управления. Курсы охватывают маркетинг, менеджмент и стратегию. Подготовьтесь к успешной карьере.</p>
                        <a href="https://mos.college/" class="btn">Перейти на сайт ОУЭУП</a>
                    </div>
                </div>
                
                <div class="university-card">
                    <div class="university-content">
                        <h2>Колледж культуры и спорта</h2>
                        <h3>Искусство и Творчество</h3>
                        <p>Погрузитесь в мир культуры. Программы включают актерское мастерство, режиссуру и хореографию. Развивайте свои художественные способности.</p>
                        <h3>Спортивные Достижения</h3>
                        <p>Достигайте вершин в спорте. Обучение по направлениям тренерской работы и спортивного менеджмента. Развивайте физические навыки и стратегическое мышление.</p>
                        <a href="https://www.shkola-tv.ru/" class="btn">Перейти на сайт Колледжа</a>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <section class="advice container">
        <h2>Как Выбрать Подходящий ВУЗ?</h2>
        <div class="advice-grid">
            <div class="advice-item">
                <h3>Определите Интересы</h3>
                <p>Выявите свои склонности. Подумайте, что вам нравится изучать. Это поможет сузить круг поиска.</p>
            </div>
            <div class="advice-item">
                <h3>Оцените Перспективы</h3>
                <p>Узнайте о карьерных возможностях. Посмотрите, кем работают выпускники. Это важно для будущего.</p>
            </div>
            <div class="advice-item">
                <h3>Изучите Программы</h3>
                <p>Подробно ознакомьтесь с учебными планами. Убедитесь, что содержание соответствует вашим ожиданиям.</p>
            </div>
            <div class="advice-item">
                <h3>Посетите Дни Открытых Дверей</h3>
                <p>Личное знакомство с вузом поможет принять решение. Задайте вопросы преподавателям и студентам.</p>
            </div>
        </div>
    </section>
    
    <section class="testimonials">
        <div class="container">
            <h2>Истории Успеха Выпускников</h2>
            <div class="testimonial-grid">
                <div class="testimonial">
                    <p>"Обучение в МУППИ дало мне прочную базу. Я смогла открыть свою психологическую практику. Благодарна университету за знания."</p>
                    <p class="testimonial-name">Анна, выпускница МУППИ</p>
                </div>
                <div class="testimonial">
                    <p>"Я выбрал ОУЭУП из-за репутации. Сейчас я работаю ведущим аналитиком в крупной компании. Университет подготовил меня к реалиям бизнеса."</p>
                    <p class="testimonial-name">Иван, выпускник ОУЭУП</p>
                </div>
                <div class="testimonial">
                    <p>"Колледж раскрыл мои таланты. Я стала профессиональной танцовщицей. Полученные знания бесценны."</p>
                    <p class="testimonial-name">Мария, выпускница Колледжа культуры и спорта</p>
                </div>
                <div class="testimonial">
                    <p>"Юридическое образование ОУЭУП – это гарантия успеха. Я работаю юристом в международной фирме. Очень доволен своим выбором."</p>
                    <p class="testimonial-name">Дмитрий, выпускник ОУЭУП</p>
                </div>
            </div>
        </div>
    </section>
    
    <footer>
        <div class="container">
            <h2>Готовы к Поступлению?</h2>
            <p>Не откладывайте свое будущее! Сделайте первый шаг к успешной карьере. Мы готовы помочь вам!</p>
            <div class="cta-buttons">
                <a href="https://muppi.ru/" class="cta-btn">Узнать больше о МУППИ</a>
                <a href="https://mos.college/" class="cta-btn">Узнать больше об ОУЭУП</a>
                <a href="https://www.shkola-tv.ru/" class="cta-btn">Узнать больше о Колледже</a>
            </div>
        </div>
    </footer>
</body>
</html>
