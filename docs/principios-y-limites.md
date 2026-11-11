# Principios y límites

[← Inicio](../README.md) · [Siguiente: modelo operativo →](modelo-operativo.md)

## Principios de diseño

### El objetivo gobierna al agente

El trabajo empieza por un resultado observable, no por elegir una herramienta. La contribución debe relacionarse con una necesidad, una restricción y una decisión de producto.

### El contexto se selecciona

Más contexto no siempre mejora la respuesta. Cada encargo distingue:

- **fuente normativa:** obliga y prevalece;
- **fuente operativa:** describe el estado vigente;
- **referencia:** ayuda, pero no decide;
- **contenido excluido:** no debe copiarse, inferirse ni compartirse.

Si dos fuentes se contradicen, el agente registra el conflicto y aplica la precedencia acordada o solicita decisión. No lo resuelve en silencio.

### La responsabilidad tiene bordes

El alcance incluye artefactos, acciones y exclusiones. En código puede expresarse como conjunto de archivos; en producto, como procesos y decisiones; en documentación, como audiencia y fuentes permitidas.

### La evidencia vale más que la declaración

“Terminado” no explica qué cambió ni por qué puede aceptarse. Una entrega identifica diferencia realizada, criterios comprobados, resultados, riesgos residuales, elementos no verificados y forma segura de continuar o revertir.

### La supervisión sigue al riesgo

Un borrador reversible y sin datos sensibles puede usar un circuito ligero. Un cambio de permisos, datos o producción necesita autorización explícita, evidencia reforzada y rollback.

### La continuidad no depende del chat

Las decisiones, el estado y los riesgos se guardan en artefactos duraderos. La conversación ayuda a trabajar, pero no sustituye la fuente del proyecto.

## Estados de una afirmación

| Estado | Uso permitido |
| --- | --- |
| Confirmada | Puede orientar ejecución y aceptación. |
| Inferida | Puede usarse si se explica la inferencia y su impacto. |
| Pendiente | No debe convertirse silenciosamente en requisito. |
| Descartada | Se conserva solo si ayuda a explicar una decisión. |

## Lo que el método no resuelve por sí solo

- No valida una fuente que nadie ha contrastado.
- No convierte una regla escrita en bloqueo automático.
- No elimina sesgos ni errores del modelo.
- No concede permisos ni autoridad.
- No sustituye experiencia de dominio, seguridad, legal o normativa.
- No demuestra retorno económico sin medición acordada.

## Límite de publicación

Una evidencia interna puede ser necesaria para operar y no ser apta para un portafolio. La versión pública demuestra el método mediante estructura, decisiones y artefactos anonimizados; nunca necesita exponer datos del cliente, rutas, credenciales, fechas sensibles o detalles reconstruibles.

Consulta la [lista de confidencialidad](confidencialidad-publicacion.md) antes de publicar.
