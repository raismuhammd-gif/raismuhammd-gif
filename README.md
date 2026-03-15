<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Banner Dino Muhammad Rais</title>
    <style>
        :root {
            --bg-color: #3b5998; /* Warna biru sirkuit */
            --text-color: #ffffff;
        }

        body {
            background-color: #0d1117; /* Warna gelap GitHub */
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            font-family: 'Courier New', Courier, monospace;
        }

        /* Container Banner */
        .banner {
            width: 800px;
            height: 200px;
            background-color: var(--bg-color);
            background-image: 
                radial-gradient(circle, rgba(255,255,255,0.1) 1px, transparent 1px);
            background-size: 20px 20px; /* Pola titik/sirkuit */
            border: 4px solid white;
            border-radius: 10px;
            position: relative;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            overflow: hidden;
        }

        /* Teks Utama */
        .banner h1 {
            color: white;
            font-size: 2.5rem;
            margin: 0;
            z-index: 2;
            text-shadow: 3px 3px #000;
        }

        .banner p {
            color: #f1c40f; /* Warna kuning untuk subtitle */
            font-size: 1.2rem;
            margin-top: 10px;
            z-index: 2;
        }

        /* Karakter Dinosaurus (Pixel Art Style) */
        .dino {
            position: absolute;
            bottom: 20px;
            width: 50px;
            height: 50px;
            background-color: black;
            /* Bentuk sederhana dino dengan clip-path */
            clip-path: polygon(20% 0%, 80% 0%, 100% 20%, 100% 50%, 70% 50%, 70% 100%, 50% 100%, 50% 70%, 20% 70%, 20% 50%, 0% 50%, 0% 20%);
        }

        .dino-left { left: 40px; transform: scaleX(-1); }
        .dino-right { right: 40px; }

        /* Animasi sederhana agar dino terlihat 'hidup' */
        @keyframes bounce {
            0%, 100% { transform: translateY(0) scaleX(-1); }
            50% { transform: translateY(-5px) scaleX(-1); }
        }
        
        .dino-left { animation: bounce 0.6s infinite; }
    </style>
</head>
<body>

    <div class="banner">
        <div class="dino dino-left"></div>
        
        <h1>Selamat Datang Di Muhammad Rais</h1>
        <p>Pengembang Fullstack & UI Designer</p>
        
        <div class="dino dino-right"></div>
    </div>

</body>
</html>

</body>
</html>
## 🌐 Socials:
[![Discord](https://img.shields.io/badge/Discord-%237289DA.svg?logo=discord&logoColor=white)](https://discord.gg/https://discord.gg/MRCsUXd7p) [![Facebook](https://img.shields.io/badge/Facebook-%231877F2.svg?logo=Facebook&logoColor=white)](https://facebook.com/Muhammad Rais) [![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/_mhd.raisz) [![TikTok](https://img.shields.io/badge/TikTok-%23000000.svg?logo=TikTok&logoColor=white)](https://tiktok.com/@mhd.raisz) [![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?logo=YouTube&logoColor=white)](https://youtube.com/@https://youtube.com/@muhammadrais2618?si=zi6oWoSJPP3QoBjP) [![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:raismuhammd@gmail.com) 

# 💻 Tech Stack:
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white) ![OpenStack](https://img.shields.io/badge/Openstack-%23f01742.svg?style=for-the-badge&logo=openstack&logoColor=white) ![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase) ![Render](https://img.shields.io/badge/Render-%46E3B7.svg?style=for-the-badge&logo=render&logoColor=white) ![OpenGL](https://img.shields.io/badge/OpenGL-%23FFFFFF.svg?style=for-the-badge&logo=opengl) ![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white) ![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white) ![JavaFX](https://img.shields.io/badge/javafx-%23FF0000.svg?style=for-the-badge&logo=javafx&logoColor=white) ![Apache](https://img.shields.io/badge/apache-%23D42029.svg?style=for-the-badge&logo=apache&logoColor=white) ![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=Apache%20Airflow&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white) ![CrateDB](https://img.shields.io/badge/CrateDB-009DC7?style=for-the-badge&logo=CrateDB&logoColor=white) ![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white) ![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white) ![Sentry](https://img.shields.io/badge/sentry-%23362D59.svg?style=for-the-badge&logo=sentry&logoColor=white) ![AMD](https://img.shields.io/badge/AMD-%23000000.svg?style=for-the-badge&logo=amd&logoColor=white) ![OpenGL](https://img.shields.io/badge/OpenGL-white?logo=OpenGL&style=for-the-badge)
# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=raismuhammd-gif&theme=dark&hide_border=false&include_all_commits=false&count_private=true)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=raismuhammd-gif&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=raismuhammd-gif&theme=dark&hide_border=false&include_all_commits=false&count_private=true&layout=compact)

## 🏆 GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=raismuhammd-gif&theme=radical&no-frame=false&no-bg=true&margin-w=4)

### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=vetical&theme=radical)

### 🔝 Top Contributed Repo
![](https://github-contributor-stats.vercel.app/api?username=raismuhammd-gif&limit=5&theme=dark&combine_all_yearly_contributions=true)

---
[![](https://visitcount.itsvg.in/api?id=raismuhammd-gif&icon=0&color=0)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
