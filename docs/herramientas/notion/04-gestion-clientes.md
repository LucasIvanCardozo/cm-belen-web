# Módulo 04: Gestión de Clientes

## 🎯 Objetivos del módulo

Al terminar este módulo vas a:

- ✅ Crear una base de datos de clientes
- ✅ Mantener toda la información de cada cliente organizada
- ✅ Hacer seguimiento del estado de cada cliente
- ✅ Organizar proyectos por cliente
- ✅ Gestionar contratos y pagos

---

## 🗄️ Base de datos de clientes

La **base de datos** es donde guardás toda la información de tus clientes en un solo lugar. Notion usa bases de datos que funcionan como tablas con filtros y vistas.

### Por qué necesitás una base de datos:

```
Sin base de datos:
❌ Buscás información en WhatsApp
❌ No sabés quién te debe dinero
❌ Perdés track de qué publicaste para quién
❌ Te olvidás de fechas importantes

Con base de datos:
✅ Todo en un solo lugar
✅ Filtrás por cliente, estado, fecha
✅ Vés de un vistazo quién es quién
✅ Organizás automáticamente
```

---

## 📊 Crear tu base de datos de clientes

### Paso 1: Crear la página

1. En tu workspace, creá una página llamada **"👥 Mis Clientes"**
2. Dentro, creá un bloque de tipo **"Tabla"** o **"Base"**
   - Escribí "/" y buscá **"Table"** o **"Tabla"**
   - Seleccioná **"Table - Full page"** para que sea en página completa

### Paso 2: Configurar las propiedades

Las **propiedades** son las columnas de tu tabla. Agregá estas:

| Propiedad        | Tipo          | Para qué                                                |
| ---------------- | ------------- | ------------------------------------------------------- |
| Nombre           | Título        | Nombre del cliente                                      |
| Estado           | Select        | Activo / Pausado / Prospects / Finalizado               |
| Tipo de servicio | Multi-select  | Gestión completa / Solo diseño / Solo ads / Consultoría |
| Instagram        | Texto         | @ del Instagram                                         |
| Precio mensual   | Moneda/número | Cuánto cobrás                                           |
| Fecha de inicio  | Fecha         | Cuándo arrancaste                                       |
| Próxima factura  | Fecha         | Cuándo cobrás                                           |
| Método de pago   | Select        | Transferencia / MP / Otro                               |
| Prioridad        | Select        | Alta / Media / Baja                                     |

### Paso 3: Agregar tus clientes

1. Tocá **"Nueva"** o el botón "+"
2. Se crea una fila nueva
3. Completá la información básica
4. Tocá en el nombre para abrir la **página del cliente**

### Paso 4: Crear la página del cliente

Cada fila de la tabla es una página. Abrila y vas a ver que está vacía. Ahí es donde ponés toda la información de ese cliente específico.

**Agregá esta estructura:**

```
JOYERÍA LUMINA
==============

📋 RESUMEN
───────────
Estado: ✅ Activo
Servicios: Gestión completa
Precio: $300 USD/mes
Desde: [Fecha]

💰 INFORMACIÓN DE PAGO
──────────────────────
Último pago: [Fecha]
Próximo vencimiento: [Fecha]
Método: Transferencia bancaria
CBU/CVU: [Los datos]
Alias: [Alias]

📱 REDES SOCIALES
──────────────────
Instagram: [@joyerialumina]
Facebook: [Link]
Web: [URL]
Otra: [Si tiene]

👤 CONTACTOS
─────────────
Contacto principal: María González
WhatsApp: [+XX XXXX XXXX]
Email: [email]
Rol: Dueña

📁 PROYECTOS RELACIONADOS
──────────────────────────
- Calendario Editorial Mayo 2026
- Campaña San Valentín
- Reportes Mensuales
```

---

## 📈 Dashboard de clientes

Además de la tabla, podés crear un **Dashboard** que te muestre información de un vistazo.

### Cómo crear el Dashboard:

1. Creá una página nueva llamada **"📊 Dashboard Clientes"**
2. Agregá un bloque **"Table"** que apunte a tu base de clientes
3. Agregá **vistas filtradas** para diferentes perspectivas

### Vistas útiles:

#### Vista: Solo activos

```
Filtro: Estado = Activo
Orden: Próxima factura ascendente
```

#### Vista: Facturación del mes

```
Filtro: Mes de próxima factura = Este mes
Mostrar: Nombre, Precio, Fecha de pago
```

#### Vista: Prospects

```
Filtro: Estado = Prospect
Orden: Fecha de contacto descendente
```

### Crear vistas adicionales:

1. En la tabla, tocá **"+"** junto a "Filtros"
2. Seleccioná **"Vista nueva"**
3. Ponele nombre (ej: "Activos", "Prospects")
4. Configurá los filtros

---

## 📁 Proyectos por cliente

Cada cliente va a tener varios **proyectos** o páginas relacionadas:

```
Joyería Lumina
├── 📄 Info General
├── 📅 Calendario Mayo 2026
├── 📅 Calendario Junio 2026
├── 📊 Reporte Abril 2026
├── 📊 Reporte Marzo 2026
├── 🎨 Assets de marca
├── 📝 Reuniones
│   ├── 2026-05-20 Reunión semanal
│   └── 2026-05-13 Reunión semanal
└── 📋 Tareas pendientes
```

### Crear esta estructura automáticamente:

Podés crear **templates** que se generen solos. Pero por ahora, hacelo manualmente:

1. Entrá a la página del cliente
2. Creá las subpáginas que necesites
3. Usá tu **Plantilla: Nueva Cuenta Cliente** del módulo anterior

---

## 📅 Seguimiento de facturación

### Crear una página de facturación:

1. Creá una página **"💰 Facturación 2026"**
2. Dentro, creá una base de datos tipo **"Tabla"**

### Propiedades de la base:

| Propiedad      | Tipo                                    |
| -------------- | --------------------------------------- |
| Cliente        | Relación (apunta a tu base de clientes) |
| Mes            | Select                                  |
| Monto          | Número                                  |
| Estado de pago | Select: Pendiente / Pagado / Vencido    |
| Fecha de pago  | Fecha                                   |
| Notas          | Texto                                   |

### Vista de facturación:

```
Vista: Facturas pendientes
Filtro: Estado de pago ≠ Pagado
Orden: Fecha de pago ascendente
```

---

## 📋 Plantilla de onboarding de cliente

Cuando agarrás un cliente nuevo, seguí este checklist:

### Checklist de onboarding:

```
□ Reunión de descubrimiento
□ Recopilar brand kit (logo, colores, fuentes)
□ Obtener acceso a redes sociales
□ Firmar contrato (o acordar términos)
□ Definir calendario de trabajo
□ Primer pago recibido
□ Crear página del cliente en Notion
□ Configurar herramientas (Meta Business Suite, Later, etc.)
□ Briefing de marca completado
□ Primera planificación de contenido creada
□ Kick-off con el cliente (reunión de arranque)
```

### Agregalo a cada página de cliente:

Copiá este checklist al final de cada página de cliente y marcalo conforme avanzás.

---

## 🎯 Sistema de alertas y recordatorios

### Usar fechas como alertas:

1. Agregá la propiedad **"Fecha"** a cualquier base
2. Notion puede mostrarte los elementos que vencen pronto
3. Usá la vista **"Calendario"** para ver todo en forma visual

### Vista calendario:

1. En tu base de clientes, creá una nueva vista
2. Seleccioná **"Calendar"** o **"Calendario"**
3. Configurá qué propiedad de fecha usar
4. Vas a ver los clientes/proyectos en un calendario

---

## 📊 Reporte mensual rápido

### Crear un mini-reporte:

En la página del cliente, mantené un resumen actualizado:

```
📊 ESTE MES
───────────
Posts publicados: 12
Reels: 4
Stories: 60+
Alcance total: 45,000
Engagement: 4.2%

📅 PRÓXIMAMENTE
────────────────
- [Tarea 1] — Fecha: [Fecha]
- [Tarea 2] — Fecha: [Fecha]

💬 ÚLTIMO CONTACTO
──────────────────
Fecha: [DD/MM]
Resumen: [Qué se habló]
```

---

## ✅ Checklist de gestión de clientes

```
□ Base de datos de clientes creada
□ Al menos 1 cliente agregado con info completa
□ Propiedades configuradas (estado, precio, fecha)
□ Vista de "Activos" creada
□ Vista de "Facturación" creada
□ Página individual de cliente creada
□ Sistema de facturación básico implementado
□ Checklist de onboarding en cada cliente
```

---

## 💡 Tips para gestión de clientes

### Organización:

- Usá el **nombre de la marca** como título principal
- Agregá el **emoji de la marca** o el **logo** si podés
- Usá **colores** en los estados (rojo = urgente, verde = bien)

### Comunicación:

- Guardá los **contactos importantes** como propiedades
- Mantené un **historial de reuniones** actualizado
- Anotá los **acuerdos verbales** por escrito

### Productividad:

- Usá **plantillas** para no empezar de cero
- Revisá tu base de clientes **1 vez por semana**
- Archívá los clientes que finalicen (no los borres)

---

## 🎯 Resumen

En este módulo aprendiste:

- Crear una base de datos de clientes
- Configurar propiedades útiles
- Hacer páginas individuales por cliente
- Crear vistas filtradas
- Gestionar facturación básica

**Próximo módulo:** Calendario editorial profesional.

---

_cm-belen — Guía Notion para CM — Módulo 04_
