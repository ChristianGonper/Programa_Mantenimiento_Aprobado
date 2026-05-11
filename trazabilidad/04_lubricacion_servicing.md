# 04 - Lubricacion, limpieza, servicing y fluidos

## Objetivo

Extraer tareas programadas de limpieza, lubricacion, servicing, replenishing, draining y fluidos aplicables a la Socata TB 10 S/N 649, usando el AMM Rev. 18 disponible como base academica.

## Consulta 1 - ATA 12 y servicing

Cuaderno: `Manuales_Socata` (`e9b2a1bb-aa57-45d5-8ee2-cc4e34d5f4c4`)

Fecha: 2026-05-11

Pregunta:

> Using only the SOCATA TB 10 maintenance manual source, extract lubrication, cleaning, servicing, replenishing, draining, and fluid-related scheduled tasks applicable to TB 10 S/N 649. Focus on ATA 12 and the inspection chart servicing rows. For each task provide task name, interval in flight hours/calendar if stated, tolerance if stated, exact chapter/page/section reference, and whether it belongs in Lubrication & Cleaning Tasks versus Special/Operational/Life Limit. Do not include service bulletins.

## Tareas para AMP / Excel `Lubrication & Cleaning Tasks`

| Tarea | Intervalo | Tolerancia/criterio | Referencia |
|---|---:|---|---|
| Drain oil system, replace/check filter and clean crankcase strainer | First engine 10 FH and 25 FH or 4 months; then 50 FH or 4 months | Tolerancia VP50: 5 FH o 15 dias | `3697 TB10 MM.pdf`, 05-20-01 (GA) Page 203, ATA 12-10 |
| Drain fuel tanks and fuel system, ventilate | Major 2000 FH and Annual | Tolerancia anual: 2 months | `3697 TB10 MM.pdf`, 05-20-01 (GA) Page 203, ATA 12-10 |
| Clean exterior surface and inspect for corrosion | 100 FH, Major 2000 FH, Annual | 10 FH para 100 h; 2 months para anual | `3697 TB10 MM.pdf`, 05-20-01 (GA) Page 203, ATA 12-20 |
| Clean engine | 100 FH, Major 2000 FH, Annual | 10 FH para 100 h; 2 months para anual | `3697 TB10 MM.pdf`, 05-20-01 (GA) Page 203, ATA 12-20 |
| Reinforce anticorrosion protection/lubricate cockpit-fuselage and landing gear areas | 50 FH, 100 FH, Major 2000 FH, Annual | 5 FH/15 days para 50 h; 10 FH para 100 h; 2 months anual | `3697 TB10 MM.pdf`, 05-20-01 (GA) Pages 203-204, ATA 20-00 |
| Reinforce anticorrosion protection/lubricate stabilizers, wings and engine compartment areas | 100 FH, Major 2000 FH, Annual | 10 FH para 100 h; 2 months anual | `3697 TB10 MM.pdf`, 05-20-01 (GA) Page 204, ATA 20-00 |
| Lubricate bearings and wheel axles | Major 2000 FH and Annual | Tolerancia anual: 2 months | `3697 TB10 MM.pdf`, 05-20-01 (GA) Page 219, ATA 32-40 |
| Lubricate door locking mechanisms | Major 2000 FH | Regla general de tolerancias | `3697 TB10 MM.pdf`, 05-20-01 (GA) Page 224, ATA 52-10 |
| Lubricate inside of elevator balancing boom | Major 2000 FH | Regla general de tolerancias | `3697 TB10 MM.pdf`, 05-20-01 (GA) Page 227, ATA 55-20 |

## Tareas relacionadas que no se duplican aqui

- Brake hydraulic fluid change cada 3 years ya fue registrada como inspeccion especial en `05_puntos_especiales_lli_tbo.md`.
- Tire inflation, brake reservoir level, shock absorber inflation/leaks se mantienen como tareas operacionales o incluidas dentro de inspecciones, no como bloque principal de lubricacion.
- Elementos con reemplazo calendarizado o TBO se trataran en `Life Limit Comp`.
