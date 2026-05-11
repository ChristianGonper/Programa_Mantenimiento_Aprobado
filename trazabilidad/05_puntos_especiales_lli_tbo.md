# 05 - Puntos especiales, LLP y TBO

## Alcance de esta fase

Este documento cubre dos bloques que deben mantenerse separados:

- Inspecciones especiales / fuera de fase: se vuelcan en AMP 8.2 y Excel `Tasks`.
- Componentes con vida limite, TBO u overhaul: se volcaran despues en AMP 10.1/10.2 y Excel `Life Limit Comp`.

## Consulta 1 - Inspecciones especiales y tareas fuera de fase

Cuaderno: `Manuales_Socata` (`e9b2a1bb-aa57-45d5-8ee2-cc4e34d5f4c4`)

Fecha: 2026-05-11

Pregunta:

> Using only the SOCATA TB 10 maintenance manual source, identify special inspections or out-of-phase scheduled inspections for TB 10 S/N 649 that are not the base A/2A/4A/80A/annual inspections. Include 400 hr engine special inspection, 500 hr, 1000 hr, calendar-based checks such as compass compensation or weighing if listed, and any notes that indicate inspection/check tasks with intervals outside the base program. For each item provide task name, interval, tolerance if stated, exact reference chapter/page/table, and whether it should be treated as a special inspection versus life-limited/TBO/overhaul item. Do not include service bulletins.

## Inspecciones especiales seleccionadas para AMP 8.2 / Excel Tasks

| Tarea | Intervalo | Tolerancia | Referencia | Tratamiento |
|---|---:|---:|---|---|
| Engine special inspection | 400 FH | 10 FH | `3697 TB10 MM.pdf`, 05-20-00 (BA), Inspection Calendar; 05-20-01 Pages 234-235 | Special inspection |
| 500 hrs special inspection | 500 FH | 50 FH | `3697 TB10 MM.pdf`, 05-20-00 (BA), Inspection Calendar | Special inspection |
| 1000 hrs special inspection | 1000 FH | 50 FH | `3697 TB10 MM.pdf`, 05-20-00 (BA), Inspection Calendar | Special inspection |
| Brake hydraulic fluid change | 3 years | No indicada | `3697 TB10 MM.pdf`, 05-20-01 Page 219 | Special inspection |
| Fuel selector filtering element clean/replace | 300 FH o 1 year | No indicada | `3697 TB10 MM.pdf`, 05-20-01 Page 213 | Special inspection/replacement |
| Flap actuator and supports visual inspection | 500 FH | No indicada | `3697 TB10 MM.pdf`, 05-20-01 Page 212 | Special inspection |
| Flight control supports inspection | 500 FH | No indicada | `3697 TB10 MM.pdf`, 05-20-01 Page 225 | Special inspection |
| Elevator hinge bearings visual inspection | 1000 FH o 2 years | No indicada | `3697 TB10 MM.pdf`, 05-20-01 Page 227 | Special inspection |

## Tareas operacionales fuera de fase para Excel `Operational Tasks`

| Tarea | Intervalo | Referencia | Tratamiento |
|---|---:|---|---|
| Weighing and balancing | 5 years o tras modificacion/reparacion mayor/cambio de equipo/pintado completo | `3697 TB10 MM.pdf`, 05-20-00 Page 2; 05-20-01 Page 202 | Operational/special calendar task |
| Compass compensation | 3 years o tras instalar equipo electrico/radio | `3697 TB10 MM.pdf`, 05-20-00 Page 2; 05-20-01 Page 222 | Operational/special calendar task |
| Air data systems tightness test | 300 FH o 3 years | `3697 TB10 MM.pdf`, 05-20-01 Page 222 | Operational task |
| Altimeter/transponder calibration/check | 24 months o regulacion local aplicable | `3697 TB10 MM.pdf`, 05-10-00 Page 3; 05-20-01 Pages 221/223 | Operational task |
| ELT visual inspection and operational test | 100 FH o 6 months | `3697 TB10 MM.pdf`, 05-20-01 Page 211 | Operational task |

## Reservado para fase de vida limite / TBO

No se vuelcan en AMP 8.2 ni en `Special Points Test/Tasks`:

- Extintores con limite/calendario.
- Sellos ELT.
- Filtros/bombas de vacio con replacement calendarizado.
- Mangueras elastomeras/vinilo.
- Access door latches con replacement.
- Motor, helice, gobernador, carburador, magnetos y starter con overhaul/TBO.

Estos elementos se trataran en AMP 10.1/10.2 y Excel `Life Limit Comp`.

## Consulta 2 - Time limits / LLP / TBO desde AMM

Cuaderno: `Manuales_Socata` (`e9b2a1bb-aa57-45d5-8ee2-cc4e34d5f4c4`)

Fecha: 2026-05-11

Pregunta:

> In source 3697 TB10 MM.pdf only, Chapter 05-10-00 Time Limits, for TB 10 S/N 649, list the time-limited or overhaul items from pages 1 through 9. Return a concise table with component, model/part if shown, interval, task type (OH, Discard, On Condition, Inspection only), and exact page number. Do not mention service bulletins. Include source citations.

Resultado usado:

| Item | Modelo/parte | Intervalo | Tipo | Referencia |
|---|---|---:|---|---|
| Alternator | ALX 8421 / ALX 8521 / ALU 8421 | Engine overhaul | OH | `3697 TB10 MM.pdf`, 05-10-00 Page 1 |
| ELT battery assembly | Segun ELT instalado | 4 years or battery life limit date | Discard | `3697 TB10 MM.pdf`, 05-10-00 Pages 1-2 |
| ELT seals | ELT90A2560009100 / ELT90A2560010001 | 12 years | Discard | `3697 TB10 MM.pdf`, 05-10-00 Page 2 |
| Fire extinguisher | MAIP/AREOFEU/L'HOTELLIER as installed | 10 years; L'HOTELLIER hydrostatic test 5 years | Discard / inspection | `3697 TB10 MM.pdf`, 05-10-00 Page 3, TR006.05 |
| Vacuum system filter | AIRBORNE 1J4-7 | 500 FH or 1 year | Discard | `3697 TB10 MM.pdf`, 05-10-00 Page 3 |
| Emergency vacuum pump | AIRBORNE 4A3-1 (14V) | 500 pump hours or 10 years | Discard | `3697 TB10 MM.pdf`, 05-10-00 Page 3 |
| Mechanical vacuum pump drive | AIRBORNE 211 CC | 6 years recommended | Discard | `3697 TB10 MM.pdf`, 05-10-00 Page 3 |
| Access door latches in AU4G | TB10 25012102 | 1500 FH | Discard | `3697 TB10 MM.pdf`, 05-10-00 Page 3 |
| Propeller | Hartzell HC-C2YK-1BF/F7666 A-2 | Overhaul per manufacturer/regulatory interval | OH | `3697 TB10 MM.pdf`, 05-10-00 Page 4 |
| Propeller governor | Hartzell F4-26 | Engine overhaul | OH | `3697 TB10 MM.pdf`, 05-10-00 Page 4 |
| Engine and equipment | Lycoming O-360-A1AD (14V) | Overhaul | OH | `3697 TB10 MM.pdf`, 05-10-00 Page 4 |
| Carburetor | Marvel 71098 MA-4-5 | Engine overhaul | OH | `3697 TB10 MM.pdf`, 05-10-00 Page 4 |
| Dual magneto | TCM D4LN3000 | Engine overhaul or 4 years | OH | `3697 TB10 MM.pdf`, 05-10-00 Page 4 |
| Starter | MZ 4222 / Lycoming LW15571 | Engine overhaul | OH | `3697 TB10 MM.pdf`, 05-10-00 Page 4 |
| Teflon hoses | Several | Unlimited | On Condition | `3697 TB10 MM.pdf`, 05-10-00 Pages 5-9 |
| Fuel selector filter / drain hose | TB10 52035114 | 2000 FH or 10 years | Discard | `3697 TB10 MM.pdf`, 05-10-00 Page 6 |
| Static/dynamic systems hose | Z00.N4085881010 | 8 years | Discard | `3697 TB10 MM.pdf`, 05-10-00 Page 8 |
| Brake hose short-life variant | Z00.N7850091701 | 5 years | Discard | `3697 TB10 MM.pdf`, 05-10-00 Page 8 |
| Other elastomer/rubber/vinyl hoses | Assorted | 5, 8 or 10 years depending on item | Discard | `3697 TB10 MM.pdf`, 05-10-00 Pages 5-9 |

## Consulta 3 - TBO motor Lycoming O-360-A1AD

Cuaderno: `Docs_motor` (`4f797c56-3b53-442d-8e07-292a40231080`)

Fecha: 2026-05-11

Pregunta:

> For Lycoming O-360-A1AD, using only documents in this notebook, extract engine TBO/overhaul limits and any relevant engine component overhaul/replacement limits explicitly applicable or generally applicable to O-360-A1AD. Include SI1009BE TBO, TCDS E-286 if useful, and operator manual if it states limits. For each item provide component, interval, task type (OH, Discard, On Condition), source title, page/section/table. Do not include unrelated service bulletins.

Resultado usado:

- Lycoming O-360-A1AD: 2000 FH or 12 calendar years, whichever occurs first. Tipo: OH.
- Fuente: `SI1009BE20Schedule.pdf`, Page 2 Calendar Time Period TBO; Page 3 Table 1 Fixed Wing Aircraft, O-360 except O-360-E = 2000 hours.
- La posible extension de TBO indicada por SI 1009BE no se aplica por defecto en este AMP academico; cualquier extension exigiria justificacion especifica.

## Seleccion para AMP 10.1 / Excel Life Limit Comp

Para mantener el trabajo defendible y manejable, se vuelcan los elementos representativos con intervalo claro y aplicabilidad directa: motor, accesorios principales, emergencia/vacio, puertas y mangueras. Las inspecciones puras se controlan en `Tasks`, no en `Life Limit Comp`.
