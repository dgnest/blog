---
layout: post

title: Una Mirada Desde El Otro Lado
subtitle: "un subtitulo va aqui"
categories: post
cover_image: /media/dgnest/blog-cover.jpg

excerpt: "El resumen que va en la postada del blog, va aqui..."

author:
  name: Vanessa Montezuma
  twitter: vanemontezuma
  link: https://twitter.com/vanemontezuma
  bio: dgnest's Member, Brand Strategist, Maker
  image: members/vanessa.png
---

Creo que no existen muchos lugares en la universidad donde se tenga la libertad de crear proyectos interdisciplinarios. En mi caso, la experiencia en el Fab Academy que llevé el 2013 hizo que cambiara mi perspectiva sobre lo que distintas visiones sobre un problema pueden lograr para crear cosas más allá de lo que uno pudiera haber imaginado.

El Fab Academy es un programa internacional del Massachussetts Institute of Technology (MIT) dirigido por Neil Gershenfeld del MIT’s Center for Bits and Atoms, basado en un curso de prototipaje rápido llamado MAS 863: Como hacer (casi) todo. Empezó siendo un programa del Center for Bits and Atoms, pero ahora se ha esparcido por todo el mundo, generando redes de fab labs. El primer Fab Lab fundado en Sudamérica fue el Fab Lab UNI, hace ya un par de años, y es donde lleve este programa.

La idea principal del programa es que uno pueda aprender a usar todas las herramientas disponibles en el laboratorio para crear prototipos rápidos. A través de seis intensos meses se aprende de todo. Cada semana tenemos una conferencia con Neil Gershenfeld, donde se explica un poco de teoría y se nos asigna una tarea que se debe cumplir, que puede ir desde escanear un objeto en 3d hasta fabricar desde cero una placa con un sensor de luz y programarla. 

La primera semana se debe realizar un video de nuestra idea para el proyecto final, que es básicamente un bosquejo de lo que se realizará después, ya que debe integrar lo que se va a aprender en los siguientes meses. Las siguientes semanas se van aprendiendo distintos conocimientos, y en las dos últimas se pide, por un lado, que se realice un plan del prototipo respondiendo una serie de preguntas para especificar lo que se va a realizar: que se va ha hacer, que materiales va a necesitar, donde se van a adquirir estos materiales, cuanto va a costar, que tareas deben ser completas, que dudas todavía están pendientes, y un calendario de actividades hasta el día de la entrega. Por otro lado se debe registrar todo (si, todo) lo que se va avanzando del proyecto final, y se debe intentar cumplir con el calendario pensando, aunque, la última semana siempre es caótica y se debe estar listo para que suceda lo impensable. 

Por una parte me sentía cómoda con programas de modelado 3d, ya que en mi carrera estamos familiarizados con programas de este tipo, y no era tan difícil empezar a usar Rhino, o utilizar cualquiera de los programas de Autodesk como 123d Make. Pero lo que si fue un reto fue fabricar placas de electrónica desde cero. 

Una de las particularidades del Fab Academy es que sigue una metodología muy interesante de hacerlo uno mismo: básicamente te lanzan a la piscina a ver qué sucede. Los instructores dan algunas ideas de cómo podemos empezar, pero uno debe de aprender haciendo. Además de eso, todo debe hacerse desde cero, por eso las placas se fabrican en el mismo Fab Lab y es preferible que no se utilice, por ejemplo, un Arduino. Ya que se tratan de prototipos, siempre se nos incentiva a que hagamos todo desde cero, o con otras placas creadas en el mismo ambiente del Academy. 

Los instructores nos enseñaban como utilizar las máquinas, en el caso de las placas, la Roland Modela, pero luego nosotros teníamos que sentarnos y hacerlo. No hace falta decir que los primeros intentos fueron desastrosos: la Roland Modela es básicamente una mini fresadora, y por lo tanto, hay que saber colocar la fresa para que los trazos de la placa no salgan muy delgados.

Durante todo el curso tuve una relación amor-odio con esa máquina, pero para ser honesta, creo que todos la teníamos. En algún momento llegué a llevarme bien con ella, pero siempre tenía momento en que quería desenchufarla y tirarla a la Túpac Amaru para que un camión le pase encima. Pero no me malinterpreten, ese fue un punto al que ahora miro con algo de nostalgia, y pienso que si bien tuve que en algún momento tuve que hacer cinco placas seguidas y ya estaba a punto de desistir, aprendí bastante de qué cosas hacer y qué no.

<div class="full zoomable"><img src="http://academy.cba.mit.edu/2013/students/montezuma.vanessa/images/sessions/w4/fabisp.jpg" alt="fabduino"></div>

<p>Uno de las primeras tareas fue hacer un Fab ISP, que es un programador para microcontroladores AVR diseñado para la producción en el Fab Lab. Como ven en la imagen, se conecta por un cable usb a la PC, y por un cable de 6 pines a otra placa, en la cuál se puede subir un programa determinado. El Fab ISP es básico para hacer casi todas las cosas del Fab Academy. Hacerlo fue una tarea algo compleja, y tuve que hacer varios intentos hasta que finalmente obtuve una luz verde -como se ve aquí en la foto triunfal- y el firmware cargó con éxito. Y si, mi Fab ISP funciona hasta ahora. Pero cuando llegó la última semana fue cuando todo comenzó a tomar más forma. Mi idea siempre había sido crear un objeto que combinara la arquitectura, el espacio público y que interactuara con las personas, que pudiera moverse o encenderse en la noche.

Comencé a pensar en que cosas se encuentran en un parque y que podrían interactuar de manera interesante con las personas. Así me imaginé que podría tratarse de un animal, como un ave que estuviera a punto de comenzar a volar.

Así fue como nació **MAPI**.

<div class="full zoomable"><img src="http://academy.cba.mit.edu/2013/students/montezuma.vanessa/images/presentation.png" alt="mapi"></div>

<div class="full">
<iframe width="640" height="360" src="//www.youtube.com/embed/4JuSptUoSYw" frameborder="0" allowfullscreen></iframe>
</div>

Se trata de un ave -aunque de perfil parece más un pterodáctilo- que se puede ubicar en un parque, y con un sensor de luz se enciende durante la noche al mismo tiempo que comienza a mover sus alas.

Para realizarlo decidí hacer un FabDuino, que como lo dice su nombre es un Arduino hecho con componentes del FabLab. Lo bueno del FabDuino es que una vez listo se puede usar en con Arduino Environment sin ningún problema. Hacerlo fue otro reto importante, desde hacer la placa, que tiene muchos detalles, hasta colocar todos los componentes con mucha paciencia para no quemar nada (y tener que volverlo a hacer todo de nuevo), y finalmente programarla en la terminal de ubuntu.

Definitivamente el Fab Academy fue una experiencia importante ya que me abrió todo un nuevo panorama. Como arquitecta podría haber diseñado un objeto, imaginado que se iluminaría y como se movería. Pero dentro del ambiente del Fab Lab pude hacerlo, crearlo con mis propias manos y saber de primera mano qué cosas funcionarían, que cosas no, y si podría eventualmente comercializarlo. Por esa razón, estar en un ambiente donde se ven proyectos de distintas profesiones (electrónica, mecatrónica, mecánica, diseño industrial, etc.) puede generar muchas posibilidades y alimentar la imaginación para crear cosas geniales.