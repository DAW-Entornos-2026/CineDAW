# CinesDAW
Software en PSeInt para el TPV de CinesDAW. Gestiona en tiempo real la venta de entradas, control de aforo, tienda de snacks, cobro con desglose de IVA/cambio y cierre de caja diario. Desarrollado con metodología Scrumban en GitHub Projects.

**Código base**

```
Algoritmo CinesDAW_Master
	
	// =========================================================================
	// DECLARACIÓN E INICIALIZACIÓN DE VARIABLES GLOBALES
	// =========================================================================
	Definir aforoMaximo, aforoActual, entradasVendidas, stockPalomitas, clientesAtendidos Como Entero
	Definir totalRecaudadoEntradas, totalRecaudadoSnacks Como Real
	Definir opcionMenu Como Entero
	
	// Valores iniciales según plantilla maestra
	aforoMaximo <- 50
	aforoActual <- 0
	entradasVendidas <- 0
	totalRecaudadoEntradas <- 0.0
	totalRecaudadoSnacks <- 0.0
	stockPalomitas <- 20
	clientesAtendidos <- 0
	
	// =========================================================================
	// BUCLE PRINCIPAL DE NAVEGACIÓN Y MENÚ
	// =========================================================================
	Repetir
		Escribir ""
		Escribir "=================================================="
		Escribir "     SISTEMA DE GESTIÓN CENTRALIZADA CinesDAW     "
		Escribir "=================================================="
		Escribir "1. Venta de Entradas y Tarifas Especiales"
		Escribir "2. Control de Aforo y Gestión de Sala"
		Escribir "3. Venta de Snacks y Control de Stock"
		Escribir "4. Pasarela de Pago, IVA y Desglose de Cambio"
		Escribir "5. Cierre de Caja y Mantenimiento"
		Escribir "0. Salir del programa"
		Escribir "--------------------------------------------------"
		Escribir "Seleccione una opción (0-5):"
		Leer opcionMenu
		Escribir ""
		
		Segun opcionMenu Hacer
			1:
				// TODO: [Issue #2] Implementado por Developer 1
				Escribir "[PENDIENTE] Caso 1 no integrado. Esperando revisión en Code Review."
				
			2:
				// TODO: [Issue #3] Implementado por Developer 2
				Escribir "[PENDIENTE] Caso 2 no integrado. Esperando revisión en Code Review."
				
			3:
				// TODO: [Issue #4] Implementado por Developer 3
				Escribir "[PENDIENTE] Caso 3 no integrado. Esperando revisión en Code Review."
				
			4:
				// TODO: [Issue #5] Implementado por Developer 4
				Escribir "[PENDIENTE] Caso 4 no integrado. Esperando revisión en Code Review."
				
			5:
				// TODO: [Issue #6] Implementado por Developer 5
				Escribir "[PENDIENTE] Caso 5 no integrado. Esperando revisión en Code Review."
				
			0:
				Escribir "Cerrando el sistema CinesDAW... ¡Hasta pronto!"			
			De Otro Modo:
				Escribir "[ERROR] Opción no válida. Introduzca un número entre 0 y 5."
		FinSegun
		
	Hasta Que opcionMenu = 0

FinAlgoritmo
```
