
<html lang="en">

<head>
    <link rel="icon" href="radukai.png">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio - Hector Galvez</title>
    <link rel="stylesheet" href="style.css">

    <style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  background-color: #000;
  color: #e5e5e5;
  font-family: 'Inter', sans-serif;
  display: flex;
  justify-content: center;
  padding: 40px;
}

/* ===== PROFILE ===== */
.profile {
  max-width: 700px;
  width: 100%;
}

.profile__header {
  display: flex;
  align-items: center;
  gap: 1.5rem;
  margin-bottom: 2rem;
}

.profile__avatar {
  width: 70px;
  height: 70px;
  border-radius: 50%;
}

.profile__name {
  font-size: 1.5rem;
  font-weight: 600;
}

.profile__role {
  font-size: 0.95rem;
  color: #aaa;
}

.profile__link {
  color: #4da3ff;
  text-decoration: none;
  font-size: 0.9rem;
}

/* ===== ABOUT ===== */
.profile__about {
  margin-bottom: 2.5rem;
}

.profile__subtitle {
  font-size: 1rem;
  font-weight: 600;
  color: #ccc;
  margin-bottom: 0.6rem;
}

.profile__description {
  font-size: 0.95rem;
  color: #bbb;
  line-height: 1.6;
}

/* ===== EXPERIENCE ===== */
.profile__experience {
  display: flex;
  flex-direction: column;
  gap: 1.2rem;
}

.experience__item {
  display: grid;
  grid-template-columns: 120px 1fr;
  gap: 1rem;
  padding: 1rem;
  border-radius: 12px;
  background-color: #0a0a0a;
  transition: transform 0.25s ease, background-color 0.25s ease;
}

.experience__item:hover {
  transform: scale(1.04);
  background-color: #111;
}

.experience__date {
  font-size: 0.9rem;
  color: #777;
}

.experience__title {
  font-size: 1rem;
  font-weight: 600;
  color: #e5e5e5;
  margin-bottom: 0.4rem;
}

.experience__desc {
  font-size: 0.9rem;
  color: #b0b0b0;
  margin-bottom: 0.4rem;
  line-height: 1.5;
}

.experience__tech {
  font-size: 0.85rem;
  color: #888;
}

/* ===== RESPONSIVE ===== */
@media (max-width: 600px) {
  .experience__item {
    grid-template-columns: 1fr;
  }
  .experience__date {
    margin-bottom: 0.3rem;
  }
}

        footer {
            color: #e6edf3;
            text-align: center;
            padding: 20px 0;
            margin-top: 50px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        footer p {
            margin: 5px 0;
            font-size: 0.95rem;
        }

        footer a {
            color: #58a6ff;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }
                nav{
            position: absolute;
            right: 0;
            top: 0;
            margin-right: 10px;
            margin-top: 10px;
        }

        nav a{
            text-decoration: none;
            color: #e6edf3;
        }
    </style>
</head>

<body>
    <nav>
        
    </nav>
    <main class="profile">
        <section class="profile__header">
            <img src="/Portafolio/radukai.png" alt="Avatar" class="profile__avatar">
            <div class="profile__info">
                <h1 class="profile__name">RaduDev</h1>
                <p class="profile__role">Fullstack Developer</p>
                <a href="mailto:galvezvillaloboshectorluis@gmail.com" class="profile__link">galvezvillaloboshectorluis@gmail.com</a>
            </div>
        </section>

        <section class="profile__about">
            <h2 class="profile__subtitle">About</h2>
            <p class="profile__description">
                Hi there! I’m Hector Luis Galvez Villalobos, a Full Stack Developer focused on building intuitive and engaging web experiences. 
                I hold a degree in Computer Systems Engineering and a technical degree in Administrative Informatics. 
                I love turning ideas into functional projects, always seeking the best solution with logic, efficiency, and a creative touch. 
                Would you like to work together on your next project?
            </p>
        </section>

        <section class="profile__experience">
            <h2 class="profile__subtitle">Work Experience</h2>

            <div class="experience__item">
                <div class="experience__date">2025 – present</div>
                <div class="experience__details">
                    <h3 class="experience__title">University Lecturer – Universidad del Tacaná</h3>
                    <p class="experience__desc">
                        I teach courses for students in Computer Systems Engineering and Pedagogy programs. 
                        My work focuses on promoting logical thinking, problem-solving, and hands-on learning in key areas such as 
                        Introduction to Computing, Robotics, Calculus, and Data & File Organization. 
                        I encourage the use of active learning methods and innovative technologies to help students 
                        develop technical and analytical skills applicable to real-world environments.
                    </p>
                </div>
            </div>

            <div class="experience__item">
                <div class="experience__date">2025 – present</div>
                <div class="experience__details">
                    <h3 class="experience__title">Web Developer – Virtual Calendar Project (Beta)</h3>
                    <p class="experience__desc">
                        I designed and developed a beta-stage web application that serves as a virtual calendar, allowing users to schedule and manage events on specific dates. 
                        The project was built using PHP, MySQL, HTML, CSS, and a touch of JavaScript, with a focus on providing an intuitive and functional interface to enhance users’ personal organization.
                    </p>
                    <p class="experience__tech">PHP • HTML • CSS • MYSQL • JAVASCRIPT</p>
                </div>
            </div>

            <div class="experience__item">
                <div class="experience__date">2024 – 2025</div>
                <div class="experience__details">
                    <h3 class="experience__title">Full Stack Developer – Virtual Scheduler Project with Spring Boot & Angular</h3>
                    <p class="experience__desc">
                        I developed a virtual scheduling system for managing and tracking appointments, dividing the project into two independent applications: 
                        a RESTful API backend built with Spring Boot, and a frontend developed in Angular using TypeScript. 
                        The system enables efficient management of users and appointments, following best practices in architecture and service communication. 
                        <a href="https://github.com/RadukaiDev/agendavirtual">Link to GitHub</a>
                    </p>
                    <p class="experience__tech">SPRINGBOOT • ANGULAR • MYSQL</p>
                </div>
            </div>

            <div class="experience__item">
                <div class="experience__date">2023 – 2024</div>
                <div class="experience__details">
                    <h3 class="experience__title">Systems Engineering Intern – ISSSTE, Dr. Roberto Nettel Flores Hospital Clinic</h3>
                    <p class="experience__desc">
                        During my internship at the Institute of Security and Social Services for State Workers (ISSSTE), 
                        I developed a virtual scheduling system for medical appointments specifically for tuberculosis patients, improving efficiency in patient care management. 
                        I provided technical support to staff in the Teaching, Human Resources, and Nursing departments, 
                        and assisted in the installation of a fingerprint-based attendance system to enhance employee access control within the hospital. 
                        <a href="https://github.com/RadukaiDev/isssteApp">Link to GitHub</a>
                    </p>
                    <p class="experience__tech">PHP • HTML • CSS • MYSQL • JAVASCRIPT • BOOTSTRAP</p>
                </div>
            </div>
        </section>

        <br>
        <section class="profile__tools">
            <h2 class="profile__subtitle">Tools</h2>
            <p class="profile__description">
                I work with a wide range of technologies used in modern software development, both on the frontend and backend. 
                My toolkit includes <strong>PHP</strong>, <strong>MySQL</strong>, <strong>Spring Boot</strong>, 
                <strong>Angular</strong>, <strong>TypeScript</strong>, <strong>HTML</strong>, <strong>CSS</strong>, 
                and <strong>JavaScript</strong>. 
                I also have experience with frameworks like <strong>Bootstrap</strong>, environments such as <strong>XAMPP</strong> and 
                <strong>Postman</strong>, and version control tools like <strong>Git</strong> and <strong>GitHub</strong>.
            </p>
        </section>

        <br>
        <section class="profile__skills">
            <h2 class="profile__subtitle">Skills</h2>
            <p class="profile__description">
                I have strong skills in web development, problem-solving, and logical thinking. 
                I hold a <strong>B2 level of English</strong> that allows me to communicate effectively in technical and collaborative environments, 
                and I’m currently <strong>learning French</strong>. 
                I’m known for being committed, adaptable, and eager to learn new technologies while tackling complex challenges.
            </p>
        </section>
            <footer>
        <p>Developed by <strong>RaduDev</strong></p>
        <p>Contact me at <a href="mailto:galvezvillaloboshectorluis@gmail.com">galvezvillaloboshectorluis@gmail.com</a></p>
    </footer>
    </main>
</body>
</html>
