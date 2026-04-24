# Mi aprendizaje
### Limitación de Recursos
Como ya sabía configurar recursos en máquinas virtuales, este concepto no se me hizo muy diferente, pero me sorprendió la flexibilidad de Docker. También me quedó muy clara la lógica para calcular la memoria swap (que no había configurado antes).

### Healthcheck
Este concepto fue totalmente nuevo. Antes pensaba que si un contenedor estaba levantado significaba que todo estaba perfecto. Gracias a la práctica, ahora entiendo que un proceso puede estar corriendo pero la aplicación puede estar "muerta" por dentro. Ademas me parecio muy util la forma de intervalos para estar constantemente supervisando.

### Dockerfile
Ya había imaginado que debía haber una forma de guardar o automatizar todo el trabajo que hacía dentro de los contenedores para no repetirlo, pero no sabía cómo. Con el Dockerfile descubrí como se hace. Aprendí la importancia de cada capa (FROM, RUN, COPY), y en general me parció muy facil configurar todo en un archivo de texto plano ya que puedo editarlo como un txt.

### Políticas de Reinicio
Aprendí que Docker puede actuar ante errores con el reinicio. Lo que más me llamó la atención fue la diferencia entre always y unless-stopped; ahora sé que si apago un contenedor manualmente y reinicio mi computadora, unless-stopped respetará mi decisión de dejarlo apagado, mientras que always intentará levantarlo pase lo que pase. 

