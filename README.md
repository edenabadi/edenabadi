<!DOCTYPE html>
<html lang="he">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>העסק שלי</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">דף הבית</a></li>
                <li><a href="#about">אודות</a></li>
                <li><a href="#services">שירותים</a></li>
                <li><a href="#contact">צור קשר</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h1>ברוכים הבאים לעסק שלי!</h1>
        <p>אנחנו כאן כדי לעזור לך עם כל מה שקשור ל... (הוסף מידע כאן)</p>
    </section>

    <section id="about">
        <h2>אודות</h2>
        <p>העסק שלי עוסק ב... (הוסף כאן מידע על העסק שלך)</p>
    </section>

    <section id="services">
        <h2>השירותים שלנו</h2>
        <ul>
            <li>שירות 1</li>
            <li>שירות 2</li>
            <li>שירות 3</li>
        </ul>
    </section>

    <section id="contact">
        <h2>צור קשר</h2>
        <form action="#">
            <label for="name">שם:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">אימייל:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">הודעה:</label>
            <textarea id="message" name="message" required></textarea>
            
            <button type="submit">שלח</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 כל הזכויות שמורות.</p>
    </footer>
</body>
</html>

