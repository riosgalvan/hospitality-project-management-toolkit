# Estructura documental recomendada

```text
[CODIGO]_[NOMBRE-PROYECTO]/
├── 01_GESTION/
├── 02_COMERCIAL-Y-CONTRATO/
├── 03_DISENO/
├── 04_PLANIFICACION/
├── 05_EJECUCION/
├── 06_PRUEBAS/
├── 07_ENTREGA/
├── 08_OPERACION-Y-SOPORTE/
└── 99_ARCHIVO/
```

## Convención para nombres

```text
AAAA-MM-DD_TipoDocumento_Proyecto_Version_Estado.ext
```

Ejemplo ficticio:

```text
2026-09-08_InformeSemanal_HotelCostaAzul_v1.0_APROBADO.pdf
```

## Reglas básicas

- Utilizar fechas en formato `AAAA-MM-DD`.
- Evitar nombres como `final`, `final2` o `ultimo`.
- Indicar versión y estado: `BORRADOR`, `REVISION` o `APROBADO`.
- Conservar el documento editable junto a la versión distribuida.
- Mover documentos sustituidos a `99_ARCHIVO`; no eliminarlos sin autorización.
- Restringir el acceso a documentación sensible.
