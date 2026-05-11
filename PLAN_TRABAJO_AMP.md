# Plan de trabajo AMP Socata TB 10

Este documento es la guia viva para completar el Programa de Mantenimiento Aprobado y el Excel de control de aeronavegabilidad. Debe mantenerse actualizado durante el trabajo.

## Regla general

No rellenar una seccion del AMP o del Excel hasta que exista su evidencia en `trazabilidad/`: cuaderno NotebookLM, documento, pagina/seccion, consulta usada y decision tomada.

## Estado rapido

| Fase | Estado | Salida principal |
|---|---|---|
| 1. Preparacion del repo | Completado | `guidance.md`, `trazabilidad/00_indice.md` |
| 2. Identificacion de configuracion | Completado | `trazabilidad/01_identificacion_tcds.md`, AMP seccion 2 |
| 3. Documentos de referencia | Completado con limitacion | `trazabilidad/02_manuales_aplicables.md`, AMP seccion 7 |
| 4. Programa base de inspecciones | Completado | `trazabilidad/03_programa_inspecciones.md`, AMP 8.1, Excel `Tasks` |
| 5. Inspecciones especiales | Completado | AMP 8.2, Excel `Special Points Test/Tasks` |
| 6. Limpieza, lubricacion y servicing | Completado | AMP apartado servicing, Excel `Tasks` |
| 7. Componentes vida limite / TBO / OH | Pendiente | AMP 10.1/10.2, Excel `Life Limit Comp` |
| 8. ADs aeronave y motor | Pendiente | AMP 10.3/11, Excel `ADs` |
| 9. Excel funcional | En curso | Formulas, `Next due`, `to go`, alertas |
| 10. Revision final contra rubrica | Pendiente | Entrega coherente AMP + Excel |

## Orden de ejecucion

1. **Base y trazabilidad**
   - Mantener `trazabilidad/00_indice.md` actualizado.
   - Registrar cada consulta relevante a NotebookLM antes de usar el dato.
   - Anotar bloqueos en `trazabilidad/documentos_pendientes.md`.

2. **Identificacion de configuracion**
   - Confirmar aeronave, S/N, ano, TCDS, motor y helice.
   - Datos actuales: Socata TB 10, S/N 649, ano 1988; motor Lycoming O-360-A1AD; helice Hartzell HC-C2YK-1BF/F 7666 A-2.
   - No profundizar en helice salvo indicacion expresa posterior.

3. **Documentos de referencia**
   - Usar AMM Socata TB 10 Rev. 18 como base academica disponible.
   - Dejar indicada la limitacion: TCDS EASA.A.378 menciona AMM Rev. 19 o posterior.
   - Usar documentacion motor: Lycoming Operator's Manual P/N 60297-12, TCDS E-286 Rev. 21 y SI 1009BE para TBO.
   - No considerar Service Bulletins de motor ni aeronave.

4. **Programa base de inspecciones**
   - Registrar inspecciones inicial 25 h, 50 h/6 meses, 100 h, 2000 h major y anual.
   - Volcar intervalos, tolerancias y referencias en AMP seccion 8.1 y Excel `Tasks`.
   - Mantener separadas las cartas/tareas individuales del programa general.

5. **Inspecciones especiales**
   - Extraer tareas fuera de fase del AMM: 400 h, 500 h, 1000 h, calendario u otras.
   - Separarlas de LLP/TBO/OH.
   - Rellenar AMP seccion 8.2 y bloque `Special Points Test/Tasks`.

6. **Limpieza, lubricacion, servicing y fluidos**
   - Extraer ATA 12 y tareas asociadas: aceite, combustible, limpieza, lubricacion, drenajes y rellenos.
   - Registrar intervalos y tolerancias si existen.
   - Rellenar el apartado de servicing del AMP y el bloque correspondiente del Excel.

7. **Componentes con vida limite, TBO y overhaul**
   - Extraer de AMM 05-10-00 y documentos de motor.
   - Clasificar cada elemento como `OH`, `Discard` u `On Condition`.
   - Incluir motor O-360-A1AD con TBO 2000 h segun SI 1009BE.
   - Rellenar AMP 10.1/10.2 y Excel `Life Limit Comp`.

8. **Directivas de aeronavegabilidad**
   - Analizar `Directivas_Aeronave` y `Directivas_motor`.
   - Separar ADs repetitivas aplicables y ADs no aplicables.
   - Justificar cada no aplicable por S/N, modelo, equipo no instalado o condicion no aplicable.
   - Rellenar AMP 10.3/11 y Excel `ADs`.

9. **Excel funcional**
   - Rellenar `Flight Log` con datos simulados para el trabajo academico.
   - Revisar `Flight Log` como fuente maestra de FH/ciclos/aterrizajes.
   - Verificar formulas de `Next due` y `to go`.
   - Mantener nombres, intervalos y referencias identicos entre AMP y Excel.

10. **Revision final contra rubrica**
    - Eliminar ejemplos ajenos que queden en la plantilla.
    - Revisar trazabilidad de cada dato importante.
    - Confirmar coherencia AMP/Excel.
    - Preparar anexos/evidencias: TCDS, reports, paginas de inspecciones especiales, LLP/TBO y ADs.

## Limitaciones actuales

- El trabajo usa AMM Rev. 18 porque es la documentacion academica disponible.
- El TCDS EASA.A.378 indica AMM Rev. 19 o posterior; se deja como limitacion documental.
- No se incluyen otros Service Bulletins de aeronave o motor.
- La helice se mantiene a nivel de identificacion suficiente salvo nueva indicacion del profesor.
