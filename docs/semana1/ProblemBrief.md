# Problem Brief — Fidelización verificable para comercios minoristas de Medellín

---

## Decisión del problema

### Problema elegido

**Los comercios minoristas tienen dificultades para convertir compradores ocasionales en clientes recurrentes cuando sus beneficios de fidelización son difíciles de conocer, conservar y redimir.**
Propuesto por: **Leonardo Carmona** ([`LeonardoCarmona.md`](./LeonardoCarmona.md)).

### Por qué elegimos este

- Es un ámbito **verificable y presencial** en cualquier comercio minorista de Medellín: podemos observarlo y entrevistar a comercios y clientes reales.
- La fidelización es clave para la expansión y consolidación de cualquier comercio, en cualquier industria, y mejora las condiciones de consumo del cliente.
- Hay acceso directo a comercios gracias a la experiencia de Leonardo con Smartilink, una plataforma para pequeños negocios en funcionamiento.
- Frente a los criterios de la Sesión 1, el caso de **varios comercios aliados que deben reconocer un mismo beneficio** encaja con el criterio de "partes que no confían entre sí comparten un mismo registro sin delegar la confianza en un administrador único".

### Propuestas descartadas

| Propuesta | Quién la propuso | Motivo del descarte |
|---|---|---|
| [COMPLETAR] | Daniel Correa Salinas ([`DanielCorrea.md`](./DanielCorrea.md)) | [COMPLETAR] |
| [COMPLETAR] | Sergio ([`SergioApellido.md`](./SergioApellido.md)) | [COMPLETAR] |

### Cómo tomamos la decisión

- **Fecha:** 25 de septiembre de 2026.
- **Participantes:** Leonardo Carmona, Daniel Correa Salinas y Sergio.
- **Método:** [COMPLETAR: consenso tras debate / votación] Cada integrante presentó su propuesta y el equipo las comparó según los criterios de la Sesión 1 y la posibilidad de validar el problema con comercios reales.

---

## Problem Brief

### Encabezado

**Proyecto:** Fidelización verificable para comercios minoristas de Medellín

Los comercios minoristas tienen dificultades para convertir compradores ocasionales en clientes recurrentes cuando sus beneficios son difíciles de conocer, conservar y redimir entre canales o establecimientos.

### Equipo y roles

| Integrante | Usuario de GitHub | Rol asumido |
|---|---|---|
| Leonardo Carmona | [carmonacreativo](https://github.com/carmonacreativo) | Desarrollo de la app y diseño de interfaz (UX/UI) |
| Daniel Correa Salinas | [correasalinasd](https://github.com/correasalinasd) | Estrategia |
| Sergio [COMPLETAR apellido] | [COMPLETAR] | Desarrollo |

- **Responsable de las entregas:** [COMPLETAR]
- **Canal de coordinación interna:** [COMPLETAR: p. ej. grupo de WhatsApp]

---

### Problema y evidencia

**Enunciado:** los comercios minoristas tienen dificultades para convertir compradores ocasionales en clientes recurrentes cuando los beneficios de fidelización son poco visibles, difíciles de consultar o inconsistentes al cambiar de canal o establecimiento.

**Contexto y alcance.** El problema se plantea para tiendas pequeñas y medianas de Medellín que venden presencialmente o en línea y ofrecen sellos, descuentos, cupones o puntos. El consumidor puede no recordar el saldo, la fecha de vencimiento o las condiciones de uso; el personal puede tener que consultar registros separados antes de autorizar un beneficio.

**Frecuencia.** Cada compra elegible y cada intento de redención son ocasiones en que la fricción puede repetirse.

**Evidencia.**
- **Experiencia propia y observación directa:** Leonardo desarrolla Smartilink, una plataforma digital en funcionamiento para pequeños negocios colombianos, con un directorio público de comercios y una red de agentes comerciales que visitan negocios a diario. En ese contacto, la dificultad para que los clientes vuelvan y el bajo uso de tarjetas de sellos son quejas recurrentes. El sistema de puntos de la plataforma (SmartiCoins) fue diseñado precisamente por esa demanda.
- **Validación pendiente:** las fricciones descritas en este brief son hipótesis basadas en el flujo observado. Se validarán con entrevistas a 5 comercios y 5 clientes (ver *Supuestos y riesgos*).

---

### Usuario y actores

El **usuario principal** es el comprador que desea reconocer, consultar y utilizar una recompensa en una compra posterior sin guardar tarjetas físicas, instalar varias aplicaciones o repetir trámites. El otro usuario principal es el **comercio minorista**, que necesita reconocer compras elegibles, administrar condiciones comerciales y medir si un programa incrementa la recompra sin imponer costos de operación excesivos.

**Cómo lo resuelven hoy y qué les cuesta.** Tarjetas de sellos, cupones, descuentos generales, una hoja de cálculo o un proveedor de software de puntos. El cliente invierte tiempo en inscribirse, recordar códigos y consultar vigencias; el comercio financia el beneficio y dedica personal a registrar compras, verificar saldos y resolver reclamaciones.

**Demás actores:**

| Actor | Papel |
|---|---|
| Cajero | Registra la venta y verifica el canje |
| Mercadeo | Establece las reglas y comunica la promoción |
| Administración | Supervisa costos y conciliación |
| Proveedor del punto de venta o de fidelización | Conserva o transmite registros |
| Plataforma de comercio electrónico | Registra los pedidos si la tienda vende en línea |
| Comercios aliados | Aceptan condiciones de emisión y redención y acuerdan quién financia el beneficio |
| Autoridades de protección al consumidor y de datos personales | No operan cada transacción, pero sus obligaciones afectan la información de promociones y el tratamiento de datos |

Una credencial digital no elimina por sí misma estos actores ni sus responsabilidades.

---

### Flujo actual de valor

1. **Definición del incentivo.** Mercadeo define el incentivo, sus requisitos, límites, vigencia y canal de difusión; el comercio asume el costo previsto del beneficio. *Obligación normativa:* las condiciones comunicadas y el manejo de datos deben cumplir el Estatuto del Consumidor (Ley 1480 de 2011) y el régimen de protección de datos (Ley 1581 de 2012).
2. **Compra.** El cliente conoce la promoción, se inscribe si es necesario y compra en caja o en el sitio web. El dinero pasa del cliente al comercio mediante el medio de pago elegido. *Intermediario:* pasarela o entidad de pagos (el programa de lealtad no procesa necesariamente el pago).
3. **Registro.** El cajero o la plataforma remite los datos de la compra al proveedor del punto de venta y, si hay integración, al administrador del programa, donde se asocian cliente, compra y saldo acumulado. *Intermediarios:* proveedor POS y administrador del programa.
4. **Comunicación.** El programa comunica puntos, sellos o cupones mediante recibo, tarjeta, aplicación, correo o mensaje. El cliente conserva esa información para una compra posterior.
5. **Redención.** Al regresar, caja consulta el registro o inspecciona el cupón; el administrador valida condiciones y registra la redención. El comercio entrega el descuento o producto y absorbe su costo.
6. **Conciliación (si hay aliados).** Las partes concilian posteriormente la compensación.

```
Mercadeo → Cliente compra → Caja/POS → Administrador del programa → Cliente conserva → Caja valida canje → Conciliación entre aliados
            (pasarela de pago)
```

---

### Fricciones identificadas

| Paso | Fricción | Causa | A quién afecta |
|---|---|---|---|
| 1 | Condiciones poco visibles o cambiantes generan incertidumbre sobre vigencia, acumulación y exclusiones | Comunicación dispersa entre publicidad, recibos y reglas internas | Cliente (espera un beneficio no disponible) y personal (explica excepciones) |
| 2–3 | La venta no se asocia al identificador correcto o el programa no se actualiza tras una compra en otro canal | Ingreso manual de datos o integración incompleta entre caja, web y programa | Cliente (pierde visibilidad de su avance) y comercio (tiempo en correcciones) |
| 4 | Tarjeta extraviada, código vencido o aplicación que no se consulta: el incentivo no se usa | Beneficio guardado en soportes que el cliente olvida | Cliente, y el comercio pierde la recompra que buscaba |
| 5 | Caja tarda en validar el saldo o rechaza un canje legítimo; riesgo de canje duplicado | Registros inconsistentes | Cliente, cajero y presupuesto del programa |
| 6 | Sin una fuente aceptada por todos, la discusión pasa a una conciliación posterior | Cada aliado tiene su propio registro | Comercios aliados |

Estas fricciones son hipótesis basadas en el flujo descrito, no incidentes ya verificados. Las entrevistas y la observación medirán tiempo de canje, errores, consultas y abandono antes de priorizar inversiones tecnológicas.

---

### Oportunidad e hipótesis

**Oportunidad priorizada:** la **visibilidad y verificación del beneficio entre la compra y la redención** (fricciones de los pasos 4, 5 y 6), especialmente cuando dos sucursales o comercios aliados deben reconocerlo. Se elige porque es un punto observable para ambos usuarios: el cliente debería poder consultar su derecho y el cajero validarlo en segundos. También permite comparar registros de compra, emisión y canje sin atribuir automáticamente a la tecnología un aumento en ventas.

**Hipótesis:** emitir una **credencial de fidelización representada por un NFT** después de una compra elegible. La credencial indicaría un identificador y remitiría a las reglas del beneficio, y un registro de eventos permitiría verificar su emisión y redención.

**Qué cambiaría para el usuario:**
- **El cliente** consulta su beneficio en una interfaz sencilla, sin guardar tarjetas ni comprar criptomonedas, y puede recuperar el acceso si pierde el dispositivo.
- **El cajero** valida el beneficio en segundos, sin consultar registros separados.
- **Los comercios aliados** comparten una misma evidencia de qué se emitió y qué se redimió.

Los datos personales y los detalles de compra se guardarían fuera de la red pública, vinculados mediante identificadores controlados. El beneficio depende de las condiciones del comercio, no del valor de mercado de la credencial.

**Piloto:** un comercio, entrevistas a 5 comercios y 5 clientes, y 4 semanas de prueba; la ventana de recompra de 90 días requerirá seguimiento posterior.

---

### Criterio de pertinencia

La pertinencia de un registro distribuido depende de un caso con **varias entidades independientes**: por ejemplo, dos comercios aliados que emiten o redimen un beneficio compartido y necesitan verificar el mismo historial **sin aceptar que una sola parte pueda modificarlo unilateralmente**.

Esto responde al criterio de la Sesión 1 sobre **partes que no confían entre sí y comparten un registro sin delegar toda la confianza en un administrador único**. También toca el criterio de **histórico inalterable**: un historial verificable ayuda a acordar qué credencial se emitió, si se redimió y qué comercio debe financiarla. La evidencia del registro no reemplaza las reglas de negocio, el contrato entre aliados ni la verificación de que la venta ocurrió.

**Cuándo NO se justifica:** para un único comercio que controla sus tiendas, una base de datos con control de acceso, copias de seguridad y auditoría puede ser más simple y barata. Una integración entre sistemas existentes podría resolverlo incluso con aliados que confíen en un operador común.

Por eso, "usar NFT" no demuestra por sí solo que blockchain sea necesaria: el piloto debe comparar costos de emisión y consulta, recuperación, privacidad, prevención de doble canje y conciliación frente a las alternativas convencionales.

---

### Supuestos y riesgos

**Supuesto 1:** los clientes valoran la recompensa y logran consultar y canjear el beneficio sin una curva de aprendizaje significativa.
*Lo invalidaría:* baja participación, rechazo de la interfaz, pérdida de acceso sin recuperación o una tasa de redención inferior a la de la alternativa convencional.

**Supuesto 2:** el comercio, y en una fase posterior sus aliados, aceptan reglas comunes de emisión, vigencia, financiación y canje.
*Lo invalidaría:* desacuerdos contractuales, datos de ventas incompletos, incapacidad para integrar la caja o un nivel de fraude mayor que los beneficios del programa.

**Supuesto 3:** el costo completo de operación, soporte, recuperación, protección de datos y transacciones es sostenible frente a una base de datos.
*Lo invalidaría:* costos variables elevados, lentitud en caja, divulgación de patrones de compra o imposibilidad de corregir errores sin perjudicar al consumidor.

**Riesgo regulatorio:** antes de emitir credenciales se deben documentar los términos de la promoción, el tratamiento de datos, los responsables y un mecanismo de reclamación. El NFT es un comprobante de un beneficio sujeto a reglas, no dinero, inversión ni garantía de reventa.
