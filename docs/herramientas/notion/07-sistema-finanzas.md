# Módulo 07: Sistema de Finanzas

## 🎯 Objetivos del módulo

Al terminar este módulo vas a:

- ✅ Crear una base de datos de ingresos
- ✅ Registrar tus gastos operativos
- ✅ Calcular tu ganancia neta
- ✅ Hacer seguimiento de facturas pendientes
- ✅ Entender tu rentabilidad por cliente

---

## 💰 Por qué necesitas un sistema financiero

Como CM freelancer, necesitás saber:

- ¿Cuánto estás ganando?
- ¿Cuánto gastás en herramientas y subscriptions?
- ¿Qué cliente es más rentable?
- ¿Cuánto tenés que cobrar para cubrir tus gastos?

```
Sin control financiero:
❌ No sabés si ganás bien o mal
❌ Gastás sin control en herramientas
❌ Te olvidás de cobrar
❌ No sabés qué cliente te conviene más

Con control financiero:
✅ Sabés exactamente cuánto ganás por mes
✅ Identificás gastos innecesarios
✅ Nunca se te escapa una factura
✅ Tomás decisiones basadas en datos
```

---

## 📊 Crear tu base de ingresos

### Paso 1: Crear la página

1. Creá una página llamada **"💰 Finanzas 2026"**
2. Dentro, creá una sección **"INGRESOS"**
3. Creá una base de datos tipo **"Tabla"**

### Paso 2: Propiedades de ingresos

| Propiedad     | Tipo     | Descripción                        |
| ------------- | -------- | ---------------------------------- |
| Cliente       | Relación | Links a tu base de clientes        |
| Mes           | Select   | Mes del ingreso                    |
| Monto         | Número   | Cuánto cobraste                    |
| Fecha de pago | Fecha    | Cuándo lo cobraste                 |
| Estado        | Select   | Facturado / Cobrado / Pendiente    |
| Concepto      | Texto    | Descripción del servicio           |
| Forma de pago | Select   | Transferencia / MercadoPago / Otro |
| Notas         | Texto    | Cualquier observación              |

### Paso 3: Registrar tus ingresos

```
EJEMPLO DE REGISTRO DE INGRESO:
══════════════════════════════

Cliente: Joyería Lumina
Mes: Mayo 2026
Monto: $300 USD
Fecha de pago: 05/05/2026
Estado: ✅ Cobrado
Concepto: Gestión completa de redes - Mayo
Forma de pago: Transferencia bancaria
Notas: Pago confirmado por email
```

---

## 💸 Crear tu base de gastos

### En la misma página, agregá sección de GASTOS

### Propiedades de gastos:

| Propiedad    | Tipo   | Descripción                                              |
| ------------ | ------ | -------------------------------------------------------- |
| Descripción  | Título | Qué compraste                                            |
| Categoría    | Select | Herramientas / Software / Marketing / Transporte / Otros |
| Monto        | Número | Cuánto gastaste                                          |
| Moneda       | Select | USD / ARS                                                |
| Fecha        | Fecha  | Cuándo lo pagaste                                        |
| Frecuencia   | Select | Único / Mensual / Anual                                  |
| Mes afectado | Select | Mes al que corresponde el gasto                          |
| Comprobante  | Texto  | Link o referencia al comprobante                         |

### Categorías sugeridas:

```
CATEGORÍAS DE GASTOS
════════════════════

📱 SOFTWARE Y HERRAMIENTAS
→ Canva Pro: $12.99 USD/mes
→ Later: $18 USD/mes
→ ChatGPT Plus: $20 USD/mes (si usás)
→ Dominio/Hosting: $[X] (si tenés web)

🎨 MARKETING Y NEGOCIO
→ Ads para tu marca personal: $[X]
→ Templates/recursos: $[X]
→ Cursos: $[X]

🚗 OPERATIVOS
→ Transporte a reuniones: $[X]
→ Celular/internet: $[X] (proporción laboral)

📋 ADMINISTRATIVOS
→ Comisión plataforma freelance: 10-20%
→ Plataforma de cobro (Stripe, PayPal): 2.9% + 30¢
```

---

## 📈 Dashboard financiero básico

### Crear una página resumen:

```
💰 RESUMEN FINANCIERO - [MES/AÑO]
══════════════════════════════════

📊 ESTADO DE RESULTADOS
────────────────────────
INGRESOS BRUTOS:              $[X]
(-) GASTOS OPERATIVOS:       $[X]
(= GANANCIA NETA:            $[X]

📈 DESGLOSE DE INGRESOS
─────────────────────────
Clientes activos: [X]
Ingreso promedio por cliente: $[X]

Por cliente:
• Joyería Lumina: $[X] (X%)
• Accesorios María: $[X] (X%)

📉 DESGLOSE DE GASTOS
──────────────────────
Software/Herramientas: $[X]
Marketing: $[X]
Operativos: $[X]
Total: $[X]

💵 FLUJO DE CAJA
────────────────
Saldo anterior: $[X]
+ Ingresos del mes: $[X]
- Gastos del mes: $[X]
= Saldo actual: $[X]

⚠️ FACTURAS PENDIENTES
────────────────────────
• [Cliente]: $[X] — Vence: [Fecha]
• [Cliente]: $[X] — Vence: [Fecha]
```

---

## 📋 Seguimiento de facturas

### Base de facturas pendientes:

| Propiedad            | Tipo                                            |
| -------------------- | ----------------------------------------------- |
| Cliente              | Relación                                        |
| Monto                | Número                                          |
| Fecha de vencimiento | Fecha                                           |
| Estado               | Select: Pendiente / Enviada / Cobrada / Vencida |
| Recordatorio         | Select: 7 días antes / 3 días antes / El día    |

### Flujo de facturación:

```
1. [Fecha acordada] → Se genera la factura
   Estado: Pendiente

2. [Fecha acordada] → Se envía la factura al cliente
   Estado: Enviada

3. [Dentro de los 5-10 días] → Cliente paga
   Estado: Cobrada

4. [Si pasa la fecha] → Estado: Vencida
   → Tomar acción: WhatsApp, email, llamada
```

---

## 💹 Cálculo de rentabilidad por cliente

### Por qué importa:

```
CLIENTE A:
→ Cobra: $300 USD/mes
→ Trabaja: 20 horas/mes
→ Ganancia/hora: $15 USD/hora
→ Gastos que genera: $5 USD (proporción)
→ Ganancia real/hora: $14.75 USD/hora

CLIENTE B:
→ Cobra: $200 USD/mes
→ Trabaja: 5 horas/mes
→ Ganancia/hora: $40 USD/hora
→ Gastos que genera: $2 USD (proporción)
→ Ganancia real/hora: $39.60 USD/hora
```

**El Cliente B es más rentable** aunque cobre menos.

### Cómo calcular en Notion:

Podés crear una vista o página dedicada:

```
RENTABILIDAD POR CLIENTE
════════════════════════

Cliente: [Nombre]
─────────────────────
Ingreso mensual: $[X]

Horas promedio dedicadas/mes: [X]
Valor por hora: $[X]/hora

Gastos atribuibles: $[X]
→ Herramientas (proporción): $[X]
→ Comunicación: $[X]
→ Transporte (si aplica): $[X]

GANANCIA NETA: $[X]
GANANCIA POR HORA: $[X]/hora

Comparativa:
→ Cliente vs. Promedio del mes: [+/-X%]
→ Cliente vs. Mejor cliente: [-X%]
```

---

## 📅 Cash flow mensual

### Seguimiento mes a mes:

```
CASH FLOW 2026
══════════════

        ENE    FEB    MAR    ABR    MAY    JUN    JUL    AGO    SEP    OCT    NOV    DIC
Ingresos  $[X]  $[X]  $[X]  $[X]  $[X]  $[X]  $[X]  $[X]  $[X]  $[X]  $[X]  $[X]
Gastos   $[X]  $[X]  $[X]  $[X]  $[X]  $[X]  $[X]  $[X]  $[X]  $[X]  $[X]  $[X]
Net      $[X]  $[X]  $[X]  $[X]  $[X]  $[X]  $[X]  $[X]  $[X]  $[X]  $[X]  $[X]
```

### Para qué sirve:

- Ver si tus ingresos son estables o variables
- Planificar meses de baja (vacaciones, enero)
- Identificar tendencias

---

## 💳 Presupuesto para herramientas

### Herramientas esenciales:

| Herramienta         | Costo mensual | Necesidad       |
| ------------------- | ------------- | --------------- |
| Canva Pro           | $12.99 USD    | ✅ Esencial     |
| Later               | $18 USD       | ⚠️ Nice to have |
| ChatGPT Plus        | $20 USD       | ⚠️ Opcional     |
| Notion              | Gratis        | ✅ Ya lo usás   |
| Meta Business Suite | Gratis        | ✅ Ya lo usás   |
| CapCut              | Gratis        | ✅ Ya lo usás   |

**Total mínimo:** $12.99 USD/mes (~$15 USD con variaciones)

### Gastos variables:

| Gasto              | Estimación mensual |
| ------------------ | ------------------ |
| Cursos/aprendizaje | $0-30 USD          |
| Templates/recursos | $0-10 USD          |
| Ads para tu marca  | $0-20 USD          |

---

## 📊 Metas financieras

### Definí tus metas:

```
METAS FINANCIERAS 2026
═════════════════════

INGRESOS:
→ Meta mensual: $[X] USD
→ Mejor mes histórico: $[X] USD
→ Año pasado (mismo período): $[X] USD

GANANCIAS:
→ Meta de ganancia neta: $[X] USD/mes
→ Mínimo aceptable: $[X] USD/mes

INVERSIONES:
→ Ahorro para PC: $[X] USD
→ Ahorro para curso (pago): $[X] USD
→ Fondo de emergencia: 3 meses de gastos
```

---

## ✅ Checklist de finanzas

```
□ Base de ingresos creada
□ Base de gastos creada
□ Al menos 1 mes de registros completado
□ Dashboard resumen creado
□ Base de facturas pendientes creada
□ Rentabilidad por cliente calculada
□ Cash flow mensual registrado
□ Metas financieras definidas
```

---

## 💡 Tips financieros para CM

### Cobranza:

- **Cobrá por adelantado** cuando puedas (50% al inicio, 50% al terminar)
- **Enviá facturas el mismo día** que termina el mes de servicio
- **Seguimiento a los 3 días** si no te pagaron
- **No trabajés gratis** esperando que "después te pagan"

### Gastos:

- **Rastreá cada gasto**, aunque sea pequeño
- **Cancelá suscripciones** que no usás
- **Aprovechá los planes anuales** si te conviene (Canva Pro anual es más barato)
- **Separá gastos personales y de trabajo** desde el banco

### Pricing:

- **Cobrá al menos** $15 USD/hora como CM principiante
- **Subí precios** cuando consigas resultados
- **Cobrá extra** por trabajos fuera del scope

---

## 🎯 Resumen

En este módulo aprendiste:

- Crear bases de ingresos y gastos
- Hacer seguimiento de facturas
- Calcular rentabilidad por cliente
- Crear dashboard financiero
- Definir metas financieras

**Próximo módulo:** Templates específicos para joyería y lujo.

---

_cm-belen — Guía Notion para CM — Módulo 07_
