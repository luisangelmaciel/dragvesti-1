<!DOCTYPE html>
<html>

<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        * {
            box-sizing: border-box;
        }
        
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
        }
        
        .headerPhoto {
            text-align: center;
            padding: 32px;
        }
        
        .row {
            display: -ms-flexbox;
            /* IE 10 */
            display: flex;
            -ms-flex-wrap: wrap;
            /* IE 10 */
            flex-wrap: wrap;
            padding: 0 4px;
        }
        /* Create two equal columns that sits next to each other */
        
        .column {
            -ms-flex: 20%;
            /* IE 10 */
            flex: 20%;
            padding: 0 4px;
        }
        
        .column img {
            margin-top: 8px;
            vertical-align: middle;
        }
        /* Style the buttons */
        
        .btnGrid {
            border: none;
            outline: none;
            padding: 10px 16px;
            background-color: #f1f1f1;
            cursor: pointer;
            font-size: 18px;
        }
        
        .btnGrid:hover {
            background-color: #ddd;
        }
        
        .btnGrid.active {
            background-color: #666;
            color: white;
        }
    </style>
</head>

<body>
    <!-- grind Inicio -->
    <!-- Header -->
    <div class="headerPhoto" id="DragQueen-DalilaVelvet">
        <h1>Turismo</h1>
        <button class="btnGrid" onclick="one()">1</button>
        <button class="btnGrid " onclick="two()">2</button>





        <button class="btnGrid active" onclick="four()">4</button>


    </div>

    <!--▶ Photo Grid -->
    <div class="row">
        <div class="column">
            <img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/Dalila-Velvet/Drag-Queen-Dalila-Velvet-Welcome-to-Philippines.webp" style="width:100% " alt="Drag-Queen-Dalila-Velvet-Welcome-to-Philippines" loading="lazy">
            <img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/Dalila-Velvet/Colombia-Drag-Queen-Dalila-Velvet-meme-corona-miss-universo.webp" style="width:100%" alt="Colombia-Drag-Queen-Dalila-Velvet-meme-corona-miss-universo" loading="lazy">
            <img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/Dalila-Velvet/Colombia-Drag-Queen-Dalila-Velvet.webp " style="width:100% " alt="Dalila-Velvet/Colombia-Drag-Queen-Dalila-Velvet" loading=" lazy ">
            <img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/Dalila-Velvet/Colombia-Drag-Queen-Dalila-Velvet-meme-envidia.webp " style="width:100% " alt="Colombia-Drag-Queen-Dalila-Velvet-meme-envidia" loading="lazy">

            <img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/Niiha-Villant/niiha-villant-sesion-de-fotos-turismo-gay-mexico-playa.jpg" style="width:100% " alt="niiha-villant-sesion-de-fotos-turismo-gay-mexico-playa" loading="lazy">
            <img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/Niiha-Villant/niiha-villant-sesion-de-fotos-turismo-gay-mexico-puerto-vallarta.jpg" style="width:100% " alt="niiha-villant-sesion-de-fotos-turismo-gay-mexico-puerto-vallarta.jpg" loading="lazy">
            <img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/Niiha-Villant/niiha-villant-sesion-de-fotos-turismo-gay-mexico-acapulco.jpg" style="width:100% " alt="niiha-villant-sesion-de-fotos-turismo-gay-mexico-acapulco" loading="lazy">
            <img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/Niiha-Villant/niiha-villant-sesion-de-fotos-turismo-gay-mexico.jpg" style="width:100% " alt="niiha-villant-sesion-de-fotos-turismo-gay-mexico.jpg" loading="lazy">
        </div>
        <div class="column">
            <img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/Drag-Papel/drag-papel-sesion-de-fotos-turismo-colombia-gay.jpg" style="width:100% " alt="drag-papel-sesion-de-fotos-turismo-colombia-gay.jpg" loading="lazy">
            <img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/Drag-Papel/drag-papel-sesion-de-fotos-turismo-colombia.jpg" style="width:100% " alt="drag-papel-sesion-de-fotos-turismo-colombia" loading="lazy">
            <img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/Drag-Papel/drag-papel-sesion-de-fotos-turismo-gay-colombia.jpg" style="width:100% " alt="drag-papel-sesion-de-fotos-turismo-gay-colombia.jpg" loading="lazy">

            <img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/Sophia-Nari/sophia-nari-drag-queen-sesion-de-fotos-turismo-gay-cdmx-mexico.JPG" style="width:100% " alt="sophia-nari-drag-queen-sesion-de-fotos-turismo-gay-cdmx-mexico" loading="lazy">
            <img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/Sophia-Nari/sophia-nari-drag-queen-sesion-de-fotos-turismo-gay-cdmx.JPG" style="width:100% " alt="sophia-nari-drag-queen-sesion-de-fotos-turismo-gay-cdmx" loading="lazy">
            <img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/Sophia-Nari/sophia-nari-drag-queen-sesion-de-fotos-turismo-gay-mx.JPG" style="width:100% " alt="sophia-nari-drag-queen-sesion-de-fotos-turismo-gay-mx" loading="lazy">
            <img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/Sophia-Nari/sophia-nari-drag-queen-sesion-de-fotos-turismo-gay.JPG" style="width:100% " alt="sophia-nari-drag-queen-sesion-de-fotos-turismo-gay" loading="lazy">
        </div>
        <div class="column">
            <img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/Ingrid-Fortuna/drag-queen-ingrid-fortuna-sesion-de-fotos-turismo-gay-mexico-cdmx.jpg" style="width:100% " alt="drag-queen-ingrid-fortuna-sesion-de-fotos-turismo-gay-mexico-cdmx" loading="lazy">
            <img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/Ingrid-Fortuna/drag-queen-ingrid-fortuna-sesion-de-fotos-turismo-gay-mexico.jpg" style="width:100% " alt="drag-queen-ingrid-fortuna-sesion-de-fotos-turismo-gay-mexico" loading="lazy">
            <img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/Ingrid-Fortuna/drag-queen-ingrid-fortuna-sesion-de-fotos-turismo-mexico-gay-cdmx.jpg" style="width:100% " alt="drag-queen-ingrid-fortuna-sesion-de-fotos-turismo-mexico-gay-cdmx" loading="lazy">

            <img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/Star-Glam/star-glam-sesion-de-fotos-drag-queen-espana.jpg" style="width:100% " alt="star-glam-sesion-de-fotos-drag-queen-espana" loading="lazy">
            <img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/Star-Glam/star-glam-sesion-de-fotos-drag-queen.jpg" style="width:100% " alt="star-glam-sesion-de-fotos-drag-queen" loading="lazy">
            <img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/Star-Glam/star-glam-sesion-de-fotos-dragqueen.jpg" style="width:100% " alt="star-glam-sesion-de-fotos-dragqueen" loading="lazy">
        </div>
        <div class="column">
            <img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/Iris-XC-Queen/iris-xc-queen-sesion-de-fotos-turismo-gay-mexico-cdmx-chihuahua.jpg" style="width:100% " alt="iris-xc-queen-sesion-de-fotos-turismo-gay-mexico-cdmx-chihuahua" loading="lazy">
            <img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/Iris-XC-Queen/iris-xc-queen-sesion-de-fotos-turismo-gay-mexico-chihuahua-cdmx.jpg" style="width:100% " alt="iris-xc-queen-sesion-de-fotos-turismo-gay-mexico-chihuahua-cdmx" loading="lazy">
            <img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/Iris-XC-Queen/iris-xc-queen-sesion-de-fotos-turismo-gay-mexico-cuu-chihuahua-cdmx.jpg" style="width:100% " alt="iris-xc-queen-sesion-de-fotos-turismo-gay-mexico-cuu-chihuahua-cdmx" loading="lazy">
            <img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/Iris-XC-Queen/iris-xc-queen-sesion-de-fotos-turismo-gay-mexico.jpg" style="width:100% " alt="iris-xc-queen-sesion-de-fotos-turismo-gay-mexico.jpg" loading="lazy">

            <img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/Victoria-Divanna-Lanz-McQueen/drag-queen-victoria-divana-lanz-mcqueen-sesion-de-fotos-turismo-colombia-gay.jpg" style="width:100% " alt="" loading="lazy">
            <img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/Victoria-Divanna-Lanz-McQueen/drag-queen-victoria-divana-lanz-mcqueen-sesion-de-fotos-turismo-gay-colombia.jpg" style="width:100% " alt="" loading="lazy">
            <img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/Victoria-Divanna-Lanz-McQueen/drag-queen-victoria-divana-lanz-mcqueen-sesion-de-fotos-turismo-gay-en-colombia.jpg" style="width:100% " alt="" loading="lazy">

            <img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/Yuni-K-Feem/yunik-feem-sesion-de-fotos-turismo-drag-queen-argentina.jpg" style="width:100% " alt="" loading="lazy">
            <img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/Yuni-K-Feem/yunik-feem-sesion-de-fotos-turismo-gay-drag-queen-argentina.jpg" style="width:100% " alt="" loading="lazy">
            <img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/Yuni-K-Feem/yunik-feem-sesion-de-fotos-turismo-zombie-drag-queen-argentina.jpg" style="width:100% " alt="" loading="lazy">
        </div>
    </div>
    <!-- Photo Grid ◀-->


    <script>
        // Get the elements with class="column "
        var elements = document.getElementsByClassName("column ");

        // Declare a loop variable
        var i;

        // Full-width images
        function one() {
            for (i = 0; i < elements.length; i++) {
                elements[i].style.msFlex = "100% "; // IE10
                elements[i].style.flex = "100% ";
            }
        }

        // Two images side by side
        function two() {
            for (i = 0; i < elements.length; i++) {
                elements[i].style.msFlex = "50% "; // IE10
                elements[i].style.flex = "50% ";
            }
        }

        // Four images side by side
        function four() {
            for (i = 0; i < elements.length; i++) {
                elements[i].style.msFlex = "25% "; // IE10
                elements[i].style.flex = "25% ";
            }
        }


        // Add active class to the current button (highlight it)
        var header = document.getElementById("DragQueen-DalilaVelvet ");
        var btns = header.getElementsByClassName("btnGrid ");
        for (var i = 0; i < btns.length; i++) {
            btns[i].addEventListener("click ", function() {
                var current = document.getElementsByClassName("active ");
                current[0].className = current[0].className.replace(" active ", " ");
                this.className += " active ";
            });
        }
    </script>
    <!-- Grind Final -->
</body>

</html>
<!-- https://dragvesti.hihello.monster/1ra-temporada/turismo/Dalila-Velvet/Drag-Queen-Dalila-Velvet-Welcome-to-Philippines.webp
https://dragvesti.hihello.monster/1ra-temporada/turismo/Dalila-Velvet/Colombia-Drag-Queen-Dalila-Velvet-meme-corona-miss-universo.webp
https://dragvesti.hihello.monster/1ra-temporada/turismo/Dalila-Velvet/Colombia-Drag-Queen-Dalila-Velvet.webp
https://dragvesti.hihello.monster/1ra-temporada/turismo/Dalila-Velvet/Colombia-Drag-Queen-Dalila-Velvet-meme-envidia.webp 
https://dragvesti.hihello.monster/1ra-temporada/turismo/Drag-Papel/drag-papel-sesion-de-fotos-turismo-colombia-gay.jpg
https://dragvesti.hihello.monster/1ra-temporada/turismo/Drag-Papel/drag-papel-sesion-de-fotos-turismo-colombia.jpg
https://dragvesti.hihello.monster/1ra-temporada/turismo/Drag-Papel/drag-papel-sesion-de-fotos-turismo-gay-colombia.jpg
https://dragvesti.hihello.monster/1ra-temporada/turismo/Ingrid-Fortuna/drag-queen-ingrid-fortuna-sesion-de-fotos-turismo-gay-mexico-cdmx.jpg
https://dragvesti.hihello.monster/1ra-temporada/turismo/Ingrid-Fortuna/drag-queen-ingrid-fortuna-sesion-de-fotos-turismo-gay-mexico.jpg
https://dragvesti.hihello.monster/1ra-temporada/turismo/Ingrid-Fortuna/drag-queen-ingrid-fortuna-sesion-de-fotos-turismo-mexico-gay-cdmx.jpg
https://dragvesti.hihello.monster/1ra-temporada/turismo/Iris-XC-Queen/iris-xc-queen-sesion-de-fotos-turismo-gay-mexico-cdmx-chihuahua.jpg 
https://dragvesti.hihello.monster/1ra-temporada/turismo/Iris-XC-Queen/iris-xc-queen-sesion-de-fotos-turismo-gay-mexico-chihuahua-cdmx.jpg 
https://dragvesti.hihello.monster/1ra-temporada/turismo/Iris-XC-Queen/iris-xc-queen-sesion-de-fotos-turismo-gay-mexico-cuu-chihuahua-cdmx.jpg 
https://dragvesti.hihello.monster/1ra-temporada/turismo/Iris-XC-Queen/iris-xc-queen-sesion-de-fotos-turismo-gay-mexico.jpg 
https://dragvesti.hihello.monster/1ra-temporada/turismo/Niiha-Villant/niiha-villant-sesion-de-fotos-turismo-gay-mexico-playa-puerto-vallarta-(10).JPG
https://dragvesti.hihello.monster/1ra-temporada/turismo/Niiha-Villant/niiha-villant-sesion-de-fotos-turismo-gay-mexico-playa-puerto-vallarta-(11).JPG
https://dragvesti.hihello.monster/1ra-temporada/turismo/Niiha-Villant/niiha-villant-sesion-de-fotos-turismo-gay-mexico-playa-puerto-vallarta-(12).JPG
https://dragvesti.hihello.monster/1ra-temporada/turismo/Niiha-Villant/niiha-villant-sesion-de-fotos-turismo-gay-mexico-playa-puerto-vallarta-(13).JPG
https://dragvesti.hihello.monster/1ra-temporada/turismo/Niiha-Villant/niiha-villant-sesion-de-fotos-turismo-gay-mexico-playa-puerto-vallarta-(6).JPG
https://dragvesti.hihello.monster/1ra-temporada/turismo/Niiha-Villant/niiha-villant-sesion-de-fotos-turismo-gay-mexico-playa-puerto-vallarta-(7).JPG
https://dragvesti.hihello.monster/1ra-temporada/turismo/Niiha-Villant/niiha-villant-sesion-de-fotos-turismo-gay-mexico-playa-puerto-vallarta-(8).JPG
https://dragvesti.hihello.monster/1ra-temporada/turismo/Niiha-Villant/niiha-villant-sesion-de-fotos-turismo-gay-mexico-playa-puerto-vallarta-(9).JPG
https://dragvesti.hihello.monster/1ra-temporada/turismo/Niiha-Villant/niiha-villant-sesion-de-fotos-turismo-gay-mexico-playa-puerto-vallarta.jpg
https://dragvesti.hihello.monster/1ra-temporada/turismo/Niiha-Villant/niiha-villant-sesion-de-fotos-turismo-gay-mexico-playa.jpg
https://dragvesti.hihello.monster/1ra-temporada/turismo/Niiha-Villant/niiha-villant-sesion-de-fotos-turismo-gay-mexico-puerto-vallarta.jpg
https://dragvesti.hihello.monster/1ra-temporada/turismo/Niiha-Villant/niiha-villant-sesion-de-fotos-turismo-gay-mexico.jpg
https://dragvesti.hihello.monster/1ra-temporada/turismo/Niiha-Villant/niiha-villant-sesion-de-fotos-turismo-gay-mexico-acapulco.jpg
https://dragvesti.hihello.monster/1ra-temporada/turismo/Sophia-Nari/sophia-nari-drag-queen-sesion-de-fotos-turismo-gay-cdmx-mexico.JPG
https://dragvesti.hihello.monster/1ra-temporada/turismo/Sophia-Nari/sophia-nari-drag-queen-sesion-de-fotos-turismo-gay-cdmx.JPG
https://dragvesti.hihello.monster/1ra-temporada/turismo/Sophia-Nari/sophia-nari-drag-queen-sesion-de-fotos-turismo-gay-mx.JPG
https://dragvesti.hihello.monster/1ra-temporada/turismo/Sophia-Nari/sophia-nari-drag-queen-sesion-de-fotos-turismo-gay.JPG
https://dragvesti.hihello.monster/1ra-temporada/turismo/Star-Glam/star-glam-sesion-de-fotos-drag-queen-espana.jpg
https://dragvesti.hihello.monster/1ra-temporada/turismo/Star-Glam/star-glam-sesion-de-fotos-drag-queen.jpg
https://dragvesti.hihello.monster/1ra-temporada/turismo/Star-Glam/star-glam-sesion-de-fotos-dragqueen.jpg
https://dragvesti.hihello.monster/1ra-temporada/turismo/Victoria-Divanna-Lanz-McQueen/drag-queen-victoria-divana-lanz-mcqueen-sesion-de-fotos-turismo-colombia-gay.jpg
https://dragvesti.hihello.monster/1ra-temporada/turismo/Victoria-Divanna-Lanz-McQueen/drag-queen-victoria-divana-lanz-mcqueen-sesion-de-fotos-turismo-gay-colombia.jpg
https://dragvesti.hihello.monster/1ra-temporada/turismo/Victoria-Divanna-Lanz-McQueen/drag-queen-victoria-divana-lanz-mcqueen-sesion-de-fotos-turismo-gay-en-colombia.jpg
https://dragvesti.hihello.monster/1ra-temporada/turismo/Yuni-K-Feem/yunik-feem-sesion-de-fotos-turismo-drag-queen-argentina.jpg
https://dragvesti.hihello.monster/1ra-temporada/turismo/Yuni-K-Feem/yunik-feem-sesion-de-fotos-turismo-gay-drag-queen-argentina.jpg
https://dragvesti.hihello.monster/1ra-temporada/turismo/Yuni-K-Feem/yunik-feem-sesion-de-fotos-turismo-zombie-drag-queen-argentina.jpg
https://youtu.be/GfJsDEH1S7I divana
<img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/resumen/01.jpg" style="width:100% " alt="" loading="lazy">
<img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/resumen/02.jpg" style="width:100% " alt="" loading="lazy">
<img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/resumen/03.jpg" style="width:100% " alt="" loading="lazy">
<img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/resumen/04.jpg" style="width:100% " alt="" loading="lazy">
<img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/resumen/05.jpg" style="width:100% " alt="" loading="lazy">
<img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/resumen/06.jpg" style="width:100% " alt="" loading="lazy">
<img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/resumen/07.jpg" style="width:100% " alt="" loading="lazy">
<img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/resumen/08.jpg" style="width:100% " alt="" loading="lazy">
<img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/resumen/09.jpg" style="width:100% " alt="" loading="lazy">
<img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/resumen/10.jpg
" style="width:100% " alt="" loading="lazy">
<img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/resumen/
10a.jpg
" style="width:100% " alt="" loading="lazy">
<img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/resumen/
11.jpg
" style="width:100% " alt="" loading="lazy">
<img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/resumen/
12.jpg
" style="width:100% " alt="" loading="lazy">
<img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/resumen/
13.jpg
" style="width:100% " alt="" loading="lazy">
<img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/resumen/
14.jpg
" style="width:100% " alt="" loading="lazy">
<img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/resumen/
15.jpg
" style="width:100% " alt="" loading="lazy">
<img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/resumen/
16.jpg" style="width:100% " alt="" loading="lazy">
<img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/resumen/17.jpg" style="width:100% " alt="" loading="lazy">
<img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/resumen/17a.jpg" style="width:100% " alt="" loading="lazy">
<img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/resumen/18.jpg" style="width:100% " alt="" loading="lazy">
<img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/resumen/19.jpg" style="width:100% " alt="" loading="lazy">
<img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/resumen/19a.jpg" style="width:100% " alt="" loading="lazy">
<img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/resumen/20.jpg" style="width:100% " alt="" loading="lazy">
<img src="https://dragvesti.hihello.monster/1ra-temporada/turismo/resumen/21.jpg" style="width:100% " alt="" loading="lazy"> 
Agatha-Toro/Agatha-Toro-drag-queen.jpg
Agatha-Toro/Agatha-Toro-drag.jpg
Agatha-Toro/Agatha-Toro.jpg
Lennox/Lennox-Gyarada-Drag-Queen-casting.webp
Lennox/Lennox-Gyarada-Drag-Queen-cuu.webp
Lennox/Lennox-Gyarada-Drag-Queen-la-carrera-drag-cdmx.webp
Lennox/Lennox-Gyarada-Drag-Queen.webp
Lennox/Lennox-Gyarada-DragQueen.webp
Lennox/Lennox-Gyarada.webp
Becky-DVich/Becky-DVich-Drag-Guadalajara-Jalisco.jpg
Becky-DVich/Becky-DVich-Drag-Queen-Guadalajara-.jpg
Becky-DVich/Becky-DVich-Drag-Queen-Guadalajara-Jalisco-(2).jpg
Becky-DVich/Becky-DVich-Drag-Queen-Guadalajara-Jalisco-(4).jpg
Becky-DVich/Becky-DVich-Drag-Queen-Guadalajara-Jalisco.jpg
Becky-DVich/Becky-DVich-Drag-Queen-Guadalajara.jpg
Becky-DVich/Becky-DVich-Drag-Queen.jpg
Becky-DVich/Becky-DVich-DragQueen-Guadalajara-Jalisco.jpg
Blondie-Lafayyate/Blondie-Lafayyate-Veracruz .jpg
Blondie-Lafayyate/Blondie-Lafayyate-drag-queen-Veracruz .jpg
Blondie-Lafayyate/Blondie-Lafayyate-dragvesti.jpg
Blondie-Lafayyate/Blondie-Lafayyate-la-carrera.jpg
Blondie-Lafayyate/Blondie-Lafayyate.jpg
Camila-Serdan/Camila-Serdan-Drag-Queen-(1).jpg
Camila-Serdan/Camila-Serdan-Drag-Queen-(5).jpg
Camila-Serdan/Camila-Serdan-Drag-Queen.jpg
Camila-Serdan/Camila-Serdan-DragQueen.jpg
Mia-Pop/Mia-Pop-Drag-Queen.jpg
Mia-Pop/Mia-Pop-drag.jpg
Mia-Pop/Mia-Pop-dragQueen.jpg
Mia-Pop/Mia-Pop.jpg
Rhonda-Sullivan/Rhonda-Sullivan (1).jpg
Rhonda-Sullivan/Rhonda-Sullivan (2).jpg
Rhonda-Sullivan/Rhonda-Sullivan (3).jpg
Rhonda-Sullivan/Rhonda-Sullivan (4).jpg
Rhonda-Sullivan/Rhonda-Sullivan (5).jpg
Rhonda-Sullivan/Rhonda-Sullivan (6).jpg
Rhonda-Sullivan/Rhonda-Sullivan (7).jpg
Rhonda-Sullivan/Rhonda-Sullivan (8).jpg
Sugar-Stone/Sugar-Stone-Drag-Queen-CDMX (1).png
Sugar-Stone/Sugar-Stone-Drag-Queen-CDMX (2).jpg
Sugar-Stone/Sugar-Stone-Drag-Queen-CDMX (3).jpg
Sugar-Stone/Sugar-Stone-Drag-Queen-CDMX (3).png
Sugar-Stone/Sugar-Stone-Drag-Queen-CDMX (4).jpg
Sugar-Stone/Sugar-Stone-Drag-Queen-CDMX (5).jpg
Sugar-Stone/Sugar-Stone-Drag-Queen-CDMX (6).jpg
Sugar-Stone/Sugar-Stone-Drag-Queen-CDMX (7).jpg
Sugar-Stone/Sugar-Stone-Drag-Queen-CDMX (8).jpg
Sugar-Stone/Sugar-Stone-Drag-Queen-CDMX (9).jpg
Sugar-Stone/Sugar-Stone-Drag-Queen-CDMX.jpg
Sugar-Stone/Sugar-Stone-Drag-Queen.png
Vagina/Vagina-Davis-.jpg
Vagina/Vagina-Davis-drag.jpg
Vagina/Vagina-Davis-jorge-uriel-ibañes-castañeda.jpg
Vagina/Vagina-Davis-jorge-uriel-ibañes.jpg
Vagina/Vagina-Davis-jorge-uriel.jpg
Vagina/Vagina-Davis-jorge.jpg
Scarlett-Unique/scarletunique(1).webp
Scarlett-Unique/scarletunique(10).webp
Scarlett-Unique/scarletunique(2).webp
Scarlett-Unique/scarletunique(3).webp
Scarlett-Unique/scarletunique(5).webp
Scarlett-Unique/scarletunique(6).webp
Scarlett-Unique/scarletunique(7).webp
Scarlett-Unique/scarletunique(8).webp
Scarlett-Unique/scarletunique(9).webp
Scarlett-Unique/scarletunique.webp
Zaphiro-Fanteasy/Zaphiro-Fanteasy-Drag-Queen (2).jpg
Zaphiro-Fanteasy/Zaphiro-Fanteasy-Drag-Queen (3).jpg
Zaphiro-Fanteasy/Zaphiro-Fanteasy-Drag-Queen (4).jpg
Zaphiro-Fanteasy/Zaphiro-Fanteasy-Drag-Queen (5).jpg
Zaphiro-Fanteasy/Zaphiro-Fanteasy-Drag-Queen (6).jpg
Zaphiro-Fanteasy/Zaphiro-Fanteasy-Drag-Queen (7).jpg
Zaphiro-Fanteasy/Zaphiro-Fanteasy-Drag-Queen.jpg
2da-temporada/Cast/03 Chihuahua - Zafiro Fanteasy.jpg
2da-temporada/Cast/04 Veracruz - Blondie Beyrragan.jpg
2da-temporada/Cast/05 Morelos Agatha.jpg
2da-temporada/Cast/06 CDMX - Mia Pop.jpg
2da-temporada/Cast/08 Camila Serdan.gif
2da-temporada/Cast/09 Sugar Stone.gif
2da-temporada/Cast/10 Zafiro Fanteasy.gif
2da-temporada/Cast/11 Vagina.gif
2da-temporada/Cast/13698235_1740957116161298_6879153348613150592_o.jpg
2da-temporada/Cast/Agatha.gif
2da-temporada/Cast/Becky DVich.gif
2da-temporada/Cast/Blondie Beyrragan.gif
2da-temporada/Cast/Chihuahua - Lennox.jpg
2da-temporada/Cast/EDOMEX - Camila Serdan.jpg
2da-temporada/Cast/Jalisco - Bcky D Vich.jpg
2da-temporada/Cast/Lennox.gif
2da-temporada/Cast/Mia.gif
2da-temporada/Cast/Michoacan Scarlett Unique.jpg
2da-temporada/Cast/Rhonda Sullivan.gif
2da-temporada/Cast/Scarlett.gif
2da-temporada/Cast/Sugar Stone.jpg
2da-temporada/Cast/Vagina-Davis.jpg
1ra-temporada/Colegio/Dalila-Velvet/Dalila-Velvet-Colegio-Drag-Queen.jpg
1ra-temporada/Colegio/Dalila-Velvet/Dalila-Velvet-Colegio-La-perra-mas-alta-de-colombia.jpg
1ra-temporada/Colegio/Dalila-Velvet/Dalila-Velvet-Colegio.jpg
1ra-temporada/Colegio/Iris-XC-Queen/Irix-XC-Queen-Colegio-De-Brujas-Drag-Queen-Chihuahua.jpg
1ra-temporada/Colegio/Iris-XC-Queen/Irix-XC-Queen-Colegio-De-Brujas-Drag-Queen.jpg
1ra-temporada/Colegio/Iris-XC-Queen/Irix-XC-Queen-Colegio-De-Brujas-DragQueen.jpg
1ra-temporada/Colegio/Niiha-Villant/Niiha-Villant-Sesion-de-fotos-colegio-colegiala-drag-queen-dragqueen.JPG
1ra-temporada/Colegio/Niiha-Villant/Niiha-Villant-Sesion-de-fotos-colegio-colegiala-drag-queen.JPG
1ra-temporada/Colegio/Niiha-Villant/Niiha-Villant-Sesion-de-fotos-colegio-colegiala.JPG
1ra-temporada/Colegio/Niiha-Villant/Niiha-Villant-Sesion-de-fotos-colegio.JPG
1ra-temporada/Colegio/Niiha-Villant/Niiha-Villant-Sesion-de-fotos.JPG
1ra-temporada/Colegio/Sophia-Nari/Sophia-Nari-Colegio-Drag-Queen-bad-girl.jpg
1ra-temporada/Colegio/Sophia-Nari/Sophia-Nari-Colegio-Drag-Queen-chica-mala.jpg
1ra-temporada/Colegio/Sophia-Nari/Sophia-Nari-Colegio-Drag-Queen.JPG
1ra-temporada/Colegio/Sophia-Nari/Sophia-Nari-Colegio-DragQueen.jpg
1ra-temporada/Colegio/Yuni-K-Feem/YunikFeem-Drag-Queen-Colegio-alien-estudiante.jpg
1ra-temporada/Colegio/Yuni-K-Feem/YunikFeem-Drag-Queen-Colegio-Alien.jpg
1ra-temporada/Colegio/Yuni-K-Feem/YunikFeem-Drag-Queen-Colegio-Sesion-de-fotos.jpg
1ra-temporada/Doll/Dalila-Velvet/Dalila-Velvet-drag-queen-sesion-de-fotos.jpg
1ra-temporada/Doll/Dalila-Velvet/Dalila-Velvet-drag-queen-sesion-de-fotos-.jpg
1ra-temporada/Doll/Dalila-Velvet/Dalila-Velvet-drag-queen-sesion-de-fotos-toys-barbie.jpg
1ra-temporada/Doll/Dalila-Velvet/Dalila-Velvet-drag-queen-sesion-de-fotos-toys-barbie-la-perra-mas-alta-de-colombia.jpg
1ra-temporada/Doll/Iris-XC-Queen/Iris-XC-Queen-Doll.jpg
1ra-temporada/Doll/Iris-XC-Queen/Iris-XC-Queen-Doll-Sesion-de-fotos.jpg
1ra-temporada/Doll/Iris-XC-Queen/Iris-XC-Queen-Dool-Sesion-de.jpg
1ra-temporada/Doll/Iris-XC-Queen/Iris-XC-Queen-Sesion-de-fotos.jpg
1ra-temporada/Doll/YuniK-Feem/Yuni-K-Feem-Doll.jpg
1ra-temporada/Doll/YuniK-Feem/Yuni-K-Feem-Doll-DragQueen.jpg
1ra-temporada/Doll/YuniK-Feem/Yuni-K-Feem-Doll-Drag-Queen.jpg
1ra-temporada/uno-a-uno/01-Yuni.jpg
1ra-temporada/uno-a-uno/02-Sophia.jpg
1ra-temporada/uno-a-uno/03-Dalila.jpg
1ra-temporada/uno-a-uno/04-Niiha.jpg
1ra-temporada/uno-a-uno/05-Victoria.jpg
1ra-temporada/uno-a-uno/06-Ingrid.jpg
1ra-temporada/uno-a-uno/07-Papel.jpg
1ra-temporada/uno-a-uno/08-Star.jpg
1ra-temporada/uno-a-uno/09-Melina.jpg
1ra-temporada/uno-a-uno/10-Miverva.jpg
1ra-temporada/uno-a-uno/11-Yanuryx.jpg
1ra-temporada/uno-a-uno/12-todas.jpg
1ra-temporada/Snatch-Game-Tributo-a/Niiha-Villant/niiha-villant-drag-queen-mexico-dragvesti-selena-snatch-game.jpg
1ra-temporada/Snatch-Game-Tributo-a/Niiha-Villant/niiha-villant-drag-queen-mexico-dragvesti-selena.jpg
1ra-temporada/Snatch-Game-Tributo-a/Niiha-Villant/niiha-villant-drag-queen-mexico-selena.jpg
1ra-temporada/Snatch-Game-Tributo-a/Niiha-Villant/niiha-villant-drag-queen-selena.jpg
1ra-temporada/Snatch-Game-Tributo-a/Niiha-Villant/selena-quintanilla.jpg
1ra-temporada/Snatch-Game-Tributo-a/Dalila-Velvet/Dalila-Velvet-DragQueen-Snatch-Game-Amelie.jpg
1ra-temporada/Snatch-Game-Tributo-a/Dalila-Velvet/Dalila-Velvet-Drag-Queen-Snatch-Game-Amelie.jpg
1ra-temporada/Snatch-Game-Tributo-a/Dalila-Velvet/Dalila-Velvet-Drag-Queen-Snatch-Game-Amelie-Tributo-a.jpg
1ra-temporada/Snatch-Game-Tributo-a/Dalila-Velvet/Dalila-Velvet-Snatch-Game-Amelie.jpg
1ra-temporada/Snatch-Game-Tributo-a/Iris-XC-Queen/Drag-Iris-XC-Queen-Snatch-Game.jpg
1ra-temporada/Snatch-Game-Tributo-a/Iris-XC-Queen/Drag-Queen-Iris-XC-Queen-SnatchGame.jpg
1ra-temporada/Snatch-Game-Tributo-a/Iris-XC-Queen/Drag-Queen-Iris-XC-Queen-Snatch-Game.jpg
1ra-temporada/Snatch-Game-Tributo-a/Sophia-Nari/Sophia-Nari-Snatch-Game.JPG
1ra-temporada/Snatch-Game-Tributo-a/Sophia-Nari/Sophia-Nari-Snatch-Game-Tributo.JPG
1ra-temporada/Snatch-Game-Tributo-a/Sophia-Nari/Sophia-Nari-Snatch-Game-Tributo-a.JPG
1ra-temporada/Snatch-Game-Tributo-a/Yuni-K-Feem/Yuni-k-feem-snatch-game-the-rocky-horror-picture-show.jpg
1ra-temporada/Snatch-Game-Tributo-a/Yuni-K-Feem/Yuni-k-feem-snatch-game-the-rocky-horror-picture-show-dragqueen.jpg
1ra-temporada/Snatch-Game-Tributo-a/Yuni-K-Feem/Yuni-k-feem-snatch-game-the-rocky-horror-picture-show-drag-queen.jpg
1ra-temporada/Glam/Dalila-Velvet/Dalila-Velvet-Glam.jpg
1ra-temporada/Glam/Dalila-Velvet/Dalila-Velvet-Glam-Drag.jpg
1ra-temporada/Glam/Dalila-Velvet/Dalila-Velvet-Glam-DragQueen .jpg
1ra-temporada/Glam/Dalila-Velvet/Dalila-Velvet-Glam-Drag-Queen.jpg
1ra-temporada/Glam/Iris-XC-Queen/Iris-XC-Queen-Dool-Sesion-de-fotos.jpg
1ra-temporada/Glam/Iris-XC-Queen/Iris-XC-Queen-Dool-Sesion-de-fotos-cosmetics.jpg
1ra-temporada/Glam/Iris-XC-Queen/Iris-XC-Queen-Dool-Sesion-de-fotos-glam.jpg
1ra-temporada/Glam/Sophia-Nari/Sophia-Nari-DragQueen-Glam.png
1ra-temporada/Glam/Sophia-Nari/Sophia-Nari-Drag-Queen-Glam.png
1ra-temporada/Glam/Sophia-Nari/Sophia-Nari-DragQueen-Glam-Photo.png
1ra-temporada/Glam/Yuni-k-Feem/Yunik-Feem-drag-queen.jpg
1ra-temporada/Glam/Yuni-k-Feem/Yunik-Feem-glam-dragqueen.jpg
1ra-temporada/Glam/Yuni-k-Feem/Yunik-Feem-glam-drag-queen.jpg
1ra-temporada/final/
solo esta yuni 
papel/resumen/0.jpg
papel/resumen/01-(1).jpg
papel/resumen/01-(2).jpg
papel/resumen/01-(3).jpg
papel/resumen/01-(4).jpg
papel/resumen/1.jpg
papel/resumen/2.jpg
papel/resumen/3.jpg
papel/resumen/4.jpg
papel/resumen/5.jpg
papel/resumen/6.jpg
papel/resumen/6a.jpg
papel/resumen/7.jpg
papel/resumen/7a.jpg
papel/resumen/8.jpg
papel/resumen/8a.jpg
papel/resumen/9.jpg
papel/resumen/9a.jpg
papel/resumen/10.jpg
papel/resumen/10a.jpg
papel/resumen/11.jpg
papel/resumen/12.jpg
papel/resumen/13.jpg
papel/resumen/14.jpg
papel/resumen/15.jpg
papel/resumen/a.jpg
papel/resumen/a1.jpg
papel/resumen/a2.jpg
papel/resumen/b.jpg
papel/resumen/b1.jpg
papel/resumen/b2.jpg
papel/resumen/c.jpg
papel/resumen/c1.jpg
papel/resumen/c2.jpg
papel/resumen/d.jpg
papel/resumen/d1.jpg
papel/resumen/d2.jpg
papel/resumen/e.jpg
papel/resumen/e1.jpg
papel/resumen/e2.jpg
papel/resumen/f.jpg
papel/resumen/g.jpg
papel/resumen/h.jpg
papel/resumen/z.jpg
papel/Ingrid-Fortuna/ingrid-fortuna.jpg
papel/Ingrid-Fortuna/ingrid-fortuna-1.jpg
papel/Ingrid-Fortuna/ingrid-fortuna-2.jpg
papel/Ingrid-Fortuna/ingrid-fortuna-mx.jpg
papel/Iris-XC-Queen/iris-mexico.jpg
papel/Iris-XC-Queen/Iris-XC-Queen-drag-queen-.jpg
papel/Iris-XC-Queen/Iris-XC-Queen-dragqueen-sesion-de-fotos.jpg
papel/Iris-XC-Queen/Iris-XC-Queen-drag-queen-sesion-de-fotos.jpg
papel/Iris-XC-Queen/Iris-XC-Queen-drag-queen-sesion-de-fotos-.jpg
papel/Melina-Isabella/melina-argentina.jpg
papel/Melina-Isabella/Melina-isabella-drag-queen-argentina-sesion-de-fotos-vestido-de-papel-(1).jpg
papel/Melina-Isabella/Melina-isabella-drag-queen-argentina-sesion-de-fotos-vestido-de-papel-(2).jpg
papel/Melina-Isabella/Melina-isabella-drag-queen-argentina-sesion-de-fotos-vestido-de-papel-(8).jpg
papel/Melina-Isabella/Melina-isabella-drag-queen-argentina-sesion-de-fotos-vestido-de-papel-(9).jpg
papel/Melina-Isabella/Melina-isabella-drag-queen-argentina-sesion-de-fotos-vestido-de-papel-(11).jpg
papel/Melina-Isabella/Melina-isabella-drag-queen-argentina-sesion-de-fotos-vestido-de-papel.jpg
papel/Melina-Isabella/Melina-isabella-drag-queen-argentina-sesion-de-fotos-vestido-de-papel-3.jpg
papel/Melina-Isabella/Melina-isabella-drag-queen-argentina-sesion-de-fotos-vestido-de-papel-4.jpg
papel/Melina-Isabella/Melina-isabella-drag-queen-argentina-sesion-de-fotos-vestido-de-papel-5.jpg
papel/Melina-Isabella/Melina-isabella-drag-queen-argentina-sesion-de-fotos-vestido-de-papel-6.jpg
papel/Melina-Isabella/Melina-isabella-drag-queen-argentina-sesion-de-fotos-vestido-de-papel-7.jpg
papel/StarGlam/star-espana.jpg
papel/StarGlam/Star-Glam-drag-queen.jpg
papel/StarGlam/Star-Glam-drag-queen-sesion.jpg
papel/StarGlam/Star-Glam-dragqueen-sesion-de-fotos.jpg
papel/StarGlam/Star-Glam-drag-queen-sesion-de-fotos.jpg
papel/Yuni-K-Feem/yuni-k-feem-dragqueen.png
papel/Yuni-K-Feem/yuni-k-feem-drag-queen.png
papel/Yuni-K-Feem/yuni-k-feem-drag-queen-sesion-de-fotos.png
periodico/Victoria-Lanz-McQueen/Victoria-Lanz-McQueen-(1).jpg
periodico/Victoria-Lanz-McQueen/Victoria-Lanz-McQueen.jpg
periodico/Victoria-Lanz-McQueen/Victoria-Lanz-McQueen-d5rag-queen.jpg
periodico/Victoria-Lanz-McQueen/Victoria-Lanz-McQueen-drag.jpg
periodico/Dalila-Velvet/Dalila-Velvet-dragqueen.jpg
periodico/Dalila-Velvet/Dalila-Velvet-dragqueen-col.jpg
periodico/Dalila-Velvet/Dalila-Velvet-dragqueen-colombia.jpg
periodico/Dalila-Velvet/Dalila-Velvet-drag-queen-colombia.jpg
periodico/Dalila-Velvet/Dalila-Velvet-dragqueen-colombia-1.jpg
periodico/Drag-Papel/Drag-papel-colombia-(5).jpg
periodico/Drag-Papel/Drag-papel-colombia.jpg
periodico/Drag-Papel/Drag-papel-colombia-1.jpg
periodico/Drag-Papel/Drag-papel-colombia-2.jpg
periodico/Niiha-Villant/Niiha-villant-drag-queen-sesion-de-fotos-cdmx-(1).jpg
periodico/Niiha-Villant/Niiha-villant-drag-queen-sesion-de-fotos-cdmx-(2).jpg
periodico/Niiha-Villant/Niiha-villant-drag-queen-sesion-de-fotos-cdmx-(3).jpg
periodico/Niiha-Villant/Niiha-villant-drag-queen-sesion-de-fotos-cdmx-(4).jpg
periodico/Niiha-Villant/Niiha-villant-drag-queen-sesion-de-fotos-cdmx-(5).jpg
periodico/Niiha-Villant/Niiha-villant-drag-queen-sesion-de-fotos-cdmx-(6).jpg
periodico/Niiha-Villant/Niiha-villant-drag-queen-sesion-de-fotos-cdmx-(7).jpg
periodico/Niiha-Villant/Niiha-villant-drag-queen-sesion-de-fotos-cdmx-(8).jpg
periodico/Niiha-Villant/Niiha-villant-drag-queen-sesion-de-fotos-cdmx-(9).jpg
periodico/Niiha-Villant/Niiha-villant-drag-queen-sesion-de-fotos-cdmx-(10).jpg
periodico/Niiha-Villant/Niiha-villant-drag-queen-sesion-de-fotos-cdmx-(11).jpg
periodico/Niiha-Villant/Niiha-villant-drag-queen-sesion-de-fotos-cdmx-(12).jpg
periodico/Niiha-Villant/Niiha-villant-drag-queen-sesion-de-fotos-cdmx-(13).jpg
periodico/Niiha-Villant/Niiha-villant-drag-queen-sesion-de-fotos-cdmx-(14).jpg
periodico/Niiha-Villant/Niiha-villant-drag-queen-sesion-de-fotos-cdmx-(15).jpg
periodico/Niiha-Villant/Niiha-villant-drag-queen-sesion-de-fotos-cdmx-(16).jpg
periodico/Niiha-Villant/Niiha-villant-drag-queen-sesion-de-fotos-cdmx-(17).jpg
periodico/Niiha-Villant/Niiha-villant-drag-queen-sesion-de-fotos-cdmx-(18).jpg
periodico/Sophia-Nari/Sophia-Nari-Drag-Queen-Sesion-De-Fotos-CDMX-(2).JPG
periodico/Sophia-Nari/Sophia-Nari-Drag-Queen-Sesion-De-Fotos-CDMX-(3).JPG
periodico/Sophia-Nari/Sophia-Nari-Drag-Queen-Sesion-De-Fotos-CDMX-(4).JPG
periodico/Sophia-Nari/Sophia-Nari-Drag-Queen-Sesion-De-Fotos-CDMX-(6).jpg
periodico/Sophia-Nari/Sophia-Nari-Drag-Queen-Sesion-De-Fotos-CDMX.JPG
periodico/Sophia-Nari/Sophia-Nari-Drag-Queen-Sesion-De-Fotos-CDMX-1.JPG
Turista
La fama lleva acompañada de entrevistas, shows y giras... motivo por el cual pasaran a ser también una: Turista. Este reto esta basado en el tema de ser “Turista”, la ganadora sera la imagen de  CGTravel para viajes y eventos Drag.
Tigrida Revuelta a Iris
Calidad y originalidad de la fotografía. Cari esta foto te voy a dar un 2 por que no veo mucho hacia la temática, me falto algo mas...sigue mostrándonos tu arte del drag.  Vestuario. Me gusta el outit pero sale un poco borrosa la foto.  Maquillaje y peluca. Hay cariña, veo tu foto y me inspira ir contigo a disfrutar de Acapulco,Veracruz o Vallarta!!! Si me irìa contigo de vacaciones lo pasariamos de lujo querida un 5 para esta foto royo HOLIDAY QUEEN.  Felicidades querida.
TR a StarGlam
En esta foto me fuera gustado ver algo más emblemático de tu ciudad... Parece una muralla...pero no me dice algo más de lo que pensaba ver... Te doy un 2, para que le eches ganas al próximo reto. 
Tu rollo de ven a conocer los años 40s de nuestra tierra me gusta... Vestuario elegido al royo Pin Up como turista me gusta, te doy un 3 y a seguir demostrando tu lado mas artística de una Drag Queen con mucho glam. 
Uff cariña, me encanto!!! En esta foto te doy el 5 por la expresión de tus ojos,estilismo. FELICIADES
TR a Ingrid
Que risa me recordastes a una amiga cuando llegamos a un hotel y no teniamos cama en Marruecos jajajaj ella tambièn era rubia... Pues solo por eso y por hacerme recordar. Espero  que sigas dandole a la cabeza y sigas haciendo cosas que nos hagan reír y ver que la vida también hay personas como tu personaje. MUAKS!!!
tg A dALILA
Esta foto para una empresa de viajes me gusta cariña, para Gay Travel en la Selva...! Besos Cariña 
TG A NIIHA
Esto si es “estilazo” cariña y bien pensado para el reto auténtico. Te las sabes cari y eso me gusta. 
Barbara a Yuni
A excepción de la primera foto, la edición es aceptable, el Makeup es correcto y la idea es la más original, aunque fuiste a la playa como muchas otras, es refrescante ver algo más que una rubia, o una diva.
B a victoria
Siempre es divertido ver vestidos caseros y con poco presupuesto, la idea de reina de Atlantis es divertida, aunque no existe reina con un Makeup mal hecho. Consejo: Pule, tienes proporciones óseas que te pueden favorecer en Makeup, aprovéchalas.
B a Papel
La única que decidió ser un personaje interestelar, si bien la calidad de la foto es mala, no es tan notoria como el mal makeup y el outfit, es como más el grinch que un extraterrestre.
B a Nari
La idea es divertida, es segura, no hubo riesgos. El makeup es malo, pero lo cubriste con lentes y eso es actuar de forma inteligente. Consejo: "la chica rubia " es un cliché por demás usado, todo el mundo se mofa de eso y hay mil versiones ¿no hay más?
-->
