# Primer punto: se selecciona la imagen del SO a instalar
 ![imagen.png](attachment: https://github.com/JCmoctezuma/Escenarios_Distribuidos/tree/master/Images/img1.png)

Luego se selecciona la opción de instalar centos8
![imagen.png](attachment:imagen.png)
 
Luego mestra una interfaz grafica que nos permite configurar nuestra maquina virtual.
![imagen.png](attachment:imagen.png)
 
 De manera predeterminada lo que falta es asignar el disco a lo cual lo seleccionamos mediante la interfaz grafica. 
 ![imagen.png](attachment:imagen.png)
 
Seguido a este paso procedemos a la instalación
![imagen.png](attachment:imagen.png)
 
En la siguiente pantalla se puede configurar parámetros de usuarios como la contraseña del super usuario y usuarios
![imagen.png](attachment:imagen.png)
 

Finalmente se reinicia la maquina virtual
![imagen.png](attachment:imagen.png)
 
En caso de no iniciar con la imagen de centos al momento de inicar la maquina presional F12 y seleccionar la opción Hard Disk 
 ![imagen.png](attachment:imagen.png)
 
Y aceptar los términos y condiciones
![imagen.png](attachment:imagen.png)
 
Ya en centos se procede a actualizar e instalar Nginx
![imagen.png](attachment:imagen.png)
 
Y levantar su servicios
![imagen.png](attachment:imagen.png) 

Luego para acceder a los servicios se deben cambiar unos parámetros en la aplicación de vrtual box en la configuración de red conectarlo a “solo anfrition”
 ![imagen.png](attachment:imagen.png)

Para finalmente acceder a la pagina mediante otro equipo
 ![imagen.png](attachment:imagen.png)

Como se pudo observar el método de montar un servicio es bastante tedioso debido a que se tiene que configurar toda la máquina virtual además que en alguno de estos pasos pueden surgir errores por tanto no es la manera mas optima para montar un servicio distribuido. Lo anterior debido a que, de ser asi, se gastarían recursos innecesarios de tiempo y dinero montando servidores de esta manera además de estas virtualizaciones pueden ser objetivo para otros fines por fuera de los creados por tanto son mas inseguros.
