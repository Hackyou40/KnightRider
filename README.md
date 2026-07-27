<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WaveRiders Surf School</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<header>
    <nav class="navbar">

        <h1>🐿️ WaveRiders</h1>

        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#courses">Courses</a></li>
            <li><a href="#gallery">Gallery</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>

    </nav>
</header>

<main>

    <!-- Hero -->

    <section class="hero">

        <h2>Surf Like a Squirrel!</h2>

        <p>
            Join WaveRiders, the world's best squirrel surf school.
            Learn to ride the waves while having fun with your furry friends!
        </p>

        <a href="#" class="button" id="bookButton">
            Book Your Lesson
        </a>

    </section>

    <!-- Gallery -->

      <section class="gallery" id="gallery">

        <img
            src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e?w=600"
            alt="Ocean waves">

        <img
            src="https://images.unsplash.com/photo-1500375592092-40eb2168fd21?w=600"
            alt="Beautiful surfing beach">

    </section>

    <!-- About -->

    <section class="about" id="about">

        <h2>Why Choose WaveRiders?</h2>

        <div class="about-cards">

            <div class="card">

                <h3>🏄 Expert Coaches</h3>

                <p>
                    Friendly squirrel instructors help you
                    learn safely and confidently.
                </p>

            </div>

            <div class="card">

                <h3>🌊 Safe Beaches</h3>

                <p>
                    Learn on beautiful beaches with gentle waves
                    perfect for beginners.
                </p>

            </div>

            <div class="card">

                <h3>⭐ Fun Experience</h3>

                <p>
                    Make unforgettable memories while learning
                    to surf.
                </p>

            </div>

        </div>

    </section>

    <!-- Courses -->

    <section class="features" id="courses">

        <div class="card">

            <h3>🏄 Beginner Lessons</h3>

            <p>Perfect for first-time surfers.</p>

        </div>

        <div class="card">

            <h3>🌊 Intermediate Lessons</h3>

            <p>Improve your surfing skills.</p>

        </div>

        <div class="card">

            <h3>🐿️ Advanced Surf Camp</h3>

            <p>Master the waves with expert coaching.</p>

        </div>

    </section>

    <!-- Testimonials -->

    <section class="testimonials">

        <h2>What Our Students Say</h2>

        <div class="testimonial-container">

            <div class="testimonial">

                <p>"Amazing experience! Highly recommended."</p>

                <h4>- Emma</h4>

            </div>

            <div class="testimonial">

                <p>"Friendly coaches and beautiful beaches."</p>

                <h4>- Oliver</h4>

            </div>

            <div class="testimonial">

                <p>"Best surf lessons I've ever taken."</p>

                <h4>- Sophia</h4>

            </div>

        </div>

    </section>

</main>

<footer id="contact">

    <div class="footer-links">

        <h3>🐿️ WaveRiders</h3>

        <p>Surf School</p>

    </div>

    <div class="footer-links">

        <a href="#about">About</a>
        <a href="#courses">Courses</a>
        <a href="#gallery">Gallery</a>
        <a href="#contact">Contact</a>

    </div>

    <div class="footer-links">

        <p>📧 hello@waveriders.com</p>
        <p>📞 +1 (555) 123-4567</p>

        <p>🌊 📸 👍</p>

    </div>

    <div class="footer-map">

        <iframe
            src="https://www.google.com/maps?q=Santa%20Monica%20Beach&output=embed"
            loading="lazy">
        </iframe>

    </div>

</footer>

<script>

const button = document.getElementById("bookButton");

button.addEventListener("click", function(event){

    event.preventDefault();

    alert("🏄 Thanks for booking a lesson with WaveRiders!");

});

</script>

</body>
</html>
