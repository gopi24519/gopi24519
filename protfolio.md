<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>protfolio</title>
    <style>
        .body{
            background-image: url('https://res.cloudinary.com/dnzjcn8ig/image/upload/v1724844295/l7tawkpblkv7tqttwyna.png');
            background-attachment:fixed;
            background-repeat: no-repeat;
            background-size: cover;
        }
        .Navigator{
            display: flex;
            flex-direction: row;
            text-align: left;
            align-items: center;
            height: 13vh;
        }
        a{
            text-decoration: none;
        }
        .Navigator-right{
            display: flex;
            flex-direction: row;
            justify-content: space-between;
            padding-left:1200px;
            align-items: right;
            
        }
        .element{
            letter-spacing: 3px;
            padding: 15PX;
            justify-content: space-between;
            font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            font-size: 20px;
            font-weight:bold;
            color: black; 
            box-shadow: 10px 10px 25px #0009;       
        }
        
        .heading{
           padding-top: 200px;
           padding-left:100px;
           font-size:9vh;
           font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
           float: left;
        }
        .home-right{
            width:50vw;
            padding-top: 90px;
            padding-left: 1050px;
            }
        .home-left{
            width:50vw;
        }
        .image{
            border-radius: 10px;
            box-shadow: 5px 5px 10px #0009,
                        -5px -5px 10px #0009; 
        }
    </style>
</head>
    <div class="Navigator">
        <div class="Navigator-right">
            <a class=" element" href="Home">Home</a>
            <a class=" element" href="ABOUT US">About Us</a>
            <a class=" element" href="EXPERIENCE">Experience</a>
            <a class=" element" href="Project">Project</a>
            <a class=" element" href="CONTACT">Contact</a>
        </div>
    </div>
<body class="body">  
        <div class="home">
            <div class="home-left">
                <h1 class="heading">Hi,I'am <span style="color:white;">Gopi Krishna </span></h1>
            </div>
            <div class="home-right">
                <img class="image" src="https://res.cloudinary.com/dnzjcn8ig/image/upload/w_1000,ar_16:9,c_fill,g_auto,e_sharpen/v1724251921/Screenshot_20240803_205823_Gallery_rtcydh.jpg"height=400px>
            </div>
        </div>
        <div>
            <div>
                
            </div>
        </div>
    
</body>
</html>
