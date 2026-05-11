# 01 - Identificacion y TCDS

## Objetivo

Identificar la configuracion aplicable de la DAHER AEROSPACE / Socata TB-10 S/N 649, ano 1988: modelo de aeronave, motor, helice y certificados de tipo aplicables.

## Consultas NotebookLM

Cuaderno: `Manuales_Socata` (`e9b2a1bb-aa57-45d5-8ee2-cc4e34d5f4c4`).

### Consulta 1 - Identificacion general

Fecha: 2026-05-10

Pregunta:

> For SOCATA TB-10 serial number 649, manufactured in 1988, identify the exact applicable aircraft model/variant, engine model(s), propeller model(s), and type certificate data sheets from the available sources. Use only the sources in this notebook. Cite the source title and exact page, section, table, note, or TCDS paragraph for each value. Also state whether serial number 649 is within the applicability/effectivity range.

Resultado usado:

- El S/N 649 esta dentro de la efectividad del AMM `3697 TB10 MM.pdf`, indicado como aplicable a S/N 1-9999.
- El IPC `3698 TB10 IPC.pdf` situa el S/N 649 dentro del rango S/N 1-822, 850-887, 889-947 para la configuracion de 14 V.
- El modelo aplicable es Type TB, Model TB 10, Normal and Utility Category.
- TCDS EASA aplicable: `EASA.A.378`, Issue 05.
- TCDS FAA aplicable: `A51EU`, Rev. 18.
- Motor identificado inicialmente: LYCOMING O-360-A1AD (14 V).
- Helice identificada inicialmente: HARTZELL HC-C2YK-1BF/F7666 A-2.

Fuentes citadas por NotebookLM:

- `3697 TB10 MM.pdf`, Chapter 05-10-00 (DA), Page 4.
- `3698 TB10 IPC.pdf`, Chapter 72-00-00, Figure 01.
- `TCDS EASA.A.378 Issue 05.pdf`, Page 1 y Page 9, Section A.I.
- `A51EU_Rev18.pdf`, Pages 1-6, Paragraph II.

### Consulta 2 - Verificacion motor/helice solo TB 10

Fecha: 2026-05-10

Pregunta:

> Focus only on Model TB 10, not TB 20 or TB 21. From TCDS EASA.A.378, FAA A51EU, and the TB10 maintenance manual, list the engine and propeller approved for TB 10 serial number 649. If multiple propeller options exist, list each option and the serial/modification applicability. Quote the page/paragraph/table references precisely and point out any uncertainty or OCR ambiguity.

Resultado usado:

- Motor aprobado para TB 10 S/N 649: Textron Lycoming O-360-A1AD.
- El S/N 649 cae en la configuracion de 14 V: S/N 1-822, 850-887, 889-947.
- Helice aprobada para TB 10 S/N 649: Hartzell HC-C2YK-1BF/F 7666 A-2, dos palas.
- No se adopta la referencia `HC-C2YL-1BF/F 7663 A-4` porque NotebookLM la vincula a una ambiguedad/posible error del change record EASA y a la seccion TB 9, no al TB 10.

Fuentes citadas por NotebookLM:

- `TCDS EASA.A.378 Issue 05.pdf`, Page 10, Section A.III.5.1: motor Textron Lycoming O-360-A1AD.
- `TCDS EASA.A.378 Issue 05.pdf`, Page 11, Section A.III.7.1: helice Hartzell HC-C2YK-1BF/F 7666 A-2.
- `3697 TB10 MM.pdf`, Chapter 05-10-00 (DA), Page 4: motor O-360-A1AD (14 V) y helice Hartzell HC-C2YK-1BF/F7666 A-2.
- `A51EU_Rev18.pdf`, Pages 5-6: confirma modelo TB 10, pero la extraccion de NotebookLM indica omision/incertidumbre OCR para motor/helice en ese fragmento.

## Datos consolidados

| Campo | Valor | Fuente | Estado |
|---|---|---|---|
| Fabricante | DAHER AEROSPACE / Socata | `TCDS EASA.A.378 Issue 05.pdf`, Page 1; `Documentacion.md` | Validado para fase 1 |
| Modelo | TB 10 | `TCDS EASA.A.378 Issue 05.pdf`, Page 9, Section A.I; `A51EU_Rev18.pdf`, Paragraph II | Validado para fase 1 |
| Numero de serie | 649 | `Informacion_preliminar.md`; efectividad AMM/IPc validada por NotebookLM | Validado para fase 1 |
| Ano de fabricacion | 1988 | `Informacion_preliminar.md` | Dato de asignacion |
| TCDS EASA aeronave | EASA.A.378 Issue 05 | `TCDS EASA.A.378 Issue 05.pdf`, Page 1 | Validado para fase 1 |
| TCDS FAA aeronave | A51EU Rev. 18 | `A51EU_Rev18.pdf`, Pages 1-6 | Validado para fase 1 |
| Modelo de motor | Textron Lycoming O-360-A1AD (14 V para S/N 649) | `TCDS EASA.A.378 Issue 05.pdf`, Page 10, Section A.III.5.1; `3697 TB10 MM.pdf`, 05-10-00 (DA), Page 4 | Validado para fase 1 |
| Modelo de helice | Hartzell HC-C2YK-1BF/F 7666 A-2 | `TCDS EASA.A.378 Issue 05.pdf`, Page 11, Section A.III.7.1; `3697 TB10 MM.pdf`, 05-10-00 (DA), Page 4 | Validado para fase 1 |

## Decisiones

- Se adopta `Textron Lycoming O-360-A1AD` como motor del AMP.
- Se adopta `Hartzell HC-C2YK-1BF/F 7666 A-2` como helice del AMP.
- Se conserva `A51EU Rev. 18` como TCDS FAA de aeronave, pero para motor/helice se prefiere EASA.A.378 + AMM porque NotebookLM detecta omision/incertidumbre OCR en el fragmento FAA A51EU.
