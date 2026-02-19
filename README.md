<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Civilized World Engineering Consultancy</title>
    <style>
        :root {
            --primary-green: #2e7d32;
            --dark-blue: #1a237e;
            --light-bg: #f4f7f4;
            --white: #ffffff;
        }

        * { box-sizing: border-box; }
        body { font-family: 'Segoe UI', Arial, sans-serif; margin: 0; color: #333; scroll-behavior: smooth; line-height: 1.6; }
        
        header { background: var(--white); padding: 15px 5%; display: flex; justify-content: space-between; align-items: center; box-shadow: 0 2px 10px rgba(0,0,0,0.1); position: sticky; top: 0; z-index: 1000; }
        .logo { font-weight: bold; font-size: 1.1rem; color: var(--primary-green); text-transform: uppercase; letter-spacing: 1px; }
        nav a { margin-left: 20px; text-decoration: none; color: #444; font-weight: 600; font-size: 0.9rem; }
        nav a:hover { color: var(--primary-green); }

        .hero { 
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://images.unsplash.com/photo-1503387762-592dea58ef21?auto=format&fit=crop&w=1600&q=80');
            background-size: cover; background-position: center; height: 60vh; color: white; 
            display: flex; flex-direction: column; justify-content: center; align-items: center; text-align: center; padding: 0 20px;
        }
        .hero h1 { font-size: 2.5rem; margin-bottom: 10px; }
        .hero p { font-size: 1.1rem; max-width: 600px; margin-bottom: 25px; opacity: 0.9; }

        section { padding: 80px 10%; border-bottom: 1px solid #eee; }
        h2 { text-align: center; color: var(--dark-blue); font-size: 2rem; margin-bottom: 40px; position: relative; }
        h2::after { content: ''; width: 60px; height: 3px; background: var(--primary-green); position: absolute; bottom: -10px; left: 50%; transform: translateX(-50%); }

        .about-content { max-width: 800px; margin: 0 auto; text-align: center; }
        .team-card { background: var(--light-bg); padding: 30px; border-radius: 10px; margin-top: 30px; border-left: 5px solid var(--primary-green); box-shadow: 0 4px 6px rgba(0,0,0,0.05); }
        .team-card h3 { color: var(--primary-green); margin: 10px 0 5px 0; font-size: 1.5rem; }
        .team-card .title { font-weight: bold; color: #1a237e; text-transform: uppercase; font-size: 0.8rem; letter-spacing: 1px; }

        .service-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 20px; }
        .card { background: var(--white); padding: 30px; border: 1px solid #ddd; border-radius: 5px; transition: 0.3s; }
        .card:hover { transform: translateY(-5px); box-shadow: 0 10px 20px rgba(0,0,0,0.1); border-color: var(--primary-green); }
        .card h3 { color: var(--primary-green); margin-top: 0; }

        .contact { background: var(--primary-green); color: white; text-align: center; }
        .contact h2 { color: white; }
        .contact h2::after { background: white; }
        .phone-link { font-size: 2.2rem; color: white; text-decoration: none; font-weight: bold; display: block; margin: 20px 0; }
        .address-box { margin-top: 20px; font-style: normal; font-size: 1.1rem; opacity: 0.9; border-top: 1px solid rgba(255,255,255,0.3); padding-top: 20px; }
        .btn { background: white; color: var(--primary-green); padding: 12px 30px; text-decoration: none; border-radius: 5px; font-weight: bold; display: inline-block; }

        footer { background: #111; color: #777; text-align: center; padding: 20px; font-size: 0.8rem; }
    </style>
</head>
<body>

    <header>
        <div class="logo">Civilized World Engineering</div>
        <nav>
            <a href="#about">About</a>
            <a href="#services">Services</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section class="hero">
        <h1>Design Your Dream Home</h1>
        <p>Comprehensive architectural and structural services from initial planning to project completion.</p>
        <a href="#contact" class="btn">Free Consultation</a>
    </section>

    <section id="about">
        <h2>About the Firm</h2>
        <div class="about-content">
            <p>Civilized World Engineering Consultancy is committed to creating beautiful, safe, and inspiring spaces. We combine technical precision with creative vision to deliver excellence in every project.</p>
            
            <div class="team-card">
                <div class="title">Lead Engineer</div>
                <h3>Souvik Sengupta</h3>
                <p>Specializing in architectural design, structural blueprints, and end-to-end project management.</p>
            </div>
        </div>
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <div class="service-grid">
            <div class="card">
                <h3>Initial Planning</h3>
                <p>We provide detailed structural blueprints and feasibility studies to start your project on the right track.</p>
            </div>
            <div class="card">
                <h3>Architectural Design</h3>
                <p>Modern and sustainable design solutions tailored to your specific needs and aesthetic preferences.</p>
            </div>
            <div class="card :hover">
                <h3>Project Completion</h3>
                <p>Ensuring your project is managed professionally from the first brick to the final handover.</p>
            </div>
        </div>
    </section>

    <section id="contact" class="contact">
        <h2>Get In Touch</h2>
        <p>Ready to turn your architectural dreams into reality? Call us today:</p>
        
        <a href="tel:+919679854401" class="phone-link">+91 9679854401</a>
        
        <div class="address-box">
            <strong>Location:</strong><br>
            Alipurduar, West Bengal, India
        </div>
    </section>

    <footer>
        <p>&copy; 2026 Civilized World Engineering Consultancy. All Rights Reserved.</p>
    </footer>

</body>
</html>
