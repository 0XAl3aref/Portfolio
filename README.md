<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Omar Fekry - Cybersecurity Specialist</title>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <!-- Font Awesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" integrity="sha512-Fo3rlrZj/k7ujTnHq6i1e+BfSh5+x8BkE5qL0yKQw5Y3i9Kp4+bQh6qV+M6N+OevXlXkkB+AdDkV7RvbvQh1PA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <!-- AOS Library for Animations -->
    <link href="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.css" rel="stylesheet">
    <style>
        /* Add all CSS here */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            color: #333;
        }

        #hero {
            background: linear-gradient(135deg, #1e3c72, #2a5298);
            color: #fff;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            position: relative;
        }

        #hero h1 {
            font-size: 3em;
        }

        #hero p {
            font-size: 1.5em;
        }

        section {
            padding: 60px 20px;
        }

        h2 {
            text-align: center;
            margin-bottom: 20px;
        }

        .container {
            max-width: 800px;
            margin: auto;
        }

        .social-icons a {
            color: white;
            margin: 0 10px;
            font-size: 1.5em;
            text-decoration: none;
        }

        footer {
            background: #2a5298;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>
    <section id="hero">
        <div>
            <h1>Omar Fekry</h1>
            <p>Cybersecurity Specialist</p>
            <div class="social-icons">
                <a href="https://www.linkedin.com/in/0mar-fekry/" target="_blank"><i class="fab fa-linkedin"></i></a>
                <a href="https://github.com/0XAl3aref" target="_blank"><i class="fab fa-github"></i></a>
                <a href="mailto:mohamedsaber.thunter@gmail.com"><i class="fas fa-envelope"></i></a>
            </div>
        </div>
    </section>
    <section id="about" data-aos="fade-up">
        <div class="container">
            <h2>About Me</h2>
            <p>A passionate Cyber Security Specialist with expertise in Security Operations...</p>
        </div>
    </section>
    <footer>
        <p>&copy; 2025 Omar Fekry</p>
    </footer>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.js"></script>
    <script>
        AOS.init({ duration: 1000, once: true });
    </script>
</body>
</html>
