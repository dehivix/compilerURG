Compilador basico para el lenguaje "UNERG"
    UNERG es un lenguaje de caracter muy basico creado para aprender a utilizar la libreria ply de python.

Puedes usarlo corriendo desde el terminal el siguiente comando:

   % python basic.py hello.unerg
   HELLO WORLD
   %

O usarlo de forma interactiva (como python):

   % python unerg.py
   [BASIC] 10 PRINT "HELLO WORLD"
   [BASIC] 20 END
   [BASIC] RUN
   HELLO WORLD
   [UNERG]

Esta es la definicion de los archivos utilizados:

   unerg.py         - Script de alto nivel que controla toda la app
   unergLex.py      - tokenizador donde se definen los tokens 
   unergParse.py      - parser donde se definen las reglas para sintaxis
   unergInterp.py     - interprete esto permite la ejecucion de los programas

debe usarse el sufijo ".unerg" para los programas, hay una lista de programas
de ejemplo con la sintaxis definida por este pequeño compilador en la carpeta /examples

Sin mas que decir "Happy hacking"
