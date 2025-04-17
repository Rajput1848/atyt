<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>No1Shop - हमारी ऑनलाइन शॉप</title>

    
    
    <link rel="stylesheet" href="styles.css"><!--Extrnal css file link-->
<style>
    /*basic styling */
    body {
        font-family: Arial, sans-serif ;
        margin: 0;
        padding: 0;
        background-color: #f8f8f8;
    }
   header{
       background-color: #333;
       color: white;
       padding: 15px;
       text-align: center;
   }
    nav ul{
       list-style: none;
       padding: 0;

   }
   nav ul li{
    display: inline;
    margin: 015px;
   }
   nav ul li a.{
    
    
    color: white;
    text-decoration: none;
   }

   .product-container{
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    padding: 20px;
   }
.product{
    background-color: white;
    padding: 20px;
    margin: 10px;
    width: 250px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0,1);
    text-align: center;
}
.product{
    width: 100;
    height: auto;
    border-radius: 8px;
}
.product h3{
    font-size: 1.2;
    margin: 10px 0;

}
.product p{
    font-size: 1em;
    color: #777;

}
.price{
    font-size: 1,4em;
    color: #333;
    margin: 10px 0;
}
.price{
    
    border: none;
    padding: 10px;
    font-size: 1.5em;
    border-radius: 5px;
    margin: 7px;
}
.अभी-बुक-करें{
background-color: #4caf50;
color: white;
border: none;
padding: 10px;
font-size: 1em;
cursor: pointer;
border-radius: 5px;
}
.अभी-बुक-करें:hover{
background-color: #45a049;
}
footer{
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
    width: 100%;
    bottom: 0;
}

    

    
</style>

</head>


<body>
    <!-- Header Section-->
     <header>
        <h1>स्वागत है मेरी ईकॉमर्स वेबसाइट पर</h1>
        <nav>
            <ul>
                <li><a href="#" style="color: white;">HOME</a></li>
                <li><a href="#Products" style="color: white;">उत्पाद</a></li>
                <li><a href="#contact"></a>संपर्क करें</a></li>

         </ul>
        </nav>
     </header>
    <!-- product display section-->
     <main id="product">
     <h2 style="text-align:center ;">हमारा प्रमुख उत्पाद:Drone</h2>
      <div class="product-container">
        <!-- Drone Product -->
    <div Class="product">
        
        <a href="https://ibb.co/93c6WW3s"><img src="https://i.ibb.co/wrBV44rM/41.jpg" alt="41" border="0" width="300:height300"></a>
        
        <h3>DRONE</h3>
        <p>यह उच्च गुणवत्ता वाला ड्रोन है, जो कैमरे और उच्च उड़ान क्षमता के साथ आता है। यह आपके एडवेंचर और फ़ोटोग्राफ़ी अनुभव को बढ़ाता है।</p>
        
  <!-- Offer Banner -->
  <div class="offer-banner">
    🔥 स्पेशल ऑफर: अभी सिर्फ ₹750 में! 🔥
  </div>

  <!-- Baaki content yahaan aayega -->


    <div class="price">₹ 750</div>
    <a href="form.html">
    <button class="अभी-बुक-करें" onclick="c:\html">अभी-बुक-करें</button>
    </a>
    </div>
      </div>
     </main>

<!-- contact Info Section-->
 <section id="contact"class="contact-onfo" style="background-color: gainsboro;">
<h3 style="text-align: center;">संपर्क जानकारी</h3>
<p style="text-align: center;"><strong>फोन नंबर:</strong>8816085313</p>
<p style="text-align: center;"><strong>ईमेल.</strong><a href="mailto:ar3434613@gmail.com" style="color: black">ar3434613@gmail.com</a></p>
<p style="text-align: center;" sty><strong>पता:</strong>New Delhi</p>

 </section>

<!-- Footer Section-->
 <footer>
    <p>&copy; 2025 मेरी ईकॉमर्स वेबसाइट. सभी अधिकार सुरक्षित हैं.</p>

 </footer>


</body>
</html>
