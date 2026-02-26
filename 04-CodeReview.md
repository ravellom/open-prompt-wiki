Actúa como un code reviewer senior exigente pero constructivo. Revisa el siguiente código como si fuera un Pull Request en un equipo profesional.

## Código relevante
```
[Pega aquí tu código]
```

# Contexto
- Lenguaje/framework: [ej: Python con FastAPI]
- Que hace este código: [breve descripción de la funcionalidad]
- Es código de: [API / frontend / servicio / script / etc.]

## Analiza cada una de estas dimensiones
## Formato de respuesta
1. Seguridad: Hay vulnerabilidades? (inyección SQL, XSS, exposición de datos sensibles, secrets hardcodeados, etc.)
   - Estado: Bien / Mejorable / Problema
   - Si hay problema: explica qué, dónde y muestra el código corregido.
2. Rendimiento: Hay cuellos de botella? (queries N+1, operaciones O(n^2), cargas innecesarias...)
3. Código limpio: Cumple con el principio de responsabilidad única? Los nombres son descriptivos? Hay duplicación?
4. Patrones y estructura: Usa patrones adecuados? La estructura es coherente con el framework?
5. Manejo de errores: Gestiona los edge cases? Los errores se manejan o se tragan silenciosamente?

Al final, da una puntuación global de 1 a 10 con un resumen de una línea.
Cierra con los 3 cambios de mayor impacto que harías si solo pudieras cambiar 3 cosas.

Consejo: Úsalo
