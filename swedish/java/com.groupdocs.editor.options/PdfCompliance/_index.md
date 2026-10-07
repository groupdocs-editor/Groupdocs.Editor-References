---
title: "PdfCompliance"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Anger PDF-standardernas efterlevnadsnivå."
type: docs
weight: 28
url: /sv/java/com.groupdocs.editor.options/pdfcompliance/
---
**Inheritance:**
java.lang.Object
```
public final class PdfCompliance
```

Anger PDF-standardernas efterlevnadsnivå.

## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [Pdf17](#Pdf17) | PDF 1.7 (ISO 32000-1) standard |
|
|  | [Pdf20](#Pdf20) | PDF 2.0 (ISO 32000-2) standard |
|
|  | [PdfA1a](#PdfA1a) | PDF/A-1a standard. |
|
|  | [PdfA1b](#PdfA1b) | PDF/A-1b (ISO 19005-1). |
|
|  | [PdfA2a](#PdfA2a) | PDF/A-2a (ISO 19005-2) standard. |
|
|  | [PdfA2u](#PdfA2u) | PDF/A-2u (ISO 19005-2) standard. |
|
|  | [PdfUa1](#PdfUa1) | PDF/UA-1 (ISO 14289-1) standard. |
|
### Pdf17 {#Pdf17}
```
public static final int Pdf17
```


PDF 1.7 (ISO 32000-1) standard


### Pdf20 {#Pdf20}
```
public static final int Pdf20
```


PDF 2.0 (ISO 32000-2) standard


### PdfA1a {#PdfA1a}
```
public static final int PdfA1a
```


PDF/A-1a standard. Denna nivå inkluderar alla krav i PDF/A-1b och kräver dessutom att dokumentstrukturen inkluderas
(även känt som att vara \"taggad\"), med målet att säkerställa att dokumentinnehållet kan sökas och återanvändas.

<br />

*** ** * ** ***

Observera att export av dokumentstrukturen avsevärt ökar minnesförbrukningen, särskilt för stora dokument.

<br />



### PdfA1b {#PdfA1b}
```
public static final int PdfA1b
```


PDF/A-1b (ISO 19005-1). PDF/A-1b har som mål att säkerställa pålitlig reproduktion av dokumentets visuella utseende.


### PdfA2a {#PdfA2a}
```
public static final int PdfA2a
```


PDF/A-2a (ISO 19005-2) standard. Denna nivå inkluderar alla krav i PDF/A-2u och kräver dessutom att dokumentstrukturen inkluderas (även känt som att vara \"taggad\"), med målet att säkerställa att dokumentinnehållet kan sökas och återanvändas.

<br />

*** ** * ** ***

Observera att export av dokumentstrukturen avsevärt ökar minnesförbrukningen, särskilt för stora dokument.

<br />



### PdfA2u {#PdfA2u}
```
public static final int PdfA2u
```


PDF/A-2u (ISO 19005-2) standard. PDF/A-2u har som mål att bevara dokumentets statiska visuella utseende över tid, oberoende av de verktyg och system som används för att skapa, lagra eller rendera filerna. Dessutom kan all text i dokumentet på ett tillförlitligt sätt extraheras som en serie Unicode-kodpunkter.


### PdfUa1 {#PdfUa1}
```
public static final int PdfUa1
```


PDF/UA-1 (ISO 14289-1) standard. Det primära syftet med PDF/UA är att definiera hur elektroniska dokument ska representeras i PDF-formatet på ett sätt som gör filen tillgänglig.


