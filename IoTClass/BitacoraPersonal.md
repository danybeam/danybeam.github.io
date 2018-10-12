# Bitacora IoT Daniel Gerardo Orozco Hernandez
## Sprint 1 (17/09 &rarr; 29/09)
* 25-09-2018:
    * Investigar caracteristicas sobre los mosquitos para saber que sensores utilizar
        * De la investigacion resulto que con medir la temperatura y la humedad era suficiente para tener una metrica inicial de la probabilidad de creacion de mosquitos
        * Contribuyo al proyecto en que nos permitio darnos cuenta que no necesitamos demasiados sensores para empezar a generar datos
* 29-09-2018:
    * Conseguir Raspberry Pi
        * Al decidirnos por una raspberry pi (RP) nos dimos cuenta que podemos hacer un poco de fog computing lo que abarataria los costos de los servicios en la nube
        * Ademas ya que nuestro prototipo solo constara de unos cuantos tableros no podiamos garantizar que la plataforma ThingSpeak tuviera un procesamiento muy complejo para los datos que planeabamos mandarle

## Sprint 2 (30/09 &rarr; 13/10)
* 06-10-2018:
    * Inicializar raspberry pi:
        * Al inicializaer rapidamente la raspberry pi fuimos capaces de prototipar rapidamente para saber cuales fueron los posibles errores que se podrian cometer (i.e. equivocarnos de sensor) y tener tiempo suficiente para corregirlos
    * Modulos para usar thingspeak, el medidor de temperatura/humedad y medidor de dioxido de carbono
        * El tener estos modulos individuales tenemos los prototipos base de como todo se conecta a internet
        * Ademas con estos prototipos pudimos hacer pruebas sobre permisos que pudieran haber faltado en algun punto del proceso
