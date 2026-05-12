# Programa de Mantenimiento Aprobado - Socata TB 10 S/N 649

Repositorio de trabajo para elaborar un Programa de Mantenimiento Aprobado (AMP) Parte-ML y un libro Excel de control de aeronavegabilidad para una Socata TB 10, S/N 649, año 1988.

Este trabajo es académico. No debe utilizarse como programa real de mantenimiento ni como herramienta real de control de aeronavegabilidad.

## Documentos principales

| Documento | Uso |
|---|---|
| `Programa_Mantenimiento_ParteML2026.md` | AMP redactado para la aeronave seleccionada |
| `Control_de_aeronavegabilidad2026.xlsx` | Libro Excel funcional: Flight Log, Tasks, Life Limit Comp y ADs |
| `Anexo_2_Reportes_revision_puntos_especiales_vida_limite.md` | Índice de reportes/páginas para puntos especiales y vida límite |
| `PLAN_TRABAJO_AMP.md` | Orden de ejecución y estado de las fases |
| `guidance.md` | Guía breve para que otro agente/persona entienda el repo |
| `METODOLOGIA_PROFESOR.md` | Explicación al profesor sobre metodología, NotebookLM y dinámica de trabajo |

## Documentos de partida

| Documento | Uso |
|---|---|
| `Informacion_preliminar.md` | Notas iniciales del profesor y alcance del trabajo |
| `Guía de Elaboración AMP.md` | Procedimiento indicado por el profesor para construir el AMP y Excel |
| `Rúbrica trabajo de Mantenimiento 2026.xlsx` | Criterios de evaluación |
| `Documentacion.md` | Inventario inicial de documentos disponibles |

## Trazabilidad

La carpeta `trazabilidad/` contiene la evidencia usada para justificar los datos volcados al AMP y al Excel. La regla de trabajo fue no introducir datos técnicos relevantes sin dejar rastro de la fuente, consulta y decisión tomada.

| Archivo | Contenido |
|---|---|
| `trazabilidad/00_indice.md` | Índice de cuadernos NotebookLM, fuentes y fases |
| `trazabilidad/01_identificacion_tcds.md` | Aeronave, motor, hélice y TCDS aplicables |
| `trazabilidad/02_manuales_aplicables.md` | AMM, documentación de motor y referencia de utilización anual |
| `trazabilidad/03_programa_inspecciones.md` | Programa base de inspecciones |
| `trazabilidad/04_lubricacion_servicing.md` | Limpieza, lubricación, servicing y fluidos |
| `trazabilidad/05_puntos_especiales_lli_tbo.md` | Inspecciones especiales, TBO, LLP y ALI |
| `trazabilidad/06_ads_celula.md` | Directivas de aeronavegabilidad de célula |
| `trazabilidad/07_ads_motor.md` | Directivas de aeronavegabilidad de motor |
| `trazabilidad/08_excel_funcional.md` | Flight Log simulado y lógica de cálculo del Excel |
| `trazabilidad/09_revision_final_rubrica.md` | Revisión final contra guía y rúbrica |
| `trazabilidad/documentos_pendientes.md` | Limitaciones documentales y fuentes no bloqueantes |

## Cuadernos NotebookLM usados

| Cuaderno | ID | Uso |
|---|---|---|
| Manuales_Socata | `e9b2a1bb-aa57-45d5-8ee2-cc4e34d5f4c4` | AMM, IPC, TCDS FAA/EASA, options kit |
| Docs_motor | `4f797c56-3b53-442d-8e07-292a40231080` | Manuales y documentación del motor Lycoming |
| Directivas_motor | `c9960318-a98c-44ca-80eb-82a2eaa37645` | ADs del motor |
| Directivas_Aeronave | `38c480ef-7d81-43ab-ae7f-2d5e9c5af8bb` | ADs de célula |
| Directivas_Aeronave_no_aplicables | `4dd19a89-8f0b-4f58-a236-aadcb3967db1` | ADs de célula no aplicables añadidas al Excel |

## Limitaciones principales

- Se usa el AMM Rev. 18 porque es la documentación disponible para el trabajo.
- El TCDS EASA.A.378 Issue 05 indica AMM Rev. 19 o posterior con Chapter 4 ALS; queda documentado como limitación académica.
- No se incorporan otros Service Bulletins de aeronave o motor.
- La hélice se mantiene a nivel de identificación suficiente por indicación del profesor.
- El `Flight Log` y los cumplimientos previos del Excel son simulados.
