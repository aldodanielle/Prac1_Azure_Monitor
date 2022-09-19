# Practica 1
## Azure Monitor
### Paso 1:
Creamos una máquina virtual en [www.portal.azure.com](https://portal.azure.com/) y llenamos los campos que sean necesarios para crearla (suscripción, SO, nombre, grupo de recursos, usuario, contraseña, etc.) y esperamos a que esta se cree.

![Imagen 1](https://github.com/aldodanielle/Prac1_Azure_Monitor/blob/main/Imgenes/P1.png)
-----------------------------------------------------------------------------------------
### Paso 2:
Dentro del portal de Azure en el buscador buscamos monitor y nos aparece una interfaz como la que a continuación vemos.

![Imagen 2](https://github.com/aldodanielle/Prac1_Azure_Monitor/blob/main/Imgenes/P2.png)
-----------------------------------------------------------------------------------------
### Paso 3:
Dentro de monitor vamos a crear una alerta para ello nos dirigimos a la sección de alertas que se encuentra en la parte izquierda de nuestra pantalla y una vez dentro de ahí seleccionamos crear y creamos una regla de alertas 

![Imagen 3](https://github.com/aldodanielle/Prac1_Azure_Monitor/blob/main/Imgenes/P3.png)
-----------------------------------------------------------------------------------------
### Paso 4:
Una vez que seleccionamos crear regla de alertas nos abre una ventana para seleccionar el recuso o recursos a los que le vamos hacer la alerta para ello filtramos nuestra información primero por suscrición, después por tipo de recurso y por último por ubicación, y seleccionamos nuestra máquina virtual que anteriormente habíamos creado la cual nombramos como VM-1


![Imagen 4](https://github.com/aldodanielle/Prac1_Azure_Monitor/blob/main/Imgenes/P4.png)
-----------------------------------------------------------------------------------------
### Paso 5:
Observamos que nuestro ámbito fue creado correctamente es decir el ámbito es en donde aplicamos nuestra regla.

![Imagen 5](https://github.com/aldodanielle/Prac1_Azure_Monitor/blob/main/Imgenes/P5.png)
-----------------------------------------------------------------------------------------
### Paso 6:
una visto que el ámbito se creó y selecciono, nos pasamos a la condición en donde elegimos que tipo de condición se va a realizar en este caso va a ser una métrica del rendimiento del CPU en donde nos avise si este se llega a pasar el 30% nos mande la alerta así como se declaró.

![Imagen 6](https://github.com/aldodanielle/Prac1_Azure_Monitor/blob/main/Imgenes/P6.png)
-----------------------------------------------------------------------------------------
### Paso 7:
Una vez creada la alerta vemos que si realmente si se creó y el costo que tiene esta alerta.

![Imagen 7](https://github.com/aldodanielle/Prac1_Azure_Monitor/blob/main/Imgenes/P7.png)
-----------------------------------------------------------------------------------------
### Paso 8:
crear una acción para ello primero creamos un grupo de acciones y se le llenando los datos que nos piden como continuación se nos muestran.

![Imagen 8](https://github.com/aldodanielle/Prac1_Azure_Monitor/blob/main/Imgenes/P8.png)
-----------------------------------------------------------------------------------------
### Paso 9:
Después de llenar los datos básicos pasamos a notificaciones y de igual manera los campos que queremos el método para que se nos notifique por correo, SMS, por medio de la aplicación Mobile.

![Imagen 9](https://github.com/aldodanielle/Prac1_Azure_Monitor/blob/main/Imgenes/P9.png)
-----------------------------------------------------------------------------------------
### Paso 10:
Vemos que realmente se creó bien la notificación y revisamos y creamos el grupo de acciones.

![Imagen 10](https://github.com/aldodanielle/Prac1_Azure_Monitor/blob/main/Imgenes/P10.png)
-----------------------------------------------------------------------------------------
### Paso 11:
también las alertas se pueden reciclar es por ello que también le agregamos un poco mas de detalle en la pestaña de detalles en donde podemos seleccionar el tipo de gravedad el cual viene en 5 niveles así mismo como el nombre y la descripción de la regla de alertar y la revisamos y creamos nuestra alerta.

![Imagen 11](https://github.com/aldodanielle/Prac1_Azure_Monitor/blob/main/Imgenes/P11.png)
-----------------------------------------------------------------------------------------
### Paso 12:
Vemos que este se creó nuestra regla.

![Imagen 12](https://github.com/aldodanielle/Prac1_Azure_Monitor/blob/main/Imgenes/P12.png)
-----------------------------------------------------------------------------------------
### Paso 13:
Creamos un área de trabajo de Log Analytics el cual de la misma en el buscados la buscamos y la creamos agregándole los datos que nos pida

![Imagen 13](https://github.com/aldodanielle/Prac1_Azure_Monitor/blob/main/Imgenes/P13.png)
-----------------------------------------------------------------------------------------
### Paso 14:
Vemos que el recurso fue creado con éxito y entramos a el recurso creado de Log Analitycs

![Imagen 14](https://github.com/aldodanielle/Prac1_Azure_Monitor/blob/main/Imgenes/P14.png)
-----------------------------------------------------------------------------------------
### Paso 15:
Dentro de Log Analytics tenemos varias opciones, una de ellas crear agentes de registro de nuestras VM solo bastaría con in a configuración de agentes, después a agregar un registro de eventos de Windows y color el tipo de acción que queremos hacer y lo aplicamos y solo con eso se crea nuestro agente. Y también podemos hacer nuestros propios registros en nuestros registros personalizados como se muestra en la segunda imagen.


![Imagen 15](https://github.com/aldodanielle/Prac1_Azure_Monitor/blob/main/Imgenes/P15.png)
![Imagen 15.1](https://github.com/aldodanielle/Prac1_Azure_Monitor/blob/main/Imgenes/P16.png)
-----------------------------------------------------------------------------------------
### Paso 16:
Volvemos a información general y aquí vos salen como obtener y recopilar la información de los diversos orígenes y para ello solo es seguir los pasos necesarios que ahí nos da, en este caso nos vamos a agregar nuestra VM creada anterior mente para ello solo damos en la opción que ahí nos sale

![Imagen 16](https://github.com/aldodanielle/Prac1_Azure_Monitor/blob/main/Imgenes/P17.png)
-----------------------------------------------------------------------------------------
### Paso 17:
Seleccionamos nuestra VM

![Imagen 17](https://github.com/aldodanielle/Prac1_Azure_Monitor/blob/main/Imgenes/P18.png)
-----------------------------------------------------------------------------------------
### Paso 18:
oprimidos el botón de conectar y solo es cuestión de esperar que se conecte nuestra VM a Log Analytics y eso sería todo.

![Imagen 18](https://github.com/aldodanielle/Prac1_Azure_Monitor/blob/main/Imgenes/P19.png)
-----------------------------------------------------------------------------------------
### Paso 19:
Por último solo sería ver que nuestra MV si se conectó al Log Analytics.

![Imagen 19](https://github.com/aldodanielle/Prac1_Azure_Monitor/blob/main/Imgenes/P20.png)
-----------------------------------------------------------------------------------------
### Paso 20:
Resultado de la alerta creada con llegada al correo.

![Imagen 20](https://github.com/aldodanielle/Prac1_Azure_Monitor/blob/main/Imgenes/P21.png)
-----------------------------------------------------------------------------------------
