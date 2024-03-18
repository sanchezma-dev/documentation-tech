
# Apache kafka con spring boot

Antes de adentrarnos en los detalles, es importante comprender qué es Apache Kafka y cómo se integra con Spring Boot.
Apache Kafka es una plataforma de transmisión de eventos distribuida diseñada para crear aplicaciones escalables y de baja latencia. Se ha convertido en una herramienta fundamental para el procesamiento de datos en tiempo real y la implementación de sistemas asincrónicos eficientes. En resumen, Kafka facilita la comunicación entre aplicaciones y permite realizar acciones de manera no bloqueante, lo que garantiza un rendimiento eficiente y sin interrupciones para los usuarios.

La integración de Kafka con Spring Boot se basa en el uso de módulos como Spring Kafka, que proporciona una API de alto nivel para interactuar con los productores y consumidores de Kafka. Además, Spring Boot ofrece una configuración automática inteligente, lo que significa que muchos aspectos de la configuración de Kafka se pueden manejar automáticamente, reduciendo así la carga sobre los desarrolladores.


### Algunos términos necesarios identificar:

- **Broker**: Un broker en Apache Kafka es un servidor que forma parte de un **clúster** y es responsable de gestionar los datos almacenados en los topics, así como procesar los datos entre productores y consumidores. Es decir,  los brokers son los nodos individuales que componen el sistema distribuido de Kafka y realizan tareas como el almacenamiento, el enrutamiento y la replicación de los datos.
- **Clúster**: Es un conjunto de uno o más servidores (brokers), que trabajan juntos para gestionar los datos y garantizar la tolerancia a fallos y la escalabilidad.
- **Topic**: Es una categoría (**temas**) donde se publican los mensajes. Los **productores** envían mensajes a un topic y los **consumidores** leen de él. Los topics están divididos en **particiones**.




Instalación



Configuración de propiedades



Producer



Consumer




Conclusión


