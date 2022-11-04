<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://getbootstrap.com/docs/5.2/assets/css/docs.css" rel="stylesheet">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Audiowide|Sofia|Trirong">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Oswald|Noto+Sans">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="stylesheet.css">
    <script src="https://kit.fontawesome.com/cd46a65f5c.js" crossorigin="anonymous"></script>


    <title>Mo'ath's Portfolio</title>

    <style>


*{
    margin: 0;
    padding: 0;
    border: 0;
}
#homediv{
    height: 100%;

    padding-top: 50px;
    background-image: url(Pictures/used.jpg);
    background-size: contain;

}
label .menu {
  position: absolute;
  right: -100px;
  top: -110px;
  z-index: 100;
  width: 200px;
  height: 50px;
  background: #333;
  border-radius: 10% 10% 10% 10%;
  -webkit-transition: .5s ease-in-out;
  transition: .5s ease-in-out;
  box-shadow: 0 0 0 0 #fff, 0 0 0 0 #fff;
  cursor: pointer;
  
}
#ulm{
  position: absolute;
  top: 200px;

}


label .hamburger {
  position: absolute;
  top: 135px;
  left: 50px;
  width: 30px;
  height: 2px;
  background: #69D2e7;
  display: none;
  -webkit-transform-origin: center;
  transform-origin: center;
  -webkit-transition: .5s ease-in-out;
  transition: .5s ease-in-out;
}

label .hamburger:after, label .hamburger:before {
  -webkit-transition: .5s ease-in-out;
  transition: .5s ease-in-out;
  content: "";
  position: absolute;
  display: block;
  width: 100%;
  height: 100%;
  background: #69d2e7;
}

label .hamburger:before { top: -10px; }

label .hamburger:after { bottom: -10px; }

label input { display: none; }

label input:checked + .menu {
  box-shadow: 0 0 0 100vw #FFF, 0 0 0 100vh #fff;
  border-radius: 0;
  
}

label input:checked + .menu .hamburger {
  -webkit-transform: rotate(45deg);
  transform: rotate(45deg);
  
}

label input:checked + .menu .hamburger:after {
  -webkit-transform: rotate(90deg);
  transform: rotate(90deg);
  bottom: 0;
  
}

label input:checked + .menu .hamburger:before {
  -webkit-transform: rotate(90deg);
  transform: rotate(90deg);
  top: 0;
  
}

label input:checked + .menu + ul { opacity: 1; }

label ul {
  z-index: 200;
  position: absolute;
  top: 50%;
  left: 50%;
  -webkit-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  opacity: 0;
  -webkit-transition: .25s 0s ease-in-out;
  transition: .25s 0s ease-in-out;
}

label a {
  margin-bottom: 1em;
  display: block;
  color: #f38630;
  text-decoration: none;
  
}



#cont{
    display: flex;
    justify-content: space-around;  
    text-align: center;
    flex-direction: row;
    flex-wrap: wrap;
    overflow: hidden;
   
   
    
    

    
      }
    
      


.hh1{
   padding-top: 100px;
    font-family: "Audiowide", sans-serif;
    font-size: 50px;
   
   }
   .hh7{
   
     font-family: "Audiowide", sans-serif;
     font-size: 50px;
    
    }
   #hh2{
   
    
    font-family: "Trirong", serif;
    font-size: 30px;
   
   
   }
   #hh3{
   
    
    font-family: "Trirong", serif;
    font-size: 20px;
   
   }
   #textdiv{
    width: 35%;
    text-align: center;
    margin-left: 7%;
    margin-right: 7%;
   }
   .resume{
    
   
    background-color: #fafafa;
     color: black;
    border: 2px solid #555555;
    padding: 16px 32px;
    font-size: 16px;
    transition-duration: 0.4s;
    cursor: pointer;
  }
   
    

  .resume:hover {
    background-color: #555555;
    color: white;}
    .mynav{
        background-color: #333;
        color: azure;
        
        padding-top: 10px;
        display: flex;
      justify-content: right;
        
        position: fixed;
       
       
        width: 100vw;
        height: 50px;
        z-index: 2;
        
      
    }
    .mynav2{
        display: flex;
        flex-direction: row;
        list-style:none ;
        justify-content: space-around;
        
        width: 50%;
        padding-right: 300px;
        color: #fafafa;
        
       
      
       
       
    }
    .bars{
        font-size: 28px;
       color: #333;

    }

    #navimg{
        position: absolute;left: 200px ;top: 20px;

    }
   
    
    

   
    .parallax{
        background:url(Pictures/edu.jpg) repeat fixed 100%;
        height: 100%;
       

    }
    .parallax-inner{
        padding: 20% 0%;
    }
    #parrah1{
        font-family: "Audiowide", sans-serif;
        font-size: 50px;
        color: azure;
        text-align: center;
        

    }


    .parallax2{
    
    
      background:url(Pictures/inspire4.jpg) repeat fixed 100%;
      background-repeat: no-repeat
    ;
    background-size: cover;
      height: 100%;

  }
  .parallax-inner2{
      padding: 3% 0%;
  }
  #parrah2{
      font-family: "Audiowide", sans-serif;
      font-size: 50px;
      color: #847e7e;
      text-align: center;
     

  }


  
  .parallax3{
    background:url(Pictures/pho.jpg) repeat fixed 100%;
    background-repeat: no-repeat
  ;
  background-size: cover;
    height: 100%;

}
.parallax-inner3{
    padding: 10% 0%;
}
#parrah3{
    font-family: "Audiowide", sans-serif;
    font-size: 50px;
    color: #fefefe;
    text-align: center;
   

}



    #educationdiv{
       
        background-color: #fafafa;
       
        background-image: url(Pictures/used.jpg);
   
        background-size: contain;
        padding: 0% 10%;
        width: 100%;
       
        
    }
    
#gif{


border-radius: 100%;

}
#EDU1{
display: flex;
flex-wrap: wrap;


padding: 1% 1%;

border: 2px solid black;
text-align: center;
height: fit-content;
justify-content: space-around;

}


#edupic1{
   
    width: 250px;

}
#edupic2{
    
    width: 400px;
    overflow:hidden;
  

}
.margin{
margin-top: 3%;
}
.text3{
font-family: "Space Mono", monospace;
font-size: 25px;
margin: 2% 0%;
width: 17rem;
max-height: 400px;


}
.text4{
font-family: "Noto Sans", sans-serif;
font-size: 16px;
}
#EDU2{
    
display: flex;
justify-content:space-around;
flex-wrap: wrap;

padding: 1% 1%;

border: 2px solid black;
text-align: center;


}
#accec2div{
background-image: url(Pictures/accec2.jpeg);
height: 350px;
width: 350px;

background-position: center;
}
#accec3div{
    background-image: url(Pictures/accec1.jpg);
    height: 350px;
    width: 500px;
    background-size: contain;
    background-repeat: no-repeat;
    
    background-position: center;
    }
#EDU3{
display: flex;
justify-content:space-around;
flex-wrap: wrap;
padding: 1% 1%;
border: 2px solid black;
text-align: center;

}
#innovationdiv{
background-image: url(Pictures/innovation1.jpeg);
height: 350px;
width: 350px;
background-size: cover;
background-position: center;
}
#innovationdiv2{
    background-image: url(Pictures/innovation2.jpeg);
    height: 350px;
    width: 500px;
    background-size: cover;
    background-position: center;
    }
.header {
text-align: center;
padding: 32px;
}
.hidegallery{
    overflow: hidden;
    padding-left: 19px;
}

.row {
display: flex;
flex-wrap: wrap;
padding: 0 4px;

overflow: hidden;

}
.row2 {
display: flex;
justify-content: space-between;
flex-wrap: wrap;
overflow: hidden;



}


.column {
flex: 25%;

min-width: 200px;
padding: 0 4px;
overflow: hidden;
}

.column img {
margin-top: 8px;
vertical-align: middle;
}
#gallary{
height: 100%;
background-image: url(Pictures/used.jpg);
background-size: contain;

}
#gallary2{
height: 100%;
background-image: url(Pictures/used.jpg);
background-size: contain;
padding-top: 30px;
width: 100%;

}
#gallary3{
height: 100%;
background-image: url(Pictures/used.jpg);
background-size: contain;
padding-top: 30px;
width: 100%;

}
#experience{
height: 100%;
background-image: url(Pictures/used.jpg);
background-size: contain;
}
#expcontainer{
display: flex;
justify-content: space-around;
flex-wrap: wrap;
padding-top: 10%;
padding-bottom: 10%;
height: 100%;
text-align: center;
overflow: hidden;

}
#exp1{
background-image: url(Pictures/exp.png);
height: 550px;
width: 400px;
background-repeat: no-repeat;

background-size: cover;
position: relative;
}
#exp1pic1{
position: absolute;
top: 68px;

left: 160px;
margin: auto;
height: 150px;
width: 200px;
background-size: cover;

border: 7px solid #686a48;
background-image: url(Pictures/exp1pic1.jpg);
}
#exp1pic2{
position: absolute;
bottom: 50px;

height: 150px;
width: 200px;
background-size: cover;
border: 7px solid #686a48;


background-image: url(Pictures/exp1pic2.jpg);
}
#exp2{
background-image: url(Pictures/exp.png);
height: 550px;
width: 400px;
background-repeat: no-repeat;

background-size: cover;
position: relative;
transform: scaleX(-1);

}
#exp2pic1{
position: absolute;
top: 68px;

left: 160px;
margin: auto;
height: 150px;
width: 200px;
background-size: cover;
transform: scaleX(-1);


border: 7px solid #686a48;
background-image: url(Pictures/eure1.jpeg);

}
#exp2pic2{
position: absolute;
bottom: 50px;

height: 150px;
width: 200px;
background-size: cover;
border: 7px solid #686a48;
transform: scaleX(-1);


background-image: url(Pictures/eure2.jpeg);
}
#exp3{
background-image: url(Pictures/exp.png);
height: 550px;
width: 400px;
background-repeat: no-repeat;

background-size: cover;
position: relative;
}
#exp3pic1{
position: absolute;
top: 68px;

left: 160px;
margin: auto;
height: 150px;
width: 200px;
background-size: cover;

border: 7px solid #686a48;
background-image: url(Pictures/ebtik1.JPG);
}
#exp3pic2{
position: absolute;
bottom: 50px;

height: 150px;
width: 200px;
background-size: cover;
border: 7px solid #686a48;


background-image: url(Pictures/ibtik3.jpg);
}




#skills{



height: 100%;
display: flex;
justify-content: space-between;
flex-wrap: wrap;
padding: 10% 15%;
background-image: url(Pictures/used.jpg);
text-align: center;
background-size: contain;


}
#skills2{

height: 100%;
display: flex;
justify-content: space-between;
flex-wrap: wrap;
padding: 10% 15%;
background-image: url(Pictures/used.jpg);
text-align: center;
background-size: contain;


}
#headerskills{

font-family: "Space Mono", monospace;
font-size: 25px;

width: 100%;
padding-top: 5%;
padding-bottom: 5%;
border: 2px solid rgb(255, 255, 255);
background-color: #8ccd91;
border-radius: 10px;
color: #fafafa;

box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2), 0 6px 20px 0 rgba(0,0,0,0.19);
}
#headerskills2{

font-family: "Space Mono", monospace;
font-size: 25px;

width: 100%;
padding-top: 5%;
padding-bottom: 5%;
border: 2px solid rgb(255, 255, 255);
background-color: #8c93cd;
border-radius: 10px;
color: #fafafa;

box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2), 0 6px 20px 0 rgba(0,0,0,0.19);
}
#skillsnames{
display: flex;
flex-direction: column;
height: 300px;
width: 18%;
justify-content: space-around;

border: 2px solid black;
background-color: #fafafa;
border-radius: 10px;

box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2), 0 6px 20px 0 rgba(0,0,0,0.19);

}
.button1 {

background-color: #4CAF50;
color: white;
border: 2px solid #4CAF50;
width: 210px; padding: 10px 1px;


}

.button1:hover  {
background-color: white; 
color: black; 


}

.button2 {
background-color: #008CBA;
color: white;
border: 2px solid #008CBA;
width: 210px; padding: 10px 1px;
}

.button2:hover {

background-color: white; 
color: black; 
}

.button3 {
background-color: #f44336;
color: white;

border: 2px solid #f44336;
width: 210px; padding: 10px 1px;
}

.button3:hover {

background-color: white; 
color: black; 
}

.button4 {
background-color: #e7e7e7;
border: 2px solid #e7e7e7;
width:210px; padding: 10px 2px;
}

.button4:hover {
background-color: white;
color: black;
}

.button5 {
background-color: white;
color: black;
border: 2px solid #555555;
width: 210px; padding: 10px 1px;
}

.button5:hover {
background-color: #555555;
color: white;
}
#none{
width: 100%;
font-size: 50px;
display: none;
}
#none2{
width: 100%;
font-size: 50px;
display: none;
}
.button5:hover + #none{display: block;}
.button4:hover + #none2{display: block;}
#emotional{
width: 100%;
display: none;
font-size: 25px;
font-family: "Brush Script MT", cursive;
}
.button1:hover + #emotional{display: block;}
#growth{
width: 100%;
display: none;
font-size: 20px;
font-family: "Brush Script MT", cursive;

}
#emotional2{
width: 100%;
display: none;
font-size: 25px;
font-family: "Brush Script MT", cursive;
}
.button1:hover + #emotional2{display: block;}
#growth{
width: 100%;
display: none;
font-size: 20px;
font-family: "Brush Script MT", cursive;

}
.button2:hover + #growth{display: block;}
#opens{
height: 80%;
display: none;
font-size: 25px;
font-family: "Brush Script MT", cursive;

}
#growth2{
width: 100%;
display: none;
font-size: 20px;
font-family: "Brush Script MT", cursive;

}
.button2:hover + #growth2{display: block;}
#opens{
height: 80%;
display: none;
font-size: 25px;
font-family: "Brush Script MT", cursive;

}
.button3:hover + #opens{display: block;}
#adapt{
width: 100%;
display: none;
font-size: 25px;
font-family: "Brush Script MT", cursive;

}
#opens2{
height: 80%;
display: none;
font-size: 25px;
font-family: "Brush Script MT", cursive;

}
.button3:hover + #opens2{display: block;}
#adapt{
width: 100%;
display: none;
font-size: 25px;
font-family: "Brush Script MT", cursive;

}
.button4:hover + #adapt{display: block;}
#adapt2{
width: 100%;
display: none;
font-size: 25px;
font-family: "Brush Script MT", cursive;

}
.button4:hover + #adapt2{display: block;}

.card {
box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
max-width: 300px;
margin: auto;
text-align: center;
font-family: arial;
}

.title {
color: grey;
font-size: 18px;

}

.buttonc {
border: none;
outline: 0;
display: inline-block;
padding: 8px;
color: white;
background-color: #000;
text-align: center;
cursor: pointer;
width: 100%;
font-size: 18px;
}


.buttonc:hover, a:hover {
opacity: 0.7;
}
.cerifi{

display: flex;
justify-content: space-between;
flex-wrap: wrap;
padding: 50px 5%;
width: 100%;

}
.ac {

text-decoration: none;
font-size: 22px;
color: black;
}
.containerlang {
width: 100%;
background-color: #ddd;

}

.lang {
text-align: right;
padding-top: 10px;
padding-bottom: 10px;
color: white;
}

.arabic {width: 90%; background-color: #04AA6D;}
.english {width: 80%; background-color: #2196F3;}

.langsec{
   
 padding-left: 20%;
text-align: center;
display: flex;
flex-direction: column;
justify-content: center;

width: 80%;
}


#certificates{
display: flex;
height: 100%;

justify-content: space-around;

flex-wrap: wrap;




}
#cetificatestitle{
text-align: center; width: 100%;
padding-bottom: 50px;
padding-top: 50px;

font-family: "Audiowide", sans-serif;
border: 1px solid rgba(0, 0, 0, 0.202);


}
#leftside{

height: 600px;
width: 40%;
background-color: #d4d897;
text-align: center;

padding: 5% 5%;



}
.cece {
max-width: 500px;
min-width: 300px;
box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
text-align: center;
margin-top: 50px;
}

.cece2 {
padding: 10px;
}










.footer-distributed{
background: rgb(131, 130, 130);
box-shadow: 0 1px 1px 0 rgba(0, 0, 0, 0.12);

width: 100%;
text-align: left;
font: bold 16px sans-serif;
padding: 15px 10px;
}

.footer-distributed .footer-left,
.footer-distributed .footer-center,
.footer-distributed .footer-right{
display: inline-block;
vertical-align: top;
}



.footer-distributed .footer-left{
width: 40%;
padding-top: 20px;
}











.footer-distributed .footer-links a{
display:inline-block;
line-height: 1.8;
font-weight:400;
text-decoration: none;
color:  #fafafa;
padding-top: 5px;
}





.footer-distributed .footer-center{
width: 35%;
}

.footer-distributed .footer-center i{
background-color:  #33383b;
color: #ffffff;
font-size: 25px;
width: 38px;
height: 38px;
border-radius: 50%;
text-align: center;
line-height: 42px;
margin: 5px 15px;
vertical-align: middle;
}

.footer-distributed .footer-center i.fa-envelope{
font-size: 12px;

}

.footer-distributed .footer-center p{
display: inline-block;
color: #ffffff;
font-weight:400;
vertical-align: middle;
margin:0;
}

.footer-distributed .footer-center p span{
display:block;
font-weight: normal;
font-size:12px;
line-height:2;
}

.footer-distributed .footer-center p a{
color:  rgb(51, 32, 178);
text-decoration: none;
}

.footer-distributed .footer-links a:before {
content: "|";
font-weight:300;
font-size: 14px;
left: 0;
color: #fff;
display: inline-block;
padding-right: 5px;
}

.footer-distributed .footer-links .link-1:before {
content: none;
}



.footer-distributed .footer-right{
width: 20%;
}





.footer-distributed .footer-icons{
margin-top: 10px;
}

.footer-distributed .footer-icons a{
display: inline-block;
width: 35px;
height: 35px;
cursor: pointer;
background-color:  #33383b;
border-radius: 2px;

font-size: 13px;
color: #ffffff;
text-align: center;
line-height: 35px;

margin-right: 3px;
margin-bottom: 5px;
}


@media (max-width: 880px) {

.footer-distributed{
font: bold 14px sans-serif;
}

.footer-distributed .footer-left,
.footer-distributed .footer-center,
.footer-distributed .footer-right{
display: inline-block;
width: 100%;
margin-bottom: 4px;
text-align: center;
}

.footer-distributed .footer-center i{
margin-left: 0;
}

}




#teensummit{
font-size: 21px;
color: #fafafa;
position: absolute;
top: 10px;
left: 25px;
}
#summitexplain{
position: absolute;
text-align: left;
color: #fafafa; 
width: 140px;
top: 80px;
left: 10px;

}
#at2016{
position: absolute;
text-align: center;
color: #fafafa; 
width: 140px;
top: 255px;
left: 130px;
font-size: 35px;


}

#summitsample{
position: absolute;
text-align: right;
color: #fafafa; 
width: 140px;
bottom: 30px;
right: 10px;


}








#exp2ti{
font-size: 25px;
color: #fafafa;
position: absolute;
top: 10px;
left: 150px;
transform: scaleX(-1);
}
#exp2exp{
position: absolute;
text-align: right;
color: #fafafa; 
width: 140px;
top: 80px;
left: 10px;
transform: scaleX(-1);

}
#exp2date{
position: absolute;
text-align: center;
color: #fafafa; 
width: 140px;
top: 255px;
left: 130px;
font-size: 35px;
transform: scaleX(-1);


}

#exp2exp2{
position: absolute;
text-align: left;
color: #fafafa; 
width: 155px;
bottom: 6px;
left: 238px;
transform: scaleX(-1);


}
#exp3ti{
font-size: 21px;
color: #fafafa;
position: absolute;
top: 10px;
left: 25px;
}
#exp3exp{
position: absolute;
text-align: left;
color: #fafafa; 
width: 140px;
top: 80px;
left: 10px;

}
#exp3date{
position: absolute;
text-align: center;
color: #fafafa; 
width: 140px;
top: 255px;
left: 100px;
font-size: 35px;



}

#exp3exp2{
position: absolute;
text-align: left;
color: #fafafa; 
width: 140px;
bottom: 0px;
right: 10px;




}



@media only screen and (min-device-width: 481px) and (max-device-width: 768px){
    .mynav2{
      display: none;
      

  }
  p.footer-links{
    display: none;
  }
  .footer-distributed .footer-left{
    padding: 0%;
  }
  .footer-company-about{
    display: none;
  }
  label .hamburger {
    display: block;
  }
  .bars{
    color: azure;
      display:block;
  }

  #navimg{
    left: 20px;
  }

  .parallax{

    background-size: 200%;
    background-repeat: no-repeat;
    background-position-x: center;
   }


   #column4{
    display: none;
   }
   #mypic1{
    height: 500px;
   }
   #mypic2{
    height: 500px;
   }
   
   #textdiv{
    width: 33%;
    margin: 0%;
   }
   .hh1{
    font-size: 30px;
   
   }
   .hh7{
    font-size: 30px;
   }
   #gif{
    height: 50px;
   }
   #hh2{
    font-size: 15px;
   }
   #hh3{
    font-size: 13px;
   }
   .resume{
    margin-bottom: 110px;
   }
   #edupic1{
    margin-bottom: 30px;
    margin-right: 20px;
   }
   #edupic2{
    margin-bottom: 30px;
    margin-right: 20px;
   }

   



  }
  @media only screen and (min-device-width: 0) and (max-device-width: 480px){
      .mynav2{
          display: none;
          
  
      }
      label .hamburger {
        display: block;
      }
      #textdiv{
        width: 80%;
        padding: 0% ;
      }
      .resume{
        margin-bottom: 30px;
      }
      #edupic21{
        width: 250px;
      }
     
      #parrah2{
        font-size: 35px;
      }
      #mypic2{
        height: 650px;
      }
      #mypic1{
        height: 650px;
      }
      p.footer-links{
        display: none;
      }
      .footer-distributed .footer-left{
        padding: 0%;
      }
      .footer-company-about{
        display: none;
      }   
      div.row{
        justify-content: center;
        width: 300px;
        height: 500px;
        overflow: scroll;
      }
      .bars{
        color: azure;
          
          display:block;
      }

      #navimg{
        left: 20px;
      }

      
      #hh7{

        font-size: 30px;
      }

      .parallax{

       background-size: 390%;
       background-repeat: no-repeat;
       background-position-x: center;
      }


      #summitsample{

       display: none;
      }
      #exp2exp2{

        display: none;

      }
      #exp3exp2{

        display: none;

      }

   
      
    


      

     




  
  
  
   
  }



















    

  



  



    </style>
   
</head>
<body style="background-image:url(used.jpg) ;background-size:contain;">

   <div class="mynav">
    <img src="Pictures/MyLogo3.png" height="15px" id="navimg" >
        
        <ul class="mynav2 ">
            <li>
                <a class="nav-link" href="">Home</a>
            </li>
            <li>
                <a class="nav-link" href="#educationdiv">Education</a>
            </li>
            <li>
                <a class="nav-link" href="#expcontainer">experience</a>
            </li>
            <li>
                <a class="nav-link" href="#skills">skills</a>
            </li>
            <li>
                <a class="nav-link" href="#cerifi">references</a>
            </li>
            <li>
                <a class="nav-link" href="#certificates">certificates</a>
            </li>
            <li>
              <a class="nav-link" href="#gallary">Gallery</a>
          </li>
        </ul>

        <label>
          <input type="checkbox">
          <span class="menu"> <span class="hamburger"></span> </span>
          <ul id="ulm">
            
            
            <li> <a href="#">Home</a> </li>
            <li> <a href="#">Education</a> </li>
            <li> <a href="#">experience</a> </li>
            <li> <a href="#">Contact</a> </li>
            <li> <a href="#">skills</a> </li>
            <li> <a href="#">references</a> </li>

            <li> <a href="#">certificates</a> </li>

            <li> <a href="#">Gallery</a> </li>

           

          </ul>
          </label>
       
         

    </div> 
 

    

    
        <div id="homediv" >

      
       
          <div id="cont">
          <div id="hpmepic1" >
              <img id="mypic1" src="Pictures/88.png" height="900px"  >
          </div>
          <div id="textdiv">
              <p class="hh1">
                  Mo'ath Bdour 
              </p><p class="hh7">Portfolio</p>
              <img src="Pictures/23.gif" height="120px" id="gif" >
              <p id="hh2">
                  Hello!
  
              </p>
              
              <p id="hh3">
                I’m Moath Bdour, a civil engineering student in Jordan university of science and 
                technology. I believe that the human mission on earth is to build it, and it’s 
                clearly the direct job for civil engineering, so this is the major reason why I love it.
                To be honest, one of my biggest dreams is to be able to travel around the world 
                and to explore the wonders that are hidden like what the ancient travelers did
                
                     
              </p>
              <a type="button" class="resume" value="Download Resume" href="https://drive.google.com/file/d/1enYrhnAr1eABPvuOfbijwTAGF4TjcGGy/view?usp=sharing" target="_blank" > Download Resume</a>
          </div>
          <div id="homepic2" >
              <img id="mypic2" src="Pictures/77.png" height="900px" >
          </div>
      </div>
  
        
     
  
        
         
  
      </div>
  
  
          
          <section class="parallax">
              <div class="parallax-inner">
                  <p id="parrah1"> Welcome to my<br> Portfolio</p>
              </div>
          </section>
          
  
  
  
  
  
  <h1 style="text-align:center ;">Education</h1>
          <div id="educationdiv">
             
                  <div id="EDU1">
                    <div id="edupic1"><img src="Pictures/EDU1.jpg" width="200px"> </div> 
                    <div id="edupic2"><img id="edupic21" src="Pictures/1.1.jpg" width="450px"> </div> 
                      
                      <div class="text3" >
                      
                           <img src="Pictures/just.png" height="75px" width="75px"  >
                          <p >Jordan University of Science and Technology</p> <p class="text4">I got a BCs degree in Civil Engineering with Excellent Grade </p><p>2017-2022</p>
                     </div>
                     
                     
                     
      
                  </div>
                  <div id="EDU2">
                      <div id="accec2div"> </div>
                      <div id="accec3div"> </div>
                      
                      
                     
                      <div class="text3" >
                           <img src="Pictures/accessimg.jpg" height="75px" width="75px"  >
                          <p >Access Program</p> <p class="text4">The "Access" program is a two-year experience for students, providing them with 480 hours of English language instruction and a number of diverse enhancement activities.</p><p>2017-2022</p></li>
                     </div>
                     
                     
                     
      
                  </div></li>
                  <li><div id="EDU3">
                      <div id="innovationdiv"> </div>
                      <div id="innovationdiv2"> </div>
                      
                      
                     
                      <div class="text3" >
                      <ul style="list-style-type: none; ">
                          <li> <img src="Pictures/innovationlab.jpg" height="75px" width="75px"  ></li>
                          <li> <p >Innovation Labs</p> <p class="text4">The Innovation Labs Clubhouses is a space where students 10-24 years are given mentoring and guidance to create projects that impact social change.</p><p>2010-2022</p></li>
                      </ul></div>
                     
                     
                     
      
                  </div></li>
              </ul>
              
             
              
       
      </div>
  
  
  
      <div id="experience">
          <div id="expcontainer">
              <div id="exp1">
                <p id="teensummit">Teen Summit At USA</p>
                <p id="summitexplain">Leadership event where Youth come together to foster global community in Boston-America</p>
                <p id="summitsample">Youth leaders participate in hackathons designed to address global issues through creativity and technology.</p>
                <p id="at2016">2016</p>
                  <div id="exp1pic1"></div>
                  <div id="exp1pic2"></div>
  
              </div>
              <div id="exp2">
                <p id="exp2ti">Eureka</p>
                <p id="exp2exp">two Mobile Labs; a general science lab and an environment-themed lab.</p>
                <p id="exp2exp2">The mobile labs aimed to provide students , opportunities and tools to interact with and implement different scientific experiments and environment-focused activities .</p>
                <p id="exp2date">2016</p>
                  <div id="exp2pic1"></div>
                  <div id="exp2pic2"></div>
  
              </div>
              <div id="exp3">
                <p id="exp3ti">Ebtekarthon</p>
                <p id="exp3exp">Ebtekarthon aims to develop and support innovative entrepreneurial projects to add a social dimension to their existing </p>
                <p id="exp3exp2"> It provides a learning environment through a group of experts and specialists who support and add valuable knowledge </p>
                <p id="exp3date">2019+2017</p>
                  <div id="exp3pic1"></div>
                  <div id="exp3pic2"></div>
  
              </div> 
              
  
  
  
          </div>
  
  
  
  
      </div>

      <div class="langsec">
        <h1>Languages</h1>

<p>Arabic</p>
<div class="containerlang">
<div class="lang arabic">90%</div>
</div>

<p>English</p>
<div class="containerlang">
<div class="lang english">80%</div>
</div>
</div> 
  
      <div id="skills">
          <div id="headerskills">
              <h1>Soft Skills</h1>
              <p>these are some of my soft skills</p>
            </div>
  
  
            
        
             <div id="gallary2">
              
              <div class="row2"> 
                  <div class="column">
                      <button class="button button1">Emotional Intelligence</button>
                    <div id="emotional"><img  src="Pictures/emotional.png" style="width:100%">
                      <p>I have the ability to recognize and manage emotions and the emotions of others.</p>
  
                    </div>
                   
                  </div>
                  
                  <div class="column">
                      <button  class="button button2"> Growth Mindset</button>
                    <div id="growth"><img src="Pictures/GROWTH.png" style="width:70%"> <p> I look at a failure to meet a quarterly goal as an opportunity to identify their strengths and weaknesses to tackle the next quarter's goal</p></div>
                   
                  </div> 
                   
                  <div class="column">
                      <button class="button button3"><div id="blue">Openness to Feedback</div> </button>
                    <div id="opens"><img src="Pictures/opens.png" style="width:100%"><p>I accept any feedbacks and  appreciate for their willingness to provide this helpful information</p></div>
                    
                  </div>
                  
                  <div class="column">
                      <button class="button button4"><div id="blue">Adaptability</div></button>
                   <div id="adapt"> <img src="Pictures/adapt.png" style="width:100%"><p>I have the ability to adapt to change — and a positive attitude about change — go a long way toward growing a successful career.</p></div>
                  
                  </div>
                  
                </div>
              </div>
          </div>
     
  
          <div id="skills2">
              <div id="headerskills2">
                  <h1>technical Skills</h1>
                  <p>these are some of my technical Skills </p>
                </div>
      
      
                
            
                 <div id="gallary3">
                  
                  <div class="row2"> 
                      <div class="column">
                          <button class="button button1">Photography</button>
                        <div id="emotional2"><img  src="Pictures/photog.png" style="width:100%">
                          <p>Im a photographer ,  videomaker and graphic designer , also i won some prizes in these fields</p>
                          
      
                        </div>
                       
                      </div>
                      
                      <div class="column">
                          <button  class="button button2"> 3D-Modeling</button>
                        <div id="growth2"><img src="Pictures/3d.png" style="width:70%"> <p>I'm intermediate at 3D-Modeling and im using Cinema-4D And Adobe After Effect</p>
                         
                        </div>
                       
                      </div> 
                       
                      <div class="column">
                          <button class="button button3"><div id="blue">Steel Structures design</div> </button>
                        <div id="opens2"><img src="Pictures/steel.jpg" style="width:100%"><p>I have the ability to design steel structures ether manual or using programs.</p>
                         
                        </div>
                        
                      </div>
                      
                      <div class="column">
                          <button class="button button4"><div id="blue">Front-End Programmer</div></button>
                       <div id="adapt2"> <img src="Pictures/front.png" style="width:100%"><p>im very good as Front-End Programmer and im using HTML and CSS Right now</p>
                       
                      </div>
                      
                      </div>
                      
                    </div>
                  </div>
              </div>

  
  
  
   <section class="parallax2">
    <div class="parallax-inner2">
        <p id="parrah2">  references </p>
    </div>
  </section>  
  
  
  
  
              <div class="cerifi">
                  <div class="card">
                      <img src="Pictures/dana.png" style="width:100%">
                      <h1>Dana Abu Areda</h1>
                      <p class="title">PhD in English Literature
                      </p>
                      <div style="margin: 24px 0;">
                        <a class="ac" href="#"><i class="fa fa-twitter"></i></a>  
                        <a class="ac" href="#"><i class="fa fa-linkedin"></i></a>  
                        <a class="ac" href="#"><i class="fa fa-facebook"></i></a> 
                      </div>
                    
                      <p><button class="buttonc">Contact</button></p>
                    </div>
                    <div class="card">
                      <img src="Pictures/asmaa.jpg"  style="width:100%">
                      <h1>Asmaa Taha</h1>
                      <p class="title">Innovation labs coordinator</p>
                      <div style="margin: 24px 0;">
                        <a class="ac" href="#"><i class="fa fa-twitter"></i></a>  
                        <a class="ac" href="#"><i class="fa fa-linkedin"></i></a>  
                        <a class="ac" href="#"><i class="fa fa-facebook"></i></a> 
                      </div>
                    
                      <p><button class="buttonc">Contact</button></p>
                    </div>
                    <div class="card">
                      <img src="Pictures/rajaee.jpg"  style=" object-fit: contain; width:100%" height="200px  " >
                      <h1>Rajae Alrousan</h1>
                      <p class="title">Civil Engineer Prof. At Just University </p>
                      <div style="margin: 24px 0;">
                        <a class="ac" href="#"><i class="fa fa-twitter"></i></a>  
                        <a class="ac" href="#"><i class="fa fa-linkedin"></i></a>  
                        <a class="ac" href="#"><i class="fa fa-facebook"></i></a> 
                      </div>
                    
                      <p><button class="buttonc">Contact</button></p>
                    </div>
                   
                    
   
              </div>
  
  
  
              <div id="certificates">
                <h1 id="cetificatestitle"> certificates </h1>
               
                <div class="verc">
  
  
                  <div class="cece">
                    <img src="Pictures/certi1.jpg" style="width:100%">
                    <div class="cece2">
                      <p>Access Program</p>
                    </div>
                  </div>
                  <div class="cece">
                    <img src="Pictures/certi2.jpg" style="width:100%">
                    <div class="cece2">
                      <p>KG1</p>
                    </div>
                  </div>
                  
                </div>
  
                <div class="verc">
  
                  <div class="cece">
                    <img src="Pictures/certi3.jpg" style="width:100%">
                    <div class="cece2">
                      <p>Quraan</p>
                    </div>
                  </div>
                  <div class="cece">
                    <img src="Pictures/certi4.jpg" style="width:100%  ">
                    <div class="cece2">
                      <p>Undergraduate Studies</p>
                    </div>
                  </div>
                  
                </div>
  
  
  
  
              </div>


              <section class="parallax3">
                <div class="parallax-inner3">
                    <p id="parrah3"> My Gallary<br>these are samples of my work</p>
                </div>
            </section> 
             


                  <div id="gallary">
      <div class="header">
          <h1>My Gallary </h1>
          <p>these are samples of my work</p>
        </div>
        <div class="hidegallery">
      <div class="row"> 
          <div class="column">
            <img src="Pictures/EDU3.jpeg" style="width:100%">
            <img src="Pictures/B.jpg" style="width:100%">
            <img src="Pictures/C.jpg" style="width:100%">
            <img src="Pictures/D.jpg" style="width:100%">
            <img src="Pictures/E.jpg" style="width:100%">
            <img src="Pictures/A.jpg" style="width:100%">
           
          </div>
          
          <div class="column">
            <img src="Pictures/g.jpg" style="width:100%">
            <img src="Pictures/a12.jpg" style="width:100%">
            <img src="Pictures/i.jpg" style="width:100%">
            <img src="Pictures/j.jpg" style="width:100%">
            <img src="Pictures/k.jpg" style="width:100%">
            <img src="Pictures/l.jpg" style="width:100%">
          </div> 
           
          <div class="column">
            <img src="Pictures/m.jpg" style="width:100%">
            <img src="Pictures/a5.jpg" style="width:100%">
            <img src="Pictures/o.jpg" style="width:100%">
            <img src="Pictures/p.jpg" style="width:100%">
            <img src="Pictures/q.jpg" style="width:100%">
            <img src="Pictures/a14.jpg" style="width:100%">
            <img src="Pictures/s.jpg" style="width:100%">
          </div>
          
          <div class="column" id="column4">
            <img src="Pictures/a9.jpg" style="width:100%">
            <img src="Pictures/u.jpg" style="width:100%">
            <img src="Pictures/v.jpg" style="width:100%">
            <img src="Pictures/a13.jpg" style="width:100%">
            <img src="Pictures/x.jpg" style="width:100%">
            <img src="Pictures/y.jpg" style="width:100%">
          </div>
        </div>
      </div>
      </div> 
  
  





            <footer class="footer-distributed">

              <div class="footer-left">
        
                <img src="Pictures/MyLogo3.png" height="15px" >
        
                <p class="footer-links">
                  <a href="#" class="link-1">Home</a>
                  
                  <a href="#educationdiv">Edcation</a>
                
                  <a href="#expcontainer">experience</a>
                
                  <a href="#skills">skills</a>
                  
                  <a href="#gallary">Gallery</a>
                  
                  <a href="#certificates">certificates</a>
                </p>
        
               
              </div>
        
              <div class="footer-center">
        
                <div>
                  <i class="fa fa-map-marker"></i>
                  <p><span>Irbid-Samad-21110</span> Jordan</p>
                </div>
        
                <div>
                  <i class="fa fa-phone"></i>
                  <p>0798696409</p>
                </div>
        
                <div>
                  <i class="fa fa-envelope"></i>
                  <p><a href="moathbdur@gmail.com">moathbdur@gmail.com</a></p>
                </div>
        
              </div>
        
              <div class="footer-right">
        
                <p class="footer-company-about">
                  <span>At The Last <br></span>
                  I wanna Thank Every one For his support
                </p>
        
                <div class="footer-icons">
        
                  <a href="https://www.facebook.com/moath.bdour9" target="_blank"><i class="fa fa-facebook"> </i></a>
                  <a href="https://twitter.com/Bdour_moath" target="_blank"><i class="fa fa-twitter"></i></a>
                  <a href="https://www.linkedin.com/in/moath-bdour-381353237/"target="_blank"><i class="fa fa-linkedin"></i></a>
                  <a href="https://github.com/moathbdour"target="_blank"><i class="fa fa-github"></i></a>
        
                </div>
        
              </div>
        
            </footer>
   



    
   
</body>
</html>
