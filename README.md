# Definir los costos de gastos por día
costo_bus_por_dia = 0.70
costo_almuerzo_por_dia = 0.50
costo_copias_por_dia = 1.00

# Solicitar al usuario la cantidad de días en la universidad
dias_universidad = int(input("Ingrese la cantidad de días en la universidad: "))

# Calcular los gastos totales
gasto_bus_total = costo_bus_por_dia * dias_universidad
gasto_almuerzo_total = costo_almuerzo_por_dia * dias_universidad
gasto_copias_total = costo_copias_por_dia * dias_universidad

# Calcular el gasto total general
gasto_total_general = gasto_bus_total + gasto_almuerzo_total + gasto_copias_total

# Imprimir los resultados
print(f"Gasto en bus: ${gasto_bus_total:.2f}")
print(f"Gasto en almuerzo: ${gasto_almuerzo_total:.2f}")
print(f"Gasto en copias: ${gasto_copias_total:.2f}")
print(f"Gasto total: ${gasto_total_general:.2f}")
