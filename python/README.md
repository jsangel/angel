Computacion-Blanda




El c�digo de Backpropagation.py utiliza como entradas el archivo cancerdata.csv

El archivo cancerdata.csv tiene los datos de 600 tumores de cancer de mama. Cada fila est� compuesta por 10 columnas con los datos organizados de izquierda a derecha as�:

Clump Thickness: 1 - 10
Uniformity of Cell Size: 1 - 10
Uniformity of Cell Shape: 1 - 10
Marginal Adhesion: 1 - 10
Single Epithelial Cell Size: 1 - 10
Bare Nuclei: 1 - 10
Bland Chromatin: 1 - 10
Normal Nucleoli: 1 - 10
Mitoses: 1 - 10
Class: (2 for benign, 4 for malignant)
Backpropagation.py se entrena por 200 �pocas y luego da como salidas el resultado esperado y la predicci�n del algoritmo, si la preducci�n fue correcta la l�nea es visualizada con fuente color verde, de lo contrario la fuente es roja. Finalmente se muestra la presici�n del algoritmo.

NOTA: El c�digo utiliza para el formato de colores de fuente c�digos de escape ANSI, por lo tanto solo se pueden visualizar correctamente los colores de fuente en las salidas en sistemas LINUX/UNIX o en un entorno como PyCharm en Windows.