## ElasticSearch Kibana con docker

Fichero de docker-compose para ejecutar los contenedores de ElasticSearch y Kibana

## Pasos para la ejecución

1. Asegurese de tener instalado docker y docker compose. Sino lo tienen pueden usar está guía para [Ubuntu](https://www.digitalocean.com/community/tutorials/como-instalar-docker-compose-en-ubuntu-18-04-es)
2. Descarguen el archivo docker-compose.yml y coloquenlo dentro de una carpeta.
3. Crear un volumen de persistencia para elasticsearch: > docker volume create elasticsearch-data
4. Desde la consola moverse hacia la raíz de la consola y ejecuten docker-compose up.

Para aprender más sobre ElasticSearch sigue este curso en [Youtube](https://www.youtube.com/channel/UCRfR3e3wnN4qzesjajbgu1Q).
Para aprender más de tecnología en español unete a nuestro [Tech Blog](https://blog.sacavix.com)
