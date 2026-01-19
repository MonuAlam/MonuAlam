<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub README Preview - Monu Alam</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;
            background-color: #0d1117;
            color: #c9d1d9;
            padding: 20px;
            line-height: 1.6;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            background-color: #161b22;
            padding: 40px;
            border-radius: 6px;
            border: 1px solid #30363d;
        }
        
        .header {
            text-align: center;
            margin-bottom: 40px;
        }
        
        h1 {
            font-size: 3em;
            margin-bottom: 10px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        
        .tagline {
            font-size: 1.3em;
            color: #8b949e;
            margin-bottom: 20px;
        }
        
        .badges {
            display: flex;
            gap: 10px;
            justify-content: center;
            flex-wrap: wrap;
        }
        
        .badge {
            height: 28px;
            border-radius: 6px;
        }
        
        hr {
            border: none;
            height: 1px;
            background-color: #30363d;
            margin: 40px 0;
        }
        
        h2 {
            font-size: 2em;
            margin-bottom: 20px;
            color: #58a6ff;
        }
        
        h3 {
            font-size: 1.3em;
            margin: 25px 0 15px;
            color: #8b949e;
        }
        
        .about {
            font-size: 1.1em;
            line-height: 1.8;
        }
        
        .about ul {
            list-style: none;
            margin-top: 15px;
        }
        
        .about li {
            margin: 10px 0;
            padding-left: 25px;
            position: relative;
        }
        
        .about li:before {
            content: "→";
            position: absolute;
            left: 0;
            color: #58a6ff;
            font-weight: bold;
        }
        
        .tech-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            margin: 15px 0;
        }
        
        .tech-badge {
            height: 28px;
        }
        
        .stats {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin: 30px 0;
        }
        
        .stat-card {
            background-color: #0d1117;
            border: 1px solid #30363d;
            border-radius: 6px;
            padding: 20px;
            text-align: center;
        }
        
        .stat-card img {
            width: 100%;
            border-radius: 6px;
        }
        
        .achievements {
            display: grid;
            gap: 20px;
            margin: 20px 0;
        }
        
        .achievement {
            background-color: #0d1117;
            border-left: 3px solid #58a6ff;
            padding: 20px;
            border-radius: 6px;
        }
        
        .achievement h4 {
            color: #58a6ff;
            font-size: 1.2em;
            margin-bottom: 10px;
        }
        
        .achievement ul {
            list-style: none;
            margin-left: 20px;
        }
        
        .achievement li {
            margin: 8px 0;
            padding-left: 20px;
            position: relative;
        }
        
        .achievement li:before {
            content: "✓";
            position: absolute;
            left: 0;
            color: #3fb950;
            font-weight: bold;
        }
        
        .competencies {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
            margin: 20px 0;
        }
        
        .competency-item {
            background-color: #0d1117;
            padding: 15px;
            border-radius: 6px;
            border: 1px solid #30363d;
            text-align: center;
            transition: all 0.3s;
        }
        
        .competency-item:hover {
            border-color: #58a6ff;
            transform: translateY(-2px);
        }
        
        .footer {
            text-align: center;
            margin-top: 40px;
            padding-top: 20px;
            border-top: 1px solid #30363d;
        }
        
        .quote {
            font-style: italic;
            color: #8b949e;
            margin: 20px 0;
            font-size: 1.1em;
        }
        
        .connect {
            display: flex;
            gap: 15px;
            justify-content: center;
            margin: 20px 0;
            flex-wrap: wrap;
        }
        
        a {
            color: #58a6ff;
            text-decoration: none;
        }
        
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header -->
        <div class="header">
            <h1>👋 Hey, I'm Monu Alam</h1>
            <p class="tagline">Software Engineer | Backend Specialist | Problem Solver</p>
            <div class="badges">
                <img class="badge" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
                <img class="badge" src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
                <img class="badge" src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=About.me&logoColor=white" alt="Portfolio">
            </div>
        </div>

        <hr>

        <!-- About Section -->
        <h2>🚀 About Me</h2>
        <div class="about">
            <p>I'm a passionate <strong>Backend Engineer</strong> who loves building scalable, high-performance systems. I specialize in crafting robust APIs, architecting microservices, and optimizing system performance. Currently working on enterprise-grade SaaS platforms with a focus on clean architecture and cloud-native solutions.</p>
            
            <ul>
                <li>🔭 Building high-performance backend systems with <strong>Spring Boot</strong> & <strong>Microservices</strong></li>
                <li>🌱 Deep diving into <strong>System Design</strong>, <strong>DSA</strong>, and <strong>Cloud Architecture</strong></li>
                <li>⚡ Optimized APIs to handle <strong>12K+ concurrent requests</strong> with sub-500ms response times</li>
                <li>🎯 Passionate about writing clean, maintainable, and scalable code</li>
            </ul>
        </div>

        <hr>

        <!-- Tech Stack -->
        <h2>🛠️ Tech Arsenal</h2>
        
        <h3>Languages</h3>
        <div class="tech-grid">
            <img class="tech-badge" src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
            <img class="tech-badge" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
            <img class="tech-badge" src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++">
            <img class="tech-badge" src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL">
        </div>

        <h3>Backend & Frameworks</h3>
        <div class="tech-grid">
            <img class="tech-badge" src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" alt="Spring Boot">
            <img class="tech-badge" src="https://img.shields.io/badge/Microservices-FF6C37?style=for-the-badge&logo=microservices&logoColor=white" alt="Microservices">
            <img class="tech-badge" src="https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white" alt="Hibernate">
            <img class="tech-badge" src="https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white" alt="Kafka">
            <img class="tech-badge" src="https://img.shields.io/badge/REST_API-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="REST API">
        </div>

        <h3>Databases</h3>
        <div class="tech-grid">
            <img class="tech-badge" src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
            <img class="tech-badge" src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
            <img class="tech-badge" src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB">
            <img class="tech-badge" src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white" alt="Oracle">
            <img class="tech-badge" src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase">
        </div>

        <h3>Cloud & DevOps</h3>
        <div class="tech-grid">
            <img class="tech-badge" src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS">
            <img class="tech-badge" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
            <img class="tech-badge" src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" alt="GitHub Actions">
            <img class="tech-badge" src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux">
        </div>

        <h3>Tools & Testing</h3>
        <div class="tech-grid">
            <img class="tech-badge" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
            <img class="tech-badge" src="https://img.shields.io/badge/JUnit-25A162?style=for-the-badge&logo=junit5&logoColor=white" alt="JUnit">
            <img class="tech-badge" src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman">
            <img class="tech-badge" src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white" alt="Jira">
        </div>

        <hr>

        <!-- Achievements -->
        <h2>💼 What I've Built</h2>
        <div class="achievements">
            <div class="achievement">
                <h4>🎯 High-Performance API Optimization</h4>
                <ul>
                    <li>Optimized <strong>80+ APIs</strong> with 60% improved response time through caching, indexing, and batching</li>
                    <li>Built systems handling <strong>100K+ assets</strong> with async processing and S3 streaming</li>
                    <li>Implemented efficient multithreading for bulk operations preventing OOM errors</li>
                </ul>
            </div>

            <div class="achievement">
                <h4>🔐 Security & Authentication</h4>
                <ul>
                    <li>Designed <strong>RBAC</strong> systems with Spring Security & JWT</li>
                    <li>Integrated AWS4Signer & IAM for secure inter-service communication</li>
                    <li>CVE-based vulnerability remediation and security hardening</li>
                </ul>
            </div>

            <div class="achievement">
                <h4>📧 Automation & Integration</h4>
                <ul>
                    <li>Built email-based ticketing systems with S3 attachments and auto-routing</li>
                    <li>Engineered workflow automation reducing manual work by 40%</li>
                    <li>Integrated Zabbix alerts for automated incident management</li>
                </ul>
            </div>

            <div class="achievement">
                <h4>☁️ Cloud Architecture</h4>
                <ul>
                    <li>Deployed scalable solutions on <strong>AWS</strong> (EC2, S3, RDS, CloudWatch, CloudFront)</li>
                    <li>Implemented CI/CD pipelines with automated testing and deployment</li>
                    <li>Multi-environment configuration management (Prod, Staging, CI)</li>
                </ul>
            </div>
        </div>

        <hr>

        <!-- GitHub Stats -->
        <h2>📊 GitHub Stats</h2>
        <div class="stats">
            <div class="stat-card">
                <img src="https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&theme=radical&hide_border=true" alt="GitHub Stats">
            </div>
            <div class="stat-card">
                <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=yourusername&layout=compact&theme=radical&hide_border=true" alt="Top Languages">
            </div>
            <div class="stat-card">
                <img src="https://github-readme-streak-stats.herokuapp.com/?user=yourusername&theme=radical&hide_border=true" alt="GitHub Streak">
            </div>
        </div>

        <hr>

        <!-- Core Competencies -->
        <h2>🎓 Core Competencies</h2>
        <div class="competencies">
            <div class="competency-item">Data Structures & Algorithms</div>
            <div class="competency-item">System Design</div>
            <div class="competency-item">Object-Oriented Programming</div>
            <div class="competency-item">Microservices Architecture</div>
            <div class="competency-item">Domain-Driven Design</div>
            <div class="competency-item">Performance Optimization</div>
            <div class="competency-item">Scalability Engineering</div>
            <div class="competency-item">Agile/Scrum Methodologies</div>
            <div class="competency-item">Test-Driven Development</div>
        </div>

        <hr>

        <!-- Contact -->
        <h2>📫 Let's Connect!</h2>
        <p style="text-align: center; margin: 20px 0;">I'm always open to interesting conversations and collaboration opportunities!</p>
        <div class="connect">
            <div>💼 <strong>LinkedIn:</strong> <a href="#">Connect with me</a></div>
            <div>📧 <strong>Email:</strong> <a href="mailto:monualam.edu@gmail.com">monualam.edu@gmail.com</a></div>
            <div>🌐 <strong>Portfolio:</strong> <a href="#">Check out my work</a></div>
        </div>

        <hr>

        <!-- Footer -->
        <div class="footer">
            <p class="quote">"Code is like humor. When you have to explain it, it's bad." – Cory House</p>
            <img src="https://komarev.com/ghpvc/?username=yourusername&color=blueviolet&style=for-the-badge" alt="Profile Views">
        </div>
    </div>
</body>
</html>
