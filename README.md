# TypeScript, su relación con NestJS y aplicaciones

¡Hola! Bienvenido a este contenido de TypeScript, su relación con NestJS y sus aplicaciones en el mismo. Esta guía está diseñado conla única intención de llevarte a un mayor entendimiento de como funciona NestJS y su acoplamiento cn TypeeScript siendo esta una herramienta poderosa.

**¿Qué aprenderás aquí?**  
- TypeScript avanzado puro (generics, utility types, conditional types, etc.)  
- Cómo aplicar todo esto en NestJS para APIs type-safe  
- Patrones avanzados que combinan tipos con arquitectura  

**Prerrequisitos:** Conocimientos básicos de TypeScript (interfaces, tipos básicos, funciones) y NestJS (módulos, servicios, controladores).

**Consejo:** No te preocupes si algo parece complicado al principio. Lee despacio, juega con los ejemplos en tu editor, y verás cómo todo encaja.

---

## 📋 Índice Interactivo

Haz clic en cualquier enlace para acceder a cada tema. **Cada sección está en su propio archivo**, organizado secuencialmente para un aprendizaje progresivo.

### 🎯 TypeScript Avanzado
Aprende los fundamentos avanzados de TypeScript que necesitarás para NestJS.

**Secuencia 1-9: Conceptos TypeScript**
- **[1️⃣ Generics: Código Reutilizable con Type Safety](./1.Generics[TypeScript].md)** — Bases de los generics, constraints, múltiples type parameters, repository pattern en NestJS
- **[2️⃣ Utility Types: Transformaciones Built-in](./2.Utility-Types[TypeScript].md)** — Partial, Pick, Omit, Record, Exclude, Extract, NonNullable, ReturnType, Parameters, Awaited
- **[3️⃣ Conditional Types: Tipos que Dependen de Condiciones](./3.Conditional-Types[TypeScript].md)** — Sintaxis ternaria de tipos, inferencia con infer, distribución, casos reales NestJS
- **[4️⃣ Mapped Types: Transformaciones de Tipos](./4.Mapped-Types[TypeScript].md)** — Iteración de propiedades, key remapping, filtrado de keys, recursividad
- **[5️⃣ Template Literal Types: Strings Type-Safe](./5.Template-Literal-Types[TypeScript].md)** — Strings con type safety, rutas type-safe, eventos, versionado API
- **[6️⃣ Decorators Deep Dive: Metadata y Reflexión](./6.Decorators[TypeScript].md)** — Decorators avanzados, reflect-metadata, reflexión en runtime
- **[7️⃣ Type Guards: Validación en Runtime](./7.Type-Guards[TypeScript].md)** — typeof, instanceof, custom guards, narrowing
- **[8️⃣ Discriminated Unions: Type Narrowing](./8.Discriminated-Unions[TypeScript].md)** — Pattern matching, type narrowing con discriminators
- **[9️⃣ Branded Types: Nominal Typing](./9.Branded-Types[TypeScript].md)** — Tipos nominales en TypeScript, Value Objects, domain types

### 🏗️ Type Safety en NestJS
Aplica los conceptos avanzados directamente en tu framework favorito.

**Secuencia 10-14: Aplicación en NestJS** 🚧 _En proceso de corrección y publicación_
- **🔟 Typed Request/Response: Inferencia Automática** — Type-safe requests, responses, validación automática
- **1️⃣1️⃣ Typed Dependency Injection: Adiós 'any'** — DI type-safe, servicios genéricos
- **1️⃣2️⃣ Typed Configuration: ConfigService Seguro** — ConfigService<T>, type-safe env vars
- **1️⃣3️⃣ Typed Events: EventEmitter con Payloads** — EventEmitter genérico, typed payloads
- **1️⃣4️⃣ Typed Database Queries: ORMs Type-Safe** — TypeORM type-safe, repositories genéricos

### 🎨 Advanced Patterns
Patrones de diseño potenciados con tipos avanzados.

**Secuencia 15-19: Patrones Arquitectónicos** 🚧 _En proceso de corrección y publicación_
- **1️⃣5️⃣ Builder Pattern: Interfaces Fluent Type-Safe** — Builder genérico, fluent interfaces
- **1️⃣6️⃣ Factory Pattern: Factories con Genéricos** — Factory pattern type-safe
- **1️⃣7️⃣ Strategy Pattern: Estrategias Intercambiables** — Strategy pattern con DI
- **1️⃣8️⃣ Decorator Pattern: Composition vs Inheritance** — Decorators vs composition
- **1️⃣9️⃣ Observer Pattern: Events y Reactive Programming** — Event-driven architecture, reactive patterns

---

**📚 Estructura de Archivos:**
```
✅ Disponibles:
1.Generics[TypeScript].md                    ← Empieza aquí
2.Utility-Types[TypeScript].md
3.Conditional-Types[TypeScript].md
4.Mapped-Types[typeScript].md
5.Template-Literal-Types[typeScript].md
6.Decorators[TypeScript].md
7.Type-Guards[TypeScript].md
8.Discriminated-Unions[TypeScript].md
9.Branded-Types[TypeScript].md

🚧 En proceso de corrección y publicación:
10.Typed-Request-Response[NestJS].md
11.Typed-Dependency-Injection[NestJS].md
12.Typed-Configuration[NestJS].md
13.Typed-Events[NestJS].md
14.Typed-Database-Queries[NestJS].md
15.Builder-Pattern[Advanced].md
16.Factory-Pattern[Advanced].md
17.Strategy-Pattern[Advanced].md
18.Decorator-Pattern[Advanced].md
19.Observer-Pattern[Advanced].md
```

💡 **Tip:** Comienza con el archivo 1️⃣ y sigue la secuencia. Cada archivo construye sobre los anteriores y toma ~15-30 minutos aprender cada concepto.

---