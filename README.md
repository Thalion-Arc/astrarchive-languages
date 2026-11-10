# Astrarchive · idiomas

Archivos que la app Astrarchive baja una sola vez, cuando quien la usa elige un idioma. No hay datos de
usuarios: solo los textos de la app traducidos y los textos impresos oficiales de las cartas.

Cada Release trae:

- `catalog.json`: qué hay publicado y en qué versión (`format`, `packs` y `cardTexts`).
- `impresos-<idioma>.sqlite`: los textos impresos de las cartas en ese idioma, por edición, armados desde
  los datos públicos de [Scryfall](https://scryfall.com).
- `<idioma>.json`: los textos de la app y de los combos en ese idioma (cuando estén listos).

La app siempre lee el último Release (`releases/latest/download`), así que cada Release nuevo tiene que
traer **todos** los archivos, no solo los que cambiaron.

Magic: The Gathering y los textos de sus cartas son propiedad de Wizards of the Coast. Astrarchive no está
afiliada a Wizards of the Coast.
