# Discussing the future of the Colonial Architecture & Town Planning Repository

Bullet points about the current state of the repo:

- The software of the [Colonial Architecture & Town Planning Repository](https://colonialarchitecture.eu) is outdated. Since TU Delft Library is moving away from supporting the underlying technical infrastructure (Fedora, Drupal, Islandora) the future of the repo is brought up for discussion.
- Apart from a research dataset originating from Universitas Gadjah Mada (Yogyakarta) the repository's contents have not been updated since its launch in 2014 and does not reflect the vast amount of digitised material that has become available in the meantime by the contributing institutions or elsewhere.
- The repository contains copies of digitised collections that _should_ also be published on the digital collections portals of the contributing institutions. If this is indeed the case, modern standards such as [IIIF](https://iiif.io) could be used to fetch images and metadata directly form the institutions, eliminating the need for copies. This would be in line with the Linked Data approach favored by the [Dutch Digital Heritage Network](https://netwerk-digitaal-erfgoed.github.io/cm-implementation-guidelines/).
- Some of the metadata-only records could potentially be adopted as part the project [Indisch Erfgoed Digitaal](https://www.metamorfoze.nl/financiering/programma-indisch-erfgoed-digitaal). 
- The [Faculty of Architecture and the Built Environment](https://www.tudelft.nl/bk/) initiated the repo and is still an important stakeholder.

Aim of this repository:

- Publishing CSV/Excel exports of the various types
- Providing an overview of the various institutional owners (unfortunately this is not available as a search facet in the repo itself)
- Communicating with stakeholders
- Publishing matched records in digital collections elsewhere
- Testing and demonstrating new approaches with e.g. IIIF

Background articles about the making of the repo:

- [Building a repository on European colonial architecture and town planning](http://resolver.tudelft.nl/uuid:6434057c-8888-458b-a3ec-9cecb6e7c281)
- [A repository for sources about European colonial architecture and town planning](http://resolver.tudelft.nl/uuid:8c6f01a4-104c-4761-b4b1-be6e8e4fd5d9)

## Overview of the repository's contents by type

Abbreviations:
- UBL = Universitaire Bibliotheken Leiden
- TUD = Delft University of Technology Library
- UGM = Universitas Gadjah Mada, Yogyakarta
- TRO = Tropenmuseum (Royal Tropical Institute)
- HNI = The New Institute (formerly Netherlands Architecture Institute)

### Metadata only

| Subcollection | Count | Exported | Matched | Comments |
| --- | --- | --- | --- | --- |
| [Persons](https://colonialarchitecture.eu/slv?sq=&fac%5B0%5D=t%3APerson&ft=0) | 169 | [persons.xlsx](https://github.com/tu-delft-library/colonial-repo-revisited/raw/main/exports/xlsx/persons.xlsx) | - | |
| [Buildings](https://colonialarchitecture.eu/slv?sq=&fac%5B0%5D=t%3ABuilding&ft=0) | 481 | [buildings.xlsx](https://github.com/tu-delft-library/colonial-repo-revisited/raw/main/exports/xlsx/buildings.xlsx) | - | |
| [Organisations](https://colonialarchitecture.eu/slv?sq=&fac%5B0%5D=t%3AOrganization&ft=0) | 80 | [organisations.xlsx](https://github.com/tu-delft-library/colonial-repo-revisited/raw/main/exports/xlsx/organisations.xlsx) | - | [2 group records of Dutch and English architects](https://colonialarchitecture.eu/slv?sq=&fac%5B0%5D=t%3AGroup) |

Other metadata-only types:
- Location: 247 (Geonames)
- Concept: 323 (AAT)
- TownPlan: 14 (No results)

### Book

| Contributor | Count | Exported | Matched | Comments |
| --- | --- | --- | --- | --- |
| [UBL](https://colonialarchitecture.eu/slv?sq=%22Leiden%20University%20Libraries%22&fac%5B0%5D=t%3ABook&ft=0) | 186 | [ubl_publications.xlsx](https://github.com/tu-delft-library/colonial-repo-revisited/raw/main/exports/xlsx/ubl/ubl_publications.xlsx) | ❌ | Could not be matched; UBL would like to obtain master copies (TIF) |
| [TUD](https://colonialarchitecture.eu/slv?sq=%22TU%20Delft%20Library%22&fac%5B0%5D=t%3ABook&ft=0) | 83 | ❌ | - | |
| [HNI](https://colonialarchitecture.eu/slv?sq=%22Het%20Nieuwe%20Instituut%22&fac%5B0%5D=t%3ABook&ft=0) | 10 | ❌ | - | |
| Total | 279 | | | 285 items in search results |

### Image

| Contributor | Count | Exported | Matched | Comments |
| --- | --- | --- | --- | --- |
| [UBL](https://colonialarchitecture.eu/slv?sq=%22Leiden%20University%20Libraries%22&ft=0&cat=Image&rows=5) | 14716 | [ubl_images.xlsx](https://github.com/tu-delft-library/colonial-repo-revisited/raw/main/exports/xlsx/ubl/ubl_images.xlsx) | [ubl_images_handles.xlsx](https://github.com/tu-delft-library/colonial-repo-revisited/raw/main/exports/xlsx/ubl/ubl_images_handles.xlsx) (14714) | 14715 hits in search results |
| [TRO](https://colonialarchitecture.eu/slv?sq=%22Tropenmuseum%22&ft=0) | 4110 | ❌ | - | |
| [Paul Suijker](https://colonialarchitecture.eu/slv?sq=suijker&fac%5B0%5D=t%3AImage&ft=0) | 2 | ❌ | - | |
| Total | 18828 | | | 18834 items in search results |

### Map

| Contributor | Count | Exported | Matched | Comments |
| --- | --- | --- | --- | --- |
| [UBL](https://colonialarchitecture.eu/slv?sq=%22Leiden%20University%20Libraries%22&ft=0&cat=Map&rows=5) | 178 | [ubl_maps.xlsx](https://github.com/tu-delft-library/colonial-repo-revisited/raw/main/exports/xlsx/ubl/ubl_maps.xlsx) | [ubl_maps_handles.xlsx](https://github.com/tu-delft-library/colonial-repo-revisited/raw/main/exports/xlsx/ubl/ubl_maps_handles.xlsx) (170) | |
| Total | 178 | | | 178 items in search results |

### Journal & JournalIssue

| Contributor | Journal Count | Issue Count | Exported | Matched | Comments |
| --- | --- | --- | --- | --- | --- |
| [UBL](https://colonialarchitecture.eu/slv?sq=%22Leiden%20University%20Libraries%22&fac%5B0%5D=t%3AJournal&ft=0) | 11 | ? | ❌ | - | |
| [TUD](https://colonialarchitecture.eu/slv?sq=%22TU%20Delft%20Library%22&fac%5B0%5D=t%3AJournal&ft=0) | 10 | ? | ❌ | - | |
| [HNI](https://colonialarchitecture.eu/slv?sq=NAI&fac%5B0%5D=t%3AJournal&ft=0) | 1 | 5 | ❌ | - | |
| Total | 22 | ? | | | 2357 issues in search results |

### Report
| Contributor | Count | Exported | Matched | Comments |
| --- | --- | --- | --- | --- |
| UGM | 2283 | ❌ | - | Originating from the research project [On Bamboo, Bricks, Tiles and Thatches](https://marinusplantemafoundation.nl/on-bamboo-bricks-tiles-and-thatches/) |
| Total | 2283 | | | 2283 items in search results |

## Data model

![Data model of the repository](/img/data-model.png)

## Todo

See [issues](https://github.com/tu-delft-library/colonial-repo-revisited/issues)
