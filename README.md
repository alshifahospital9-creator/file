<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sunrise Hospital</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        /* Reset & basic styles */
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Roboto', sans-serif; line-height: 1.6; color: #333; }

        header {
            background-color: #007BFF;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }

        header h1 { margin-bottom: 10px; }

        nav {
            margin-top: 10px;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover { text-decoration: underline; }

        section { padding: 60px 20px; max-width: 1200px; margin: auto; }

        .about, .departments, .doctors, .appointment, .contact { margin-bottom: 40px; }

        h2 { color: #007BFF; margin-bottom: 20px; }

        .departments .dept-card, .doctors .doc-card {
            background: #f8f9fa;
            padding: 20px;
            margin: 10px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            display: inline-block;
            width: calc(33% - 40px);
            vertical-align: top;
            text-align: center;
        }

        .departments .dept-card h3, .doctors .doc-card h3 { margin-bottom: 10px; }

        .appointment form, .contact form {
            display: flex;
            flex-direction: column;
        }

        .appointment input, .appointment select, .appointment textarea,
        .contact input, .contact textarea {
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .appointment button, .contact button {
            background-color: #007BFF;
            color: #fff;
            border: none;
            padding: 15px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }

        .appointment button:hover, .contact button:hover {
            background-color: #0056b3;
        }

        footer {
            background-color: #f1f1f1;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }

        @media(max-width: 900px) {
            .departments .dept-card, .doctors .doc-card { width: calc(50% - 40px); }
        }

        @media(max-width: 600px) {
            .departments .dept-card, .doctors .doc-card { width: 100%; }
        }
    </style>
</head>
<body>

    <header>
        <h1>Sunrise Hospital</h1>
        <nav>
            <a href="#about">About Us</a>
            <a href="#departments">Departments</a>
            <a href="#doctors">Doctors</a>
            <a href="#appointment">Appointment</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- About Section -->
    <section id="about" class="about">
        <h2>About Us</h2>
        <p>Welcome to Sunrise Hospital, where patient care meets excellence. We provide state-of-the-art medical services with a compassionate touch.</p>
    </section>

    <!-- Departments Section -->
    <section id="departments" class="departments">
        <h2>Our Departments</h2>
        <div class="dept-card">
            <h3>Cardiology</h3>

