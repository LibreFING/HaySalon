TODO cosas para hacer:
=======================

- Diagramar layout y vistas `listo`
- Programar el layout `en proceso`

- Obtencion de datos:
  - Forma 1: Aprovechar el UniTime de la Fing
    - Queda pendiente investigar mas a fondo sobre unitime y que posibilidades se tiene para realizar consultas.
    - http://www.fing.edu.uy/sysadmin/aplicaciones/unitime
    - http://www.fing.edu.uy/sites/default/files/2013/7202/informe-v1.1.pdf

  - Forma 2: Obtener los datos del pdf
    - Info sobre OCR de tablas en PDF's: `leer links`
      - http://stackoverflow.com/questions/6173439/can-ocr-software-reliably-read-values-from-a-table
      - http://stackoverflow.com/a/14419669/1710845 
      - PDFMiner (utilidad de python): http://www.unixuser.org/~euske/python/pdfminer/

    - Si bien es algo interesante para experimentar, no tiene mucho sentido puesto que son pdf's generados por unitime mismo.
    - Es totalmente ineficiente parsear la info de pdf generados desde una base de datos, cuando se tiene acceso a esa misma base de datos (esperamos tener acceso).
    - Modulo para  extraer datos del pdf: http://www.fing.edu.uy/horarios ` En proceso`
    - Parsear datos (las horas materias y los salones)

- Mostrarlos en un listView inicialmente


Ideas locas para implementar
=============================

Aca `*vos*` aportas ;)

- Avisar al usuario x minutos antes, que tiene una clase próximamente, informando nombre de materia, horario, salón
  y datos extra dados por el user.
- Codigos QR impresos en cada salon para escanear con el celular y la aplicacion te de info sobre horarios ocupados de ese salon y salones cercanos que esten libres
