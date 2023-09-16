<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amazon</title>
    <style>
        * {
    margin: 0;
    font-family: Arial;
    border: border-box;
}

.navbar {
    
    height: 83px;
    background-color: #0f1111;
    color: white;
    display: flex;
    align-items: center;
    justify-content: space-evenly;
}

.nav-logo {
    height: 100px;
    width: 100px;
}

.logo {
    background-image: url("amazonlogo.jpg");
    background-size: cover;
    padding: 5px;
    height: 80px;
    width: 100px;   
}

.nav-address {
    padding: 18px;  
}

/* for box 2 */

.add-first {
    color: #cccccc;
    font-size: 1rem;
    margin-left: 15px;
}

.add-sec {
    font-size: 1rem;
    margin-left: 3px;
}

.add-icon {
    display: flex;
    align-items: center;
}

.search {
    display: flex;
    background-color: pink;
    justify-content: space-evenly;
    width: 620px;
    height: 35px;
    border-radius: 5px;
}


.search:hover {
    border: 3px solid skyblue;
}

.search-select {
    background-color: #f3f3f3;
    width: 50px;
    text-align: center;
    border-top-left-radius: 5px;
    border-bottom-left-radius: 5px;
    border: none;
}

.search-input {
    width: 100%;
    font-size: 1rem;
    border: none;
}

/* Box 3 */

.search-icon {
    width: 45px;
    align-items: center;
    justify-content: center;
    display: flex;
    background-color: rgb(225, 157, 11);
    border-top-right-radius: 5px;
    border-bottom-right-radius: 5px;
    color: black;
}
/* Box 4 */

span {
    font-size: .7rem;
}

.nav-second {
    font-size: 0.85rem;
    font-weight: 600;
}   
/* box 6 */

.nav-cart i {
    font-size: 30px;
}

.nav-cart {
    font-size: 1rem;
}


/* panel */

.panel  {
    height: 40px;
    background-color: #190a3b;
    display: flex;
    color: white;
    align-items: center;
    justify-content: space-evenly;
}

.panel-opt p {
    display: inline;
    margin: 5px;
}

.panel-opt {
    width: 70%;
    font-size: .85rem;
}

.panel-deals {
    font-size: 1rem;
}


/* Hero section */
.hero-section {
    background-image: url("Boat.jpg");
    background-size: cover;
    height: 330px;
}

/* Shop-section*/

.shop-section {
    display: flex;
    justify-content: space-evenly;
    background-color: #e4eeec;
}

.box {
    /* border: 2px solid black; */
    height: 400px;
    width: 23%;
    background-color: white;
    padding: 20px 0px 15px;
    margin-top: 20px;
}

.box-img {
    height: 310px;
    background-size: cover;
    margin-top: 1rem;
    margin-bottom: 1rem;
}

.box-content {
    margin-left: 1rem;
    margin-right: 1rem;
}

.box-content p {
    color: rgb(19, 144, 102);
}
/* Footer*/

footer {
    margin-top: 50px;
}

.foot-panel1 {
    background-color: #37475a;
    color: white;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 0.85rem;
}


.fot-panel2 {
    background-color: rgb(3, 40, 42);
    color: white;
    height: 300px;
    display: flex;
    justify-content: space-evenly;
} 

ul {
    margin-top: 30px;
}

ul a {
    display: block;
    font-size: .9rem;
    margin-top: 10px;
    color: aqua;
}
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="">
</head>
<body>
    <header>
        <div class="navbar">
            <div class="nav-logo border">
                <div class="logo">
                </div>
            </div>

            <div class="nav-address">
                <p class="add-first">Deliver to</p>
                <div class="add-icon">
                    <i class="fa-solid fa-location-dot"></i>
                    <p class="add-sec">India</p>
                </div>
            </div>

            <div class="search">
                <select class="search-select">
                    <option>All</option>
                </select>
                <input placeholder="Search Amazon" class="search-input">
                <div class="search-icon">
                    <i class="fa-solid fa-magnifying-glass"></i>
                </div>
            </div>

            <div class="nav-sigin">
                <p> <span> Hello, Sign in</span></p>
                <p class="nav-second"> Account & Lists </p>
            </div>

            <div class="nav-sigin">
                <p> <span> Return </span></p>
                <p class="nav-second"> & Orders </p>
            </div>

            <div class="nav-cart border">
                <i class="fa-solid fa-cart-plus"></i>
              Cart 
             </div>
        </div>

        <div class="panel">
            <div class="panel-all">
                <i class="fa-solid fa-bars"></i>
                All
            </div>
            <div class="panel-opt">
                <p>Today's Deal</p>
                <p>Amazon miniTV</p>
                <p>Best sellers</p>
                <p>Electronics</p>
                <p>Gadgets</p>
                <p>Mobile Phones</p>
                <p>New Release</p>
                <p>Customer Service</p>
                <p>Registry</p>
                <p>Gift Cards</p>
                <p>Sell</p>
            </div>
            <div class="panel-deals">
                Shop Deals in Electronics
            </div>
        </div>
    </header>
<a href="">
    <div class="hero-section">
    </div></a>
    <div class="shop-section">
        <div class="box1 box">
            <div class="box-content">
                <h3>Bluetooth Calling Watches Under Rs 999 only /- </h3>
                <a href="">
                <div class="box-img" style="background-image: url('watch.jpg');"></div></a>
                     <a href=""> <p>see more</p> </a>
            </div>
        </div>

        <div class="box2 box"><div class="box-content">
            <h3> Start Your Fitness Journey Under 99 | Get 60% offers* </h3>
            <a href="">
            <div class="box-img" style="background-image: url('fitness.jpg');"></div></a>
                 <a href=""> <p>see more</p> </a>
        </div>
    </div>

        <div class="box3 box"><div class="box-content">
            <h3> Gardening Essentials Starting from 299 only /- </h3>
            <a href="">
            <div class="box-img" style="background-image: url('Gardening.jpg');"></div></a>
                 <a href=""> <p>see more</p> </a>
        </div>
    </div>

        <div class="box4 box"><div class="box-content">
            <h3>One stop shop for all your wedding shopping </h3>
            <a href="">
            <div class="box-img" style="background-image: url('today.png');"></div></a>
                 <a href=""> <p>see more</p> </a>
                   </div>
                </div>
        </div>

        <div class="shop-section">
            <div class="box5 box">
                <div class="box-content">
                    <h3>Get Kitchen Products and Get Upto 70% Offers* </h3>
                    <a href="">
                    <div class="box-img" style="background-image: url('kitchen.jpg');"></div></a>
                         <a href=""> <p>see more</p> </a>
                </div>
            </div>
    
            <div class="box6 box"><div class="box-content">
                <h3> Leaked | Watch Now Only on miniTV </h3>
                <a href="">
                <div class="box-img" style="background-image: url('miniTV.jpg');"></div></a>
                     <a href=""> <p>see more</p> </a>
            </div>
        </div>
    
            <div class="box3 box"><div class="box-content">
                <h3> Mega Fashion Days | Under ₹699 | Amazon brands & more</h3>
                <a href="">
                <div class="box-img" style="background-image: url('shirt.jpg');"></div></a>
                     <a href=""> <p>see more</p> </a>
            </div>
        </div>
    
            <div class="box4 box"><div class="box-content">
                <h3>Make Your Home Galaxy </h3>
                <a href="">
                <div class="box-img" style="background-image: url('decor.jpg');"></div></a>
                     <a href=""> <p>see more</p> </a>
                       </div>
                    </div>
            </div>

            <footer>
                <div class="foot-panel1">
                    Back to Top
                </div>
                <div class="fot-panel2">
                 <ul>
                        <p>Get to Know Us</p>
                           <a> About Us </a>
                            <a>Carrer</a>
                            <a>Press Release</a>
                            <a>Amazon science</a>
                    </ul>
                    <ul>
                        <p>Get to Know Us</p>
                           <a> About Us </a>
                            <a>Carrer</a>
                            <a>Press Release</a>
                            <a>Amazon science</a>
                    </ul>
                    <ul>
                        <p>Get to Know Us</p>
                           <a> About Us </a>
                            <a>Carrer</a>
                            <a>Press Release</a>
                            <a>Amazon science</a>
                    </ul>
                    <ul>
                        <p>Get to Know Us</p>
                        <a> About Us </a>
                         <a>Carrer</a>
                         <a>Press Release</a>
                         <a>Amazon science</a>
                    </ul>
                </div>
            </footer>
</body>
</html>
