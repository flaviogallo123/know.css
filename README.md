# know.css


.imagem-newres1,.imagem-newres2, .imagem-newres3, .imagem-newres4, .imagem-testimonialres,.imagem-exploreres{
visibility: hidden;
}


.imagem-testimonialres{
position:absolute;
left: -200px;
top:0px;
visibility: hidden;
}


.quadrado-cabeca{
width:100%;
height: 157px;
position: absolute;
left: 0px;
top: 0px;
background-color: #2d2c2f;
}

.logo-cabeca{
position:Absolute;
top:45px;
left:187px;
z-index: 999;
}

.menu2{
list-style:none;
float:left;
position:absolute;
left:685px;
top:41px;
z-index: 999;
}

.about{
position:relative;
left:-2px;
}

.pages{
position:relative;
right: 4px;
}

.seta-drop{
width:17px;
height:18px;
position:relative;
right:295px;
top:4px;
}

.gallery{
position:relative;
left: 6px;
}

.blog{
position:relative;
left: 4px;
}


.contacts{
position:relative;
left: 2px;
}

.menu2 li{
position:relative;
float:left;
}

.menu2 li a:focus{
  color: #f34a2e;
}

.menu2 li a{
color:#333; 
text-decoration:none; 
padding:5px 24px; 
display:block;
font-family: 'Open Sans', sans-serif;
font-weight: 400;
font-style: normal;
color: #ffffff;
text-decoration: none;
border-color: transparent;
font-size: 13px;
}


.menu2 li a:hover{
background:#333;
color:#fff;
/* -moz-box-shadow:0 3px 10px 0 #CCC;
-webkit-box-shadow:0 3px 10px 0 #ccc;
text-shadow:0px 0px 5px #fff; */
}

.menu2 li  ul{
position:absolute;
top:25px;
left:0;
background-color:rgb(14, 12, 12);
display:none;
}

.menu2 li:hover ul, .menu2 li.over ul{display:block;}

.menu2 li ul li{
display:block;
width:150px;
}

.top-nav {
display: flex;
flex-direction: row;
align-items: center;
justify-content: space-between;
/* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
color: rgb(202, 0, 0);
height: 50px;
padding: 1em;
}

.menu-hamburguer {
display: flex;
flex-direction: row;
list-style-type: none;
margin: 0;
padding: 0;
visibility: hidden;

}

.menu-hamburguer > .li {
margin: 0 1rem;
overflow: hidden;

}

.menu-button-container {
display: none;
height: 10%;
width: 10px;
cursor: pointer;
flex-direction: column;
justify-content: center;
align-items: center;
position:absolute;
left:217px;
top:100px;
z-index: 9999;

}

#menu-toggle {
display: none;

}

.quadrado-hamburguer{
background-color: #2d2c2f;
width:40px;
height:39px;
position:absolute;
left:202px;
top:90px;
visibility: hidden;
}

.menu-button,
.menu-button::before,
.menu-button::after {
display: block;
background-color:  #f34a2e;
position: absolute;
height:3px;
width: 22px;
transition: transform 400ms cubic-bezier(0.23, 1, 0.32, 1);
border-radius: 2px;

}

.menu-button::before {
content: '';
margin-top: -7px;
}

.menu-button::after {
content: '';
margin-top: 7px;

}

#menu-toggle:checked + .menu-button-container .menu-button::before {
margin-top: 0px;
transform: rotate(405deg);

}

#menu-toggle:checked + .menu-button-container .menu-button {
background: rgba(255, 255, 255, 0);
}

#menu-toggle:checked + .menu-button-container .menu-button::after {
margin-top: 0px;
transform: rotate(-405deg);
}


* {box-sizing: border-box}
body { margin:0}
.mySlides {display: none}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
max-width: 1000px;
position: relative;
margin:0px;
top:107px;
z-index: 999;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 48.1%;
  /* width: auto; */
  padding: 16px;
  margin-top: -22px;
  color: white;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right:0;
  border-radius: 3px 0 0 3px;
  z-index: 999;
  
}

.prev{
left:-11px;
}

/* On hover, add a black background color with a little bit see-through */


.seta-prev{
width:7%;
height:6%;
/* position:absolute;
left:20px;
top:30px; */
}

.seta-next{
  width:7%;
  height:6%;
  position:relative;
  left:1009px;
}


/* Fading animation */
.fade {
  animation-name: fade;
  animation-duration: 1.5s;
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .prev, .next,.text {font-size: 11px}
}




.teste1{
width:735px;
height: 45px;
z-index: 999;
position:absolute;
left:0px;
top:-61px;
}

.teste-fundo1{
  width:749px;
  height: 46px;
  z-index: 999;
  position:absolute;
  left:795px;
  top:609px;
  transform: rotate(180deg);
  }

.quadrado-slide1{
width:154.4%;
background-color: #596273;
height:626px;
}


.imagem-slide1{
position:absolute;
left:787px;
top:85px;
width:58.5%;
height:70.4%;
}
  
.titulo-slide1{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #ffffff;
font-size: 44px;
line-height: 1.8;
letter-spacing: 0px;
position: absolute;
left:188px;
top:48px;
}
  
.texto-slide1{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #ffffff;
font-size: 16px;
line-height: 1.6;
letter-spacing: 0px;
position: absolute;
left:188px;
top:203px;
width:40%;
}
  
.botao-slide1{
font-family: 'Open Sans', sans-serif;
font-weight: 700;
font-style: normal;
color: #f5f5f5;
font-size: 14px;
background-color: #2d2c2f;
border-color: transparent;
position: absolute;
left:187px;
top:428px;
width:136px;
height:45px;
}


  

.teste2{
width:735px;
height: 45px;
z-index: 999;
position:absolute;
left:0px;
top:-61px;
}


.quadrado-slide2{
width:154.4%;
background-color: #ec8558;
height:616px; 
}


.imagem-slide2{
position:absolute;
left:905px;
top:164px;
width:46.7%;
height:57.1%;
}

.titulo-slide2{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #ffffff;
font-size: 44px;
line-height: 1.8;
letter-spacing: 0px;
position: absolute;
left:188px;
top:48px;
width:109%;
}

.texto-slide2{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #ffffff;
font-size: 16px;
line-height: 1.6;
letter-spacing: 0px;
position: absolute;
left:188px;
top:197px;
width:41.5%;
}

.botao-slide2{
font-family: 'Open Sans', sans-serif;
font-weight: 700;
font-style: normal;
color: #f5f5f5;
font-size: 14px;
background-color: #2d2c2f;
border-color: transparent;
position: absolute;
left:187px;
top:447px;
width:136px;
height:45px;
}

.teste-fundo2{
width:735px;
height: 45px;
z-index: 999;
position:absolute;
left:0px;
top:-61px;
}

.teste-fundo2{
width:749px;
height: 46px;
z-index: 999;
position:absolute;
left:795px;
top:599px;
transform: rotate(180deg);
}
    



.teste3{
width:735px;
height: 45px;
z-index: 999;
position:absolute;
left:0px;
top:-61px;
}


.quadrado-slide3{
width:154.4%;
background-color: #4ec4c8;
height:611px; 
}


.imagem-slide3{
position:absolute;
left:787px;
top:85px;
width:58.5%;
height:72.2%;
}

.titulo-slide3{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #ffffff;
font-size: 44px;
line-height: 1.8;
letter-spacing: 0px;
position: absolute;
left:188px;
top:48px;
width:109%;
}

.texto-slide3{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #ffffff;
font-size: 16px;
line-height: 1.6;
letter-spacing: 0px;
position: absolute;
left:188px;
top:203px;
width:44.5%;
}

.botao-slide3{
font-family: 'Open Sans', sans-serif;
font-weight: 700;
font-style: normal;
color: #f5f5f5;
font-size: 14px;
background-color: #2d2c2f;
border-color: transparent;
position: absolute;
left:187px;
top:428px;
width:136px;
height:45px;
}

.teste-fundo3{
width:735px;
height: 45px;
z-index: 999;
position:absolute;
left:0px;
top:-61px;
}

.teste-fundo3{
width:749px;
height: 46px;
z-index: 999;
position:absolute;
left:795px;
top:595px;
transform: rotate(180deg);
}


.subtitulo-laranja-welcome{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #f34a2e;
font-size: 16px;
line-height: 1.8;
letter-spacing: 3px;
position:absolute;
left:662px;
top:852px;
}

.titulo-welcome{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #2d2c2f;
font-size: 44px;
line-height: 1.8;
letter-spacing: 0px;
position:absolute;
left:671.4px;
top:860px;
}

.linha1{
border:1px solid #2d2c2f;
width:94px;
height: 2px;
position:absolute;
left:725px;
top:983px;
}

.texto-welcome{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #666666;
font-size: 16px;
line-height: 1.9;
letter-spacing: 0px;
position:absolute;
left:386px;
top:1017px;
width:50%;
text-align: center;
}

.container {
display: flex;
flex-flow: column wrap;
margin: 5%;
padding: 1%;
width:20vw;
position:absolute;
left:400px;
top:1120px;
}

.sidebar {
background-color: #f34a2e;
flex-grow: 1;
margin:9.8%;
padding: 0.5%;
height: 13px;
text-align: center;
}

.sb1 {
flex-grow: 0;
width:126px;
}

.numero1{
color: #f34a2e;
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
font-size: 16px;
line-height: 1.9;
letter-spacing: 0px;
position:relative;
left:425px;
top:-54px;
}

.international{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #f34a2e;
font-size: 14px;
line-height: 1.8;
letter-spacing: 0px;
position:absolute;
left:43px;
top:0px;
}


.sb2 {
flex-grow: 0;
width:448px;
}

.numero2{
color: #f34a2e;
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
font-size: 16px;
line-height: 1.9;
letter-spacing: 0px;
position:relative;
left:264px;
top:-53px;
}

.grants{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #f34a2e;
font-size: 14px;
line-height: 1.8;
letter-spacing: 0px;
position:absolute;
left:43.2px;
top:69px;
}



.sb3 {
flex-grow: 0;
width:423px;
}

.numero3{
color: #f34a2e;
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
font-size: 16px;
line-height: 1.9;
letter-spacing: 0px;
position:relative;
left:276px;
top:-53px;
}

.scholar{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #f34a2e;
font-size: 14px;
line-height: 1.8;
letter-spacing: 0px;
position:absolute;
left:43.2px;
top:137px;
}

.imagem-testimonial{
width:100%;
height:522px;
position:absolute;
left:0px;
top:1549px;
}

.subtitulo-testimonial{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #ffffff;
font-size: 16px;
line-height: 1.8;
letter-spacing: 3px;
position:absolute;
left:700.3px;
top:1621px;
}

.titulo-testimonial{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #ffffff;
font-size: 44px;
line-height: 1.8;
letter-spacing: 0px;
position:absolute;
left:632px;
top:1626px;
}

.linha-testi{
border:1px solid #ffff;
width:94px;
height: 2px;
position:absolute;
left:725px;
top:1749px;
}



* {
box-sizing: border-box
}


body {
margin: 0
}


.mySlides2 {
display: none;
width: 100%;
}


.slideshow-container2 {
width: 1000px;
position: relative;
margin: auto;
position:absolute;
left:280px;
top:1820px;
visibility: visible;
}

/* Next & previous buttons */
.prev2,
.next2 {
cursor: pointer;
position: absolute;
top: 50%;
width: auto;
padding: 16px;
margin-top: -22px;
color: white;
font-size:22px;
transition: 0.6s ease;
border-radius: 0 3px 3px 0;
user-select: none;
}

#seta-prev2{
position:relative;
left:456px;
top:166px;
}


/* Position the "next button" to the right */
.next2 {
right: 0;
border-radius: 3px 0 0 3px;
}

#seta-next2{
position:relative;
left:438px;
top:166px;
}






/* Fading animation */
.fade2 {
-webkit-animation-name: fade;
-webkit-animation-duration: 1.5s;
animation-name: fade;
animation-duration: 1.5s;
}

@-webkit-keyframes fade {
from {
opacity: .4
}
to {
opacity: 1
}
}

@keyframes fade {
from {
opacity: .4
}
to {
opacity: 1
}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
.prev2,
.next2,
.text {
font-size: 11px
}


}

.slide-teste{
width:735px;
height: 45px;
z-index: 999;
position:absolute;
left:0px;
top:1488px;
}

.slide-teste2{
width:735px;
height: 45px;
z-index: 999;
position:absolute;
left:809px;
top:2055px;
transform: rotate(180deg);
}




.texto1{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #ffffff;
font-size: 16px;
line-height: 1.9;
letter-spacing: 0px;
position:absolute;
left:117px;
top:-17px;
text-align: center;
width:75%;
}

.nome1{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #ffffff;
font-size: 14px;
line-height:2.3;
letter-spacing: 1px;
position:absolute;
left:434px;
top:104px;
}

.texto2{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #ffffff;
font-size: 16px;
line-height: 1.9;
letter-spacing: 0px;
position:absolute;
position:absolute;
left:117px;
top:-17px;
text-align: center;
width:75%;
}

.nome2{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #ffffff;
font-size: 14px;
line-height: 1.8;
letter-spacing: 1px;
position:absolute;
left:415px;
top:71px;
}

.texto3{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #ffffff;
font-size: 16px;
line-height: 1.9;
letter-spacing: 0px;
position:absolute;
left:117px;
top:-17px;
text-align: center;
width:75%;
}

.nome3{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #ffffff;
font-size: 14px;
line-height: 1.8;
letter-spacing: 1px;
position:absolute;
left:435px;
top:66px;
}


.texto4{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #ffffff;
font-size: 16px;
line-height: 1.9;
letter-spacing: 0px;
position:absolute;
left:117px;
top:-17px;
text-align: center;
width:75%;
}

.nome4{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #ffffff;
font-size: 14px;
line-height: 1.8;
letter-spacing: 1px;
position:absolute;
left:435px;
top:66px;
}


.subtitulo-laranja-new{
position:absolute;
left:714px;
top:2183px;
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #f34a2e;
font-size: 16px;
line-height: 1.8;
letter-spacing: 3px;
}

.titulo-new{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #2d2c2f;
font-size: 44px;
line-height: 1.8;
letter-spacing: 0px;
position:absolute;
left:585.5px;
top:2188px;
}

.linha-new{
border:1px solid #2d2c2f;
width:94px;
height: 2px;
position:absolute;
left:725px;
top:2311px;
}

.texto-new{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #666666;
font-size: 16px;
line-height:30.5px;
letter-spacing: 0px;
position:absolute;
left:386px;
top:2345px;
width: 50%;
text-align: center;
}

.imagem-new1{
position:absolute;
left:187px;
top:2537px;
width:294px;
height: 386px;
}

.new-numero1{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #666666;
font-size: 44px;
line-height: 1.8;
letter-spacing: 0px;
position:absolute;
left:227.8px;
top:2573px;
}

.october{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #666666;
font-size: 14px;
line-height: 1.8;
letter-spacing: 0px;
position:absolute;
left:289.5px;
top:2643px;
}


.laranja-new1{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #f34a2e;
font-size: 14px;
line-height: 1.8;
letter-spacing: 0px;
position:absolute;
left:227.9px;
top:2685px;
}

.texto-new1{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #666666;
font-size: 16px;
line-height: 1.9;
letter-spacing: 0px;
position:absolute;
left:227.9px;
top:2736px;
width:13%;
}


.imagem-new2{
position:absolute;
left:480px;
top:2537px;
width:293px;
height: 386px;
}

.new-numero2{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #666666;
font-size: 44px;
line-height: 1.8;
letter-spacing: 0px;
position:absolute;
left:520.4px;
top:2573px;
}

.february{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #666666;
font-size: 14px;
line-height: 1.8;
letter-spacing: 0px;
position:absolute;
left:582.3px;
top:2643px;
}


.laranja-new2{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #f34a2e;
font-size: 14px;
line-height: 1.8;
letter-spacing: 0px;
position:absolute;
left:520.4px;
top:2685px;
}

.texto-new2{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #666666;
font-size: 16px;
line-height: 1.9;
letter-spacing: 0px;
position:absolute;
left:520.4px;
top:2736px;
width:13%;
}


.imagem-new3{
position:absolute;
left:772px;
top:2537px;
width:293px;
height: 386px;
}

.new-numero3{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #666666;
font-size: 44px;
line-height: 1.8;
letter-spacing: 0px;
position:absolute;
left:813px;
top:2573px;
}

.may{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #666666;
font-size: 14px;
line-height: 1.8;
letter-spacing: 0px;
position:absolute;
left:874.7px;
top:2643px;
}


.laranja-new3{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #f34a2e;
font-size: 14px;
line-height: 1.8;
letter-spacing: 0px;
position:absolute;
left:813px;
top:2685px;
}

.texto-new3{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #666666;
font-size: 16px;
line-height: 1.9;
letter-spacing: 0px;
position:absolute;
left:813px;
top:2736px;
width:16%;
}


.imagem-new4{
position:absolute;
left:1065px;
top:2537px;
width:292px;
height: 386px;
}


.new-numero4{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #666666;
font-size: 44px;
line-height: 1.8;
letter-spacing: 0px;
position:absolute;
left:1105.5px;
top:2573px;
}

.april{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #666666;
font-size: 14px;
line-height: 1.8;
letter-spacing: 0px;
position:absolute;
left:1167.3px;
top:2643px;
}


.laranja-new4{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #f34a2e;
font-size: 14px;
line-height: 1.8;
letter-spacing: 0px;
position:absolute;
left:1105.5px;
top:2685px;
}

.texto-new4{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #666666;
font-size: 16px;
line-height: 1.9;
letter-spacing: 0px;
position:absolute;
left:1105.5px;
top:2736px;
width:16%;
}

.botao-new{
font-family: 'Open Sans', sans-serif;
font-weight: 700;
font-style: normal;
font-size: 14px;
color: #f5f5f5;
background-color: #2d2c2f;
border-color: transparent;
position:absolute;
left:700px;
top:2963px;
text-align: center;
width:144px;
height:45px;
}




.teste-letter{
width:735px;
height: 45px;
z-index: 999;
position:absolute;
left:0px;
top:3047px;
}
  

.teste-fundoletter{
width:737px;
height: 46px;
z-index: 999;
position:absolute;
left:806px;
top:3660px;
transform: rotate(363.4deg);
}


.fundo-email{
position:absolute;
left:0px;
top:3108px;
width:100%;
height:591px;

}

.fundo-emailres{
position:absolute;
right:0px;
top:3108px;
visibility:hidden;
}

.subtitulo-letter{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #ffffff;
font-size: 16px;
line-height: 1.8;
letter-spacing: 3px;
position:absolute;
left:694px;
top:3175px;
}

.titulo-letter{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #ffffff;
font-size: 44px;
line-height: 1.8;
letter-spacing: 0px;
position:absolute;
left:649.5px;
top:3180px;
}


.linha-letter{
border:1px solid #ffffff;
width:94px;
height: 2px;
position:absolute;
left:725px;
top:3303px;
}

.texto-letter{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #ffffff;
font-size: 16px;
line-height:31px;
letter-spacing: 0px;
position:absolute;
left:409px;
top:3337px;
width:47%;
text-align: center;
}

.input-email{
border-color: transparent;
background-color: rgba(0,0,0,0.1);
font-style: normal;
font-weight: 400;
line-height: 21px;
padding: 11px 99px;
font-size: 14px;
border: 1px solid transparent;
text-rendering: auto;
letter-spacing: normal;
word-spacing: normal;
text-transform: none;
text-indent: 0px;
text-shadow: none;
position:absolute;
left:587px;
top:3454px;
}

::placeholder{
color:#fff;
position:relative;
right:179px;
top:1px;
font-style: normal;
font-weight: 400;
line-height: 21px;
padding: 11px 99px;
font-size: 14px;
font-family: 'Open Sans', sans-serif;
}





.botao-letter{
font-family: 'Open Sans', sans-serif;
font-weight: 700;
font-style: normal;
font-size: 14px;
color: #f5f5f5;
background-color: #2d2c2f;
border-color: transparent;
text-align: center;
width:144px;
height:45px;
position:absolute;
left:700px;
top:3529px;
}


.laranja-teacher{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #f34a2e;
font-size: 16px;
line-height: 1.8;
letter-spacing: 3px;
position:absolute;
left:726.4px;
top:3766px;
}

.titulo-team{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #2d2c2f;
font-size: 44px;
line-height: 1.8;
letter-spacing: 0px;
position:absolute;
left:667px;
top:3771px;
}


.linha-team{
border:1px solid #2d2c2f;
width:94px;
height: 2px;
position:absolute;
left:725px;
top:3894px;
}


.texto-team{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #666666;
font-size: 16px;
line-height: 1.9;
letter-spacing: 0px;
position:absolute;
left:394px;
top:3928px;
text-align: center;
width:49%;
}

.team1{
position:absolute;
left:286px;
top:4115px;
}

.nome-team1{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #2d2c2f;
font-size: 44px;
line-height: 1.8;
letter-spacing: 0px;
position:absolute;
left:254.2px;
top:4280px;
}

.trabalho1{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #f34a2e;
font-size: 14px;
line-height: 1.8;
letter-spacing: 0px;
position:absolute;
left:340.4px;
top:4385px;
}

.texto-pessoa1{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #666666;
font-size: 16px;
line-height: 1.9;
letter-spacing: 0px;
position:absolute;
left:256.4px;
top:4436px;
text-align: center;
width:15%;
}

.icon-face1{
position:absolute;
left:298px;
top:4573px;
width:29px;
height:30px;
}

.icon-twitter1{
position:absolute;
left:357px;
top:4573px;
width:30px;
height:29px;
}

.icon-pinte1{
position:absolute;
left:413px;
top:4567px;
width:38px;
height:38px;
}

.team2{
position:absolute;
left:686px;
top:4115px;
}

.team-team2{
position:absolute;
left:686px;
top:4115px;
}

.nome-team2{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #2d2c2f;
font-size: 44px;
line-height: 1.8;
letter-spacing: 0px;
position:absolute;
left:649.5px;
top:4280px;
}

.trabalho2{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #f34a2e;
font-size: 14px;
line-height: 1.8;
letter-spacing: 0px;
position:absolute;
left:701.4px;
top:4385px;
}

.texto-pessoa2{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #666666;
font-size: 16px;
line-height: 1.9;
letter-spacing: 0px;
position:absolute;
left:656px;
top:4436px;
text-align: center;
width:15%;
}

.icon-face2{
position:absolute;
left:698px;
top:4573px;
width:29px;
height:30px;
}

.icon-twitter2{
position:absolute;
left:757px;
top:4573px;
width:30px;
height:29px;
}

.icon-pinte2{
position:absolute;
left:813px;
top:4567px;
width:38px;
height:38px;
}



.team3{
position:absolute;
left:1086px;
top:4115px;
}


.nome-team3{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #2d2c2f;
font-size: 44px;
line-height: 1.8;
letter-spacing: 0px;
position:absolute;
left:1037.3px;
top:4280px;
}

.trabalho3{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #f34a2e;
font-size: 14px;
line-height: 1.8;
letter-spacing: 0px;
position:absolute;
left:1125px;
top:4385px;
}

.texto-pessoa3{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #666666;
font-size: 16px;
line-height: 1.9;
letter-spacing: 0px;
position:absolute;
left:1087px;
top:4436px;
text-align: center;
width:11%;
}

.icon-face3{
position:absolute;
left:1098px;
top:4573px;
width:29px;
height:30px;
}

.icon-twitter3{
position:absolute;
left:1157px;
top:4573px;
width:30px;
height:29px;
}

.icon-pinte3{
position:absolute;
left:1213px;
top:4567px;
width:38px;
height:38px;
}


.teste-explore{
width:735px;
height: 45px;
z-index: 999;
position:absolute;
left:0px;
top:4662px;
}

.teste-fundoexplore{
width:749px;
height: 46px;
z-index: 999;
position:absolute;
left:794px;
top:5323px;
transform: rotate(363.4deg);
}



.imagem-explore{
position:absolute;
left:0px;
top:4723px;
width:100%;
height: 638px;
}

.subtitulo-explore{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #ffffff;
font-size: 16px;
line-height: 1.8;
letter-spacing: 3px;
position:absolute;
left:733.4px;
top:4795px;
}

.titulo-explore{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #ffffff;
font-size: 44px;
line-height: 1.8;
letter-spacing: 0px;
position:absolute;
left:595.7px;
top:4800px;
}

.linha-explore{
border:1px solid #ffffff;
width:94px;
height: 2px;
position:absolute;
left:725px;
top:4923px;
}



.slideshow-container3 {
width: 1000px;
position: relative;
margin: auto;
position:absolute;
left:280px;
top:5093px;
visibility: visible;
}

/* Next & previous buttons */
.prev3,
.next3 {
cursor: pointer;
position: absolute;
top: 50%;
width: auto;
padding: 16px;
margin-top: -22px;
color: white;
font-size:22px;
transition: 0.6s ease;
border-radius: 0 3px 3px 0;
user-select: none;
}

#seta-prev3{
position:relative;
left:456px;
top:143px;
}


/* Position the "next button" to the right */
.next3 {
right: 0;
border-radius: 3px 0 0 3px;
}

#seta-next3{
position:relative;
left:438px;
top:143px;
}






/* Fading animation */
.fade2 {
-webkit-animation-name: fade;
-webkit-animation-duration: 1.5s;
animation-name: fade;
animation-duration: 1.5s;
}

@-webkit-keyframes fade {
from {
opacity: .4
}
to {
opacity: 1
}
}

@keyframes fade {
from {
opacity: .4
}
to {
opacity: 1
}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
.prev3,
.next3,
.text {
font-size: 11px
}
}


.imagem-numero1{
position:absolute;
left:117px;
top:-120px;
}


.mini-texto1{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #ffffff;
font-size: 14px;
line-height: 1.8;
letter-spacing: 0px;
position:absolute;
left:117px;
top:-33px;
}

.slide-texto1{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #e8e8e8;
font-size: 16px;
line-height: 1.9;
letter-spacing: 0px;
position:absolute;
left:117px;
top:16px;
width:75%;
}


.imagem-numero2{
position:absolute;
left:117px;
top:-120px;
}

.mini-texto2{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #ffffff;
font-size: 14px;
line-height: 1.8;
letter-spacing: 0px;
position:absolute;
left:117px;
top:-33px;
}

.slide-texto2{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #e8e8e8;
font-size: 16px;
line-height: 1.9;
letter-spacing: 0px;
position:absolute;
left:117px;
top:16px;
width:75%;
}


.imagem-numero3{
position:absolute;
left:117px;
top:-120px;
}

.mini-texto3{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #ffffff;
font-size: 14px;
line-height: 1.8;
letter-spacing: 0px;
position:absolute;
left:117px;
top:-33px;
}

.slide-texto3{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #e8e8e8;
font-size: 16px;
line-height: 1.9;
letter-spacing: 0px;
position:absolute;
left:117px;
top:16px;
width:75%;
}


.imagem-numero4{
position:absolute;
left:117px;
top:-120px;
}

.mini-texto4{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #ffffff;
font-size: 14px;
line-height: 1.8;
letter-spacing: 0px;
position:absolute;
left:117px;
top:-33px;
}

.slide-texto4{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #e8e8e8;
font-size: 16px;
line-height: 1.9;
letter-spacing: 0px;
position:absolute;
left:117px;
top:16px;
width:75%;
}

.subtitulo-touch{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #f34a2e;
font-size: 16px;
line-height: 1.8;
letter-spacing: 3px;
position:absolute;
left: 708.4px;
top:5433px;
}

.titulo-contact{
font-weight: 700;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #2d2c2f;
font-size: 44px;
line-height: 1.8;
letter-spacing: 0px;
position:absolute;
left:675px;
top:5438px;
}

.linha-contact{
border:1px solid #2d2c2f;
width:94px;
height: 2px;
position:absolute;
left:725px;
top:5561px;
}

.icon-telefone{
position:absolute;
left:176px;
top:5678px;
width:38px;
height:38px;
}

.telefone1{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
font-size: 16px;
color: #666666;
line-height: 1.6;
letter-spacing: 0px;
position:absolute;
left:254.6px;
top:5671px;
text-decoration: none;
}

.telefone2{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
font-size: 16px;
color: #666666;
line-height: 1.6;
letter-spacing: 0px;
position:absolute;
left:254.6px;
top:5697px;
text-decoration: none;
}


.icon-local{
position:absolute;
left:583px;
top:5680px;
width:34px;
height:34px;
}
  

.endereco{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #666666;
font-size: 16px;
line-height: 1.6;
letter-spacing: 0px;
position:absolute;
left:654.8px;
top:5655px;
width:14%;
}


.icon-email{
position:absolute;
left:986px;
top:5676px;
width:30px;
height:30px;
}

.email{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #666666;
font-size: 16px;
line-height: 1.6;
letter-spacing: 0px;
position:absolute;
left:1055px;
top:5662px;
}

.teste-maps{
width:735px;
height: 45px;
z-index: 999;
position:absolute;
left:0px;
top:5836px;
}

.teste-fundomaps{
width:753px;
height: 46px;
z-index: 999;
position:absolute;
left:790px;
top:6257px;
transform: rotate(363.5deg);
}

.maps{
position:absolute;
left:0px;
top:5897px;
width:100%;
height: 401px;
}

.quadrado-rodape{
width:100%;
height:231px;
background-color: #2d2c2f;
position:absolute;
left:0px;
top:6296px;
}

.icon-face-roda{
width:42px;
height: 39px;
position:absolute;
left:560px;
top:98px;
}

.icon-twitter-roda{
width:40px;
height: 39px;
position:absolute;
left:656px;
top:98px;
}

.icon-insta-roda{
width:36px;
height: 36px;
position:absolute;
left:754px;
top:100px;
}

.icon-pinte-roda{
width:40px;
height:40px;
position:absolute;
left:848px;
top:98px;
}

.icon-in-roda{
width:40px;
height:40px;
position:absolute;
left:944px;
top:98px;
}

.marca{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #a9a9a9;
font-size: 14px;
line-height: 1.4;
letter-spacing: 0px;
position:absolute;
left:664.6px;
top:167px;
}

.privacy{
font-weight: 400;
font-style: normal;
font-family: 'Open Sans', sans-serif;
color: #a9a9a9;
font-size: 14px;
line-height: 1.4;
letter-spacing: 0px;
text-decoration: none;
position:absolute;
left:791.9px;
top:181px;
}


@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .prev, .next,.text {font-size: 11px}
}


@media (max-width: 700px) {

.imagem-newres1,.imagem-newres2, .imagem-newres3, .imagem-newres4, .imagem-testimonialres, .fundo-emailres,.imagem-exploreres{
visibility: visible;
}


.quadrado-cabeca{
width:100%;
height: 300px;
}


.menu-button-container {
display: flex;
}

.logo-cabeca{
position:absolute;
left:120px;
}




.menu2{
visibility: hidden;
position:absolute;
left:0px;
top:0px
}

.menu-hamburguer {
position: absolute;
top: 0;
margin-top: 50px;
left: 0;
flex-direction: column;
width: 100%;
justify-content: center;
align-items: center;
visibility: visible;
z-index: 999;
position: absolute;
top:160px;
z-index: 9999;
}



#menu-toggle ~ .menu-hamburguer  .li {
height: 0;
margin: 0;
padding: 0;
border: 0;
transition: height 400ms cubic-bezier(0.23, 1, 0.32, 1);
z-index: 9999;
}



#menu-toggle:checked ~ .menu-hamburguer  .li {
border: 1px solid #333;
height: 2.5em;
padding: 0.5em;
transition: height 400ms cubic-bezier(0.23, 1, 0.32, 1);
z-index: 9999;
}


.menu-hamburguer  > .li {
display: flex;
justify-content: center;
margin: 0;
padding: 0.5em 0;
width: 100%;
color: white;
background-color: #222;
z-index: 9999;
}



.menu-hamburguer  > li:not(:last-child) {
border-bottom: 1px solid #444;
}


.quadrado-hamburguer{
visibility: hidden;
z-index: 999;
}

.slideshow-container{
position:relative;
left:0px;
top:148px;
}

.seta-prev{
width:25px;
height:25px;
}

.seta-next{
width:25px;
height:25px;
position:absolute;
left:0px;
}

.quadrado-slide1{
width:100%;
height: 714px;
}

.teste1{
width:210px;
height: 21px;
position: absolute;
left: 0px;
top:-37px;
}

.titulo-slide1{
position:absolute;
left:16px;
top:8px;
font-size:32px;
}

.texto-slide1{
position:absolute;
left:16px;
top:109px;
font-size:14px;
width:93%;
line-height:18.2px;
}

.botao-slide1{
position:absolute;
left:15px;
top:250px;
font-size:12px;
width:110px;
}

.imagem-slide1{
position:absolute;
left:0px;
top:325px;
width:444px;
height: 334px;
}

.teste-fundo1{
width:210px;
height: 21px;
position:absolute;
left:234px;
top:698px;
}

.quadrado-slide2{
width:100%;
height: 787px;
}

.teste2{
width:210px;
height: 21px;
position: absolute;
left: 0px;
top:-37px;
}

.titulo-slide2{
position:absolute;
left:16px;
top:13px;
font-size:32px;
width:83%;
line-height: 48px;
}

.texto-slide2{
position:absolute;
left:16px;
top:190px;
font-size:14px;
width:92%;
line-height:18px;
}

.botao-slide2{
position:absolute;
left:15px;
top:349px;
font-size:12px;
width:110px;
}

.imagem-slide2{
position:absolute;
left:15px;
top:409px;
width:429px;
height: 323px;
}

.teste-fundo2{
width:210px;
height: 21px;
position:absolute;
left:234px;
top:771px;
}


.quadrado-slide3{
width:100%;
height: 718px;
}

.teste3{
width:210px;
height: 21px;
position: absolute;
left: 0px;
top:-37px;
}

.titulo-slide3{
position:absolute;
left:16px;
top:13px;
font-size:32px;
width:83%;
line-height: 48px;
}

.texto-slide3{
position:absolute;
left:16px;
top:109px;
font-size:14px;
width:92%;
line-height:18px;
}

.botao-slide3{
position:absolute;
left:15px;
top:268px;
font-size:12px;
width:110px;
}

.imagem-slide3{
position:absolute;
left:0px;
top:343px;
width:444px;
height: 335px;
}

.teste-fundo3{
width:210px;
height: 22px;
position:absolute;
left:234px;
top:701px;
}

.subtitulo-laranja-welcome{
position:absolute;
left: 131.9px;
top:1016px;
font-size: 14px;
letter-spacing:2px;
}

.titulo-welcome{
position:absolute;
left: 149px;
top:1025px;
font-size:32px;
}

.linha1{
position:absolute;
left: 205px;
top:1112px;
width:34px;
}

.texto-welcome{
position:absolute;
left: 11px;
top:1129px;
font-size: 14px;
width:95%;
text-align: center;
letter-spacing: 0px;
line-height: 1.5;
}

.container{
position:absolute;
left:-35px;
top:1265px;
width:90%;
}

.sidebar{
margin:5.9%;
}

.sb1{
width:26.6%;
}

.international{
position:absolute;
left:28px;
top:-10px;
font-size:13px;
}

.numero1{
position:absolute;
left:414px;
top:-14px;
font-size: 14px;
}

.sb2{
width:94.3%;
}

.grants{
position:absolute;
left:28px;
top:49px;
font-size:13px;
}

.numero2{
position:absolute;
left:414px;
top:45px;
font-size: 14px;
}



.sb3{
width:89.2%;
}

.scholar{
position:absolute;
left:28px;
top:108px;
font-size:13px;
}

.numero3{
position:absolute;
left:414px;
top:104px;
font-size: 14px;
}

.imagem-testimonial{
position:absolute;
left:0px;
top:1533px;
width:100%;
height:382px;
visibility: hidden;
}


.imagem-testimonialres{
position:absolute;
left:0px;
top:1533px;
width:100%;
height:382px;
visibility: visible;
}

.slide-teste{
position:absolute;
left:0px;
top:1496px;
width:210px;
height: 21px;
}

.slide-teste2{
width:210px;
height: 23px;
position:absolute;
left:234px;
top:1898px;
}

.subtitulo-testimonial{
position:absolute;
left:163px;
top:1561px;
font-size:14px;
letter-spacing:2px;
}

.titulo-testimonial{
position:absolute;
left:120px;
top:1567px;
font-size:32px;
}

.linha-testi{
position:absolute;
left:205px;
top:1654px;
width:34px;
}



.slideshow-container2{
position:absolute;
left:-590px;
top:1654px;
z-index: 999;
}


.texto1{
position:absolute;
left:604.9px;
top:36px;
font-size: 14px;
width:41.4%;
text-align: center;
line-height: 21px;
}

.nome1{
position:absolute;
left:757.4px;
top:138px;
font-size: 13px;
}

.texto2{
position:absolute;
left:604.9px;
top:36px;
font-size: 14px;
width:41.4%;
text-align: center;
line-height: 21px;
}

.nome2{
position:absolute;
left:740px;
top:119px;
font-size: 13px;
}

.texto3{
position:absolute;
left:604.9px;
top:36px;
font-size: 14px;
width:41.4%;
text-align: center;
line-height: 21px;
}

.nome3{
position:absolute;
left:758.4px;
top:98px;
font-size: 13px;
}


#seta-next2{
position:absolute;
left:805px;
top:202px;
}

#seta-prev2{
position:absolute;
left:776px;
top:202px;
}


.subtitulo-laranja-new{
position:absolute;
left:174.5px;
top:1968px;
font-size: 14px;
letter-spacing:2px;
}

.titulo-new{
position:absolute;
left:86.5px;
top:1975px;
font-size:32px;
}

.linha-new{
position:absolute;
left:205px;
top:2062px;
width:34px;
}

.texto-new{
position:absolute;
left:15.6px;
top:2079px;
font-size: 14px;
width:93%;
line-height: 21px;
}

.imagem-new1{
position:absolute;
left:0px;
top:2239px;
width:100%;
height:222px;
visibility: hidden;
}

.imagem-newres1{
position:absolute;
left:14px;
top:2239px;
width:93.6%;
height:212px;
}

.new-numero1{
position:absolute;
left:36px;
top:2242px;
font-size:32px;
}

.october{
position:absolute;
left:80.9px;
top:2285px;
font-size:14px;
}

.laranja-new1{
position:absolute;
left:36px;
top:2315px;
font-size: 13px;
}

.texto-new1{
position:absolute;
left:36px;
top:2355px;
font-size: 14px;
width:90%;
line-height: 21px;
}


.imagem-new2{
position:absolute;
left:14px;
top:2471px;
width:93.6%;
height:212px;
visibility: hidden;
}

.imagem-newres2{
position:absolute;
left:14px;
top:2471px;
width:93.5%;
height:211px;
}

.new-numero2{
position:absolute;
left:36px;
top:2474px;
font-size:32px;
}

.february{
position:absolute;
left:80.9px;
top:2517px;
font-size:14px;
}

.laranja-new2{
position:absolute;
left:36px;
top:2547px;
font-size: 13px;
}

.texto-new2{
position:absolute;
left:36px;
top:2586px;
font-size: 14px;
width:88%;
line-height: 21px;
}


.imagem-new3{
position:absolute;
left:14px;
top:2702px;
width:93.6%;
height:212px;
visibility: hidden;
}

.imagem-newres3{
position:absolute;
left:14px;
top:2702px;
width:93.5%;
height:211px;
}

.new-numero3{
position:absolute;
left:36px;
top:2705px;
font-size:32px;
}

.may{
position:absolute;
left:80.9px;
top:2748px;
font-size:14px;
}

.laranja-new3{
position:absolute;
left:36px;
top:2778px;
font-size: 13px;
}

.texto-new3{
position:absolute;
left:36px;
top:2818px;
font-size: 14px;
width:88%;
line-height: 21px;
}


.imagem-new4{
position:absolute;
left:14px;
top:2934px;
width:93.6%;
height:213px;
visibility: hidden;
}

.imagem-newres4{
position:absolute;
left:14px;
top:2934px;
width:93.5%;
height:212px;
}

.new-numero4{
position:absolute;
left:36px;
top:2937px;
font-size:32px;
}

.april{
position:absolute;
left:80.9px;
top:2980px;
font-size:14px;
}

.laranja-new4{
position:absolute;
left:36px;
top:3010px;
font-size: 13px;
}

.texto-new4{
position:absolute;
left:36px;
top:3050px;
font-size: 14px;
width:88%;
line-height: 21px;
}

.botao-new{
position:absolute;
left:175px;
top:3166px;
width:94px;
font-size: 12px;
}


.fundo-email{
position:absolute;
left:0px;
top:3271px;
width:100%;
height:380px;
visibility: hidden;
}

.fundo-emailres{
position:absolute;
left:0px;
top:3271px;
width:100%;
height:380px;
}

.teste-letter{
position:absolute;
left:0px;
top:3234px;
width:210px;
height: 21px;
}

.teste-fundoletter{
width:210px;
height: 23px;
position:absolute;
left:233px;
top:3623px;
transform: rotate(366deg);
}



.subtitulo-letter{
position:absolute;
left:158.5px;
top:3299px;
font-size: 14px;
letter-spacing:2px;
}

.titulo-letter{
position:absolute;
left:133px;
top:3306px;
font-size:32px;
}

.linha-letter{
position:absolute;
left:205px;
top:3393px;
width:34px;
}

.texto-letter{
position:absolute;
left:22.2px;
top:3410px;
font-size: 14px;
width:90%;
line-height: 21px;
}

.input-email{
position:absolute;
left:15px;
top:3487px;
width:414px;
height:47px;
}

::placeholder{
font-size: 12px;
position:absolute;
right:260px;
top:3px;
}

.botao-letter{
position:absolute;
left:170px;
top:3544px;
width:104px;
font-size: 12px;
}

.laranja-teacher{
position:absolute;
left:184.4px;
top:3684px;
font-size: 14px;
letter-spacing:2px;
}

.titulo-team{
position:absolute;
left:145.3px;
top:3690px;
font-size: 32px;
}

.linha-team{
position:absolute;
left:205px;
top:3777px;
width:34px; 
}

.texto-team{
position:absolute;
left:22.2px;
top:3794px;
font-size: 14px;
width:90%;
line-height: 21px;
}

.team1{
position:absolute;
left:136px;
top:3933px;
}

.nome-team1{
position:absolute;
left:136.3px;
top:4103px;
font-size: 32px;
}

.trabalho1{
position:absolute;
left:193px;
top:4172px;
font-size:13px;
}

.texto-pessoa1{
position:absolute;
left:22.2px;
top:4212px;
font-size: 14px;
width:90%;
line-height: 21px;
}

.icon-face1{
position:absolute;
left:166px;
top:4298px;
width:21px;
height:21px;
}

.icon-twitter1{
position:absolute;
left:212px;
top:4298px;
width:21px;
height:21px;
}

.icon-pinte1{
position:absolute;
left:255px;
top:4294px;
width:26px;
height:26px;
}


.team2{
position:absolute;
left:136px;
top:4359px;
}

.nome-team2{
position:absolute;
left:132.9px;
top:4529px;
font-size: 32px;
}

.trabalho2{
position:absolute;
left:156.4px;
top:4598px;
font-size:13px;
}

.texto-pessoa2{
position:absolute;
left:12px;
top:4638px;
font-size: 14px;
width:96%;
line-height: 21px;
}

.icon-face2{
position:absolute;
left:166px;
top:4724px;
width:21px;
height:21px;
}

.icon-twitter2{
position:absolute;
left:212px;
top:4724px;
width:21px;
height:21px;
}

.icon-pinte2{
position:absolute;
left:255px;
top:4720px;
width:26px;
height:26px;
}


.team3{
position:absolute;
left:136px;
top:4785px;
}

.nome-team3{
position:absolute;
left:124px;
top:4955px;
font-size: 32px;
}

.trabalho3{
position:absolute;
left:178.4px;
top:5024px;
font-size:13px;
}

.texto-pessoa3{
position:absolute;
left:9px;
top:5064px;
font-size: 14px;
width:96%;
line-height: 21px;
}

.icon-face3{
position:absolute;
left:166px;
top:5129px;
width:21px;
height:21px;
}

.icon-twitter3{
position:absolute;
left:212px;
top:5129px;
width:21px;
height:21px;
}

.icon-pinte3{
position:absolute;
left:255px;
top:5125px;
width:26px;
height:26px;
}

.teste-explore{
position:absolute;
left:0px;
top:5178px;
width:210px;
height: 21px;
}

.teste-fundoexplore{
width:210px;
height: 23px;
position:absolute;
left:233px;
top:5652px;
transform: rotate(366.3deg);
}
  


.imagem-explore{
visibility: hidden;
}

.imagem-exploreres{
position:absolute;
left:0px;
top:5215px;
width: 100%;
height: 465px;
}

.subtitulo-explore{
position:absolute;
left:190.4px;
top:5243px;
font-size: 14px;
letter-spacing:2px;
}

.titulo-explore{
position:absolute;
left:94px;
top:5249px;
font-size:32px;
}

.linha-explore{
position:absolute;
left:205px;
top:5336px;
width:34px;
}


.slideshow-container3{
position:absolute;
left:-76px;
top:5460px;
width:100%;
}

.imagem-numero1{
position:absolute;
left:91px;
top:-94px;
width:418px;
height:42px;
}

.mini-texto1{
position:absolute;
left:91px;
top:-45px;
font-size: 13px;
}

.slide-texto1{
position:absolute;
left:91px;
top:-4px;
font-size: 14px;
width:93%;
line-height: 21px;
}

.imagem-numero2{
position:absolute;
left:91px;
top:-94px;
width:418px;
height:42px;
}

.mini-texto2{
position:absolute;
left:91px;
top:-45px;
font-size: 13px;
}

.slide-texto2{
position:absolute;
left:91px;
top:-4px;
font-size: 14px;
width:93%;
line-height: 21px;
}


.imagem-numero3{
position:absolute;
left:91px;
top:-94px;
width:418px;
height:42px;
}

.mini-texto3{
position:absolute;
left:91px;
top:-45px;
font-size: 13px;
}

.slide-texto3{
position:absolute;
left:91px;
top:-4px;
font-size: 14px;
width:91%;
line-height: 21px;
}


.imagem-numero4{
position:absolute;
left:91px;
top:-94px;
width:418px;
height:42px;
}

.mini-texto4{
position:absolute;
left:91px;
top:-45px;
font-size: 13px;
}

.slide-texto4{
position:absolute;
left:91px;
top:-4px;
font-size: 14px;
width:91%;
line-height: 21px;
}

#seta-prev3{
position:absolute;
left:261px;
top:141px;
}

#seta-next3{
position:absolute;
left:291px;
top:141px;
}

.next3{
width:0%;
}

.subtitulo-touch{
position:absolute;
left:170.2px;
top:5713px;
font-size: 14px;
letter-spacing:2px;
}

.titulo-contact{
position:absolute;
left:151.7px;
top:5720px;
font-size:32px;
}

.linha-contact{
position:absolute;
left:205px;
top:5807px;
width:34px;
}

.icon-telefone{
position:absolute;
left:6px;
top:5874px;
width:33px;
height:33px;
}

.telefone1{
position:absolute;
left:90px;
top:5870px;
font-size: 14px;
}

.telefone2{
position:absolute;
left:90px;
top:5888px;
font-size: 14px;
}

.icon-local{
position:absolute;
left:12px;
top:5949px;
width:27px;
height:27px;
}
  
.endereco{
position:absolute;
left:90px;
top:5929px;
font-size: 14px;
width:40%;
line-height:18px;
}


.icon-email{
position:absolute;
left:14px;
top:6019px;
width:27px;
height:26px;
}

.email{
position:absolute;
left:90px;
top:6007px;
font-size: 14px;
}

.maps{
position:absolute;
left:0px;
top:6149px;
width: 100%;
height:399px;

}


.teste-maps{
position:absolute;
left:0px;
top:6112px;
width:210px;
height: 21px;
}

.teste-fundomaps{
width:210px;
height: 23px;
position:absolute;
left:233px;
top:6521px;
transform: rotate(366.3deg);
}

.quadrado-rodape{
width:100%;
height:149px;
position:absolute;
left:0px;
top:6549px;
}

.icon-face-roda{
position: absolute;
left:147px;
top:60px;
width:23px;
height:21px;
}

.icon-twitter-roda{
position: absolute;
left:179px;
top:60px;
width:22px;
height:21px;
}

.icon-insta-roda{
position: absolute;
left:212.5px;
top:61px;
width:19px;
height:19px;
}

.icon-pinte-roda{
position: absolute;
left:243px;
top:60px;
width:22px;
height:21px;
}


.icon-in-roda{
position: absolute;
left:276px;
top:60px;
width:22px;
height:21px;
}

.marca{
position: absolute;
left:130px;
top:90px;
font-size: 12px;
}

.privacy{
position: absolute;
left:239px;
top:102px;
font-size: 12px;

}


}








