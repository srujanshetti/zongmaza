# zongmaza
![AR-rahman-black-and-white-image](https://user-images.githubusercontent.com/114070795/191580016-d6857fbd-9d9f-4d05-84ec-5eb732c73894.jpg)
*{
    margin: 0px;
    padding: 0px;
}
body{
    background-color: #0a183d;
    font-family: montserrat,sans-serif;
    font-weight: 400;
}
.box{
    position: fixed;
    left: 0%;
    top: 5%;
}
.menu{
border: 1px solid none;
height: 80px;
margin-top: -40px;
background: #08192d;
}
ul{
    float: left;
    margin: 30px 230px;
}
ul li{
float: left;
margin: 0px 50px;
list-style-type: none;
}
ul li a{
    text-decoration: none;
    color: #ffffff;
}
ul li a:hover{
    color: #fc0254;

}
.h{
    
    color: #979aa5;
}
span{
    color: white;
    margin: 0px 5px;
}
h4{
    position: absolute;
left: 81%;
top: -21%;
color: white;
font-weight: 400;
text-transform: capitalize;
}
.signup{
    position: absolute;
    left: 87%;
    top: -20%;
    width: 200px;
    cursor: pointer;
}
h5{
    color: #fc0254;
    font-weight: 400;
    font-size: 16px;
    animation: 4s signup none;
text-transform: capitalize;
}
@keyframes signup{
    0%{
        transform: translatex(100px);
        opacity: 0;
    }
    100%{
transform: none;
opacity: 1;    
}  
}
.symb{
    position: absolute;
    left: 4%;
    top: -35%;

}

h2{
    text-transform: uppercase;
    color: white;
    font-weight: 600;
    font-size: 25px;
    animation: 2s text none ;

}
font{
    color:#fc0254;

}
@keyframes text{
    0%{
        transform: translateY(-100px);
        opacity: 0;
    }
    100%{
transform: none;
opacity: 1;    
}  
}
.image{
    position: absolute;
    top: 100%;
    animation: 2s img none;

}
@keyframes img{
    0%{
        transform: translateY(-100px);
        opacity: 0;
    }
    100%{
transform: none;
opacity: 1;   
    }
}
.contents{
    position: absolute;
    left:4%;
    top: 300%;
    text-transform: capitalize;
    animation: 2s contents none;

} 
h1{
    color: rgba(15, 17, 15, 0.914);
    font-size: 50px;
    text-transform: capitalize;
}
@keyframes contents{
    0%{
        transform: translatex(-100px);
        opacity: 0;
    }
    100%{
transform: none;
opacity: 1;    
    }
}
h3{
    width: 600px;
    color: rgb(43, 85, 122);
    text-align: justify;
    font-weight: 400;
}
.buttons{
    position: absolute;
    top: 110%;

}
button{
    padding: 20px;
    border-radius: 60px;
width: 200px;
background: #fc0254;
color: antiquewhite;
border: none;
outline: none;
cursor: pointer;
font-weight: 400;
font-family: montserrat,sans-serif;
letter-spacing: 1px;
box-shadow: 0px 2px 10px #000;

}
.button{
    padding: 20px;
    border-radius: 60px;
width: 200px;
background: #383b70;
color: antiquewhite;
border: none;
outline: none;
cursor: pointer;
font-weight: 400;
font-family: montserrat,sans-serif;
letter-spacing: 1px;
box-shadow: 0px 2px 10px #000;
margin: 0px 10px;
}


HTML CODE
<html>
<head>
<title>zongmaaza music</title>
<link rel="stylesheet" href="music.css" type="text/css">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300&display=swap" rel="stylesheet">


</head>

<body>
    <div class="box">
<div class="menu">
    <ul>
        <li><a href="index.html">Home</a> </li>
        <li><a href="">About</a> </li>
        <li><a href="">Discover</a></li>
        <li><a href="">My Library</a></li>
        <li><a href="">news</a></li>
        <li><a href="">Contact</a></li>
        <li></li>
        <li class="user">
            <a href="" class="h" >Help</a>
            <span>|</span>
           <a href=""><h4>Login</h4></a>
            <h5 class="signup">Create an account</h5>
        </li>


    </ul>
    <div class="symb">
        <h2><font>zong</font>maaza</h2>

    </div>
    <div>

    </div>
    <div class="image">
        <img src="images\AR-rahman-black-and-white-image.jpg" height="700" width="1700">
    </div>
    <div class="contents">
        <h1><font>Listen </font>to new music</h1>
        <h3>Beautiful music is the art of the prophets that can calm the agitations of the soul,
            it is one of the most magnificent and delightful presents God has given us.</h3>
<div class="buttons">
    <button>Sign in</button>
   <a href="start.html"><button class="button2">Start free trial</button><a </a>

</div>
    </div>

</div>
    </div>






</body>
















</html>
