# MLOps
***
### TL;DR

Como meter Machine Learning en las empresas es más complicado de lo que parece, se han inventado un montón de técnicas chulas para conseguirlo. Sin ellas se sufre mucho. Básicamente, es muy parecido a cocinar bien:

- Pesalo bien todo
- Apunta bien la receta que vas siguiendo
- Prueba como va quedando la cosa
- Echale un ojo, que no se queme
- Servir bien a los invitados
- Repetirlo y que salga genial!

---

Una de las últimas *buzzwords* en el mundo de Data Science es **MLOps** o *Machine Learning Operational Management*. Hace poco era lo que se llamaba Machine Learning en producción, pero con el paso de los últimos 1-2 años ha ido evolucionado a este nombre mucho más apetecible para cualquier *slide*.

![alt text](https://github.com/KaonToPion/mlops/blob/main/mlops.svg? "Ciclo MLOps")


La construcción del concepto MLOps se ha ido formando según las empresas han ido dandose cuenta de que el Machine Learning no funcionaba. 


![alt text](https://github.com/KaonToPion/mlops/blob/main/kim.gif? "Oh mama")

*"Uf, lo que ha dicho"*

Muchos proyectos se quedaban en el limbo de los notebooks o los power points. Se asigna dinero para un proyecto, pero llevar ese modelo a una infrastructura para que diese un servicio constante (productivizar) era otro cantar. Algunos, pocos, llegaban a esa situación, pero una vez ahí ¿que pasaba? ¿Se seguían entrenando? ¿Y si cambian los datos? ¿Y si salía un modelo mejor? Un lío.

Para que Data Science funcione aplicado al mundo empresarial tiene que ser capaz de escalar y de no convertirse en un monstruo imposible de mantener.

La pregunta obvia es ¿porqué es diferente de lo que se ha hecho con el desarrollo *tradicional* de software? 
Este es posible gracias a una serie de técnicas de ingeniería desarrolladas durante años que básicamente consisten en gestionar bien código de programación. Desde la aparición de la [*IAC*](https://en.wikipedia.org/wiki/Infrastructure_as_code) (Infrastructure as Code), esto se ha extendido incluso a la gestión de la arquitectura y la infrastructura. Gracias a esto las prácticas [DevOps](https://en.wikipedia.org/wiki/DevOps) han permitido simplificar y escalar procesos y operaciones.

Aquí es donde viene el PeRo con el Machine Learning. Los modelos de aprendizaje son el resultado de la interacción de estas dos cosas:

- El código: Lo que podríamos llamar *El Algoritmo*. 
- El dato: Lo que podríamos llamar *el bollicao* del Algoritmo

Cambios en cualquiera de estos dos componentes, darán un resultado diferente.Claro, esto le duele un poquito en el corazón al desarrollo de software tradicional. Tu puedes tener un código brutalmente bien hecho, testeado, unas clases de colegio privado, con la documentación justa, pero...*crap in, crap out*. Pero lo peor no es eso, sino que en no pocas ocasiones, es simplemente *sth different in, who the fuck knows what's out*. 



**La Ingeniería** ha vuelto a ponerse las pilas y a partir de unos pocos principios muy simples, han empezado a surgir un montón de herramientas y técnicas:


1. Asegurate de todas las cantidades (Reproducibilidad).
Llevar un buen registro de como se ha generado el modelo.
 - Datos: Guardate un hash,la query para obtenerlos o los propios datos utilizados.
 - Código: Obvio
 - Máquina utilizada

2. Apunta la receta cada vez que hagas el plato (Versionado)
 
3. Prueba el plato, a ver cómo queda (Testing)

4. Echale un ojo, no sea que se te queme (Monitorizar)

5. Sirveselo a los invitados como el mejor camarero (Despliegue)

5. Ahora, repitelo con los ojos cerrados, y que esté igual de rico (Automatizar)
 



