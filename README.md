<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="prot.js" defer></script>
    <link rel="stylesheet" href="prot.css">
    <link href="https://cdn.jsdelivr.net/npm/remixicon@3.5.0/fonts/remixicon.css" rel="stylesheet">
    <script src="https://kit.fontawesome.com/f45df03eff.js" crossorigin="anonymous"></script>
  
</head>
<body>
    <div id="header">
        <div class="container">
            <nav>
               <h1 class="u"><span>U</span>tkarsh.</h1>
              
                <ul id="sidemenu">
                   <li><a href="#header">Home</a></li>
                   <li><a href="#about">About</a></li>
                   <li><a href="#services">Courses</a></li>
                   <li><a href="#protfolio">Work</a></li>
                   <li><a href="#contact">Contact</a></li>
                   <i class="fa fa-times" onclick="closemenu()"></i>
                </ul>
                <i class="fa fa-bars" onclick="openmenu()"></i>
            </nav>
            <div class="header-text">
                <p class="pink">FullStack Devloper</p>
                <h1 class="orange">Hi,I a'm <span> Utkarsh</span> </h1>
                <h1 class="kkk">From India</h1>
            </div>
        </div>
    </div>
    <div id="about">
        <div class="container">
            <div class="row">
                <div class="about-col-1">
                    <img src="user.png">
                    </div>
                    <div class="about-col-2">
                
                        <h1 class="sub-titel">About Me</h1>
                        <p>Pursuing Gradute Degree With A Passion For Aspiring Link Between My Theoretical I Knownledge And Practical World Seeking An opportunity To Put My World.Seeking On Opportunity To Put My Creative Skill To Work.Passionate About Work For Technology .</p>

                        <div class="tab-titles"> 
                            <div class="tab-links active-link" onclick="opentab('Skills')">Skills</div>
                            <!-- <div class="tab-links"onclick="opentab('Experience')">Experience</div> -->
                            <div class="tab-links"onclick="opentab('Education')">Education</div>
</div>
                            <div class="tab-contents active-tab" id="Skills">
                                <ul>
                                    <li><span>Forntend</span><br>HTML,CSS,JAVASCRIPT</li>
                                    <li><span>Backend</span><br>NODE JS,Python</li>
                                </ul>
                            </div>
                            <div class="tab-contents" id="Experience">
                                <ul>
                                    <li><span>2021 -current</span><br>UI/UX Design Traning at ET Institute</li>
                                    <li><span>2019 -2021</span><br>Team lead at StarApp LLC.</li>
                                    <li><span>2017 -2019</span><br>UI/UX Design Executive at Coin Digital Ltd.</li>
                                    <li><span>2016 - 2017</span><br>Intership at ekart eCommerce.</li>
                                </ul>
                            </div>
                            <div class="tab-contents" id="Education">
                                <ul>
                                    <li><span>College Name </span><br>Sitabai Shende College Nashik University Maharashtra</li>
                                    <li><span>BCA</span><br>Bachlore Of Computer Application.
                                    </li>
                                    <li><span>PassOut Years</span><br>july 2025</li>
                                    <li><span>12th Passout</span><br>S.T High School College Pulgaon,Maharashtra India HSC 12th <br/>Percentage=42.00%</li>
                               
                                </ul>
                            </div>
                        </div>
                </div>


            </div>
        </div>
    </div>

    <!-- ............services...........  -->

    <div id="services">
        <div class="container">
            <h1 class="sub-titel">My Complete Courses</h1>
            <div class="services-list">
                <div>
                    <i class="fa-brands fa-html5"></i>
                    <h2>HTML</h2>
                    <p>The HyperText Markup Language or HTML is the standard markup language for documents designed to be displayed in a web. <br> It defines the content and structure of web content. It is often assisted by technologies  such as Cascading Style Sheets (CSS) and scripting languages such as JavaScript.
                    </p>
                    <a href="https://www.bing.com/search?q=htnl+made+for&form=ANNTH1&refig=0a58b4e7259e4642a9e776109b500be8&pc=U531">Learn more</a>
                </div>
                <div>
                    <i class="fa-brands fa-css3-alt"></i>
                    <h2>CSS</h2>
                    <p>CSS is one of the cornerstones of the web. If HTML is the bones of a website, CSS is what makes the site look better than a skeleton. Without CSS, web pages would be dull and boring.</p>
                    <a href="https://www.bing.com/search?q=css+made+for&qs=n&form=QBRE&sp=-1&lq=0&pq=css+made+for&sc=9-12&sk=&cvid=001E6CB63DEB46F582A4DE29D3BCFB16&ghsh=0&ghacc=0&ghpl=">Learn more</a>
                </div>
                <div>
                    <i class="fa-brands fa-js"></i>
                    <h2>Js</h2>
                    <p>JavaScript , often abbreviated as JS, is a programming language and core technology of the World Wide Web, alongside HTML and CSS. <br> As of 2024 , 98.9% of websites use JavaScript on the client side for webpage behavior, often incorporating third-party libraries.</p>
                    <a href="https://www.bing.com/search?q=js++made+for&qs=n&form=QBRE&sp=-1&ghc=1&lq=0&pq=js++made+for&sc=11-12&sk=&cvid=D70BC99830104E22A6BEDD3D55B00654&ghsh=0&ghacc=0&ghpl=">Learn more</a>
                </div>
                <div>
                    <i class="fa-brands fa-node-js"></i>
                    <h2>NODE JS</h2>
                    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the</p>
                    <a href="#">Learn more</a>
                </div>
                <div>
                    <i class="fa-brands fa-python"></i>
                    <h2>Python</h2>
                    <p>Python is a high-level, general-purpose programming language. Its design philosophy emphasizes code readability with the use of significant indentation. Python is dynamically typed and garbage-collected.</p>
                    <a href="https://www.bing.com/search?pglt=41&q=python+made+for&cvid=26a661f2a3234ad0981e807f6def197f&gs_lcrp=EgZjaHJvbWUyBggAEEUYOTIGCAEQABhAMgYIAhAAGEAyBggDEAAYQDIGCAQQABhAMgYIBRAAGEAyBggGEAAYQDIGCAcQABhAMgYICBAAGEDSAQg0NjI0ajBqMagCALACAA&FORM=ANNTA1&PC=U531">Learn more</a>
                </div>
            </div>
        </div>
    </div>
    <!-- ..........protfoilio........  -->
       <div id="protfolio">
        <div class="container">
            <h1 class="sub-titel">My Work</h1>
            <div class="work-list">
                <div class="work">
                    <img src="work-1.png">
                    <div class="layer">
                        <h1>Create Website</h1>
                        <a href="http://127.0.0.1:5502/protfolio.html#protfolio"><i class="fas fa-external-link-alt"></i></a>
                    </div>
                </div>
                <div class="work">
                    <img src="work-2.png">
                    <div class="layer">
                        <h1>Create Server</h1>
                        <p></p>
                        <a href="#"><i class="fas fa-external-link-alt"></i></a>
                    </div>
                </div>
                <div class="work">
                    <img src="work-3.png">
                    <div class="layer">
                        <h1>Create Api</h1>
                        <p></p>
                        <a href="#"><i class="fas fa-external-link-alt"></i></a>
                    </div>
                </div>
            </div>
            <a href="#" class="btn">See More</a>
        </div>
       </div>
       <div id="contact">
        <div class="container">
            <div class="row">
                <div class="contact-left">
                    <h1 class="sub-title">Contact Me</h1>
                    <p><i class="fas fa-paper-plane"></i> utkarshchoudhari597@gmail.com</p>
                    <p><i class="fas fa-phone-square-alt"></i> 9503733381</p>
                </div>
                <!-- <a href="my-cv.pdf" download class="btn  btn2">Downlode CV</a> -->
                <div class="contact-right">
                    <form name="submit-to-google-sheet">
                        <input type="text" name="Name" placeholder="Your name" required>
                        <input type="email" name="Email" placeholder="Your Email" required>
                        <input type="text" name="lastname" placeholder="your lastname">
                        <input id="phone" type="tel"  pattern="[0-9]{10}">
                        <textarea name="Meassage"  rows="6" placeholder="Your message"></textarea>

                        <button type="submit" class="btn btn2">Submit</button>
                    </form>
                    <span id="msg">Hello</span>
                </div>
            </div>
        </div>
             <div class="copyright">
                <p>Copyright @ utkarsh. <i class="fa fa-heart"></i></p>

             </div>
       </div>
    

    <script>
        var tablinks=document.getElementsByClassName("tab-links");
           var tabcontents=document.getElementsByClassName("tab-contents");
   
           function opentab(tabname){
               for(tablink of tablinks){
                   tablink.classList.remove("active-link")
               }
               for(tabcontent of tabcontents){
                   tabcontent.classList.remove("active-tab");
               }
               event.currentTarget.classList.add("active-link")
               document.getElementById(tabname).classList.add("active-tab")
           }

       </script>

       <script>
        var sidemenu=document.getElementById("sidemenu")

        function openmenu(){
            sidemenu.style.right="0"
        }
       
        function closemenu(){
            sidemenu.style.right="-200px"
        }

       </script>

<script>
    const scriptURL = 'https://docs.google.com/spreadsheets/d/1gtkSJ14P9Ux_usdZr7CuYWzxSyHGcHzVSTLEd9xEI8U/edit#gid=2001452332'
    const form = document.forms['submit-to-google-sheet']
  
    form.addEventListener('submit', e => {
      e.preventDefault()
      fetch(scriptURL, { method: 'POST', body: new FormData(form)})
        .then(response => console.log('Success!', response))
        .catch(error => console.error('Error!', error.message))
    })
  </script>
    
</body>
</html>
