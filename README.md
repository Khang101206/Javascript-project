# final-project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Merriweather:wght@400;700&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@500&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@1,700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link
        rel="stylesheet"
        type="text/css"
        href="https://cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.css"
      />
    <link rel="stylesheet" href="css/general.css">
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="css/home.css">
    <link rel="stylesheet" href="css/responsive.css">
</head>
<body>
    <header>
        <div class="nav-bar-header">
            <div class="phone-and-logo">
                <p class="hotline">Hotline 1900 090909</p>
                <div class="logo"><a><img src="img/logo.svg"></a></div>
                <div class="name-store"><a><p>Luxury Store</p></a></div>
            </div>
            <div class="three-bars">
                <a>
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
                      </svg> 
                </a>                 
            </div>
            <div class="social-box">
                <ul>
                    <li><a><img src="img/fb.svg"></a></li>    
                    <li><a><img src="img/ins.svg"></a></li>
                    <li><a><img src="img/tiktok.svg"></a></li>
                    <li><a><img src="img/Youtube.svg"></a></li>
                </ul>
                <div class="cart-button" >
                    <div class="quantity-product"></div>
                    <a href="cart.html">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 3h1.386c.51 0 .955.343 1.087.835l.383 1.437M7.5 14.25a3 3 0 00-3 3h15.75m-12.75-3h11.218c1.121-2.3 2.1-4.684 2.924-7.138a60.114 60.114 0 00-16.536-1.84M7.5 14.25L5.106 5.272M6 20.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm12.75 0a.75.75 0 11-1.5 0 .75.75 0 011.5 0z" />
                          </svg>                     
                    </a>
                </div>
                <div><a class="login-button" href="signIn.html">Login</a></div>
            </div>
        </div>
        <div class="menu-header">
            <ul class="menu-header_all">
                <li class="home menu-header_item"><a class="header-item" href="home.html">HOME</a></li>
                <li class="category menu-header_item">
                    <a class="header-item">CATEGORY</a>
                    <ul class="category-item">
                        <li><a class="header-item-item" href="brand.html?category=All"><p>All</p></a></li>
                    </ul>
                </li>
                <li class="brand menu-header_item">
                    <a class="header-item">BRAND</a>
                    <ul class="brand-item">
                        <li><a class="brand_a" href="brand.html?category=All"><p>All</p></a></li>
                    </ul>
                </li>
                <li class="blog menu-header_item"><a class="header-item" href="blog.html">BLOG</a></li>
            </ul>
            <div class="search">
                <div class="search-input">
                    <input class="search-header" type="text" placeholder="Search...">
                    <div class="products-search hide">
                        <!-- <a class="search-item">
                            <img src="watchesImg/cartier(1).png" alt="">
                            <p>Hublot Classic Fusion Ceramic Blue Chronograph 42mm 541.CM.7170.RX</p>
                        </a> -->
                    </div>
                </div>
                <a class="search-header-button"><div class="search-header-button"><p>Search</p></div></a>
            </div>
        </div>
        <div class="menu-box">
            <ul class="menu-box_mobile">				
                <li class="menu-box-item">
                    <a href="/home.html">HOME</a>
                </li>
                <li class="menu-box-item menu-box-item-list menu-box-category-list">
                    <a>CATEGORY</a>
                    <ul class="category-list">   
                        <li>
                            <a style="width: 700px;" href="brand.html?category=All">All</a>
                        </li> 
                    </ul>
                </li>
                <li class="menu-box-item menu-box-item-list menu-box-brand-list">
                    <a>BRAND</a>
                    <ul class="brand-list">
                        <li>
                            <a href="brand.html?category=All">All</a>
                        </li>  
                    </ul>
                </li>
                <li class="menu-box-item">
                    <a>SERVICE</a>
                </li>     
                <li class="menu-box-item">
                    <a href="blog.html">BLOG</a>
                </li>  
                <div class="user-nav-mb" class="menu-box-item">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M15.75 9V5.25A2.25 2.25 0 0013.5 3h-6a2.25 2.25 0 00-2.25 2.25v13.5A2.25 2.25 0 007.5 21h6a2.25 2.25 0 002.25-2.25V15m3 0l3-3m0 0l-3-3m3 3H9" />
                      </svg>
                      <a href="/signIn.html">Login</a>
                </div>          
            </ul>
        </div>
    </header>
    <main style="padding: 0;">
        <div class="home-page_vid">
            <div class="home">
                <video autoplay muted loop id="myVideo">
                    <source type="video/mp4" src="img/vid.mp4">
                </video>
            </div>
        </div>
        <div class="event">
            <p class="text">Events</p>
            <div class="event-slider">
                <div class="sliderContainer">
                    <div class="slider single-item">
                        <div class="slider-item_event">
                            <div class="event-title">
                                <p>Jacob & Co. Bugatti Chiron Tourbillon Blue Titanium Watch Launching Event</p>
                            </div>
                            <div class="event-img">
                                <img src="img/event1.png">
                            </div>
                        </div>
                        <div class="slider-item_event">
                            <div class="event-title">
                                <p>Jacob & Co Fleurs De Jardin Rainbow watch in a private party night at Rose Villa</p>
                            </div>
                            <div class="event-img">
                                <img src="img/event2.png">
                            </div>
                        </div>
                        <div class="slider-item_event">
                            <div class="event-title">
                                <p>Hermle Vietnam Showroom at C-Space is officially launched</p>
                            </div>
                            <div class="event-img">
                                <img src="img/event3.png">
                            </div>
                        </div>
                    </div>
                    <div class="progressBarContainer">
                      <div class="item">
                        <span data-slick-index="0" class="progressBar"></span>
                      </div>
                      <div class="item">
                        <span data-slick-index="1" class="progressBar"></span>
                      </div>
                      <div class="item">
                        <span data-slick-index="2" class="progressBar"></span>
                      </div>
                    </div>
                  </div>
            </div>
        </div>
        <div class="brand_home-page">
            <a class="brand-item_home-page" href="brand.html?brand=Chopard">
                <img src="img/chopard.png">
                 <p>Chopard</p>
            </a>
            <a class="brand-item_home-page" href="brand.html?brand=Hublot">
                <img src="img/hublot.png">
                 <p>Hublot</p>
            </a>
            <a class="brand-item_home-page" href="brand.html?brand=Omega">
                <img src="img/Omega.png">
                 <p>Omega</p>
            </a>
            <a class="brand-item_home-page" href="brand.html?brand=Rolex">
                <img src="img/rolex.png">
                 <p>Rolex</p>
            </a>
            <a class="brand-item_home-page" href="brand.html?brand=Jacob%20&%20Co">
                <img src="img/JacobAndCo.png">
                 <p>Jacob & Co</p>
            </a>
            <a class="brand-item_home-page" href="brand.html?brand=Patek%20Philippe">
                <img src="img/patek.png">
                 <p>Patek Philippe</p>
            </a>
        </div>
        <div class="new-arrivals">
            
        </div>
        <div class="our-partner_home-page">
            <div class="our-partner_text">
                <p class="text">Our partner</p>
            </div>
            <div class="our-partner">
                <div class="our-partner-item"><img src="img/doitac_image_1.png"></div>
                <div class="our-partner-item"><img src="img/doitac_image_2.png"></div>
                <div class="our-partner-item"><img src="img/doitac_image_3.png"></div>
                <div class="our-partner-item"><img src="img/doitac_image_4.png"></div>
            </div>
        </div>

    </main>
    <footer>
        <div class="footer-menu">
            <div class="footer-menu-title footer-title">
                <h2>MENU</h2>
            </div>
            <div class="footer-menu-all-item">
                <div class="footer-menu-item"><a>Home</a></div>
                <div class="footer-menu-item"><a>Category</a></div>
                <div class="footer-menu-item"><a>Brand</a></div>
                <div class="footer-menu-item"><a>Service</a></div>
                <div class="footer-menu-item"><a>Blog</a></div>
                <div class="footer-menu-item"><a>About</a></div> 
            </div>
        </div>
        <div class="contact">
            <div class="contact-title footer-title">
                <h2>CONTACT</h2>
            </div>
            <div class="contact-all">
                <div class="contact-item_location contact-item">
                    <div class="location-logo contact-logo">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                            <path stroke-linecap="round" stroke="#b6b6b6" stroke-linejoin="round" d="M15 10.5a3 3 0 11-6 0 3 3 0 016 0z" />
                            <path stroke-linecap="round" stroke="#b6b6b6" stroke-linejoin="round" d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1115 0z" />
                          </svg>                          
                    </div>
                    <p>203 Tran Hung Dao, District 1, Ho Chi Minh City</p>
                </div>
                <div class="contact-item_phone contact-item">
                    <div class="phone-logo contact-logo">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="#b6b6b6" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 002.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.173.417l-.97 1.293c-.282.376-.769.542-1.21.38a12.035 12.035 0 01-7.143-7.143c-.162-.441.004-.928.38-1.21l1.293-.97c.363-.271.527-.734.417-1.173L6.963 3.102a1.125 1.125 0 00-1.091-.852H4.5A2.25 2.25 0 002.25 4.5v2.25z" />
                        </svg>
                    </div>
                    <p>1900090909</p>
                </div>
                <div class="contact-item_email contact-item">
                    <div class="email-logo contact-logo">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                            <path stroke-linecap="round" stroke="#b6b6b6" stroke-linejoin="round" d="M21.75 6.75v10.5a2.25 2.25 0 01-2.25 2.25h-15a2.25 2.25 0 01-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0019.5 4.5h-15a2.25 2.25 0 00-2.25 2.25m19.5 0v.243a2.25 2.25 0 01-1.07 1.916l-7.5 4.615a2.25 2.25 0 01-2.36 0L3.32 8.91a2.25 2.25 0 01-1.07-1.916V6.75" />
                          </svg>                          
                    </div>
                    <p>Luxurystore123@gmail.com</p>
                </div>
            </div>
        </div>
        <div class="policy">
            <div class="policy-title footer-title">
                <h2>POLICY</h2>
            </div>
            <div class="policy-all">
                <div class="policy-item"><a>Privacy Policy </a></div>
                <div class="policy-item"><a>Warranty Policy</a></div>
                <div class="policy-item"><a>Payment Policy</a></div>
                <div class="policy-item"><a>Delivery Policy </a></div>
                <div class="policy-item"><a>Order & Purchase Guide</a></div>
            </div>
        </div>
    </footer>
    <script
    type="text/javascript"
    src="https://code.jquery.com/jquery-1.11.0.min.js"
  ></script>
  <script
    type="text/javascript"
    src="https://code.jquery.com/jquery-migrate-1.2.1.min.js"
  ></script>
  <script
    type="text/javascript"
    src="https://cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.min.js"
  ></script>
    <script src="/js/home.js"></script>
    <script type="module" src="js/search.js"></script>
    <script  type="module" src="/js/main.js"></script>
</body>
</html>
