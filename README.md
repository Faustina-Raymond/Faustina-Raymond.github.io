
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Faustina Raymond - Digital Marketing & Marketing Operations</title>
<style>
* {#ff0000
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
font-weight: 900;
color: #000000;
}

header p {
font-size: 1.3em;
opacity: 0.95;
margin-bottom: 30px;
color: #ffffff;
}

header p.tagline {
color: #ffd700;
font-weight: 600;
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

/* Profile Section */
.profile-intro {
padding: 60px 0;
background: white;
}

.profile-content {
display: grid;
grid-template-columns: 1fr 1fr;
gap: 50px;
align-items: center;
max-width: 1000px;
margin: 0 auto;
}

.profile-image {
width: 100%;
max-width: 400px;
height: 500px;
object-fit: cover;
border-radius: 20px;
box-shadow: 0 15px 40px rgba(102, 126, 234, 0.3);
margin: 0 auto;
display: block;
}

.profile-text h2 {
font-size: 2.5em;
margin-bottom: 20px;
color: #667eea;
}

.profile-text p {
font-size: 1.1em;
line-height: 1.8;
margin-bottom: 20px;
}

/* About Section */
.about {
padding: 60px 0;
background: #f8f9fa;
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

/* Graphics Portfolio Section */
.graphics-portfolio {
padding: 60px 0;
background: white;
}

.graphics-portfolio h2 {
text-align: center;
font-size: 2.5em;
margin-bottom: 20px;
color: #667eea;
}

.graphics-portfolio > .container > p {
text-align: center;
font-size: 1.1em;
margin-bottom: 50px;
color: #666;
max-width: 800px;
margin-left: auto;
margin-right: auto;
}

.graphics-grid {
display: grid;
grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
gap: 30px;
margin-bottom: 50px;
}

.graphic-item {
background: white;
border-radius: 15px;
overflow: hidden;
box-shadow: 0 10px 30px rgba(0,0,0,0.1);
transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.graphic-item:hover {
transform: translateY(-10px);
box-shadow: 0 20px 40px rgba(102, 126, 234, 0.3);
}

.graphic-item img {
width: 100%;
height: 400px;
object-fit: cover;
display: block;
}

.graphic-caption {
padding: 20px;
background: #f8f9fa;
}

.graphic-caption h3 {
font-size: 1.3em;
color: #667eea;
margin-bottom: 10px;
}

.graphic-caption p {
color: #666;
font-size: 0.95em;
line-height: 1.6;
}

/* Event Photos Section */
.event-photos {
padding: 40px 0;
}

.event-photos h3 {
text-align: center;
font-size: 2em;
margin-bottom: 40px;
color: #667eea;
}

.event-grid {
display: grid;
grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
gap: 30px;
}

.event-item {
position: relative;
border-radius: 15px;
overflow: hidden;
box-shadow: 0 10px 30px rgba(0,0,0,0.15);
transition: transform 0.3s ease;
}

.event-item:hover {
transform: scale(1.05);
}

.event-item img {
e1ea0337d40b402dfa753be1038920ca1064866a
}

.event-overlay {
position: absolute;
bottom: 0;
left: 0;
right: 0;
background: linear-gradient(to top, rgba(0,0,0,0.8), transparent);
padding: 20px;
color: white;
}

.event-overlay h4 {
font-size: 1.2em;
margin-bottom: 5px;
}
.content-calendar {
padding: 60px 0;
background: white;
}

.content-calendar h2 {
text-align: center;
font-size: 2.5em;
margin-bottom: 30px;
color: #667eea;
}

.content-calendar p {
text-align: center;
font-size: 1.1em;
margin-bottom: 40px;
color: #666;
max-width: 800px;
margin-left: auto;
margin-right: auto;
}

.calendar-preview {
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
padding: 40px;
border-radius: 15px;
color: white;
max-width: 900px;
margin: 0 auto 30px;
box-shadow: 0 10px 30px rgba(102, 126, 234, 0.3);
}

.calendar-preview h3 {
font-size: 1.8em;
margin-bottom: 20px;
text-align: center;
}

.calendar-stats {
display: grid;
grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
gap: 20px;
margin-top: 30px;
}

.stat-card {
background: rgba(255, 255, 255, 0.15);
padding: 20px;
border-radius: 10px;
text-align: center;
transition: all 0.3s ease;
}

.stat-card:hover {
background: rgba(255, 255, 255, 0.25);
transform: translateY(-3px);
}

.stat-number {
font-size: 2.5em;
font-weight: 700;
display: block;
margin-bottom: 5px;
}

.stat-label {
font-size: 1em;
opacity: 0.9;
}

.calendar-table {
background: white;
border-radius: 10px;
overflow: hidden;
box-shadow: 0 5px 15px rgba(0,0,0,0.08);
margin-bottom: 20px;
}

.calendar-table table {
width: 100%;
border-collapse: collapse;
}

.calendar-table th {
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
color: white;
padding: 15px;
text-align: left;
font-weight: 600;
font-size: 0.95em;
}

.calendar-table td {
padding: 15px;
border-bottom: 1px solid #e0e0e0;
color: #333;
font-size: 0.9em;
}

.calendar-table tr:hover {
background: #f8f9fa;
}

.pillar-badge {
display: inline-block;
padding: 4px 12px;
border-radius: 15px;
font-size: 0.85em;
font-weight: 600;
}

.pillar-motivation { background: #e3f2fd; color: #1976d2; }
.pillar-team { background: #f3e5f5; color: #7b1fa2; }
.pillar-wellness { background: #e8f5e9; color: #388e3c; }
.pillar-office { background: #fff3e0; color: #f57c00; }
.pillar-tech { background: #fce4ec; color: #c2185b; }

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

.profile-content {
grid-template-columns: 1fr;
gap: 30px;
}

.profile-image {
height: 400px;
}

.experience-grid, .project-grid, .skills-grid, .graphics-grid, .event-grid {
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
<p class="tagline">Driving Growth Through Strategic Campaigns, Facebook Ads & Operational Excellence</p>
<div class="cta-buttons">
<a href="#projects" class="btn btn-primary">View My Work</a>
<a href="#contact" class="btn btn-secondary">Get In Touch</a>
</div>
</div>
</header>

<!-- Profile Introduction -->
<section class="profile-intro">
<div class="container">
<div class="profile-content">
<img src="https://raw.githubusercontent.com/placeholder-tech/placeholder-images/main/professional-woman-portrait.jpg" alt="Faustina Raymond" class="profile-image" onerror="this.style.display='none'">
<div class="profile-text">
<h2>Meet Faustina</h2>
<p>A results-driven marketing professional with a passion for creating impactful campaigns and seamless operations. My journey in digital marketing has been marked by successful brand activations, strategic content planning, and operational excellence.</p>
<p>From managing major events like Face of Royal to executing high-ROI Facebook ad campaigns, I bring a unique blend of creative strategy and operational efficiency to every project.</p>
</div>
</div>
</div>
</section>

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

<!-- Graphics Portfolio Section -->
<section class="graphics-portfolio">
<div class="container">
<h2>Creative Graphics Portfolio</h2>
<p>A showcase of professionally designed marketing materials, social media graphics, and promotional content created for various brands and campaigns.</p>

<div class="graphics-grid">
<div class="graphic-item">
<img src="https://i.ibb.co/placeholder1" alt="Lipstick Product Campaign" onerror="this.style.background='linear-gradient(135deg, #f093fb 0%, #f5576c 100%)'; this.style.display='flex'; this.style.alignItems='center'; this.style.justifyContent='center'; this.innerHTML='<div style=padding:20px;text-align:center;color:white><h3>Lipstick Campaign</h3><p>Product Launch Design</p></div>'">
<div class="graphic-caption">
<h3>Beauty Product Campaign</h3>
<p>Designed engaging product showcase graphics for lipstick launch featuring bold colors and compelling copy that speaks to diverse audiences.</p>
</div>
</div>

<div class="graphic-item">
<img src="https://i.ibb.co/placeholder2" alt="Beauty Expo Event Graphics" onerror="this.style.background='linear-gradient(135deg, #ffecd2 0%, #fcb69f 100%)'; this.style.display='flex'; this.style.alignItems='center'; this.style.justifyContent='center'; this.innerHTML='<div style=padding:20px;text-align:center;color:#333><h3>Beauty Expo</h3><p>Event Promotion</p></div>'">
<div class="graphic-caption">
<h3>Beauty Fair Event Promotion</h3>
<p>Created promotional materials for Beauty Fair event at Eko Convention Center, featuring clean layouts and effective call-to-action elements.</p>
</div>
</div>

<div class="graphic-item">
<img src="https://i.ibb.co/placeholder3" alt="Cleaning Service Marketing" onerror="this.style.background='linear-gradient(135deg, #a8edea 0%, #fed6e3 100%)'; this.style.display='flex'; this.style.alignItems='center'; this.style.justifyContent='center'; this.innerHTML='<div style=padding:20px;text-align:center;color:#333><h3>Cleaning Service</h3><p>Brand Marketing</p></div>'">
<div class="graphic-caption">
<h3>Service Marketing Graphics</h3>
<p>Developed vibrant marketing materials for Clairvoyant Cleaning Service's back-to-school campaign with clear service offerings and contact details.</p>
</div>
</div>
</div>

<!-- Event Photos -->
<div class="event-photos">
<h3>Behind The Scenes: Event Management</h3>
<div class="event-grid">
<div class="event-item">
<img src="https://i.ibb.co/placeholder4" alt="Face of Royal Event" onerror="this.style.background='linear-gradient(135deg, #667eea 0%, #764ba2 100%)'; this.style.display='flex'; this.style.alignItems='center'; this.style.justifyContent='center'; this.style.color='white'; this.style.fontSize='1.5em'; this.innerHTML='<div style=padding:40px;text-align:center>Face of Royal<br>Event Management</div>'">
<div class="event-overlay">
<h4>Face of Royal 2025</h4>
<p>Major event coordination and execution</p>
</div>
</div>

<div class="event-item">
<img src="https://i.ibb.co/placeholder5" alt="Professional Headshot" onerror="this.style.background='linear-gradient(135deg, #f093fb 0%, #f5576c 100%)'; this.style.display='flex'; this.style.alignItems='center'; this.style.justifyContent='center'; this.style.color='white'; this.style.fontSize='1.5em'; this.innerHTML='<div style=padding:40px;text-align:center>Marketing<br>Professional</div>'">
<div class="event-overlay">
<h4>Marketing Professional</h4>
<p>Strategic campaign execution</p>
</div>
</div>
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

<!-- Content Calendar Section -->
<section class="content-calendar">
<div class="container">
<h2>Content Calendar Management</h2>
<p>Strategic social media content planning and execution across TikTok and LinkedIn platforms with detailed creative direction and content pillars.</p>

<div class="calendar-preview">
<h3>📅 October - November 2025 Content Strategy</h3>
<p style="text-align: center; margin-bottom: 30px;">Multi-platform content calendar featuring engaging workplace humor, product showcases, and team culture content.</p>
<div class="calendar-stats">
<div class="stat-card">
<span class="stat-number">40+</span>
<span class="stat-label">Scheduled Posts</span>
</div>
<div class="stat-card">
<span class="stat-number">2</span>
<span class="stat-label">Platforms</span>
</div>
<div class="stat-card">
<span class="stat-number">10+</span>
<span class="stat-label">Content Pillars</span>
</div>
</div>
</div>

<div class="calendar-table">
<h3 style="padding: 20px; margin: 0; color: #667eea;">TikTok & LinkedIn Content Calendar - Sample</h3>
<table>
<thead>
<tr>
<th>Date</th>
<th>Platform</th>
<th>Content Pillar</th>
<th>Caption</th>
<th>Format</th>
</tr>
</thead>
<tbody>
<tr>
<td>Oct 1, 2025</td>
<td>TikTok</td>
<td><span class="pillar-badge pillar-office">Workday Energy</span></td>
<td>That AC feeling when your Zoom call just got cooler</td>
<td>Video</td>
</tr>
<tr>
<td>Oct 1, 2025</td>
<td>LinkedIn</td>
<td><span class="pillar-badge pillar-motivation">Monday Motivation</span></td>
<td>Like an AC that cools and refreshes, a calm mind fuels clear thinking</td>
<td>Still Graphics</td>
</tr>
<tr>
<td>Oct 3, 2025</td>
<td>TikTok</td>
<td><span class="pillar-badge pillar-tech">Family Kitchen Fun</span></td>
<td>Microwave magic saves the dinner scramble</td>
<td>Video</td>
</tr>
<tr>
<td>Oct 3, 2025</td>
<td>LinkedIn</td>
<td><span class="pillar-badge pillar-wellness">Question</span></td>
<td>What's the real difference between inverter and non-inverter ACs?</td>
<td>Still Graphics</td>
</tr>
<tr>
<td>Oct 6, 2025</td>
<td>TikTok</td>
<td><span class="pillar-badge pillar-tech">Chill Mode Chronicles</span></td>
<td>Fan breeze + family movie = instant chill vibes</td>
<td>Video</td>
</tr>
<tr>
<td>Oct 6, 2025</td>
<td>LinkedIn</td>
<td><span class="pillar-badge pillar-team">Collaborative Team</span></td>
<td>Teamwork makes the dream work! Name a colleague who's been your rock</td>
<td>Video</td>
</tr>
<tr>
<td>Oct 10, 2025</td>
<td>TikTok</td>
<td><span class="pillar-badge pillar-office">HR Related</span></td>
<td>If you laugh you will increase my salary</td>
<td>Video</td>
</tr>
<tr>
<td>Oct 10, 2025</td>
<td>LinkedIn</td>
<td><span class="pillar-badge pillar-wellness">Quiz</span></td>
<td>Save energy, save costs: Choose eco-friendly office appliances</td>
<td>Still Graphics</td>
</tr>
</tbody>
</table>
</div>

<div style="text-align: center; margin-top: 40px;">
<a href="https://drive.google.com/file/d/1gBQyUP0VyadcmkwIff9dgJuuXXWNuCx9/view?usp=drivesdk" class="btn" style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); color: white; padding: 15px 35px; text-decoration: none; border-radius: 25px; font-weight: 600; display: inline-block;">View Full Content Calendar →</a>
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
