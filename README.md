<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Κατάστημα Αθλητικών Ειδών</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Κατάστημα Αθλητικών Ειδών</h1>
            <nav>
                <ul>
                    <li><a href="#">Αρχική</a></li>
                    <li><a href="#">Προϊόντα</a></li>
                    <li><a href="#">Υπηρεσίες</a></li>
                    <li><a href="#">Επικοινωνία</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="about">
        <div class="container">
            <h2>Ποιοί Είμαστε</h2>
            <p>Καλωσορίσατε στο Κατάστημα Αθλητικών Ειδών. Είμαστε αφοσιωμένοι στην προμήθεια υψηλής ποιότητας αθλητικών ειδών για όλους τους αθλητές.</p>
        </div>
    </section>

    <section id="products">
        <div class="container">
            <h2>Τα Προϊόντα Μας</h2>
            <div class="product">
                <img src="product1.jpg" alt="Προϊόν 1">
                <h3>Προϊόν 1</h3>
                <p>Περιγραφή του προϊόντος 1.</p>
            </div>
            <div class="product">
                <img src="product2.jpg" alt="Προϊόν 2">
                <h3>Προϊόν 2</h3>
                <p>Περιγραφή του προϊόντος 2.</p>
            </div>
            <!-- Περισσότερα προϊόντα μπορούν να προστεθούν εδώ -->
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Επικοινωνία</h2>
            <form>
                <label for="name">Όνομα:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Μήνυμα:</label>
                <textarea id="message" name="message" required></textarea>

                <button type="submit">Αποστολή</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>Κατάστημα Αθλητικών Ειδών &copy; 2024</p>
        </div>
    </footer>
</body>
</html>
