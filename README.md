# Introduction-about-me
<!DOCTYPE html>
<html lang="eng">
<meta charset="UTF-8" />
    <title>Profile</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script&display=swap" rel="stylesheet">
    
    <style>
    .gradient-background{
        background:linear-gradient(200deg, #62ea47, #0ba2e3);
        background-size: 200% 200%;
        animation:gradient-animation 18s ease-in;
    }



    h1{
        font-family: 'Dancing Script', cursive;
        display: grid;
        justify-content: center;
    }

    h2{
        padding: 0;
        margin-top: 100px;
        margin-left: 27%;
        margin-bottom: 0%;
        display: grid;
        justify-content: left;
    }
    
    img{
        margin-top: 30px;
        margin-left: 500px;
        border-radius: 50%;
        display: grid;
        align-items: center;
        justify-content: center;
    }

    .cute{
        margin-left: 10%;
    }

    .cute-1{
        border-radius: 5%;
        margin-left: 0%;
        border: black solid 5px;
        float: left;
    }

    .contant-me{
        margin-left: 10%;
        margin-top: 0%;
        float:left;
    }

    .contant{
    margin-top: 10%;
}

    p{margin-top: 0%;
        font-family: 'Courier New', Courier, monospace;
        display: grid;
        justify-content: center;
     }

    span{
        color:rgba(255, 0, 8, 0.872);
        font-weight: 500;
    }

    li{
        margin-top: 4%;
        margin-left: 25%;
        list-style: none;
        font-family: 'Courier New', Courier, monospace;;
    }
    </style>
    <body>
        <section>
            <div class="gradient-background">
                <img class="cute" src="./images/Screenshot (70).png" height="50px"/>
                <h1>I am <span>Khin</span> </h1>
                <p>A person who Try to be a Webdeveloper.</p>   
            <img src="./images/Khin.jpg" height="200px" width="150px"/>    
        </div>
        </section>

        <section>
            <div id="Educational-Background">
            <h2 > Educational-Background </h2>
            <img class="cute-1" src="./images/education.png" height=200px width="300px" />   
            <ul>
                <li>Age - 19yr</li>
                <li>Education - Finished High School</li>
                <li>Learning - Chinese(HSK-3), English , Webdeveloping </li>
            </ul>
        </div>
        </section>
     
        <section>
            <div id="Things-Like-To-Do">
            <h2>Things Like To Do</h2>
            <img class="cute-1" src="./images/cute.png" height="200"/>
            <ul>
                <li>Eating spicy things</li>
                <li>Reading Books</li>
                <li>Watching Movies</li>
            </ul>
        </div>
        </section>

        <section>
           <div class="Contant Me">
            <img class="contant-me" src="./images/contant me.png" height="200px"/>
            <ul  class="contant">
                <li><a rel="stylesheet" href="https://t.me/khinnyein11">Telegram</a></li>
                <li><a rel="stylesheet" href="https://www.facebook.com/khin.nyein.7315720?mibextid=ZbWKwL">Facebook</a></li>
                <li>Phone-number - 09766380062</li>
            </ul>
           </div>
        </section>
    </body>
</html>
