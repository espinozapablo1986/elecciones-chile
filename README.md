# Chile Vota — Atlas Presidencial 1989–2025

Web interactiva y estática sobre elecciones presidenciales chilenas entre 1989 y 2025.

## Publicar y compartir

**Netlify Drop:** ingresa a https://app.netlify.com/drop y arrastra la carpeta `elecciones_chile_web` (o un ZIP de su contenido descomprimido). Netlify genera un enlace público. El sitio es 100% estático y no necesita backend.

**GitHub Pages:** crea un repositorio público, sube `index.html` a la raíz, activa Settings → Pages → Deploy from a branch (main / root). La dirección resultante permite compartir los comparadores configurados mediante los parámetros en el `#` de la URL.

**Uso local:** abre `index.html` con cualquier navegador. Se puede utilizar sin servidor y sin conexión a Internet; solamente los enlaces a las fuentes necesitan acceso a Internet. El botón "Compartir" requiere publicar el sitio en una dirección HTTPS para producir un enlace compartible.

## Funciones

- Evolución de bloques políticos en primera vuelta, en modo amplio y desagregado.
- Gráficos de líneas y barras apiladas.
- Comparador de dos elecciones, configurable.
- Archivo de 55 candidaturas y nueve comicios.
- Línea de tiempo de gobiernos.
- Participación electoral y cambios normativos.
- Exportación de datos a CSV y gráficos a PNG.
- Compartir vista: los parámetros de comparación quedan guardados en la URL.
- Diseño responsive, accesible y sin dependencias externas.

## Metodología

Los resultados por candidatura están tomados de compilaciones del TRICEL, Servel, BCN y el Observatorio de Historia y Política de la PUCV. La serie histórica de participación anterior a 2025 reproduce la metodología de DecideChile, y no equivale a las tasas históricas sobre inscritos.

**Las familias políticas son una clasificación analítica elaborada para el sitio; no son categorías oficiales del escrutinio.** Los bloques amplios suman izquierda + centroizquierda y derecha + centroderecha. Centro y candidaturas transversales se reportan por separado. Los porcentajes de bloque se calculan a partir de porcentajes individuales redondeados. Balotajes no se mezclan con primeras vueltas.

Última actualización editorial: 13 de noviembre de 2026.

## Fuentes

- https://tribunalcalificador.cl/resultados_de_elecciones/
- https://www.bcn.cl/siit/elecciones_historicas/eleciones.html?tipo=Presidenciales
- https://www.bcn.cl/leychile/Navegar/imprimir?idNorma=1219231&idVersion=2025-12-02
- https://tribunalcalificador.cl/wp-content/uploads/2026/01/Sent-de-proclamacion.pdf
- https://observatoriohp.cl/2021/09/16/887/
- https://www.decidechile.cl/api/media/file/2daVuelta_Informe1512.pdf
