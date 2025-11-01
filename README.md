# Cafe
my cafe website
    </section>
    <section id="about" class="about" data-aos="fade-up">
        <h2>About Us</h2>
        <p>Founded in 2020, Pizza Paradise brings authentic Italian flavors to your doorstep. Our dough is hand-tossed, and toppings are sourced fresh daily.</p>
    </section>
    <section id="contact" class="contact" data-aos="fade-up">
        <h2>Contact Us</h2>
        <p>123 Pizza Lane, Flavor Town | (555) 123-4567</p>
        <form>
            <input type="text" placeholder="Name" required><br>
            <input type="email" placeholder="Email" required><br>
            <textarea placeholder="Message"></textarea><br>
            <button class="btn" type="submit">Send</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2023 Pizza Paradise. Follow us: <i class="fab fa-facebook"></i> <i class="fab fa-instagram"></i></p>
    </footer>
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
        AOS.init();
        // Simple menu toggle for mobile
        document.querySelector('.menu-toggle').addEventListener('click', () => {
            document.querySelector('.nav-links').classList.toggle('active');
        });
    </script>
</body>
</html>
