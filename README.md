<!DOCTYPE html>
<html>
	<head>
        <meta charset = "utf-8">
        <title>"Prueba de Pages LCMando"</title>
        <link rel="stylesheet" href="Front.css">
        <!-- Required meta tags -->
        <meta name="viewport" content="width=device-width,initial-scale=1">
        <!-- Bootstrap CSS -->
        <link href="dist/Bootstrap/css/bootstrap.min.css" rel="stylesheet">
 	</head>
    <body>
    	<!-- Bootstrap JS -->

	   <script src="dist/Bootstrap/js/bootstrap.bundle.min.js"></script>

        <div class="container">
            <nav>
                <h1>NavBar</h1>
                <a href="https://github.com/">Home</a>
            </nav>
        </div>
        <div>

        <!-- Slideshow container -->
        <div class="slideshow-container fade">

        <!-- Full images with numbers and message Info -->
        <div class="Containers">
            <div class="MessageInfo">1 / 3</div>
            <img src="Mando1.jpg" style="width:100%">
            <div class="Info">First caption</div>
        </div>

        <div class="Containers">
            <div class="MessageInfo">2 / 3</div>
            <img src="Mando2.jpg" style="width:100%">
            <div class="Info">Second Caption</div>
        </div>

        <div class="Containers">
            <div class="MessageInfo">3 / 3</div>
            <img src="Mando3.jpg" style="width:100%">
            <div class="Info">Third Caption</div>
        </div>

        <!-- Back and forward buttons -->
        <div>
            <a class="Back" onclick="plusSlides(-1)">&#10094;</a>
            <a class="forward" onclick="plusSlides(1)">&#10095;</a>
        </div>
        <br>

        <!-- The circles/dots -->
            <div style="text-align:center">
                <span class="dots" onclick="currentSlide(1)"></span>
                <span class="dots" onclick="currentSlide(2)"></span>
                <span class="dots" onclick="currentSlide(3)"></span>
            </div>
        </div>
        <script src=moves.js></script>
    </body>


</html>
