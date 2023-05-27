# scan
Este proyecto es una aplicación que utiliza HTML, CSS, JavaScript para encriptar y desencriptar texto. La encriptación se realiza mediante la sustitución de ciertas letras por otras según un conjunto específico de reglas. La aplicación solo acepta letras minúsculas y no se permiten acentos ni caracteres especiales.

La página web cuenta con campos para que el usuario pueda ingresar el texto que desea encriptar o desencriptar y seleccionar la opción correspondiente. El resultado de la operación se muestra en la pantalla y existe la opción de copiar el texto encriptado o desencriptado al portapapeles mediante un botón de "copiar".
This app uses Redis as a vector database, but there are many other options highlighted ../examples/vector_databases depending on your need.
This is a simple starting point - if you hit issues deploying your use case you may need to tune (non-exhaustive list):
The prompt and parameters for the model for it to answer accurately
Your search to return more relevant results
Your chunking/embedding approach to store the most relevant content effectively for retrieval
