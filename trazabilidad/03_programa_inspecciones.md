# 03 - Programa de inspecciones

## Objetivo

Extraer el programa base de inspecciones del AMM Socata TB 10 Rev. 18 disponible para el trabajo academico, sin confundirlo con el detalle completo de cartas de inspeccion.

## Consulta 1 - Programa base

Cuaderno: `Manuales_Socata` (`e9b2a1bb-aa57-45d5-8ee2-cc4e34d5f4c4`)

Fecha: 2026-05-10

Pregunta:

> Using only the SOCATA TB 10 maintenance manual in this notebook, identify the base scheduled maintenance/inspection program for TB 10 S/N 649. I need the inspection names/check types, intervals in flight hours/calendar/cycles if given, allowed tolerances/extensions if given, and exact references (chapter/page/section/table). Do not list every inspection chart item; distinguish the general inspection program from individual task cards. If the annual inspection relationship to 50h/100h/200h checks is stated, include it.

Resultado usado:

| Inspeccion | Intervalo | Tolerancia | Referencia |
|---|---:|---:|---|
| "A" Inspection - First 25 hours | 25 FH inicial | 5 FH | `3697 TB10 MM.pdf`, 05-20-00 (BA) Page 1-2; 05-20-02 |
| "2A" Inspection / VP50 | 50 FH o 6 meses | 5 FH o 15 dias | `3697 TB10 MM.pdf`, 05-20-00 (BA) Page 1-2; 05-20-03 |
| "4A" Inspection / VP100 | 100 FH | 10 FH | `3697 TB10 MM.pdf`, 05-20-00 (BA) Page 1-2; 05-20-04 |
| Engine special inspection | 400 FH | 10 FH | `3697 TB10 MM.pdf`, 05-20-00 (BA) Page 1 |
| 500 hrs special inspection | 500 FH | 50 FH | `3697 TB10 MM.pdf`, 05-20-00 (BA) Page 1 |
| 1000 hrs special inspection | 1000 FH | 50 FH | `3697 TB10 MM.pdf`, 05-20-00 (BA) Page 1 |
| "80A" Major Inspection | 2000 FH | Sin tolerancia indicada | `3697 TB10 MM.pdf`, 05-20-00 (BA) Page 1; 05-20-05 |
| Annual Inspection (AI) | 12 meses | 2 meses | `3697 TB10 MM.pdf`, 05-20-00 (BA) Page 1; 05-20-06 |

Reglas de tolerancia:

- El tiempo entre dos inspecciones del mismo tipo no puede exceder `intervalo + tolerancia`.
- Las tolerancias no se acumulan para eliminar una inspeccion de nivel inferior.
- Si una inspeccion tiene limite horario y calendario, aplica el que venza antes.
- Para aeronaves registradas en EE. UU. no se permite tolerancia en la anual; no se aplica a este trabajo salvo cambio de matricula/criterio.

Relacion anual/hora:

- La inspeccion anual busca danos por envejecimiento que pueden no detectarse en inspecciones rutinarias.
- El manual permite omitir ciertas operaciones marcadas con `0` si se hizo inspeccion de 100 h en los ultimos 3 meses, salvo que la anual reemplace a una inspeccion de 100 h.

Decision para el AMP/Excel:

- En el bloque base se registran "A", "2A", "4A", "80A" y Annual Inspection.
- Las inspecciones 400 h, 500 h y 1000 h se reservaran para el bloque de inspecciones especiales, porque quedan fuera de la cadencia base 25/50/100/anual/major.
