---
title: "PdfCompliance"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Specifica il livello di conformità agli standard PDF"
type: docs
weight: 28
url: /it/nodejs-java/com.groupdocs.editor.options/pdfcompliance/
---
**Inheritance:**
java.lang.Object
```
public final class PdfCompliance
```

Specifica il livello di conformità agli standard PDF

## Campi

| Campo | Descrizione |
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


Standard PDF/A-1a. Questo livello include tutti i requisiti di PDF/A-1b e richiede inoltre che la struttura del documento sia inclusa
(nota anche come "taggato"), con l'obiettivo di garantire che il contenuto del documento possa essere ricercato e riutilizzato.

<br />

*** ** * ** ***

Nota che l'esportazione della struttura del documento aumenta significativamente il consumo di memoria, soprattutto per i documenti di grandi dimensioni.

<br />



### PdfA1b {#PdfA1b}
```
public static final int PdfA1b
```


PDF/A-1b (ISO 19005-1). PDF/A-1b ha l'obiettivo di garantire una riproduzione affidabile dell'aspetto visivo del documento.


### PdfA2a {#PdfA2a}
```
public static final int PdfA2a
```


Standard PDF/A-2a (ISO 19005-2). Questo livello include tutti i requisiti di PDF/A-2u e richiede inoltre che la struttura del documento sia inclusa (nota anche come "taggato"), con l'obiettivo di garantire che il contenuto del documento possa essere ricercato e riutilizzato.

<br />

*** ** * ** ***

Nota che l'esportazione della struttura del documento aumenta significativamente il consumo di memoria, soprattutto per i documenti di grandi dimensioni.

<br />



### PdfA2u {#PdfA2u}
```
public static final int PdfA2u
```


Standard PDF/A-2u (ISO 19005-2). PDF/A-2u ha l'obiettivo di preservare l'aspetto visivo statico del documento nel tempo, indipendente dagli strumenti e dai sistemi utilizzati per creare, archiviare o renderizzare i file. Inoltre, qualsiasi testo contenuto nel documento può essere estratto in modo affidabile come una serie di punti di codice Unicode.


### PdfUa1 {#PdfUa1}
```
public static final int PdfUa1
```


Standard PDF/UA-1 (ISO 14289-1). Lo scopo principale di PDF/UA è definire come rappresentare i documenti elettronici nel formato PDF in modo da rendere il file accessibile.


