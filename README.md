# Dev container para artículo científico

En este repo se encuentra la configuración para elaborar un artículo científico usando Python y Quarto. 

La manera más sencilla de usar este repo es seguir las siguientes indicadiones.

## Requisitos de software

- Instalar VS Code
- Instalar Git
- Instalar Docker
- Instalar la extensión "Dev Containers" en VS Code

## Pasos

- Tener Docker corriendo en la PC
- Clonar el repositorio
- Abrir el folder clonado en VS Code
- Aparecerá una notificación en VS Code preguntando si quieres abrir el folder en un dev container. Elegir que sí. VS Code empezará el proceso de construcción del dev container. Esto puede tomar varios minutos. Una vez concluído, se podrá acceder a los archivos y editar.
- El archivo principal es "index.qmd", puedes hacer cambios en tu versión local. Para integrar cambios, usar Pull Requests en Github.

En caso requieras instalar librerías de Python, añadirlas al archivo "requirements.txt". Luego de eso, abrir la Paleta de Comandos de VS Code y elegir "Rebuild dev container".