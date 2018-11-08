# ¿Qué contiene el MBR?


El MBR, son sectores que dividen datos en los DD. El tamaño mínimo de 
cada sector es de 512 B.

El primer sector del DD es el llamado MBR, esta contemplado el 
Programa del Gestor de Arranque, que mide 446 B, y se encarga de que 
el SO sea ejecutado correctamente. En segundo lugar hay un espacio 
reservado para la Tabla de Particiones, que almacena los datos de las 
particiones que ser han echo en el DD. Ocupa 64 B.
Y para finalizar, tenemos el numero de identificación del MBR, 
que se llama Firma. Solo ocupa 2 B.
