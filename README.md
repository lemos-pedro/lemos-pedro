<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ariclene Pedro de Lemos - Desenvolvedor FullStack</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background: linear-gradient(135deg, #1a2a6c, #b21f1f, #1a2a6c);
            color: #fff;
            line-height: 1.6;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        header {
            text-align: center;
            padding: 60px 20px;
            background: rgba(0, 0, 0, 0.3);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            margin-bottom: 40px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
        }

        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 5px solid #fff;
            object-fit: cover;
            margin: 0 auto 20px;
            background: linear-gradient(45deg, #ff8a00, #e52e71);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 60px;
        }

        h1 {
            font-size: 3rem;
            margin-bottom: 10px;
            background: linear-gradient(45deg, #ff8a00, #e52e71);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
        }

        .subtitle {
            font-size: 1.5rem;
            color: #ffd700;
            margin-bottom: 20px;
        }

        .about {
            background: rgba(255, 255, 255, 0.1);
            padding: 30px;
            border-radius: 15px;
            margin-bottom: 40px;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }

        .about h2 {
            color: #ffd700;
            margin-bottom: 20px;
            font-size: 2rem;
        }

        .about p {
            font-size: 1.1rem;
            line-height: 1.8;
            text-align: justify;
        }

        .skills {
            background: rgba(255, 255, 255, 0.1);
            padding: 30px;
            border-radius: 15px;
            margin-bottom: 40px;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }

        .skills h2 {
            color: #ffd700;
            margin-bottom: 25px;
            font-size: 2rem;
        }

        .tech-icons {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }

        .tech-icon {
            display: flex;
            flex-direction: column;
            align-items: center;
            transition: transform 0.3s ease;
        }

        .tech-icon:hover {
            transform: translateY(-10px);
        }

        .tech-icon img {
            width: 50px;
            height: 50px;
            margin-bottom: 10px;
        }

        .tech-icon span {
            font-size: 0.9rem;
            text-align: center;
        }

        .stats {
            display: flex;
            gap: 30px;
            flex-wrap: wrap;
            margin-bottom: 40px;
        }

        .stat-card {
            flex: 1;
            min-width: 300px;
            background: rgba(255, 255, 255, 0.1);
            padding: 30px;
            border-radius: 15px;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }

        .stat-card h2 {
            color: #ffd700;
            margin-bottom: 20px;
            font-size: 1.8rem;
        }

        .stat-content {
            display: flex;
            align-items: center;
            justify-content: center;
            min-height: 150px;
        }

        .placeholder-img {
            width: 100%;
            height: 180px;
            background: linear-gradient(45deg, #667eea, #764ba2);
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.2rem;
            text-align: center;
            padding: 20px;
        }

        footer {
            text-align: center;
            padding: 30px;
            background: rgba(0, 0, 0, 0.3);
            border-radius: 15px;
            margin-top: 40px;
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin: 20px 0;
        }

        .social-links a {
            color: #fff;
            font-size: 2rem;
            transition: transform 0.3s ease, color 0.3s ease;
        }

        .social-links a:hover {
            transform: scale(1.2);
            color: #ffd700;
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 2rem;
            }
            
            .subtitle {
                font-size: 1.2rem;
            }
            
            .stats {
                flex-direction: column;
            }
            
            .tech-icons {
                gap: 15px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="profile-img">
                <i class="fas fa-user"></i>
            </div>
            <h1>Ariclene Pedro de Lemos</h1>
            <div class="subtitle">Desenvolvedor FullStack</div>
        </header>

        <section class="about">
            <h2>Sobre Mim</h2>
            <p>Me chamo Ariclene Pedro de Lemos, tenho 17 anos e sou natural de Luanda, Angola. Atualmente curso informática no ensino médio e sou profundamente apaixonado por tecnologia e desenvolvimento de software. Estou constantemente explorando novas ferramentas, linguagens de programação e metodologias de desenvolvimento, com o objetivo de criar soluções inovadoras e de alto impacto. Meu foco é unir conhecimento técnico e criatividade para transformar ideias em projetos concretos, sempre atento às tendências do mercado de tecnologia e às melhores práticas do setor.</p>
        </section>

        <section class="skills">
            <h2>Linguagens e Tecnologias</h2>
            <div class="tech-icons">
                <div class="tech-icon">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg" alt="HTML">
                    <span>HTML</span>
                </div>
                <div class="tech-icon">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg" alt="CSS">
                    <span>CSS</span>
                </div>
                <div class="tech-icon">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" alt="JavaScript">
                    <span>JavaScript</span>
                </div>
                <div class="tech-icon">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" alt="Python">
                    <span>Python</span>
                </div>
                <div class="tech-icon">
                    <img src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/django.svg" alt="Django">
                    <span>Django</span>
                </div>
                <div class="tech-icon">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/flask/flask-original.svg" alt="Flask">
                    <span>Flask</span>
                </div>
                <div class="tech-icon">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/bootstrap/bootstrap-original.svg" alt="Bootstrap">
                    <span>Bootstrap</span>
                </div>
                <div class="tech-icon">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/tailwindcss/tailwindcss-original.svg" alt="Tailwind">
                    <span>Tailwind</span>
                </div>
                <div class="tech-icon">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg" alt="PostgreSQL">
                    <span>PostgreSQL</span>
                </div>
                <div class="tech-icon">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original.svg" alt="MySQL">
                    <span>MySQL</span>
                </div>
                <div class="tech-icon">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linux/linux-original.svg" alt="Linux">
                    <span>Linux</span>
                </div>
                <div class="tech-icon">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" alt="Git">
                    <span>Git</span>
                </div>
            </div>
        </section>

        <section class="stats">
            <div class="stat-card">
                <h2>Estatísticas do GitHub</h2>
                <div class="stat-content">
                    <div class="placeholder-img">
                        GitHub Stats - Mostraria suas estatísticas de commits, issues, pull requests e outras métricas de contribuição
                    </div>
                </div>
            </div>
            <div class="stat-card">
                <h2>Linguagens Mais Usadas</h2>
                <div class="stat-content">
                    <div class="placeholder-img">
                        Top Languages - Mostraria um gráfico das linguagens de programação que você mais utiliza nos seus projetos
                    </div>
                </div>
            </div>
        </section>

        <footer>
            <h2>Conecte-se Comigo</h2>
            <div class="social-links">
                <a href="#"><i class="fab fa-github"></i></a>
                <a href="#"><i class="fab fa-linkedin"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
            </div>
            <p>© 2023 Ariclene Pedro de Lemos. Todos os direitos reservados.</p>
        </footer>
    </div>
</body>
</html>
