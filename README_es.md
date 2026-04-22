<p align="center">
  <img src="assets/clawink_logo.png" alt="Clawink — OpenClaw for Business Systems" width="800" />
</p>

<p align="center">
  <strong>Clawink — OpenClaw for Business Systems</strong><br />
  Convierte sistemas de negocio complejos en una capa de producto operable por IA.
</p>

<p align="center">
  Conecta tu sistema · Publica capacidades ejecutables · Deja que la IA planifique, previsualice, confirme y ejecute trabajo real
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-Apache%202.0-blue.svg" alt="Apache 2.0 License" /></a>
  <img src="https://img.shields.io/badge/Open%20Source-Preview-black" alt="Open Source Preview" />
  <img src="https://img.shields.io/badge/Code%20Release-Planned-0A7EA4" alt="Code Release Planned" />
</p>

<p align="center">
  <a href="README.md">English</a> ·
  <a href="README_zh-CN.md">中文</a> ·
  <a href="README_ja.md">日本語</a> ·
  <a href="README_ko.md">한국어</a> ·
  <a href="README_es.md">Español</a>
</p>

<p align="center">
  <a href="#why-clawink-es">Por qué Clawink</a> ·
  <a href="#highlights-es">Puntos clave</a> ·
  <a href="#architecture-es">Arquitectura</a> ·
  <a href="#from-connection-to-control-es">De la conexión a la operación</a> ·
  <a href="#teams-and-scenarios-es">Equipos</a> ·
  <a href="#status-es">Estado actual</a> ·
  <a href="#roadmap-es">Hoja de ruta</a> ·
  <a href="#community-es">Comunidad</a>
</p>

---

<a id="why-clawink-es"></a>

## Por qué Clawink

La mayoría de los sistemas de negocio no fallan por falta de funciones. Fallan por la fricción de uso.

Los usuarios suelen tener que entender menús, flujos, permisos y reglas operativas antes de poder aprovechar realmente el sistema. Clawink no pone otra interfaz de chat encima de esa complejidad. Organiza la capacidad del sistema como una capa operable por IA para que la gente pase de "primero aprender el sistema" a "expresar directamente el objetivo".

Clawink se apoya en dos líneas coordinadas:

- Línea de planificación: lee documentación, estructura capacidades, propone flujos, los valida y publica activos listos para runtime.
- Línea conversacional: consume solo activos ya publicados durante la conversación y no recompone toda la capacidad en cada mensaje.

Por eso Clawink no es solo una carcasa de chat. Es una capa operativa para sistemas de negocio reales.

<a id="highlights-es"></a>

## Puntos clave

Si quieres captar primero las diferencias principales de Clawink, empieza por estas tres:

<table>
  <tr>
    <td valign="top" width="33%">
      <strong>Arquitectura de dos líneas</strong><br />
      La línea de planificación genera y publica activos listos para runtime. La línea conversacional consume solo activos ya publicados.
    </td>
    <td valign="top" width="33%">
      <strong>Vía rápida para sistemas existentes</strong><br />
      No hace falta reconstruir desde cero toda una capa de producto con IA. Conecta Clawink a tu sistema actual y aprovecha antes la base de OpenClaw.
    </td>
    <td valign="top" width="33%">
      <strong>Ejecución controlada y observable</strong><br />
      Las acciones de alto riesgo siguen `preview -> confirm -> submit`, mientras la traza de ejecución y la revisión de resultados siguen visibles.
    </td>
  </tr>
</table>

<a id="architecture-es"></a>

## Arquitectura

La línea de planificación genera activos revisados. La línea de ejecución usa solo activos publicados y ejecuta bajo reglas de previsualización, confirmación y control operativo.

<p align="center">
  <img src="assets/clawink_arch_en.png" alt="Clawink architecture diagram" width="1400" />
</p>

<a id="from-connection-to-control-es"></a>

## De la conexión a la operación

1. **Conectar el sistema**: importa Swagger, OpenAPI o Markdown y completa la autenticación para llegar a capacidades reales.
2. **Publicar activos operativos**: convierte APIs, acciones de página y dependencias de negocio en flujos y activos de capacidad listos para runtime.
3. **Dejar que la IA opere**: los usuarios expresan objetivos y Clawink se encarga del enrutamiento, la vista previa, la confirmación, la ejecución y el resultado.

## Lo que realmente obtienes

- **Un espacio de trabajo de IA capaz de asumir sistemas de negocio**: conexión, planificación, ejecución, autenticación, observabilidad y gobierno en una misma superficie.
- **Una capa de producto para usuarios reales**: el usuario expresa un objetivo y Clawink lo traduce en consultas, ejecuciones y resultados del sistema.
- **Una consola operativa para equipos de negocio**: el resultado de la planificación queda como flujos, activos, estados de publicación y registros, no como prompts aislados.
- **Una base estable para equipos de ingeniería**: puedes ampliar modelos, Skills, MCP e integraciones sin rehacer la cadena principal de ejecución.

<a id="teams-and-scenarios-es"></a>

## Equipos y escenarios

- **Equipos de producto**: quieren convertir un back office, una herramienta interna o un SaaS en un producto de IA conversacional y ejecutable.
- **Equipos con UX compleja**: quieren que los usuarios expresen objetivos sin aprender menús, flujos y reglas operativas complicadas.
- **Equipos de plataforma e integración**: quieren concentrar varios sistemas, paneles administrativos y APIs en una sola entrada operativa con IA.
- **Equipos orientados a la ejecución**: quieren llevar la IA más allá de explicar el sistema y permitirle consultar, previsualizar, confirmar y ejecutar.
- **Equipos de entrega y gobierno**: quieren mantener control de riesgo, autenticación, visibilidad y trazabilidad mientras la IA realiza trabajo real.

<a id="status-es"></a>

## Estado actual

Este repositorio es la vista previa pública de Clawink.

- Por ahora publica la visión del producto, la arquitectura, la hoja de ruta y los recursos de marca.
- El runtime principal y el código del producto siguen en el repositorio interno mientras el modelo del producto termina de estabilizarse.
- La liberación pública del código llegará por etapas mediante una sincronización unidireccional desde el repositorio interno.

En otras palabras, Clawink avanza hacia el código abierto, pero este repositorio todavía no es la liberación pública completa.

<a id="roadmap-es"></a>

## Hoja de ruta

La apertura del proyecto se plantea en cuatro etapas:

1. Vista previa pública: README, arquitectura, hoja de ruta y recursos de marca.
2. Núcleo público: módulos seleccionados de runtime, empaquetado y flujo mínimo para desarrolladores.
3. Superficie de extensión pública: algunos Skills, ejemplos de integración y documentación para extensiones externas.
4. Apertura más amplia: ampliar gradualmente los módulos públicos y reforzar CI y colaboración comunitaria.

Consulta [ROADMAP.md](ROADMAP.md) para ver el plan actual.

<a id="community-es"></a>

## Comunidad

- Sigue el repositorio para enterarte de los hitos de apertura.
- Usa Issues y Discussions para compartir escenarios, necesidades de integración y feedback.
- Consulta [CONTRIBUTING.md](CONTRIBUTING.md) para ver cómo colaborar durante esta etapa de vista previa.
- Para temas de seguridad, sigue el proceso de reporte privado descrito en [SECURITY.md](SECURITY.md).
- Antes de planificar una adopción real, toma como referencia la hoja de ruta y las publicaciones oficiales.
