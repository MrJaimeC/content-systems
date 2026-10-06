# Content Systems

Repositorio privado para guardar el sistema editorial de Jaime: briefs de carruseles, newsletters, runbooks y assets de referencia.

## Que contiene

- `carousel-briefs/`: briefs historicos de carruseles y decisiones editoriales.
- `drafts/` y `newsletter-drafts/`: borradores HTML y textos de newsletters.
- `assets/`: imagenes de referencia usadas para mantener estilo visual y branding.
- `jaime-carousel-leadmagnet-runbook.md`: proceso de carruseles y lead magnets.
- `jaime-newsletter-runbook.md`: proceso de newsletter.
- `carousel-news-blacklist.md`: temas o URLs recientes para evitar repeticion.
- `carousel-delivery-config.json`: configuracion operativa de entrega.

## Que no debe contener

- Credenciales, tokens, claves API o codigos de acceso.
- `.env` o ficheros equivalentes con secretos.
- Outputs pesados: ZIPs, PDFs finales, videos, carpetas `outbox/` o `generated/`.
- Bases de datos locales, caches, logs o temporales.

## Uso

Este repo sirve como copia versionada del conocimiento editorial, no como almacen final de entregables.

Flujo recomendado:

1. Actualizar briefs, runbooks o reglas editoriales aqui.
2. Mantener los paquetes finales en Drive o en `outbox/` local.
3. Subir solo material fuente util para reproducir el sistema.
4. Revisar secretos antes de cada push.

## Identidad de commits

Los commits deben atribuirse a la cuenta personal de Jaime:

```text
Jaime Cabadas <164075036+MrJaimeC@users.noreply.github.com>
```

Esto permite que GitHub cuente las contribuciones en `MrJaimeC` sin exponer el email personal.
