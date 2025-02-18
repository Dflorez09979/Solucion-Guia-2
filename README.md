# Solucion-Guia-2

import pandas as pd
# Ruta
file_path = r'E:\\OneDrive - Banco Agrario de Colombia S.A\\PROGRAMACION PARA CIENCIA DE DATOS\\telecom_churn.csv'
# Importa el archivo
df = pd.read_csv(file_path)
# Muestra las 5 primeras filas del Df
print("5 primeras filas del Df:")
print(df.head())
# Cuenta filas y columnas tiene el Df
print("\nNúmero de filas y columnas:")
print(df.shape)
# Muestra información general del Df y el tipo de Dato
print("\nInformación general del Df:")
print(df.info())
# Identifica valores nulos en alguna columna
print("\nValores nulos en cada columna:")
print(df.isnull().sum())
