# Codigo_simple
# Ejercicio 2 Asistencia de estudiantes

# Creamos la lista de los estudiantes
Estudiantes=["Eddie", "Henrey", "Elizabeth", "Lilia", "Caterine"]

# Creamos la lista que guarda solo a los estudiantes ausentes recorriendo la lista de estudiantes
# Pedimos al usuario el estado del estudiantes u¿y se verifica si es A (ausente)
Ausentes=[ e for e in Estudiantes if(Estado := input(f"¿ {e} está presente (P) o ausente (A)? ")) == "A" or Estado == "a"]

# Calculamos los presentes y restamos los ausentes del total
Presentes=len(Estudiantes) - len(Ausentes)

# Mostramos cuantos estuvieron presentes 
print(f"Numero de presentes: {Presentes}")

# Mostramos la lista de estudiantes ausentes 
print("Lista de ausentes: ", Ausentes)

