<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario</title>
</head>
<body>
    <h1>TAQUERIA</h1>
    <h2>Menu</h2>
    <h3>Tacos</h3>
<ul>
    <li>Bisteck....................$15.00</li>
    <li>Suadero...................$20.00</li>
    <li>Longaniza...............$15.00</li>
    <li>Guisado..................$20.00</li>
    <li>Maciza....................$25.00</li>

</ul>
<h3>
    <dl>
        <dt>Complementos</dt>
        <dd>Con piña....................$10.00</dd>
        <dd>Carne extra...............$15.00</dd>
        <dd>Con quesillo..............$10.00</dd>
        <dt>Carne</dt>
        <dd>Enchilada..................$20.00</dd>
        <dd>Campechana.............$20.00</dd>
        <dd>Hawaillana................$20.00</dd>
        <dd>Al ajillo.................$20.00</dd>
    </dl>
</h3>

<h2>Realiza tu pedido</h2>
<form action="" method="">
    Nombre   <input type="text" placeholder="Juan Perez" maxlength="30" minlength="3" required> <br>
    Telefono <input type="tel" minlength="10" maxlength="10" placeholder="5539293818" value="52"> <br>
    Correo   <input type="email" placeholder="usuario@dominio.com" minlength="40" maxlength="60"> <br>

    ¿Para llevar o Para comer en el local? <br>
    <pre>
    <input type="radio" value="Llevar" name="Llevar"> Para llevar <br>
    <input type="radio" value="Local" name="Llevar"> En el local <br>

    Ingresa tu direccion <br>
    <textarea name="" id="direccion" cols="30" rows="10" placeholder="Aspiros 68 Santa Matria Azcapotzalco"></textarea> <br>
    Para cuando es tu orden <input type="date" value="2022-01-01" minlength="2022-11-19" maxlength="2050-12-31">

   Elige tus tacos <select name="2orden" id="">
    <option value="bisteck">Bisteck</option>
    <option value="suadero">Suadero</option>
    <option value="longaniza">Longaniza</option>
    <option value="guisado">Guisado</option>
    <option value="maciza">Maciza</option>
    <input type="number" minlength="1" maxlength="20">
   </select>
   Elige tus complementos <br>
   Con Piña <input type="checkbox" Con Piña> 
   Carne extra <input type="checkbox" Carne extra> 
   Con quesillo <input type="checkbox" Con quesillo> 

   Elige el tipo de carne <br>
   Enchilada <input type="checkbox" Enchilada> 
   Campechana <input type="checkbox" Campechana> 
   Hawaillana <input type="checkbox" Hawaillana> 
   al ajillo <input type="checkbox" Al ajillo> 

   Elige tus tacos <select name="1orden" id="">
    <option value="bisteck">Bisteck</option>
    <option value="suadero">Suadero</option>
    <option value="longaniza">Longaniza</option>
    <option value="guisado">Guisado</option>
    <option value="maciza">Maciza</option>
    <input type="number" minlength="1" maxlength="20">
   </select>
   Elige tus complementos <br>
   Con Piña <input type="checkbox"Con Piña> 
   Carne extra <input type="checkbox" Carne extra> 
   Con quesillo <input type="checkbox" Con quesillo> 

   Elige el tipo de carne <br>
   Enchilada <input type="checkbox" Enchilada> 
   Campechana <input type="checkbox" Campechana> 
   Hawaillana <input type="checkbox" Hawaillana> 
   Al ajillo <input type="checkbox" Al ajillo> 

   Elige tus tacos <select name="3orden" id=""> 
    <option value="bisteck">Bisteck</option>
    <option value="suadero">Suadero</option>
    <option value="longaniza">Longaniza</option>
    <option value="guisado">Guisado</option>
    <option value="maciza">Maciza</option>
    <input type="number" minlength="1" maxlength="20">
   </select>
   Elige tus complementos <br>
   Con Piña <input type="checkbox" Con Piña>
   Carne extra <input type="checkbox" Carne extra> 
   Con quesillo <input type="checkbox" Con quesillo> 

   Elige el tipo de carne <br>
   Enchilada <input type="checkbox" Enchilada> 
   Campechana <input type="checkbox" Campechana> 
   Hawaillana <input type="checkbox" Hawaillana> 
   Al ajillo <input type="checkbox" Al ajillo> 
</pre>
<input type="submit" value="Enviar">
<input type="reset" value="Restablecer">

Escoge un color <input type="color">
password <input type="password">
Selecciona el archivo que quieres enviar <input type="file">
</form>
</body>
</html>
