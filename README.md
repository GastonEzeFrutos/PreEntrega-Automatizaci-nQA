# PreEntrega-Automatizaci-nQA
Automatización de Pruebas - Sauce Demo

Propósito del Proyecto

Este proyecto tiene como propósito validar la automatización de la página web de comercio electrónico de pruebas Sauce Demo (Swag Labs). A través de scripts automatizados, se busca garantizar el correcto funcionamiento de los flujos principales de la aplicación, como la interacción con el carrito de compras.

Tecnologías Utilizadas

Python: Lenguaje de programación base.

Selenium WebDriver: Herramienta para la automatización de acciones en el navegador web.

Pytest: Framework de pruebas para estructurar y ejecutar los tests de manera eficiente.

Visual Studio Code (VS Code): Editor de código utilizado para el desarrollo del proyecto.

Instalación

Para poder ejecutar este proyecto en tu entorno local, necesitas tener Python instalado. Luego, sigue estos pasos para instalar las dependencias necesarias:

Clona este repositorio en tu equipo local.

Abre la carpeta del proyecto en Visual Studio Code.

Abre una nueva terminal en VS Code y ejecuta los siguientes comandos para instalar Selenium y Pytest:

pip install selenium
pip install pytest


(Nota: Se recomienda utilizar un entorno virtual para instalar estas dependencias).

Ejecución de las Pruebas

Para correr los casos de prueba automatizados, asegúrate de estar en el directorio raíz del proyecto desde tu terminal y ejecuta el siguiente comando:

python -m pytest test_cart.py


Esto iniciará la ejecución de las pruebas definidas en el archivo test_cart.py y mostrará los resultados en la consola.
