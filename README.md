Examen_parcial_2_Fabian_y_Noé
1.	Descargar archivo dataset.xlxs. 
2.	Tener OpenRefine
3.	Procesar el archivo dataset.xlxs en OpenRefine 
4.	Editar los nombres de los autores: 
a.	Los nombres siguen la siguiente estructura: Apellido, nombre
b.	Eliminar los caracteres especiales de los nombres
c.	Aplicar los métodos de cluster: 
i.	Key collision – fingerprint
ii.	Key collision – metaphone3
iii.	Key Collision – Daitch-Mokotoff
iv.	Nearest neighbor – ppm


5.	Editar los lugares de publicación: 
a.	Quitar los caracteres especiales de los lugares de publicación
b.	Aplicar el método de cluster:
i.	Key collision – fingerprint
6.	Editar las editoriales: 
a.	Quitar los caracteres especiales de la columna de editorial
b.	Aplicar los métodos de cluster:
i.	Key collision – fingerprint
ii.	Key collision – Metaphone3
iii.	Key collision – Daitch-mokotoff
iv.	Nearest neighbor – ppm
7.	Editar los años de publicación: 
a.	Los años deben de venir en formato de número, para esto quitar los caracteres especiales. 
b.	Aplicar los métodos de cluster:
i.	Key collision – fingerprint
ii.	Key collision – ngram-fingerprint
c.	Transformar esta columna a número

8.	Descargar el archivo procesado de OpenRefine en formato .xls 
9.	Crear carpetas y modificar nombres de archivos en una estructura adecuada:
-	Crear dos carpetas (para los datos procesados y sin procesar, respectivamente).
-	Editar el nombre de los archivos con el siguiente formato: año_mes_día_procesar/sin_procesar. Ejemplo: 2021_08_11_procesados
