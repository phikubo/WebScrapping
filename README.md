# WebScrapping
Archivos para bajar imágenes para ML y relacionados.


##Instrucciones

    Para descargar un conjunto de datos:
        1) Abrir Chrome
        2) Realizar busqueda y seleccionar opción imagenes
        3) Abrir herramientas de desarrollador y abrir consola (javascript)
        4) Realizar un scroll sobre las imagenes hasta donde se desee.
        5) Ejecutar linea por linea de código javascript hasta conseguir descargar el urls.txt
        6) Crear la carpeta images y subcarpeta con el nombre deseado por ejemplo nombreDeCarpeta
        7) Comprobar en el entorno virtual existen las librerías: requests, cv2, argparse y imutils
            7.1) Si alguna no existe se debe descargar con pip, resulta util: pip install opencv-python-headless para cv2 y imutils
        8) Ejectuar el archivo de python así:
            #python downpics.py --urls urls.txt --output images/nombreDeCarpeta
        9) Eliminar imagenes innecesarias.
