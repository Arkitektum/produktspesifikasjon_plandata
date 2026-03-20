---
title: "Reguleringsplanforslag - Høring og offentlig ettersyn"
updated: "2025-12-03"
organization: "Direktoratet for byggkvalitet"
logo: "https://register.geonorge.no/data/organizations/974760223_DIBK_liten.jpg"
---

# Produktspesifikasjon: Reguleringsplanforslag - Høring og offentlig ettersyn

*Reguleringsplanforslag er et forslag til et nytt arealplankart med tilhørende bestemmelser som fastlegger bruk, flerbruk og vern i bestemte områder - planområdet. Reguleringsplanforslaget er utarbeidet som en områderegulering for et større område eller som en detaljregulering for enkelttiltak eller mindre områder. Datasettet genereres fra den landsdekkende kopien av reguleringsplanforslag. Denne holdes oppdatert med data fra de originale plandataene som forvaltes i kommunene. Oppdateringen skjer ved synkronisering fra kommunene sine data.*

**Nøkkelord:** Reguleringsplanforslag, Reguleringsplan, Arealplan, Områdeplan, Detaljplan, Plan

**Emnekategorier:** Plan og eiendom

**Geografisk utstrekning:** **Geografisk utstrekning**:

- **Vest**: 2.0
- **Øst**: 33.0
- **Sør**: 57.0
- **Nord**: 72.0

**Tidsmessig utstrekning**:

- **Tidsperiode**:
  - **Fra**: 2025-10-17
  - **Til**: 2025-10-17

## Om spesifikasjonen


**Unik identifikator:** c114a146-821f-4570-aefe-a65e67c0edba<br>
**Fullstendig navn:** Reguleringsplanforslag - Høring og offentlig ettersyn<br>
**Versjon:** 2025-10-17<br>
**Opprettet dato:** 2025-10-17<br>
**Endret dato:** 2025-10-17<br>
**Språk:** nor<br>
**Kontaktinformasjon:** Direktoratet for byggkvalitet

## Om produktet Reguleringsplanforslag - Høring og offentlig ettersyn


**Romlig representasjonstype:** Vektor<br>
**Romlig oppløsning:** <br>
**Begrensninger:** **Juridiske begrensninger**:

- **Tilgangsbegrensninger**: Norge digitalt begrenset
- **Bruksbegrensninger**: Lisens
- **Lisens**: Norge digitalt-lisens
- **Lisenslenke**: <https://www.geonorge.no/Geodataarbeid/geografisk-infrastruktur/Norge-digitalt/Avtaler-og-maler/Norge-digitalt-lisens/>
- **Andre begrensninger**: Nedlasting av data begrenset til Norge digitalt avtaleparter.

**Sikkerhetsbegrensninger**:

- **Klassifisering**: Ugradert<br>
**Kontaktinformasjon:** Direktoratet for byggkvalitet

### Formål

Dekke Norge digitalt parter sine behov for tilgang til reguleringsplanforslag (geografiske data - vektordata), spesielt i forbindelse med offentlig ettersyn og for å kunne gi høringsuttalelser.

### Bruksområde

Arealplanlegging, saksbehandling i henhold til plan og bygningsloven, utarbeidelse av statistikk, vurdering av tiltak/prosjekter, innsyn i kommunens reguleringsplaner.

## Omfang

- **Omfang**:

  - **Identifikasjon**: hele datasettet
  - **Nivå**: dataset
  - **Utstrekning**: - **Beskrivelse**: National

## Datainnhold og struktur

**Beskrivelse**: Arealplanlegging, saksbehandling i henhold til plan og bygningsloven, utarbeidelse av statistikk, vurdering av tiltak/prosjekter, innsyn i kommunens reguleringsplaner.

## Datakvalitet

**Nivå**: dataset



**Beskrivelse**:
Det er kun de geografiske dataene (vektordataene) av reguleringsplanforslagene som er tilgjengelige for nedlasting. De tilhørende plandokumenter/bestemmelser finnes i kommunenes planregistre. Det ligger en lenke på planområdene i de geografiske dataene som peker til kommunenes planregistre, og dermed gjør dokumentene lettere tilgjengelig for brukerne.
Et reguleringsplanforslag kan inneholde ett eller flere vertikalnivåer; under grunnen, på grunnen/vannoverflaten, over grunnen, på bunnen og i vannsøylen.
Datasettet er delt i vertikalnivå (vn1 til vn5) avhengig av i hvilket vertikalnivå forslaget ligger, eventuelt flere vertikalnivåer.
- Under grunnen (tunnel) = 1
- På grunnen/vannoverflate = 2
- Over grunnen (bru) = 3
- På bunnen (vann/sjø) = 4
- I vannsøylen = 5

## Vedlikehold

**Vedlikeholdsfrekvens**: Kontinuerlig

**Status**: Planlagt

## Leveranse

- **Leveranse**:

  - **Leveransemedium**:
    - **unitsOfDelivery**: landsfiler
    - **Medienavn**: WMS-tjeneste
    - **Leveransetjeneste**:
      - **Tjenesteendepunkt**: <https://nap.ft.dibk.no/services/wms/reguleringsplanforslag/?service=WMS&request=GetCapabilities>
      - **Tjenesteegenskap**:
        - **type**: WMS-tjeneste
        - **Verdi**: OGC:WMS
  - **Leveranseformat**: - **Formatnavn**: PNG

- **Leveranse**:

  - **Leveransemedium**:
    - **unitsOfDelivery**: landsfiler
    - **Medienavn**: OGC API-Features
    - **Leveransetjeneste**:
      - **Tjenesteendepunkt**: <https://nap.ft.dibk.no/services/rest/reguleringsplanforslag/vn1>
      - **Tjenesteegenskap**:
        - **type**: OGC API-Features
        - **Verdi**: OGC:API-Features
  - **Leveranseformat**: - **Formatnavn**: GeoJSON

- **Leveranse**:

  - **Leveransemedium**:
    - **unitsOfDelivery**: landsfiler
    - **Medienavn**: OGC API-Features
    - **Leveransetjeneste**:
      - **Tjenesteendepunkt**: <https://nap.ft.dibk.no/services/rest/reguleringsplanforslag/vn2>
      - **Tjenesteegenskap**:
        - **type**: OGC API-Features
        - **Verdi**: OGC:API-Features
  - **Leveranseformat**: - **Formatnavn**: GeoJSON

- **Leveranse**:

  - **Leveransemedium**:
    - **unitsOfDelivery**: landsfiler
    - **Medienavn**: OGC API-Features
    - **Leveransetjeneste**:
      - **Tjenesteendepunkt**: <https://nap.ft.dibk.no/services/rest/reguleringsplanforslag/vn3>
      - **Tjenesteegenskap**:
        - **type**: OGC API-Features
        - **Verdi**: OGC:API-Features
  - **Leveranseformat**: - **Formatnavn**: GeoJSON

- **Leveranse**:

  - **Leveransemedium**:
    - **unitsOfDelivery**: landsfiler
    - **Medienavn**: OGC API-Features
    - **Leveransetjeneste**:
      - **Tjenesteendepunkt**: <https://nap.ft.dibk.no/services/rest/reguleringsplanforslag/vn4>
      - **Tjenesteegenskap**:
        - **type**: OGC API-Features
        - **Verdi**: OGC:API-Features
  - **Leveranseformat**: - **Formatnavn**: GeoJSON

- **Leveranse**:

  - **Leveransemedium**:
    - **unitsOfDelivery**: landsfiler
    - **Medienavn**: OGC API-Features
    - **Leveransetjeneste**:
      - **Tjenesteendepunkt**: <https://nap.ft.dibk.no/services/rest/reguleringsplanforslag/vn5>
      - **Tjenesteegenskap**:
        - **type**: OGC API-Features
        - **Verdi**: OGC:API-Features
  - **Leveranseformat**: - **Formatnavn**: GeoJSON

- **Leveranse**:

  - **Leveransemedium**:
    - **unitsOfDelivery**: landsfiler
    - **Medienavn**: Atom Feed
    - **Leveransetjeneste**:
      - **Tjenesteendepunkt**: <https://nap.ft.dibk.no/services/download/reguleringsplanforslag/atom>
      - **Tjenesteegenskap**:
        - **type**: Atom Feed
        - **Verdi**: W3C:AtomFeed
  - **Leveranseformat**: - **Formatnavn**: PostGIS

- **Leveranse**:

  - **Leveransemedium**:
    - **unitsOfDelivery**: landsfiler
    - **Medienavn**: Egen nedlastningsside
    - **Leveransetjeneste**:
      - **Tjenesteendepunkt**: <https://nap.ft.dibk.no/services/download/klimagasskalkulator/>
      - **Tjenesteegenskap**:
        - **type**: Egen nedlastningsside
        - **Verdi**: WWW:DOWNLOAD-1.0-http--download
  - **Leveranseformat**: - **Formatnavn**: GeoJSON

- **Leveranse**:

  - **Leveransemedium**:
    - **unitsOfDelivery**: landsfiler
    - **Medienavn**: Geonorge nedlastning
    - **Leveransetjeneste**:
      - **Tjenesteendepunkt**: <https://nap.ft.dibk.no/services/nedlasting/api/capabilities/>
      - **Tjenesteegenskap**:
        - **type**: Geonorge nedlastning
        - **Verdi**: GEONORGE:DOWNLOAD
  - **Leveranseformat**:
    - **Formatnavn**: GeoPackage

    - **Formatnavn**: PostGIS

    - **Formatnavn**: GML

- **Leveranse**:

  - **Leveransemedium**:
    - **Medienavn**: Reguleringsplanforslag - Høring og offentlig ettersyn
    - **Leveransetjeneste**:
      - **Tjenesteendepunkt**: <https://nap.ft.dibk.no/services/wms/reguleringsplanforslag/?service=WMS&request=GetCapabilities>
      - **Tjenesteegenskap**:
        - **type**: Reguleringsplanforslag - Høring og offentlig ettersyn
        - **Verdi**: WMS-tjeneste
  - **Leveranseformat**: - **Formatnavn**: PNG
  - **Leveranseomfang**: Tjeneste

## Metadata

**Metadatastandard**: ISO19115

**Metadatastandardversjon**: 2003

**Metadatadato**: 2026-02-27

**språk**: nor

**Kontakt**:

- **Organisasjon**: Direktoratet for byggkvalitet
- **Kontaktperson**: Olaug Hana Nesheim
- **Logo**: <https://register.geonorge.no/data/organizations/974760223_DIBK_liten.jpg>
- **Epost**: ftb@dibk.no
- **rolle**: pointOfContact

**Metadataidentifikator**:

- **Utsteder**: Geonorge
- **kode**: c114a146-821f-4570-aefe-a65e67c0edba
- **koderom**: <https://kartkatalog.geonorge.no/metadata/>
- **Metadatalenke**: <https://kartkatalog.geonorge.no/metadata/c114a146-821f-4570-aefe-a65e67c0edba>

**Lenker**:

- **lenke**: <https://www.geonorge.no/geonetwork/srv/nor/csw?service=CSW&request=GetRecordById&version=2.0.2&outputSchema=http://www.isotc211.org/2005/gmd&elementSetName=full&id=c114a146-821f-4570-aefe-a65e67c0edba>
  **relasjon**: describedby
  **type**: application/xml
  **tittel**: Metadata (ISO 19139)

- **lenke**: <https://nap.ft.dibk.no/services/download/klimagasskalkulator/>
  **relasjon**: enclosure
  **type**: text/html
  **tittel**: Nedlasting

- **lenke**: <https://nap.ft.dibk.no/services/nedlasting/api/capabilities/>
  **relasjon**: enclosure
  **type**: text/html
  **tittel**: Distribusjon

- **lenke**: <https://nap.ft.dibk.no/services/wms/reguleringsplanforslag/?service=WMS&request=GetCapabilities>
  **relasjon**: alternate
  **type**: text/html
  **tittel**: Kartvisning

- **lenke**: #!?zoom=3&lon=306722&lat=7197864&wms=<https://nap.ft.dibk.no/services/wms/reguleringsplanforslag/>
  **relasjon**: service
  **type**: text/html
  **tittel**: Tjeneste

## Tilleggsinformasjon

Det er kun de geografiske dataene (vektordataene) av reguleringsplanforslagene som er tilgjengelige for nedlasting. De tilhørende plandokumenter/bestemmelser finnes i kommunenes planregistre. Det ligger en lenke på planområdene i de geografiske dataene som peker til kommunenes planregistre, og dermed gjør dokumentene lettere tilgjengelig for brukerne.
Et reguleringsplanforslag kan inneholde ett eller flere vertikalnivåer; under grunnen, på grunnen/vannoverflaten, over grunnen, på bunnen og i vannsøylen.
Datasettet er delt i vertikalnivå (vn1 til vn5) avhengig av i hvilket vertikalnivå forslaget ligger, eventuelt flere vertikalnivåer.
- Under grunnen (tunnel) = 1
- På grunnen/vannoverflate = 2
- Over grunnen (bru) = 3
- På bunnen (vann/sjø) = 4
- I vannsøylen = 5
