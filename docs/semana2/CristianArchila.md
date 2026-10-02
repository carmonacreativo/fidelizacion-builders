# Historias de usuario individuales

**Nombre:** Cristian Archila Atehortua

**Usuario de GitHub:** [CAA99](https://github.com/CAA99)

---

## Mis historias de usuario

| # | Rol | Historia de usuario |
| :---: | :---: | --- |
| 1 | Cliente | Como **cliente** quiero consultar el beneficio que tengo disponible y hasta cuándo puedo usarlo, para decidir si vuelvo al comercio. |
| 2 | Cliente | Como **cliente** quiero recuperar el acceso a mi beneficio si cambio de teléfono, para no perder lo que ya acumulé. |
| 3 | Cliente | Como **cliente** quiero canjear mi beneficio en el momento de la compra, para recibir el descuento sin trámites adicionales. |
| 4 | Cajero | Como **cajero** quiero comprobar en segundos que un beneficio es válido y que no fue usado antes, para cerrar la venta sin hacer esperar al cliente. |
| 5 | Comercio | Como **comercio** quiero que el beneficio se emita al registrar una compra elegible, para no depender de un registro manual. |
| 6 | Administrador del programa | Como **administrador del programa** quiero definir las reglas del beneficio, para que se apliquen siempre igual. |
| 7 | Comercio aliado | Como **comercio aliado** quiero consultar un historial común de beneficios emitidos y usados, para conciliar qué financió cada parte. |

## La más importante y por qué

| Orden de importancia | Historia # | Por qué |
| :---: | :---: | --- |
| 1 (la más importante) | #1 | Ataca las dos fricciones que el Problem Brief prioriza: la del paso 4 (el incentivo no se usa porque el cliente no lo recuerda o no lo encuentra) y la del paso 1 (condiciones poco visibles). Es el punto observable de toda la hipótesis: si el cliente no puede ver qué tiene ni hasta cuándo, no vuelve. |
| 2 | #4 | Ataca la fricción del paso 5 (validación lenta o rechazo de un canje legítimo, con riesgo de canje duplicado). Es el momento en que el comercio entrega valor y asume el costo; si falla, el piloto se cae por la operación, no por la idea. |
| 3 | #5 | Sostiene las dos anteriores: sin emisión al registrar una compra elegible no existe ningún beneficio que consultar ni validar. Además resuelve la fricción 2–3 (la venta no se asocia al identificador correcto o no se refleja entre canales). |
| 4 | #3 | Cierra el ciclo de valor: convierte el beneficio en un descuento realmente aplicado. Depende de que la emisión y la validación ya funcionen, por eso va después. |
| 5 | #2 | Mitiga el Supuesto 1 del Problem Brief: la pérdida de acceso sin recuperación invalidaría la hipótesis. Va después del ciclo mínimo porque solo importa una vez que existe un beneficio que perder, pero sin ella la solución reproduce la fricción de la tarjeta extraviada que quiere eliminar. |
| 6 | #6 | Reduce la fricción del paso 1 desde el lado del comercio y evita canjes fuera de condiciones, que son costo directo del programa. Es una regla de operación, no el recorrido central del usuario. |
| 7 (la menos importante) | #7 | Habilita el escenario donde un registro compartido entre varias partes se justifica de verdad, pero el piloto definido en el Problem Brief es de un solo comercio: es el siguiente paso, no el MVP. |
