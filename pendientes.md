# Pendientes — sitio iatelier

## Bugs / cosas rotas

- [x] **Newsletter (index)** — Botón conectado a `armandosmh.substack.com/subscribe`. Copy actualizado.
- [x] **"Hablemos →" en cards de servicios (index)** — Apuntan a `contacto.html`. Página dedicada creada con formulario (nombre, correo, servicio, mensaje).
- [x] **Logo del nav (index)** — Apunta a `index.html`.
- [x] **Formulario de contacto (contacto.html)** — Conectado y funcionando.

## Contenido pendiente

- [x] **Página Sobre (sobre.html)** — Página personal de Armando creada. Placeholder para foto. Nav actualizado en las 5 páginas.
- [x] **Foto para sobre.html** — armando.png integrada.
- [x] **Sección Bio/Portafolio (index)** — Eliminada (HTML + CSS). Existe sobre.html para esa info.
- [x] **Nav del index** — Agregados links a Cursos, Servicios (anchor) y Hablemos (CTA). Nav consistente en las 4 páginas.
- [~] **Sistema de inscripción** — Arquitectura definida: Tally → redirect a Mercado Pago. Sección de "Próximas sesiones" ya en cursos.html. Subtareas:
  - [ ] Crear cuenta en Tally (si no existe)
  - [ ] Crear formulario-plantilla con campos: nombre, correo, organización (opcional), ¿cómo te enteraste? (opcional)
  - [ ] Configurar cierre automático por número de respuestas (25 para Fundamentos, 15 para talleres)
  - [ ] Configurar página de confirmación con redirect al link de pago
  - [ ] Conectar Tally → Google Sheets para tener registro centralizado de inscripciones
  - [ ] Crear link de pago en Mercado Pago para la primera sesión (nombre, precio, descripción)
  - [ ] Actualizar los `href="#"` en cursos.html con los links reales de Tally
  - [ ] Definir flujo de seguimiento: correo a quienes se inscriben pero no pagan en 48h
  - [ ] Definir proceso para cuando se abra una nueva fecha: qué se duplica, qué se crea nuevo
  - [ ] Probar el flujo completo de punta a punta antes de publicar
- [~] **Nivel 0 en cursos.html** — Descartado por ahora. Requisito mínimo: haber usado al menos una herramienta de IA. Se revisa cuando escale.
- [x] **Páginas de servicios** — Creadas formacion.html y aumentos.html. Cards del index actualizadas para apuntar a las nuevas páginas.
- [x] **Copy de formacion.html** — Revisado y editado.
- [x] **Copy de aumentos.html** — Revisado y editado.
- [x] **Diseño de formacion.html** — Revisado: spacing, section labels, dividers, grain, identidad visual.
- [x] **Diseño de aumentos.html** — Revisado: spacing, section labels, dividers, grain, proceso rediseñado como lista vertical.
- [ ] **Página MAIA** — Crear maia.html: explicación del marco metodológico propio. Agregar al nav.

## SEO y metadatos

- [x] **Meta description** — Mejorada en index.html y cursos.html.
- [x] **Open Graph tags** — `og:title`, `og:description`, `og:image`, `og:url` + Twitter Cards en index y cursos.
- [x] **Favicon** — Implementado (SVG + apple-touch-icon) en las 6 páginas.

## Deuda técnica (resuelta)

- [x] **Rutas de fuentes Maax** — Fuentes copiadas a `fonts/`. Rutas actualizadas en los 5 HTML.
- [x] **CSS compartido** — Extraído a `styles.css`: fonts, tokens, reset, nav, grain, utilities. Los 6 HTML lo importan.
- [x] **Limpieza JS en index** — Revisado. No había código muerto de horizontal scroll pendiente.
