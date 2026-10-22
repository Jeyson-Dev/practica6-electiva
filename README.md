# Foro 6 - Servidor web nginx con Docker Compose

Servidor web nginx corriendo localmente con Docker Compose, sirviendo el contenido del directorio `src`.

## Estructura

```
.
├── docker-compose.yml
└── src/
    └── index.html
```

El directorio `src` se monta como volumen en `/usr/share/nginx/html` dentro del contenedor.

## Uso

```bash
docker compose up -d
```

Abrir en el navegador: http://localhost:8080

Para detener:

```bash
docker compose down
```
