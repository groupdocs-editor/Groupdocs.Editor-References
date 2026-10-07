---
title: "PdfCompliance"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Specificeert het PDF‑normen‑compliance‑niveau."
type: docs
weight: 28
url: /nl/java/com.groupdocs.editor.options/pdfcompliance/
---
**Inheritance:**
java.lang.Object
```
public final class PdfCompliance
```

Specificeert het PDF‑normen‑compliance‑niveau.

## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [Pdf17](#Pdf17) | PDF 1.7 (ISO 32000-1) standaard |
|
|  | [Pdf20](#Pdf20) | PDF 2.0 (ISO 32000-2) standaard |
|
|  | [PdfA1a](#PdfA1a) | PDF/A-1a standaard. |
|
|  | [PdfA1b](#PdfA1b) | PDF/A-1b (ISO 19005-1). |
|
|  | [PdfA2a](#PdfA2a) | PDF/A-2a (ISO 19005-2) standaard. |
|
|  | [PdfA2u](#PdfA2u) | PDF/A-2u (ISO 19005-2) standaard. |
|
|  | [PdfUa1](#PdfUa1) | PDF/UA-1 (ISO 14289-1) standaard. |
|
### Pdf17 {#Pdf17}
```
public static final int Pdf17
```


PDF 1.7 (ISO 32000-1) standaard


### Pdf20 {#Pdf20}
```
public static final int Pdf20
```


PDF 2.0 (ISO 32000-2) standaard


### PdfA1a {#PdfA1a}
```
public static final int PdfA1a
```


PDF/A-1a standaard. Dit niveau omvat alle vereisten van PDF/A-1b en vereist bovendien dat de documentstructuur wordt opgenomen
(ook bekend als "tagged"), met als doel te zorgen dat documentinhoud kan worden doorzocht en hergebruikt.

<br />

*** ** * ** ***

Let op dat het exporteren van de documentstructuur het geheugenverbruik aanzienlijk verhoogt, vooral bij grote documenten.

<br />



### PdfA1b {#PdfA1b}
```
public static final int PdfA1b
```


PDF/A-1b (ISO 19005-1). PDF/A-1b heeft als doel een betrouwbare reproductie van het visuele uiterlijk van het document te waarborgen.


### PdfA2a {#PdfA2a}
```
public static final int PdfA2a
```


PDF/A-2a (ISO 19005-2) standaard. Dit niveau omvat alle eisen van PDF/A-2u en vereist bovendien dat de documentstructuur wordt opgenomen (ook bekend als "tagged"), met als doel te zorgen dat documentinhoud kan worden doorzocht en hergebruikt.

<br />

*** ** * ** ***

Let op dat het exporteren van de documentstructuur het geheugenverbruik aanzienlijk verhoogt, vooral bij grote documenten.

<br />



### PdfA2u {#PdfA2u}
```
public static final int PdfA2u
```


PDF/A-2u (ISO 19005-2) standaard. PDF/A-2u heeft als doel het statische visuele uiterlijk van het document in de loop van de tijd te behouden, onafhankelijk van de tools en systemen die worden gebruikt voor het maken, opslaan of renderen van de bestanden. Bovendien kan alle tekst in het document betrouwbaar worden geëxtraheerd als een reeks Unicode‑codepunten.


### PdfUa1 {#PdfUa1}
```
public static final int PdfUa1
```


PDF/UA-1 (ISO 14289-1) standaard. Het primaire doel van PDF/UA is om te definiëren hoe elektronische documenten in het PDF‑formaat worden weergegeven op een manier die de toegankelijkheid van het bestand mogelijk maakt.


