# Speedometer Pro regional data downloads

Public, licensed map and search data for downloadable regions. This repository
contains no app source code, credentials, personal journeys or user search logs.

## Coverage

The first validation pack covers northern Melbourne, Australia, only. It is not
an Australia-wide or worldwide offline map. Online search in Speedometer Pro is
not restricted to these download regions. Additional countries and regions need
their own verified extracts and source-licence checks before appearing here.

Each release contains an immutable ZIP and a manifest with its geographic bounds,
source dates, record counts, compressed and installed sizes, and SHA-256 digest.
The app pins approved digests. Do not trust a modified ZIP or its own manifest to
authorize installation. Download only a region whose bounds include your trip.

## What is included

- Protomaps/OpenStreetMap visual vector tiles, local styles, fonts and sprites.
- A disk-backed place/address search index from licensed Overture source records.
- Attribution and licence notices, also available inside each ZIP.

These packs provide offline map display and search, **not offline routing or
live traffic**. Map data may omit a business, unit, entrance or street. Coordinates
do not establish a legal/safe driveway or lane. Check results before travelling.

## Licences and sources

Map tiles: © OpenStreetMap contributors, via Protomaps. See
[OpenStreetMap copyright](https://www.openstreetmap.org/copyright) and
[ODbL 1.0](https://opendatacommons.org/licenses/odbl/1-0/).
The original open data is available from OpenStreetMap and the Protomaps daily
build named in each manifest. These regional tiles are produced works.

Places: Overture Maps Foundation, CDLA-Permissive-2.0. The full agreement is
included in `LICENSE_CDLA.txt`. Public records are filtered and indexed.

Australian addresses: G-NAF © Geoscape Australia licensed by the Commonwealth of
Australia. Distributed by OpenAddresses via Overture; reindexed for search.
Available under the [Open G-NAF Core End User Licence Agreement](https://geoscape.com.au/wp-content/uploads/2024/08/EULA-G-NAF-Core-1.pdf).
Addresses used for sending mail must be checked against a secondary source.
Data is provided as-is, without warranty of accuracy or fitness; licence sections
3 and 5 apply. No provider endorsement is implied.

Noto fonts: SIL Open Font License, included in `fonts/OFL.txt`.
Protomaps styles: BSD-3-Clause, included in `LICENSE_STYLE.txt`.
Nothing here grants exclusive rights in the underlying open data.
