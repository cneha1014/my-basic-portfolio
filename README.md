# my-basic-portfolio

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Neha's Portfolio</title>
   
    <style>
        html{
            border: 2px solid #4e4bef;
            border-radius: 0.4px;
            box-shadow: 0 0 1px rgba(0, 0, 0, 0.5);
        }
         body {
            font-family: Arial, sans-serif;
            margin: 70px;
            padding: 0;
            background-color: #d1cfe6;
            color: #333333;
            border: 10px solid #020202;
            box-sizing: border-box;
        }
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #bbc3f7;
            color: #333333;
            border: #000000;
        }
        
header {
    background-color:#186ebffd;  
    color: white; 
    align-items: justify;   
    padding: 3%;
    height: 150px;
    width: 1450px;
}


#header-container {
    display: flex;             
    justify-content: space-between; 
    align-items: center; 
    width: 150px;
    height: 150px;   
    position: relative;
     
}


#header-text {
    text-align: right; 
    justify-items: auto;
    display: contents;   
    margin-right: auto;
    float: right; 
    font-size: large;  
    padding: 100px;
    position: absolute;
    right: 200px; 
    top: -800px;
  
       
}


#profile-pic {
    width: 170px;             
    height: 170px;            
    border-radius: 900%;       
    object-position: left;         
    align:left;
    position:relative;
    top: -76.55px;
    left: 5px;
   
  
    
    
}
 nav {
            text-align: center;
            margin: 40px 0;
        }
        nav a {
            margin: 0 35px;
            text-decoration: none;
            color:#186ebffd;
            font-weight: bold;
        }
        nav a:hover {
            color:#186ebffd;
        }
        section {
            padding: 2em;
            max-width: 800px;
            margin: auto;
        }
        .section-title {
            text-align: center;
            color:#186ebffd;
        }
        .skills-list, .hobbies-list {
            list-style: none;
            padding: 0;
        }
        .skills-list li, .hobbies-list li {
            background: #eef6fc;
            margin: 5px 0;
            padding: 70px;
            border-radius: 8px;
        }
        footer {
            text-align: center;
            padding: 1em 0;
            background-color:#186ebffd;
            color: white;
        }
        #contact a {
    color:#186ebffd; 
    text-decoration: none; 
}

#contact a:hover {
    color: #3000cc00; 
}

#contact ul {
    list-style: none; 
    padding: 0;       
    margin-left: 20px; 
}

#contact li {
    background: #09429d; 
    padding: 10px;      
    margin: 5px 0;       
    border-radius: 5px;  
    text-align: justify; 
    position: relative;  
}

#contact li::before {
    content: "•";       
    color: #0055cc;     
    font-size: 20px;    
    position: absolute; 
    left: -20px;        
    top: 0;
}
#contact {
    background-color: rgba(155, 205, 247, 0);
    z-index: 10%; 
    color: #0c0c0c; 
    padding: 1px; 
    border-radius: 10px; 
    max-width: 300px; 
    margin: 10px auto; 
    box-shadow: 0 4px 6px rgb(0, 0, 0); 
}

#contact a {
    color: #0d00ff; 
    text-decoration: none; 
}

#contact a:hover {
    color: #2c00cd; 
p {
        line-height: 1.8;
    }
}
 </style>
 
</head>
<body>
    <header>
    
        <div id="header-content";>
            <div id="header-text">
        <h1>Welcome to My Portfolio</h1>
        <h3>NEHA C,MCA Graduate</h3>
        </div>
        <div id="profile-pic" id="clear"> 
         <img src="neha.img (2).jpg" alt="Neha's Profile Picture" id="profile-pic"></div>
        
        </div>
    
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#Technical skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#Researchpaper">Research paper</a>
        <a href="#hobbies">Hobbies</a>
        <a href="#contact">Contact</a>
    </nav>
    <section id="about">
        <h2 class="section-title">About Me</h2>
        <p style="text-align: justify;">
            Hello! I’m Neha, an accomplished Master of Computer Applications graduate with a deep passion for software development and artistic expression. My expertise spans Core Java, Spring Boot, SQL, and web technologies such as HTML, CSS, and JavaScript, enabling me to craft efficient, scalable, and user-focused applications.

            Beyond my technical pursuits, I channel my creativity into sketching and writing, enriching my ability to approach problems from innovative perspectives. With a commitment to continuous learning and excellence, I am driven to deliver impactful solutions that blend technical precision with a touch of artistry.
            
        </p>
        <hr>
        <h2 class="section-title"> Technical Skills</h2>
        <ul class="skills-list"></ul>
            <li>Core Java</li>
            <li>OOPs Concepts</li>
            <li>Collections in Java</li>
            <li>Spring Security</li>
            <li>Spring Boot</li>
            <li>DBMS</li>
            <li>SQL</li>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
         </ul>
         <hr>
         <h2 class="section-title"> Non-Technical Skills</h2>
        <ul class="skills-list"></ul>
            <li>Adaptability</li>
            <li>Time management</li>
            <li>collaboration & Teamwork</li>
            <li>Work ethic</li>
            <li>Eager to learn new skills</li>
        </ul>
        <hr>
        <h2 class="section-title">Projects</h2>
        <p style="text-align: justify;">
            <strong>Personal AI Desktop Assistant:</strong> <br>
            A Personal AI Desktop Assistant is a software application designed to automate tasks and provide assistance through voice recognition and data integration. It can perform actions such as opening applications, setting reminders, managing files, searching the web, or retrieving information based on user commands. 

Built using technologies like Python, APIs, and natural language processing (NLP), it enhances productivity by simplifying repetitive tasks. Features such as voice interaction, task scheduling, and integration with third-party services make it highly versatile. It can be customized for personal or professional use, providing a user-friendly interface to streamline daily activities.
        </p>

        <p style="text-align: justify;">
            <strong>Stockpile Applications:</strong> <br>
            A Stockpile Application is an advanced software solution designed to streamline inventory management and enhance supply chain efficiency. It enables businesses to monitor stock levels in real time, track procurement and allocation activities, and optimize storage and distribution processes.  

With features like inventory tracking, automated alerts, and data-driven insights, it helps reduce stockouts, minimize overstocking, and improve operational accuracy. By integrating seamlessly with supply chain workflows, the application ensures businesses maintain a balanced inventory, enhance productivity, and meet customer demands more effectively.
         
        <p style="text-align: justify;">
            <strong>E-Press Club:</strong> <br>
            This project aims to establish an organizational platform catering to
journalists and other professionals involved in the creation
and dissemination of news. It endeavors to provide a structured framework
conducive to collaboration, innovation, and the efficient flow of information
within the industry. Through its initiatives, the project seeks to enhance the
effectiveness and impact of journalism in society
        </p>

        </h2>
        <hr>

        <h2 class="section-title">ResearchPaper</h2>
        <h3>Blue Brain:</h3>
        <p style="text-align: justify;">
            The Blue Brain Project is a pioneering research initiative aimed at creating a digital reconstruction of the human brain to study its structure and functionality. It focuses on understanding the brain's complexities by simulating neural networks at various levels using advanced computational models.  

            By replicating how neurons and synapses interact, the project seeks to uncover insights into brain disorders, memory, and cognition. Leveraging supercomputers and data-driven techniques, it provides a platform for virtual experiments that are otherwise impractical. The Blue Brain Project represents a significant step toward bridging neuroscience and technology, contributing to advancements in medical and artificial intelligence research. 
        </p>
        <hr>

        <h2 class="section-title">Hobbies</h2>
        <ul class="hobbies-list"></ul>
            <li>Exploring New Recipes.</li>
            <li>Pencil Sketching & Painting.</li>
            <li>Singing & also listening to music.</li>
            <li>Playing indoor & outdoor games.</li>
         </ul>
         


    </section>
    
    
    <section id="contact">
        <h2 class="section-title">Contact Me</h2>
        <ul>
            mail ID: <a href="mailto:cneha1014@gmail.com">cneha1014@gmail.com</a><br>
            LinkedIn: <a href="https://www.linkedin.com/in/neha-c-a26a9a233/">linkedin.com/in/neha-profile</a><br>
            Instagram: <a href="https://www.instagram.com/neha_cneh/profilecard/?igsh=djR4dWZwM2tqZmVv">@neha-profile</a><br>
        </ul>
            
    </section>
    
    
    <footer>
        <p>&copy;  Neha's Portfolio. All Rights Reserved.</p>
    </footer>
</body>
</html>
