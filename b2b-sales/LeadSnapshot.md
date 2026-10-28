# Lead Snapshot

## Objetivo del documento

> Definir la vista de Lead Snapshot en HubSpot que el SDR outbound ve al momento de llamar: el orden de los campos, qué significa cada uno, cuándo se completa y quién deja la vista lista en el enriquecimiento.

El equipo de SDRs outbound pidió reordenar la sección de Lead Snapshot para mostrar, de forma ordenada, la información más relevante antes de la llamada. Esta especificación sale de [EQU-31 — Personalización del Lead Snapshot](https://linear.app/equipconstruye/issue/EQU-31/personalizacion-del-lead-snapshot) (HubSpot, Knowledge Base).

El Lead Snapshot es la ficha que el SDR consulta en HubSpot. Complementa el research previo; no lo reemplaza.

## Relación con otros documentos

| Documento | Cómo se relaciona |
| --- | --- |
| [LeadPlanning.md](LeadPlanning.md) | Research previo a la llamada (plantillas de obra privada y pública, empresa, proyectos y buyer personas). El Lead Snapshot es la vista en HubSpot que el SDR ve al llamar. Esta ficha no reemplaza el lead planning. |
| [LeadCategoriesByTiers.md](LeadCategoriesByTiers.md) | Framework de Tier 1, Tier 2 y Tier 3 que alimenta el campo **Tier**. |
| [IdealCustomerProfile.md](IdealCustomerProfile.md) | Buyer personas detrás del teléfono y del correo del contacto principal. |

## Orden de la nueva vista

Los campos se muestran en este orden:

1. RUC / DNI (Respond)
2. Razón Social (Respond)
3. Nombre Comercial
4. Actividad Comercial
5. Dirección
6. Tier
7. Origen
8. Número de teléfono
9. Correo Electrónico
10. Categorías de productos (Respond)
11. Motivo de No compra (Opcional)
12. Asesor encargado (Respond)
13. Etiqueta del lead

**Contexto de IA** forma parte de la vista y está definido en la tabla de campos. En EQU-31 no tiene un número propio dentro de esta lista.

## Campos

| Campo | Explicación | Ejemplos |
| --- | --- | --- |
| RUC / DNI (Respond) | Aquí va el número de RUC de 11 dígitos, que en la gran mayoría de leads empieza con el número 20 por ser personas jurídicas y debe estar relacionado con la razón social de la empresa. | 20453695957 |
| Razón Social | Es el nombre completo de la empresa que aparece en consulta RUC - SUNAT. Usado para términos comerciales y legales. En la vista aparece como Razón Social (Respond). | ISUM CONTRATISTAS E.I.R.L. |
| Nombre comercial | Este es el nombre que se usa en las redes sociales y en el sitio web de la empresa. Normalmente es más corto y fácil de recordar. | ISUM |
| Actividad comercial | Este dato aparece en el mismo sitio web de consulta RUC - SUNAT o buscando directamente en Google [RUC] + actividad comercial. Una empresa puede tener más de una actividad comercial, pero en HubSpot se debe colocar la actividad principal. | ACTIVIDADES DE ARQUITECTURA E INGENIERÍA Y ACTIVIDADES CONEXAS DE CONSULTORÍA TÉCNICA |
| Dirección | En este campo podemos agregar tanto la dirección de las oficinas de la empresa como de la ubicación de sus actuales proyectos. | Oficinas ubicadas en la región Callao y una sucursal en Cajamarca. Vienen desarrollando proyectos en localidades como Morropón (Piura), Jaén (Cajamarca), San Ignacio (Cajamarca) y Chiclayo (Lambayeque). |
| Tier | Este es un análisis que se realiza según el framework de categorización del ICP por Tiers. Sólo hay 3 opciones: Tier 1, Tier 2, Tier 3. Si no encaja en ninguno, es mejor dar aviso para poder eliminar o colocar el lead en la blacklist. Ver [LeadCategoriesByTiers.md](LeadCategoriesByTiers.md). | Tier 3 |
| Origen | Seleccionar una opción según la fuente del lead. | SEACE |
| Número de Teléfono | Es el número que se encontró del buyer persona o del contacto principal que está asociado a ese lead. | +51 994-306-408 |
| Correo Electrónico | Es el correo electrónico que se encontró del buyer persona o del contacto principal. | isumeirl@gmail.com |
| Categorías de productos (Respond) | Aquí se coloca las categorías de materiales que el lead mostró interés o que solicitó una cotización por Respond. Principalmente aplica para leads de origen LOST y NO CALIFICADO. Para leads nuevos, puedes dejarlos vacío o llenarlo con una sugerencia en base a la etapa de los proyectos que tienen en ejecución. | Acero; Cemento y Embolsados; Ladrillos y Placas; Tuberías, Válvulas y conexiones; Electricidad; Químicos para la construcción; Cerámicos y porcelanatos; Pegamentos y fraguas; Pinturas; Baños y cocinas; Herramientas; Otro artículos de ferretería. |
| Motivo de NO compra | Este campo aplica sólo para los leads de origen LOST y NO CALIFICADO que ya tengan algún deal o negocio asociado. En la vista aparece como Motivo de No compra (Opcional). | Cliente no dio feedback a cotización. |
| Asesor encargado | Este campo aplica sólo para los leads que ya tienen registro de algún negocio en HubSpot y que tengan el campo «Asesor» completado. Las únicas opciones están en la lista canónica de asesores. En la vista aparece como Asesor encargado (Respond). | Alessandro Gotuzzo |
| Etiqueta del lead | Esta etiqueta lo completan los mismos SDRs de acuerdo a su criterio. | Caliente |
| Contexto de IA | En este campo se debe colocar algunos comentarios puntuales sobre los proyectos que están en etapa de construcción, por empezar o por finalizar. | Más de 350,000 m² construidos para constructoras, desarrolladores, instituciones y entidades públicas. Proyectos multifamiliares como Óvalo Pardo, 23 pisos y 20,042 m² en Miraflores. También presentan La Pinta 130, 7 pisos y 3,500 m² en San Isidro. |

## Reglas de uso

### Motivo de No compra

Aplica sólo cuando se cumplen las dos condiciones:

- El origen del lead es **LOST** o **NO CALIFICADO**.
- El lead ya tiene algún deal o negocio asociado.

En la vista el campo es opcional. El ejemplo de EQU-31 es «Cliente no dio feedback a cotización.»

### Asesor encargado

Aplica sólo cuando se cumplen las dos condiciones:

- El lead ya tiene registro de algún negocio en HubSpot.
- El campo «Asesor» de ese negocio está completado.

No se inventan nombres. Las únicas opciones son las de la lista canónica de abajo.

### Categorías de productos

- Se registran las categorías de materiales en las que el lead mostró interés o pidió una cotización por Respond.
- El uso principal es en leads de origen **LOST** y **NO CALIFICADO**.
- En leads nuevos el campo puede quedar vacío, o llenarse con una sugerencia según la etapa de los proyectos en ejecución.

### Tier y blacklist

- Las únicas opciones son **Tier 1**, **Tier 2** y **Tier 3**, según el framework de [LeadCategoriesByTiers.md](LeadCategoriesByTiers.md).
- Si la cuenta no encaja en ninguno, hay que dar aviso para eliminar el lead o colocarlo en la blacklist. No se fuerza un tier.

### Actividad comercial, contacto y etiqueta

- Si la empresa tiene más de una actividad comercial, en HubSpot se coloca sólo la actividad principal (consulta RUC de SUNAT, o la búsqueda «[RUC] + actividad comercial»).
- El RUC tiene 11 dígitos, en la gran mayoría de leads empieza con 20 (persona jurídica) y debe corresponder a la razón social.
- Teléfono y correo son los del buyer persona o del contacto principal asociado al lead. Los perfiles de buyer persona están en [IdealCustomerProfile.md](IdealCustomerProfile.md).
- La etiqueta del lead la completan los SDRs según su criterio. El ejemplo de EQU-31 es «Caliente».
- Contexto de IA resume comentarios puntuales de proyectos en construcción, por empezar o por finalizar.

## Lista canónica de asesores

El campo **Asesor encargado** sólo admite estos valores:

- Alessandro Gotuzzo
- Maria Cristina Vasquez
- Luis Reyme
- Freysy Carretero
- Kevin Enrique Ibarra
- Erika Jesús Ramos Manzanares
- Luis Ricardo Tupiño Varillas

## Responsabilidad en el enriquecimiento

Este cambio afecta el proceso de enriquecimiento que sigue Peter. Peter y Jack deben dejar esta vista **100% completada** como parte del enriquecimiento, para que el SDR sepa que el lead ya tiene la información suficiente para trabajarlo.

Los campos condicionales se completan cuando aplica su regla: Motivo de No compra en LOST y NO CALIFICADO con negocio asociado, Asesor encargado cuando ya hay negocio y el campo «Asesor» está lleno, y Categorías de productos puede quedar vacío en un lead nuevo. El resto de la vista no se entrega a medias.

## Fuente

- Issue: [EQU-31 — Personalización del Lead Snapshot](https://linear.app/equipconstruye/issue/EQU-31/personalizacion-del-lead-snapshot)
- Label: HubSpot. Proyecto: Knowledge Base.
