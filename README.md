Proyectos Personales en Python
Se cargan dos documentos ejemplos del trabajo personal hecho por Juan Manuel Lopez

En el repositorio se cargaron dos ejemplos muy utiles para diferentes propositos en los cuales la extraccion de informacion para asi extraer sus metadatos y en el segundo se encarga de cifrar cualquier mensaje echo por la persona y decifrado 

Cifrado de mensajes-PIA.py
- Cifra y decifra mensajes en base64
- Codigo bien explicado y comentado
- pueden hacerce cambios para cifrados mas seguros

Extraccion de metadatos-PIA.py
- Utiliza librarias compatibles 
- Puede cambiar la URL que usted prefiera
- Puede extrar todo dato o imagen de la pagina elegida 

INSTRUCCIONES 
 
Cifrado de mensajes-PIA.py

Instalar las dependecias necesarias:
pip install pycryptodome

Guarda el archivo como criptografia.py y ejecútalo en la terminal con:
python criptografia.py

Cuando el programa lo solicite, escribe un mensaje que deseas cifrar:
Mensaje: Hola, esto es una prueba

Una vez ingreasdo el mensaje el programa va a generar:
- Llaves RSA (privada y pública)
- Mensaje cifrado
- Mensaje descifrado

Extraccion de metadatos-PIA.py

Instalar las dependecias necesarias:
pip install requests beautifulsoup4

Guarda el archivo como extraccion_metadatos.py y ejecútalo en la terminal con:
python extraccion_metadatos.py

El programa se encargara de:

- Accede a la página web definida en URL_BASE.
- Extrae las publicaciones buscando elementos HTML específicos (div, span).
- Obtiene el título, autor y fecha de cada entrada.
- Imprime los resultados en la consola en el formato:
