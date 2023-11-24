# DCIT_205_IA
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="with=device-width, initial-scale=1.0">
    <title> DEPARTMENT OF COMPTER SCIENCE  </title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@100;300;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
  </head>
    <body>
    <section class="header">
      <nav>
        <a href="index.html"><img src="images/comScience_logo.png"></a>
        <div class="nav-links" id="navLinks">
          <i class="fa fa-times" onclick="hideMenu()"></i>
          <ul>
            <li><a href="">HOME</a></li>
            <li><a href="">STUDY WITH US</a></li>
            <li><a href="">COURSE FINDER</a></li>
            <li><a href="">SCHOOLS</a></li>
            <li><a href="">RESEARCH</a></li>
            <li><a href="">ALUMNI AND FRIENDS</a></li>
            <li><a href="">NEWS</a></li>
            <li><a href="">EVENTS</a></li>
            <li><a href="">ABOUT</a></li>
          </ul>
        </div>
        <i class="fa fa-bars" onclick="showMenu()"></i>
      </nav>

      <div class="text-box">
        <h1> GATEWAY TO WORLD CLASS COMPUTER SCIENCE EDUCATION</h1>
        <p>dont know what<br> to type yet </p>
        <a href=""class="hero-btn">still blank  </a>
      </div>
    </section>
<!-----course---->
<section class="course">
  <h1> Short Courses we offer</h1>
  <p>Our eight week intensive certificate course is open to senior high school graduates,<br>tertiary students, school graduates, workers and the general public.
  </p>

  <div class="row">
      <div class=" course-col">
        <h3>Introduction To Web Programming</h3>
        <p>Understand the  fundamentals of technologies and create web-based applications with latest technologies.</p>
      </div>
        <div class=" course-col">
          <h3>Computer Network fundamentals[CCNA].</h3>
          <p> We provide quality training for students to become a Cisco Certified Network Associate.</p>
        </div>
         <div class=" course-col">
        <h3>Mobile Application Development</h3>
        <p>We provide world class technologies for Mobile Application Development using the mobile-first worklight by IBM.</p>
         </div>
         <div class=" course-col">
          <h3>Introduction To Security and Ethical Hacking </h3>
          <p>Learn the various technigues used to secure a computer system from attacks through hacking.</p>
        </div>   
  </div>
</section>

<!--------- courses2 -------->
<section class="campus">
  <h1> Short Courses we Offer </h1>
  <p>Our eight week intensive certificate course is open to senior high school graduates,<br>tertiary students, school graduates, workers and the general public.
  </p>


</section>

<!--------JavaScript for Toggle Menu------->
      <script>
      var navLinks = document.getElementById("navLinks");
      function showMenu(){
        navLinks.style.right = "0";
      }
      function hideMenu(){
        navLinks.style.right =" -200px";
      }
    </script>
  </body>
</html>
