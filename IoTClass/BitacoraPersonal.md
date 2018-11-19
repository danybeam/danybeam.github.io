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

## Se aviso a la maestra que a partir de este punto se reporta por semana

## Semana de 15/10 &rarr; 21/10
* 20-10-2018:
   * Modulo para medir CO2:
      * El tener estos modulos individuales tenemos los prototipos base de como todo se conecta a internet
      * con este modulo terminamos de programar lo necesario para generar datos
   * Programa de punto de entrada y ciclo infinito:
      * Con este programa se integraron todas las tecnologias para el proyecto
      * Con este programa podemos usar los modulos continuamente para hacer mediciones y empezar a hacer analitics en la nub

## Semana de 22/10 &rarr; 28/10
Nos pusimos de acuerdo para hacer trabajo no relacionado con la materia  
No hubo avances

## Semana de 29/10 &rarr; 04/11
* IoT Day, 03/11:
   * Empece plugin de heatmap para ThingSpeak
      * esto nos permitio poder cumplir un requerimiento directo y no tener que bajar la escala de nuestro proyecto
   * Hice diagrama UML del proyecto
      * al poder ver la arquitectura del proyecto en una sola imagen es mas facil mantener el codigo porque sabemos que funcion tiene cada componente
   * Hice diagrama ER
      * al tener la estructura de las tablas que almacenan informacion podemos saber a que tenemos acceso y a que no

## Semana de 05/11 &rarr; 11/11
* 10/11/2018:
   * Termine el plugin de heatmap con opcion para cambiar el radio de los puntos automaticamente
      * esto nos permite saber que tanta influencia ejerce cada nodo dentro del sistema en general

## Semana de 12/11 &rarr; 18/11
* 17/11/2018:
   * Co-escribir el reporte
