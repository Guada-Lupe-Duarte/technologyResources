# Análisis funcional

Referencia: VictorC

1. Tomar requerimientos
2. Impact Maping
3. user story maping
4. Casos de uso
5. user story + casos de aceptación

Luego pasamos a la etapa de:

1. Event Storming
2. Backlog
3. Product Backlog
4. Planing

**Apunte:**  [link] https://www.youtube.com/watch?v=MRCnLtxwHOc&t=6329s

**Apunte de** [link] https://www.youtube.com/watch?v=cqhtcY9CbUE

1. **Toma de requisitos:** con el cliente, otras áreas. Momento clave para entender qué quiere el cliente y juntar toda la información útil, despejar dudas. Recopilar toda la información posible, en notas, etc.
Este documento debe ser firmado por el cliente para que luego no haya malos entendidos y todo quede validado y documentado. No pueden quedar cosas en el aire. “Esto es lo que entra, en estos plazos. Esto otro no”.

2. **Modelo de requisitos**: redactar en puntos todos los requisitos que hemos recopilado de la reunión. También se definen los roles de la app. Definir requisitos funcionales según el rol. Ej: tendremos rol admin, rol operador y rol cliente. Rol cliente tiene que poder loguearse. Rol cliente tiene que poder seleccionar un producto y luego ir al carrito, etc, (definir todo lo que el cliente puede hacer dentro de la aplicación).
Se escribe de manera sencilla, sin entrar en niveles técnicos.

También hay que describir los requisitos no funcionales: tienen que ver con cosas técnicas, por ejemplo el tiempo de resupesta máximo que puede tener. Ej: Si un usuario manda un mensaje a un chat tiene que mostrarse a tiempo real no puede tardar 1 min // El servicio tiene que estar disponible 24 hr al día.

Una vez que tenemos todos los requisitos bien escritos y detallados, es cuando podemos definir cada una de esas funcionalidad y pasamos a crear los Casos de uso.

3. **Casos de uso**: en este punto sí entramos en las funcionalidades, vamos a escribir que implica cada una de esas funcionalidades y lo hacemos a detalle, es decir, teniendo en cuenta todas las posibilidades para evitar problemas a futuro por no haber pensado en alguna de ella. 

Ej login: usuario entra a la agina de loginy encuentra un campo de usuario, un campo de contraseña, un campo de mantener la sesión iniciada o recordarme y un botón.   

- Caso de uso correcto: usuario ingresa usuario en el campo de usuario, ingresa la contraseña en el campo de contraseña, elije “recordarme” y hace clic al botón. Si todo coincide, le mostrará un mensaje de confirmación y podrá ingresar al sitio. Se guarda el token e login por n tiempo para que el usuario no se tenga que volver a loguear.

- Variante 1:  usuario ingresa usuario en el campo de usuario, ingresa la contraseña en el campo de contraseña pero no elije “recordarme” y el token de expiración finaliza cuando cierra la sesión. Si todo coincide, le mostrará un mensaje de confirmación y podrá ingresar al sitio.

- Variante 2: usuario ingresa mal el usuario en el campo de usuario, ingresa la contraseña en el campo de contraseña, elije “recordarme” y hace clic al botón. No coincide el campo de usuario y se le envia un mensaje de error con la indicación “Usuario incorrecto, por favor revise los campos”.

4. **Modelo de datos:** describir todas las entidades que vamos a almacenar. Primero definir cuáles va haber y luego todos los datos que vamos a almacenar de un usuario o de un producto. Ej: un usuario, qué datos vamos a guadra de ese usuario? email, dni, nombre y apelludo. O del producto: descripción, tamaño, peso, precio, color, etc. 
Luego tenemos que definir qué relación va haber entre esas entidades. Por ejemplo: si tenemos una colección de productos, va haber una colecion que tenga un titulo y un nombre y va a tenrr asociado un tipo de proucto. esto es independiente de la bbdd que usaremos, eso luego se define. 
Este es un punto clave para encontrar puntos que quizás no se tuvieron en cuanta al principio.

5. **Tecnología a utilizar:** segpun los costos y tiempos. X tecnología solventa lo que necesitamos?. Conocido como determinar el stack tecnologico. Definir todas la tecnologías que vamos a utilizar, desde el front sobre cómo vamos a mostrarlo, el back, las apis a utilizar, bbdd.
 
6. **Análisis de riesgos:** importante tenerlo en cuenta para evitar riesgos, qué riesgos tiene el proyecto, qué puede pasar en el proyecto? que nos deteriore o nos complique el desarrollo del proyecto. Por ejemplo, que la tecnoloía que pensamos usar no sea compatible; el framwok que ibamos a utilizar no es compatible; que la infraestructura que tiene el cliente no nos permita la libertades que queremos. Analizarlo por los tiempos y costos. “Qué pasaría si…”

7. **Estimación de costos:** las horas que nos va llevar el proyecto. Si tenemos que comprar licencias, o si tenemos que pagarlas, se incluyen acá.
*Una vez definido el coste podremos saber cuánto vale el proyecto.*
Definir si contamos con los recursos necesarios, personas que hacen la funcionalidad en 3 días u 8 días, cambia el presupuesto. Depende la carga tareas de cada uno. 
Coste de que se cumplan o no los riesgos, si pasa esto me puede costar 5 días, si me pasa esto otro me puede costar 15. Tener margen y privisón de lo que puede pasar y cuánto nos puede llevar.
Se le pregunta al desarrollor y es la persona encargada de saber estimar cuánto tiemp le lleva un requerimiento.
Preferible ser pesimista.

8. **Calcular el precio de nuestro proyecto:** separar en “cuánto me va a salir en el mejor de casos” y “cuánto me puede salir en el peor de los casos”. Buscar un punto medio que sea de utlidad.

**Apunte:** [link] https://www.lucidchart.com/pages/es/que-es-el-lenguaje-unificado-de-modelado-uml

[Links (1)](https://www.notion.so/Links-1-72b8afc174f342e1a2ed2a5c87eb5810?pvs=21)

[Recomendaciones (1)](https://www.notion.so/Recomendaciones-1-3b79baa4f8744e01aa7e509871331011?pvs=21)