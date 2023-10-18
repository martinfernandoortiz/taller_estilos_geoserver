<h2>Taller Interno IGN - Estilos en Geoserver - 2023</h2>

<h4>Prerequisitos:</h4> 

* tener docker, y docker compose instalado
* algún QGIS instalado
* algún editor de Código instalado (VS Codium, o similares)
* conocimientos básicos de cartografía

<h4>Instalación</h4>

1. Descargar el archivo * [docker-compose.yml](https://github.com/martinfernandoortiz/taller_estilos_geoserver/blob/main/docker-compose.yml) ![imagen](https://github.com/martinfernandoortiz/taller_estilos_geoserver/assets/38224115/5729c704-7cc8-43c3-a7f3-5094ae3ef4fb)

2. Crear una carpeta en Documentos que se llame "Docker"
3. Copiar el archivo descargado a la carpeta "Docker"
4. Abrir Símbolo de Sistema - Toca el botón de inicio de Windows y escribi cmd

![imagen](https://github.com/martinfernandoortiz/taller_estilos_geoserver/assets/38224115/e93782de-0b74-4097-b677-7a2db329aad6)


5. Escribí en la cmd ```cd Documents/Docker```  - Lo que hará ésto es ir a la carpeta Docker dentro de Documents. Puede ser que en tu computadora Documents se llamé Documentos. En ese caso pone ```cd Documentos/Docker```![imagen](https://github.com/martinfernandoortiz/taller_estilos_geoserver/assets/38224115/021ea4b5-2bb3-4c40-ae23-69068a60552e)

6. Escribí ```docker-compose up -d```  Lo que hará esto es instalar en un contenedor geoserver y postgis. Cuando termines ya estará todo instalado
7. En un navegador, ejecuta ```http://localhost:8080/geoserver ``` . Recorda que de forma predeterminada las credenciales de geoserver son  ```usuario: admin  password:geoserver ```
8. Cuando dejes usar geoserver escribí en la cmd  ```docker-compose stop ``` . Ésto es importante, sino tu computadora seguirá consumiendo memoria
9. Cuando quieras volver a utilizar geoserver, repetí el paso 4 y 5 para después escribir ```docker-compose start ``` . Cuando termines repetis el pasó 8
---


