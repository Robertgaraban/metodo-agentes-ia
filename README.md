# Método de trabajo con agentes de IA

Construyo y documento sistemas con agentes de IA organizados por roles. Esta ficha describe el método. No presenta a los agentes como sustitutos de la responsabilidad humana ni describe funcionalidades de IA para usuarios finales.

## Roles

Coordinación, ejecución, revisión, pruebas y documentación. Cada rol tiene instrucciones, límites, fuentes autorizadas, archivos bajo su responsabilidad y un formato de entrega.

## Cómo circula un encargo

1. El encargo se registra con su alcance y sus criterios de aceptación.
2. Se asignan el dominio, el artefacto y los límites de cada especialista.
3. Un rol ejecuta y otro distinto revisa cuando el riesgo lo requiere.
4. Las puertas de calidad —pruebas, revisión y comprobaciones del resultado— deciden si la entrega pasa.
5. Lo que toca datos reales o producción necesita aprobación humana, copia previa y una vía para volver atrás.
6. Las decisiones, riesgos y evidencias quedan vinculados al encargo.

## Dónde lo he usado

- En el desarrollo de ABYSS, durante mi etapa en el proyecto.
- En un pipeline documental Markdown → PDF/DOCX.
- En un sistema de gestión para una organización, confidencial, en producción con datos reales.
- En la organización y revisión de conocimiento técnico y documentación pública.

## Estado

Es mi forma habitual de organizar el trabajo. Los agentes son herramientas de investigación, desarrollo, revisión y documentación. El agente de IA integrado en el producto del proyecto confidencial está en desarrollo y no forma parte de esta ficha.

## Ejemplos anonimizados

### Ficha pública de un sistema confidencial

- **Criterio de aceptación:** explicar alcance, arquitectura y papel desempeñado sin publicar cliente, dominio, infraestructura, código ni datos.
- **Resultado de revisión:** se creó una ficha pública en un repositorio con historial limpio y se comprobó la ausencia de identificadores sensibles.

### Saneamiento de una presencia pública

- **Criterio de aceptación:** retirar afirmaciones sin respaldo y alinear texto visible, metadatos y datos estructurados.
- **Resultado de revisión:** especialistas con archivos separados corrigieron contenido y otro control verificó términos bloqueantes, sintaxis y consistencia.

### Cambio técnico con datos reales

- **Criterio de aceptación:** ejecutar por lotes controlados, con copia previa, comprobaciones de integridad y una vía de reversión.
- **Resultado de revisión:** el cambio solo se acepta cuando quedan registrados el resultado, los riesgos y el siguiente paso.

## Límites

Este método no demuestra que todos los proyectos usen IA para sus usuarios finales. Tampoco delega en un modelo las decisiones sobre datos personales, producción o aceptación final.

## Autor

Robert Garabán — Consultor de IA aplicada y Product Owner.

[Perfil profesional](https://www.linkedin.com/in/robertgaraban/)
