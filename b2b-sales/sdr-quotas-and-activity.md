## Metas y actividad del SDR outbound

## Sobre qué trata
En este documento se utiliza la metodología a la inversa para poder hacer el cálculo de la cantidad de pipeline que debe generar el SDR de manera mensual y semanal para lograr su cuota asignada por gerencia. Además, esto permite poder planificar la actividad de prospección que debe seguir el SDR, usando ciertas tasas de conversión para prospección por los canales más prioritarios en Equip, que son llamadas y correos.
 
La pregunta que responde este documento es: **¿cuántos leads necesito trabajar para llegar a mi cuota como SDR outbound?**


## Asignación de cuotas y supuestos
Para poder proyectar la generación de pipeline y la actividad que debe tener un SDR en Equip, se establecieron los siguientes supuestos y cuotas, en base a la data histórica del año 2026:

1. Tasa de conversión (de cotización a negocio ganado) = 20%
2. Ticket promedio, acá se establecieron 3 escenarios (optimista = $13,000 USD; moderado = $10,000 USD; pesimista = $7,000 USD)

La cuota mensual asiganda por el equipo comercial es de: $110 000.

Con estos datos se realizaron los cálculos para poder conocer la cantidad de pipeline mensual y semanal que necesita generar cada SDR:

---

## Generación de pipeline y calificación de leads

Con estos datos se realizaron los cálculos para poder conocer la cantidad de pipeline mensual y semanal que necesita generar cada SDR:
 
- **Pipeline** = Cuota ÷ Tasa de conversión (cotización a venta)
- **Requerimientos a cotizar** = Pipeline ÷ Ticket promedio

Como la cuota y la tasa de conversión son las mismas en los 3 escenarios, el pipeline que debe generar el SDR no cambia:
 
| Por SDR | Mensual (USD) | Semanal (USD) |
|---|---:|---:|
| Cuota | $110,000 | $27,500 |
| Pipeline | $550,000 | $137,500 |
 
Lo que sí cambia según el ticket promedio es la cantidad de requerimientos que se deben cotizar (con lista de materiales que podemos atender) para llegar a ese pipeline:
 
| Escenario | Ticket promedio | Requerimientos a cotizar (mensual) | Requerimientos a cotizar (semanal) | Negocios ganados esperados (mensual) |
|---|---:|---:|---:|---:|
| Optimista | $13,000 | 42 | 11 | ~8 |
| Moderado | $10,000 | 55 | 14 | 11 |
| Pesimista | $7,000 | 79 | 20 | ~16 |
 
> Los negocios ganados esperados se obtienen aplicando el 20% de conversión sobre los requerimientos cotizados (equivale a Cuota ÷ Ticket promedio).

---

## Gestión de leads por etapas del pipeline
Una vez definida la cantidad de requerimientos a cotizar, se aplica nuevamente la metodología a la inversa para conocer cuántos leads debe tener el SDR en cada etapa del pipeline. Para ello se utilizan las siguientes tasas de conversión entre etapas:
 
| Etapa | Conversión hacia la siguiente etapa |
|---|---:|
| Base inicial → Enriquecidos y priorizados | 80% |
| Enriquecidos y priorizados → Con respuesta | 60% |
| Con respuesta → Con lista de materiales | 15% |
| Con lista de materiales → Requerimientos a cotizar | 50% |
 
La cantidad de leads necesaria en cada etapa se calcula dividiendo la cantidad de la etapa siguiente entre su tasa de conversión. Por ejemplo: *Con lista de materiales = Requerimientos a cotizar ÷ 50%*.
 
### Escenario optimista (ticket de $13,000 USD)
 
| Etapa | Mensual | Semanal |
|---|---:|---:|
| Base inicial | 1,175 | 294 |
| Enriquecidos y priorizados | 940 | 235 |
| Con respuesta | 564 | 141 |
| Con lista de materiales | 85 | 21 |
| Requerimientos a cotizar | 42 | 11 |
 
### Escenario moderado (ticket de $10,000 USD)
 
| Etapa | Mensual | Semanal |
|---|---:|---:|
| Base inicial | 1,528 | 382 |
| Enriquecidos y priorizados | 1,222 | 306 |
| Con respuesta | 733 | 183 |
| Con lista de materiales | 110 | 28 |
| Requerimientos a cotizar | 55 | 14 |
 
### Escenario pesimista (ticket de $7,000 USD)
 
| Etapa | Mensual | Semanal |
|---|---:|---:|
| Base inicial | 2,183 | 546 |
| Enriquecidos y priorizados | 1,746 | 437 |
| Con respuesta | 1,048 | 262 |
| Con lista de materiales | 157 | 39 |
| Requerimientos a cotizar | 79 | 20 |
 
> Las cifras están redondeadas al entero más cercano; los valores exactos están en el Excel *Playbook-Outbound-sdr* (tab "Cuota y Pipeline").
 
---

## Actividad mensual y semanal
Finalmente, se proyecta la actividad que tiene que ejecutar el SDR por canal de manera mensual, semanal y diaria. El punto de partida es la cantidad de leads **con lista de materiales** que se necesita en cada escenario, y se aplican las siguientes tasas de conversión aproximadas de prospección fría:
 
| Canal | Conversión a lista de materiales (aprox.) |
|---|---:|
| Llamadas | 10% |
| Correos | 3% |
 
- **Actividad mensual** = Leads con lista de materiales ÷ Tasa de conversión del canal
- **Actividad semanal** = Actividad mensual ÷ 4
- **Actividad diaria** = Actividad semanal ÷ 5
| Escenario | Canal | Mensual | Semanal | Diario |
|---|---|---:|---:|---:|
| Optimista | Llamadas | 846 | 212 | 42 |
| Optimista | Correos | 2,821 | 705 | 141 |
| Moderado | Llamadas | 1,100 | 275 | 55 |
| Moderado | Correos | 3,667 | 917 | 183 |
| Pesimista | Llamadas | 1,571 | 393 | 79 |
| Pesimista | Correos | 5,238 | 1,310 | 262 |



