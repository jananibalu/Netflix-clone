#HTML code 
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Netflix Websit Clone</title>
  <link rel="stylesheet" href="net.css">
  <style>
    
  </style>
</head>
<body>
<div class="header">
  <nav>
    <img src="logo1.PNG" class="logo">
    <div>
      <button class="language-btn">English<img src="down-icon3.png"></button>
      <button>Sign in</button>
      
    </div>
  </nav>
  <div class="header-content">
    <h1>Unlimited movies, TV shows and more.</h1>
    <h3>Watch naywhere and cancal anytime.</h3>
    <p>Ready to whatch? Enter your email to create or restart your membership.</p>
    <fome class="email-signup">
      <input type="email" placeholder="Email address" required>
      <button type="submit">Get started</button>
    </fome>
  </div>
</div>
<div class="features">
  <div class="row">
    <div class="text-col">
      <h2>Enjoy on your TV</h2>
      <p>Watch on smart TVs, playstation,Xbox,Chromecast,Apple TV,Blu-ray players and More.</p>
    </div>
    <div class="img-col">
     <img src="feature-1.JPEG">
    </div>
  </div>
  <div class="row">
    <div class="img-col">
      <img src="feature-2.JPEG">
    </div>
    <div class="text-col">
      <h2>Download your shows to watch offline.</h2>
      <p>Save your favourites easily and always have something to watch.</p>
    </div>
    
  </div>
  <div class="row">
    <div class="text-col">
      <h2>Watch everywhere.</h2>
      <p>Stream unlimited movies and TV shows on your phone, tablet, laptop, and TV.</p>
    </div>
    <div class="img-col">
      <img src="feature-3.JPEG">
    </div>
  </div>
  <div class="row">
    <div class="img-col">
      <img src="feature-4.JPEG">
    </div>
    <div class="text-col">
      <h2>Create profiles for children.</h2>
      <p>Send children on adventures with their favourite characters in a space made just for them—free with your membership.</p>
    </div>
    
  </div>
</div>
<div class="faq">
  <h2>Frequently Asked Questions</h2>
  <ul class="accordion">
    <li>
      <input type="radio" name="accordion" id="first">
      <label for="first">what is Netflix?</label>
      <div class="content">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
        quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
        consequat.</p>
      </div>
    </li>

    <li>
      <input type="radio" name="accordion" id="second">
      <label for="second">How much does Netflix cost?</label>
      <div class="content">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
        quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
        consequat.</p>
      </div>
    </li>

    <li>
      <input type="radio" name="accordion" id="third">
      <label for="third">What can I watch?</label>
      <div class="content">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
        quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
        consequat.</p>
      </div>
    </li>

    <li>
      <input type="radio" name="accordion" id="fourth">
      <label for="fourth">How do I cancel?</label>
      <div class="content">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
        quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
        consequat.</p>
      </div>
    </li>

<li>
      <input type="radio" name="accordion" id="fifth">
      <label for="fifth">What can I watch on Netflix?</label>
      <div class="content">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
        quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
        consequat.</p>
      </div>
    </li>

    <li>
      <input type="radio" name="accordion" id="sixth">
      <label for="sixth">Is Netflix good for kids?</label>
      <div class="content">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
        quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
        consequat.</p>
      </div>
    </li>
  </ul>
  <small>Ready to whatch? enter your email to create or restart your membership.</small>
  <fome class="email-signup">
      <input type="email" placeholder="Email address" required>
      <button type="submit">Get started</button>
    </fome>
</div>
<div class="footer">
  <h2>Questions? Call 000-0000-000</h2>
  <div class="row">
    <div class="col">
      <a href="#">FAQ</a>
      <a href="#">Investor</a>
      <a href="#">Peivacy</a>
      <a href="#">Speed Test</a>
    </div>
    <div class="col">
      <a href="#">Help Content</a>
      <a href="#">Jobs</a>
      <a href="#">Cookies Preferences</a>
      <a href="#">Legal Notices</a>
    </div>
    <div class="col">
      <a href="#">Account</a>
      <a href="#">Ways to watch</a>
      <a href="#">Corpoate Information</a>
      <a href="#">Only on Netflix</a>
    </div>
    <div class="col">
      <a href="#">Media Center</a>
      <a href="#">Term of use</a>
      <a href="#">Contact us</a>
    </div>
  </div>
  <button class="language-btn">English<img src="down-icon3.png"></button>
  <p class="copyright-txt">Netflix India</p>
</div>
</body>
</html>





#CSS code


*{
    margin: 0;
    padding: 0;
    font-family: 'poppins',sans-serif;
    box-sizing: border-box;
    }
    
    body{
      background: #000;
      color: #fff;
    }
    .header{
    width: 100%;
    height: 100vh;
    background-image: linear-gradient(rgba(0,0,0,0.7),rgba(0,0,0,0.7)), url(header-image.JPEG);
    background-size: cover;
    background-position: center;
    padding: 10px 8px;
    position: relative;
    }
    nav{
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 10px 0px;
    
    }
    .logo{
       
    width: 150px;
    cursor: pointer;
    mix-blend-mode: color-white;
    }
    
    nav button{
      border: 0;
      outline: 0;
      background: #db0001;
      color: #fff;
      padding: 7px 20px;
      font-size: 12px;
      border-radius: 4px;
      margin-left: 10px;
      cursor: pointer;
    }
    .language-btn{
      display: inline-flex;
      align-items: center;
      background: transparent;
      border: 1px solid #fff;
      padding: 7px 10px;
    
    }
    .language-btn img {
      background-color: transparent;
      width: 10px;
      margin-left: 10px;
     
    }
    .header-content{
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%,-50%);
      text-align: center;
      margin-top: 100px;
    }
    .header-content h1{
      font-size: 60px;
      line-height: 70px;
      font-weight: 600;
      max-width: 650px;
    }
    .header-content h3{
      font-weight: 400;
      margin-bottom: 20px;
    }
    .email-signup{
      background: #fff;
      border-radius: 4px;
      display: flex;
      align-items: center;
      margin-top: 30px;
      overflow: hidden;
    }
    .email-signup input{
      flex: 1;
      border: 0;
      outline: 0;
      margin-left: 20px;
      font-size: 25px;
    }
    .email-signup button{
      background: #db0001;
      border: 0;
      outline: 0;
      color: #fff;
      font-size: 20px;
      cursor: pointer;
      padding: 15px 30px;
    }
    
    /*---------------features------------*/
    
    .features{
      padding: 50px 12%;
      font-size: 22px;
    }
    .row{
      display: flex;
      width: 100%;
      align-items: center;
      flex-wrap: wrap;
      padding: 50px 0;
    }
    .text-col{
      flex-basis: 50%;
      margin-bottom: 20px;
    }
    .img-col{
      flex-basis: 50%;
      margin-bottom: 20px;
    }
    .img-col img{
      display: block;
      width: 90%;
      margin: auto;
    }
    .features h2{
      font-size: 50px;
      font-weight: 600;
      margin-bottom: 20px;
    }
    /*------------------FAQ-------------*/
    .faq{
      padding: 10px 12px;
      text-align: center;
      font-size: 18px;
    }
    .faq h2{
      font-weight: 500;
      font-size: 40px;
    }
    .accordion{
      margin: 60px auto;
      width: 100%;
      max-width: 750px;
    }
    .accordion li{
      list-style: none;
      width: 100%;
      padding: 5px;
    }
    .accordion li label{
      display: flex;
      align-items: center;
      padding: 20px;
      font-size: 18px;
      font-weight: 500%;
      background: #303030;
      margin-bottom: 2px;
      cursor: pointer;
      position: relative;
    }
    label::after{
      content: '+';
      font-size: 34px;
      position: absolute;
      right: 20px;
      transition: transform 0.5s;
    }
    input[type="radio"]{
      display: none;
    }
    .accordion .content{
      background: #303030;
      text-align: left;
      padding: 0 20px;
      max-height: 0;
      overflow: hidden;
      transition: max-height 0.5s, padding 0.5s;
    }
    .accordion input[type="radio"]:checked + label + .content{
      max-height: 600px;
      padding: 30px 20px;
    }
    .accordion input[type="radio"]:checked + label::after{
      transform: rotate(135deg);
    }
    .faq .email-signup{
      max-width: 100;
      margin: 20px auto 60px;
      flex: 1;
      border: 0;
      outline: 0;
      margin-left: 200px;
      margin-right: 200px;
      display: transparent;
    }
    .faq small{
      font-size: 23px;
    }
   /* ----------fooder---------*/
   .footer{
    padding: 50px 15% 10px;
    border-top: 6px solid #333;
    color: #777;
    }
    footer h2{
      font-size:  18px;
      font-weight: 400;
      margin-bottom: 30px;
    }
    .footer .col{
      flex-basis: 25%;
      flex-grow: 1;
      margin-bottom: 20px;
    }
    .footer .col a{
     display: block;
     text-decoration: none;
     color: #777;
    font-size: 14px;
     margin-bottom: 10px;
    }
    .footer .row{
      align-items: first-start;
      padding: 10px 0;

    }
    .footer .language-btn{
      color: #fff;
      padding: 10px 20px;
    border-radius: 3px;
    background-color: transparent;
    .
    
      }
      .copyright-txt{
        font-size: 14px;
        margin-top: 20px;
        margin-bottom: 10px;
      }

      @media only screen and(max-width: 600px){
        .logo{
          width: 100px;
        }
        nav button{
          padding: 5px 10px;

        }
        nav .language-btn{
          padding: 4px 8px;
        }
        .header-content{
          position: unset;
          transform: none;
          padding-top: 150px;
       
       }
       .header-content h1{
        font-size: 30px;
       }
       .email-signup button{
        font-size: 12px;
        padding: 10px 15px;

       }
      }


 
