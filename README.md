# Personal-website
echo "# Personal-website" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Naziya-S/Personal-website.git
git push -u origin main

```html
<!DOCTYPE html>

<html lang="en">

<head>

  <meta charset="UTF-8">

  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Naziya Shaik's Personal Website</title>

  <link rel="stylesheet" href="styles.css">

</head>

<body>

  <header>

    <nav>

      <ul>

        <li><a href="#about">About</a></li>

        <li><a href="#projects">Projects</a></li>

        <li><a href="#contact">Contact</a></li>

      </ul>

    </nav>

    <h1>John Doe</h1>

  </header>

 

  <main>

    <section id="about">

      <h2>About Me</h2>

      <p>Hi, I'm Naziya Shaik, An experienced IT Operations and Systems Engineer on a mission to transition into the dynamic world of Cybersecurity. My insatiable curiosity drives me to explore and implement innovative solutions, enhancing digital safety for organizations and individuals in today's rapidly evolving digital landscape. Equipped with a foundation in Project Management, leadership, and conflict resolution, I excel at managing challenging interactions and navigating complex environments. Join me on this exciting journey toward a safer digital future.</p>

    </section>

 

    <section id="projects">

      <h2>Projects</h2>

      <div class="project">

        <h3>Project 1</h3>

        <p>Security Analyst 🎩, analyzing malware and file hash, scrutinize suspicious emails and conduct employee interviews. Safeguard digital assets by identifying and assessing risks. Outlining a Containment Plan with due considerations. Securing the digital landscape!</p>

        <button class="toggle-description">Toggle Description</button>

      </div>

      <div class="project">

        <h3>Project 2</h3>

        <p>Participating in the ELCanHack event has been an enriching experience, where I delved into the complexities and real-time environment. Working within the incident response team was both stimulating and educational, allowing me to refine my technical skills and deepen my understanding of cybersecurity protocols and presentation skills. Using the Semperis tool provided valuable insights into potential attacker tactics and honed my strategic thinking abilities. Team collaboration</p>

        <button class="toggle-description">Toggle Description</button>

      </div>

    </section>

 

    <section id="contact">

      <h2>Contact</h2>

      <form>

        <label for="name">Name:</label>

        <input type="text" id="name" name="Naziya Shaik" required>

 

        <label for="email">Email:</label>

        <input type="email" id="email" name="emailtonaziyashaik@gmail.com" required>

 

        <label for="message">Message:</label>

        <textarea id="message" name="Please reachme out to my email" required></textarea>

 

        <button type="submit">Send</button>

      </form>

    </section>

  </main>

 

  <footer>

    <p>&copy; 2023 John Doe. All rights reserved.</p>

  </footer>

 

  <script src="script.js"></script>

</body>

</html>

```

 
