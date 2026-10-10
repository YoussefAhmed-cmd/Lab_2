# Lab_2
HTML Code:

<html>

<head>

<title>John Doe Portfolio</title>
<link rel="stylesheet" href="behavior.css">


</head>

<body>
    <header>
        <h1>John Doe</h1>
        <p>Web Developer  Designer  Freelancer</p>
    </header>
    <h2>About Me</h2>
    <p>
        Hello! I'm John, a passionate web developer with experience in creating responsive and
        <br>interactive websites. I love coding, designing, and bringing ideas to life on the web.
    </p>
    <h2>Projects</h2>
    <div class=" project-container">
    <div class="project-card">
        <h3>Project One</h3>
        <p>A brief description of the project goes here.</p>
    </div>

    <div class="project-card">
        <h3>Project Two</h3>
        <p>A brief description of the project goes here.</p>
    </div>

    <div class="project-card">
        <h3>Project Three</h3>
        <p>A brief description of the project goes here.</p>
    </div>
    </div>
    <h2>Contact Me</h2>
    <form>
        <input type="text" placeholder="Your Name">

        <input type="email" placeholder="Your Email">

        <textarea placeholder="Your Message"></textarea>

        <button type="submit">Send Message</button>
    </form>
    <footer>
        <p>© 2025 John Doe. All Rights Reserved.</p>
    </footer>
</body>
</html>

CSS Code:

header {
    background-color: #123;
    color: white;
    text-align: center;
    padding: 16px 14px;
}

h1 {
        margin: 0 0 0 0;
        font-size: 26px;
        text-align: center
}

p {
        margin: 0 0 0 0;
        color: #321;
        text-align:center
}
h2{
    text-align:center
}
h3{
    text-align :center
}
body {
    margin: 0;
    text-align: center;
    font-family: 'Times New Roman', Times, serif;
    background-color: #0000;
    color: #222;
}
.project-container {
    display: flex;
    justify-content: center;
    gap: 16px;
}
.projects {
    padding: 45px 20px 75px;
}

.projects h2 {
        text-align: center;
        font-size: 28px;
        margin: 0 0 30px;
}




.project-card {
    background-color: white;
    width: 245px;
    padding: 18px 16px;
}

.project-card h3 {
        margin: 0 0 12px;
        font-size: 17px;
}

.project-card p {
        margin: 0;
        font-size: 14px;
}

footer {
    background-color: #222;
    color: white;
    text-align: center;
    padding: 16px;
}

footer p {
        margin: 0;
        font-size: 13px;
}
