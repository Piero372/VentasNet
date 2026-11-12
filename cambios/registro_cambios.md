# Registro de cambios

## 1. Solicitudes Registradas
- **INC-001**: Error en el cálculo del total por cantidad. Criterio: Precio 50 x cantidad 3 = S/ 150 (Estado: En proceso).
- **CR-002**: Aplicar descuento de 10% desde S/ 200. Criterio: Subtotal 200 -> S/ 180; subtotal 150 -> S/ 150 (Estado: En proceso).

## 2. Matriz de Impacto
- **INC-001**: Requisito RF-001 | Archivo: src/ventas.py | Riesgo: Total incorrecto | Prueba: 50x3=150 | Decisión: Aprobada
- **CR-002**: Requisito RF-002 | Archivo: src/ventas.py, docs/requisitos.md | Riesgo: Umbral incorrecto | Prueba: Subtotales 150, 200 y 300 | Decisión: Aprobada
