# Pendientes — sitio iatelier

## Bugs / cosas rotas

- [x] **Newsletter (index)** — Botón conectado a `armandosmh.substack.com/subscribe`. Copy actualizado.
- [x] **"Hablemos →" en cards de servicios (index)** — Apuntan a `contacto.html`. Página dedicada creada con formulario (nombre, correo, servicio, mensaje).
- [x] **Logo del nav (index)** — Apunta a `index.html`.
- [ ] **Formulario de contacto (contacto.html)** — HTML listo. Conectar con Tally (embed o link) para manejar todo desde ahí junto con inscripciones.

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
- [ ] **Nivel 0 en cursos.html** — Agregar sección de cursos introductorios gratuitos: uno para Claude, uno para Gemini, uno para ChatGPT. Definir formato, contenido y si llevan inscripción o son abiertos.
- [x] **Páginas de servicios** — Creadas formacion.html y aumentos.html. Cards del index actualizadas para apuntar a las nuevas páginas.
- [ ] **Copy de formacion.html** — Revisar y editar el contenido generado.
- [ ] **Copy de aumentos.html** — Revisar y editar el contenido generado.
- [ ] **Diseño de formacion.html** — Revisar estructura visual, secciones y layout.
- [ ] **Diseño de aumentos.html** — Revisar estructura visual, secciones y layout.

## SEO y metadatos

- [x] **Meta description** — Mejorada en index.html y cursos.html.
- [x] **Open Graph tags** — `og:title`, `og:description`, `og:image`, `og:url` + Twitter Cards en index y cursos.
- [ ] **Favicon** — No hay `<link rel="icon">`. Aparece el ícono genérico del navegador.

## Para cuando haya hosting real

- [x] **Rutas de fuentes Maax** — Fuentes copiadas a `fonts/`. Rutas actualizadas en los 5 HTML.
- [x] **CSS compartido** — Extraído a `styles.css`: fonts, tokens, reset, nav, grain, utilities. Los 6 HTML lo importan.
- [x] **Limpieza JS en index** — Revisado. No había código muerto de horizontal scroll pendiente.
