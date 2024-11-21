<!DOCTYPE html>
<html lang="en">
<head>

    <style>
	       *{
    font-family: Arial, Helvetica, sans-serif;
}
.container{
    width: 65%;
    margin-left: 15%;
    padding: 20px, 0px;
    border: rgb(224, 216, 216);
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}
body{
    margin-left: 5%;
    
}
header{
    text-align: center;
    padding-top: 30px;
    line-height: .7;
}
img{
    background: black;
    border: solid black;
    border-radius: 100px;
}
nav{
    background-color: #333;
    margin: 0 20px;
    border-radius: 2px;
    position: sticky;
    top: 0;
    z-index: 1000;
}
nav ul{
    list-style-type: none;
    display: flex;
    padding: 8px;
    justify-content: center;
}
nav ul li{
    margin: 0 21px;
}
nav ul li a{
    text-decoration: none;
    color: white;
    font-weight: bold;
    text-transform: capitalize;
    padding: 5px;
}
nav ul li a:hover{
    background-color: white;
    color: black;
    border-radius: 10px;
}
h3{
    border-bottom: 3px solid #333;
    margin: 0 20px;
    color: #333;
}
section {
    margin-bottom: 10px;
}
section h3 {
    border-bottom: 2px solid #333;
    padding-bottom: 5px;
    margin-bottom: 10px;
    color: #333;
}
.para{
    margin:15px 20px 15px;
    text-align: justify;
    line-height: 1.2;
}
ul{
    list-style-type: none;
}
.ul li{
    background-color: rgb(240, 224, 208);
    margin: 5px 0px 13px 0;
    border-left: 5px solid rgb(35, 34, 34);
    padding: 7px 0 7px 15px;
    border-radius: 3px;
    margin-left: -20px;
    margin-right: 20px;

}
table{
    width: 96%;
    margin: 10px 20px 20px 20px;
}
table, th, td{
    border-collapse: collapse;
}
th, td{
    border: 1px solid rgb(52, 50, 50);
    padding: 10px;
}
table th{
    background-color: rgb(210, 232, 225);
}
form {
    display: flex;
    flex-direction: column;
}

form label {
    margin-top: 10px;
    margin-left: 20px;
}

form input, form textarea {
    padding: 10px;
    margin: 5px 0;
    margin-left: 20px;
    margin-right: 20px;
}

button {
    background-color: #4CAF50;
    color: white;
    border: none;
    padding: 10px;
    cursor: pointer;
    margin-top: 10px;
   margin: 0 20px;
}

button:hover {
    background-color: #45a049;
}
  
footer{
    text-align: center;
    padding-bottom: 20px;
}
	</style>
	
	
    <meta charset="UTF-7">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ASSIGNMENT</title>
    <link rel="stylesheet" href="CV.CSS">
</head>
<body>
    <div class="container">
    <header>
    <img src="photo.jpg" height="200px" width="200px" alt="no image here">
    <h2>Saikot Roy</h2>
    <p>Web Designer</p>
    <p>Email: saikotroy.bugm20@gmail.com| Phone: +8801538408305</p>
    <p>Adress: Dept Of Geology and Mining, University Of Barishal</p>
    </header>
    <nav>
        <ul>
            <li><a href="#about">About Me</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#experience">Experience</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#achievement">Achievement</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <selection>
    <h3>About Me</h3>
    <p class="para">Motivated web developer with 2 years of experience in creating dynamic and responsive website using HTML, CSS. Strong ability to learn and adapt to new technologies, with a passion for creating user friendly designs.</p>
    </selection>
    <section id="skills">
    <h3>Skills</h3>
    <ul class="ul li">
        <li>HTML5 & CSS3</li>
        <li>Bootstrap Framework</li>
        <li>Adobe Photoshop & Illustrator</li>
    </ul>
    </section>
    <section id="experience">
    <h3>Experience</h3>
    <ul class="ul li">
        <li><b>Digital marketing speacialist- </b> Samrat IT (Jan 2022 - Mar 2023)<br>Developed and maintaied the company website, ensuring a smooth user experience across all devieces.</li>
        <li><b>Web developer- </b>ABC Solutions(Aug 2020 - Dec 2021)<br>Assisted in the development of client websites, focusing on front-end design and functionality.</li>
      
    </ul>
    </section>
    <section id="education">
    <h3>Education</h3>
    <table>
        <tr>
            <th>Degree</th>
            <th>Institution</th>
            <th>Session Year</th>
            <th>CGPA</th>
        </tr>
        <tr>
            <td>Bachelor of Science in Geology and Mining (on going) </td>
            <td>University of Barishal</td>
            <td>2019-20 </td>
            <td>3.40 up </td>
        </tr>
        <tr>
            <td>Higher Secondary Certificate</td>
            <td>Govt. Collage Bangabandhu College </td>
            <td>2018</td>
            <td>4.50</td>
        </tr>
    </table>
    </section>
    <section id="achievement">
    <h3>Achievements and Awards</h3>
    <ul class="ul li">
        <li>Coursera best Student Awards - 2021</li>
        
    </ul>
    </section>
    <section id="projects">
    <h3>Projects and Research</h3>
    <ul class="ul li">
        <li><b>Project Title: </b>Dynamic Portfolio Website<br>Develped a responsive portfolio website with interactive features using HTML, CSS, and JavaScript.</li>
        <li><b>Research paper: </b>Optimizing Web Performance<br>Conducted research on web performance optimization techniques and implemented findings in real world projects.</li>
    </ul>
    </section>
    <section id="contact">
    <h3>Contact Me</h3>
    <form action="submit_form.php" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        
        <label for="message">Message:</label>
        <textarea id="message" name="message" required></textarea>
        
        <button type="submit">Send Message</button>
    </form>
    </section>
    <footer>
        2024 Saikot - All Rights Reserved
    </footer>
</div>
</body>
</html>
