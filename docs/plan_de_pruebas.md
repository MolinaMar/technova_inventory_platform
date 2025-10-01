# Plan de Pruebas
- Unitarias: pytest en funciones del backend
- Integración: validar comunicación entre módulos
- Funcionales: flujos completos
- Regresión: al final de cada sprint
- Aceptación: al cierre de cada entrega

## Prueba Manual
- Nombre: Validación de login
- Objetivo: Comprobar acceso con credenciales válidas e inválidas
- Entradas: usuario="admin", password="1234"
- Resultado esperado: acceso permitido si credenciales son correctas
- Herramienta: Validación visual
- Ubicación: /tests/manual
