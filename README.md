# mirage-maps

Offline map packages downloaded by the Mirage app (Ajustes > Navegação > Mapas offline).
Each Brazilian state is one GitHub Release with two assets:

| Asset | Contents |
| --- | --- |
| `<uf>-basemap-z14.pmtiles` | Vector streets (OpenMapTiles schema, Planetiler), zoom 0-14 |
| `<uf>-routing-gh11.zip` | GraphHopper 11 car graph used for offline routing |

The app verifies size and SHA-256 from its bundled catalog before installing.

## Available

The app downloads one package per region:

| Region | Release |
| --- | --- |
| Norte | `norte-2026-10-15-r2` |
| Nordeste | `nordeste-2026-10-15-r2` |
| Centro-Oeste | `centro-oeste-2026-10-15-r2` |
| Sudeste | `sudeste-2026-10-15-r2` |
| Sul | `sul-2026-10-15-r2` |

Per-state releases (`<uf>-2026-10-13`) stay published for manual import.

## License

Map data © OpenStreetMap contributors, available under the
[Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/).
Source extracts: Geofabrik / openstreetmap.fr regional PBFs.
