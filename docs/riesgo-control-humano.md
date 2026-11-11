# Riesgo y control humano

[← Calidad y evidencia](calidad-y-evidencia.md) · [Inicio](../README.md) · [Casos anonimizados →](casos-anonimizados.md)

## Clasificación práctica

| Nivel | Ejemplos | Operación | Aprobación |
| --- | --- | --- | --- |
| Bajo | Borrador local, análisis reversible | Revisión ligera | Según política |
| Medio | Comunicación pública, integración reversible | Pruebas y revisión separada | Producto o dominio |
| Alto | Datos reales, permisos, migraciones | Rollback y revisión técnica y funcional | Humana explícita |
| Crítico | Seguridad, obligación normativa, pérdida irreversible | Plan formal y doble control | Autoridad designada |

El nivel se determina por impacto y reversibilidad, no por tamaño.

## Decisiones que no se delegan en silencio

- ampliar alcance o usar una fuente no autorizada;
- publicar información de una organización o persona;
- cambiar permisos, credenciales o acceso;
- borrar, migrar o transformar datos sin recuperación;
- ejecutar en producción;
- enviar mensajes o candidaturas en nombre de alguien;
- aceptar riesgos legales, normativos o de seguridad;
- afirmar resultados sin respaldo.

## Privacidad por diseño

1. **Minimizar:** aportar solo lo necesario.
2. **Separar:** conservar fuentes privadas fuera de artefactos públicos.
3. **Anonimizar:** eliminar nombres, fechas, rutas e identificadores reconstruibles.
4. **Limitar retención:** no duplicar originales ni evidencia sensible.
5. **Revisar salida:** buscar exposición directa e indirecta.

## Coste y proporcionalidad

Se controla con encargos cortos, fuentes seleccionadas, reutilización de decisiones, paralelismo útil, límites de iteración, escalado justificado y cierre cuando la evidencia es suficiente. El presupuesto puede ser tiempo, iteraciones, consumo o dinero y debe guardar relación con valor y riesgo.

## Reversibilidad

Antes de una acción de riesgo alto se identifica el estado inicial, se define y comprueba recuperación, se fijan señales de fallo y responsable de detener, se decide qué ocurre con datos creados y se obtiene aprobación. Si no existe recuperación razonable, el nivel de riesgo aumenta.

## Fallo seguro

Ante fuentes ausentes, permisos fallidos o evidencia contradictoria, se detiene la acción material y continúa el diagnóstico seguro. “No puedo verificar” no significa “no funciona”; la falta de permiso nunca autoriza otra vía.
