<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="https://unpkg.com/feather-icons/dist/feather.min.css">
    <title>Your Purchase</title>
    <style>
        
        html{
            margin: 0;
            display: flex;
            justify-content: center;
        }
        body{
            margin: 0;
            width: 40%;
            font-family: Arial, sans-serif;
        }
        body header
        {
            background-color:#F7FBFC ; 
            padding-top: 30px;
            
        }
        .icon{
            font-size: 50px;
        }
        .message
        {
            text-align: center;
        }
        .customer_information{
            display: flex;
            justify-content: space-around;
            
        }
        
         p{
            color: #333;
            line-height: 2px;
        }
        button{
            color: #eeee;
            background-color: #000000;
            padding: 15px;
            margin-top: 10px;
            border-radius: 5px;
            cursor: pointer;
            border: none;
        }
        button:hover{
            background-color: #333;
        }
        hr{
            margin: 20px 0;
            height: 3px;
            background-color: #ebeeee;
            border: none;
        }
        .summary{
            text-align: center;
        }
        .orders{
            margin: 0;
            display: flex;
            align-items: center;
            
        }
        .orders img{
            max-width: 100px;
            margin-right: 20px;
        }
        .description{
            flex-grow: 1;
        }
        .description span{
            color:#8C95A0 ;
        }
        #total{
            display: flex;
            justify-content: flex-end;
        }
        #totals{
            text-align: center;
        }
        #totals span{
            margin-left: 50px;
            margin-right: 50px;
            text-align: right;
        }
        #total_price{
            font-weight: bold;
        }
        #total_price span{
            
            margin-left: 70px;
        }
        footer{
            background-color: #F7FBFC;
            margin-top: 10px;
            border-radius: 5px;
        }
        footer div{
            text-align: center;
            padding-top: 10px;
        }
        footer p{
            line-height: 20px;
            color: #000000;
        }
        .link a{
            font-size: xx-large;
            margin-bottom: 10px;
            text-decoration: none;
        }

        @media only screen and (max-width: 1070px) {
            body {
                width: 90%; /* Adjust as needed for smaller screens */
            }
            .message {
                text-align: center;
            }
    
            .message p {
                line-height: 1.5;
            }
            .customer_information {
                flex-direction: column;
                text-align: center;
            }
    
            .customer_information div {
                margin-bottom: 20px;
            }
    
            .orders {
                flex-direction: column;
            }
    
            .orders img {
                max-width: 40%;
                margin-right: 0;
                margin-left: 30%;
                
            }
    
            #total {
                flex-direction: column;
            }
    
            #totals span {
                margin-left: 0;
                margin-right: 0;
                text-align: center;
            }
    
            #total_price span {
                margin-left: 0;
                text-align: center;
            }
        }
        
        
    </style>
    </html>
</head>
<body>
    <header>
        <section class="message">
            <!-- <i class="fa fa-shopping-cart icon" aria-hidden="true"></i> -->
            <i data-feather="shopping-cart" style="width: 40px; height: 36px; color: #3498db;"></i>
            <h1>Thank you for your purchase</h1>
            <p>Hi "his name", we'er getting your order ready to be shipped.</p>
            <p>We will notify you when it has been sent.</p>
            <button>View more order</button>
        </section>
        <hr class="hr">
        <section class="customer_information">
            <div>
                <h3>Shipping address</h3>
                <p>Steve Shipper</p>
                <p>Shipping Company</p>
                <p>2261 Market Street #4667</p>
                <p>San Francisco CA 94114</p>
            </div>
            <div>
                <h3>Payment method</h3>
                <p>VISA Ending in 123 - $38.90</p>
            </div>
        </section>
    </header>
    <main>
    
    <h3 class="summary">Order summary</h3>
    <hr>
    <section class="orders">
        <div class="image">
            <img src="https://upload.wikimedia.org/wikipedia/en/a/af/WSC_Logo_notext.png" alt="image">
        </div>
        <div class="description">
            <h3>Blender Machine <span>x1</span></h3>
            <p>Lorem, ipsum dolor sit amet</p>
            <p>consectetur adipisicing elit. </p>
        </div>
        <div class="price">
            <h3>$65.95</h3>
        </div>
    </section>
    <hr>
    <section class="orders">
        <div class="image">
            <img src="https://upload.wikimedia.org/wikipedia/en/a/af/WSC_Logo_notext.png" alt="image">
        </div>
        <div class="description">
            <h3>Blender Machine <span>x1</span></h3>
            <p>Lorem, ipsum dolor sit amet</p>
            <p>consectetur adipisicing elit. </p>
        </div>
        <div class="price">
            <h3>$<s>107.95</s></h3>
            <p>$99.95</p>
        </div>
    </section>
    <hr>
    <section id="total">
        <div id="totals">
            <p>Subtotal <span>$165.9 </span></p>
            <p>Shipping <span>$10.00 </span></p>
            <hr>
            <p id="total_price">Total <span>$175.9</span></p>
        </div>
    </section>
    </main>
    <footer>
        <div>
            <p>
                if you have any questions, reply to this <br>email or <b>contact us at</b> abc@gmail.com <br>2261 Market Street #4667 San Francisco, CA 94114
            </p>
            <div class="link">
            <a href="#" class="fa fa-facebook-square"></a>
            <a href="#" class="fa fa-twitter-square"></a>
            <a href="#" class="fa fa-linkedin-square"></a>
            <a href="#" class="fa fa-instagram" style="color: red;"></a>
            </div>
        </div>
    </footer>
    <script src="https://unpkg.com/feather-icons/dist/feather.min.js"></script>
    <script>
        feather.replace();
    </script>
</body>
