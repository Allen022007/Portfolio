# Ex01 Portfolio
## Date: 10/06/2026

```
Name :  W Allen Johnston Ozario
Reg. No : 212224110004
```

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM

about.html
```
<!DOCTYPE html>
<html>
<head>
    <title>About</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<div class="nav">
    <a href="port.html">Home</a>
    <a href="about.html" class="active" aria-current="page">About</a>
    <a href="skills.html">Skills</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
</div>

<div class="page">
    <h1>About Me</h1>
    <p class="lead">I build clean, accessible, and responsive web experiences.</p>

    <p>
        I'm a passionate developer who enjoys creating websites that are clean,
        responsive and easy to use.
    </p>

    <p>
        I love learning new technologies and solving real-world problems
        through design and code.
    </p>

    <p>
        <a href="port.html" class="btn btn-primary">← Back to Home</a>
    </p>
</div>

</body>
</html>
```

contact.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Contact </title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<div class="nav">
    <a href="port.html">Home</a>
    <a href="about.html">About</a>
    <a href="skills.html">Skills</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
</div>

<div class="page">
    <h1>Contact Me</h1>

    <p>Email: allenozario.rambo@email.com</p>
    <p>Phone: +91 8838321230</p>
    <a href="https://www.linkedin.com/in/allen-w/">LinkedIn: https://www.linkedin.com/in/allen-w/</a>
</div>

</body>
</html>
```

port.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Home</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<div class="nav">
    <a href="port.html">Home</a>
    <a href="about.html">About</a>
    <a href="skills.html">Skills</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
</div>

<div class="home">
    <h1>Hello, I'm Allen </h1>
    <p>Web Developer</p>
    <p>I build simple, clean and user-friendly web apps 🧑‍💻</p>
</div>

</body>
</html>
```

projects.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Contact </title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<div class="nav">
    <a href="port.html">Home</a>
    <a href="about.html">About</a>
    <a href="skills.html">Skills</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
</div>




<div class="page">
    <h1>My Projects</h1>

    <div class="projects-container">

        <div class="project">
            <h3>Portfolio Website</h3>
            <p>Built a personal portfolio using HTML and CSS with responsive design.</p>
            <a href="#">View Project</a>
        </div>

        <div class="project">
            <h3>Lifeline AI</h3>
            <p>
                AI-powered system that detects early signs of emotional distress,
                silent abuse, or mental health decline by analyzing subtle signals —
                like voice tone, message sentiment, and changes in phone usage.
            </p>
            <a href="#">View Project</a>
        </div>

        <div class="project">
            <h3>To-Do Web App</h3>
            <p>Simple task manager built with JavaScript for daily productivity.</p>
            <a href="#">View Project</a>
        </div>

    </div>
</div>
</body></html>
```

skills.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Skills</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<div class="nav">
    <a href="port.html">Home</a>
    <a href="about.html">About</a>
    <a href="skills.html">Skills</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
</div>

<div class="page">
    <h1>My Skills</h1>

    <div class="skill">HTML</div>
    <div class="skill">CSS</div>
    <div class="skill">JavaScript</div>
    <div class="skill">React</div>
    <div class="skill">Python</div>
</div>

</body>
</html>
```

style.css
```
:root {
    --bg: #0f172a;
    --panel: #1e293b;
    --muted: #e5e7eb;
    --accent: #8b5cf6;
    --accent-2: #4f46e5;
    --accent-cta: #38bdf8;
    --glass: rgba(255,255,255,0.03);
    --card-shadow: 0 15px 40px rgba(0,0,0,0.5);
    --radius: 14px;
}

body {
    margin: 0;
    font-family: "Segoe UI", Arial, sans-serif;
    background: linear-gradient(180deg, var(--bg), #081024 160%);
    color: var(--muted);
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}

/* Navbar */
.nav {
    text-align: center;
    padding: 18px 12px;
    background: rgba(17,24,39,0.9);
    box-shadow: 0 6px 18px rgba(0,0,0,0.45);
    backdrop-filter: blur(4px);
}

.nav a {
    color: var(--muted);
    text-decoration: none;
    margin: 0 14px;
    font-size: 16px;
    font-weight: 700;
    padding: 8px 14px;
    border-radius: 10px;
    transition: all 180ms ease;
}

.nav a:hover {
    color: white;
    transform: translateY(-2px);
    background: linear-gradient(90deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
}

.nav a:focus {
    outline: 2px solid var(--accent);
    outline-offset: 2px;
}

.nav a.active,
.nav a[aria-current="page"] {
    background: linear-gradient(90deg, rgba(139,92,246,0.14), rgba(79,70,229,0.08));
    color: white;
    box-shadow: 0 6px 20px rgba(79,70,229,0.12);
}

/* port.html */
.home {
    text-align: center;
    padding: 160px 20px;

    background: linear-gradient(135deg, #4f46e5, #7c3aed);
}

.home h1 {
    font-size: 52px;
    margin-bottom: 10px;
}

.home p {
    font-size: 18px;
    opacity: 0.95;
}

/*page */
.page {
    max-width: 1000px;
    margin: 60px auto;
    padding: 48px 36px;

    background: linear-gradient(180deg, rgba(255,255,255,0.02), var(--panel));
    border-radius: calc(var(--radius) + 4px);

    box-shadow: var(--card-shadow);
    transition: transform 240ms ease, box-shadow 240ms ease;
    animation: fadeUp 420ms ease both;
}

.page:hover {
    transform: translateY(-6px);
}

.page h1 {
    font-size: 32px;
    margin-top: 0;
    margin-bottom: 8px;
    letter-spacing: -0.5px;
    color: white;
}

.lead {
    font-size: 16px;
    margin-top: 0;
    margin-bottom: 18px;
    color: rgba(229,231,235,0.9);
}

p { line-height: 1.7; color: rgba(229,231,235,0.95); }

/* Buttons */
.btn {
    display: inline-block;
    text-decoration: none;
    padding: 10px 16px;
    border-radius: 10px;
    font-weight: 700;
    color: white;
    transition: transform 150ms ease, box-shadow 150ms ease;
}

.btn:focus { outline: 3px solid rgba(59,130,246,0.18); outline-offset: 3px; }

.btn-primary {
    background: linear-gradient(90deg, var(--accent-2), var(--accent));
    color: white;
    box-shadow: 0 8px 28px rgba(79,70,229,0.12);
}

.btn-primary:hover { transform: translateY(-3px); box-shadow: 0 14px 38px rgba(79,70,229,0.15); }

@keyframes fadeUp {
    from { opacity: 0; transform: translateY(8px); }
    to { opacity: 1; transform: translateY(0); }
}

/* skills.html */
.skill {
    display: inline-block;
    padding: 10px 18px;
    margin: 10px;
    border-radius: 25px;

    background: #8b5cf6;
    color: white;
    font-weight: bold;
}

/* Projects.html */
/* ===== GRID LAYOUT ===== */
.projects-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 30px;
    margin-top: 40px;
}

/* ===== CARD ===== */
.project {
    background: #1f2937;
    padding: 25px;
    border-radius: 14px;
    color: white;

    box-shadow: 0 10px 30px rgba(0,0,0,0.5);

    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

/* button */
.project a {
    margin-top: 15px;
    display: inline-block;
    padding: 8px 14px;
    background: #38bdf8;
    color: black;
    border-radius: 6px;
    text-decoration: none;
    font-weight: 600;
}


/* Contact.html */
.contact p {
    margin: 10px 0;
    font-size: 16px;
}

/* ===== Footer ===== */
.footer {
    text-align: center;
    padding: 18px;
    background: #111827;
    margin-top: 40px;
}

/*responsive*/
@media(max-width: 600px){
    .project {
        width: 90%;
    }

    .home h1 {
        font-size: 34px;
    }
}

```

## OUTPUT

![alt text](<Screenshot 2026-02-11 154406.png>)
![alt text](<Screenshot 2026-02-11 154236.png>)
![alt text](<Screenshot 2026-02-11 154412.png>)
![alt text](<Screenshot 2026-02-11 160335.png>)
![alt text](<Screenshot 2026-02-11 160124.png>)

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
