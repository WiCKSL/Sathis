<!DOCTYPE html>

<html>
<head>
  <title> Sathish protfolio</title>
  <style>
  body {
        font-family: Arial sans-serif;
        margin: 0;
         padding: 0;
          backgroud-color: #7cf00;
  }
  header {
    background-color: #6495ED;
    color: #00000;
    text-align: center;
    padding: 2rem 0;
    position: relatice; /* Add this*/
  }
  .header-content h1 {
      font-size: 2.5rem;
  }
  /*Add styles for the round profile picture */
  .profile-picture {
    width: 100px; /*Adjust the size as needed */
    height: 100px;
    border-radius: 75% /* create a circular shape */
    object-fit: cover; /* to ensure the image fills the circular area */
    position: absolute; /* Add this */
    top: 75px; /* Adjust top position as needed */
    left: 200px; /* Adjust left position as needed */
  }
  nav {
    background-color: #333;
    color: #fff;
    text-align: center;
  }
  nav ul {
        list-style-type:name;
        padding: 0;
  }
  nav ul li {
    display: inline;
    margin: 0 20px;
  }
  nav ul li a {
    text-decoration: none;
    color:  #fff;
  }
  .section-content {
     background-color: #ADD8E6;
    color: #000;
    padding: 2rem;
    margin: 1rem;
    border-radius: 20px;
    box-shadow: 0 0 10px  rgba (0, 0, 0, 0.1);
  }
  .download-button{
    background-color:  #000;
    color:  #fff;
    padding:  0.5rem 1rem;
    text-decoration: none;
    border-radius: 20px;
    display: inline-block;
    margin-top: 10px;
  }
  .download-button: hover {
    background-color: black;
  }
  footer {
    text-align: center;
    padding: 1rem 0;
    background-color:  #000;
    color:  #0000ff;
  }
  ul {
    list-style-type: lower-alpha;
    padding-left: 20px;
  }
  </style>
</head>
<body>
  <header>
        <img  src="" >
    <width="100px" height="100px" >
    <p>Hi I,M</p>
        <h1> SATHISHKUMAR.S,</h1>
        <p>  (STUDENT)  </p>  
         
  </header>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#education">Education</a></li>
        <li><a href="#skill">Skill</a></li>
        <li><a href="#language">Language</a></li>
  </ul>
    </nav>
    <section id="about">
      <div class="section-content">
        <h2> ABOUT</h2>
        <p>  WELCOME Everyone! </p> 
        <p>  I consider myself a responsible and orderly person.</p>
      </div>
    </section>
  <section id="Skills">
      <div class="section-content">
        <h2> SKILLS</h2>
        <ul style="list-style-type:square">
          <li> HTML </li>
          <li> Mobile repairing </li>
          <li> Creative poster</li>
          <li> IBM skill learning</li>
        </ul>
      </div>
    </section>
    <section id="education">
      <div class="section-content">
        <h1> EDUCATION </h1>
        <h2>HIGER EDUCATION</h2>
        <p>Government Hr.Sec School</p>
        <p>2019-2020</p>
        <h2>STUDIED AT BHARATHIAR UNIVERSITY</h2>
        <p>2021 at present</p>
        <h3>Bsc.(INFORMATION TECHNOLOGY)</h3>
        <p> Pioneer College of Arts and Science </p>
      </div>
    </section>
    <section id="language">
      <div class="section-content">
        <h2>LANGUAGE</h2>
        <ul style="list-style-type:square">
          <li>Tamil (native)</li>
          <li>English</li>
        </ul>
      </div>
    </section>
</body>
</html>
