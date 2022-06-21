Header Section
The header section can be found within the <nav> tag and simply contains an unordered list of anchors to different sections of the page.

<nav>
            <h1 style="color: #8e43e7;font-size: 25px;">Aarish</h1>
            <ul>
                <li><a href="#">HOME</a></li>
                <li><a href="#">ABOUT</a></li>
                <li><a href="#">SKILLS</a></li>
                <li><a href="#">PROJECT</a></li>
                <li><a href="#">CONTACT</a></li>
            </ul>
</nav>
  
  
Main section
The header main section can be found within the <div> tag and and using .detel class to style the section. 

<div class="detel">
            <h1>I,M Aarish <span>Ali</span></h1>
<!--main section content-->
</div>
  
About Section
The about section contains a quick about section where two section is there in left section qucik about text is there and right section text with icon is there.
 <div class="about_main">
   <div id="about_big">
     <div id="about_card" class="about_card">
       <!--Left section content-->
     </div>
   </div>
   <!--Right side about content-->
   <div class="about_column"></div>
   <div class="about_column"></div>
   <div class="about_column"></div>
  </div>

  
 Education Section
The education section creates a vertical timeline with my education history. By default, it shows date, degree, and some additional details.
For example:
  <ul class="line_ul">
          <li>
            <div>
              <time>Aug 2021 Present</time>
              <p>Master of computer application</p>
            </div>
          </li>
  </ul>
  To add style education section, simply .line_ul class is given.

  
Experience Section
  The experience section creates a horizontal timeline with all my relevant experience.

  
Footer Section
  
The footer section contain name as well as an unordered list of all of your social or coding related profiles. By default it contains Github, Twitter, and Linkedin. I usw Font Awesome icon associated with the social profile.
