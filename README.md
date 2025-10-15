
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Faustina Raymond - Digital Marketing & Marketing Operations</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background: #f8f9fa;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Header */
        header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 80px 0;
            text-align: center;
        }

        header h1 {
            font-size: 3em;
            margin-bottom: 10px;
            font-weight: 700;
        }

        header p {
            font-size: 1.3em;
            opacity: 0.95;
            margin-bottom: 30px;
        }

        .cta-buttons {
            margin-top: 30px;
        }

        .btn {
            display: inline-block;
            padding: 12px 30px;
            margin: 0 10px;
            border-radius: 25px;
            text-decoration: none;
            font-weight: 600;
            transition: all 0.3s ease;
        }

        .btn-primary {
            background: white;
            color: #667eea;
        }

        .btn-primary:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.2);
        }

        .btn-secondary {
            background: transparent;
            color: white;
            border: 2px solid white;
        }

        .btn-secondary:hover {
            background: white;
            color: #667eea;
        }

        /* About Section */
        .about {
            padding: 60px 0;
            background: white;
        }

        .about h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
            color: #667eea;
        }

        .about p {
            font-size: 1.1em;
            max-width: 800px;
            margin: 0 auto 30px;
            line-height: 1.8;
        }

        /* Skills Section */
        .skills {
            padding: 60px 0;
            background: #f8f9fa;
        }

        .skills h2 {
            text-align: center;
            font-size: 2.5em;
            margin-bottom: 50px;
            color: #667eea;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
        }

        .skill-card {
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.08);
            transition: transform 0.3s ease;
        }

        .skill-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.15);
        }

        .skill-card h3 {
            color: #667eea;
            margin-bottom: 15px;
            font-size: 1.4em;
        }

        .skill-card ul {
            list-style: none;
        }

        .skill-card li {
            padding: 5px 0;
            color: #666;
        }

        .skill-card li:before {
            content: "✓ ";
            color: #667eea;
            font-weight: bold;
            margin-right: 8px;
        }

        /* Experience Section */
        .experience {
            padding: 60px 0;
            background: white;
        }

        .experience h2 {
            text-align: center;
            font-size: 2.5em;
            margin-bottom: 50px;
            color: #667eea;
        }

        .experience-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 30px;
            max-width: 1000px;
            margin: 0 auto;
        }

        .experience-card {
            background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
            color: white;
            padding: 35px;
            border-radius: 15px;
            transition: transform 0.3s ease;
        }

        .experience-card:nth-child(2) {
            background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
        }

        .experience-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 30px rgba(0,0,0,0.2);
        }

        .experience-card h3 {
            font-size: 1.6em;
            margin-bottom: 15px;
            border-bottom: 2px solid rgba(255,255,255,0.3);
            padding-bottom: 10px;
        }

        .experience-card p {
            margin-bottom: 20px;
            opacity: 0.95;
            line-height: 1.7;
        }

        .experience-card ul {
            list-style: none;
        }

        .experience-card li {
            padding: 8px 0;
            padding-left: 20px;
            position: relative;
        }

        .experience-card li:before {
            content: "▸";
            position: absolute;
            left: 0;
            font-weight: bold;
        }

        /* Projects Section */
        .projects {
            padding: 60px 0;
            background: #f8f9fa;
        }

        .projects h2 {
            text-align: center;
            font-size: 2.5em;
            margin-bottom: 50px;
            color: #667eea;
        }

        .project-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }

        .project-card {
            background: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.08);
            transition: transform 0.3s ease;
            border-top: 4px solid #667eea;
        }

        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 30px rgba(102, 126, 234, 0.2);
        }

        .project-card h3 {
            font-size: 1.4em;
            margin-bottom: 15px;
            color: #667eea;
        }

        .project-card p {
            margin-bottom: 20px;
            color: #666;
        }

        .project-link {
            display: inline-block;
            padding: 10px 20px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-size: 0.9em;
            transition: all 0.3s ease;
        }

        .project-link:hover {
            transform: translateX(5px);
            box-shadow: 0 5px 15px rgba(102, 126, 234, 0.3);
        }

        /* Contact Section */
        .contact {
            padding: 80px 0;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            text-align: center;
        }

        .contact h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        .contact p {
            font-size: 1.2em;
            margin-bottom: 30px;
        }

        .contact-info {
            display: flex;
            justify-content: center;
            gap: 40px;
            margin-top: 30px;
            flex-wrap: wrap;
        }

        .contact-item {
            display: flex;
            align-items: center;
            gap: 10px;
            background: rgba(255,255,255,0.1);
            padding: 15px 25px;
            border-radius: 10px;
            transition: all 0.3s ease;
        }

        .contact-item:hover {
            background: rgba(255,255,255,0.2);
            transform: translateY(-3px);
        }

        .contact-item a {
            color: white;
            text-decoration: none;
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 30px;
        }

        .social-link {
            display: inline-block;
            width: 50px;
            height: 50px;
            background: rgba(255,255,255,0.2);
            border-radius: 50%;
            line-height: 50px;
            text-align: center;
            color: white;
            text-decoration: none;
            font-size: 1.2em;
            transition: all 0.3s ease;
        }

        .social-link:hover {
            background: white;
            color: #667eea;
            transform: translateY(-3px);
        }

        /* Footer */
        footer {
            background: #2d3748;
            color: white;
            text-align: center;
            padding: 20px 0;
        }

        /* Responsive */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2em;
            }

            header p {
                font-size: 1.1em;
            }

            .btn {
                display: block;
                margin: 10px auto;
                max-width: 200px;
            }

            .experience-grid, .project-grid, .skills-grid {
                grid-template-columns: 1fr;
            }

            .contact-info {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <h1>Faustina Raymond</h1>
            <p>Digital Marketing Specialist & Marketing Operations Executive</p>
            <p style="font-size: 1em; opacity: 0.9;">Driving Growth Through Strategic Campaigns, Facebook Ads & Operational Excellence</p>
            <div class="cta-buttons">
                <a href="#projects" class="btn btn-primary">View My Work</a>
                <a href="#contact" class="btn btn-secondary">Get In Touch</a>
            </div>
        </div>
    </header>

    <!-- About Section -->
    <section class="about">
        <div class="container">
            <h2>Welcome to My Portfolio</h2>
            <p>I'm a professional digital marketing specialist with a proven track record of running successful campaigns and managing comprehensive marketing operations. My expertise spans from executing high-performing Facebook ads campaigns to managing large-scale marketing operations including asset distribution, event coordination, and sales exhibitions.</p>
            <p>As a marketing operations executive, I've successfully managed company assets across multiple distribution centers, coordinated major events like Face of Royal, and organized sales exhibitions that drive business growth. I combine strategic marketing thinking with operational excellence to deliver measurable results.</p>
        </div>
    </section>

    <!-- Skills Section -->
    <section class="skills">
        <div class="container">
            <h2>My Skills & Expertise</h2>
            <div class="skills-grid">
                <div class="skill-card">
                    <h3>Digital Marketing</h3>
                    <ul>
                        <li>Facebook Ads Management</li>
                        <li>Social Media Marketing</li>
                        <li>Content Creation</li>
                        <li>Email Campaign Strategy</li>
                        <li>SEO Optimization</li>
                        <li>Copywriting</li>
                    </ul>
                </div>
                <div class="skill-card">
                    <h3>Marketing Operations</h3>
                    <ul>
                        <li>Company Asset Management</li>
                        <li>T-shirt Distribution Logistics</li>
                        <li>Banner Distribution Across DCs</li>
                        <li>Event Management & Coordination</li>
                        <li>Sales Exhibition Planning</li>
                        <li>Operations Process Optimization</li>
                    </ul>
                </div>
                <div class="skill-card">
                    <h3>Strategy & Execution</h3>
                    <ul>
                        <li>Sales Funnel Design</li>
                        <li>Customer Avatar Development</li>
                        <li>Social Media Calendar Planning</li>
                        <li>Video Editing</li>
                        <li>Virtual Assistant Services</li>
                        <li>Sales Management</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Experience Section -->
    <section class="experience">
        <div class="container">
            <h2>My Work Experience</h2>
            <div class="experience-grid">
                <div class="experience-card">
                    <h3>Digital Marketing Specialist</h3>
                    <p>As a professional digital marketer, I've driven growth for multiple companies through strategic marketing initiatives:</p>
                    <ul>
                        <li>Run high-performing Facebook ads with massive results</li>
                        <li>Organize and execute major sales campaigns as Sales Manager</li>
                        <li>Create captivating content and compelling copy</li>
                        <li>Develop detailed customer avatars for targeted marketing</li>
                        <li>Design and implement effective sales funnels</li>
                        <li>Manage comprehensive social media strategies</li>
                    </ul>
                </div>
                <div class="experience-card">
                    <h3>Marketing Operations Executive</h3>
                    <p>Leading marketing operations with focus on asset management and large-scale event execution:</p>
                    <ul>
                        <li>Manage distribution of company assets (t-shirts, promotional materials)</li>
                        <li>Coordinate banner sharing across multiple Distribution Centers (DCs)</li>
                        <li>Plan and execute sales exhibitions and promotional events</li>
                        <li>Organize major events including Face of Royal and similar programs</li>
                        <li>Oversee logistics and operations for marketing activations</li>
                        <li>Ensure brand consistency across all physical touchpoints</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section class="projects" id="projects">
        <div class="container">
            <h2>Featured Work & Case Studies</h2>
            <div class="project-grid">
                <div class="project-card">
                    <h3>Facebook Ads Campaign Results</h3>
                    <p>Executed a high-performing Facebook ads campaign with massive daily results, demonstrating expertise in audience targeting and ad optimization.</p>
                    <a href="https://drive.google.com/file/d/1Fi5nl6OEB47f1OEJToIYf-QJlrBX1aSx/view?usp=drivesdk" class="project-link" target="_blank">View Results →</a>
                </div>
                <div class="project-card">
                    <h3>Sales Funnel Strategy</h3>
                    <p>Designed and implemented a comprehensive sales funnel that guides prospects through the customer journey with strategic touchpoints and conversions.</p>
                    <a href="https://drive.google.com/file/d/1FdvGq970u8Se77lLG2ZnfUda5dCOnMdL/view?usp=drivesdk" class="project-link" target="_blank">View Funnel →</a>
                </div>
                <div class="project-card">
                    <h3>Customer Avatar Development</h3>
                    <p>Created detailed customer avatars to enable precise targeting and personalized marketing strategies for improved campaign performance.</p>
                    <a href="https://drive.google.com/file/d/1U13bEnDMZCLaQhMaLHS7aj3I8KiDFT_P/view?usp=drivesdk" class="project-link" target="_blank">View Avatar →</a>
                </div>
                <div class="project-card">
                    <h3>Social Media Calendar</h3>
                    <p>Developed strategic social media calendars for consistent brand presence and engagement across multiple platforms.</p>
                    <a href="https://drive.google.com/file/d/1gBQyUP0VyadcmkwIff9dgJuuXXWNuCx9/view?usp=drivesdk" class="project-link" target="_blank">View Calendar →</a>
                </div>
                <div class="project-card">
                    <h3>Creative Content Portfolio</h3>
                    <p>A showcase of engaging creative content including graphics, videos, and marketing materials designed for various campaigns.</p>
                    <a href="https://drive.google.com/file/d/1HrzwRvMDBf09AG7TAit8wFoQYItO8-Ns/view?usp=drivesdk" class="project-link" target="_blank">View Creatives →</a>
                </div>
                <div class="project-card">
                    <h3>Event Management Portfolio</h3>
                    <p>Successfully managed multiple marketing events including Face of Royal, sales exhibitions, and promotional activations with comprehensive logistics coordination.</p>
                    <a href="#contact" class="project-link">Contact for Details →</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact" id="contact">
        <div class="container">
            <h2>Let's Work Together</h2>
            <p>Ready to grow your business with strategic marketing and operations excellence?</p>
            <div class="contact-info">
                <div class="contact-item">
                    <span>📧</span>
                    <a href="mailto:raymondfausina12@gmail.com">raymondfausina12@gmail.com</a>
                </div>
                <div class="contact-item">
                    <span>📱</span>
                    <a href="tel:+2349031576892">+234 903 157 6892</a>
                </div>
                <div class="contact-item">
                    <span>📍</span>
                    <span>Jakande Lekki, Lagos State, Nigeria</span>
                </div>
            </div>
            <a href="mailto:raymondfausina12@gmail.com" class="btn btn-primary" style="margin-top: 30px;">Send Me an Email</a>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2025 Faustina Raymond. All rights reserved.</p>
            <p style="margin-top: 10px; font-size: 0.9em;">Digital Marketing Specialist | Marketing Operations Executive</p>
        </div>
    </footer>
</body>
</html>
