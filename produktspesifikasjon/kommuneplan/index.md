---
title: "Kommuneplaner (landsdekkende kopi)"
updated: "2025-12-03"
organization: "Direktoratet for byggkvalitet"
logo: "https://register.geonorge.no/data/organizations/974760223_DIBK_liten.jpg"
---

# Produktspesifikasjon: Kommuneplaner (landsdekkende kopi)

*Fra 1.1.2026 vil Direktoratet for byggkvalitet opprettholde «Norge digitalt arealplankartløsning» (NAP) med datasett for kommuneplaner og denne oppføringen er oppdatert med distribusjoner.

Kommuneplanen skal være kommunens overordnede styringsdokument. Den skal gi rammer for virksomhetenes planer og tiltak, og planer for bruk og vern av arealer i kommunen. Alle kommuner skal ha en kommuneplan. En samlet kommuneplan består både av en samfunnsdel med handlingsdel og en arealdel. Kommunen bestemmer gjennom vedtak av kommunal planstrategi om kommunen skal gjennomføre en full kommuneplanrevisjon av alle delene, eller om bare deler av kommuneplanen skal revideres, og hva revisjonen skal gå ut på. Kommuneplanen skal ivareta både kommunale, regionale og nasjonale mål, interesser og oppgaver, og bør omfatte alle viktige mål og oppgaver i kommunen. Den skal ta utgangspunkt i den kommunale planstrategien og legge retningslinjer og pålegg fra statlige og regionale myndigheter til grunn. Det kan utarbeides kommunedelplan for bestemte områder, temaer eller virksomhetsområder. Kommuneplanen skal ha en handlingsdel som angir hvordan planen skal følges opp de fire påfølgende år eller mer, og revideres årlig (Regjeringen.no).

Datasettet genereres fra den landsdekkende kopien av kommuneplaner . Denne holdes oppdatert med data fra de originale plandataene i kommunene. Oppdateringen skjer ved synkronisering fra kommunene.*

**Nøkkelord:** Kommuneplan, Kommunedelplan, Arealformål, Arealbruk, Plan

**Emnekategorier:** Plan og eiendom

**Geografisk utstrekning**:

- **Vest**: 2.0
- **Øst**: 33.0
- **Sør**: 57.0
- **Nord**: 72.0

**Tidsmessig utstrekning**:

- **Tidsperiode**:
  - **Fra**: 2025-09-16
  - **Til**: 2025-09-16

## Om spesifikasjonen


> **Denne versjonen av produktspesifikasjonen:** <br>
> **Opprettet dato:** 2025-09-16<br>
> **Endret dato:** 2025-09-16<br>
> **Språk:** nor<br>
> **Kontaktinformasjon:** Direktoratet for byggkvalitet

## Om produktet Kommuneplaner (landsdekkende kopi)


> **Romlig representasjonstype:** Vektor<br>
> **Unik identifikator:** 41435fda-93ba-48a8-bd56-79a9287b6dad<br>
> **Kontaktinformasjon:** Direktoratet for byggkvalitet
>
> **Romlig oppløsning:** 
>
> **Begrensninger:** **Ressursbegrensninger**:
>
> - **Bruksbegrensninger**: Ikke egnet for kommunens arealplanarbeid. Oppdaterte data fås hos kommunen. Private forslagsstillere må henvende seg direkte til kommunen.
>
> **Juridiske begrensninger**:
>
> - **Tilgangsbegrensninger**: Norge digitalt begrenset
> - **Bruksbegrensninger**: Lisens
> - **Lisens**: Norge digitalt-lisens
> - **Lisenslenke**: <https://www.geonorge.no/Geodataarbeid/geografisk-infrastruktur/Norge-digitalt/Avtaler-og-maler/Norge-digitalt-lisens/>
>
> **Sikkerhetsbegrensninger**:
>
> - **Klassifisering**: Ugradert

### Formål

Dekke Norge digitalt partenes behov for overordnede arealplaner i kommunene.

### Bruksområde

Arealplanlegging, saksbehandling i henhold til plan og bygningsloven, utarbeidelse av statistikk, vurdering av tiltak/prosjekter, innsyn i kommunens arealplan.

## Omfang

**Identifikasjon**: hele datasettet
**Nivå**: dataset
**Utstrekning**: National

## Datainnhold og struktur

**Beskrivelse**: Arealplanlegging, saksbehandling i henhold til plan og bygningsloven, utarbeidelse av statistikk, vurdering av tiltak/prosjekter, innsyn i kommunens arealplan.

## Datakvalitet

**Nivå**: dataset

- **Kvalitetsmål**: Produktspesifikasjon: Del 3.1 - Kommuneplanens arealdel
  **Målebeskrivelse**: Dataene er ikke vurdert iht produktspesifikasjonen
  **Beskrivende resultat**: Dataene er ikke vurdert iht produktspesifikasjonen

**Beskrivelse**: Det er kun de geografiske dataene (vektordataene) av arealdelen som er tilgjengelige for nedlasting. De tilhørende plandokumenter finnes i kommunenes planregistre. Det ligger en lenke på planområdene i de geografiske dataene som peker til kommunenes planregistre, og dermed gjør dokumentene lettere tilgjengelig for brukerne.

## Vedlikehold

**Vedlikeholdsfrekvens**: Hvert halvår

**Status**: Planlagt

## Leveranse

- **Leveranse**:

  - **Leveransemedium**:
    - **Leveranseenheter**: landsfiler
    - **Medienavn**: WMS-tjeneste
    - **Leveransetjeneste**:
      - **Tjenesteendepunkt**: <https://nap.ft.dibk.no/services/wms/kommuneplaner/?service=WMS&request=GetCapabilities>
      - **Tjenesteegenskap**:
        - **type**: WMS-tjeneste
        - **Verdi**: OGC:WMS
  - **Leveranseformat**:
    - **Formatnavn**: PNG

- **Leveranse**:

  - **Leveransemedium**:
    - **Leveranseenheter**: landsfiler
    - **Medienavn**: OGC API-Features
    - **Leveransetjeneste**:
      - **Tjenesteendepunkt**: <https://nap.ft.dibk.no/services/rest/kommuneplaner/>
      - **Tjenesteegenskap**:
        - **type**: OGC API-Features
        - **Verdi**: OGC:API-Features
  - **Leveranseformat**:
    - **Formatnavn**: GeoJSON

- **Leveranse**:

  - **Leveransemedium**:
    - **Leveranseenheter**: landsfiler
    - **Medienavn**: OGC API-Features
    - **Leveransetjeneste**:
      - **Tjenesteendepunkt**: <https://nap.ft.dibk.no/services/rest/kommunedelplaner>
      - **Tjenesteegenskap**:
        - **type**: OGC API-Features
        - **Verdi**: OGC:API-Features
  - **Leveranseformat**:
    - **Formatnavn**: GeoJSON

- **Leveranse**:

  - **Leveransemedium**:
    - **Leveranseenheter**: landsfiler
    - **Medienavn**: Atom Feed
    - **Leveransetjeneste**:
      - **Tjenesteendepunkt**: <https://nap.ft.dibk.no/services/download/kommuneplaner/atom>
      - **Tjenesteegenskap**:
        - **type**: Atom Feed
        - **Verdi**: W3C:AtomFeed
  - **Leveranseformat**:
    - **Formatnavn**: PostGIS

- **Leveranse**:

  - **Leveransemedium**:
    - **Leveranseenheter**: landsfiler
    - **Medienavn**: Atom Feed
    - **Leveransetjeneste**:
      - **Tjenesteendepunkt**: <https://nap.ft.dibk.no/services/download/kommunedelplaner/atom>
      - **Tjenesteegenskap**:
        - **type**: Atom Feed
        - **Verdi**: W3C:AtomFeed
  - **Leveranseformat**:
    - **Formatnavn**: PostGIS

- **Leveranse**:

  - **Leveransemedium**:
    - **Leveranseenheter**: landsfiler
    - **Medienavn**: Egen nedlastningsside
    - **Leveransetjeneste**:
      - **Tjenesteendepunkt**: <https://nap.ft.dibk.no/services/download/klimagasskalkulator/>
      - **Tjenesteegenskap**:
        - **type**: Egen nedlastningsside
        - **Verdi**: WWW:DOWNLOAD-1.0-http--download
  - **Leveranseformat**:
    - **Formatnavn**: GeoJSON

- **Leveranse**:

  - **Leveransemedium**:
    - **Leveranseenheter**: landsfiler
    - **Medienavn**: Geonorge nedlastning
    - **Leveransetjeneste**:
      - **Tjenesteendepunkt**: <https://nap.ft.dibk.no/services/nedlasting/api/capabilities/>
      - **Tjenesteegenskap**:
        - **type**: Geonorge nedlastning
        - **Verdi**: GEONORGE:DOWNLOAD
  - **Leveranseformat**:
    - **Formatnavn**: GeoPackage

    - **Formatnavn**: GML

    - **Formatnavn**: PostGIS

- **Leveranse**:

  - **Leveransemedium**:
    - **Medienavn**: Kommuneplaner (landsdekkende kopi)
    - **Leveransetjeneste**:
      - **Tjenesteendepunkt**: <https://nap.ft.dibk.no/services/wms/kommuneplaner/?service=WMS&request=GetCapabilities>
      - **Tjenesteegenskap**:
        - **type**: Kommuneplaner (landsdekkende kopi)
        - **Verdi**: WMS-tjeneste
  - **Leveranseformat**:
    - **Formatnavn**: PNG
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
- **kode**: 41435fda-93ba-48a8-bd56-79a9287b6dad
- **koderom**: <https://kartkatalog.geonorge.no/metadata/>
- **Metadatalenke**: <https://kartkatalog.geonorge.no/metadata/41435fda-93ba-48a8-bd56-79a9287b6dad>

**Lenker**:

- **lenke**: <https://www.geonorge.no/geonetwork/srv/nor/csw?service=CSW&request=GetRecordById&version=2.0.2&outputSchema=http://www.isotc211.org/2005/gmd&elementSetName=full&id=41435fda-93ba-48a8-bd56-79a9287b6dad>
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

- **lenke**: <https://nap.ft.dibk.no/services/wms/kommuneplaner/?service=WMS&request=GetCapabilities>
  **relasjon**: alternate
  **type**: text/html
  **tittel**: Kartvisning

- **lenke**: #!?zoom=3&lon=306722&lat=7197864&wms=<https://nap.ft.dibk.no/services/wms/kommuneplaner/>
  **relasjon**: service
  **type**: text/html
  **tittel**: Tjeneste

## Tilleggsinformasjon

Det er kun de geografiske dataene (vektordataene) av arealdelen som er tilgjengelige for nedlasting. De tilhørende plandokumenter finnes i kommunenes planregistre. Det ligger en lenke på planområdene i de geografiske dataene som peker til kommunenes planregistre, og dermed gjør dokumentene lettere tilgjengelig for brukerne.
