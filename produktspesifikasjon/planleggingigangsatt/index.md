---
title: "Planområde for planlegging igangsatt"
updated: "2026-01-28"
organization: "Direktoratet for byggkvalitet"
logo: "https://register.geonorge.no/data/organizations/974760223_DIBK_liten.jpg"
---

# Produktspesifikasjon: Planområde for planlegging igangsatt

*Datasettet viser område(r) hvor det er varslet at planlegging skal igangsettes etter plan- og bygningsloven (pbl). Formålet er å kunne identifisere og vise hvor planarbeid er startet, slik at naboer, berørte parter, høringsmyndigheter og kommunen får informasjon om planinitiativet.*

**Nøkkelord:** planområde, planomriss, Arealplan, Plan

**Emnekategorier:** Plan og eiendom

**Geografisk utstrekning**:

- **Vest**: 2.0
- **Øst**: 33.0
- **Sør**: 57.0
- **Nord**: 72.0

**Tidsmessig utstrekning**:

- **Tidsperiode**:
  - **Fra**: 2025-10-17
  - **Til**: 2025-10-17

## Om spesifikasjonen


> **Denne versjonen av produktspesifikasjonen:** <br>
> **Opprettet dato:** 2025-10-17<br>
> **Endret dato:** 2025-10-17<br>
> **Språk:** nor<br>
> **Kontaktinformasjon:** Direktoratet for byggkvalitet

## Om produktet Planområde for planlegging igangsatt


> **Romlig representasjonstype:** Vektor<br>
> **Unik identifikator:** 779a554b-fc3e-48a6-b202-561b07e9d4c2<br>
> **Kontaktinformasjon:** Direktoratet for byggkvalitet
>
> **Romlig oppløsning:** **Avstand**:
>
> - **Måleenhet**: meter
> - **Verdi**: 0.01
>
> **Begrensninger:** **Juridiske begrensninger**:
>
> - **Tilgangsbegrensninger**: Åpne data
> - **Bruksbegrensninger**: Lisens
> - **Lisens**: Norsk lisens for offentlige data (NLOD) 2.0
> - **Lisenslenke**: <https://data.norge.no/nlod/no/2.0>
>
> **Sikkerhetsbegrensninger**:
>
> - **Klassifisering**: Ugradert

### Formål

Formålet er å kunne identifisere og vise hvor planarbeid er startet, slik at naboer, berørte parter, høringsmyndigheter og kommunen får informasjon om planinitiativet og kan medvirke i prosessen.

### Bruksområde

Datasettet brukes som grunnlag ved oversendelse av planinitiativ til kommunen og høringsparter, i varsel om oppstart av planarbeid, som underlag i saksbehandling, uttalelser fra høringsmyndigheter og registrering i  kommunale planregister, samt for visning i kartløsninger.

## Omfang

- **Omfang**:

  - **Identifikasjon**: hele datasettet
  - **Nivå**: dataset
  - **Utstrekning**:
    - **Beskrivelse**: National
  - **Nivåbeskrivelse**:
    #### datafangst
    Datamodellen brukes for å legge ved gml filer for planområdet som brukes i tjenesten for varsel om planoppstart.

    #### innsynstjeneste
    Tjeneste for innsyn i planområder som er varslet for planlegging igangsatt.

## Datainnhold og struktur

**Beskrivelse**: Datasettet brukes som grunnlag ved oversendelse av planinitiativ til kommunen og høringsparter, i varsel om oppstart av planarbeid, som underlag i saksbehandling, uttalelser fra høringsmyndigheter og registrering i  kommunale planregister, samt for visning i kartløsninger.

### Datamodell - datafangst



[Objektkatalog - datafangst](datafangst/objektkatalog.html)



<a href="datafangst/datafangst_feature_catalogue.png" title="Klikk for stor visning"><img src="datafangst/datafangst_feature_catalogue.png" alt="Datamodell datafangst" style="max-width: 100%; height: auto;" /></a>

### Datamodell - innsynstjeneste



[Objektkatalog - innsynstjeneste](innsynstjeneste/objektkatalog.html)



<a href="innsynstjeneste/innsynstjeneste_feature_catalogue.png" title="Klikk for stor visning"><img src="innsynstjeneste/innsynstjeneste_feature_catalogue.png" alt="Datamodell innsynstjeneste" style="max-width: 100%; height: auto;" /></a>

## Referansesystem

| EPSG-kode | Navn på referansesystem |
| --- | --- |
| [EPSG:25832](https://epsg.io/25832) | [EUREF89 UTM sone 32, 2d](https://register.geonorge.no/epsg-koder) |
| [EPSG:25833](https://epsg.io/25833) | [EUREF89 UTM sone 33, 2d](https://register.geonorge.no/epsg-koder) |
| [EPSG:25835](https://epsg.io/25835) | [EUREF89 UTM sone 35, 2d](https://register.geonorge.no/epsg-koder) |
| [EPSG:3035](https://epsg.io/3035) | [EUREF89 / ETRS89-LAEA Europe](https://register.geonorge.no/epsg-koder) |
| [EPSG:4326](https://epsg.io/4326) | [WGS84 Geografisk](https://register.geonorge.no/epsg-koder) |
| [EPSG:3857](https://epsg.io/3857) | [Web Mercator / Pseudo-Mercator](https://register.geonorge.no/epsg-koder) |

## Datakvalitet

**Nivå**: dataset





## Datafangst og produksjon

**Datainnsamling og prosessering**:

- **Prosesstrinn**:
  - **Beskrivelse**: datafangst skjer gjennom tjenesten varsel om planoppstart på fellestjenester plan som fylles ut av forslagsstiller eller plankonsulent

## Vedlikehold

**Vedlikeholdsfrekvens**: Kontinuerlig

**Status**: Kontinuerlig oppdatert

## Leveranse

- **Leveranse**:

  - **Leveransemedium**:
    - **Leveranseenheter**: landsfiler
    - **Medienavn**: OGC API-Features
    - **Leveransetjeneste**:
      - **Tjenesteendepunkt**: <https://plandata.ft.dibk.no/services/rest/planleggingigangsatt>
      - **Tjenesteegenskap**:
        - **type**: OGC API-Features
        - **Verdi**: OGC:API-Features
  - **Leveranseformat**:
    - **Formatnavn**: GeoJSON

- **Leveranse**:

  - **Leveransemedium**:
    - **Leveranseenheter**: landsfiler
    - **Medienavn**: WMS-tjeneste
    - **Leveransetjeneste**:
      - **Tjenesteendepunkt**: <https://plandata.ft.dibk.no/services/wms/planleggingigangsatt/?service=WMS&request=GetCapabilities>
      - **Tjenesteegenskap**:
        - **type**: WMS-tjeneste
        - **Verdi**: OGC:WMS
  - **Leveranseformat**:
    - **Formatnavn**: PNG

    - **Formatnavn**: BMP

    - **Formatnavn**: GeoTIFF

    - **Formatnavn**: JPEG

    - **Formatnavn**: TIFF

- **Leveranse**:

  - **Leveransemedium**:
    - **Medienavn**: Planområde for planlegging igangsatt
    - **Leveransetjeneste**:
      - **Tjenesteendepunkt**: <https://plandata.ft.dibk.no/services/wms/planleggingigangsatt/?service=WMS&request=GetCapabilities>
      - **Tjenesteegenskap**:
        - **type**: Planområde for planlegging igangsatt
        - **Verdi**: WMS-tjeneste
  - **Leveranseformat**:
    - **Formatnavn**: PNG
  - **Leveranseomfang**: Tjeneste

## Metadata

**Metadatastandard**: ISO19115

**Metadatastandardversjon**: 2003

**Metadatadato**: 2026-03-20

**språk**: nor

**Kontakt**:

- **Organisasjon**: Direktoratet for byggkvalitet
- **Kontaktperson**: Olaug Hana Nesheim
- **Logo**: <https://register.geonorge.no/data/organizations/974760223_DIBK_liten.jpg>
- **Epost**: ftb@dibk.no
- **rolle**: pointOfContact

**Metadataidentifikator**:

- **Utsteder**: Geonorge
- **kode**: 779a554b-fc3e-48a6-b202-561b07e9d4c2
- **koderom**: <https://kartkatalog.geonorge.no/metadata/>
- **Metadatalenke**: <https://kartkatalog.geonorge.no/metadata/779a554b-fc3e-48a6-b202-561b07e9d4c2>

**Lenker**:

- **lenke**: <https://www.geonorge.no/geonetwork/srv/nor/csw?service=CSW&request=GetRecordById&version=2.0.2&outputSchema=http://www.isotc211.org/2005/gmd&elementSetName=full&id=779a554b-fc3e-48a6-b202-561b07e9d4c2>
  **relasjon**: describedby
  **type**: application/xml
  **tittel**: Metadata (ISO 19139)

- **lenke**: <https://plandata.ft.dibk.no/services/rest/planleggingigangsatt>
  **relasjon**: enclosure
  **type**: text/html
  **tittel**: Nedlasting

- **lenke**: <https://plandata.ft.dibk.no/services/wms/planleggingigangsatt/?service=WMS&request=GetCapabilities>
  **relasjon**: alternate
  **type**: text/html
  **tittel**: Kartvisning

- **lenke**: #!?zoom=3&lon=306722&lat=7197864&wms=<https://plandata.ft.dibk.no/services/wms/planleggingigangsatt/>
  **relasjon**: service
  **type**: text/html
  **tittel**: Tjeneste

