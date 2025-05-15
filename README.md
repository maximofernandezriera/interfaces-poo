# Las interfaces y cosas que molan como los restaurantes

Estás un restaurante. No necesitas saber cómo funciona la cocina, qué ollas usan o la receta secreta del chef para cada plato. Lo único que te importa es la **carta (el menú)**. La carta te dice qué platos puedes pedir (entrantes, principales, postres) y, una vez que pides algo, esperas recibir ese plato.  
En la programación orientada a objetos, una **interfaz** es como esa carta del restaurante. Es un **contrato** que dice "esto es lo que se puede hacer", pero no dice *cómo* se hace.  

**¿Para qué sirve?**  
Sirve para definir un conjunto de acciones que diferentes tipos de objetos pueden realizar, sin importar cómo las realizan internamente. Volviendo al ejemplo:

* Diferentes "cocinas" (objetos en programación) pueden preparar una "lasaña" (una acción definida en la interfaz "MenúItaliano"). Una podría ser una cocina de un restaurante de lujo y otra la cocina de tu casa. Ambas "implementan" la acción "hacer lasaña" de la interfaz "MenúItaliano", pero cada una lo hará a su manera, con sus propios ingredientes y técnicas.

La interfaz ("MenúItaliano") solo garantiza que podrás "pedir lasaña" y obtendrás algo que es una lasaña. Esto permite que tu programa principal (el "comensal") pueda interactuar con cualquier "cocina" que cumpla con la interfaz "MenúItaliano" de la misma manera, sin preocuparse por los detalles específicos de cada una. Esto hace que el código sea más flexible y fácil de mantener.  
En resumen, una interfaz es un **acuerdo sobre qué se puede hacer**, permitiendo que diferentes partes de un sistema colaboren sin necesidad de conocer los detalles internos de las otras, siempre que todas respeten ese acuerdo.
