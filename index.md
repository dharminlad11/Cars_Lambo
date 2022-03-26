<!DOCTYPE html>
<html>

<head>
    <link rel="shortcut icon" type="image/png" href="favicon2.png">
    <title>Automobile</title>

    <style>
        body {
            width: 1200px;
            height: 60px;
            margin: 0px auto;
            padding: 20px;
            border-radius: 1px;
            background-color: #92A8D1;
        }

        .body1 {
            width: 1200px;
            height: 40px;
            /* border: 3px solid black; */
            color: white;
            margin-top: 85px;
            padding: 20px;
            border-radius: 1px;
            font-family: "Montserrat, sans-serif";
            text-transform: uppercase;
            background-color: #34568B;
        }


        .body2 {
            width: 330px;
            height: 600px;
            /* border: 1px solid black; */
            margin-top: 30px;
            padding: 20px;
            border-radius: 1px;
            background-color: #34568B;
            box-shadow: 5px 5px 3px grey;

        }

        .body3 {
            float: right;
            width: 820px;
            height: 600px;
            /* border: 1px solid black; */
            margin-top: -650px;
            padding-right: -10px;
            border-radius: 1px;
            margin-bottom: 80px;
        }

        main {
            width: 800px;
            float: left;
        }

        aside {
            width: 400px;
            float: right;
            padding-left: 20px;
        }

        img {
            float: left;
            margin-top: 0px;
            padding-left: 15px;
        }

        h1 {
            float: right;
            margin-top: 30px;
            padding-right: 20px;
            font-size: 35px;
            font-style: italic;
            font-family: 'Magneto';
        }

        h2 {
            float: right;
            margin-top: 10px;
            padding-right: 90px;
            font-size: 28px;
            font-family: "Bahnschrift Light";
            text-align: center;
            font-weight: bold;
        }

        h3 {
            float: right;
            margin-top: 10px;
            padding-right: 570px;
            font-size: 40px;
            font-family: "Bahnschrift Light";
            letter-spacing: 1.5px;
        }

        .navigation {
            display: flex;
            box-shadow: 5px 5px 3px grey;
            letter-spacing: 2px;
        }



        .listing {
            margin-top: 70px;
            font-family: "Bahnschrift Light";
            text-align: left;
            letter-spacing: 1.5px;
        }



        li {
            list-style-type: none;
            font-weight: bold;
            font-family: "Bahnschrift Light";
        }

        a {
            display: block;
            width: calc(1200px / 4.5);
            height: 50px;
            text-align: center;
            line-height: 10px;
            text-decoration: none;
            color: #121212;
            font-family: "Bahnschrift Light";
            font-weight: bold;
            font-size: 25px;
        }


        a:hover {
            color: white;
        }

        nav {
            width: 1220px;
        }

        .img1 {
            margin-top: -37px;
            padding-left: 10px;
            margin-bottom: 20px;

        }

        p {
            margin-top: 120px;
            padding-left: 15px;
            text-align: justify;
            font-family: "Bahnschrift Light";
        }

        .para1 {
            margin-top: 0px;
            padding-left: 10px;
            text-align: justify;
            font-family: "Bahnschrift Light";
        }

        .para2 {
            margin-top: 0px;
            padding-left: 10px;
            text-align: justify;
            font-family: "Bahnschrift Light";
            font-weight: bold;
            letter-spacing: 1px;
        }

        .li1 {
            font-family: "Bahnschrift Light";
        }

        .foot {
            text-align: center;
            margin-top: 0px;
            padding-left: 10px;
            font-family: "Bahnschrift Light";
            margin-bottom: 100px;
            font-weight: bold;
            font-size: 22px;
        }

        .avlogo {
            padding-right: 50px;
        }

        a:active {
            color: white;
        }
    </style>

</head>

<body>
    <img src="logo.png" alt="Automobile" width="80" height="80">
    <h1>Lamborghini</h1>
    <!-- Name : Dharmin Lad
         Email: dlad3073@conestogac.on.ca
    -->

    <div class="body1">
        <nav>
            <ul class="navigation" class="li1">
                <li><a href="welcome.html" class="option">Home</a></li>
                <li><a href="#" class="option">Portfolio</a></li>
                <li><a href="#" class="option">About</a></li>
                <li><a href="#" class="option">Contact</a></li>
            </ul>
        </nav>
    </div>

    <div class="body2">
        <h2>Aventador Models </h2> <small></small><br><br>
        <ul class="listing">
            <a href= "https://www.youtube.com/watch?v=viW44cUfxCE">AVENTADOR SVJ</a>
            <a href="https://www.youtube.com/watch?v=C74Hq3HVD0Y">LP 780-4 ULTIMAE</a>
            <a href="https://www.youtube.com/watch?v=1gu1noIun8U">ULTIMAE ROADSTER</a>

        </ul>
        <img src="aventador.png" alt="logo" width="300px" height="200px" class="avlogo">
    </div>

    <div class="body3" class="para1">
        <h3>AVENTADOR</h3>
        <img src="lamborghini.jpg" alt="cars" width="800" height="400px" class="img1">
        <p class="para2">Automobili Lamborghini S.p.A. is an Italian brand and manufacturer of luxury sports cars and
            SUVs based in
            Sant'Agata Bolognese. The company is owned by the Volkswagen Group through its subsidiary Audi.
            Revolutionary thinking is at the heart of every idea from Automobili Lamborghini. Whether it is
            aerospace-inspired design or technologies applied to the naturally aspirated V12 engine or carbon-fiber
            structure, going beyond accepted limits is part of our philosophy. The Aventador advances every concept of
            performance, immediately establishing itself as the benchmark for the super sports car sector. Giving a
            glimpse of the future today, it comes from a family of supercars already considered legendary.</p>
    </div>

</body>

<footer>
    <hr style="width:100%; text-align:left; margin-left:0;background-color: black; height:2px; ">
    <p class="foot">Copyright &copy; HTML Entity Dharmin Lad - dlad3073@conestogac.on.ca - 2021</p>
</footer>

</html>
