# Suikogaiden Vol.2: Duelo en Crystal Valley — Traducción al español

Traducción de fans, no oficial y apoyada con IA, al español de **Gensou Suiko Gaiden Vol.2:
Crystal Valley no Kettou** («Duelo en Crystal Valley», PlayStation, Konami 2001, SLPM-866.63),
la segunda parte de la novela visual de Nash Latkje. Continuación de la
[traducción de Vol.1](https://fjveralv.github.io/Traduccion_esp_Suikogaiden1/), con las mismas
herramientas y el mismo glosario.

**Versión 1.1: traducción completa** — las 8.078 líneas de las 46 escenas, los menús del sistema,
la pantalla de título, las tarjetas de episodio y la ayuda de la galería de imágenes están en
español.

➡️ **[Ver la página del proyecto](https://fjveralv.github.io/Traduccion_esp_Suikogaiden2/)**

## Descargar el parche

El parche está en [`parche/Suikogaiden2_ES.v1.1.ppf`](parche/Suikogaiden2_ES.v1.1.ppf) (formato
**PPF 3.0**). `parche/Suikogaiden2_ES.ppf` es siempre la última versión, y la misma copia se publica
en `docs/` para la web. Instrucciones en
[`parche/LEEME.txt`](parche/LEEME.txt).

El juego solo salió en Japón. El parche se aplica sobre el disco japonés **con el parche inglés de
la comunidad ya aplicado**, en `.bin/.cue` RAW (no `.iso`):

| | |
|---|---|
| Imagen de origen | `Gensou Suiko Gaiden Vol. 2 (Eng. Patched).bin` |
| MD5 | `F3A6A6B2BB8925E1876703D089558280` |
| SHA-1 | `221284DBCA176F32E6BC372527F84DEC032B619A` |
| SHA-1 del resultado | `918635EF26817F0767D652749CB493F01AFF5731` |

1. Haz una copia de tu `.bin` en inglés.
2. Aplica `Suikogaiden2_ES.v1.1.ppf` con **PPF-O-Matic** o **MultiPatch** (comprueban que el disco es el
   correcto).
3. Carga el `.cue` apuntando al `.bin` parcheado en tu emulador.

Este proyecto **no distribuye ninguna imagen ni archivo del juego original**.

## Qué está traducido

- Diálogos y narración (`DATA/SCRIPT.R2`): 46 escenas, 8.078 líneas.
- Fuente con `á é í ó ú ü ñ ¿ ¡ Á É Í Ó Ú Ñ`, dibujadas en huecos libres de la fuente inglesa.
- Menús y sistema (ejecutable `SLPM_866.63`): guardar/cargar, tarjeta de memoria, opciones,
  velocidad del texto, importación de datos de Suikogaiden Vol.1 y de Suikoden I/II, títulos de
  episodio de las partidas.
- Pantalla de título: «PULSA START», menú «NUEVA / CONTINUAR / ESPECIAL» y subtítulo
  «Duelo en Crystal Valley».
- Tarjetas de episodio: «Episodio 1 『Orgullo』», «Episodio 2 『Caleria』»,
  «Episodio 3 『Dragón feroz』», «Episodio final 『La verdad final』», «Fin.», «Hasta pronto.».
- Ayuda de la galería de imágenes (`DATA/SYS.Z2` → `PART00.TIM`): «→:SIGUIENTE / ←:ATRÁS /
  ○:VER CG / X:SALIR / □:OCULTAR», con las letras del original y S, V y tildes dibujadas en el
  mismo estilo.
- Sin traducir (son imágenes poco visibles): los rótulos «NOW LOADING» y «MESSAGE SKIP ON/OFF».

## Novedades

**v1.1**
- Corrige el **cuelgue al empezar una partida nueva**: el parche inglés tiene una pequeña rutina de
  código escondida entre los textos del sistema, justo después de «Saved to card », y la traducción
  de ese mensaje era más larga y la pisaba. Ahora la herramienta protege esa zona.
- Traduce la ayuda de la galería de imágenes.

**v1.0**
- Primera versión: historia, menús, título y tarjetas de episodio en español.

## Créditos

- Traducción al español y herramientas: fveralv.
- Basado en el parche inglés de la comunidad de Gensou Suiko Gaiden Vol.2.
- Gensou Suiko Gaiden y Suikoden © Konami. Proyecto de fans sin ánimo de lucro, no afiliado ni
  respaldado por Konami.
