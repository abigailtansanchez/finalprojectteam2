  
<!DOCTYPE html>
<html lang="en">

<head>
  <!-- Compiled and minified CSS -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css">

  <!--Import Google Icon Font-->
  <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">

  <link rel="stylesheet" href="style.css">

  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>FAQ</title>
</head>

<body>
<!-----------------------NavBar------------------------>
<div class="navbar-fixed">
  <nav>
    <div class="nav-wrapper">
      <a href="index.html" class="brand-logo"><img src="logo.png" width="Auto" height="45"></a>
      <a href="#" class="sidenav-trigger" data-target="mobile-nav">
        <i class="material-icons">menu</i></a>
      <ul class="right hide-on-med-and-down">
        <li><a href="index.html">HOME</a></li>
        <li><a href="#AboutUs">ABOUT US</a></li>
        <li><a class="dropdown-trigger" data-target="dropdown1" href="#">TUTORIALS<i class="material-icons right">arrow_drop_down</i></a></li>
        <li><a class="dropdown-trigger" data-target="dropdown2" href="#">PROGRAMS<i class="material-icons right">arrow_drop_down</i></a></li>
        <li><a href="#contact">INQUIRY</a></li>
        <li><a href="FAQ.html">FAQ</a></li>
        <li><a href="#ContactUs">CONTACT US</a></li>
      </ul>
    </div>
<!-- Dropdown -->
  <ul id="dropdown1" class="dropdown-content">
    <li><a href="https://www.youtube.com/watch?v=wvd04h7FCgo&list=PLB0ual5EM8q2S1JSGPyzylb4u_ZI_LMME" target="_blank">Javascript - Document Object Model (DOM)</a></li>
    <li><a href="https://www.youtube.com/watch?v=8n8hhPmVPQA&list=PLB0ual5EM8q1n2gMwqQG8HLOnDSlz1K_3" target="_blank">JavaScript Fundamentals</a></li>
    <li><a href="https://www.youtube.com/watch?v=4mTAE2-YyAw&list=PLB0ual5EM8q16U9ll-FDrzwFYkpN5BzbH" target="_blank">Materialize CSS</a></li>
    <li><a href="https://www.youtube.com/watch?v=77dNVZb0nQs&list=PLB0ual5EM8q1QDMgYbGsdUQIe58lL5pXg" target="_blank">Materialize Project</a></li>
  </ul>

  <ul id="dropdown2" class="dropdown-content">
    <li><a href="https://www.tesdaonlinecourses.com/tag/creative-web-design-level-iii/" target="_blank">Creative Web Design Level III</a></li>
    <li><a href="https://www.tesdaonlinecourses.com/tag/creative-web-design-level-iii/" target="_blank">Web Development Level III</a></li>
    <li><a href="https://www.e-tesda.gov.ph/" target="_blank">E-TESDA</a></li>
  </ul>
  </nav>
</div>

<div>
<ul class="sidenav" id="mobile-nav">
  <li><a href="index.html">HOME</a></li>
  <li><a href="#AboutUs">ABOUT US</a></li>
  <li><a class="dropdown-trigger" data-target="dropdown3" href="#">TUTORIALS<i class="material-icons right">arrow_drop_down</i></a></li>
  <li><a class="dropdown-trigger" data-target="dropdown4" href="#">PROGRAMS<i class="material-icons right">arrow_drop_down</i></a></li>
  <li><a href="#contact">INQUIRY</a></li>
  <li><a href="FAQ.html">FAQ</a></li>
  <li><a href="#ContactUs">CONTACT US</a></li>
</ul>

<!-- Dropdown -->
<ul id="dropdown3" class="dropdown-content">
  <li><a href="https://www.youtube.com/watch?v=8n8hhPmVPQA&list=PLB0ual5EM8q1n2gMwqQG8HLOnDSlz1K_3" target="_blank">JavaScript Fundamentals</a></li>
  <li><a href="https://www.youtube.com/watch?v=wvd04h7FCgo&list=PLB0ual5EM8q2S1JSGPyzylb4u_ZI_LMME" target="_blank">Javascript (DOM)</a></li>
  <li><a href="https://www.youtube.com/watch?v=4mTAE2-YyAw&list=PLB0ual5EM8q16U9ll-FDrzwFYkpN5BzbH" target="_blank">Materialize CSS</a></li>
  <li><a href="https://www.youtube.com/watch?v=77dNVZb0nQs&list=PLB0ual5EM8q1QDMgYbGsdUQIe58lL5pXg" target="_blank">Materialize Project</a></li>
</ul>

<ul id="dropdown4" class="dropdown-content">
      <li><a href="https://www.tesdaonlinecourses.com/tag/creative-web-design-level-iii/" target="_blank">Creative Web Design Level III</a></li>
      <li><a href="https://www.tesdaonlinecourses.com/tag/creative-web-design-level-iii/" target="_blank">Web Development Level III</a></li>
      <li><a href="https://www.e-tesda.gov.ph/" target="_blank">E-TESDA</a></li>
</ul>
</div>
<!-----------------------End of NavBar------------------------>


  <div class="section" id="faq">
<!--------------------Typebox-------------------->
    <div class="row">
      <div class="col s12">
        <div id="faq-search" class="card z-depth-0 faq-search-image center-align p-35">
          <div class="card-content">
            <h1 class="header center orange-text">Frequently Asked Questions</h1><br>
            <h5>Search our help center for quick answers</h5><br>
            <input placeholder=" Start typing your search..." id="search-input" type="text"
              class="search-box validate white search-circle search-shadow">
          </div>
        </div>
      </div>
    </div>
<!--------------------End of Typebox-------------------->
<!--------------------Links-------------------->
    <div class="faq row">
      <div class="col s12 m6 l3">
        <a class="black-text" href="https://www.tesda.gov.ph/Downloadables/TR%20-%20Web%20Development%20NC%20III.pdf" target="_blank">
          <div class="card z-depth-0 grey lighten-3 faq-card">
            <div class="card_content center-align">
              <i class="material-icons dp48 orange-text">book</i>
              <h6><b>Curriculum</b></h6>
              <p>Consectetur minim veniam</p>
            </div>
          </div>
        </a>
      </div>
      <div class="col s12 m6 l3">
        <a class="black-text" href="https://www.pixinvent.com/materialize-material-design-admin-template/laravel/demo-4/page-faq-detail">
          <div class="card z-depth-0 grey lighten-3 faq-card">
            <div class="card_content center-align">
              <i class="material-icons dp48 red-text">chat_bubble_outline</i>
              <h6><b>FAQ</b></h6>
              <p>Consectetur minim veniam</p>
            </div>
          </div>
        </a>
      </div>
      <div class="col s12 m6 l3">
        <a class="black-text" href="https://www.pixinvent.com/materialize-material-design-admin-template/laravel/demo-4/page-faq-detail">
          <div class="card z-depth-0 grey lighten-3 faq-card">
            <div class="card_content center-align">
              <i class="material-icons dp48 green-text">perm_identity</i>
              <h6><b>Community</b></h6>
              <p>Consectetur minim veniam</p>
            </div>
          </div>
        </a>
      </div>
      <div class="col s12 m6 l3">
        <a class="black-text" href="https://www.pixinvent.com/materialize-material-design-admin-template/laravel/demo-4/page-faq-detail">
          <div class="card z-depth-0 grey lighten-3 faq-card">
            <div class="card_content center-align">
              <i class="material-icons dp48 blue-text">people</i>
              <h6><b>Instructors</b></h6>
              <p>Consectetur minim veniam</p>
            </div>
          </div>
        </a>
      </div>
      <div class="col s12 m3 l3">
    </div>
  </div>
<!--------------------End of Links-------------------->

<!-----------------------Contact Us------------------------>
<section id="contact" class="section section-conatact scrollspy">
  <div class="container1">
    <div class="row">
      <div class="col s12 m6">
       <div class="card-panel grey darken-3 white-text center">
        <i class="material-icons">email</i>
        <h5>Feel free to Inquire</h5>
        <p>Check for our new online program and ask how for regular email updates.</p>
       </div>
       <div>
        <ul class="collection with-header">
          <li class="collection-header"><h4>Contact Information</h4></li>
          <li class="collection-item"><b>Company Name:</b> <a class="black-text" href="#">Dream Plug Inc.</a></li>
          <li class="collection-item"><b>Email:</b> <a class="black-text" href="https://accounts.google.com/ServiceLogin/identifier?service=mail&amp;passive=true&amp;rm=false&amp;continue=https%3A%2F%2Fmail.google.com%2Fmail%2F&amp;ss=1&amp;scc=1&amp;ltmpl=default&amp;ltmplcache=2&amp;emr=1&amp;osid=1&amp;flowName=GlifWebSignIn&amp;flowEntry=ServiceLogin">DreamPlug02@gmail.com</a></li> 
        </ul>
       </div> 
      </div>
      <div class="col s12 m6">
        <div class="card-panel grey lighten-3 center">
          <h5>Get a Personal Quotation</h5>
          <div class="input-field">
            <input type="text" placeholder="Name">
          </div>
          <div class="col s12 m6 input-field">
            <input type="text" placeholder="Email">
          </div>
          <div class="col s12 m6 input-field">
            <input type="text" placeholder="Phone">
          </div>
          <div class="input-field">
            <ul>What interest you?</ul>
            <p>
              <label class="col s6 m3 input-field offset-l2">
                <input type="checkbox" id="check1" class="filled-in">
                <span>MaterializeCSS</span>
              </label>
              <label class="col s6 m3 input-field">
                <input type="checkbox" id="check2" class="filled-in">
                <span>JavaScript</span>
              </label>
              <label class="col s12 m3 input-field">
                <input type="checkbox" id="check3" class="filled-in">
                <span>Figma UI Design</span>
              </label>
          </div>
          <div class="input-field">
            <textarea class="materilaize-textarea" placeholder="Enter Message"></textarea>
          </div>
          <input type="submit" value="Submit" class="btn-large waves-effect waves-light orange ">
        </div>
        </div>
      </div>
    </div>
</section>
<!-----------------------End of Contact Us------------------------>

<!-----------------------Footer------------------------>
  <footer class="page-footer grey darken-3">
    <div class="container">
      <div class="row">
        <div class="col s12 l6" id="AboutUs">
          <h5>About us</h5>
          <p class="amber-text text-darken-4">We are students of Optimum Creative Web Design. This will
            served
            as our project. Hope you find this website usefull in kearning coding.</p>
        </div>
        <div class="col s12 l4 offset-l2" id="ContactUs">
          <h5>Contact Us</h5>
          <ul>
            <li><a href="https://www.facebook.com/" target="_blank"
                class="amber-text text-darken-4">Facebook
                <i class="material-icons left">facebook</i>
              </a></li>
          </ul>
          <ul>
            <li><a href="https://www.youtube.com/channel/UCJ0gf-cKiXFAJoA4nK9Hq1g" target="_blank"
                class="amber-text text-darken-4">Youtube
                <i class="material-icons left">subscriptions</i>
              </a></li>
          </ul>
          <ul>
            <li><a href="https://www.instagram.com/" target="_blank"
                class="amber-text text-darken-4">Instagram
                <i class="material-icons left">local_see</i>
              </a></li>
        </div>
      </div>
    </div>
    <div class="footer-copyright grey darken-4">
      <div class="container center-align">&copy; 2021 Dream Plug</div>
    </div>
  </footer>
<!-----------------------End of Footer------------------------>

<!-- Compiled and minified JavaScript -->
<script src=" https://https://code.jquery.com/jquery-2.1.1.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script>

<!--This codes are for Initialization-->
<script type="text/javascript">

  $(document).ready(function () {
    $('.parallax').parallax();
  });

  $(document).ready(function () {
    $('.sidenav').sidenav();
  });

// Navbar
const elemsDropdown = document.querySelectorAll(".dropdown-trigger");
const instancesDropdown = M.Dropdown.init(elemsDropdown, {
    coverTrigger: false
});

</script>
        
</body>

</html>
