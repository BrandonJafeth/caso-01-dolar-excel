# Caso 1 · ¿Cuándo conviene comprar dólares?

> **Pregunta:** ¿En qué meses el dólar suele estar más caro o más barato en Costa Rica?
> **Respuesta corta:** [pendiente]

Caso publicado en: https://datos.brandoncarrillo.dev/casos/dolar-excel

## Datos

| Fuente | Qué se usó | Descargado el | Licencia |
|---|---|---|---|
| BCCR | Tipo de cambio de referencia compra/venta, diario | 2026-11-19 | Términos de uso del BCCR: uso personal, empresarial u organizacional sin alterar el contenido; citar la fuente |

Los archivos originales no están en el repo. Para reproducir, descargalos en `data/raw/` según `fuentes.md`.

## Cómo reproducirlo

```
uv sync
uv run jupyter lab
```

Abrí los notebooks en orden (`notebooks/01-...`, `02-...`) y ejecutá **Kernel → Restart Kernel and Run All Cells**.

## Estructura

```
data/raw/         datos originales, sin tocar (no se suben)
data/processed/   datos limpios que generan los scripts
sql/              consultas y scripts de base de datos
notebooks/        exploración y análisis, en orden
src/              código reutilizable (limpieza, conexión a la base)
reports/          resultados finales: JSON para el sitio, gráficos, memo
```

## Hallazgos

1. [Hallazgo 1]
2. [Hallazgo 2]
3. [Hallazgo 3]

## Limitaciones

- [Qué no cubren los datos o qué supuestos se hicieron]

---
Brandon Carrillo Álvarez · [LinkedIn](https://www.linkedin.com/in/brandonca/) · [Portafolio](https://datos.brandoncarrillo.dev)
