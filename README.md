
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width,initial-scale=0.1">

</head>
<body>

<header style="background-color: hsl(215, 44%, 89%);">
      <h1 style="font-size: 500%;">KroShet<span>.</span></h1>
      <nav>
          <div class="nav-links" id="navLinks">
           <h1 onclick="hideMenu()"><i class="fa-solid fa-times"></i></h1>
            <ul>
               <li><a href="#home"><button class="button1">HOME</button></a></li>
               <li><a href="#about"><button class="button1">ABOUT</button></a></li>
               <li><a href="#products"><button class="button1">PRODUCTS</button></a></li>
               <li><a href="#review"><button class="button1">REVIEW</button></a></li>
               <li><a href="#contact"><button class="button1">CONTACT</button></a></li>
               <a href="#contact"><button class="button5"><i class="fa-solid fa-user"></i></button></a>
               <a href="#cart"><button class="button5"><i class="fa-solid fa-cart-shopping"></i></button></a>
               <a href="#footer"><button class="button5"><i class="fa-solid fa-phone"></i></button></a>
            </ul>
         </div>
         <h1 onclick="showMenu()"><i class="fa-solid fa-bars"></i></h1>
      </nav>

</header>

<!---home section starts--->

<section class="home" id="home">

   <div class="content">
      <h2>Made Just For You</h2>
      <span>-Handmade by Shanaia-</span>
      <P>This webpage allows you to buy our products</P>
      <a href="#products" class="button2">Shop Now</a>
   </div>

</section>
<!---home section ends--->

<!---about section starts--->

<section class="about" id="about">
   <h1 class="heading"> <span> About</span> Us </h1>

   <div class="row">

      <div class="image-container">
         <img src="https://scontent.xx.fbcdn.net/v/t1.15752-9/434832382_390208403835304_1849855060679512844_n.jpg?stp=dst-jpg_p206x206&_nc_cat=110&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeGkx9-bwzVfb1ho4Tdc61U_ytjwNSgt5FDK2PA1KC3kUMezhD4DhaRO9STEUqQu2MNXVbW2-LGPi41trpk8qXHQ&_nc_ohc=JvzBrjODpYkAb5G4eWh&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent.xx&oh=03_AdWDQetXyZt6II8dl63723q5-Q2ylNtiDLMdBqS27BdR4A&oe=663CDDBD" alt="pic"></img>
         <h3>Student Crocheter</h3>
      </div>

      <div class="content">
         <h3>Why choose us?</h3>
         <p>Handycraft is the best remedy for everybodys stress in everyday life.  With that, KroShet was made.

            At first, it's only for leizure and hobby.  Until someones noticed that we are makng lovely items and order to us.

            Now,  we are making handmade crochet items like different flowers, wallets, bags, stuff toys and many more.</p>
         <a href="#" class="button3">learn more</a>
      </div>

   </div>
</section>

<!---about section ends--->

<!---product section starts--->

<section class="products" id="products">

   <h1 class="heading"> Latest <span>Products</span> </h1>

   <div class="box-container">

      <div class="box">
            <div class="image">
               <img src="https://scontent.xx.fbcdn.net/v/t1.15752-9/434827638_881443103750250_5729044630470401261_n.jpg?stp=dst-jpg_p206x206&_nc_cat=100&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeGfqZc0LpUGXBxFloOfTM2VdaWzaa_peKN1pbNpr-l4o5dJ6NATSfexLp6krr43mopN01ee8TPzcU2rZiNHJFTH&_nc_ohc=sdWjPM3NUYEAb76p9Wm&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent.xx&oh=03_AdXv9UuzFg02LAsb4Mj-b2qdze35CM-q9FyCk8R__dNl7w&oe=663C0417" alt="rose pins" width="200px" height="200px">
               <div id="item1"></div>
               <div class="icons">
                  <a href="#" class="fas fa-heart"></a>
                  <a href="#" class="cart-btn" onclick="addToCart(item1)">add to cart</a>
                  <a href="#" class="fas fa-share"></a>
                  </div>
               </div>
            <div class="content">
               <h2>ROSE BROOCH PINS</h2>
               <div class="price"> ₱50 <span> ₱55 </span> </div>
         </div>
      </div>

      <div class="box">
            <div class="image">
               <img src="https://scontent.xx.fbcdn.net/v/t1.15752-9/434891784_243198802147545_5536717637926183644_n.jpg?stp=dst-jpg_p206x206&_nc_cat=107&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeGlecLru4HBgrksxP9XYdFZ1I_IACMKod7Uj8gAIwqh3rwoJi1q6rPUq0794_2r2fgR0T9491PsrXcs1r5qRP_1&_nc_ohc=vHmNeF634CIAb74T60l&_nc_oc=AdhYD-vxi9HVSAItcAmAV9jRgwSNcHYSWRVrnz9iUNzWS5CUqt2xSwN-JQuPPS15mZsP_TbaooPh45EDg2t9_-gK&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent.xx&oh=03_AdW0YH_imuorCnDiy32dummdf5BTzvyZtl0LrP1NsXSAHw&oe=663BF7A2" alt="tulips & lavender" width="200px" height="200px">
               <div class="icons">
                  <a href="#" class="fas fa-heart"></a>
                  <a href="#" class="cart-btn">add to cart</a>
                  <a href="#" class="fas fa-share"></a>
               </div>
            </div>
         <div class="content">
            <h2>TULIPS AND LAVENDERS</h2>
            <div class="price"> ₱100 <span> ₱120 </span> </div>
         </div>
      </div>

      <div class="box">
            <div class="image">
               <img src="https://scontent.xx.fbcdn.net/v/t1.15752-9/434903729_308578668715202_3855147007892353315_n.jpg?stp=dst-jpg_p206x206&_nc_cat=105&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeEne_SXX2sVf2jCt_ICDQW4dew9jGJDA7p17D2MYkMDuhgOWGHeDuzM_e0mqYvPh86SKuCR8M2OUT_zpxjNE3ea&_nc_ohc=smOsGj9-vnQAb5aQ22g&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent.xx&oh=03_AdUHPR023c0QiupBMGTcQyqqR6w69BvEukBVRDqNHkVs9A&oe=663C11EA" alt="hearts" width="200px" height="200px">
               <div class="icons">
                  <a href="#" class="fas fa-heart"></a>
                  <a href="#" class="cart-btn">add to cart</a>
                  <a href="#" class="fas fa-share"></a>
               </div>
            </div>
         <div class="content">
            <h2>HEART KEYCHAINS</h2>
            <div class="price"> ₱20 <span> ₱25 </span> </div>
         </div>
      </div>

      <div class="box">
            <div class="image">
               <img src="https://scontent.fmnl14-1.fna.fbcdn.net/v/t1.15752-9/434825502_396141133337746_6433347102719241880_n.jpg?stp=dst-jpg_p206x206&_nc_cat=107&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeHt4hdre_THQGgq94t3vj61r5p5QS-pG1mvmnlBL6kbWddcXEnLmoIBL25UAhNuvkkzRD2miSKhr-QMrhTslVg3&_nc_ohc=UCvsm54oiJwAb5Y6iy2&_nc_ht=scontent.fmnl14-1.fna&oh=03_AdXvDHz5BlKTYHaZcg7Uy650hj9FomVaoRtLpoWx-dRXBw&oe=663C1A22" alt="tulips" width="200px" height="200px">
               <div class="icons">
                  <a href="#" class="fas fa-heart"></a>
                  <a href="#" class="cart-btn">add to cart</a>
                  <a href="#" class="fas fa-share"></a>
               </div>
            </div>
         <div class="content">
            <h2>TULIP KEYCHAINS</h2>
            <div class="price"> ₱50 <span> ₱55 </span> </div>
         </div>
      </div>

      <div class="box">
            <div class="image">
               <img src="https://scontent.xx.fbcdn.net/v/t1.15752-9/433856845_988940346182953_2490407180261103679_n.jpg?stp=dst-jpg_p206x206&_nc_cat=104&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeGw6PHmPCFZIjsRTX-2aFBED33SM2IkDCkPfdIzYiQMKRGznAk2XCmyMTIEF6MhB_cDdS9LFAIY5im257_FT54J&_nc_ohc=XocufKQx3iEAb7xbm7N&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent.xx&oh=03_AdWaSUtieG0DJEptdQyw3lzfYbzsn2PjH7Qs-XgcRSnT4w&oe=663C12D7" alt="forgetmenot flowers" width="200px" height="200px">
               <div class="icons">
                  <a href="#" class="fas fa-heart"></a>
                  <a href="#" class="cart-btn">add to cart</a>
                  <a href="#" class="fas fa-share"></a>
               </div>
            </div>
         <div class="content">
            <h2>FORGET-ME-NOT FLOWERS</h2>
            <div class="price"> ₱120 <span> ₱140 </span> </div>
         </div>
      </div>

      <div class="box">
            <div class="image">
               <img src="https://scontent.xx.fbcdn.net/v/t1.15752-9/435139328_3753865974846046_6936299184396270669_n.jpg?stp=dst-jpg_p206x206&_nc_cat=108&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeGuFYQbk6TUGJWzCTjNx_9TAGkMEhpa0lkAaQwSGlrSWWy7hSooSFmzWvGKo0r2mdtx1B_K_rbjYCQ_EyGAAkAt&_nc_ohc=0Ixq9CM3DuUAb48pKIm&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent.xx&oh=03_AdXpJS2i6F-7FLjvKZAwV7MJ8kWI9V57i5c4iJozA6s8nQ&oe=663C245A" alt="dino" width="200px" height="200px">
               <div class="icons">
                  <a href="#" class="fas fa-heart"></a>
                  <a href="#" class="cart-btn">add to cart</a>
                  <a href="#" class="fas fa-share"></a>
               </div>
            </div>
         <div class="content">
            <h2>DINOSAUR</h2>
            <div class="price"> ₱350 <span> ₱400 </span> </div>
         </div>
      </div>

      <div class="box">
            <div class="image">
               <img src="https://scontent.fmnl14-1.fna.fbcdn.net/v/t1.15752-9/433830411_798058081739898_5657188024988365264_n.jpg?stp=dst-jpg_s417x417&_nc_cat=109&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeEzq6GBza7ItFTmdMX3lD_a0vjT4QBreUvS-NPhAGt5SwVrPkA6ImBhGN6UMNSPi7WbG5bIIN0HFkhdGrkwVeew&_nc_ohc=U06BMWkeXe0Ab60Sa1K&_nc_ht=scontent.fmnl14-1.fna&oh=03_AdXX87jhDZbtYQQyAYS8MPk3NWrlYC2q89vaY_EBTyMeYg&oe=663C1695" alt="headband" width="200px" height="200px">
               <div class="icons">
                  <a href="#" class="fas fa-heart"></a>
                  <a href="#" class="cart-btn">add to cart</a>
                  <a href="#" class="fas fa-share"></a>
               </div>
            </div>
         <div class="content">
            <h2>HEADBAND</h2>
            <div class="price"> ₱100 <span> ₱120 </span> </div>
         </div>
      </div>

      <div class="box">
            <div class="image">
               <img src="https://scontent-sin6-4.xx.fbcdn.net/v/t1.15752-9/438238498_1100621117659709_3160105877277882183_n.jpg?stp=dst-jpg_p206x206&_nc_cat=101&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeGb45avGq9h7lnkwQ7GqkCXXdHgq0v6-Ghd0eCrS_r4aF79J0RiugUoium7ddAqSElIC3we6HImQsZa_b8NF3FJ&_nc_ohc=B894NFr1DncAb61tgD6&_nc_ht=scontent-sin6-4.xx&oh=03_AdUUhEYW5dUskpQT9czrqlx8csx50Ry0iztpsCXvhdo1tQ&oe=664332A8" alt="coaster" width="200px" height="200px">
               <div class="icons">
                  <a href="#" class="fas fa-heart"></a>
                  <a href="#" class="cart-btn">add to cart</a>
                  <a href="#" class="fas fa-share"></a>
               </div>
            </div>      
         <div class="content">
            <h2>BOQUET COASTER</h2>
            <div class="price"> ₱60 <span> ₱80 </span> </div>
         </div>
      </div>

      <div class="box">
         <div class="image">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQUaaYbPWhy6dCWPDFfWWtePLAWvdclcdvOK_j00eHOsg&s" alt="mushroom" width="200px" height="200px">
            <div class="icons">
               <a href="#" class="fas fa-heart"></a>
               <a href="#" class="cart-btn">add to cart</a>
               <a href="#" class="fas fa-share"></a>
            </div>
         </div>      
      <div class="content">
         <h2>MUSHROOM KEYCHAIN</h2>
         <div class="price"> ₱30 <span> ₱40 </span> </div>
      </div>
   </div>

   </div>   

</section>

<!---product section ends--->

<!---review section starts--->

<section class="review" id="review">

   <h1 class="heading"> Costumer's <span> Review </span></h1>

   <div class="box-container">

     <div class="box">
        <div class="stars">
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
         </div>
         <p>I loved it, it's a beautiful decoration at home</p>
         <div class="user">
            <img src="https://scontent.xx.fbcdn.net/v/t1.15752-9/365575098_6718787981546398_6069969873376224953_n.jpg?stp=dst-jpg_p206x206&_nc_cat=103&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeEK-SxhQQ7fVe1WpqrRsLRQ0lXB6lqDbbjSVcHqWoNtuLMj0WSlsuLbe00YKXYfI-kx3iMwWbGCxxzYC9owPS8a&_nc_ohc=cAM3Bidx3aIQ7kNvgE63UA1&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent.xx&oh=03_Q7cD1QERCklHaXuIqjYm7zF0aWp93HPd9fvpK-F8eb95ZNaV5g&oe=665C45B0" alt="pfp">
            <div class="user-info">
               <h3>Mimi</h3>
               <span>happy customer</span>
            </div>
         </div>
         <span class="fas fa-quote-right"></span>
      </div>

      <div class="box">
         <div class="stars">
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
         </div>
         <p>Beautiful</p>
         <div class="user">
            <img src="https://scontent.xx.fbcdn.net/v/t1.15752-9/367704438_305227965514453_5776387803873321718_n.jpg?stp=dst-jpg_p206x206&_nc_cat=101&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeE3Cw4UAi-_CRhxC4n6l4UR3YESJF8LDlLdgRIkXwsOUjki8tDzmPb8lPTWOIHCCYRQcG5YoXAc2tJY9yPGZNIs&_nc_ohc=T3ITGr7MAo8Q7kNvgHleK87&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent.xx&oh=03_Q7cD1QFebS5vE_GKZiDKMo93xc8dvfC1fYMzBb7eO9aDSAYJVQ&oe=665C4259" alt="pfp">
            <div class="user-info">
               <h3>Keshi_</h3>
               <span>happy customer</span>
            </div>
         </div>
         <span class="fas fa-quote-right"></span>
      </div>

      <div class="box">
         <div class="stars">
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
        </div>
        <p>The way you made it is so nice</p>
        <div class="user">
           <img src="https://scontent.xx.fbcdn.net/v/t1.15752-9/356576486_799723468490746_7090014758369815655_n.jpg?stp=dst-jpg_p206x206&_nc_cat=104&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeHnGW25AdTKFmJTouxhG-5TqJGLHIQ6NUKokYschDo1Ql3VOTPgJjAzaLzzEmPSA9HESV5wuAiGAQ5ze3t0XlP8&_nc_ohc=aQoaB_pw558Q7kNvgHLrrnX&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent.xx&oh=03_Q7cD1QG9GY4MtoERVbCpNZQfxEtD4RfnCmzsK4z8a-x6TNyBtg&oe=665C30EA" alt="pfp">
            <div class="user-info">
               <h3>Tintin</h3>
               <span>happy customer</span>
            </div>
         </div>
         <span class="fas fa-quote-right"></span>
      </div>

      <div class="box">
         <div class="stars">
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
        </div>
        <p>NICEEEEE</p>
        <div class="user">
           <img src="https://scontent.fmnl33-2.fna.fbcdn.net/v/t1.15752-9/356477626_654766829910435_3137986050197847107_n.jpg?stp=dst-jpg_p206x206&_nc_cat=111&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeGiJsxXtKVLp-_MOewKlhhyqiielUxGt4SqKJ6VTEa3hL1sAs7GP3AjlovCHrIhp0uiyPtPK59aijm_B_bEVPPV&_nc_ohc=3Z7SULD6B9sQ7kNvgFoc58P&_nc_ht=scontent.fmnl33-2.fna&oh=03_Q7cD1QGGbJk5jJKGhnTPijzViqZGRpIE-o70fLZAuK9Io6LZCQ&oe=665B3245" alt="pfp">
            <div class="user-info">
               <h3>Beomgyu</h3>
               <span>happy customer</span>
            </div>
         </div>
         <span class="fas fa-quote-right"></span>
      </div>

      <div class="box">
         <div class="stars">
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
        </div>
        <p>I like how you made it</p>
        <div class="user">
           <img src="https://scontent.fmnl33-6.fna.fbcdn.net/v/t1.15752-9/440356197_453299667146136_608961050259834957_n.jpg?stp=dst-jpg_p206x206&_nc_cat=109&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeEvGZezYDmGke99rFOdPk_2WzC-17xpj99bML7XvGmP3xS45TLMe9oa-2zWTrlfFYnjXxlIayPXitamTUCTJKtz&_nc_ohc=MHOITwZZLPEQ7kNvgEwznmF&_nc_ht=scontent.fmnl33-6.fna&oh=03_Q7cD1QFiXOEkmdYarjVAcmqBtm-tDn6VvCZq6SCiny0xDJpBYA&oe=665B2D60" alt="pfp">
            <div class="user-info">
               <h3>Kai_meeeee</h3>
               <span>happy customer</span>
            </div>
         </div>
         <span class="fas fa-quote-right"></span>
      </div>

      <div class="box">
         <div class="stars">
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
        </div>
        <p>SHE LIKED ITTTT</p>
        <div class="user">
           <img src="https://scontent.fmnl33-5.fna.fbcdn.net/v/t1.15752-9/344292397_190495737264127_6041877201457094155_n.jpg?stp=dst-jpg_p206x206&_nc_cat=102&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeHgBgbJBK-c1JvoLWcJvD3ByWf8RJMkLDfJZ_xEkyQsN3tYukzlAChGUA4cfAlIyMjfODEH4HMIzbFTM6xKyg_-&_nc_ohc=bMu5dJRBGCQQ7kNvgHf7Ryl&_nc_ht=scontent.fmnl33-5.fna&oh=03_Q7cD1QFi1H_ppJEPcDlSWomDBeAdWaG_rimbZPkRPS6wZhJbmg&oe=665B2DA3" alt="pfp">
            <div class="user-info">
               <h3>Han_Jisung</h3>
               <span>happy customer</span>
            </div>
         </div>
         <span class="fas fa-quote-right"></span>
      </div>

   </div>

</section>

<!---review section ends--->

<!---contact section starts--->

<section class="contact" id="contact">

   <h1 class="heading"> Contact <span> Us </span> </h1>

   <div class="row">

      <form actions="">
         <input type="text" placeholder="name" class="box">
         <input type="email" placeholder="email" class="box">
         <input type="number" placeholder="number" class="box">
         <textarea name="" class="box" placeholder="message" id="" cols="30" rows="10">
         </textarea>
         <input type="submit" value="send message" class="button4">
      </form>

      <div class="image">
         <img src="https://scontent.xx.fbcdn.net/v/t1.15752-9/438203981_7617106571673615_3688751262025994305_n.jpg?stp=dst-jpg_p206x206&_nc_cat=102&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeHFnXgGQV4tRb27DzuYr5xyY1N1UR8HnB5jU3VRHwecHmW4YJMMMiP4s6FnWjxuSA-k1ozATRlEfJ2MHpVRkyP3&_nc_ohc=T67rov2vjlwAb42fvf4&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent.xx&oh=03_Q7cD1QFUbSxFFF565c2nWjZhP1mBzO78ootDWcMTz_8Cy6I0aA&oe=664EED3A" alt="kroshet">
      </div>

   </div>

</section>

<!---contact section ends--->

<!---footer section starts--->

<section class="footer" id="footer">

   <div class="box-container">

      <div class="box">
         <h3>Quick Links</h3>
         <a href="#">home</a>
         <a href="#">about</a>
         <a href="#">product</a>
         <a href="#">review</a>
         <a href="#">contact</a>
      </div>

      <div class="box">
         <h3>Extra Links</h3>
         <a href="#">my account</a>
         <a href="#">my orders</a>
         <a href="#">my favorites</a>
      </div>

      <div class="box">
         <h3>Locations</h3>
         <a href="#">Gapan</a>
         <a href="#">Waltermart, Gapan</a>
         <a href="#">Robinson, Gapan</a>
      </div>

      <div class="box">
         <h3>Contact Info</h3>
         <a href="#">09157774298</a>
         <a href="#">09674325812</a>
         <a href="#">KroShet@facebook.com</a>
      </div>

   </div>

   <div class="credit"> created by <span> Shanaia Vaness A. Cabatan </span> | all rights reserved </div>

</section>

<!---footer section ends--->

<!------Javascript for Toggle Menu------->
<script>

    var navLinks = document.getElementById("navLinks")

    function showMenu(){
      navLinks.style.right = "0"
    }
    function hideMenu(){
      navLinks.style.right = "-200px"
    }

</script>

</body>
</html>
