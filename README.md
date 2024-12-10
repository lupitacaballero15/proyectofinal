
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Pizzería "La Rebanada Perdida"</title>
	<style>
		* {
			box-sizing: border-box;
		}
		body{
			font-family: Aptos Display;
			padding: 10px;
			background: #f1f1f1;
		}
		.header{
			padding: 30px; 
			text-align: center; 
			background: #ff9e00;
			border: 3px solid black;
		}
		.header h1 { 
		font-size: 60px;
	}
	.topnav {
		overflow: hidden; 
		background-color: #910503;
		border: 3px solid black;
	}
	.topnav a {
		float: left;
		display: block; 
		color: #f2f2f2; 
		text-align: center;
		padding: 14px 16px; 
		text-decoration: none;
	}
	.topnav a:hover {
		background-color: #c0392b; 
		color: white;
	}
	.leftcolumn {
		float: left; 
		width: 75%;
	}
	.rightcolumn {
		float: left; 
		width: 25%;
		background-color: #f1f1f1; 
		padding-left: 20px;
	}
	.fakeimg {
		width: 100%; 
		padding: 20px;
	}
	.card {
		background-color: white;
		border: 3px solid black;
		padding: 20px; 
		margin-top: 20px;
	}
	.card1 {
		background-color: white;
		margin-top: 20px;
		border: 3px solid black;
	}
	.row::after{
		content: ""; 
		display: table; 
		clear: both;
	}
	.footer{
		color: white;
		padding: 20px; 
		text-align: center; 
		background: #ff9e00; 
		margin-top: 20px;
		border: 3px solid black;
	}
@media screen and (max-width: 800px) {
	.leftcolumn, .rightcolumn {
		width: 100%;
		padding: 0;
	}
}

@media screen and (max-width: 800px){
	.topnav a {
		float: none; 
		width: 100%;
	}
}
	p{
		font-family: Times New Roman;
		text-align: center;
	}
	</style>
</head>
<body>
	<div class="header">
		<h1>Pizzería "La Rebanada Perdida"</h1>
		<p>¡Busca tu rebanada perdida en nuestra sucursal!</p>
	</div>
	<div class="topnav">
		<a href="menupizza_caballero.html">Menú</a> 
		<a href="promociones_caballero.html">Promociones</a> 
		<a href="pedidos_caballero.html">Pedidos</a>
		<a href="pizza_caballero.html" style="float:right">Inicio</a>
	</div>
	<div class="row">
		<div class="leftcolumn">
			<div class="card">
				<div class="fakeimg" style="height:726px;"><img src="pizza1.jpg" alt="pizza" height="100%" width="100%"></div>
					<p>¡Haz tu pedido con nosotros!</p>
					<p>En tiempo, calidad y excelente sabor... ¡Solo nosotros somos los mejores!</p> 
				</div> 
		</div>
		<div class="rightcolumn">
			<div class="card">
				<h2>Nosotros</h2>
				<div class="fakeimg" style="height: 100px;">
					<img src="logopizza.png" alt="pizza" height="80px" width="200px">				</div> 
				<p>Somos una empresa 100% jarocha, creada por una universitaria</p> 
			</div> 
			<div class="card1">
				<div class="fakeimg">
					<a href="https://www.mercadolibre.com.mx/">
						<img src="mercadolibre.jpg" alt="mercadolibre" height="308px" width="250px">
					</a>
				</div>
			</div>
			<div class="card">
				<h3>Siguenos en nuestras redes sociales</h3>
				<p><strong>Faceboook:</strong> La Rebanada Perdida<br><strong>Instagram:</strong> @larebanadaperdida</p>
			</div>
		</div>
	</div>
	<div class="footer"> 
		<h3>Sitio web</h3>
		<h4>Proyecto Final para la clase de Desarrollo Web</h4>
	</div>
</body>
</html>
