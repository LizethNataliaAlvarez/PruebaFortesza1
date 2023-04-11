# Proyecto de Automatización con Serenity
Este proyecto de automatización utiliza Serenity BDD para realizar pruebas de automatización en aplicaciones web.

# Instalación
Antes de poder utilizar este proyecto de automatización, debes instalar las siguientes herramientas:

Java 8 
Gradle 7.6
ChromeDriver Versión 112.0.5615.50 (Build oficial) (64 bits)

Se clona este repositorio utilizando el siguiente comando:

bash
Copy code
git clone https://github.com/LizethNataliaAlvarez/PruebaFortesza2.git

# Ejecución
Para  realizar la ejecución por medio de la terminal de la prueba automatizada se ejecuta el siguiente comando:

bash
Copy code
gradle clean test aggregate

Para realizar la ejecución por medio del proyecto se ejecuta el archivo "Runner"


# Comando para generar los reportes de la prueba Automatizada

# gradle clean test aggregate - 
Ejecuta todas las pruebas de automatización y genera un informe de resultados en formato HTML.

# gradle clean test aggregate -Dtags="login" - 
Ejecuta solo las pruebas de automatización que tienen la etiqueta "login" y genera un informe de resultados en formato HTML.

gradle clean test aggregate -Dheadless.mode=true - 
Ejecuta todas las pruebas de automatización en modo headless y genera un informe de resultados en formato HTML.

# Información de Contacto
Si tienes alguna pregunta o problema con este proyecto de automatización, puedes ponerse en contacto conmigo en mi dirección de correo electrónico: lizethnaq13@gmail.com.
