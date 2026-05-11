# Guidance para agentes

Trabajo: elaborar un Programa de Mantenimiento Aprobado (AMP) Parte-ML y un libro Excel de control de aeronavegabilidad para una DAHER AEROSPACE / Socata TB-10, S/N 649, ano 1988.

Documentos principales del repo:
- `Programa_Mantenimiento_ParteML2026.md`: AMP a rellenar.
- `Control_de_aeronavegabilidad2026.xlsx`: Excel funcional a completar.
- `Informacion_preliminar.md`: enunciado y datos iniciales.
- `Guía de Elaboración AMP.md`: metodologia del profesor.
- `Documentacion.md`: inventario inicial de fuentes en NotebookLM.

Cuaderno principal NotebookLM:
- Nombre: `Manuales_Socata`
- ID: `e9b2a1bb-aa57-45d5-8ee2-cc4e34d5f4c4`
- Uso: consultar manuales largos mediante `nlm notebook query`, reportes o tablas.

Cuadernos adicionales:
- `Docs_motor`: `4f797c56-3b53-442d-8e07-292a40231080`
- `Directivas_motor`: `c9960318-a98c-44ca-80eb-82a2eaa37645`
- `Directivas_Aeronave`: `38c480ef-7d81-43ab-ae7f-2d5e9c5af8bb`

Reglas de trabajo:
- No rellenar datos tecnicos sin fuente trazada.
- Guardar cada extraccion relevante en `trazabilidad/`.
- Indicar documento, pagina/seccion, consulta usada y decision tomada.
- Si falta una fuente, anadirla a `trazabilidad/documentos_pendientes.md`.
- Mantener coherencia exacta entre AMP y Excel.
- No hacer todo en una tirada: avanzar por fases y parar ante bloqueos reales.
- Usar `uv` para cualquier gestion de dependencias Python.
- Motor fijado: Textron Lycoming O-360-A1AD; no considerar SB de motor ni aeronave.
- Helice: mantener una unica referencia suficiente; no profundizar salvo orden expresa.

Fases principales:
1. Identificacion: aeronave, motor, helice, TCDS y aplicabilidad.
2. Manuales aplicables: AMM, motor, helice, SB/SIL, revision y fecha.
3. Programa base: inspecciones programadas y tolerancias.
4. Servicing: limpieza, lubricacion, fluidos y ATA 12.
5. Especiales/LLP/TBO: puntos especiales, vida limite y overhaul.
6. ADs: celula y motor, aplicables y no aplicables justificadas.
7. Sincronizacion final AMP/Excel y revision contra rubrica.
