# Proyecto-Espe

<html lang="en">
<head>
</head>
<body style="background-color:#ff8000;">
    <form name="f1" method="POST" action="guardar.php">
        <center>
            <table border= 5px bgcolor="#00ffff">
            <tr>    
                <th colspan="2" style="color:red;">FORMULARIO DE REGISTRO</th>
            </tr>
            <tr>
                <td style="color:blue;">USUARIO</td>
                <td><input type="text" name="A" size="100" maxlength="8" style="background-color:#00ffff;color:black"></td>
            </tr>
            <tr>
                <td style="color:blue;">CONTRASEÑA</td>
                <td><input type="password" name="B" size="100" maxlength="50" style="background-color:#00ffff;color:black"></td>
            </tr>
            <tr>
                <td style="color:blue;">EMAIL</td>
                <td><input type="text" name="C" size="100" maxlength="30" style="background-color:#00ffff;color:black"></td>
            </tr>
                            <th colspan="2" style="color:red;">MENSAJE</th>
            </tr>
            <tr>
                <th colspan="2" style="color:blue;">SI DESPUES DE BUSCAR TU CORREO SE ABRE ESTA PAGINA SIGNIFICA QUE SI EXISTE SU CORREO</th>
            </tr>
            <tr>
                <br><th colspan="2"><input type="submit" name="Enviar" value="Registrar"><input type="button" onclick="location.href='http://localhost/usuarios/ingresar.html';" value="Ingresar" /><BR><a href="consulta.html">Olvido su contraseña</a></th>
            </tr>
            </table>   
    </form>
</body>
</html>
