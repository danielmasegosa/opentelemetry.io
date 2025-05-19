---
title: Señales
description: Aprende sobre las categorías de telemetría soportadas por OpenTelemetry
aliases: [data-sources, otel-concepts]
weight: 11
default_lang_commit: c370886c9926e6cab3738ababbf6ff5692899bbd
---

El propósito de OpenTelemetry es recolectar, procesar y exportar [señales][signals].
Las Señales son salidas del sistema que describen la actividad subyacente del
sistema operativo y aplicaciones corriendo en una plataforma. Una señal puede ser
algo que quieras medir en un punto específico de tiempo, como la temperatura,
el uso de memoria o un evento que vaya a través de los componentes de tu sistema
distribuido que te gustaría trazar. Puedes agrupar diferentes señales juntas
para observar el funcionamiento interno de la misma pieza de tecnología desde diferentes
ángulos.

OpenTelemetry actualmente soporta:

- [Trazas](traces)
- [Métricas](metrics)
- [Logs](logs)
- [Baggage](baggage)

Bajo desarrollo o en etapa de [propuesta][proposal]:

- [Eventos][Events], un tipo específico de [log](logs)
- [Profiles] está bajo el trabajo del Profiling Working Group.

[Events]: /docs/specs/otel/logs/data-model/#events
[Profiles]:
  https://github.com/open-telemetry/opentelemetry-specification/blob/main/oteps/profiles/0212-profiling-vision.md
[proposal]:
  https://github.com/open-telemetry/opentelemetry-specification/tree/main/oteps/#readme
[signals]: /docs/specs/otel/glossary/#signals
