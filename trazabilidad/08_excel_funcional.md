# Trazabilidad - Excel funcional y Flight Log simulado

## Objetivo

Hacer operativo `Control_de_aeronavegabilidad2026.xlsx` para que el libro cumpla la parte de control de aeronavegabilidad indicada por la rubrica: acumulacion de horas/ciclos/aterrizajes, calculo de `Next due`, remanentes `to go` y alertas por formato condicional.

## Fuente y criterio de trabajo

- Documento profesor: `Guía de Elaboración AMP.md`, fase "Paso 7: Excel funcional".
- Rubrica: `Rúbrica trabajo de Mantenimiento 2026.xlsx`, hoja `Control Aeronavegabilidad`.
- Decision academica del usuario: el `Flight Log` se rellena con datos simulados.
- Hipotesis de utilizacion documentada en AMP seccion 6: 100 FH/ano, 80 vuelos/ciclos/ano y 90 aterrizajes/ano, con tolerancia +/-25%.

## Datos simulados introducidos

- Saldo inicial simulado a 31/12/2024:
  - 2080.0 FH acumuladas.
  - 1040 ciclos acumulados.
  - 1240 aterrizajes acumulados.
- Vuelos simulados entre 12/01/2025 y 10/05/2026.
- Ultimo vuelo simulado: 10/05/2026.
- Totales resultantes al corte academico:
  - 2132.0 FH.
  - 1067 ciclos.
  - 1273 aterrizajes.

## Logica funcional aplicada

- `Flight Log`:
  - Columna E acumula FH: fila anterior + horas del vuelo.
  - Columna F acumula ciclos: fila anterior + ciclos del vuelo.
  - Columna G acumula aterrizajes: fila anterior + aterrizajes del vuelo.
- `Tasks`, `Life Limit Comp` y `ADs`:
  - Las celdas de lectura superior enlazan con el ultimo valor no vacio del `Flight Log`.
  - `Next due` por horas/ciclos/aterrizajes se calcula como `Performed + Interval`.
  - `to go` por horas/ciclos/aterrizajes se calcula como `Next due - lectura actual`.
  - `Next due` calendario se calcula como `Performed date + days`.
  - `to go` calendario se calcula como `Next due date - fecha ultimo vuelo`.
- Formato condicional:
  - Rojo: tarea vencida (`to go <= 0`).
  - Amarillo: tarea proxima (`0 < to go <= 30`).

## Correcciones de coherencia hechas durante la fase

- Se completo `ELT visual inspection and operational test` en `Tasks` con seguimiento operativo independiente.
- Se completo `Fuel selector filter/drain hose` en `Life Limit Comp`.
- Se completo la fila de `DGAC F-2001-306` en `ADs`, manteniendola como condicionada/no repetitiva sin intervalo identificado.
- Se descombinaron filas de datos que impedian formulas y edicion independiente.

## Limitaciones

- Los valores de cumplimiento previo (`Performed`) son simulados para que el Excel sea funcional y demostrable.
- En ADs o componentes condicionados por S/N de pieza, equipo instalado o modificacion incorporada, el Excel conserva la decision como `Uncertain` o `N/A` en observaciones.
- El libro queda preparado para recalcular al abrirse en Excel/LibreOffice; la verificacion local confirma que no hay formulas con errores textuales (`#REF!`, `#VALUE!`, `#NAME?`, `#DIV/0!`, `#N/A`).
