# Análisis funcional

1. Tomar requerimientos
2. Flowchart
3. Impact Maping
4. user story maping
5. Casos de uso
6. user story + casos de aceptación

Luego pasamos a la etapa de:

1. Event Storming
2. Backlog
3. Product Backlog
4. Planing

**Referencia 1**  [link] https://www.youtube.com/watch?v=MRCnLtxwHOc&t=6329s

**Referencia 2** [link] https://www.youtube.com/watch?v=cqhtcY9CbUE

1. **Toma de requisitos:** con el cliente, otras áreas. Momento clave para entender qué quiere el cliente y juntar toda la información útil, despejar dudas. Recopilar toda la información posible, en notas, etc.
Este documento debe ser firmado por el cliente para que luego no haya malos entendidos y todo quede validado y documentado. No pueden quedar cosas en el aire. “Esto es lo que entra, en estos plazos. Esto otro no”.
<Modelo de requisitos: listar todos los requisitos que hemos recopilado de la reunión. 
Detallar: 
- título, 
- prioridad, 
- descripción
- acciones iniciadoras
- comportamiento esperado
- requerimientos funcionales
- caso de error
- requerimientos no funcionales>
  
2. **Flowchart:** a partir del detalle de los requerimientos, armar el diagrama nos permite visualizar en plano general y evitar cuellos de botella.[link] /technologyResources/Análisis funcional/Flowchart.markdown 

3. **DER | Modelo de datos:** describir todas las entidades que vamos a almacenar. Primero definir cuáles va haber y luego todos los datos que vamos a almacenar de un usuario o de un producto. Ej: un usuario, qué datos vamos a guadra de ese usuario? email, dni, nombre y apelludo. O del producto: descripción, tamaño, peso, precio, color, etc. 
Luego tenemos que definir qué relación va haber entre esas entidades. Por ejemplo: si tenemos una colección de productos, va haber una colecion que tenga un titulo y un nombre y va a tenrr asociado un tipo de proucto. esto es independiente de la bbdd que usaremos, eso luego se define. 
Este es un punto clave para encontrar puntos que quizás no se tuvieron en cuanta al principio.

4. **Tecnología a utilizar:** según los costos y tiempos. X tecnología solventa lo que necesitamos?. Conocido como determinar el stack tecnologico. Definir todas la tecnologías que vamos a utilizar, desde el front sobre cómo vamos a mostrarlo, el back, las apis a utilizar, bbdd.

[ En caso de tener que cotizar: 
**Análisis de riesgos:** importante tenerlo en cuenta para evitar riesgos, qué riesgos tiene el proyecto, qué puede pasar en el proyecto? que nos deteriore o nos complique el desarrollo del proyecto. Por ejemplo, que la tecnoloía que pensamos usar no sea compatible; el framwok que ibamos a utilizar no es compatible; que la infraestructura que tiene el cliente no nos permita la libertades que queremos. Analizarlo por los tiempos y costos. “Qué pasaría si…”

**Estimación de costos:** las horas que nos va llevar el proyecto. Si tenemos que comprar licencias, o si tenemos que pagarlas, se incluyen acá.
*Una vez definido el coste podremos saber cuánto vale el proyecto.*
Definir si contamos con los recursos necesarios, personas que hacen la funcionalidad en 3 días u 8 días, cambia el presupuesto. Depende la carga tareas de cada uno. 
Coste de que se cumplan o no los riesgos, si pasa esto me puede costar 5 días, si me pasa esto otro me puede costar 15. Tener margen y privisón de lo que puede pasar y cuánto nos puede llevar.
Se le pregunta al desarrollor y es la persona encargada de saber estimar cuánto tiemp le lleva un requerimiento.
Preferible ser pesimista.

**Calcular el precio de nuestro proyecto:** separar en “cuánto me va a salir en el mejor de casos” y “cuánto me puede salir en el peor de los casos”. Buscar un punto medio que sea de utlidad.]


5. **Historia de usuario:**
se trata de una forma narrativa de explicar y conocer qué quiere nuestro cliente, representado de la forma que sea. Las US fomentan el debate, la colaboración y mantienen un equipo ágil. Las US pueden variar en su granularidad. A mayor tamaño mayor será el grado de incertidumbre.
El product backlog contiene las US, ordenadas y priorizadas.
- Los títulos de las US es recomendable que comiencen con un verbo.(Ej. “Generar orden de pago”)
- Evitemos, en lo posible, usar expresiones técnicas al narrar, pensemos en escribir en el lenguaje del cliente, del product owner.
- Es recomendable pensar siempre en un doble para en la US

Debemos saber que una **historia de usuario** narra qué quiere el cliente o el usuario, y un **caso de uso** detalla en cómo lo quiere.


**Casos de uso**: en este punto sí entramos en las funcionalidades, vamos a escribir que implica cada una de esas funcionalidades y lo hacemos a detalle, es decir, teniendo en cuenta todas las posibilidades para evitar problemas a futuro por no haber pensado en alguna de ella. 

Ej login: usuario entra a la agina de loginy encuentra un campo de usuario, un campo de contraseña, un campo de mantener la sesión iniciada o recordarme y un botón.   

- Caso de uso correcto: usuario ingresa usuario en el campo de usuario, ingresa la contraseña en el campo de contraseña, elije “recordarme” y hace clic al botón. Si todo coincide, le mostrará un mensaje de confirmación y podrá ingresar al sitio. Se guarda el token e login por n tiempo para que el usuario no se tenga que volver a loguear.

- Variante 1:  usuario ingresa usuario en el campo de usuario, ingresa la contraseña en el campo de contraseña pero no elije “recordarme” y el token de expiración finaliza cuando cierra la sesión. Si todo coincide, le mostrará un mensaje de confirmación y podrá ingresar al sitio.

- Variante 2: usuario ingresa mal el usuario en el campo de usuario, ingresa la contraseña en el campo de contraseña, elije “recordarme” y hace clic al botón. No coincide el campo de usuario y se le envia un mensaje de error con la indicación “Usuario incorrecto, por favor revise los campos”.


 


**Apunte:** [link] https://www.lucidchart.com/pages/es/que-es-el-lenguaje-unificado-de-modelado-uml

[Links (1)](https://www.notion.so/Links-1-72b8afc174f342e1a2ed2a5c87eb5810?pvs=21)

[Recomendaciones (1)](https://www.notion.so/Recomendaciones-1-3b79baa4f8744e01aa7e509871331011?pvs=21)