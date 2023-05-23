<!-- # flipkart.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flipcart test</title>
    <style>
        *{
           margin:0;
           padding:0;
        }
        #screen{
            width:100%;
            border:5px solid black;
        }
        #navbar {
        width: 100%;
        height: 40px;
        background-color: #2874f0;
        display: flex;
        justify-content: center;
        align-items: center;
        padding: 10px 0px;
    }
    #plus-color{
        color:yellow;
        font-weight: 800;
    }
    #p-expl {
        color: white;
        position: relative;
        top: -3px;

    }
    #search{
        width:400px;
        height:20px;
        padding:6px;
        margin:0px 16px;
        display: flex;
        justify-content: space-between;
        border-radius:3px;
        background-color: white;
        
    }
     #search input{
        width:380px;
        border: none;
        outline:none;
        font-size: 15px;
     }
     #loginB {
        padding: 8px 40px;
        font-size: 15px;
        font-weight:600;
        border: none;
        outline: none;
        color: blue;
    }
    #profile{
        width:30%;
        display: flex;
        justify-content: space-evenly;
        color: white;
        align-items: center;
    }
    #angle-down{
         font-size:8px;
    }
    #navbar1{
        width:100%;
        height:30px;
        display: flex;
        justify-content: space-evenly;
        border:1px solid black;
        background-color: white;
    }
    #body{
        border:1px solid red;
        width:100%;
        display: flex;
        justify-content: space-between;
        
    }
    #body>div:nth-child(1){
        width:18%;
        border: 1px solid black;
    }
    #body>div:nth-child(2){
        width:78%;
        border: 1px solid grey;
    }
    #body>div:nth-child(1)>div{
        border: 1px solid grey;
        margin-left: 20px;

    }
    #product {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            border: 1px solid grey;
        }

        #product>div {
            width: 18%;
            height: 370px;
            margin-bottom: 20px;
        }

        #product>div:hover {
            border: 1px solid black;
        }

        #product>div>img {
            width: 100%;
            height: 75%;
        }
        @media screen and (max-width:400px){
            #navbar>div:nth-child(1){
            display: block;
            margin-left: 10px;
            /* color:white; */
       
        }
        }
        


    </style>
</head>
<body>
<div>
    <div id="navbar">
        <div>
            <img src="https://static-assets-web.flixcart.com/fk-p-linchpin-web/fk-cp-zion/img/flipkart-plus_8d85f4.png"
            style="width:70%; height:20px;"/>
            <p id="p-expl">Explore
            <span id="plus-color">plus</span>
            <img src="https://static-assets-web.flixcart.com/fk-p-linchpin-web/fk-cp-zion/img/plus_aef861.png"
                    width="10px" ;height="10px" ;>
            </p>
            </div>

            <div id="search">
                <input type="search" placeholder="Search for product and more">
                <i class="fa-solid fa-magnifying-glass"></i>
            </div>

            <button id="loginB">Login</button>
        <div id="profile">
            <div>Become a Seller</div>
            <div> More
                <i class="fa-solid fa-angle-down" id="angle-down"></i>
            </div>
            <div>Cart
                <i class="fa-solid fa-cart-shopping"></i>
                
            </div>
            </div>
        </div>
        </div>
    <div id="navbar1">
        
            <div>Electronics
                <i class="fa-solid fa-angle-down "style="font-size:8px;margin-top:12px;"></i>
            </div>
            <div>TVs & Appliances
                <i class="fa-solid fa-angle-down"style="font-size:8px;margin-top:12px;"></i>
            </div>
            <div>Men
                <i class="fa-solid fa-angle-down" style="font-size:8px;margin-top:12px;"></i>
            </div>
            <div>Women
                <i class="fa-solid fa-angle-down" style="font-size:8px;margin-top:12px;"></i>
            </div>
            <div>Baby & Kids
                <i class="fa-solid fa-angle-down" style="font-size:8px;margin-top:12px;"></i>
            </div>
            <div>Home & Furniture
                <i class="fa-solid fa-angle-down" style="font-size:8px;margin-top:12px;"></i>
            </div>
            <div>Sports, Books & More
                <i class="fa-solid fa-angle-down" style="font-size:8px;margin-top:12px;"></i>
            </div>
            <div>Flights
                <i class="fa-solid fa-angle-down" style="font-size:8px;margin-top:12px;"></i>
            </div>
            <div>Offer zone
                <i class="fa-solid fa-angle-down" ;style="font-size:8px;margin-top:12px"></i>
            </div>
        
    </div>
    <div id="body">
        <!-- 1stdiv -->
        <div>
                <div>
                <h5>CATEGORIES</h5>
                <p><i class="fa-solid fa-angle-left" style="font-size:8px;margin-top:12px"></i>
                Clothing & Accessories</p>
                <h5>               
<i class="fa-solid fa-angle-down" ;style="font-size:8px;margin-top:12px"></i>
               
                Topwear</h5>
                <p>Shirt</p>
                <p>T-shirt</p>
                <p>Tops</p>
               </div>

               <div>
                <H4>GENDER
                    <i class="fa-solid fa-angle-down" ;style="font-size:8px;margin-top:12px"></i>
            
                </H4>
               </div>
        </div>
        <!-- right -->
        <div id="product">
            <div>
                <img src="https://rukminim1.flixcart.com/image/612/612/xif0q/t-shirt/j/8/l/s-vd-os-100-lt1970-sw-veirdo-original-imagp8zkf7jd5gvr.jpeg?q=70"/>
                   <h5>Shirt</h5>
                <p>Rs.299</p>
            </div>
            <div>
                <img src="https://rukminim1.flixcart.com/image/612/612/xif0q/t-shirt/s/c/p/m-db1024-15-3bros-original-imagz8zjfxthf7kn.jpeg?q=70"/>
                <h5>t-shirt</h5>
                <p>Rs.299</p>
            </div>

            <div>
                <img src="https://rukminim1.flixcart.com/image/612/612/xif0q/t-shirt/j/8/l/s-vd-os-100-lt1970-sw-veirdo-original-imagp8zkf7jd5gvr.jpeg?q=70"/>
                <h5>t-shirt</h5>
                <p>Rs.299</p>
            </div>

            <div>
                <img src="https://rukminim1.flixcart.com/image/612/612/xif0q/t-shirt/s/c/p/m-db1024-15-3bros-original-imagz8zjfxthf7kn.jpeg?q=70"/>
                <h5>t-shirt</h5>
                <p>Rs.299</p>
            </div>

            <div>
                <img src="https://rukminim1.flixcart.com/image/612/612/xif0q/t-shirt/j/8/l/s-vd-os-100-lt1970-sw-veirdo-original-imagp8zkf7jd5gvr.jpeg?q=70"/>
                <h5>Shirt</h5>
                <p>Rs.299</p>
            </div>

            <div>
                <img src="https://rukminim1.flixcart.com/image/612/612/xif0q/t-shirt/s/c/p/m-db1024-15-3bros-original-imagz8zjfxthf7kn.jpeg?q=70"/>

                <h5>Shirt</h5>
                <p>Rs.299</p>
            </div>

            <div>
                <img src="https://rukminim1.flixcart.com/image/612/612/xif0q/t-shirt/j/8/l/s-vd-os-100-lt1970-sw-veirdo-original-imagp8zkf7jd5gvr.jpeg?q=70"/>
                <h5>Shirt</h5>
                <p>Rs.299</p>
            </div>

            <div>
                <img src="https://rukminim1.flixcart.com/image/612/612/xif0q/t-shirt/s/c/p/m-db1024-15-3bros-original-imagz8zjfxthf7kn.jpeg?q=70"/>

                <h5>Shirt</h5>
                <p>Rs.299</p>
            </div>

            <div>
                <img src="https://rukminim1.flixcart.com/image/612/612/xif0q/shirt/s/u/f/s-st10-vebnor-original-imagprjgsdzafrqb.jpeg?q=70"/>
                <h5>Shirt</h5>
                <p>Rs.299</p>
            </div>
            


            
    </div>
</div>
</body>
</html>
