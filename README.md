<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jatin Kumar' ke pange </title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color:#000080
        }
        header {
            background-color: #008000
            color: sky blue;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        nav {
            margin: 20px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
        }
        section {
            padding: 50px 20px;
            text-align: center;
        }
        section h2 {
            font-size: 2rem;
            margin-bottom: 20px;
        }
        #about, #projects, #skills, #contact {
            background-color: white;
            margin: 20px;
            padding: 40px;
            border-radius: 10px;
            box-shadow: 1px 5px 9px rgba(0,0,0,0.1);
        }
        .projects-grid {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .project-item {
            background-color: #4682B4;
            margin: 10px;
            padding: 20px;
            width: 30%;
            border-radius: 10px;
            box-shadow: 0px 4px 8px rgba(0,0,0,0.1);
        }
        footer {
            background-color: #008080;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
    </style>
</head>
<body>

<!-- Header Section -->
<header>
    <h1>Jatin Kumar'KE PANGE</h1>
    <nav>
        <a href="#about">About Me</a>
        <a href="#projects">Projects</a>
        <a href="#skills">Skills</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<!-- About Section -->
<section id="about">
    <h2>About Me</h2>
    <p>Hello! JANTE HO TUM MERE BARE MAIN KI MAIN KON HU,   AGER JANTE HOGE TO Y THODI PADTE , APPMERE BARE MAIN JANNE AAYE HO YHA TO KUCH JAN KAR HI JANA     BOLO  JAY  PAPA KI   ....  .</p>
</section>

<!-- Projects Section -->
<section id="projects">
    <h2>My Projects</h2>
    <div class="projects-grid">
        <div class="project-item">
            <h3>Project 1: Online Phone Repair Shop</h3>
            <p>A  TO   APPKA KOI BHI PHONE HO   KOI BHI  USME KUCH BHI HUAA HO TO APP YHA  AA SAKTE HO YHA SABHI PRKAR KE PHONE MILTE H SAMJHE KYA  SABHI MATLB SABHI.</p>
        </div>
        <div class="project-item">
            <h3>Project 2: DHAMO MAIN KHANA BNANE KA GYAN</h3>
            <p>TO AGER APPKO KABHI BHI KISI DHAM MAIN KHANA BNANA H TO APP MERE SE BATT KAR SAKTE H KIKESE BNAYE SAMJHE NA .</p>
        </div>
        <div class="project-item">
            <h3>Project 3: BANDER KO BHGANE KA TARIKA</h3>
            <p>TO APKO PTA H KI BANDER KISE KAHTE H NHI TO NIKL JAO YHA SE ,, YHA PAR BANDERO  KO KHETO  SE BHGANE KA KAM KIYA JTA H SAMJHE KYA .</p>
        </div>
    </div>
</section>

<!-- Skills Section -->
<section id="skills">
    <h2>My Skills</h2>
    <p>ye rahi meri kuch uplabhdhiya jo maine ase hi hasil kar li h   :</p>
    <ul>
        <li>HTML, and JavaScript</li>
       
      <li>Phone and Electronics Repair</li>
       
        <li>Shayari Writing</li>
    </ul>
</section>

<!-- Contact Section -->
<section id="contact">
    <h2>Contact Me</h2>
    <p>TO APPKO MERA YE KAM ACHA LGA TO APP MESSEG YA CLL KAR SAKTE DIYE NO PAR SAMJHE!</p>
    <p>Email: <a href="mailto:jk4521948gmail.com">jatin@example.com</a></p>
    <p>Phone: +91 7018424304</p>
</section>

<!-- Footer Section -->
<footer>
    <p>&copy; 2024 Jatin Kumar. All Rights Reserved.</p>
</footer>

</body>
</html>
