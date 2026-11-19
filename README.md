# Hermanos Alvarez · Mezcal Madurado en Vidrio

Ficha de producto interactiva (piloto) para el **Mezcal Hermanos Alvarez Madurado en Vidrio**: agave cupreata, 48% Alc. Vol., 750 ml, 14 meses bajo tierra en barril de vidrio.

Desarrollada por **CAVA Estudio** a partir del portafolio comercial de la marca.

## Secciones

1. **Inicio:** marca, categoría y datos clave.
2. **Ficha técnica:** graduación (regla 35–55%) y maduración (24 meses, 14 llenos), con explicaciones desplegables.
3. **Proceso:** línea de tiempo de 8 pasos, de la jima a la maduración. La tierra sube en el escenario a medida que se avanza.
4. **Nota de cata:** vista, olfato y sabor.
5. **Quiz:** 4 preguntas en formato carta de lotería.
6. **Origen:** maestro mezcalero y sellos de certificación (DOM, NOM-070/142, IMPI, Orgullo Michoacán).

## Estructura

```
index.html            HTML + CSS + JS en un solo archivo, sin dependencias de build
assets/img/           botellas recortadas (webp), logos (png) y fotos del proceso (jpg)
assets/fonts/         DM Serif Display (licencia OFL incluida)
```

La tipografía Jost se carga desde Google Fonts.

## Ver en local

Sirve la carpeta con un servidor local (abriendo `index.html` directo como archivo, el brillo de la botella no aparece porque el navegador bloquea la máscara CSS en `file://`):

```bash
python3 -m http.server 8000
```

## Publicar con GitHub Pages

1. Sube el contenido de esta carpeta a un repositorio.
2. En **Settings → Pages**, elige la rama `main` y la carpeta `/ (root)`.
3. La ficha quedará en `https://<usuario>.github.io/<repositorio>/`.

## Pendientes del piloto

- Botella en alta resolución con fondo transparente (la actual sale del PDF, ~666 px de alto).
- Foto real del barril de vidrio enterrado (hoy es una ilustración).
- Confirmar el tiempo de maduración: el portafolio dice 14 meses y la etiqueta dice "1 Año".
- Maridaje, forma de servir y datos logísticos (cajas y pallets).
- Logo en vector.
- Versiones en inglés y portugués.

## Créditos

Fotografías, logotipo y textos de marca: Mezcal Hermanos Alvarez. Diseño y desarrollo: CAVA Estudio.
