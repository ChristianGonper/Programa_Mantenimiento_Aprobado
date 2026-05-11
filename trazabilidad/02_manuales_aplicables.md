# 02 - Manuales aplicables

## Objetivo

Identificar los documentos de referencia de la seccion 7 del AMP: manual de mantenimiento de aeronave, documentacion de motor y TCDS/TBO aplicables.

## Decisiones de alcance

- Motor fijado: Textron Lycoming O-360-A1AD.
- No se consideran otros Service Bulletins de aeronave o motor.
- La helice se mantiene con una unica referencia suficiente salvo indicacion posterior.

## Consulta 1 - AMM Socata TB 10

Cuaderno: `Manuales_Socata` (`e9b2a1bb-aa57-45d5-8ee2-cc4e34d5f4c4`)

Fecha: 2026-05-10

Pregunta:

> For the SOCATA TB 10 S/N 649, identify the exact applicable aircraft maintenance manual from the notebook sources. Provide title, part number if shown, revision number/status, revision/date/effective date, applicability/effectivity range, and exact source title plus page/section references. If part number is not shown, say not found.

Resultado usado:

| Documento | Referencia | Revision/fecha | Aplicabilidad | Estado |
|---|---|---|---|---|
| SOCATA TB 10 Maintenance Manual, Tomes 1-7 | P/N Z00.18010310E0R18 | Rev. 18, SEP 06 | S/N 1-9999, incluye S/N 649 | Disponible, pero no ultima requerida por TCDS |

Fuentes citadas por NotebookLM:

- `3697 TB10 MM.pdf`, Title Pages Tomes 1-7: titulo y P/N.
- `3697 TB10 MM.pdf`, Chapter 00-LRP (CA), Page 132: Revision 18, SEP 06.
- `3697 TB10 MM.pdf`, Chapter 00-LRR (CA), Page 1 y headers del manual: Validity S/N 1-9999.
- `TCDS EASA.A.378 Issue 05.pdf`, Page 15, Section A.IV, Paragraph 2: el AMM debe estar en Revision 19 o posterior, incluyendo Chapter 4 Airworthiness Limitations, mas temporary revisions pendientes.

Decision:

- Para este trabajo academico se usara el AMM disponible en el cuaderno: Rev. 18, SEP 06, P/N Z00.18010310E0R18.
- Se dejara indicada como limitacion documental que el TCDS EASA.A.378 Issue 05 exige AMM Rev. 19 o posterior, pero el profesor no exige al alumno disponer de la ultima revision.
- La Rev. 18 se considera base valida de trabajo academico para continuar con programa base, servicing, puntos especiales y componentes, siempre citando la limitacion.

## Consulta 2 - Documentacion de motor Lycoming O-360-A1AD

Cuaderno: `Docs_motor` (`4f797c56-3b53-442d-8e07-292a40231080`)

Fecha: 2026-05-10

Pregunta:

> For the Lycoming O-360-A1AD engine, identify the exact applicable engine maintenance/operator/overhaul documents and TCDS from the notebook sources. Provide title, document number/part number, revision number/status, revision/date/effective date, applicability to O-360-A1AD, and exact source title plus page/section references. Do not include service bulletins except TCDS or TBO/service instruction if it is needed for TBO.

Resultado usado:

| Documento | Referencia | Revision/fecha | Aplicabilidad | Uso |
|---|---|---|---|---|
| Operator's Manual Lycoming O-360, HO-360, IO-360, AIO-360, HIO-360 & TIO-360 Series | P/N 60297-12 | 8th Edition, October 2005; revision pages through December 2009 | Incluye O-360-A1AD | Manual operativo/motor |
| FAA TCDS E-286 Lycoming Engines O-360 series | E-286 | Rev. 21, 30 Apr 2013 | Lista O-360-A1AD | TCDS motor |
| Parts Catalog Lycoming O-360-A Wide Cylinder Flange Models | PC-306-1 | PC-306-1B, July 1980; reprint Aug 1991 | Incluye O-360-A1AD | Referencia piezas |
| Parts Catalog Textron Lycoming O, LO, TO-360 Series Wide Cylinder Flange Models | PC-306-2 | PC-306-2B, Aug 1981; revision page menciona Jun 2010 | Incluye O-360-A1AD | Referencia piezas |
| Service Instruction Time Between Overhaul (TBO) Schedules | SI 1009BE | 24 Apr 2020 | O-360 except O-360-E: 2000 h | TBO motor |

Fuentes citadas por NotebookLM:

- `60297-12.pdf`, Title Page; Section 1 Page 1-4; Section 2 Page 2-10.
- `E-286_Rev_21.pdf`, Pages 1-2.
- `PC-306-1.pdf`, Title Page; Technical Publication Revision Page; Section 1 Page 1-1.
- `PC-306-2.pdf`, Title Page; Technical Publication Revision Page; Section 1 Page 1-1.
- `SI1009BE20Schedule.pdf`, Page 1 y Table 1 Page 3.

Decision:

- Para la seccion 7 del AMP se incluiran el Operator's Manual P/N 60297-12, el TCDS E-286 Rev. 21 y SI 1009BE para TBO.
- No se incorporan otros SB de aeronave o motor por decision de alcance del usuario.
