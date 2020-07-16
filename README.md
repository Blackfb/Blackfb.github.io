

<!DOCTYPE html>
<html lang="en-us">
<head>
  <meta charset="UTF-8">
  <title>Activity 1: Basic HTML Bio</title>
</head>
<body>
  <!-- header start -->
  <div id="header" class="section">
    <article>
      <a target="_blank" href="Desktop/ISLER/GUCLER/UcanSoft/Backround.jpeg">
      <img src="IMG_4398.jpeg" alt="The Future">
      </a>
    
  </article>
      <h1>Resul Cobanoglu</h1>
  </div>
  <!-- header end -->
  
  <!-- About Me section start -->
  <div class="section">
      <h1><span>About Me</span></h1>
      <p>
          Hey! I'm <strong>Resul</strong>. Coding has changed my world. It's not just about apps. Learning to code gave me <i>problem-solving skills</i> and a way to communicate with others on a technical level. I can also develop websites and use my coding skills to get a better job. And I learned it all at <strong>Rutgers Data Science Bootcamp</strong> 
      </p>
      <p class="quote">"Declare variables, not war"</p>
  </div>
  <!-- About Me section end -->

          <!-- My Skills section start -->
          <div class="section">
            <h1><span>My Skills</span></h1>
            <ul>
                <li>HTML <br />
                    <progress min="0" max="100" value="80"></progress>
                </li>
                <li>JavaScript <br />
                    <progress min="0" max="100" value="70"></progress>
                </li>
                <li>Python <br />
                    <progress min="0" max="100" value="90"></progress>
                </li>
            </ul>
        </div>
        <!-- My Skills section end -->

        <!-- Form section start -->
        <div class="section">
          <h1><span>Contact Me</span></h1>
          
          <svg class="face" height="100" width="100">
              <circle cx="50" cy="50" r="50" fill="#FDD835"/>
              <circle cx="30" cy="30" r="10" fill="#FFFFFF"/>
              <circle cx="70" cy="30" r="10" fill="#FFFFFF"/>
              <circle cx="30" cy="30" r="5" fill="#000000"/>
              <circle cx="70" cy="30" r="5" fill="#000000"/>
              <path d="M 30 70 q 20 20 40 0" stroke="#FFFFFF" stroke-width="5" fill="none" />
          </svg>
               
          <form>
              <input name="name" placeholder="Name" type="text" required /><br/>
              <input name="email" placeholder="Email" type="email" required /><br/>
              <textarea name="message" placeholder="Message" required ></textarea>
              <input type="submit" value="SEND" class="submit" />
          </form>
      </div>
      <!-- Form section end -->

          <!-- Contacts section start -->
          <div class="section" id="contacts">
            <h1><span>Follow Me</span></h1>
            <div>
                <!-- <a href="https:" target="_blank"> -->
                
                </a>
                <a href="#">
                    <img alt="Linkedln" src="https://www.linkedin.com/in/resul-cobanoglu-00354b197/"/>
                </a>
                <a href="#">
                    <img alt="Twitter" src="https://" />
                </a>
            </div>
        </div>
        <!-- Contacts section end -->
        
        <div class="copyright">
            &copy; 2017 My Blog. All rights reserved.
        </div>
</body>

</html>
