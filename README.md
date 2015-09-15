# App-Radios
Aplicaciones de radios para celulares
<!DOCTYPE html> 
<html>
<head>
<meta charset="utf-8">
<title>ZOO - Radio Mobile Web App</title>
<link rel="stylesheet" type="text/css" href="include/style.css">
<link href="jquery.mobile-1.0.min.css" rel="stylesheet" type="text/css"/>
<script src="jquery-1.6.4.min.js" type="text/javascript"></script>
<script src="jquery.mobile-1.0.min.js" type="text/javascript"></script>
function musesCallback(event,value){
    alert('event: "'+event+'", value: "'+value+'"');
}
</head> 
<body> 

<div data-role="page" id="page">
	<div class="header">    	
		<div class="logo"></div>
	</div>
	<div data-role="content">	
		<ul data-role="listview" class="mainmenu">
			<li><a href="#page2">
            <h3>RADIO ZOO</h3>
            <p>Escuchanos online</p></a></li>
            <li><a href="#page3">
            <h3>PAGINA WEB</h3>
            <p>Toda la ZOO en un solo lugar</p></a></li>
			<li><a href="#page4">
            <h3>FACEBOOK</h3>
            <p>Comunidad ZOO</p> </a></li>
            <li><a href="#page5">
            <h3>TWITTER</h3>
            <p>ZOO en diminutivo</p></a></li>
            <li><a href="#page6">
            <h3>WHATSAPP</h3>
            <p>Mensajeanos en directo</p></a></li>
            <li><a href="#page7">
            <h3>CONTACTO</h3>
            <p>Vias de contacto para Anunciantes</p></a></li>
		</ul>		
	</div>
	<div data-role="footer" class="fotterbg">
		<h4>Page Footer</h4>         
	</div>
</div>

<div data-role="page" id="page2">
	<div class="header">    	
		<div class="logo"></div>
	</div>
	<div data-role="content" class="bodycopy">	
		<h2>Radio ZOO - Online</h2>
               
        <!-- BEGINS: AUTO-GENERATED MUSES RADIO PLAYER CODE -->
        <div class="player">
			<object classid="clsid:D27CDB6E-AE6D-11cf-96B8-444553540000" 	width="269" height="52">
			<param name="movie" value="muses.swf" />
			<param name="flashvars" value=			"url=http://72.29.85.108:9007/stream&lang=es&codec=aac&volume=75&introurl=&autoplay=true&tracking=true&jsevents=true&skin=ffmp3-faredirfare.xml&title=Radio%20ZOO&welcome=Bienvenidos%20a ZOO" />
			<param name="wmode" value="transparent" />
			<param name="allowscriptaccess" value="always" />
			<param name="scale" value="noscale" />
			<embed src="muses.swf" flashvars="url=http://72.29.85.108:9007/stream&lang=es&codec=aac&volume=75&introurl=&autoplay=true&tracking=true&jsevents=true&skin=ffmp3-faredirfare.xml&title=Radio%20ZOO&welcome=Bienvenidos%20a ZOO" width="269" scale="noscale" height="52" wmode="transparent" allowscriptaccess="always" type="application/x-shockwave-flash" />
			</object>
        </div>     
		                   	
<!-- ENDS: AUTO-GENERATED MUSES RADIO PLAYER CODE -->
        	
        
	</div>
	<div data-role="footer" class="fotterbg">
		<h4>
		  <a href="#page" data-role="button" data-icon="back">Volver</a>
		  </h4>
	</div>
</div>

<div data-role="page" id="page3">
	<div class="header">    	
		<div class="logo"></div>
	</div>
	<div data-role="content" class="bodycopy">	
		<h2>Pagina Web</h2>	
	</div>
	<div data-role="footer" class="fotterbg">
		<h4><a href="#page" data-role="button" data-icon="back">Volver</a></h4>
	</div>
</div>

<div data-role="page" id="page4">
	<div class="header">    	
		<div class="logo"></div>
	</div>
	<div data-role="content" class="bodycopy">	
		<h2>Facebook</h2>
        <br>
        <br>
        <a href="https://www.facebook.com/Zooradiofm935?ref=ts&fref=ts">Comunidad ZOO en FACEBOOK </a>  
	</div>
	<div data-role="footer" class="fotterbg">
		<h4><a href="#page" data-role="button" data-icon="back">Volver</a></h4>
	</div>
</div>
<div data-role="page" id="page5">
  <div class="header">    	
		<div class="logo"></div>
	</div>
  <div data-role="content" class="bodycopy">
  <h2>Twitter</h2>
  </div>
  <div data-role="footer" class="fotterbg">
    <h4><a href="#page" data-role="button" data-icon="back">Volver</a></h4>
  </div>
</div>
<div data-role="page" id="page6">
  <div class="header">    	
		<div class="logo"></div>
	</div>
  <div data-role="content" class="bodycopy">
  <h2>Whatsapp</h2>
  </div>
  <div data-role="footer" class="fotterbg">
    <h4><a href="#page" data-role="button" data-icon="back">Volver</a></h4>
  </div>
</div>
<div data-role="page" id="page7">
  <div class="header">    	
		<div class="logo"></div>
	</div>
  <div data-role="content" class="bodycopy">
  <h2>Contacto</h2>
  </div>
  <div data-role="footer" class="fotterbg">
    <h4><a href="#page" data-role="button" data-icon="back">Volver</a></h4>
  </div>
</div>


</body>
</html>
