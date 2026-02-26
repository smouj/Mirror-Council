# Mirror Council

[![Language: English](https://img.shields.io/badge/Language-English-blue.svg)](README.md)
[![Idioma: Español](https://img.shields.io/badge/Idioma-Espa%C3%B1ol-green.svg)](README.es.md)

Skill especializada para operaciones de **multi-agent** en entornos multiagente (OpenClaw/KiloCode).

## Descripción general

Mirror Council permite ejecutar tareas de multi-agent con un flujo seguro, reproducible y trazable.

## Cuándo usar

- Necesitas ejecución estructurada en el dominio **multi-agent**.
- Quieres resultados reproducibles (plan, verificación y rollback).
- Necesitas guardrails explícitos de seguridad y control del operador.

## Capacidades principales

- Activación por triggers para escenarios de multi-agent.
- Flujo de 4 pasos (análisis, planificación, ejecución, validación).
- Formato de salida estandarizado para operación y reporte.
- Guardrails security-first.

## Entradas

- Objetivo y alcance
- Entorno/contexto (repo, VPS, servicio, etc.)
- Restricciones y tolerancia al riesgo

## Salidas

- Resumen operativo
- Plan aplicado
- Cambios realizados
- Evidencia de verificación
- Pasos de rollback
- Riesgo residual

## Archivos

- `SKILL.md` → Especificación en inglés
- `SKILL.es.md` → Especificación en español
- `README.md` → Documentación en inglés
- `README.es.md` → Documentación en español

## Límites y guardrails

- Nunca exponer secretos.
- Nunca ejecutar acciones destructivas sin confirmación explícita.
- Preferir cambios mínimos y reversibles.

## Troubleshooting

1. Verificar acceso a herramientas/autenticación.
2. Revalidar alcance y conectividad del entorno.
3. Reducir a cambio mínimo seguro.
4. Reintentar con comandos de verificación explícitos.

## Ejemplo rápido

**Input:** "Audita y mejora el flujo de multi-agent."

**Salida esperada:**
- Alcance + plan
- Ejecución segura
- Comandos de verificación
- Procedimiento de rollback
