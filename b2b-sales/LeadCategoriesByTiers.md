# Categorización de cuentas por tiers

## Objetivo del documento

> Definir cómo el equipo de SDRs de Equip organiza las cuentas en tres tiers según su afinidad con el ICP, y cómo usa esa clasificación en la prospección outbound y en la entrega de leads calificados a los ejecutivos comerciales.

La categorización permite enfocar de manera más eficiente los esfuerzos de prospección del equipo de SDR's outbound, mediente un análisis multivariable que toma en cuenta la descripción del ICP, los tops clientes de Equip y las señales de oportunidad de compra para poder determinar si una empresa es Tier 1, Tier 2 o Tier 3. La explicación de cada tiers se explica en este documento.


Esta guía no reemplaza otros documentos de la carpeta:

- El perfil de cliente ideal, los buyer personas y las señales de oportunidad de compra que se encuentran en [IdealCustomerProfile.md](IdealCustomerProfile.md) y en [BuySignals](buysignals.md).
- El puntaje de 1 a 10 y el campo «Prioridad actual» están en [LeadScoring.md](LeadScoring.md).
- La investigación previa a la llamada está en [LeadPlanning.md](LeadPlanning.md).
- Los orígenes de los leads que se cargan al pipeline de outbound están en [LeadSource.md](LeadSource.md).

Recuerda que antes de iniciar el proceso de categorización la sección de lead snapshot debe estar completa, caso contrario no tendrás la información suficiente para poder clasificar a los leads. Para mayor información sobre como completar los campos de lead snapshot, revisar los documentos de [Lead Snapshot](LeadSnapshot.md) y [Lead Planning](LeadPlanning.md)

---

## 1. Resumen de la categorización

### 1.1 Variables de evaluación

Al investigar una cuenta se revisan seis variables:

| Variable | Qué se mira |
| --- | --- |
| **Actividad comercial** | Actividad registrada en SUNAT y su relación con la construcción, el desarrollo inmobiliario, obra civil o ingeniería civil |
| **Tipo de proyecto u obra** | Naturaleza de las obras y la etapa en la que se encuentra, a medida que la obra llega a la última etapa, hay menor oportunidad de venta. El tipo de proyecto también puede determinar qué categorías de materiales podrían necesitar |
| **Ubicación** | Dónde están los proyectos y qué tan accesibles son logísticamente para Equip. |
| **Número de proyectos** | Cuántos proyectos ejecuta en paralelo, como indicador de potencial de compra y recurrencia. |
| **Área de contacto** | Si existe un área responsable de los requerimientos de materiales y si hay un contacto de fácil acceso para iniciar la conversación. |
| **Señal de oportunidad de compra** | Algún evento o acción relevante que se relacione con el lead y que aumente las posibilidades de compra. Sirve para llegar en el timing correcto y con un mensaje más personalizado. |

### 1.2 Definición de cada tier

**Tier 1 — Generan un valor superior y mayor probabilidad de fidelización** Negocios recurrentes, compras de alto valor y relaciones duraderas. Combina proyectos inmobiliarios, varias obras en ejecución y un área especializada en la gestión de materiales. Tiene mayor oportunidad de vender distintas categorías.

**Tier 2 — Afinidad con el ICP, multicategoría pero dificultad logística.** También encaja con el perfil de cliente ideal, pero alguna condición limita la oportunidad frente al Tier 1: accesibilidad logística, número de proyectos, posibilidad de vender otras categorías o acceso al área de compras.

**Tier 3 — Compras de menor volumen y unicategoría.** Necesidades pequeñas o puntuales, sobre todo de mantenimiento, reparaciones o remodelaciones. Suelen ser servicios complementarios o negocios cuya actividad principal no es la construcción.

### 1.3 Criterios por variable

Definido en EQU-20. Cada celda es el criterio de esa variable, no el tier automático de la cuenta.

| Variable | Tier 1 | Tier 2 | Tier 3 |
| --- | --- | --- | --- |
| **Actividad comercial en SUNAT** | Construcción de edificios y actividades inmobiliarias realizadas con bienes propios o arrendados. | Construcción de carreteras, construcción de otras obras de ingeniería civil, terminación y acabado de edificios, y construcción de proyectos de servicio público. | Actividades de arquitectura e ingeniería y consultoría técnica, instalaciones eléctricas, y transporte de carga por carretera. |
| **Tipo de proyecto u obra** | Viviendas multifamiliares de 5 pisos o más, condominios o urbanizaciones con más de una etapa, edificios residenciales y otros proyectos inmobiliarios. | Edificaciones para instituciones del Estado, obras civiles (parques e infraestructura vial), colegios, institutos y universidades, proyectos comerciales y de retail, e irrigación y saneamiento. | Reparación y mantenimiento de oficinas, remodelación de tiendas y servicios generales |
| **Ubicación de los proyectos** | Lima Top, Lima Moderna, Callao, Lima Norte, Lima Sur y regiones con mayor actividad económica como Arequipa, Piura, La Libertad y Lambayeque | EL resto de regiones del Perú | Resto de regiones del Perú. |
| **Número de proyectos en paralelo** | Más de 2. | Uno. | Uno. |
| **Área de contacto** | Área de Supply, Logística, Compras u Oficina Técnica, con el contacto disponible en HubSpot, LinkedIn o Unify. | Sin contacto de esas áreas, pero con un contacto administrativo o de gerencia. | La gerencia compra directamente los materiales de la obra. |
| **Señal de oportunidad de compra** | Existe más de 1 señal clara de oportunidad compra, por ejemplo, una constructora contratando un residente de obra para un proyecto por iniciar en La Victoria, Lima. Se registró que en LinkedIn el encargado de Logística está buscando nuevos aliados para el desarrollo de uno de los proyectos. Se encontró que uno de los gerentes fue entrevistado en un podcast de YouTube hablando sobre los proyectos en preventa | Existe una señal mínima de oportunidad de compra como el registro de un nuevo contrato en el portal de proveedores del Estado para la construccción de un nuevo hospital en provincia por X millones | Existe una señal no muy relevante pero que puede generar un indicio que la empresa tiene un proyecto activo como la publicación de una foto por parte de un ingeniero o supervisor de la obra o la mención del nombre de la empresa en una noticia. |

Lectura de la tabla, ya definida:

- La actividad en SUNAT es solo una referencia. Se revisa junto con los proyectos y el resto de la cuenta.
- En número de proyectos, Tier 2 y Tier 3 dicen lo mismo: un solo proyecto. Esa variable, por sí sola, no separa esos dos niveles.
- No encontrar un contacto no equivale a confirmar que el área no existe.

Qué no está en la tabla: la regla para mezclar variables de distintos niveles, el trato de exactamente 2 proyectos y el corte de «alrededores de Lima». Eso está en la sección 4.

### 1.4 Validación final

Para evitar que se filtre un lead que no encaje con ningún tier es recomendable poder hacer un doble check. Aquí algunos ejemplos del porqué se deben descalificar o excluir a un lead de la lista de categorización:

1. Si el lead aparece en SUNAT con el estado de NO HABIDO o tiene problemas legales graves o deuda coactiva.
2. Si el lead no ha tenido actividad en la ejecución de proyectos u obras por más de 1 año.
3. Si no se logró detectar al menos 1 señal de oportunidad de compra relacionada con el lead en evaluación.
4. El lead aparece como proveedor no cuenta con RNP, sólo en los casos cuando la empresa trabaja con el Estado y no en proyectos privados como el caso de las inmobiliarias.
5. Cuando el lead aparece como un subdistribuidor o pequeña ferretería que quiere comprar para revender.

---
