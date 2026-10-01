# Práctica 4 — Diagrama de contexto

**Equipo:**
**Sistema:**
**Integrantes:**

---

## Parte A — Entidades externas y flujos

Antes de dibujar, llenen esta tabla. Una fila por entidad externa. Tomen como punto de partida los participantes que identificaron en E1 y la especificación funcional del lunes.

| Entidad externa | Datos que le entrega al sistema | Datos que recibe del sistema |
|---|---|---|
| Cliente | Membresia | Pago de Membresia |
| Empleado | Pago | Comprobante de pago |
| Administrador  | Total de Ventas  | Recibo de Ventas |
|  |  |  |

**¿Qué quedó fuera del sistema y por qué?** Anoten al menos un elemento que consideraron como entidad externa y descartaron (porque en realidad es parte del sistema, o porque no intercambia datos con él), y expliquen la decisión en 2 o 3 líneas.

>Quedo fuera un sistema de rutinas que ayudaría a los clientes del GYM 

---

## Parte C — Declaración de propósito

En 2 o 3 líneas: ¿para qué existe el sistema, a quién sirve y qué beneficio produce? No describan pantallas ni tecnología.

> El sistema fue creado con el proposito de ayudar en la administración y el control de usuarios de Sorya´s GYM, asi evitando las infiltraciones de usuaios que no esten suscritos 

---

## Parte D — Contenido de los flujos

Una fila por cada flecha de su diagrama. En "Datos que contiene" listen los datos concretos que viajan en ese flujo.

| Flujo | Origen → Destino | Datos que contiene |
|---|---|---|
| Pago de Membresias | Sistema-Cliente | Duración de la membresia y costo |
| Comprobante de pago | Sistema-Empleado | Duración de la membresia y costo |
| Comprobante de pago | Sistema-Empleado | Sueldo |
| Recibo de Ventas | Sistema Administrador | Total de Ventas del dia |
|  |  |  |
|  |  |  |

---

## Declaración de uso de IA

Si no usaron IA, escriban «No usamos IA» en la primera fila.

| Herramienta | Para qué la usaron | Qué verificaron |
|---|---|---|
|  |  |  |
