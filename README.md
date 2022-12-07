# HUM-RAAHI
This is my html webpage. Which i have made for my college work purpose .
<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        .must
        {
            color:yellow;
            font-family: cursive;
        
        }
    </style>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HUM-SAFAR</title>

    <link rel="stylesheet" href="https://unpkg.com/swiper/swiper-bundle.min.css" />

    <!-- font link  -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">

    <!--  css  -->
            <link rel="stylesheet" href="A:\CA\work3.css">

</head>
<body>
    


<header>

    <div id="menu-bar" class="fas fa-bars"></div>

    <a href="https://www.linkedin.com/in/yash-raj-74013224b" class="logo"><span>HUM</span>RAAHI</a>

    <nav class="navbar">
        <a href="#home">home</a>
        <a href="#book">book</a>
        <a href="#packages">packages</a>
        <a href="#services">services</a>
        <a href="#gallery">gallery</a>
        <a href="#review">review</a>
        <a href="A:\CA\contact us.html">contact us</a>
    </nav>

    <div class="icons">
        <i class="fas fa-search" id="search-btn"></i>
        <i class="fas fa-user" id="login-btn"></i>
    </div>

    <form action="" class="search-bar-container">
        <input type="search" id="search-bar" placeholder="search here...">
        <label for="search-bar" class="fas fa-search"></label>
    </form>

</header>


<!-- login  -->
<div class="login-form-container">

    <i class="fas fa-times" id="form-close"></i>

    <form action="">
        <h3>login</h3>
        <input type="email" class="box" placeholder="enter your email">
        <input type="password" class="box" placeholder="enter your password">
        <input type="submit" value="login now" class="btn">
        <input type="checkbox" id="remember">
        <label for="remember">remember me</label>
        <p>forget password? <a href="#">click here</a></p>
        <p>don't have and account? <a href="#">register now</a></p>
    </form>

</div>

 <!-- home  -->
    <section class="home" id="home">

    <div class="content">
        <h3>adventure is worthwhile</h3>
        <p>Pay Money To Us We Will Take You Wherever You Wanna Go. </p>
        <a href="#" class="btn">discover more</a>
    </div>

    <div class="controls">
        <span class="vid-btn active" data-src="A:\CA\video2.mp4"></span>
        <span class="vid-btn" data-src="A:\CA\video.1.mp4"></span>
        <span class="vid-btn" data-src="A:\CA\video3.mp4"></span>
        <span class="vid-btn" data-src="A:\CA\production ID_4443766.mp4"></span>
        <span class="vid-btn" data-src="A:\CA\production ID_4440999.mp4"></span>
    </div>

    <div class="video-container">
        <video src="images/vid-1.mp4" id="video-slider" loop autoplay muted></video>
    </div>

</section>



  <!-- book  -->

<section class="book" id="book">

    <h1 class="heading">
        <span>b</span>
        <span>o</span>
        <span>o</span>
        <span>k</span>
        <span class="space"></span>
        <span>n</span>
        <span>o</span>
        <span>w</span>
    </h1>

    <div class="row">

        <div class="image">
            <img src="https://c4.wallpaperflare.com/wallpaper/227/60/1/anime-the-place-promised-in-our-early-days-the-place-promised-in-our-early-days-hd-wallpaper-preview.jpg"  height="520" align="" alt="">
        </div>

        <form action="">
            <div class="inputBox">
                <h3>where to</h3>
                <input type="text" placeholder="place name">
            </div>
            <div class="inputBox">
                <h3>how many</h3>
                <input type="number" placeholder="number of guests">
            </div>
            <div class="inputBox">
                <h3>arrivals</h3>
                <input type="date">
            </div>
            <div class="inputBox">
                <h3>leaving</h3>
                <input type="date">
            </div>
            <input type="submit" class="btn" value="book now" onclick="one()">
        </form>

    </div>

</section>



<!-- packages -->

<section class="packages" id="packages">

    <h1 class="heading">
        <span>p</span>
        <span>a</span>
        <span>c</span>
        <span>k</span>
        <span>a</span>
        <span>g</span>
        <span>e</span>
        <span>s</span>
    </h1>

    <div class="box-container">

        <div class="box">
            <img src="A:\CA\image 1.jpg" alt="">
            <div class="content">
                <h3> <i class="fas fa-map-marker-alt"></i> Bali</h3>
                <p>Tee-ravel is a team of experienced and professional drivers in Bali. We are offering personal and complete service for your Bali Travel needs.Please contact us to book your ticket now and win a chance to get 40% off in your ticket price.</p>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="far fa-star"></i>
                </div>
                <div class="price">Rs.60,090.00 <span>Rs.78,120.00</span> </div>
                <a href="#" class="btn">book now</a>
            </div>
        </div>

        <div class="box">
            <img src="A:\CA\image 2.jpg" alt="">
            <div class="content">
                <h3> <i class="fas fa-map-marker-alt"></i> hawaii </h3>
                <p>Aloha, ocean views, sandy shores,and sunny climes you’re on the ultimate Hawaii travel package. Please contact us to book your ticket now and win a chance to get 40% off in your ticket price.</p>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="far fa-star"></i>
                </div>
                <div class="price"> Rs.44,990.00 <span>Rs.55,120.00</span> </div>
                <a href="#" class="btn">book now</a>
            </div>
        </div>

        <div class="box">
            <img src="A:\CA\image 3.jpg" alt="">
            <div class="content">
                <h3> <i class="fas fa-map-marker-alt"></i> Jaipur </h3>
                <p>ind complete list of Rajasthan tour and travel packages with available best services. Easy Hotel Booking We have tied up with hotels that have excellent services, great rooms at great prices.</p>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="far fa-star"></i>
                </div>
                <div class="price">Rs.5,990.00 <span>Rs.7,120.00</span> </div>
                <a href="#" class="btn">book now</a>
            </div>
        </div>

        <div class="box">
            <img src="A:\CA\image 4.jpg" alt="">
            <div class="content">
                <h3> <i class="fas fa-map-marker-alt"></i>Rajasthan </h3>
                <p>Rajasthan Tour Packages - Book budget tour & travel holiday packages to Rajasthan. Enjoy affordable trips, enjoy the royal taste. We offer full Rajasthan sightseeing tour packages at minimum price.</p>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="far fa-star"></i>
                </div>
                <div class="price"> Rs.4,990.00 <span>Rs.5,120.00</span> </div>
                <a href="#" class="btn">book now</a>
            </div>
        </div>

        <div class="box">
            <img src="A:\CA\image 5.jpg" alt="">
            <div class="content">
                <h3> <i class="fas fa-map-marker-alt"></i> Tokyo </h3>
                <p>Tokyo Anime Tour with Hakone & Nagoya Autumn Tokyo / Hakone / Nagoya Join our delightful autumn Anime Tour of Japan, exploring anime and manga must-sees through Tokyo, Hakone, and Nagoya</p>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="far fa-star"></i>
                </div>
                <div class="price"> Rs.43,390.00 <span>Rs.54,120.00</span> </div>
                <a href="#" class="btn">book now</a>
            </div>
        </div>

        <div class="box">
            <img src="A:\CA\image 6.jpg" alt="">
            <div class="content">
                <h3> <i class="fas fa-map-marker-alt"></i> Jammu & Kashmir </h3>
                <p>Tour Packages starts from Jammu Delightful Kashmir Tour Enchanting Kashmir Tour Katra with Shivkhori Tour Glorious Jammu and Kashmir and Vaishno Devi Tour Katra Patnitop Srinagar Gulmarg Pahalgam Sonmarg</p>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="far fa-star"></i>
                </div>
                <div class="price"> Rs.11,990.00 <span>Rs.15,120.00</span> </div>
                <a href="#" class="btn">book now</a>
            </div>
        </div>

    </div>

</section>



<!-- services -->

<section class="services" id="services">

    <h1 class="heading">
        <span>s</span>
        <span>e</span>
        <span>r</span>
        <span>v</span>
        <span>i</span>
        <span>c</span>
        <span>e</span>
        <span>s</span>
    </h1>

    <div class="box-container">

        <div class="box">
            <i class="fas fa-hotel"></i>
            <h3>affordable hotels</h3>
            <p> We give you best services related to hotels and residential facilities ! We will give you best hotels in your budget. Ranging from a Lodge to a Five-Star Hotel in a cheap price.</p>
        </div>
        <div class="box">
            <i class="fas fa-utensils"></i>
            <h3>food and drinks</h3>
            <p>Food and Drinks are availed to you. Premium foods are available in a resonable rate. variety of dishes with variety of drinks are availed in your Exclusive trip package</p>
        </div>
        <div class="box">
            <i class="fas fa-bullhorn"></i>
            <h3>safty guide</h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Inventore commodi earum, quis voluptate exercitationem ut minima itaque iusto ipsum corrupti!</p>
        </div>
        <div class="box">
            <i class="fas fa-globe-asia"></i>
            <h3>around the world</h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Inventore commodi earum, quis voluptate exercitationem ut minima itaque iusto ipsum corrupti!</p>
        </div>
        <div class="box">
            <i class="fas fa-plane"></i>
            <h3>fastest travel</h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Inventore commodi earum, quis voluptate exercitationem ut minima itaque iusto ipsum corrupti!</p>
        </div>
        <div class="box">
            <i class="fas fa-hiking"></i>
            <h3>adventures</h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Inventore commodi earum, quis voluptate exercitationem ut minima itaque iusto ipsum corrupti!</p>
        </div>

    </div>

</section>



<!-- gallery   -->

<section class="gallery" id="gallery">

    <h1 class="heading">
        <span>g</span>
        <span>a</span>
        <span>l</span>
        <span>l</span>
        <span>e</span>
        <span>r</span>
        <span>y</span>
    </h1>

    <div class="box-container">

        <div class="box">
            <img src="https://www.tripsavvy.com/thmb/nB_VbZj6wGNXdPGYnsnLpyvm9Wc=/2122x1412/filters:fill(auto,1)/GettyImages-537000923-541774dbe2d44759815fdf0719b04685.jpg" alt="">
            <div class="content">
                <h3>Gujrat.</h3>
                <p><span class="must">Must visit:</span>Rann Of Kutch.</p>
                <a href="#" class="btn">see more</a>
            </div>
        </div>
        <div class="box">
            <img src="A:\CA\image 7.jpg" alt="">
            <div class="content">
                <h3>Himachal Pradesh.</h3>
                <p><span class="must">Must visit:</span>Divya Mam's  home.</p>
                <a href="#" class="btn">see more</a>
            </div>
        </div>
        <div class="box">
            <img src="A:\CA\pexels-chen-ichun-1874905.jpg" alt="">
            <div class="content">
                <h3>Banglore.</h3>
                <p><span class="must">Must vist:</span>Radha Krishna Temple</p>
                <a href="#" class="btn">see more</a>
            </div>
        </div>
        <div class="box">
            <img src="A:\CA\image 9.jpg" alt="">
            <div class="content">
                <h3>Hyderabad.</h3>
                <p><span class="must">Must visit:</span> Char Minar</p>
                <a href="#" class="btn">see more</a>
            </div>
        </div>
        <div class="box">
            <img src="https://tse2.mm.bing.net/th?id=OIP.yJFy9jRGHng627iHIZhzYgHaEK&pid=Api&P=0" alt="">
            <div class="content">
                <h3>Jammu Kashmir.</h3>
                <p><span class="must">Must visit:</span> Vaishno Devi Maa.</p>
                <a href="#" class="btn">see more</a>
            </div>
        </div>
        <div class="box">
            <img src="https://tse2.mm.bing.net/th?id=OIP.ysL9_Bpxd0RfTFmtICrEkQHaFj&pid=Api&P=0" alt="">
            <div class="content">
                <h3>Dhanbad.</h3>
                <p><span class="must">Must visit:</span>Wasseypur.</p>
                <a href="#" class="btn">see more</a>
            </div>
        </div>
        <div class="box">
            <img src="https://tse3.mm.bing.net/th?id=OIP.sskkSsUs3ydrU7yJeloN9AHaEK&pid=Api&P=0" alt="">
            <div class="content">
                <h3>Japan.</h3>
                <p><span class="must">Must visit:</span> Kyoko.</p>
                <a href="#" class="btn">see more</a>
            </div>
        </div>
        <div class="box">
            <img src="https://tse3.mm.bing.net/th?id=OIP.9-sXZB-9k3M4Lvp1UiW53wHaFj&pid=Api&P=0" alt="">
            <div class="content">
                <h3>Punjab.</h3>
                <p><span class="must">Must vist:</span> Golden Temple.</p>
                <a href="#" class="btn">see more</a>
            </div>
        </div>
        <div class="box">
            <img src="https://tse1.mm.bing.net/th?id=OIP.svtbfeLsV6P8ilHusHitNAHaE8&pid=Api&P=0" alt="">
            <div class="content">
                <h3>Jaipur.</h3>
                <p><span class="must">Must visit:</span>Jantar Mantar.</p>
                <a href="#" class="btn">see more</a>
            </div>
        </div>

    </div>

</section>



<!-- review   -->

<section class="review" id="review">

    <h1 class="heading">
        <span>r</span>
        <span>e</span>
        <span>v</span>
        <span>i</span>
        <span>e</span>
        <span>w</span>
    </h1>

    <div class="swiper-container review-slider">

        <div class="swiper-wrapper">

            <div class="swiper-slide">
                <div class="box">
                    <img src="https://i.pinimg.com/originals/8c/e7/4e/8ce74e67ed562ed714846274b8b3d7f2.jpg" alt="">
                    <h3>GOKU</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsa adipisci quisquam sunt nesciunt fugiat odit minus illum asperiores dolorum enim sint quod ipsam distinctio molestias consectetur ducimus beatae, reprehenderit exercitationem!</p>
                    <div class="stars">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="far fa-star"></i>
                    </div>
                </div>
            </div>
            <div class="swiper-slide">
                <div class="box">
                    <img src="https://img.artpal.com/512122/1-17-26t.jpg" alt="">
                    <h3>ITACHI</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsa adipisci quisquam sunt nesciunt fugiat odit minus illum asperiores dolorum enim sint quod ipsam distinctio molestias consectetur ducimus beatae, reprehenderit exercitationem!</p>
                    <div class="stars">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="far fa-star"></i>
                    </div>
                </div>
            </div>
            <div class="swiper-slide">
                <div class="box">
                    <img src="A:\CA\divya mam.jpeg" alt="">
                    <h3>DIVYA MAM</h3>
                    <p>This is a good website. Yash who has made this project is my favourite student. I will GIVE FULL MARKS to them sa their project is so good. I am glad that i am the techer of YASH and wish to be in the next semester also. </p>
                    <div class="stars">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="far fa-star"></i>
                    </div>
                </div>
            </div>
            <div class="swiper-slide">
                <div class="box">
                    <img src="https://i.pinimg.com/originals/24/72/3e/24723e14c6ea83dba68f27ab73d855b8.jpg" alt="">
                    <h3>VEGETA</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsa adipisci quisquam sunt nesciunt fugiat odit minus illum asperiores dolorum enim sint quod ipsam distinctio molestias consectetur ducimus beatae, reprehenderit exercitationem!</p>
                    <div class="stars">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="far fa-star"></i>
                    </div>
                </div>
            </div>
            <div class="swiper-slide">
                <div class="box">
                    <img src="https://ums.lpu.in/lpuums/DisplayImageForPowerBi.aspx?id=c65e930d-1fd3-4b9d-b74a-0387b7732c7f" alt="">
                    <h3>DIVYA MADAM</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsa adipisci quisquam sunt nesciunt fugiat odit minus illum asperiores dolorum enim sint quod ipsam distinctio molestias consectetur ducimus beatae, reprehenderit exercitationem!</p>
                    <div class="stars">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="far fa-star"></i>
                    </div>
                </div>
            </div>
            <div class="swiper-slide">
                <div class="box">
                    <img src="https://wallpaperaccess.com/full/879694.png" alt="">
                    <h3>SASUKE</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsa adipisci quisquam sunt nesciunt fugiat odit minus illum asperiores dolorum enim sint quod ipsam distinctio molestias consectetur ducimus beatae, reprehenderit exercitationem!</p>
                    <div class="stars">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="far fa-star"></i>
                    </div>
                </div>
            </div>

        </div>

    </div>

</section>



<!-- contact  -->

<section class="contact" id="contact">
    
    <h1 class="heading">
        <span>c</span>
        <span>o</span>
        <span>n</span>
        <span>t</span>
        <span>a</span>
        <span>c</span>
        <span>t</span>
        <span class="space"></span>
        <span>u</span>
        <span>s</span>
        
    </h1>

    <div class="row">

        <div class="image">
            <img src="https://dthezntil550i.cloudfront.net/1z/latest/1z2106291344089220021176382/b00102ec-5608-4117-a0bb-09fbf3e31268.png" alt="">
        </div>

        <form action="">
            <div class="inputBox">
                <input type="text" placeholder="name">
                <input type="email" placeholder="email">
            </div>
            <div class="inputBox">
                <input type="number" placeholder="number">
                <input type="text" placeholder="subject">
            </div>
            <textarea placeholder="message" name="" id="" cols="30" rows="10"></textarea>
            <input type="submit" class="btn" value="send message" onclick="one()">
        </form>

    </div>
    
</section>

<!-- contact-->

<!-- brand section  -->
<section class="brand-container">

    <div class="swiper-container brand-slider">
        <div class="swiper-wrapper">
            <div class="swiper-slide"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSTv3eicbhRCePsBTy7HFg__lC3mSyPwiNelA&usqp=CAU" alt=""></div>
            <br>
            <div class="swiper-slide"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSIdRNDe_hvK6pLuOEAzKOg8qGJ43VOpQ1mhw&usqp=CAU" alt=""></div>
            <br>
            <div class="swiper-slide"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTMUr8Jhln5U5XIV-i07Q247j83YvJ4x_SyFg&usqp=CAU" alt=""></div>
            <br>
            <div class="swiper-slide"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTUk8YFtBcDCQSLxDoNHgfLamkMZQxmBzhsfw&usqp=CAU" alt=""></div>
            <div class="swiper-slide"><img src="https://w7.pngwing.com/pngs/153/31/png-transparent-netflix-macos-bigsur-icon.png" alt=""></div>
            <div class="swiper-slide"><img src="images/6.jpg" alt=""></div>
        </div>
    </div>

</section>

<!-- footer section  -->

<section class="footer">

    <div class="box-container">

        <div class="box">
            <h3>about us</h3>
            <p>Our team consist of two individuals Yash and Aditya. We both have created this webpage . We worked hard day and night to make this project successfull. We took refrence from different videos and websites to accquire knowledge to make this website fully dynamic and responsive.</p>
        </div>
        <div class="box">
            <h3>Project Sponsors:</h3>
            <a href="#">Divya Mam</a>
            <a href="#">Rashmi Mittal</a>
            <a href="#">Narendra Modi</a>
            <a href="#">Baldev Raj Mittal</a>
            <a href="#">Yash Raj</a>
            <a href="#">Aditya Mishra</a>
            
         </div>
        <div class="box">
            <h3>quick links</h3>
            <a href="#">home</a>
            <a href="#">book</a>
            <a href="#">packages</a>
            <a href="#">services</a>
            <a href="#">gallery</a>
            <a href="#">review</a>
            <a href="#">contact</a>
        </div>
        <div class="box">
            <h3>follow us</h3>
            <a href="#">facebook</a>
            <a href="#">instagram</a>
            <a href="#">twitter</a>
            <a href="#">linkedin</a>
        </div>

    </div>

    <h1 class="credit"> created by <span> Yash Raj And Aditya Mishra </span> | Project By Divya Mam ! </h1>

</section>
















<script src="https://unpkg.com/swiper/swiper-bundle.min.js"></script>

<!-- custom js file link  -->
<script src="A:\CA\work2.js"></script>



<script>
    alert
    function one()
    {
        alert("Warning\n Your Data Has Been Recorded!")
    }
</script>


</body>
</html>
