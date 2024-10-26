<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>{{ site.title | default: "Your Name - Data Science & Machine Learning Portfolio" }}</title>
    <link rel="stylesheet" href="{{ '/assets/styles.css' | relative_url }}">
</head>
<body>

<header>
    <h1>Default Name</h1>
    <p>Data Scientist | Machine Learning Enthusiast | Portfolio</p>
</header>

<main>
    <section id="about">
        <h2>About Me</h2>
        {{ site.sections['about'].content }}
    </section>

    <section id="education">
        <h2>Educational Background</h2>
        {{ site.sections['education'].content }}
    </section>

    <section id="work">
        <h2>Work Experience</h2>
        {{ site.sections['work'].content }}
    </section>

    <section id="projects">
        <h2>Projects</h2>
        {{ site.sections['projects'].content }}
    </section>

    <section id="awards">
        <h2>Awards and Honors</h2>
        {{ site.sections['awards'].content }}
    </section>

    <section id="publications">
        <h2>Publications</h2>
        {{ site.sections['publications'].content }}
    </section>
</main>

<footer>
    <p>Connect with me on <a href="https://www.linkedin.com/in/your-profile" target="_blank">LinkedIn</a> | View my <a href="https://github.com/your-profile" target="_blank">GitHub</a></p>
</footer>

</body>
</html>
