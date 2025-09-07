<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ashik Iqbal - Android Developer</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
            color: #f0f6fc;
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
            background: rgba(255, 255, 255, 0.05);
            border-radius: 20px;
            margin-bottom: 30px;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.2);
        }
        
        h1 {
            font-size: 3.5rem;
            margin-bottom: 10px;
            background: linear-gradient(90deg, #4CAF50, #8BC34A);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        
        h2 {
            font-size: 1.8rem;
            margin-bottom: 20px;
            color: #c9d1d9;
        }
        
        h3 {
            font-size: 1.5rem;
            margin: 30px 0 20px;
            color: #8BC34A;
            display: flex;
            align-items: center;
        }
        
        h3 i {
            margin-right: 10px;
        }
        
        .tagline {
            font-size: 1.2rem;
            color: #8b9bb4;
            max-width: 800px;
            margin: 0 auto 25px;
        }
        
        .profile-info {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            margin-bottom: 40px;
        }
        
        .card {
            flex: 1;
            min-width: 300px;
            background: rgba(255, 255, 255, 0.05);
            border-radius: 15px;
            padding: 25px;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.2);
        }
        
        .stats {
            display: flex;
            justify-content: space-around;
            margin-top: 20px;
            flex-wrap: wrap;
            gap: 15px;
        }
        
        .stat-item {
            text-align: center;
            padding: 15px;
            background: rgba(255, 255, 255, 0.08);
            border-radius: 10px;
            flex: 1;
            min-width: 120px;
        }
        
        .stat-number {
            font-size: 1.8rem;
            font-weight: bold;
            color: #4CAF50;
        }
        
        .stat-label {
            font-size: 0.9rem;
            color: #8b9bb4;
        }
        
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            margin-top: 15px;
        }
        
        .skill {
            background: rgba(79, 139, 74, 0.2);
            padding: 8px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
            display: flex;
            align-items: center;
        }
        
        .skill i {
            margin-right: 5px;
        }
        
        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }
        
        .social-links a {
            display: inline-block;
            width: 50px;
            height: 50px;
            border-radius: 50%;
            background: linear-gradient(135deg, #4CAF50, #8BC34A);
            color: white;
            text-align: center;
            line-height: 50px;
            font-size: 1.5rem;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        
        .social-links a:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(76, 175, 80, 0.4);
        }
        
        .highlight {
            color: #4CAF50;
            font-weight: bold;
        }
        
        .quote {
            font-style: italic;
            color: #8b9bb4;
            text-align: center;
            margin: 20px 0;
            padding: 15px;
            border-left: 3px solid #4CAF50;
            background: rgba(76, 175, 80, 0.1);
            border-radius: 0 10px 10px 0;
        }
        
        @media (max-width: 768px) {
            h1 {
                font-size: 2.5rem;
            }
            
            h2 {
                font-size: 1.5rem;
            }
            
            .profile-info {
                flex-direction: column;
            }
            
            .stat-item {
                min-width: 100px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Hi, I'm Ashik Iqbal</h1>
            <h2>Android App Developer</h2>
            <p class="tagline">A passionate Android developer from Bangladesh specializing in Kotlin, Jetpack Compose, and creating innovative mobile solutions</p>
            
            <div class="social-links">
                <a href="https://linkedin.com/in/ash1ik-iqbal" target="_blank"><i class="fab fa-linkedin-in"></i></a>
                <a href="https://fb.com/ashi1k" target="_blank"><i class="fab fa-facebook-f"></i></a>
                <a href="https://instagram.com/hulu_dada" target="_blank"><i class="fab fa-instagram"></i></a>
                <a href="mailto:ashikiqbal.nitercse@gmail.com"><i class="far fa-envelope"></i></a>
            </div>
        </header>
        
        <section class="profile-info">
            <div class="card">
                <h3><i class="fas fa-user-graduate"></i> About Me</h3>
                <p>I'm an Android developer with expertise in <span class="highlight">Kotlin, Jetpack Compose, Java, OOP, and Data Structures</span>. I'm passionate about creating clean, efficient, and user-friendly mobile applications.</p>
                
                <div class="quote">
                    "Craving is the key of success."
                </div>
                
                <p>Currently, I'm deepening my knowledge in Android development with Kotlin and exploring advanced Jetpack Compose techniques to build modern Android applications.</p>
            </div>
            
            <div class="card">
                <h3><i class="fas fa-laptop-code"></i> Skills & Technologies</h3>
                <div class="skills">
                    <div class="skill"><i class="fab fa-android"></i> Android</div>
                    <div class="skill"><i class="fab fa-kotlin"></i> Kotlin</div>
                    <div class="skill"><i class="fab fa-java"></i> Java</div>
                    <div class="skill"><i class="fas fa-database"></i> MySQL</div>
                    <div class="skill"><i class="fab fa-firebase"></i> Firebase</div>
                    <div class="skill"><i class="fab fa-figma"></i> Figma</div>
                    <div class="skill"><i class="fab fa-git-alt"></i> Git</div>
                    <div class="skill"><i class="fab fa-linux"></i> Linux</div>
                    <div class="skill"><i class="fas fa-code"></i> C/C++</div>
                </div>
                
                <h3 style="margin-top: 25px;"><i class="fas fa-tools"></i> Development Tools</h3>
                <div class="skills">
                    <div class="skill"><i class="fas fa-code"></i> Android Studio</div>
                    <div class="skill"><i class="fas fa-terminal"></i> Terminal</div>
                    <div class="skill"><i class="fab fa-git-alt"></i> GitHub</div>
                </div>
            </div>
        </section>
        
        <div class="card">
            <h3><i class="fas fa-chart-line"></i> GitHub Stats</h3>
            <div class="stats">
                <div class="stat-item">
                    <div class="stat-number">750+</div>
                    <div class="stat-label">Commits</div>
                </div>
                <div class="stat-item">
                    <div class="stat-number">15+</div>
                    <div class="stat-label">Projects</div>
                </div>
                <div class="stat-item">
                    <div class="stat-number">10+</div>
                    <div class="stat-label">Repositories</div>
                </div>
                <div class="stat-item">
                    <div class="stat-number">500+</div>
                    <div class="stat-label">Contributions</div>
                </div>
            </div>
            
            <p style="margin-top: 20px; text-align: center; color: #8b9bb4;">
                Note: These are representative stats as GitHub's API sometimes doesn't show accurate data.
            </p>
        </div>
    </div>
    
    <script>
        // Simple counter animation for stats
        document.addEventListener('DOMContentLoaded', function() {
            const statNumbers = document.querySelectorAll('.stat-number');
            const duration = 2000; // ms
            const frameRate = 30; // fps
            const totalFrames = Math.round(duration / (1000 / frameRate));
            
            statNumbers.forEach(stat => {
                const targetValue = parseInt(stat.textContent);
                let currentFrame = 0;
                const startValue = Math.round(targetValue * 0.2);
                const increment = (targetValue - startValue) / totalFrames;
                let currentValue = startValue;
                
                const counter = setInterval(() => {
                    currentFrame++;
                    currentValue += increment;
                    stat.textContent = Math.round(currentValue) + (stat.textContent.includes('+') ? '+' : '');
                    
                    if (currentFrame >= totalFrames) {
                        clearInterval(counter);
                        stat.textContent = targetValue + (stat.textContent.includes('+') ? '+' : '');
                    }
                }, 1000 / frameRate);
            });
        });
    </script>
</body>
</html>
