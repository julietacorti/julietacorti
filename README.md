- 👋 Hi, I’m @julietacorti
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
julietacorti/julietacorti is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
cantEmpleados = int(input("Ingrese la cantidad de empleados"))
if cantEmpleados<1:
	int("Valores incorrectos.")
	cantEmpleados = int(input("Ingrese la cantidad de empleados"))

for range in ciclo (1, cantEmpleados):
	nombre = int(input("Ingrese el nombre del empleado."))
	horario = int(input("Ingrese el horario actual."))
	if horario <0 or horario>24:
		int("Valores incorrectos, pruebe nuevamente.")
		ciclo = ciclo + 1
