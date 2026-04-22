<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Polai Academy | Home of Success</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root {
            --primary: #1e3c72;
            --secondary: #2a5298;
            --accent: #ff9800;
            --white: #ffffff;
            --success: #27ae60;
            --danger: #e74c3c;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Poppins', sans-serif; scroll-behavior: smooth; }
        body { background-color: #f8f9fa; color: #333; }

        /* Navigation */
        nav {
            background: var(--primary);
            padding: 15px 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }
        .logo { color: var(--white); font-size: 1.6rem; font-weight: 800; letter-spacing: 1px; }
        .logo span { color: var(--accent); }
        .nav-links a { color: var(--white); text-decoration: none; margin-left: 20px; font-weight: 500; transition: 0.3s; }
        .nav-links a:hover { color: var(--accent); }

        /* Hero Section */
        .hero {
            height: 75vh;
            background: linear-gradient(rgba(30, 60, 114, 0.8), rgba(42, 82, 152, 0.8)), 
                        url('https://images.unsplash.com/photo-1522202176988-66273c2fd55f?auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            background-position: center;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            color: var(--white);
            text-align: center;
            padding: 20px;
        }
        .hero h1 { font-size: 3.5rem; margin-bottom: 15px; text-transform: uppercase; }
        .hero p { font-size: 1.3rem; max-width: 800px; margin-bottom: 30px; opacity: 0.9; }
        .btn-main { background: var(--accent); color: white; padding: 15px 40px; border-radius: 50px; text-decoration: none; font-weight: bold; font-size: 1.1rem; transition: 0.3s; box-shadow: 0 5px 15px rgba(255, 152, 0, 0.4); }
        .btn-main:hover { transform: scale(1.05); background: #e68900; }

        /* Stats Grid */
        .test-features { padding: 80px 10%; background: white; text-align: center; }
        .test-features h2 { font-size: 2.5rem; color: var(--primary); margin-bottom: 50px; }
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); gap: 25px; }
        .feat-card { padding: 40px 20px; border-radius: 20px; background: #fdfdfd; border: 1px solid #eee; transition: 0.3s; }
        .feat-card:hover { transform: translateY(-10px); box-shadow: 0 15px 30px rgba(0,0,0,0.1); border-color: var(--accent); }
        .feat-card i { font-size: 3rem; color: var(--accent); margin-bottom: 20px; }
        .feat-card h3 { margin-bottom: 10px; color: var(--primary); }

        /* Exam Categories */
        .exams { padding: 60px 10%; background: #eef2f7; text-align: center; }
        .exam-tags { display: flex; flex-wrap: wrap; justify-content: center; gap: 15px; margin-top: 20px; }
        .tag { background: var(--primary); color: white; padding: 10px 25px; border-radius: 5px; font-weight: 500; font-size: 0.9rem; }

        /* Footer */
        footer { background: #111; color: white; padding: 60px 10% 30px; text-align: center; }
        .social-link { color: #ff0000; font-size: 2.5rem; text-decoration: none; margin: 20px 0; display: inline-block; }
        .footer-text { opacity: 0.7; font-size: 0.9rem; margin-top: 20px; }

        @media (max-width: 768px) {
            .hero h1 { font-size: 2.5rem; }
            .nav-links { display: none; }
            .grid { grid-template-columns: 1fr; }
        }
    </style>
</head>
<body>

    <nav>
        <div class="logo">Polai<span> Academy</span></div>
        <div class="nav-links">
            <a href="#">Home</a>
            <a href="#mock">Mock Test</a>
            <a href="#about">About</a>
            <a href="https://youtube.com/@polaiacademy" target="_blank">YouTube</a>
        </div>
    </nav>

    <section class="hero">
        <h1>Excel in Competitive Exams</h1>
        <p>Your ultimate destination for SSC-GD, Railway, OSSC, and Class 1-10 preparation with smart bilingual content.</p>
        <a href="#mock" class="btn-main">Start Your Test Now</a>
    </section>

    <section class="test-features" id="mock">
        <h2>Smart Mock Test Portal</h2>
        <div class="grid">
            <div class="feat-card">
                <i class="fas fa-file-signature"></i>
                <h3>80 Questions</h3>
