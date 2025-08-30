
<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>6-сынып қазақ әдебиеті</title>
    <style>
        :root {
            --white: #FFFFFF;
            --light-green: #E8F5E9;
            --green: #4CAF50;
            --yellow: #FFEB3B;
            --red: #F44336;
            --blue: #2196F3;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--light-green);
            color: #333;
        }
        
        header {
            background: linear-gradient(135deg, var(--green), var(--blue));
            color: white;
            padding: 1rem;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        .book-cover {
            text-align: center;
            margin: 20px 0;
        }
        
        .book-cover img {
            max-width: 300px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        }
        
        .content-section {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 30px;
        }
        
        .chapter-card {
            background-color: white;
            border-radius: 8px;
            padding: 15px;
            width: calc(33% - 20px);
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }
        
        .chapter-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }
        
        .chapter-card h3 {
            color: var(--green);
            border-bottom: 2px solid var(--yellow);
            padding-bottom: 8px;
        }
        
        .media-container {
            margin-top: 15px;
        }
        
        .media-btn {
            display: inline-block;
            padding: 8px 12px;
            margin: 5px;
            border-radius: 5px;
            background-color: var(--blue);
            color: white;
            text-decoration: none;
            font-size: 14px;
            transition: background-color 0.3s;
        }
        
        .media-btn:hover {
            background-color: var(--green);
        }
        
        .task-btn {
            background-color: var(--yellow);
            color: #333;
        }
        
        .task-btn:hover {
            background-color: var(--red);
            color: white;
        }
        
        .download-btn {
            background-color: var(--green);
        }
        
        .download-btn:hover {
            background-color: var(--blue);
        }
        
        footer {
            background-color: var(--green);
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 30px;
        }
        
        @media (max-width: 768px) {
            .chapter-card {
                width: calc(50% - 20px);
            }
        }
        
        @media (max-width: 480px) {
            .chapter-card {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>6-сынып қазақ әдебиеті</h1>
        <p>Оқулық материалдары, аудио-видеолар және тапсырмалар</p>
    </header>
    
    <div class="container">
        <div class="book-cover">
            <img src="БЕТ.jpg" alt="6-сынып қазақ әдебиеті оқулығы">
        </div>
        
        <div class="content-section">
            <!-- 1-тарау -->
            <div class="chapter-card" style="background-color: var(--light-green);">
                <h3>1. Қазақ фольклоры</h3>
                <p>Халықтың ауыз әдебиеті, жырлар, ертегілер, мақал-мәтелдер</p>
                <div class="media-container">
                    <a href="#" class="media-btn">Аудио оқу</a>
                    <a href="#" class="media-btn">Видео сабақ</a>
                    <a href="#" class="media-btn task-btn">Тапсырмалар</a>
                    <a href="#" class="media-btn download-btn">Жүктеу</a>
                </div>
            </div>
            
            <!-- 2-тарау -->
            <div class="chapter-card" style="background-color: #FFF8E1;">
                <h3>2. Ертегілер әлемі</h3>
                <p>Қазақ халқының дәстүрлі ертегілері, олардың түрлері мен ерекшеліктері</p>
                <div class="media-container">
                    <a href="#" class="media-btn">Аудио оқу</a>
                    <a href="#" class="media-btn">Видео сабақ</a>
                    <a href="#" class="media-btn task-btn">Тапсырмалар</a>
                    <a href="#" class="media-btn download-btn">Жүктеу</a>
                </div>
            </div>
            
            <!-- 3-тарау -->
            <div class="chapter-card" style="background-color: #E3F2FD;">
                <h3>3. Дастандар</h3>
                <p>"Қозы Көрпеш - Баян сұлу", "Ер Тарғын" сияқты дастандар</p>
                <div class="media-container">
                    <a href="#" class="media-btn">Аудио оқу</a>
                    <a href="#" class="media-btn">Видео сабақ</a>
                    <a href="#" class="media-btn task-btn">Тапсырмалар</a>
                    <a href="#" class="media-btn download-btn">Жүктеу</a>
                </div>
            </div>
            
            <!-- 4-тарау -->
            <div class="chapter-card" style="background-color: #F3E5F5;">
                <h3>4. Ақындар шығармалары</h3>
                <p>Жамбыл, Абай, Мағжан, Мұқағали шығармалары</p>
                <div class="media-container">
                    <a href="#" class="media-btn">Аудио оқу</a>
                    <a href="#" class="media-btn">Видео сабақ</a>
                    <a href="#" class="media-btn task-btn">Тапсырмалар</a>
                    <a href="#" class="media-btn download-btn">Жүктеу</a>
                </div>
            </div>
            
            <!-- 5-тарау -->
            <div class="chapter-card" style="background-color: #E0F7FA;">
                <h3>5. Қазақ прозасы</h3>
                <p>М.Әуезов, Ғ.Мүсірепов, С.Мұқанов шығармалары</p>
                <div class="media-container">
                    <a href="#" class="media-btn">Аудио оқу</a>
                    <a href="#" class="media-btn">Видео сабақ</a>
                    <a href="#" class="media-btn task-btn">Тапсырмалар</a>
                    <a href="#" class="media-btn download-btn">Жүктеу</a>
                </div>
            </div>
            
            <!-- 6-тарау -->
            <div class="chapter-card" style="background-color: #F1F8E9;">
                <h3>6. Заманауи қазақ әдебиеті</h3>
                <p>Қазіргі заманғы қазақ жазушыларының шығармалары</p>
                <div class="media-container">
                    <a href="#" class="media-btn">Аудио оқу</a>
                    <a href="#" class="media-btn">Видео сабақ</a>
                    <a href="#" class="media-btn task-btn">Тапсырмалар</a>
                    <a href="#" class="media-btn download-btn">Жүктеу</a>
                </div>
            </div>
        </div>
    </div>
    
    <footer>
        <p>© 2025-26 оқу жылы</p>
        <p>Қайназарова Жұлдыз Есімханқызы</p>
    </footer>

    <script>
        // JavaScript код для функционала приложения
        document.addEventListener('DOMContentLoaded', function() {
            // Здесь можно добавить функционал для работы с аудио/видео
            console.log('Қосымша жүктелді');
            
            // Пример: при клике на кнопку аудио
            const audioBtns = document.querySelectorAll('.media-btn:nth-child(1)');
            audioBtns.forEach(btn => {
                btn.addEventListener('click', function(e) {
                    e.preventDefault();
                    alert('Аудио оқу басталады...');
                    // Здесь можно добавить реальный плеер аудио
                });
            });
            
            // Пример: при клике на кнопку видео
            const videoBtns = document.querySelectorAll('.media-btn:nth-child(2)');
            videoBtns.forEach(btn => {
                btn.addEventListener('click', function(e) {
                    e.preventDefault();
                    alert('Видео сабақ ашылады...');
                    // Здесь можно добавить реальный плеер видео
                });
            });
            
            // Пример: при клике на кнопку тапсырмалар
            const taskBtns = document.querySelectorAll('.task-btn');
            taskBtns.forEach(btn => {
                btn.addEventListener('click', function(e) {
                    e.preventDefault();
                    const chapter = this.closest('.chapter-card').querySelector('h3').textContent;
                    alert(chapter + ' тарауының тапсырмалары ашылады...');
                });
            });
            
            // Пример: при клике на кнопку жүктеу
            const downloadBtns = document.querySelectorAll('.download-btn');
            downloadBtns.forEach(btn => {
                btn.addEventListener('click', function(e) {
                    e.preventDefault();
                    const chapter = this.closest('.chapter-card').querySelector('h3').textContent;
                    alert(chapter + ' материалы жүктеуге дайын...');
                });
            });
        });
    </script>
</body>
</html>
