# Dalton Pacífico — Documentación de tokens

Documentación didáctica del sistema de design tokens **Dalton Foundations 2.0**, mostrando la migración del sistema anterior (*as is*) al nuevo (*to be*) basado en super tokens.

## Contenido

| Archivo | Descripción |
|---|---|
| `index.html` | Guía didáctica: de colores sueltos a super tokens en capas (as is → to be). |
| `documentacion-tokens.html` | Catálogo completo de las 10 colecciones de variables, con casos de uso tomados de las descripciones reales de cada token en Figma. |

## La arquitectura en 3 capas

1. **Primitivos** (`number-scale`, `color-prim`, `typography-prim`) — la materia prima.
2. **Semánticos** (`spacing`, `radius`, `stroke`, `devices`, `color-sem`, `typography-sem`) — los roles con propósito. **Esta es la capa que usan los diseñadores.**
3. **Componentes** (`color-comp`) — las piezas listas que heredan de la capa semántica.

## Ver en línea (GitHub Pages)

Una vez subido el repositorio, activa GitHub Pages en **Settings → Pages → Source: `main` / root**. El sitio quedará disponible en:

```
https://<tu-usuario>.github.io/dalton-pacifico/
```

## Fuente

Los valores y descripciones se extrajeron directamente de las variables del archivo de Figma **Dalton Foundations 2.0** vía la API de Figma.
