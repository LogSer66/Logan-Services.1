# Logan-Services
Logan Services
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Logan Services | Professional Auto Repair in Vandalia, OH</title>
    <style>
        :root {
            --primary-color: #d9381e; /* Mechanic Red Accent */
            --dark-color: #1a1a1a;
            --light-color: #f8f9fa;
            --text-color: #333333;
        }
        
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            color: var(--text-color);
            line-height: 1.6;
            background-color: #ffffff;
        }

        /* Hero Section */
        header {
            background: linear-gradient(rgba(0, 0, 0, 0.75), rgba(0, 0, 0, 0.85)), url('https://unsplash.com') no-repeat center center/cover;
            color: #ffffff;
            padding: 100px 20px;
            text-align: center;
        }

        header h1 {
            font-size: 3rem;
            letter-spacing: 2px;
            color: #ffffff;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.2rem;
            margin-bottom: 30px;
            color: #cccccc;
        }

        .cta-buttons a {
            display: inline-block;
            padding: 12px 30px;
            margin: 10px;
            text-decoration: none;
            font-weight: bold;
            border-radius: 5px;
            transition: 0.3s;
        }

        .btn-primary {
            background-color: var(--primary-color);
            color: #ffffff;
        }

        .btn-primary:hover {
            background-color: #b82c14;
        }

        .btn-secondary {
            border: 2px solid #ffffff;
            color: #ffffff;
        }

        .btn-secondary:hover {
            background-color: #ffffff;
            color: var(--dark-color);
        }

        /* Sections */
        section {
            padding: 60px 20px;
            max-width: 1000px;
            margin: 0 auto;
        }

        h2 {
            font-size: 2rem;
            color: var(--dark-color);
            margin-bottom: 20px;
            border-bottom: 3px solid var(--primary-color);
            display: inline-block;
            padding-bottom: 5px;
        }

        /* Services Grid */
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .service-card {
            background: var(--light-color);
            padding: 20px;
            border-left: 5px solid var(--primary-color);
            border-radius: 3px;
        }

        .service-card h3 {
            margin-bottom: 10px;
            color: var(--dark-color);
        }

        /* Pricing Table */
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }

        th, td {
            padding: 12px 15px;
            text-align: left;
            border-bottom: 1px solid #ddd;
        }

        th {
            background-color: var(--dark-color);
            color: white;
        }

        tr:nth-child(even) {
            background-color: var(--light-color);
        }

        .price-note {
            font-size: 0.9rem;
            color: #666;
            margin-top: 15px;
            display: block;
        }

        /* Contact & Footer */
        .contact-info {
            background-color: var(--light-color);
            padding: 30px;
            border-radius: 5px;
            margin-top: 20px;
        }

        .contact-info p {
            margin-bottom: 15px;
            font-size: 1.1rem;
        }

        .contact-info a {
            color: var(--primary-color);
            text-decoration: none;
            font-weight: bold;
        }

        footer {
            background-color: var(--dark-color);
            color: #888888;
            text-align: center;
            padding: 40px 20px;
            font-size: 0.85rem;
            border-top: 4px solid var(--primary-color);
        }

        footer strong {
            color: #cccccc;
        }

        @media (max-width: 600px) {
            header h1 { font-size: 2.2rem; }
            .cta-buttons a { display: block; margin: 10px 0; }
        }
    </style>
</head>
<body>

    <!-- Hero Section -->
    <header>
        <h1>LOGAN SERVICES</h1>
        <p>Professional Auto Repair & Maintenance | Vandalia, Ohio</p>
        <div class="cta-buttons">
            <a href="tel:+16143327689" class="btn-primary">Call Now: +1 (614) 332-7689</a>
            <a href="mailto:edsbabe1@gmail.com" class="btn-secondary">Email Us</a>
        </div>
    </header>

    <!-- About Section -->
    <section id="about">
        <h2>About Us</h2>
        <p><strong>Logan Services</strong> is a trusted local auto repair shop established in <strong>January 2026</strong> in Vandalia, Ohio. Founded and operated by <strong>Rhonda Hardin</strong>, we are fully dedicated to providing our community with honest, transparent pricing and exceptional mechanical work. We treat every vehicle with the utmost care as if it were our own.</p>
    </section>

    <!-- Services Section -->
    <section id="services">
        <h2>Our Services</h2>
        <div class="services-grid">
            <div class="service-card">
                <h3>Diagnostic Services</h3>
                <p>Advanced computer scanning to accurately identify check engine lights and system errors quickly.</p>
            </div>
            <div class="service-card">
                <h3>Brake Repairs</h3>
                <p>Full-service brake maintenance including pad replacement, rotors, and fluid line bleeding.</p>
            </div>
            <div class="service-card">
                <h3>Engine & Transmission</h3>
                <p>Dependable mechanical repairs, standard engine tune-ups, and complex component replacements.</p>
            </div>
            <div class="service-card">
                <h3>Oil & Fluid Changes</h3>
                <p>Fast and clean routine fluid maintenance designed to maximize and prolong your engine's lifespan.</p>
            </div>
            <div class="service-card">
                <h3>Suspension & Steering</h3>
                <p>Wheel alignments, shock absorbers, struts, and steering rack diagnostics and repairs.</p>
            </div>
            <div class="service-card">
                <h3>Electrical Systems</h3>
                <p>Battery testing, alternator diagnostics, starter replacements, and wiring system repairs.</p>
            </div>
        </div>
    </section>

    <!-- Pricing Section -->
    <section id="pricing">
        <h2>Affordable Pricing & Estimates</h2>
        <table>
            <thead>
                <tr>
                    <th>Service</th>
                    <th>Estimated Starting Price</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td><strong>Standard Oil & Filter Change</strong></td>
                    <td>From $45.00</td>
                </tr>
                <tr>
                    <td><strong>Full Synthetic Oil Change</strong></td>
                    <td>From $75.00</td>
                </tr>
                <tr>
                    <td><strong>Computerized Engine Diagnostics</strong></td>
                    <td>From $89.00</td>
                </tr>
                <tr>
                    <td><strong>Brake Pad Replacement (Per Axle)</strong></td>
                    <td>From $150.00</td>
                </tr>
                <tr>
                    <td><strong>Tire Rotation & Safety Inspection</strong></td>
                    <td>From $35.00</td>
                </tr>
                <tr>
                    <td><strong>Battery Testing & Replacement</strong></td>
                    <td>From $120.00</td>
                </tr>
            </tbody>
        </table>
        <small class="price-note">*Note: Prices may vary depending on your vehicle's make, model, and specific fluid or component requirements. Contact us for a precise, written quote.</small>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact & Location</h2>
        <div class="contact-info">
            <p><strong>📍 Shop Address:</strong> 1200 Industrial Park Dr., Vandalia, OH 45377</p>
            <p><strong>📞 Phone:</strong> <a href="tel:+16143327689">+1 (614) 332-7689</a></p>
            <p><strong>✉️ Email:</strong> <a href="mailto:edsbabe1@gmail.com">edsbabe1@gmail.com</a></p>
            <p><strong>🕒 Hours:</strong> Monday – Friday: 8:00 AM – 5:00 PM | Saturday: By Appointment</p>
        </div>
    </section>

    <!-- Legal Footer -->
    <footer>
        <p><strong>Trade Name (DBA):</strong> Logan Services &nbsp;|&nbsp; <strong>Legal Entity Name:</strong> Rhonda Hardin DDS (Sole Proprietorship) &nbsp;|&nbsp; <strong>EIN:</strong> 43-2300705</p>
        <p style="margin-top: 15px; color: #555555;">&copy; 2026 Logan Services. All rights reserved.</p>
    </footer>

</body>
</html>
<p style="font-size: 12px; color: #666; text-align: center; margin-top: 20px;">
  <strong>Privacy Policy:</strong> We respect your privacy. Logan Services collects and uses your personal information (such as name, phone number, and email) solely to provide auto repair services, process payments via Stripe, and communicate with you about your vehicle. We do not sell, rent, or share your data with third parties for marketing purposes. All financial transactions are securely processed by Stripe under their privacy guidelines.
</p>
