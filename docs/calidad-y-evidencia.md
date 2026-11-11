# Calidad y evidencia

[← Modelo operativo](modelo-operativo.md) · [Inicio](../README.md) · [Riesgo y control humano →](riesgo-control-humano.md)

## De criterio a evidencia

| Criterio | Evidencia adecuada | Evidencia insuficiente |
| --- | --- | --- |
| Un enlace público funciona | Respuesta sin sesión y destino revisado | “Parece correcto” |
| Un documento conserva su diseño | Render o captura inspeccionada | El archivo se generó |
| Una regla se aplica | Prueba del escenario y su excepción | La regla aparece en el prompt |
| No se exponen secretos | Escáner más revisión de contenido y cambios | Una sola búsqueda |
| Un texto es publicable | Lista de confidencialidad completada | No nombra al cliente |

## Modelo de evidencia

```yaml
resultado: qué quedó disponible
alcance: qué se cambió y qué no
fuentes: qué gobernó la decisión
comprobaciones:
  - criterio: condición esperada
    metodo: prueba, inspección o revisión
    resultado: aprobado, rechazado o no verificado
riesgos_residuales: límites que permanecen
aprobacion: quién debe decidir y en qué estado está
continuidad: siguiente paso seguro
```

Los nombres pueden adaptarse a la herramienta. Lo importante es evitar una evidencia que solo diga “hecho”.

## Puertas de calidad

### Preparación

- objetivo observable, fuentes y alcance;
- riesgo, reversibilidad y criterio de aceptación.

### Ejecución

- cambios dentro del alcance y supuestos declarados;
- protección del trabajo ajeno y ausencia de datos innecesarios.

### Revisión

- correspondencia entre resultado y necesidad;
- coherencia técnica y documental;
- pruebas pertinentes y riesgos residuales;
- diferencia explícita entre política y control real.

### Aceptación

- evidencia comprensible;
- excepciones visibles;
- aprobación acorde al riesgo;
- traspaso y rollback cuando procedan.

## Matriz de controles

| Control | Regla escrita | Control mecánico | Verificación humana | Evidencia |
| --- | --- | --- | --- | --- |
| Alcance de archivos | Sí/No | Sí/No/Parcial | Sí/No | Enlace o registro |
| Datos sensibles | Sí/No | Sí/No/Parcial | Sí/No | Escáner y revisión |
| Criterios funcionales | Sí/No | Sí/No/Parcial | Sí/No | Prueba o acta |
| Publicación | Sí/No | Sí/No/Parcial | Sí/No | Lista completada |

“Parcial” debe explicar qué cubre el mecanismo y qué queda al juicio humano.

## Revisión eficaz

Empieza por la intención, diferencia bloqueantes de mejoras, cita el criterio, presenta evidencia, reconoce lo no comprobado y evita reescribir sin registrar el cambio. Usa la [plantilla de revisión](../templates/revision.md).

## Evidencia pública e interna

La evidencia interna puede incluir registros detallados dentro de la política del proyecto. La pública debe ser mínima y anonimizada. Para demostrar capacidad basta con mostrar anatomía, tipos de control, decisiones abstractas y validación; no datos productivos.
