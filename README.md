# Landing_Page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"
  />
    <title>Animated Landing Airport page</title>

</head>
<body>
    <header>
        <nav>
            <div class="logo">
                <img src="LOGO.png" width="200">
            </div>
            <h1>FLIGHTS.COM</h1>
            <div class="menu"> 
                
                <a href="#">PKR</a>
                <a href="#">Home</a>
                <a href="#">Flights</a>
                
                <a href="#">Features</a>
                <a href="#">Booking</a>
                <a href="#">Login</a>

            </div>

        </nav>

        <div class="li">
            <div class="box1"> </div> <br>

        <div class= "box2"></div>
        <br>
        <div class = "box3"></div>
        <br>
        </div>
        
        <div class="container">
        <div class = "left animate__animated animate__zoomIn animate__delay-1s"> 
            <br>
            <h1>The Perfect place <br> for your special trip</h1>
            <br>
            <h2> Discover dreamy holiday places all over the world</h2> <br>
            <button> Find Yours </button>
            </div>
            <div class = "right animate__animated animate__zoomIn animate__delay-2s">
                <img src ="plane.JPG">
            </div>
            
        </div>
        </div>
 
    </header>

    <section class = "featured-flights">
        <h2>Featured Flights</h2>
        <div class = "flights-container">
            <div class = "flight">
                <img src="dest1.JPG">
                <div class = "flight-details">
                    <h3> New York to Istanbul</h3>
                    <p> Starting from $1400 USD</p>
                </div>
            </div>
            <div class = "flight">
                <img src="dest3.JPG">
                <div class = "flight-details">
                <h3> Paris to New York </h3>  
                <p>Starting from $375 USD</p>  
            </div>
            </div>

            <div class="flight">
                <img src="dest4.JPG">
                <div class ="flight-details">
                    <h3>Pakistan to Tehran</h3>
                    <p>Starting from $375 USD</p>
                </div>
            </div>

        
        </div>
    </section>

    <footer>
        <div class="footer-container">
            <div class = "footer-section about">
                <h3> About Us</h3>
                <p>FlIGHTS.COM is your perfect partner for planning and booking your dream trips. 
                    Discover exciting destinations
                    all over the world with us
                </p>
            </div>

            <div class = "footer-section contact">
                <h3>Contact Us</h3>
                <ul> 
                    <li>Email: support@flights.com</li>
                    <li>Phone: +123 456 7890</li>
                    <li>Address: GULISTAN E JOHAR GULSHAN NIPA</li>
                </ul>
                
            </div>
            <div class = "footer-section social">
                <h3> Follow Us</h3>
                <a href="#"><img src="facebook-icon.JPG"></a>
                <a href="#"><img src="twitter-icon.JPG"></a>
                <a href="#"><img src="Iinstagram-icon.JPG"></a>
            </div>

        </div>

        <div class="footer-bottom">
            <p>&copy; 2024 FLIGHTS.COM | Designed By ALINA KHURRAM</p>
        </div>
    </footer>


</body>
</html>

-----------------------------------------------------------------------------------
#CSS


* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

body {
    background-color: black;
    color: white;
    font-family: Arial, sans-serif;
}

h1 {
    color: white;
}

h2 {
    color: white;
}

nav {
    width: 100%;
    height: 100px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0px 100px;
}

.menu a {
    text-decoration: none;
    color: white;
    font-size: 20px;
    padding: 10px 20px;
    margin: 0px 5px;
}

.menu a:last-child {
    background: #e74c3c;
    border-radius: 5px;
}

.menu a:hover {
    background: #e74c3c;
    border-radius: 5px;
    transition: 0.4s linear;
}

.li {
    position: absolute;
    top: 22%;
    left: 8%;
}

.box1 {
    width: 10px;
    height: 10px;
    background: white;
}

.box2 {
    width: 60px;
    height: 2px;
    background: white;
}

.box3 {
    width: 100px;
    height: 2px;
    background: white;
}

.container {
    width: 100%;
    height: 100vh;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 100px;
}

.left {
    flex-basis: 60%;
}

.right {
    flex-basis: 40%;
    display: flex;
    justify-content: center;
    align-items: center;
}

.right img {
    width: 80%;
    max-width: 500px;
    height: auto;
}

.left h1 {
    font-size: 3.5rem;
    line-height: 3.5rem;
    margin-bottom: 20px;
}

.left h2 {
    font-size: 1.5rem;
    line-height: 2rem;
    margin-bottom: 20px;
}

button {
    background-color: #e74c3c;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #c0392b;
    transition: 0.3s;
}

.featured-flights {
    padding: 50px 100px;
    background-color: #222;
    text-align: center;
}

.featured-flights h2 {
    font-size: 2.5rem;
    margin-bottom: 30px;
    color: #e74c3c;
}

.flights-container {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

.flight {
    flex-basis: 30%;
    margin-bottom: 30px;
    background-color: #333;
    border-radius: 10px;
    overflow: hidden;
    text-align: center;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    transition: transform 0.3s;
}

.flight:hover {
    transform: scale(1.05);
}

.flight img {
    width: 100%;
    height: auto;
    border-bottom: 5px solid #e74c3c;
}

.flight-details {
    padding: 20px;
}

.flight h3 {
    font-size: 1.5rem;
    margin-bottom: 10px;
}

.flight p {
    font-size: 1rem;
    color: #bbb;
}

footer{
    background-color: #333;
    color: #bbb;
    padding: 50px 100px;
}

.footer-container{
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
}

.footer-section{
    flex-basis: 22%;
    margin-bottom: 20px;
}

.footer-section h3{
    margin-bottom: 20px;
    color: white;
}

.footer-section p,
.footer-section ul,
.footer-section li {
    margin-bottom: 10px;
}

.footer-section ul{
    list-style: none;
    padding: 0;
}

.footer-section a{
    text-decoration: none;
    color: #bbb;
}

.footer-section a:hover{
    color: white;
}

.footer-bottom{
    text-align: center;
    padding: 20px;
    border-top: 1px solid #444;
    margin-top: 20px;
    color: #bbb;

}


.footer-section.social a{
    display: inline-block;
    margin-right: 10px;
}

.footer-section.social a img{
    width: 30px;
    height: 30px;
}
