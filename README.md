# sh1
<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>Saber Hacer 3</title>
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
	 <link rel="icon" href="images/perfil.jpg">
</head>

<body><br>
	<br>
	<div class="container">
		<section>
		
			<div class="row">
      <div class="col-xl-5"  style="background-color:#FFFFFF" align="left">
		  <img src="images/hacer3.png" width="500" height="500" title="Perfil" class="rounded"> 
      </div>		
	
				
		<!-- 2da Mitad -->
      <div class="col-xl-5"  style="background-color:#F11D1D">
		  <br>
		  <p align="center">
		  <font color="white"><label>Cotiza el mejor seguro para ti</label></font>
		  </p>
		  
		  <!-- TABLA -->

	  <table align="center">
			<tr>
			<td> <input list="Marca" name="Marca" placeholder="Marca" class="form-control" />
				<datalist id="Marca">
				  <option value="Audi">
				  <option value="Ford">
				  <option value="Mini Cooper">
				  <option value="Chevrolet">
				  <option value="KIA">
				  <option value="BMW">
				</datalist></td>
				
				<td><input list="modelo" name="modelo" placeholder="Modelo" class="form-control"/>
				<datalist id="modelo">
				  <option value="Audi A5">
				  <option value="Ford Lobo Platinum">
				  <option value="Mini Cooper">
				  <option value="Chevrolet Cruze">
				  <option value="KIA Sportage">
				  <option value="BMW B3">
				</datalist></td>
			</tr>
			
			
			<tr>	
			<td><input list="sub" name="sub" placeholder="Submarca" class="form-control"/>
				<datalist id="sub">
				  <option value="1">
				  <option value="2">
				  <option value="3">
				  <option value="4">
				  <option value="5">
				  <option value="6">
				</datalist></td>
				
				<td><input list="Descripcion" name="Descripcion" placeholder="Descripción" class="form-control"/>
				<datalist id="Descripcion">
				  <option value="rojo">
				  <option value="azul">
				  <option value="amarillo">
				  <option value="plata">
				  <option value="guindo">
				  <option value="verde">
				</datalist></td>
			</tr>
			
			
			<tr>
			<td colspan="2"> <input list="Detalle" name="Detalle" placeholder="Detalle" class="form-control" />
				<datalist id="Detalle">
				  <option value="equipado">
				  <option value="no equipado">
				  <option value="deportivo">
				  <option value="quema cocos">
				  <option value="Turbo">
				  <option value="300 k/h">
				</datalist>
				</td>
			</tr>
			
			
			<tr>
			<td colspan="2"><input type="text" class="form-control" id="nombre" name="nombre" placeholder="Nombre(s)" class="form-control"></td>
			
			<tr>
				<td><input type="text" class="form-control" id="nombre" name="nombre" required "" placeholder="Apellido paterno"></td>
				<td><input type="text" class="form-control" id="nombre" name="nombre" required "" placeholder="Apellido Materno"></td>
			</tr>
			
			
			<tr>
				<td><input type="text" class="form-control" id="nombre" name="nombre" required "" placeholder="Teléfono"></td>
				<td><input type="text" class="form-control" id="nombre" name="nombre" required "" placeholder="Correo electrónico"></td>
			</tr>
			
			
			<tr>
				<td>
					
					<input list="genero" name="genero" placeholder="Género" class="form-control"/>
				<datalist id="genero">
				  <option value="Masculino">
				  <option value="Femenino">
				</datalist>
				</td>

				<td><input type="text" class="form-control" id="nombre" name="nombre" required "" placeholder="Código postal"></td>
			</tr>
		  
		  <tr>
			<td colspan="2"> <input list="edad" name="edad" placeholder="Edad" class="form-control" />
				<datalist id="edad">
				  <option value="18">
				  <option value="19">
				  <option value="20">
				  <option value="21">
				  <option value="22">
				  <option value="23">
				</datalist>
				</td>
			</tr>


			<tr>
			<td colspan="2" align="center"> 
				<div class="form-check form-check-inline" align="center">
            <input class="form-check-input" type="checkbox" value="" id="checkbox4" name="checkbox4">
            <label class="form-check-label" for="checkbox4" align= "center">
				<font color="white">Acepto que he leído el Aviso de privacidad</font>
            </label>
        		</div>
				</td>
			</tr>
		</table><br>
		  
		  <button type="button" class="btn btn-success btn-lg btn-block">Cotiza Gratis</button>
      </div>
    </div>
		</section>
	  
  		
	</div>
</body>
</html>
