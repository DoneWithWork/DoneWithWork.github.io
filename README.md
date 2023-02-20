<!DOCTYPE html>

<html lang="en" >
<head>
    <meta charset="utf-8" />
    <link rel="icon" href="smile.png" />
    <title>DoneWithWork</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="styles.css" />

</head>
<body>
    <button onclick="topFunction()" id="myBtn" title="Go to top">&uarr;</button>
    <script>// Get the button:
        let mybutton = document.getElementById("myBtn");

        // When the user scrolls down 20px from the top of the document, show the button
        window.onscroll = function () { scrollFunction() };

        function scrollFunction() {
            if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
                mybutton.style.display = "block";
            } else {
                mybutton.style.display = "none";
            }
        }

        // When the user clicks on the button, scroll to the top of the document
        function topFunction() {
            document.body.scrollTop = 0; // For Safari
            document.documentElement.scrollTop = 0; // For Chrome, Firefox, IE and Opera

        }
       
    </script>

    <div class="header">
     
        <div class="container">

            <nav>

                <img src="logo.png" alt="Logo IMG" class="logo" />

                <ul>

                    <li><a href="#home">Home</a></li>
                    <li><a href="#freelance">Freelance</a></li>
                    <li><a href="#youtube">YouTube</a></li>
                    <li><a href="#contacts">Contacts</a></li>
                </ul>
            </nav>
          
        </div>
    </div>



    <section id="home" class="home">
        <h1>Who am I?</h1>
        <img src="Smile.png" class="smile" />
        <p>Hi. I'm DoneWithWork. A student who enjoys programming and anything tech</p>
        <p>Part time Freelancer, YouTuber and Video game creator</p>
        <p>Always Happy :)</p>

    </section>
    <section id="freelance" class="freelance">
        <h2>Freelance</h2>
        <div class="container2">

            <div class="box1">
                <p>Programming knowledge</p>

                <div class="graph">
                    <div class="bar">
                        <span style="width: 60%;">Python</span>
                        <div class="percentage">60%</div>
                    </div>
                    <div class="bar">
                        <span style="width: 20%;">Unity C#</span>
                        <div class="percentage">20%</div>
                    </div>
                    <div class="bar">
                        <span style="width: 10%;">HTML</span>
                        <div class="percentage">10%</div>
                    </div>
                    <div class="bar">
                        <span style="width: 10%;">Java</span>
                        <div class="percentage">10%</div>
                    </div>
                    <div class="x-axis"></div>
                    <div class="y-axis"></div>
                </div>
                <div class="knowledge">
                    <p>My expertise: </p>
                    <ul>
                        <li>Development in Python</li>
                        <li>Game Development Unity 2D</li>
                        <li>Content Creator</li>
                        <li>Blockchain, just a little :)</li>
                    </ul>


                </div>
            </div>
            <div class="box2">
                <!-- Put this code anywhere in the body of your page where you want the badge to show up. -->
                <p>Fiverr</p>
                <div itemscope itemtype='http://schema.org/Person' class='fiverr-seller-widget' style='display: inline-block; '>
                    <a itemprop='url' href=https://www.fiverr.com/donewithwork rel="nofollow" target="_blank" style='display: inline-block; border: 5px solid black;'>
                        <div class='fiverr-seller-content' id='fiverr-seller-widget-content-bbbdb2b7-0dc2-4285-a0f9-ba9f729c7740' itemprop='contentURL' style='display: none;'></div>
                        <div id='fiverr-widget-seller-data' style='display: none; '>
                            <div itemprop='name'>donewithwork</div>
                            <div itemscope itemtype='http://schema.org/Organization'><span itemprop='name'>Fiverr</span></div>
                            <div itemprop='jobtitle'>Seller</div>
                            <div itemprop='description'>
                                I make 2D video games in Unity.
                                Basic to intermediate games with basic art, music and sound effects.
                                I have a Youtube channel: DoneWithWork
                                Check it out :)
                                ALL PRICES ARE NEGOTIABLE.
                            </div>
                        </div>
                    </a>
                </div>

                <script id='fiverr-seller-widget-script-bbbdb2b7-0dc2-4285-a0f9-ba9f729c7740' src='https://widgets.fiverr.com/api/v1/seller/donewithwork?widget_id=bbbdb2b7-0dc2-4285-a0f9-ba9f729c7740' data-config='{"category_name":"Programming \u0026 Tech"}' async='true' defer='true'></script>

            </div>
        </div>
    </section>
    <section id="youtube" class="youtube">
        <h3>YouTube</h3>
        <div class="row">
            <div class="video">
                <p>Mad Lib Game</p>
                <iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/glIqLSyf0sI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            </div>
            <div class="video">
                <p>Dangerous Waters</p>
                <iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/-XaMisbkjZY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            </div>
            <div class="video">
                <p>Tic Tac Toe Python</p>
                <iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/WBAnEGyBuaQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            </div>
        </div>
        <div class="row">
            <div class="video">
                <p>Console Game Python Part 0</p>
                <iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/mkkVrWzUhtI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            </div>
            <div class="video">
                <p>Console Game Python Part 1</p>
                <iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/eaoIK-WQFqw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            </div>
            <div class="video">
                <p>Console Game Python Part 2</p>
                <iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/RuRRpjkQdsg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            </div>
        </div>



    </section>
    <section id="contacts" class="contacts">
        <div class="title">
            <h4>Contacts</h4>
        </div>
        <div class="contact-items">
            <div class="contact-item">
                <a href="https://www.youtube.com/channel/UCYa5xuMVV0J0LcGoFTgiXBw" target="_blank"><img src="youtube.png" alt="youtube"></a>
                <p>YouTube</p>
            </div>

            <div class="contact-item">
                <a href="https://www.linkedin.com/in/DoneWithWork" target="_blank"><img src="linkedin.png" alt="Linkedin"></a>
                <p>Linkedin</p>
            </div>

            <div class="contact-item">
                <a href="https://twitter.com/DoneWithWork" target="_blank"><img src="twitter.png" alt="twitter"></a>
                <p>Twitter</p>
            </div>

            <div class="contact-item">
                <a href="https://github.com/DoneWithWork" target="_blank"><img src="github.png" alt="GitHub"></a>
                <p>GitHub</p>
            </div>

            <div class="contact-item">
                <a href="https://www.instagram.com/donewithwork_1/" target="_blank"><img src="instagram.png" alt="Linkedin"></a>
                <p>Instagram</p>
            </div>

        </div>

    </section>
    <section class="credits">
        <h6>Credits</h6>
        <a href="https://www.flaticon.com/free-icons/youtube" title="youtube icons">Youtube icons created by Md Tanvirul Haque - Flaticon</a>
        <a href="https://www.flaticon.com/free-icons/twitter-logo" title="twitter logo icons">Twitter logo icons created by Md Tanvirul Haque - Flaticon</a>
        <a href="https://www.flaticon.com/free-icons/github" title="github icons">Github icons created by Pixel perfect - Flaticon</a>
        <a href="https://www.flaticon.com/free-icons/linkedin" title="linkedin icons">Linkedin icons created by Freepik - Flaticon</a>
        <a href="https://www.flaticon.com/free-icons/instagram-logo" title="instagram logo icons">Instagram logo icons created by Laisa Islam Ani - Flaticon</a>
      
    </section>

</body>
</html>
