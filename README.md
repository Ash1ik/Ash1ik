<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Profile Enhancer</title>
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
            padding: 20px;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            background: rgba(255, 255, 255, 0.05);
            border-radius: 20px;
            padding: 30px;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.2);
        }
        
        header {
            text-align: center;
            padding: 30px 0;
            margin-bottom: 20px;
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            background: linear-gradient(90deg, #4CAF50, #8BC34A);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        
        h2 {
            font-size: 1.5rem;
            margin-bottom: 20px;
            color: #c9d1d9;
        }
        
        h3 {
            font-size: 1.3rem;
            margin: 25px 0 15px;
            color: #8BC34A;
            display: flex;
            align-items: center;
        }
        
        h3 i {
            margin-right: 10px;
        }
        
        p {
            margin-bottom: 15px;
            color: #c9d1d9;
        }
        
        .code-block {
            background: #1e1e1e;
            border-radius: 10px;
            padding: 20px;
            margin: 20px 0;
            overflow-x: auto;
            font-family: 'Courier New', monospace;
            border: 1px solid #333;
        }
        
        .code-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 15px;
            padding-bottom: 10px;
            border-bottom: 1px solid #333;
        }
        
        .code-header h4 {
            color: #8BC34A;
        }
        
        .copy-btn {
            background: #4CAF50;
            color: white;
            border: none;
            padding: 5px 10px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 0.9rem;
            transition: background 0.3s;
        }
        
        .copy-btn:hover {
            background: #3d8b40;
        }
        
        .instructions {
            background: rgba(76, 175, 80, 0.1);
            border-left: 3px solid #4CAF50;
            padding: 15px;
            border-radius: 0 10px 10px 0;
            margin: 20px 0;
        }
        
        .instructions h4 {
            margin-bottom: 10px;
            color: #8BC34A;
        }
        
        .instructions ol {
            margin-left: 20px;
        }
        
        .instructions li {
            margin-bottom: 10px;
        }
        
        .preview {
            background: #0d1117;
            border-radius: 10px;
            padding: 20px;
            margin: 20px 0;
            border: 1px solid #333;
        }
        
        .preview-header {
            text-align: center;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 1px solid #333;
        }
        
        .badges {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin: 15px 0;
        }
        
        .badge {
            background: #2d333b;
            padding: 5px 10px;
            border-radius: 20px;
            font-size: 0.9rem;
            display: inline-flex;
            align-items: center;
        }
        
        .badge i {
            margin-right: 5px;
        }
        
        .stats {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            margin: 20px 0;
        }
        
        .stat {
            background: rgba(76, 175, 80, 0.1);
            padding: 15px;
            border-radius: 10px;
            flex: 1;
            min-width: 150px;
            text-align: center;
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
        
        @media (max-width: 768px) {
            h1 {
                font-size: 2rem;
            }
            
            h2 {
                font-size: 1.3rem;
            }
            
            .container {
                padding: 20px;
            }
            
            .stat {
                min-width: 120px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>GitHub Profile Enhancer</h1>
            <h2>For Ashik Iqbal - Android Developer</h2>
            <p>This tool will help you create a more engaging GitHub profile with better stats display</p>
        </header>
        
        <section>
            <h3><i class="fas fa-info-circle"></i> About</h3>
            <p>Your GitHub profile is your developer portfolio. A well-crafted README can make a strong impression. Below is enhanced Markdown code for your GitHub profile.</p>
            
            <div class="instructions">
                <h4>How to use this code:</h4>
                <ol>
                    <li>Create a new repository with the same name as your GitHub username</li>
                    <li>Add a README.md file to this repository</li>
                    <li>Copy and paste the code below into your README.md file</li>
                    <li>Customize the content with your specific information</li>
                    <li>Commit the changes to make it live on your profile</li>
                </ol>
            </div>
        </section>
        
        <section>
            <h3><i class="fas fa-code"></i> Enhanced README.md Code</h3>
            <div class="code-block">
                <div class="code-header">
                    <h4>Markdown Code for GitHub Profile</h4>
                    <button class="copy-btn" onclick="copyCode()">Copy Code</button>
                </div>
                <pre><code>## Hi there 👋, I'm Ashik Iqbal

### Android App Developer from Bangladesh

I'm a passionate Android developer with expertise in Kotlin, Jetpack Compose, Java, OOP, and Data Structures. I love creating clean, efficient, and user-friendly mobile applications.

- 🔭 I’m currently working on Android app development
- 🌱 I’m currently learning **App Development using Kotlin**
- 👯 I’m looking to collaborate on open-source Android projects
- 💬 Ask me about **Kotlin, Jetpack Compose, Java, OOP, Data Structure**
- 📫 How to reach me: **ashikiqbal.nitercse@gmail.com**
- ⚡ Fun fact: Craving is the key of success.

### 🛠️ Languages and Tools

<p align="left">
  <a href="https://developer.android.com" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original-wordmark.svg" alt="android" width="40" height="40"/>
  </a>
  <a href="https://kotlinlang.org" target="_blank" rel="noreferrer">
    <img src="https://www.vectorlogo.zone/logos/kotlinlang/kotlinlang-icon.svg" alt="kotlin" width="40" height="40"/>
  </a>
  <a href="https://www.java.com" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/>
  </a>
  <a href="https://firebase.google.com/" target="_blank" rel="noreferrer">
    <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/>
  </a>
  <a href="https://git-scm.com/" target="_blank" rel="noreferrer">
    <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/>
  </a>
  <a href="https://www.figma.com/" target="_blank" rel="noreferrer">
    <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/>
  </a>
  <a href="https://www.mysql.com/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/>
  </a>
</p>

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ashi1kiqbal&show_icons=true&theme=dark&locale=en" alt="ashi1kiqbal" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=ashi1kiqbal&show_icons=true&theme=dark&locale=en&layout=compact" alt="ashi1kiqbal" />
</p>

### 🔗 Connect with Me

<p align="left">
  <a href="https://linkedin.com/in/ash1ik-iqbal" target="blank">
    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="ashik-iqbal17" height="30" width="40" />
  </a>
  <a href="https://fb.com/ashi1k" target="blank">
    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="ashi1k" height="30" width="40" />
  </a>
  <a href="https://instagram.com/hulu_dada" target="blank">
    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="hulu_dada" height="30" width="40" />
  </a>
</p>

### 📈 Activity Graph

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=ashi1kiqbal&theme=react-dark" alt="ashi1kiqbal" />
</p>

### 🏆 GitHub Trophies

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=ashi1kiqbal&theme=onedark" alt="ashi1kiqbal" />
</p>

### 👀 Profile Views

<p align="center"> 
  <img src="https://komarev.com/ghpvc/?username=ashi1kiqbal&label=Profile%20views&color=0e75b6&style=flat" alt="ashi1kiqbal" /> 
</p></code></pre>
            </div>
        </section>
        
        <section>
            <h3><i class="fas fa-eye"></i> Preview</h3>
            <div class="preview">
                <div class="preview-header">
                    <h4>How your GitHub profile will look</h4>
                </div>
                
                <h2>Hi there 👋, I'm Ashik Iqbal</h2>
                <h3>Android App Developer from Bangladesh</h3>
                
                <p>I'm a passionate Android developer with expertise in Kotlin, Jetpack Compose, Java, OOP, and Data Structures.</p>
                
                <div class="badges">
                    <div class="badge"><i class="fab fa-android"></i> Android</div>
                    <div class="badge"><i class="fab fa-kotlin"></i> Kotlin</div>
                    <div class="badge"><i class="fab fa-java"></i> Java</div>
                    <div class="badge"><i class="fas fa-database"></i> MySQL</div>
                </div>
                
                <div class="stats">
                    <div class="stat">
                        <div class="stat-number">750+</div>
                        <div class="stat-label">Commits</div>
                    </div>
                    <div class="stat">
                        <div class="stat-number">15+</div>
                        <div class="stat-label">Projects</div>
                    </div>
                    <div class="stat">
                        <div class="stat-number">10+</div>
                        <div class="stat-label">Repositories</div>
                    </div>
                    <div class="stat">
                        <div class="stat-number">500+</div>
                        <div class="stat-label">Contributions</div>
                    </div>
                </div>
                
                <p>Note: The actual stats on your profile will be pulled dynamically from GitHub.</p>
            </div>
        </section>
        
        <section>
            <h3><i class="fas fa-lightbulb"></i> Additional Tips</h3>
            <div class="instructions">
                <ol>
                    <li>Pin your best repositories to your profile</li>
                    <li>Add a project showcase to highlight your work</li>
                    <li>Contribute to open source to increase your activity graph</li>
                    <li>Keep your profile updated with your latest skills and projects</li>
                    <li>Use GitHub Actions to automatically update your README</li>
                </ol>
            </div>
        </section>
    </div>

    <script>
        function copyCode() {
            const codeElement = document.querySelector('code');
            const textArea = document.createElement('textarea');
            textArea.value = codeElement.textContent;
            document.body.appendChild(textArea);
            textArea.select();
            document.execCommand('copy');
            document.body.removeChild(textArea);
            
            const button = document.querySelector('.copy-btn');
            const originalText = button.textContent;
            button.textContent = 'Copied!';
            
            setTimeout(() => {
                button.textContent = originalText;
            }, 2000);
        }
        
        // Add Font Awesome icons
        const script = document.createElement('script');
        script.src = 'https://kit.fontawesome.com/a076d05399.js';
        script.crossOrigin = 'anonymous';
        document.head.appendChild(script);
    </script>
</body>
</html>
