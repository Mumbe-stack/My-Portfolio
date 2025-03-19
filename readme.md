html
  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="css/styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
</head>
<body>

    <header>
        <h1>Mercy Mumbe</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>


    <section id="hero">
        <img src="./mumbe.jpeg" alt="my image">
        <div class="hero-content">
            <h2>Hello, I am Mercy Mumbe</h2>
            <p>Aspiring Software Developer | Passionate about Web Development</p>
         
            
        </div>
    </section>

  
    <section id="about">
        <h2>About Me</h2>
        <p>I am a procurement officer with a strong analytical mindset and a passion for optimizing supply chain processes. </p>
        <p>With experience in sourcing, contract management, and supplier negotiations, I thrive in fast-paced environments that require strategic decision-making and problem-solving.</p>
        <p>Currently, I am transitioning into software development, driven by my interest in technology and its impact on business efficiency.</p>
        <p>My goal is to bridge the gap between procurement and technology, leveraging software solutions to enhance operational workflows and decision-making.</p>
    </section>


    <section id="skills">
        <h2>Skills</h2>
        <div class="skills">
            <h3>Skill Sets</h3>
            <ul>
                <li>Procurement & Supply Chain Management – Supplier negotiation, contract management, strategic sourcing</li>
                <li>Data Analysis – Cost analysis, market research, trend forecasting</li>
                <li>Project Management – Cross-functional collaboration, risk management, process optimization</li>
                <li>Software Development (Aspiring) – Learning programming languages such as Python, JavaScript, and SQL</li>
                <li>Technology & Business Integration – Exploring automation tools, ERP systems, and data-driven decision-making</li>
                <li>Communication & Problem-Solving – Strong analytical and interpersonal skills to drive innovation and efficiency
                </li>
            </ul> 
        
    </section>

   
    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: <a href="#">mercymumbe17@gmail.com</a></p>
        <p>GitHub: <a href="#" >https://github.com/Mumbe-stack</a></p>
    </section>


    <footer>
        <p>© 2025 Mercy Mumbe | Software Developer Portfolio</p>
    </footer>

</body>
</html>


css

  *
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    scroll-behavior: smooth;
    font-family: "Montserrat", sans-serif;
    font-optical-sizing: auto;
    font-weight: <weight>;
    font-style: normal;
}



header {
    background-color: aqua;
    color: white;
    display: flex;
    justify-content:space-around;
    align-content: center;
    
    padding: 1rem;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}


#hero{
    display: flex;
    align-items: center;
    justify-content: space-around;
    text-align: center;
    padding: 50px;
    background-color: greenyellow;

}

.hero-image{
    width: 200px;
    height: 100px;
    border-radius: 50%;
    object-fit: contain;
    margin-right: 20px;
    background-color: aliceblue;
}

hero-text{
    max-width: 600px;
}


#hero::before {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    z-index: 1;
}

.hero-content {
    position: relative;
  
}


section {
    padding: 50px 20px;
    text-align: center;
}

#about, #contact {
    background-color: #0cc53a;
}
#about
{
    text-align: left;
}
#skills {
    background-color: #ddd;
}

.skills {
    background: rgb(245, 147, 0);
    padding: 15px;
    margin: 10px;
    border-radius: 8px;
    text-align: left;
   
}


footer {
    text-align: center;
    padding: 15px;
    background-color: #333;
    color: white;
}


@media (max-width: 768px) {
    #hero {
        height: 60vh;
    }

    nav ul li {
        display: block;
        margin: 10px 0;
    }
}



