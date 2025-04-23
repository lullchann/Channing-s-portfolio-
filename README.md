# Channing-s-portfolio-
index_html = """
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Channing Williams Portfolio</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>
  <header>
    <h1>Channing Williams</h1>
    <p>Web Designer | Student Athlete | Community Builder</p>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>
      I’m Channing Williams, a student athlete, web designer, and someone who’s always thinking about how to uplift others—on and off the court.  
      I spend my early mornings grinding on the basketball court, and my afternoons designing clean, creative websites. My passion for service is just as strong as my passion for design—I love giving back through community work, mentorship, and helping others bring their ideas to life through design.
    </p>
    <p>
      Whether I’m leading a team project or running drills at practice, I bring energy, commitment, and creativity to everything I do. I believe websites should not just work—they should inspire. Let me show you how I bring that energy to design.
    </p>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <ul>
      <li>Figma / Adobe XD</li>
      <li>HTML / CSS</li>
      <li>Responsive Design</li>
      <li>Wireframing & Prototyping</li>
      <li>Branding & Creative Concepts</li>
      <li>Team Leadership & Communication</li>
      <li>Community Outreach & Service Planning</li>
    </ul>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    
    <div class="project">
      <h3>FroYo Galaxy</h3>
      <p>A cosmic-themed frozen yogurt site using parallax scrolling and gradients for a playful shopping experience.</p>
    </div>

    <div class="project">
      <h3>Lofi Lounge</h3>
      <p>A chill blog and playlist hub for lo-fi fans, built around calming visuals and cozy interactions.</p>
    </div>

    <div class="project">
      <h3>Plantasy App</h3>
      <p>A mobile concept that gamifies plant care with cute icons, user tracking, and digital garden vibes.</p>
    </div>

    <div class="project">
      <h3>The Imaginarium</h3>
      <p>A personal storytelling-themed site featuring whimsical layouts and scroll-triggered animations.</p>
    </div>
  </section>

  <section id="service">
    <h2>Service & Leadership</h2>
    <p>
      Outside of design and athletics, I’m passionate about making an impact in my community. I’ve volunteered for local youth programs, helped organize charity drives, and participated in clean-up efforts around the city. 
    </p>
    <p>
      I believe leadership doesn’t stop at the scoreboard or the screen—it’s about showing up for others and helping your community grow.
    </p>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:channingwilliams@email.com">channingwilliams@email.com</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Channing Williams</p>
  </footer>
</body>
</html>
"""

style_css = """
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', sans-serif;
  line-height: 1.6;
  background-color: #f9f9f9;
  color: #333;
  padding: 20px;
}

header {
  text-align: center;
  padding: 40px 0;
  background-color: #FF6F61;
  color: white;
}

h1 {
  font-size: 2.5em;
}

section {
  margin: 40px 0;
}

h2 {
  color: #6C5B7B;
  margin-bottom: 15px;
}

ul {
  list-style: disc;
  margin-left: 20px;
}

.project {
  background: #fff;
  padding: 15px;
  margin-bottom: 20px;
  border-left: 5px solid #FF6F61;
  box-shadow: 0 2px 5px rgba(0,0,0,0.05);
}

a {
  color: #6C5B7B;
  text-decoration: none;
}

footer {
  text-align: center;
  padding: 20px;
  font-size: 0.9em;
  color: #999;
}
"""
