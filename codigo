# Nombre de estudiante: Nasser Perez
# Grupo: 213022_46
# Programa: Ingenieria Electronica
# Codigo Fuente: Autoria Propia
# Nombre de programa: Fase 5 - matriz que registra las horas trabajadas por un equipo durante la semana
''' Descripcion: Una matriz registra las horas trabajadas por un equipo
durante la semana: [Nombre del Recurso, Lunes, Martes, ..., Viernes].
Necesitas calcular el total de horas semanales por persona y señalar si
alguien excedió las horas estándar '''

'''Requisitos de Desarrollo: 
Matriz: Crear una matriz con 4 recursos y horas trabajadas por día
(valores numéricos).

Módulos: Se requiere un módulo (función) para calcular la suma
total de horas semanales por recurso y clasificar su jornada.

Lógica de Negocio:

- Calcular la suma de horas para cada recurso.
- Clasificar la jornada como "Sobretiempo" si el total de horas
es mayor al umbral de 40 horas.
- Clasificar como "Horario Estándar" o inferior si no excede
el umbral.

- Salida: Imprimir el nombre de cada recurso, su total de horas
semanales y la clasificación de su jornada.'''
# Definir la matriz de horas trabajadas por recurso
horas_trabajadas = [
    ["Nasser", 8, 7, 8, 6, 9],
    ["Alejandra", 7, 8, 8, 12, 7],
    ["Bravo", 9, 6, 8, 7, 8],
    ["Robinson", 12, 9, 8, 9, 6]
]
# Definir el umbral de horas estándar
UMBRAL_HORAS = 40
# Función para calcular el total de horas semanales por recurso y clasificar su jornada
def calcular_horas_y_clasificar(matriz):
    resultados = []
    for recurso in matriz:
        nombre = recurso[0]
        horas_semanales = sum(recurso[1:])
        if horas_semanales > UMBRAL_HORAS:
            clasificacion = "Sobretiempo"
        else:
            clasificacion = "Horario Estándar"
        resultados.append((nombre, horas_semanales, clasificacion))
    return resultados
# Calcular y clasificar las horas trabajadas
resultados = calcular_horas_y_clasificar(horas_trabajadas)
# Imprimir los resultados
for nombre, horas, clasificacion in resultados:
    print(f"Recurso: {nombre}, Total de Horas Semanales: {horas}, Clasificación: {clasificacion}")
