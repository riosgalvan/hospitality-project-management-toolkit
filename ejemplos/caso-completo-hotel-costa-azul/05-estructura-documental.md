# Estructura documental — Hotel Costa Azul

## Carpeta principal

```text
HTL-2026-001_HotelCostaAzul_RivieraMaya/
├── 00_CONTROL_DEL_PROYECTO/
├── 01_OFERTA_Y_CONTRATO/
├── 02_DISENO_Y_DOCUMENTACION/
├── 03_PROVEEDORES_Y_COMPRAS/
├── 04_EJECUCION_Y_OBRA/
├── 05_COSTOS_Y_FACTURACION/
├── 06_INFORMES_Y_CALIDAD/
├── 07_CIERRE_Y_GARANTIA/
└── 99_ARCHIVO/
```

La estructura se mantiene deliberadamente compacta. Solo se añaden subcarpetas cuando el volumen real lo justifica.

## Contenido principal

| Carpeta | Contenido |
|---|---|
| `00_CONTROL_DEL_PROYECTO` | Acta, planificación, RACI, RAID, pendientes y cambios |
| `01_OFERTA_Y_CONTRATO` | Alcance contratado, anexos y aprobaciones comerciales |
| `02_DISENO_Y_DOCUMENTACION` | Planos, diseño, criterios y versiones aprobadas |
| `03_PROVEEDORES_Y_COMPRAS` | Pedidos, entregas, ofertas e inventario recibido |
| `04_EJECUCION_Y_OBRA` | Plan de zonas, avances, fotografías autorizadas y partes |
| `05_COSTOS_Y_FACTURACION` | Control económico con acceso restringido |
| `06_INFORMES_Y_CALIDAD` | Informes semanales, pruebas y evidencias |
| `07_CIERRE_Y_GARANTIA` | Entrega, formación, garantías y aceptación |
| `99_ARCHIVO` | Versiones sustituidas o anuladas |

## Convención de nombres

```text
AAAA-MM-DD_TIPODOC_Descripcion_vNN_ESTADO.ext
```

Ejemplos:

```text
2026-09-07_ACTA_InicioProyecto_v01_APROBADO.pdf
2026-10-16_INF_SeguimientoSemanal_v01_EMITIDO.pdf
2026-11-27_PRU_ResultadosValidacion_v02_APROBADO.xlsx
2026-12-04_ACTA_CierreProyecto_v01_APROBADO.pdf
```

## Estados documentales

- `BORRADOR`: en preparación.
- `REVISION`: enviado para comentarios.
- `APROBADO`: versión autorizada.
- `SUSTITUIDO`: reemplazado por otra versión y movido a archivo.

## Control de acceso

- Dirección económica: acceso a costes y contratos.
- TI y equipo técnico: acceso a diseño, pruebas e inventario.
- Equipo ampliado: acceso a planificación e informes sin información sensible.
- No se almacenan contraseñas en esta estructura documental.
