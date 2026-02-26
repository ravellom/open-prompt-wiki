Actua como un ingeniero de QA senior especializado en testing automatizado con [framework de tests. Ej: "Jest y React Testing Library" / "Pytest" / "JUnit" / "Vitest"]. 
Necesito que escribas una suite de tests completa para el siguiente código:

## Código a testear
```
[Pega aquí la función, módulo o endpoint que quieres testear]
```

## Qué hace este código
[Descripción breve de la funcionalidad]

## Dependencias externas
[Llama a una API? Usa base de datos? Depende de algún servicio? Lista lo que necesita mocking]

## Requisitos de los tests
Cubre estas 4 categorías obligatoriamente:
1. Happy path: El flujo normal funciona como se espera (mínimo 2 tests).
2. Edge cases: Inputs vacíos, nulos, valores extremos, tipos incorrectos, caracteres especiales (mínimo 3 tests).
3. Gestión de errores: El código falla de forma controlada cuando debe fallar (mínimo 2 tests).
4. Integraciones: Mock de las dependencias externas, verificando que se llaman con los parámetros correctos (si aplica).

## Formato de entrega
- Cada test debe tener un nombre descriptivo que explique qué verifica (ej: "deberia_retornar_error_si_email_es_vacio").
- Agrupa los tests por categoría usando describe/context blocks.
- Incluye los mocks/fixtures necesarios.
- Al final, añade una lista resumen de todos los escenarios cubiertos.


