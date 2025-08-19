<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jimmy Assignment Help Services</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #f8f9fa;
            color: #333;
            line-height: 1.6;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        header {
            background: linear-gradient(135deg, #1a2a6c, #b21f1f, #fdbb2d);
            color: white;
            padding: 20px 0;
            text-align: center;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        }
        
        .logo {
            font-size: 2.5rem;
            font-weight: bold;
            margin-bottom: 10px;
        }
        
        .tagline {
            font-size: 1.2rem;
            margin-bottom: 20px;
        }
        
        .contact-info {
            background-color: rgba(255, 255, 255, 0.2);
            padding: 10px;
            border-radius: 5px;
            display: inline-block;
            margin-bottom: 10px;
        }
        
        .hero {
            text-align: center;
            padding: 60px 20px;
            background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), url('https://images.unsplash.com/photo-1501504905252-473c47e087f8?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2070&q=80');
            background-size: cover;
            background-position: center;
            color: white;
        }
        
        .hero h2 {
            font-size: 2.5rem;
            margin-bottom: 20px;
        }
        
        .hero p {
            font-size: 1.2rem;
            max-width: 800px;
            margin: 0 auto 30px;
        }
        
        .btn {
            display: inline-block;
            background-color: #25D366;
            color: white;
            padding: 15px 30px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.1rem;
            transition: all 0.3s ease;
            margin: 10px;
        }
        
        .btn:hover {
            background-color: #128C7E;
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
        }
        
        .services {
            padding: 60px 0;
            background-color: white;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 40px;
            font-size: 2.2rem;
            color: #1a2a6c;
        }
        
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .service-card {
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            padding: 25px;
            border-radius: 10px;
            text-align: center;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        
        .service-card:hover {
            transform: translateY(-10px);
        }
        
        .service-icon {
            font-size: 3rem;
            margin-bottom: 20px;
            color: #1a2a6c;
        }
        
        .service-card h3 {
            margin-bottom: 15px;
            color: #1a2a6c;
        }
        
        .subjects {
            padding: 60px 0;
            background: linear-gradient(135deg, #1a2a6c, #b21f1f);
            color: white;
        }
        
        .subjects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        
        .subject-item {
            background-color: rgba(255, 255, 255, 0.1);
            padding: 20px;
            border-radius: 10px;
            text-align: center;
            backdrop-filter: blur(10px);
        }
        
        .guarantees {
            padding: 60px 0;
            background-color: white;
        }
        
        .guarantees-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
        }
        
        .guarantee-card {
            text-align: center;
            padding: 30px 20px;
            border-radius: 10px;
            background-color: #f8f9fa;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
        }
        
        .guarantee-icon {
            font-size: 2.5rem;
            color: #1a2a6c;
            margin-bottom: 20px;
        }
        
        /* New Success Section */
        .success {
            padding: 60px 0;
            background: linear-gradient(135deg, #1a2a6c, #b21f1f);
            color: white;
        }
        
        .score-display {
            text-align: center;
            margin-bottom: 40px;
        }
        
        .score {
            font-size: 5rem;
            font-weight: bold;
            color: #fdbb2d;
            text-shadow: 0 0 10px rgba(253, 187, 45, 0.5);
            margin: 20px 0;
        }
        
        .score-text {
            font-size: 1.5rem;
            margin-bottom: 10px;
        }
        
        .reviews-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .review-card {
            background-color: rgba(255, 255, 255, 0.1);
            padding: 25px;
            border-radius: 10px;
            backdrop-filter: blur(10px);
            position: relative;
        }
        
        .review-card:before {
            content: '"';
            font-size: 5rem;
            position: absolute;
            top: -10px;
            left: 10px;
            opacity: 0.2;
            line-height: 1;
        }
        
        .review-text {
            margin-bottom: 20px;
            font-style: italic;
        }
        
        .reviewer {
            text-align: right;
            font-weight: bold;
        }
        
        .contact {
            padding: 60px 0;
            background: linear-gradient(135deg, #1a2a6c, #b21f1f);
            color: white;
            text-align: center;
        }
        
        .contact-options {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin-top: 30px;
        }
        
        .contact-option {
            background-color: rgba(255, 255, 255, 0.1);
            padding: 20px;
            border-radius: 10px;
            width: 300px;
            backdrop-filter: blur(10px);
        }
        
        .whatsapp-link {
            display: block;
            margin-top: 15px;
            color: #25D366;
            text-decoration: none;
            font-weight: bold;
        }
        
        footer {
            background-color: #1a2a6c;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        
        @media (max-width: 768px) {
            .logo {
                font-size: 2rem;
            }
            
            .hero h2 {
                font-size: 2rem;
            }
            
            .contact-options {
                flex-direction: column;
                align-items: center;
            }
            
            .score {
                font-size: 4rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">Jimmy Assignment Help</div>
            <div class="tagline">Professional Academic Assistance Services</div>
            <div class="contact-info">
                <i class="fab fa-whatsapp"></i> WhatsApp: +254100852064
            </div>
        </div>
    </header>
    
    <section class="hero">
        <div class="container">
            <h2>Expert Assignment Help Services</h2>
            <p>Get professional assistance with your academic assignments, research papers, online exams, and more. Our team of experts is ready to help you achieve academic excellence.</p>
            <a href="https://wa.me/254100852064" class="btn">
                <i class="fab fa-whatsapp"></i> Contact on WhatsApp
            </a>
        </div>
    </section>
    
    <section class="services">
        <div class="container">
            <h2 class="section-title">Our Services</h2>
            <div class="services-grid">
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-graduation-cap"></i>
                    </div>
                    <h3>Thesis & Dissertation</h3>
                    <p>Professional assistance with thesis and dissertation writing, editing, and formatting.</p>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-laptop-code"></i>
                    </div>
                    <h3>Online Exams & Coursework</h3>
                    <p>Help with online examinations, quizzes, and various coursework assignments.</p>
                </div>
