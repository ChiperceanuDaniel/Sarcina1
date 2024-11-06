<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Un site complex cu HTML și CSS">
</head>
<body>

    <header>
        <h1>Site Complex cu HTML și CSS</h1>
    </header>

    <nav>
        <a href="#home">Acasă</a>
        <a href="#about">Despre</a>
        <a href="#services">Servicii</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="container">
        <section id="home">
            <h2>Bine ați venit pe site-ul nostru!</h2>
            <p>Acesta este un exemplu de pagină complexă care include formulare, tabele, imagini și multe altele.</p>
        </section>

        <section id="about">
            <h2>Despre Noi</h2>
            <p>Noi oferim soluții inovative pentru afacerea dumneavoastră, inclusiv dezvoltarea de site-uri web și aplicații personalizate.</p>
        </section>

        <section id="services">
            <h2>Servicii</h2>
            <ul>
                <li>Dezvoltare web</li>
                <li>Design grafic</li>
                <li>Consultanță IT</li>
                <li>SEO (Optimizare pentru motoarele de căutare)</li>
            </ul>
        </section>

        <section id="contact">
            <h2>Contactați-ne</h2>
            <div class="form-container">
                <h3>Formular de contact</h3>
                <form action="#" method="post">
                    <label for="name">Nume:</label>
                    <input type="text" id="name" name="name" required><br><br>
                    
                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" required><br><br>
                    
                    <label for="message">Mesaj:</label><br>
                    <textarea id="message" name="message" rows="4" cols="50" required></textarea><br><br>
                    
                    <button type="submit">Trimite</button>
                </form>
            </div>
        </section>

        <section>
            <h2>Galerie de imagini</h2>
            <div class="image-container">
                <img src="https://via.placeholder.com/200" alt="Imagine 1">
                <img src="https://via.placeholder.com/200" alt="Imagine 2">
                <img src="https://via.placeholder.com/200" alt="Imagine 3">
            </div>
        </section>

        <section>
            <h2>Tabel cu date</h2>
            <table>
                <tr>
                    <th>ID</th>
                    <th>Nume</th>
                    <th>Email</th>
                </tr>
                <tr>
                    <td>1</td>
                    <td>Ion Popescu</td>
                    <td>ion@example.com</td>
                </tr>
                <tr>
                    <td>2</td>
                    <td>Maria Ionescu</td>
                    <td>maria@example.com</td>
                </tr>
                <tr>
                    <td>3</td>
                    <td>Andrei Vasile</td>
                    <td>andrei@example.com</td>
                </tr>
            </table>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Site Complex - Toate drepturile rezervate</p>
    </footer>

</body>
</html>
