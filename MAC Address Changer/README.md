<h1><b>Guía para modificar la MAC en Windows</b></h1>

Guía para modificar la MAC en Windows
Con unos simples pasos, es posible alterar la dirección MAC de todas las interfaces de red que deseemos. No necesitamos ser un hacker para hacerlo y ésta pequeña guía nos demuestra qué es muy sencillo alterar la MAC. A nivel de red doméstica, esto no representa un gran riesgo. Sin embargo, si estamos en un entorno corporativo, la situación es diferente. Si como administradores de red permitimos que cualquiera o bien, permitimos que personas no autorizadas puedan alterar ese dato, los riesgos son innumerables. A continuación, podéis ver cómo alterar la dirección MAC en Windows 10:

Entrar a <strong>Administrador de Dispositivos</strong>.
Seleccionar el apartado de <strong>Adaptadores de Red</strong>.
Escogemos la interfaz de red a la que queremos cambiar la dirección MAC.
Hacemos clic derecho en lo escogido y seleccionamos la opción «<strong>Propiedades</strong>«.
Pasamos a la pestaña «<strong>Opciones Avanzadas</strong>«, luego a la cajita de «<strong>Propiedad</strong>» y nos encontraremos con <strong>Direcciones Administradas Localmente</strong> o <strong>Locally Administered Address</strong>
Fíjate en el campo de texto (<strong>Valor</strong>) en donde se encuentra la dirección MAC y siéntete libre de borrarlo y cambiarlo
Acto seguido, vuelve a introducir la dirección MAC de tu preferencia, respetando el formato y sin separadores/espacios.
Reinicia el ordenador
Vuelve a ejecutar el «<strong>cmd</strong>»
Escribes «<strong>ipconfig/all</strong>» y listo: dirección MAC alterada.

![image](https://github.com/MrGuillote/CURSOS/assets/89352244/630713b8-1ca7-46da-85d0-8c0b1e638958)

Un detalle importante es que es posible que no aparezca este campo de «Locally Administered Address» en las propiedades de tu tarjeta de red, por lo que tendrás que recurrir a software externo para realizar este cambio. Algunos de los programas más recomendables son los siguientes:

<h1><b>Technitium MAC</b></h1>

[Technitium TMAC https://technitium.com/tmac/](https://technitium.com/tmac/)


Es un programa gratuito y de fácil instalación. Sólo es cuestión de realizar la descarga de forma directa o por Torrent, seguir unos pocos pasos y tendrás al programa ejecutándose. Más abajo, vemos un ejemplo de cómo el programa lista todas las interfaces de red, la dirección de MAC actual, su estatus de conexión y mucho más:

![image](https://github.com/MrGuillote/CURSOS/assets/89352244/6ac856dd-5130-46dd-9192-48cbadc511c5)

Para cambiar la MAC de alguna de las interfaces, debes seleccionar alguna de ellas y dirígete al apartado «Change MAC Address» que se encuentra un poco más abajo. Allí, debes escribir la dirección que tú prefieras o bien, haz clic en el botón «Random MAC Address» para que el programa asigne de manera aleatoria una dirección para tu interfaz.

En caso de que lo necesites, existe una opción que exporta que en formato .txt un reporte con los detalles de las interfaces. Así, puedes tenerlo en tu archivo o compartirlo con las personas que así lo necesitan. Debes ir a «File» (Archivo) > Export Text Report > Indica el nombre del archivo> Guardar

![image](https://github.com/MrGuillote/CURSOS/assets/89352244/e7b4975f-3c55-4983-a0ec-cc10eb3d2fae)


<h2><b>SMAC</b></h2>

Es otro programa con licencia gratuita que te permite modificar con facilidad la dirección MAC de todos tus adaptadores. Tienes la opción de desplegar solamente los adaptadores activos o bien, de desplegar la lista completa en donde se verifican tanto los activos como inactivos. ¿Cómo cambias la dirección? Simplemente escoge la que deseas e indica en el campo «New Spoofed MAC Address».

Por otro lado, desde este programa puedes controlar cada una de las interfaces realizando acciones como reiniciarlas, refrescar su estado actual, generar un número aleatorio de dirección MAC si no queremos indicar uno, entre otras.

![image](https://github.com/MrGuillote/CURSOS/assets/89352244/30c4d3f0-2e88-4ef9-a8dc-0b5886d02633)

A pesar de todo lo demostrado, existen administradores de red que aún confían en procesos como el filtrado MAC. Tal vez porque resulta más práctico, o porque simplemente no ven el riesgo de que haya algún tipo de ataque. Sin embargo, ya no existe organización a salvo de los ataques, y si no se toman las medidas de seguridad adecuadas, las consecuencias pueden tener costes demasiado altos.

Por otro lado, el usuario común con permisos de administrador y con el mínimo nivel de conocimiento para hacerlo, puede manipular la dirección MAC de sus adaptadores de red. He ahí el motivo por el cual recomendamos tener precaución con guías como estas y saber lo que se está haciendo.
