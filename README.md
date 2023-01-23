# carrds
</body>
</html>
<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css">
<title>JS Bin</title>
<style type="text/css">

#wrap { /* main container dont change width height and margin */
background-image: radial-gradient(circle, rgba(247,208,230,1) 0%, rgba(255,255,255,1) 100%);
background-position: 0% 0%;
background-repeat: repeat;
background-size: cover;
width: 350px;
height: auto;
margin:auto;
border-radius:8px;
border: 2px solid white;
padding-top:4px;
padding-bottom:8px;
padding-left:8px;
padding-right:8px;
-webkit-box-shadow: 0px 0px 5px 0px rgba(255, 135, 197,1);
-moz-box-shadow: 0px 0px 5px 0px rgba(255, 135, 197,1);
box-shadow: 0px 0px 5px 0px rgba(255, 135, 197,1);
}

#header
{
height: 1px;
background: white;
border-radius: 5px 5px 0px 0px
}

#paneOne { 
width: 168px;
height: 220px;
background: white;
float: left;
justify-content: center;

}

#img {
border: 2px solid #FFF6FA;
-webkit-filter: drop-shadow(0px 0px 1px #fff);
float: left;

}

.minPane {
width: 105px;
height: 160px;
background: #FF0;
scrollbar-width: none;
border: solid 1px #FF95CD;
white-space: normal;
border-radius: 4px;
display: inline-block;
font-family: 'Cousine', monospace;
font-size: 0.79em;
line-height: 1.1;
margin: 10px 10px 10px 10px;
padding: 1em;
vertical-align: middle;
transition: 1s;
overflow-y: scroll;
text-align: center;
background: rgba(255, 255, 255, 0.8);
 


}
.minPane:hover{
transform: scale(1.2);
background: #fff;
z-index: 9;
box-shadow: 2px 2px 2px #000;
}

.minPane {
 -ms-overflow-style: none;  /* Internet Explorer 10+ */
    scrollbar-width: none;  /* Firefox */
}
.minPane::-webkit-scrollbar { 
    display: none;  /* Safari and Chrome */
}

#wideMinPane { float: left;
background: #F00;
border: solid 1px #000;
height: 90px;
background: #000;
width: 398px;
}

#afterMini {
height: 35px;
border-radius: 0px 0px 5px 5px;
background: #Fff;
clear: left;
border: 1px solid #ffd2ea;

}

#container {
width: auto;
white-space: nowrap;
box-sizing: border-box;
height: 219px;
overflow-y: hidden;
background-image: url(https://lesbiana.crd.co/assets/images/gallery04/ f0ef235b_original.png?v=c15eb6f6);
background-position: center;
background-repeat: repeat;
background-size: auto;
box-sizing: border-box;
white-space: nowrap;
}

mark {
background: #fff;
border: 1px solid #FF95CD;
border-radius: 4px;
font-family:'handy';
color: #FF95CD;
padding-left: 15px;
padding-right:15px;
text-align: center;
text-decoration: none;
display: inline-block;
font-size: 1em;
margin: 0px 1px;
cursor: hidden;
}

a {
text-decoration: underline;
text-decoration-style: dotted;
color: #FF78BC;
font-weight: bold;

}
a:hover {
webkit-filter: blur(1px);
filter: blur(1px);
transition: .6s;
}

<style>
@font-face {
font-family: 'powerpuff girls';
src: url(https://dl.dropbox.com/s/sfryv4nuc5cjozr/Powerpuff.ttf);
}

#puff {
font-family: 'powerpuff girls';
font-size: 2.7em;
background:linear-gradient(to top, #fff 2%, #FFB3DE 100%);
-webkit-background-clip: text;
-webkit-text-fill-color: transparent;
-webkit-text-stroke: 0.5px #FF78BC;
-webkit-filter: drop-shadow(0px 0px 1.5px #FF87C5);
}

@font-face {
font-family: Pixel;
src: url(https://dl.dropbox.com/s/f4hqprekhvkgrfk/pixelpoiiz.ttf);
}
  


#Pixel {
padding: 0.25em;
font-family: Pixel;
background: transparent;
z-index: 109;
color: #ffd2ea;
-webkit-text-stroke: 0.5px #FFA4D6;
left:19em;
bottom: 28em;
opacity: 98%;

}


}
}

.box { /* css for main boxes */
font-family: 'Cousine', monospace;
font-weight: 400;
color: #000;
box-shadow: 0 0 8px 8px white inset;
height: 2em;
width: 100%;
border: 1px solid #ffd2ea;
padding-top: 1em;
padding-bottom: 0.5em;
padding-left: 0.5em;
padding-right: 0.5em;
overflow-y: scroll;
position:static;
transition: width 2s, height 2s;
-webkit-transition: opacity 2s linear;
-webkit-transition: all 1s ease-in-out;
-moz-transition: all 1s ease-in-out;
-o-transition: all 1s ease-in-out;
background: rgb(255,255,255);
background: linear-gradient(0deg, rgba(255,255,255,1) 32%, rgba(255,210,234,1) 100%);

}

.box:hover { /* animation for hover */
overflow-y: scroll;
height: 8em;
width: 65%;
z-index: 2;
border-radius: .5em;
transform-origin: 50% 50%;
-moz-transition: all 2s;
-webkit-transition: all 2s;
background: rgb(255,255,255);
background: radial-gradient(circle, rgba(255,255,255,1) 45%, rgba(255,210,234,1) 100%);
}

@font-face {
font-family:'handy';
src: url(https://dl.dropbox.com/s/kqvt2miu9r4y9ye/handy00.ttf);
}
#handy {
font-family:'handy';
font-size: 0.7em;
left: 0;
bottom: 0.5em;
margin: 0;

}

}
}
</style>
</head>
<body>
<div id="wrap">

<div id="header">
<div id="Pixel">
<div style="text-align:left">
name </div>
</div>
</div>
<div id="paneOne">

<p><img src="https://pbs.twimg.com/media/EukFsajVcAEdhX_?format=jpg&name=900x900" alt="Profile" style="width:150px;height:150px; margin:auto; border-radius: 50%; border: 2px solid #FFD2EA; justify-content: center; display: flex;">
<div id="handy">pronouns age </div>
<i class="fa fa-facebook"></i>
<i class="fa fa-twitter "></i>
<i class="fa fa-instagram"></i>
<i class="fa fa-curiouscat"></i>




</div>

<div id="container">
<div class="minPane">
<mark>about <IMG SRC="https://64.media.tumblr.com/tumblr_lm6r8zwgnr1qfoi4t.gif">
</mark> 


<br>
<br>
info info info info info info info info nfo info info <br>

<br>
<mark> links<IMG SRC=https://i122.photobucket.com/albums/o260/mhilka/minigifs/fig-coracaopisca.gif> </mark>
<br>
<br>
<a href="https://curiouscat.qa/faery2000s" target="_blank">curiouscat</a> <a href="https://.crd.co/" target="_blank">recursos</a> <a href="https://carrd.co/itzhuo" target="_blank">referral</a> <a href="https://tumblr.com/" target="_blank">tumblr</a> <br>
</div>
<div class="minPane">
<mark>interests <IMG SRC="https://64.media.tumblr.com/tumblr_lu2dgqlfzG1qfoi4t.gif">
</mark> 
You can add these infinitely, just add another div class="lala" in between greater than/less than signs.
</div>

<div class="minPane">
<mark>interests <IMG SRC="https://64.media.tumblr.com/tumblr_lu2dgqlfzG1qfoi4t.gif">
</mark> 
You can add these infinitely, just add another div class="lala" in between greater than/less than signs.
</div>

<div class="minPane">
You can add these infinitely, just add another div class="lala" in between greater than/less than signs.

</div>

</div>




</div>

</div>

</div>

</body>
</html>
