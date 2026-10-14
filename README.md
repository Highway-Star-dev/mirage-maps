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
| Acre | `ac-2026-10-13` |
| Alagoas | `al-2026-10-13` |
| Amapá | `ap-2026-10-13` |
| Amazonas | `am-2026-10-13` |
| Bahia | `ba-2026-10-13` |
| Ceará | `ce-2026-10-13` |
| Distrito Federal | `df-2026-10-13` |
| Espírito Santo | `es-2026-10-13` |
| Goiás | `go-2026-10-13` |
| Maranhão | `ma-2026-10-13` |
| Mato Grosso | `mt-2026-10-13` |
| Mato Grosso do Sul | `ms-2026-10-13` |
| Minas Gerais | `mg-2026-10-13` |
| Paraná | `pr-2026-10-13` |
| Paraíba | `pb-2026-10-13` |
| Pará | `pa-2026-10-13` |
| Pernambuco | `pe-2026-10-13` |
| Piauí | `pi-2026-10-13` |
| Rio Grande do Norte | `rn-2026-10-13` |
| Rio de Janeiro | `rj-2026-10-13` |

## License

Map data © OpenStreetMap contributors, available under the
[Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/).
Source extracts: Geofabrik / openstreetmap.fr regional PBFs.
