# Estilo-Formulario-Completo
<!DOCTYPE html>
<html>
<head>
<title>FormularioCompleto</title>
<style>
 	label{
 		color: red;
 	}
 	.boton{
 		color: blue;
 	}
 	#submit{
 		color: green;
 	}
</style>
</head>
<body>
	<table border=2>
		<p><th colspan=2>Formulario de usuario</th></p>
    <form method="POST" action="http://formadorestic.com/alumnosasir2/procesaformulario_usuario.php">
    <tr><td>
		<label for="nombre">Nombre: </label>
		</td><td>
		<input type="text" id="nombre" name="nombre" placeholder="Introduzca su nombre">
		</td></tr>
	<tr><td>
		<label for="password">Contraseña: </label>
		</td><td>
		<input type="password" id="password" name="password" placeholder="Introduzca su contraseña">
		</td></tr>
	<tr><td>
		<label for="direccion">Dirección:</label>
		</td><td>
		<textarea id="direccion" name="direccion" placeholder="Introduzca su direccion" rows="10" cols="30">
		</textarea>
		</td></tr>
	<tr><td>
		Seleccione uno o varios deportes: 
		</td><td>
		<input id="hockey" type="checkbox" name="deportes[]" value="Hockey">
		<label for="hockey">Hockey</label>
		<br>
		<input id="futbol" type="checkbox" name="deportes[]" value="Fútbol">
		<label for="futbol">Fútbol</label>
		<br>
		<input id="badminton" type="checkbox" name="deportes[]" value="Bádminton">
		<label for="badminton">Bádminton</label>
		<br>
		<input id="padel" type="checkbox" name="deportes[]" value="Pádel">
		<label for="padel">Pádel</label>
		<br>
		<input id="volleyball" type="checkbox" name="deportes[]" value="Volleyball">
		<label for="volleyball">Volleyball</label>
		</td></tr>
	<tr><td>
		Género: 
		</td><td>
		<input id="hombre" type="radio" name="sexo" value="Hombre">
		<label for="hombre">Hombre</label>
		<br>
		<input id="mujer" type="radio" name="sexo" value="Mujer">
		<label for="mujer" style="text-align: center;">Mujer</label>
		</td></tr>	
	<tr><td>
		<label for="edad">Seleccione su edad: </label>
		</td><td>
		<select id="edad" name="edad">
			<option value="menor de edad">-18</option>
    		<option value="18">18</option>
    		<option value="mayor de edad">+18</option>
    	</select>
		</td></tr>
	<tr><td>
		<input type="file" value="Examinar..." id=examinar>
	<tr><td>
		<input type="button" class="boton" value="Click aquí">
		<input type="reset" class="boton" value="Restablecer">
		<input type="submit" id="submit" value="Enviar formulario">
		</td></tr>
</form>
</body>
</html>
