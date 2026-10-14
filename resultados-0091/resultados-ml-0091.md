# Reporte de Análisis de Datos - Pandas

`ian gutierrez Machine Learning pandas, NC 0091`

## 1. DataFrame Convertido
         Concierto  Asistentes  Duracion_horas
0  Rock en Español       15000             3.0
1            Banda        8000             2.5
2          Norteño       12000             3.0
3              Pop       20000             2.0
4      Electrónica       25000             4.0
5          Clásica        3000             2.0

## 2.1 Primeras Filas (head)
         Concierto  Asistentes  Duracion_horas
0  Rock en Español       15000             3.0
1            Banda        8000             2.5

## 2.2 Últimas Filas (tail)
     Concierto  Asistentes  Duracion_horas
4  Electrónica       25000             4.0
5      Clásica        3000             2.0

## 2.3 Dimensiones (Filas, Columnas)
(6, 3)

## 2.4 Tipos de Datos por Columna
Concierto             str
Asistentes          int64
Duracion_horas    float64
dtype: object

## 2.5 Información General (info)
<class 'pandas.DataFrame'>
RangeIndex: 6 entries, 0 to 5
Data columns (total 3 columns):
 #   Column          Non-Null Count  Dtype  
---  ------          --------------  -----  
 0   Concierto       6 non-null      str    
 1   Asistentes      6 non-null      int64  
 2   Duracion_horas  6 non-null      float64
dtypes: float64(1), int64(1), str(1)
memory usage: 276.0 bytes


## 3. Estadísticas Generales de la Columna 'Asistentes'
count        6.000000
mean     13833.333333
std       7985.403350
min       3000.000000
25%       9000.000000
50%      13500.000000
75%      18750.000000
max      25000.000000
Name: Asistentes, dtype: float64

## 4. Ordenar Ascendente por Asistentes
         Concierto  Asistentes  Duracion_horas
5          Clásica        3000             2.0
1            Banda        8000             2.5
2          Norteño       12000             3.0
0  Rock en Español       15000             3.0
3              Pop       20000             2.0
4      Electrónica       25000             4.0

## 5. Ordenar Descendente por Duracion_horas
         Concierto  Asistentes  Duracion_horas
4      Electrónica       25000             4.0
0  Rock en Español       15000             3.0
2          Norteño       12000             3.0
1            Banda        8000             2.5
3              Pop       20000             2.0
5          Clásica        3000             2.0

`ian gutierrez Machine Learning pandas, NC 0091`