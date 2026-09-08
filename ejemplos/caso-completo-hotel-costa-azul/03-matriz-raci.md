# Matriz RACI — Hotel Costa Azul

## Leyenda

- **R:** ejecuta la actividad.
- **A:** responde por el resultado y aprueba.
- **C:** debe ser consultado.
- **I:** debe mantenerse informado.

| Actividad | Dirección | Jefe de proyecto | TI hotel | Dirección de obra | Líder técnico | Instalación | Compras |
|---|---|---|---|---|---|---|---|
| Aprobar objetivo y presupuesto | A | R | C | C | I | I | I |
| Confirmar alcance | A | R | C | C | C | I | I |
| Validar diseño | I | R | A | C | R | C | I |
| Coordinar acceso a zonas | I | C | I | A/R | I | C | I |
| Confirmar material | I | A | C | I | C | I | R |
| Preparar cuartos técnicos | I | A | C | R | C | R | I |
| Instalar infraestructura | I | A | C | C | R | R | I |
| Aprobar interrupciones | I | R | A | C | C | I | I |
| Ejecutar pruebas | I | A | C | I | R | R | I |
| Resolver incidencias técnicas | I | A | C | C | R | R | C |
| Elaborar documentación final | I | A/R | C | I | R | C | I |
| Formar al equipo de operación | I | A | R | I | R | C | I |
| Aceptar el proyecto | A | R | C | I | C | I | I |

## Comprobaciones realizadas

- Cada actividad tiene un único `A`.
- Todas las actividades tienen al menos un `R`.
- La aprobación de una interrupción corresponde a TI del hotel, no al instalador.
- Dirección interviene en alcance y cierre, pero no en decisiones técnicas diarias.
