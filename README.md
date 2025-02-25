Cotizador de Seguros
Descripción del Programa
Este programa permite calcular el costo de una póliza de seguro basada en diferentes factores personales y financieros del asegurado. Se ejecuta en un bucle hasta que el usuario decide salir escribiendo "SALIR". Cada cotización se calcula sumando recargos sobre un precio base, dependiendo de la edad del asegurado, su estado civil, cantidad de hijos, número de propiedades y nivel de ingresos.
Funcionamiento del Programa
	1	Entrada de Datos:
	◦	Nombre del asegurado.
	◦	Edad del asegurado.
	◦	Estado civil y, si está casado, la edad de su cónyuge.
	◦	Cantidad de hijos.
	◦	Número de propiedades.
	◦	Salario mensual.
	2	Cálculo de Recargos:
	◦	Edad del asegurado: Se aplica un recargo de acuerdo con su grupo de edad.
	◦	Edad del cónyuge: Si está casado, se calcula un recargo similar basado en su edad.
	◦	Cantidad de hijos: Se agrega un recargo adicional por cada hijo.
	◦	Número de propiedades: Se aplica un recargo del 35% sobre el precio base por cada propiedad.
	◦	Salario mensual: Se agrega un recargo del 5% sobre el salario del asegurado.
	3	Cálculo del Precio Final:
	◦	Se suma el precio base más todos los recargos calculados.
	◦	Se muestra el recargo total y el precio final de la cotización.
	4	Repetición del Proceso:
	◦	Se solicita una nueva cotización hasta que el usuario ingrese "SALIR".
Consideraciones Claves del Problema
	•	Validación de entradas: Se debe asegurar que las entradas sean valores numéricos cuando corresponda.
	•	Estructura del bucle: Debe permitir múltiples cotizaciones sin reiniciar el programa.
	•	Cálculo correcto de recargos: Cada factor debe sumarse adecuadamente para obtener el precio final.
	•	Formato de salida: Se deben mostrar los valores con dos decimales para mejor presentación.
Posibles Mejoras
	1	Interfaz Gráfica (GUI): Implementar una interfaz visual para facilitar la interacción con el usuario.
	2	Mejor validación de datos: Manejar posibles errores en la entrada de datos (por ejemplo, evitar letras en campos numéricos).
	3	Historial de cotizaciones: Permitir almacenar y visualizar las cotizaciones anteriores.
	4	Descuentos o promociones: Agregar lógica para descuentos especiales a ciertos perfiles de asegurados.
	5	Exportación de cotizaciones: Posibilidad de guardar las cotizaciones en un archivo o enviarlas por correo.
# Tarea-Extra-semana-3
