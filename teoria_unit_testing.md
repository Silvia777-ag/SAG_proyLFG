UNIT TESTING es una técnica de prueba que valida el funcionamiento de las unidades de código más pequeñas y aisladas, como funciones o métodos, para garantizar que se comporten como se espera. 

COMO USAR escribiendo código de prueba que define una entrada esperada y valida la salida en el código a probar.  Procedimiento identificar la unidad: Elige el componente más pequeño que quieres probar (una función, un método, una clase).  Escribir el código de prueba: 
Crea un script de prueba que: configure el entorno necesario, ejecute la unidad de código con una entrada específica, valide que la salida obtenida coincide con el resultado esperado, ejecutar el código de prueba y verifica si pasa o falla.

TEST DOUBLES (dobles de prueba) se usa si la unidad depende de otras partes del sistema, usa test doublés como mocks o stubs para aislar la unidad que estás probando.

POR QUÉ USAR para detectar errores tempranamente, mejorar el diseño del código, asegurar la calidad y facilitar la refactorización sin introducir regresiones. 
Para la detección temprana de errores, identifica fallas en el código rápidamente, antes de que se integren con el resto del sistema.
Mejora el diseño, obliga a escribir código más modular y desacoplado, ya que cada unidad debe ser fácil de probar de forma aislada.
Previene regresiones, si un error corregido reaparece, las pruebas fallarán, evitando que la versión defectuosa llegue a producción.
Facilita la refactorización, permite reestructurar el código de forma segura, sabiendo que las pruebas seguirán validando la funcionalidad existente.
Proporciona confianza aumenta la seguridad al realizar cambios, ya que se tiene un conjunto de pruebas automatizadas que verifican el correcto funcionamiento.

CUÁNDO USAR Durante todo el ciclo de desarrollo, especialmente cuando se escribe una nueva unidad de código o se corrigen errores, y de forma automatizada antes de realizar cambios o despliegues. 
Antes de implementar una nueva funcionalidad, escribe las pruebas unitarias para la nueva unidad de código.
Al corregir un bug, crea una prueba unitaria que reproduzca el error antes de corregirlo.  De esta manera, la prueba fallará y, al corregir el código, la prueba pasará, asegurando que el error no reaparecerá.
Durante la integración, asegura que cada módulo funcione correctamente antes de integrarlo con otros componentes del sistema.
Como parte del proceso de despliegue, integra las pruebas automatizadas en tu flujo de integración continua para que se ejecuten automáticamente cada vez que se realiza un cambio en el código o antes de desplegar una nueva versión.
