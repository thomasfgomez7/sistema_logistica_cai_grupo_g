## Convenciones de código

Seguimos estándares inspirados en las guías de .NET.

### Naming Convention

#### PascalCase
- Clases
- Métodos
- Constantes
- Propiedades
- Eventos
- Interfaces (con prefijo 'I')

#### camelCase
- Variables locales
- Parámetros


### Mantengamos el código limpio
- Métodos cortos (máx. ~20-30 líneas)
- Una sola responsabilidad por método (SRP)
- Evitar código duplicado (DRY)
- Nombres descriptivos (NO usar var1, data, etc.)
- Evitar comentarios innecesarios

### Git - Buenas prácticas

#### Commits

Usar mensajes claros:

- feat: agregar cálculo de costo de envío
- fix: corregir error en validación de pedidos
- refactor: mejorar estructura del servicio de clientes

Evitar commits no descriptivos como:
- cambios
- fix
- update

