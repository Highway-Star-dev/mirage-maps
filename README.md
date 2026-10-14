# mirage-maps

Offline map packages downloaded by the Mirage app (Ajustes > Navegação > Mapas offline).
Each Brazilian state is one GitHub Release with two assets:

| Asset | Contents |
| --- | --- |
| `<uf>-basemap-z14.pmtiles` | Vector streets (OpenMapTiles schema, Planetiler), zoom 0-14 |
| `<uf>-routing-gh11.zip` | GraphHopper 11 car graph used for offline routing |

The app verifies size and SHA-256 from its bundled catalog before installing.

## Available

| State | Release |
| --- | --- |
| Minas Gerais | `mg-2026-10-13` |

## License

Map data © OpenStreetMap contributors, available under the
[Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/).
Source extracts: Geofabrik / openstreetmap.fr regional PBFs.
