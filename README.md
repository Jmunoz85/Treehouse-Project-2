# Treehouse Project 2 
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Jose Munoz Portfolio</title>
    <link rel="stylesheet" href="css/normalize.css" />
    <link href='http://fonts.googleapis.com/css?family=Nunito:400,300' rel='stylesheet' type='text/css'>
    <link rel="stylesheet" href="css/styles.css" />
  </head>
  <body>
    <header>
      <h1>Student Name</h1>
      <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#index.html/portfolio">Portfolio</a></li>
        <li><a href="#index.html/contact">Contact</a></li>
        <li><a href="#index.html/skills">Skills</a></li>
      </ul>
      </nav>

      <div class="profile-image">
        <img src="images/responsive-layout-profile.png" alt="Image of Student">
        <p>Hi! I'm a front-end developer who loves responsive design and css.
        I am currently pursuing a tech degree in front-end web development at Treehouse
        and can't wait to be an official graduate.</p
      </div>
    </header>
      <h2 id="portfolio">Portfolio</h2>
       <ul class="portfolio-items">
        <li>
          <img src="images/portfolio-1.png" alt="Marketing website that i'm intersted in">
          <h2>Marketing Page</h2>
          <p>This project shows the front page of a marketing website meant for a particular business
          that I'm interested in.</p>
       </li>
       <li>
         <img src="images/portfolio-2.png" alt="Search Page">
         <h2>Search Page</h2>
         <p>This project searches through a specific data base to find information that the user is trying to look up.</p>
      </li>
      <li>
        <img src="images/portfolio-3.png" alt="Travel App">
        <h2>Travel App</h2>
        <p>This project compares travel times based on different transportation methods and tells you the best one.</p>
      </li>
      <li>
        <img src="images/portfolio-4.png" alt="A map of all my favorite spots">
        <h2>Map of Favorite Spots</h2>
        <p>This project using mapping apis to plot points to my favorite spots in the city for a do it yourself walking tour.</p>
      </li>
      <li>
        <img src="images/portfolio-5.png" alt="Images of my favorite memories">
        <h2>Photo Gallery</h2>
        <p>This project shows pictures from a recent trip to the viewer and allows them to easily navigate through photos.</p>
      </li>
      <li>
        <img src="images/portfolio-6.png" alt="Digital Calculator">
        <h2>Calculator</h2>
        <p>Someone can enter in the numbers they want, and press the big blue button and get the result.</p>
      </li>
      <li>
        <img src="images/portfolio-6.png" alt="Digital Calculator">
        <h2>Skills</h2>
        <p>Someone can enter in the numbers they want, and press the big blue button and get the result.</p>
      </li>
       </ul>
      <div>
       <h2 id="contact">Contact</h2>
       <p>If you're interested in chatting or want more information on what i've been working on, I'd love to hear from you!</p>
       <p>Phone (111) 555-1234</p>
       <p>Email cooldevs@gmail.com</p>
      </div>
      <footer>
        <ul class="footer-nav">
          <li>
            <p>Student Name<p>
          <li>
            <p><a href="#">Back To Top</a></p>
          </li>
       </ul>
    </footer>
  </body>
</html>





*{
  box-sizing: border-box;
}

.portfolio-items li img {
  max-width: 100%;
}
.portfolio-items {
  list-style: none;
  text-align: center;
  background-color:white;
}
.footer-nav li {
  display: inline-block;
  margin-right: 40px;
  text-decoration: overline;
}
h2 {
  text-align: center;
  padding-top: 20px;
}
nav ul {
    list-style-type: none;
    text-align: center;
    color: red;

}
h1 {
  text-align: center;
  color: black;
}
p {
  text-align: center;
  padding-top: 5px;
  padding-bottom: 15px;
}
nav a {
  color: black;
  text-decoration: none;
  padding-top: 10px;
  padding-bottom: 10px;
}
@media (min-width: 768px) {
  .portfolio-items {
    width: 33%;
    display: inline-block;
  }
}
@media (min-width: 1024px) {

}
