# Forged Ops Pilot – offline map areas

Map files for the **Forged Ops Pilot** phone app (Fly > Offline map areas). Each release holds one map area as an
`.mbtiles` file (vector tiles, zoom 0–13) that the app downloads and then draws without any internet signal.

This repository holds **only map files**. The app itself is not here.

| Area | File | Size | Map data of |
|---|---|---|---|
| South Africa, Lesotho and Eswatini | `za.mbtiles` | 303 MB | 1 November 2026 |

The app reads its list of areas from `packs.json` in this repository (on the `main` branch), which points at the
release files here.

## Licence and attribution

Map data © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors, available under the
[Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/). The files are cut from the
daily [Protomaps](https://maps.protomaps.com/builds/) planet builds and are made available under the same ODbL
licence.

## Not an aeronautical chart

These maps are for orientation only. They are not aeronautical charts and must not be used as the sole means of
navigation; the official AIP charts of each country remain the reference.
