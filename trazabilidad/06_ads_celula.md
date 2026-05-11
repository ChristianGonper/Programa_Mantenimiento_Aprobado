# 06 - ADs de celula

Cuaderno disponible: `Directivas_Aeronave` (`38c480ef-7d81-43ab-ae7f-2d5e9c5af8bb`).

Cuaderno adicional para ADs no aplicables: `Directivas_Aeronave_no_aplicables` (`4dd19a89-8f0b-4f58-a236-aadcb3967db1`).

## Consulta 1 - Aplicabilidad ADs aeronave

Fecha: 2026-05-11

Pregunta:

> Analyze all AD PDFs in this notebook for applicability to SOCATA TB 10 serial number 649. Produce a table with: AD number, authority, subject, affected model/serial/equipment, applicability to TB 10 S/N 649 (Applicable / Not applicable / Uncertain), reason for applicability or non-applicability, whether the AD has repetitive requirements, repetitive interval if any, and exact source title/page/paragraph cited. Focus on information needed for an academic AMP and Excel ADs tab. Do not include service bulletins as AMP tasks, only mention them if an AD mandates them.

## Resultado consolidado

| AD | Autoridad | Asunto | Aplicabilidad TB 10 S/N 649 | Repetitiva | Intervalo repetitivo / efecto | Decision |
|---|---|---|---|---|---|---|
| 2007-0034 | EASA | Time Limits - life limit engine and NLG mounts | Applicable | No | Introduce life limit 10000 FH | Controlar como ALI/life limit y registrar en ADs |
| 2007-0101 | EASA | Cabin access door hooks | Uncertain | Yes | 110 FH until terminating action | Registrar como incierta por equipamiento; controlar si hooks AU4G instalados |
| 2015-0130 | EASA | Horizontal stabilizer spar corrosion | Applicable | Yes | 72 months | Registrar como repetitiva aplicable |
| 2018-0030R1 | EASA | Wing front attachments | Applicable, Group 1 MSN 001-803 | Yes | 2000 FH or 3000 LDG; some actions 12 months | Registrar como repetitiva aplicable |
| 2025-0160 | EASA | Lower rudder hinge fitting | Applicable | Yes | 12 months | Registrar como repetitiva aplicable |
| F-1992-206R3 | DGAC France | Exhaust system | Applicable by S/N 1-1191 | No | One-time / compliance action | Registrar en Excel; no en AMP repetitivas |
| F-1994-264R1 | DGAC France | Wing front attachments | Not applicable | N/A | Superseded by 2018-0030R1 | Registrar N/A |
| F-1994-265R4 | DGAC France | Main landing gear support ribs | Applicable if Case A, S/N 1-803 | Yes | 1500 LDG or 1000 FH if Case A | Registrar como aplicable/condicional |
| F-1996-143 | DGAC France | Front belt upper attachment | Uncertain | No | Depends on upholstering | Registrar en Excel |
| F-1999-062 | DGAC France | Fuel system / 14V gage | Uncertain | No | Depends on 14V and engine control panel amendment D | Registrar en Excel |
| F-2001-002 | DGAC France | Rudder bearing | Not applicable | N/A | Superseded by 2025-0160 | Registrar N/A |
| F-2001-005 | DGAC France | Seat unlocking | Uncertain | No | Depends on MOD 165 | Registrar en Excel |
| F-2001-305 | DGAC France | Nose gear fork spare part | Uncertain | No | Only if affected spare fork installed | Registrar en Excel |
| F-2001-306 | DGAC France | Wing front attaching bolts | Uncertain/N.A. by S/N | No | S/N 649 not listed; only if affected spare axes installed | Registrar en Excel |
| F-2001-446R1 | DGAC France | Ammeter circuit option | Uncertain | No | Depends on ammeter option installed | Registrar en Excel |
| F-2003-368R2 | DGAC France | Aileron/elevator gimbal joints | Uncertain | Yes | 110 FH or 14 months unless terminating mod/SB applied | Registrar como repetitiva condicional |

## ADs repetitivas a reflejar en AMP 10.3

- EASA 2007-0101, si aplica por ganchos de puerta AU4G/aluminio: 110 FH.
- EASA 2015-0130: horizontal stabilizer spar, 72 months.
- EASA 2018-0030R1: wing front attachments, 2000 FH or 3000 LDG; acciones/inspecciones adicionales segun grupo y estado.
- EASA 2025-0160: lower rudder hinge fitting, 12 months.
- DGAC F-1994-265R4: main landing gear support ribs, 1500 LDG or 1000 FH si Case A.
- DGAC F-2003-368R2: flight control gimbal joints, 110 FH or 14 months si no hay terminating action.

## Nota de rubrica

El Excel debe conservar tambien las ADs no aplicables o inciertas con motivo en `Remarks`, porque la rubrica valora justificar aplicabilidad y no aplicabilidad.

## Consulta 2 - ADs de celula no aplicables adicionales

Fecha: 2026-05-11

Cuaderno: `Directivas_Aeronave_no_aplicables` (`4dd19a89-8f0b-4f58-a236-aadcb3967db1`)

Pregunta:

> Lista todas las directivas de aeronavegabilidad de célula TB aplicables a Socata/TB que NO aplican a nuestra aeronave Socata TB 10 S/N 649 año 1988. Para cada AD indica número AD, autoridad, asunto, motivo exacto de no aplicabilidad y si el motivo es por número de serie, por fecha/model year anterior, o por equipo no instalado. Devuelve una tabla concisa.

Resultado usado en Excel `ADs`:

| AD | Autoridad | Asunto | Motivo N/A escrito en Remarks |
|---|---|---|---|
| DGAC F-1981-202 / 81-202-(A) | DGAC / Bureau Veritas | Forward CG limit / flap actuator modification | N/A por ser previa a nuestra aeronave: aplica a S/N 1-239; S/N 649 año 1988 queda fuera y la modificación viene de serie |
| DGAC F-1994-249R1 | DGAC | Wing rear attachment fittings | N/A por numero de serie: S/N 649 no incluido |
| DGAC F-1999-319 | DGAC | Vertical stabilizer forward junction doubler | N/A por numero de serie/configuracion segun analisis academico |
| DGAC F-2001-307 | DGAC | Door hinge attachment on upper fuselage | N/A por numero de serie: S/N 649 no incluido |
| DGAC F-2003-285 | DGAC | Nose gear fork | N/A por numero de serie: S/N 649 no incluido |

Decision:

- Se añadieron estas ADs al bloque Aircraft del Excel `ADs`, sin intervalos de control porque no aplican.
- La AD de 1981 se justifica por ser previa a nuestra aeronave y venir la modificación de serie, segun indicacion del usuario.
- Las demas se justifican como `N/A por numero de serie`, salvo la 1999-319 que se deja como `N/A por numero de serie/configuracion` para mantener la nota de analisis academico.
