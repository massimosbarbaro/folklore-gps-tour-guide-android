# Krivapete Tour Guide: GPS and map tour of folklore sites

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23205253.svg)](https://doi.org/10.5281/zenodo.23205253)

*Guida turistica GPS e su mappa ai luoghi di una leggenda popolare*

**Android** · 2020 · version 1.0 (2)  
Author: **Massimo Sbarbaro** ([ORCID 0009-0006-8965-9013](https://orcid.org/0009-0006-8965-9013))

## Overview

A tour guide to the places linked to the *Krivapete*, the women with backward-turned feet of the folk tradition of a Slovene-speaking valley area. A map shows the sites; for each site a character tells, in first person and in the local Slovene dialect with Italian translation, the legend tied to that place. The app measures the distance from the user, opens navigation to the site and lets the visitor take and browse photos.

I designed and programmed this application in 2020. It is published here in 2026 as part of the documented record of my software work, with a permanent DOI on Zenodo.

## Main functions

- Map with markers for each site of the tour (`Screen1`).
- Location screen with the user's position and the distance to each site (`LocationScreen`).
- Navigation to the selected site through the device's map application (`Navigate`).
- Monologue of the character linked to each place, in dialect and Italian, with optional text-to-speech reading.
- Photo gallery with the camera (`GalleryScreen`).

## Data

Coordinates and texts are embedded in the app; photos taken by the user are stored on the device.

## Technology

MIT App Inventor 2: Map, Marker, LocationSensor, Navigation, ActivityStarter, Camera, TextToSpeech, TinyDB; location, camera and storage permissions.

## Repository contents

| Path | Content |
|---|---|
| `project/*.aia` | The App Inventor project, ready to be imported (*Projects → Import project (.aia)* at ai2.appinventor.mit.edu). |
| `source/src/` | Screen designs (`.scm`, JSON) and block programs (`.bky`, Blockly XML), one pair per screen. |
| `source/assets/` | Button icons and App Inventor extensions used by the project. |
| `source/youngandroidproject/` | Project properties (package, version, theme). |

## What is not included

Photographs, illustrations, logos, sound recordings and stock images are **not** included: most of them belong to third parties (photographers, illustrators, performers, the commissioning organisation). The project still opens in App Inventor; the components that showed those media are simply empty. The name of the commissioning organisation and the funding statement have been removed, together with addresses, telephone numbers, e-mail addresses and websites of third parties; web addresses used by the app have been replaced with `example.org`. The compiled APK and its signing key are not published.

## Related repositories

- [multilingual-gps-tour-guide-android](https://github.com/massimosbarbaro/multilingual-gps-tour-guide-android)
- [carnival-traditions-tour-guide-android](https://github.com/massimosbarbaro/carnival-traditions-tour-guide-android)

## How to cite

Use the citation metadata in [`CITATION.cff`](CITATION.cff) (GitHub: *Cite this repository*). The release is archived on Zenodo with the DOI [10.5281/zenodo.23205253](https://doi.org/10.5281/zenodo.23205253).

> Sbarbaro, Massimo. 2020. *Krivapete Tour Guide: GPS and map tour of folklore sites*. Software (Android, 2020), version 1.0 (2). Zenodo. https://doi.org/10.5281/zenodo.23205253.

## License

Released under the [MIT License](LICENSE). © 2020 Massimo Sbarbaro.
