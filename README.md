# Food-Wagon-Website HTML Code

<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="style.css">

  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js">

  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css"
    integrity="sha512-z3gLpd7yknf1YoNbCzqRKc4qyor8gaKU1qmn+CShxbuBusANI9QpRohGBreCFkKxLhei6S9CQXFEbbKuqLg0DA=="
    crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>

<body>

  <!--Header-->

  <div class="container">

    <div class="row header">
      <div class=" logo_div">
        <img class="logo" src="imgs/logo.png" alt="Logo">
      </div>

      <div class="search_span_1 ">
        <span>Deleiver to: </span><i class="fa-solid fa-location-dot icon_color"></i><span><span class="norm_span">
            Current location</span></span><span> Karachi, Pakistan</span>
      </div>

      <div class="search_span_2 ">
        <i class="fa-solid fa-magnifying-glass icon_color"></i><span> Search Food</span>
      </div>


      <div class="button_div ">
        <button class="btn btn-warning login_button"><i class="fa-solid fa-user"></i>&nbsp;&nbsp;Login</button>
      </div>
    </div>
  </div>


  <!--Search_Div-->



  <div class="searchdiv">
    <div class="searchheading">
      <h1>Are you starving?</h1>
      <p>Within a few clicks, find meals that are accessible near you</p>

      <div class="searchimage">
        <img src="imgs/Image.png" alt="Poster">
      </div>
    </div>



    <div class="searchdiv_searchbar">
      <div class="searchdiv_searchbar_innerdiv">
        <i class="fa-solid fa-motorcycle"></i>
        Deleivery
      </div>
      <div class="searchdiv_searchbar_innerdiv_pickup">
        <i class="fa-solid fa-bag-shopping"></i>
        Pick Up
      </div>
      <div class="searchdiv_searchbar_innerdiv_searchbar">
        <i class="fa-solid fa-location-dot"></i>
        <form>
          <input class="searchdiv_searchbar_innerdiv_searchbar_form" type="text" placeholder="Enter Your Address">
        </form>
      </div>
      <button class="searchdiv_searchbar_innerdiv_searchbar_button">
        <i class="fa-solid fa-magnifying-glass"></i>
        <span>Find Food</span>
      </button>
    </div>
  </div>

  <!--Card_Div-->

  <div class="container">

    <div class="row cardDivMain">
      <div class="col-md-6 col-lg-3 col-sm-6 cardDiv">

        <div class="sale_tag">
          <div class="num">
            15
          </div>
          <div class="off">
            <div class="per">%</div>
            <div class="offin">Off</div>
          </div>
        </div>

        <img class="cardDiv_img" src="imgs/CardDeal (1).png" alt="Card1">
        <h6 class="cardTittle">Grey Vage</h6>
        <p class="cardDays">6 Days Remaining</p>
      </div>
      <div class="col-md-6 col-lg-3 col-sm-6 cardDiv">

        <div class="sale_tag">
          <div class="num">
            10
          </div>
          <div class="off">
            <div class="per">%</div>
            <div class="offin">Off</div>
          </div>
        </div>

        <img class="cardDiv_img" src="imgs/CardDeal (4).png" alt="Card1">
        <h6 class="cardTittle">Grey Vage</h6>
        <p class="cardDays">6 Days Remaining</p>
      </div>
      <div class="col-md-6 col-lg-3 col-sm-6 cardDiv">

        <div class="sale_tag">
          <div class="num">
            25
          </div>
          <div class="off">
            <div class="per">%</div>
            <div class="offin">Off</div>
          </div>
        </div>

        <img class="cardDiv_img" src="imgs/CardDeal (2).png" alt="Card1">
        <h6 class="cardTittle">Grey Vage</h6>
        <p class="cardDays">6 Days Remaining</p>
      </div>
      <div class="col-md-6 col-lg-3 col-sm-6 cardDiv">

        <div class="sale_tag">
          <div class="num">
            20
          </div>
          <div class="off">
            <div class="per">%</div>
            <div class="offin">Off</div>
          </div>
        </div>

        <img class="cardDiv_img" src="imgs/CardDeal (3).png" alt="Card1">
        <h6 class="cardTittle">Grey Vage</h6>
        <p class="cardDays">6 Days Remaining</p>
      </div>
    </div>
  </div>

  <!--About-->

  <div class="about">
    <div class="container">

      <div class="howWork">
        <h3 class="howWorkHeading">How does it work</h3>
      </div>

      <div class="row aboutDiv">
        <div class="col-md-6 col-lg-3 col-sm-6">
          <img class="aboutIcons" src="imgs/icon (3).png" alt="icon">
          <h6 class="abooutTittle">Select Location</h6>
          <p>Choose the location where your food will be deleivered</p>
        </div>

        <div class="col-md-6 col-lg-3 col-sm-6">
          <img class="aboutIcons" src="imgs/icon (4).png" alt="icon">
          <h6 class="abooutTittle">Choose Order</h6>
          <p>Check over hundreds of menus to pick your favorite food</p>
        </div>

        <div class="col-md-6 col-lg-3 col-sm-6">
          <img class="aboutIcons" src="imgs/icon (1).png" alt="icon">
          <h6 class="abooutTittle">Pay Advance</h6>
          <p>It's quick, safe, and simple. Select several methods of payment</p>
        </div>

        <div class="col-md-6 col-lg-3 col-sm-6">
          <img class="aboutIcons" src="imgs/icon (2).png" alt="icon">
          <h6 class="abooutTittle"><br>Enjoy Meals</h6>
          <p>Food is made and delivered directly to your home.</p>
        </div>
      </div>

    </div>
  </div>

  <!--Popular Items Section-->

  <div class="container">

    <div class="row cardDivMain3">

      <div class="popularItems">
        <h3 class="popularItemsHeading">Popular Items</h3>
      </div>

      <div class="col-md-6 col-lg-3 col-sm-6 cardDiv">
        <img class="cardDiv_img" src="imgs/PopularItems (4).png" alt="Card1">
        <h6 class="cardTittle">Cheese Burger</h6>
        <h6 class="cardLocation">
          <i class="fa-solid fa-location-dot icon_color"></i> Burger Arena
        </h6>
        <h6 class="cardTittlePrice">3.88$</h6>
        <div class="buttonDiv">
          <button class="btn btn-warning orderNowBtn">
            <h5 class="orderNowBtnTxt">Order Now</h5>
          </button>
        </div>
      </div>

      <div class="col-md-6 col-lg-3 col-sm-6 cardDiv">
        <img class="cardDiv_img" src="imgs/PopularItems (1).png" alt="Card1">
        <h6 class="cardTittle">Toffe's Cake</h6>
        <h6 class="cardLocation">
          <i class="fa-solid fa-location-dot icon_color"></i>
          Top Stick
        </h6>
        <h6 class="cardTittlePrice">4.00$</h6>
        <div class="buttonDiv">
          <button class="btn btn-warning orderNowBtn">
            <h5 class="orderNowBtnTxt">Order Now</h5>
          </button>
        </div>

      </div>

      <div class="col-md-6 col-lg-3 col-sm-6 cardDiv">
        <img class="cardDiv_img" src="imgs/PopularItems (2).png" alt="Card1">
        <h6 class="cardTittle">Dancake</h6>
        <h6 class="cardLocation">
          <i class="fa-solid fa-location-dot icon_color"></i>
          Cake World
        </h6>
        <h6 class="cardTittlePrice">1.99$</h6>
        <div class="buttonDiv">
          <button class="btn btn-warning orderNowBtn">
            <h5 class="orderNowBtnTxt">Order Now</h5>
          </button>
        </div>

      </div>

      <div class="col-md-6 col-lg-3 col-sm-6 cardDiv">
        <img class="cardDiv_img" src="imgs/PopularItems (3).png" alt="Card1">
        <h6 class="cardTittle">Crispy Sandwitch</h6>
        <h6 class="cardLocation">
          <i class="fa-solid fa-location-dot icon_color"></i>
          FastFood Dine
        </h6>
        <h6 class="cardTittlePrice">3.00$</h6>
        <div class="buttonDiv">
          <button class="btn btn-warning orderNowBtn">
            <h5 class="orderNowBtnTxt">Order Now</h5>
          </button>
        </div>
      </div>

      <!--Featured Products Section-->

      <div class="container">

        <div class="row cardDivMain">

          <div class="popularItems2">
            <h3 class="popularItemsHeading2">Featured Restaurants</h3>
          </div>

          <div class="col-md-6 col-lg-3 col-sm-6 cardDiv">
            <img class="cardDiv_img" src="imgs/featured (2).png" alt="Card1">
            <div class="outerDiv">
              <div class="resLogo">
                <img src="imgs/Restaruant Logo.png" alt="Food World Logo">
              </div>
              <h6 class="cardTittle2">Food World</h6>
              <h6 class="cardStar">
                <i class="fa-solid fa-star"></i> 46
              </h6>
              <p class="openNow">Open Now</p>
            </div>
          </div>

          <div class="col-md-6 col-lg-3 col-sm-6 cardDiv">
            <img class="cardDiv_img" src="imgs/featured (3).png" alt="Card1">
            <div class="outerDiv">
              <div class="resLogo">
                <img src="imgs/RestaurantsLogo (3).png" alt="Pizza Hub Logo">
              </div>
              <h6 class="cardTittle2">Pizza Hub</h6>
              <h6 class="cardStar">
                <i class="fa-solid fa-star"></i> 48
              </h6>
              <p class="openTomorrow">Open Tomorrow</p>
            </div>

          </div>

          <div class="col-md-6 col-lg-3 col-sm-6 cardDiv">
            <img class="cardDiv_img" src="imgs/featured (1).png" alt="Card1">
            <div class="outerDiv">
              <div class="resLogo">
                <img src="imgs/RestaurantsLogo (2).png" alt="Dunkin Donuts Logo">
              </div>
              <h6 class="cardTittle2">Donuts Hut</h6>
              <h6 class="cardStar">
                <i class="fa-solid fa-star"></i> 46
              </h6>
              <p class="openNow">Open Now</p>
            </div>

          </div>

          <div class="col-md-6 col-lg-3 col-sm-6 cardDiv">
            <img class="cardDiv_img" src="imgs/featured.png " alt="Card1">

            <div class="outerDiv">
              <div class="resLogo">
                <img src="imgs/RestaurantsLogo.png" alt="Subway Logo">
              </div>
              <h6 class="cardTittle2">Soft Cream</h6>
              <h6 class="cardStar">
                <i class="fa-solid fa-star"></i> 50
              </h6>
              <p class="openNow">Open Now</p>
            </div>
          </div>

        </div>


        <div class="row cardDivMain">

          <div class="col-md-6 col-lg-3 col-sm-6 cardDiv">
            <img class="cardDiv_img" src="imgs/food.png" alt="Card1">
            <div class="outerDiv">
              <div class="resLogo">
                <img src="imgs/RestaurantsLogo (1).png" alt="Ruby Tuesday Logo">
              </div>
              <h6 class="cardTittle3">Ruby Tuesday</h6>
              <h6 class="cardStar">
                <i class="fa-solid fa-star"></i> 46
              </h6>
              <p class="openTomorrow">Open Tomorrow</p>

            </div>
          </div>

          <div class="col-md-6 col-lg-3 col-sm-6 cardDiv">
            <img class="cardDiv_img" src="imgs/food (3).png" alt="Card1">
            <div class="outerDiv">
              <div class="resLogo">
                <img src="imgs/Restaruant Logo (2).png" alt="KFC Logo">
              </div>
              <h6 class="cardTittle5">Karachi Food Center</h6>
              <h6 class="cardStar">
                <i class="fa-solid fa-star"></i> 50
              </h6>
              <p class="openNow">Open Now</p>
            </div>

          </div>

          <div class="col-md-6 col-lg-3 col-sm-6 cardDiv">
            <img class="cardDiv_img" src="imgs/food (4).png" alt="Card1">
            <div class="outerDiv">
              <div class="resLogo">
                <img src="imgs/RestaurantsLogo (4).png" alt="Red Square Logos">
              </div>
              <h6 class="cardTittle2">Red Square</h6>
              <h6 class="cardStar">
                <i class="fa-solid fa-star"></i> 42
              </h6>
              <p class="openTomorrow">Open Tomorrow</p>
            </div>

          </div>

          <div class="col-md-6 col-lg-3 col-sm-6 cardDiv">
            <img class="cardDiv_img" src="imgs/food (2).png " alt="Card1">

            <div class="outerDiv">
              <div class="resLogo">
                <img src="imgs/Restaruant Logo (1).png" alt="Taco Bell Logo">
              </div>
              <h6 class="cardTittle4">Taco Bell</h6>
              <h6 class="cardStar">
                <i class="fa-solid fa-star"></i> 46
              </h6>
              <p class="openNow">Open Now</p>
            </div>
          </div>

        </div>

        <div class="buttonDiv2">
          <button class="btn btn-warning viewAllBtn">
            <h5 class="viewAllBtnTxt">View All ></h5>
          </button>
        </div>
      </div>
    </div>


    <div class="">
      <div class="container">

        <div class="row cardDivMainSBF1">

          <div class="col-md-4 col-lg-2 col-sm-6 searchByFood">
            <img src="imgs/searchByFood (1).png" alt="Burger Image">
            <h6 class="searchByFoodTxt">Burger</h6>
          </div>

          <div class="col-md-4 col-lg-2 col-sm-6 searchByFood">
            <img src="imgs/searchByFood (2).png" alt="">
            <h6 class="searchByFoodTxt">Pizza</h6>

          </div>

          <div class="col-md-4 col-lg-2 col-sm-6 searchByFood">
            <img src="imgs/searchByFood (3).png" alt="">
            <h6 class="searchByFoodTxt">Steak</h6>

          </div>

          <div class="col-md-4 col-lg-2 col-sm-6 searchByFood">
            <img src="imgs/searchByFood (4).png" alt="">
            <h6 class="searchByFoodTxt">Chowmein</h6>

          </div>

          <div class="col-md-4 col-lg-2 col-sm-6 searchByFood">
            <img src="imgs/searchByFood (5).png" alt="">
            <h6 class="searchByFoodTxt">Sub-Sandwitches</h6>

          </div>

          <div class="col-md-4 col-lg-2 col-sm-6 searchByFood">
            <img src="imgs/searchByFood (6).png" alt="">
            <h6 class="searchByFoodTxt">Noodles</h6>

          </div>
        </div>

        <div class="row cardDivMainSBF">
          <div class="col-md-4 col-lg-4 col-sm-4 searchByFood">
            <h4 class="searchByFoodTxt2">Search By Food</h4>

          </div>

          <div class="col-md-4 col-lg-4 col-sm-4 searchByFood">
            <button class="searchByFoodTxt3OuterDiv2">
              <h4 class="searchByFoodTxt3">
                 < </h4>
            </button>

          </div>

          <div class="col-md-4 col-lg-4 col-sm-4 searchByFood">
            <button class="searchByFoodTxt3OuterDiv">
              <h4 class="searchByFoodTxt3">></h4>
            </button>

          </div>
        </div>

      </div>
    </div>
    
    <!--Install App Section-->

    <div class="container">
      <div class="about2">
        <div class="dailyBonus row">
          <img src="imgs/mobileApp (1).png" alt="Discount Tag">
          <h4>Daily <br> Discounts</h4>

          <img class="image2" src="imgs/mobileapp(3).png" alt="Location Tag">
          <h4 class="head2">Live <br> Tracing</h4>

          <img class="image3" src="imgs/mobileApp (2).png" alt="Deleivery Tag">
          <h4 class="head3">Quick <br> Deleivery</h4>

        </div>
      </div>
      

      <div class="installApp">
        <div class="mobileImg">
          <img src="imgs/mobile.png" alt="Mobile images">

        </div>

        <div class="installApp2">
          <h1>Install the app</h1>
          <p>It's never been easier to order food. 
            Look for the <br> finest discounts and you'll
             be lost in a world of <br> delectable food.
          </p>

          <div class="imgDiv">

            

            <img src="imgs/App Store Download Button.png" alt="App Store Logo">

         
            <img src="imgs/Google Play Download.png" alt="Play Store Logo">

          </div>
        </div>

      </div>
    </div>


    <!--Best Deals Section-->

    <div class="bestdeals">
      <div class="bestdealcol1">
        <h2>Best deals <span>Crispy Sandwiches</span></h2>
        <p>Enjoy the large size of sandwiches. Complete
          perfect slice of sandwiches.</p>
        <button class="btn btn-warning proceedOrderBtn2">
            <h3 class="proceedOrderBtnTxt">PROCEED TO ORDER  </h3>
        </button>

      </div>
      <div class="bestdealcol2">
        <img src="imgs/bestDeals (1).png" alt="Deal1 Image">

      </div>
    </div>

    <div class="bestdeals">
      
      <div class="bestdealcol2">
        <img src="imgs/bestDeals (2).png" alt="Deal1 Image">

      </div>

      <div class="bestdealcol1">
        <h2>Celebrate  parties
          with <span>Fried Chicken</span></h2>
        <p>Get the best fried chicken smeared with <br> a lip smacking lemon chili flavor.</p>
        <button class="btn btn-warning proceedOrderBtn2">
            <h3 class="proceedOrderBtnTxt">PROCEED TO ORDER </h3>
        </button>

      </div>
    </div>

    <div class="bestdeals">
      <div class="bestdealcol1">
        <h2>Wanna eat hot <br>
          & spicy <span>Pizza?</span></h2>
        <p>Pair up with a friend and enjoy the <br>
          hot and crispy pizza pops. Try it <br> 
          with the best deals.</p>
        <button class="btn btn-warning proceedOrderBtn2">
            <h3 class="proceedOrderBtnTxt">PROCEED TO ORDER  </h3>
        </button>

      </div>
      <div class="bestdealcol2">
        <img src="imgs/bestDeals (3).png" alt="Deal1 Image">

      </div>
    </div>



    <div class=" bottomBanner">
      <img src="imgs/bottombanner.png" alt="banner">
      <h1 class="bottomBannerHeading" >Are you ready to order with <br> the best deals?</h1>
      <button class="btn btn-warning proceedOrderBtn">
        <h6 class="proceedOrderBtnTxt">PROCEED TO ORDER</h6>
      </button>

    </div>

    <!-- Remove the container if you want to extend the Footer to full width. -->
<div class=" my-5">
  <!-- Footer -->
  <footer
          class="text-center text-lg-start text-white"
          >
    <!-- Grid container -->
    <div class="container p-4 pb-0">
      <!-- Section: Links -->
      <section class="">
        <!--Grid row-->
        <div class="row topCitiesRow">
          <h6 class="text-sentencecase mb-4 font-weight-bold topCities">
              Our top cities
            </h6>
          <!-- Grid column -->
          <div class="col-md-2 col-lg-2 col-xl-2 mx-auto mt-3">
            <p>
              <a class="text-white">San Fransico</a>
            </p>
            <p>
              <a class="text-white">Miami</a>
            </p>
            <p>
              <a class="text-white">Jakarta</a>
            </p>
            <p>
              <a class="text-white">Las Vegas</a>
            </p>
            <p>
              <a class="text-white">New York</a>
            </p>
          </div>
          <!-- Grid column -->

          <!-- Grid column -->
          <div class="col-md-2 col-lg-2 col-xl-2 mx-auto mt-3">
            <p>
              <a class="text-white">Abu Dhabi</a>
            </p>
            <p>
              <a class="text-white">Tokyo</a>
            </p>
            <p>
              <a class="text-white">San Andreas</a>
            </p>
            <p>
              <a class="text-white">Washington DC</a>
            </p>
            <p>
              <a class="text-white">Portland</a>
            </p>
          </div>
          <!-- Grid column -->

          <hr class="w-100 clearfix d-md-none" />

          <!-- Grid column -->
          <div class="col-md-2 col-lg-2 col-xl-2 mx-auto mt-3">
            <p>
              <a class="text-white">Nashville</a>
            </p>
            <p>
              <a class="text-white">Orange County</a>
            </p>
            <p>
              <a class="text-white">Atlanta</a>
            </p>
            <p>
              <a class="text-white">Charlotte</a>
            </p>
            <p>
              <a class="text-white">Denver</a>
            </p>
          </div>
          <!-- Grid column -->

          <hr class="w-100 clearfix d-md-none" />

          <!-- Grid column -->
          <div class="col-md-3 col-lg-2 col-xl-2 mx-auto mt-3">
            <p>
              <a class="text-white">Chicago</a>
            </p>
            <p>
              <a class="text-white">Phoenix</a>
            </p>
            <p>
              <a class="text-white">Sacramento</a>
            </p>
            <p>
              <a class="text-white">Oklahoma City</a>
            </p>
            <p>
              <a class="text-white">Columbus</a>
            </p>
          </div>

          <!-- Grid column -->
          <hr class="w-100 clearfix d-md-none" />

          <!-- Grid column -->
          <div class="col-md-4 col-lg-3 col-xl-3 mx-auto mt-3">
            <p>
              <a class="text-white">New Mexico</a>
            </p>
            <p>
              <a class="text-white">East Bay</a>
            </p>
            <p>
              <a class="text-white">Jakarta</a>
            </p>
            <p>
              <a class="text-white">New Orleans</a>
            </p>
            <p>
              <a class="text-white">Long Beach</a>
            </p>
          </div>
          <!-- Grid column -->
        </div>
        <!--Grid row-->
      </section>
      <!-- Section: Links -->

      <hr class="my-3">

      <!-- Section: Copyright -->
      <section class="p-3 pt-0">
        <div class="row d-flex align-items-center">
          <!-- Grid column -->
          <div class="col-md-7 col-lg-8 text-center text-md-start">
            
          </div>
         
          <!-- Grid column -->
        </div>
      </section>
      <!-- Section: Copyright -->
    </div>
    <!-- Grid container -->
  </footer>
  <!-- Footer -->
</div>
<!-- End of .container -->


<!-- Remove the container if you want to extend the Footer to full width. -->
<div class="footer2container  my-">

  <footer class="text-center text-lg-start  mt-xl-5 pt-4">
  <!-- Grid container -->
  <div class="container p-4">
    <!--Grid row-->
    <div class="footer2 row">
      <!--Grid column-->
      <div class="col-lg-3 col-md-6 mb-4 mb-lg-0">
        <h5 class="text-sentencecase mb-4">Company</h5>

        <ul class="list-unstyled mb-4">
          <li>
            <a href="#!" class="text-white">About us</a>
          </li>
          <li>
            <a href="#!" class="text-white">Team</a>
          </li>
          <li>
            <a href="#!" class="text-white">Careers</a>
          </li>
          <li>
            <a href="#!" class="text-white">Blog</a>
          </li>
        </ul>
      </div>
      <!--Grid column-->

      <!--Grid column-->
      <div class="col-lg-3 col-md-6 mb-4 mb-lg-0">
        <h5 class="text-sentencecase mb-4">Contact</h5>

        <ul class="list-unstyled">
          <li>
            <a href="#!" class="text-white">Help & Support</a>
          </li>
          <li>
            <a href="#!" class="text-white">Partner with us</a>
          </li>
          <li>
            <a href="#!" class="text-white">Ride with us</a>
          </li>
        </ul>
      </div>
      <!--Grid column-->

      <!--Grid column-->
      <div class="col-lg-3 col-md-6 mb-4 mb-lg-0">
        <h5 class="text-sentencecase mb-4">Legal</h5>

        <ul class="list-unstyled">
          <li>
            <a href="#!" class="text-white">Terms & Conditions</a>
          </li>
          <li>
            <a href="#!" class="text-white">Refund & Cancellation</a>
          </li>
          <li>
            <a href="#!" class="text-white">Privacy Policy</a>
          </li>
          <li>
            <a href="#!" class="text-white">Cookie Policy</a>
          </li>

        </ul>
      </div>
      <!--Grid column-->

      <!--Grid column-->
      <div class="col-lg-3 col-md-6 mb-4 mb-lg-0">
        <h6 class="text-sentencecase mb-4">Receive exclusive offers in your mailbox</h6>

        <div class="form form-outline  mb-4">
          <input type="email" id="form5Example2" placeholder="Enter Your Email Address" class="form-control" />
          <label class="form-label" for="form5Example2"></label>
        </div>

        <button type="submit" class="btn btn-warning btn-block subscribeBtn">Subscribe</button>
      </div>
      <!--Grid column-->
    </div>
    <!--Grid row-->
  </div>
  <!-- Grid container -->

  <!-- Copyright -->
  <div class="copyrightDiv text-center p-3 ">
    © 2023 Copyright:
    <a class="text-white" >Muhammad Taha Talib</a>
  </div>
  <!-- Copyright -->
</footer>

</div>
<!-- End of .container -->


</body>
</html>
