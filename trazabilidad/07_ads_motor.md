# 07 - ADs de motor

Cuaderno disponible: `Directivas_motor` (`c9960318-a98c-44ca-80eb-82a2eaa37645`).

Modelo de motor fijado para el trabajo: Textron Lycoming O-360-A1AD.

## Consulta 1 - Aplicabilidad ADs motor

Fecha: 2026-05-11

Pregunta:

> Analyze all AD PDFs in this notebook for applicability to Lycoming O-360-A1AD installed on SOCATA TB 10 S/N 649. Produce a table with: AD number, authority, subject, affected engine/model/component/serial/equipment, applicability to Lycoming O-360-A1AD (Applicable / Not applicable / Uncertain), reason for applicability or non-applicability, whether the AD has repetitive requirements, repetitive interval if any, and exact source title/page/paragraph cited. Focus on information needed for an academic AMP and Excel ADs tab. Do not include service bulletins as AMP tasks, only mention them if an AD mandates them.

## Resultado consolidado

| AD | Autoridad | Asunto | Aplicabilidad O-360-A1AD | Repetitiva | Intervalo | Decision |
|---|---|---|---|---|---|---|
| EASA 2005-0023R3 | EASA | Exhaust valve and guide inspection | Applicable, all Lycoming piston engines | Yes | 440 operating hours if no Hi-Chrome guides | Registrar como repetitiva aplicable |
| EASA 2024-0111 | EASA | Reciprocating engine inspection | Uncertain | Uncertain | Segun TCCA AD CF-2005-40 | Registrar incierta por fecha fabricacion/overhaul |
| FAA 2002-12-07 | FAA | Oil filter converter plate gasket | Uncertain, O-360-A1AD listed | Yes | 50 h TIS until terminating action | Registrar condicional |
| FAA 2004-10-14 | FAA | Crankshaft gear retaining bolt | Applicable after propeller strike event | No | Event-based | Registrar como no repetitiva/evento |
| FAA 2005-19-11 | FAA | Crankshaft replacement | Uncertain | No | N/A | Depende fecha/serial |
| FAA 2005-26-10 | FAA | ECi Classic Cast cylinders | Uncertain | No | N/A | Depende cilindros instalados |
| FAA 2006-10-21 | FAA | ECi connecting rods | Uncertain | No | N/A | Depende connecting rods instalados |
| FAA 2006-12-07 | FAA | ECi Classic Cast cylinders | Uncertain | No | N/A | Depende cilindros instalados |
| FAA 2006-20-09 | FAA | Crankshaft replacement | Uncertain | No | N/A | Superseded/covered by later crankshaft AD logic |
| FAA 2007-04-19R1 | FAA | Superior Air Parts cylinders | Uncertain | No | N/A | Depende cilindros SAP instalados |
| FAA 2008-19-05 | FAA | ECi Titan cylinders | Uncertain | Yes | 50 operating hours TIS | Registrar condicional |
| FAA 2009-26-12 | FAA | ECi Titan cylinders | Uncertain | Yes | 50 operating hours TIS | Registrar condicional |
| FAA 2010-07-08 | FAA | KAES rebuilt turbochargers | Not applicable | No | N/A | O-360-A1AD no es turbo |
| FAA 2012-03-07 | FAA | HA-6 carburetor | Uncertain | No | N/A | El TB10 usa Marvel MA-4-5, verificar instalado |
| FAA 2012-19-01 | FAA | Crankshaft replacement | Uncertain | No | N/A | Depende engine/crankshaft S/N |
| FAA 2015-02-07 | FAA | Propeller governor shaft set screws | Not applicable | Yes | At each installation | Afecta motores aerobatic wide deck; O-360-A1AD no aplica |
| FAA 2017-16-11 | FAA | Connecting rod bushings | Uncertain | No | N/A | Depende si engine/parts estan en MSB |
| FAA 2024-21-02 | FAA | Connecting rod bushings | Not applicable/superseded | Yes | Superseded by 2026-04-11 | Controlar por AD 2026-04-11 |
| FAA 2026-04-11 | FAA | Connecting rod bushings | Uncertain | Yes | Every oil change until terminating replacement | Registrar condicional |
| FAA 92-12-05 | FAA | Piston pin replacement | Uncertain | No | N/A | Depende engine S/N/pin P/N |
| FAA 96-09-10 | FAA | Oil pump impeller | Uncertain | No | N/A | Depende impeller installed |
| FAA 97-15-11 | FAA | Piston pin replacement | Uncertain | No | N/A | Depende S/N/cylinder kits |
| FAA 98-02-08 | FAA | Crankshaft inspection for fixed-pitch propellers | Not applicable | Yes | N/A | TB10 configurado con Hartzell constant-speed propeller |

## ADs repetitivas a reflejar en AMP 10.3

- EASA 2005-0023R3: exhaust valve and guide inspection, 440 operating hours si no hay Hi-Chrome guides.
- FAA 2002-12-07: oil filter converter plate gasket, 50 h TIS hasta terminating action si aplican fechas/kit/gasket.
- FAA 2008-19-05: ECi Titan cylinder assemblies, 50 h TIS si cilindros afectados instalados.
- FAA 2009-26-12: ECi Titan cylinder assemblies, 50 h TIS si cilindros afectados instalados.
- FAA 2026-04-11: connecting rod bushings, cada oil change hasta terminating replacement si partes afectadas instaladas.

## Nota de rubrica

Las ADs inciertas se mantienen en Excel con condicion de aplicabilidad. Para un control real habria que revisar engine S/N, crankshaft S/N, cilindros, connecting rods/bushings, carburador y registros de overhaul; para este trabajo academico se documenta la condicion.
