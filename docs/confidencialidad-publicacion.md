# Confidencialidad y publicación

[← Casos anonimizados](casos-anonimizados.md) · [Inicio](../README.md)

## Regla

Un caso público demuestra criterio y método sin permitir reconstruir la identidad, la operación o la infraestructura de una organización.

## Lista previa a publicar

### Identidad

- [ ] No aparecen nombres de cliente, empresa, producto privado o personas.
- [ ] Nombres de archivo, capturas y metadatos tampoco los revelan.
- [ ] Sector, ubicación, fecha y función no identifican indirectamente.

### Operación

- [ ] No hay datos reales, usuarios, volúmenes ni cifras no autorizadas.
- [ ] No se publican rutas, dominios, identificadores o estructura interna.
- [ ] No se describen permisos, incidentes o vulnerabilidades explotables.
- [ ] Diseñado, probado, en desarrollo y en producción no se intercambian.

### Tecnología y afirmaciones

- [ ] No hay secretos, credenciales ni configuración.
- [ ] Código y diagramas son públicos, propios o abstractos.
- [ ] Una regla manual no se presenta como automatización.
- [ ] Cada métrica tiene fuente y autorización; si no, se elimina.
- [ ] La capacidad actual se separa de la hoja de ruta.
- [ ] Se explican límites y elementos no verificables.

### Enlaces e historial

- [ ] Los enlaces responden sin sesión.
- [ ] El historial no contiene información retirada.
- [ ] Las tarjetas de vista previa no exponen contenido antiguo.
- [ ] Descargables y SVG se revisaron como texto y visualmente.

## Patrón de anonimización

| Evitar | Preferir |
| --- | --- |
| Organización y sector específico | “Una organización” |
| Fecha exacta | “Durante la puesta en marcha” |
| Número de usuarios | “Usuarios operativos” |
| Arquitectura identificable | “Sistema de gestión” |
| Resultado cuantitativo sin fuente | Resultado cualitativo verificable |
| “La IA lo controla” | “La regla se revisa manualmente” |

## Historial limpio

Eliminar información de la versión actual no siempre la retira del historial. Si hubo material confidencial, puede ser preferible un repositorio público nuevo y anonimizado, manteniendo el original privado y respetando atribución y licencias.

## Evidencia defendible

Una formulación pública es defendible si puede explicarse en una entrevista sin revelar al cliente y existe evidencia privada legítima. La confidencialidad limita lo mostrado; no autoriza afirmaciones más amplias.
