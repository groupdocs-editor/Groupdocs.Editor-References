---
title: "PdfCompliance"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Gibt das Konformitätsniveau der PDF-Standards an"
type: docs
weight: 28
url: /de/nodejs-java/com.groupdocs.editor.options/pdfcompliance/
---
**Inheritance:**
java.lang.Object
```
public final class PdfCompliance
```

Gibt das Konformitätsniveau der PDF-Standards an

## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [Pdf17](#Pdf17) | PDF 1.7 (ISO 32000-1) Standard |
|
|  | [Pdf20](#Pdf20) | PDF 2.0 (ISO 32000-2) Standard |
|
|  | [PdfA1a](#PdfA1a) | PDF/A-1a Standard. |
|
|  | [PdfA1b](#PdfA1b) | PDF/A-1b (ISO 19005-1). |
|
|  | [PdfA2a](#PdfA2a) | PDF/A-2a (ISO 19005-2) Standard. |
|
|  | [PdfA2u](#PdfA2u) | PDF/A-2u (ISO 19005-2) Standard. |
|
|  | [PdfUa1](#PdfUa1) | PDF/UA-1 (ISO 14289-1) Standard. |
|
### Pdf17 {#Pdf17}
```
public static final int Pdf17
```


PDF 1.7 (ISO 32000-1) Standard


### Pdf20 {#Pdf20}
```
public static final int Pdf20
```


PDF 2.0 (ISO 32000-2) Standard


### PdfA1a {#PdfA1a}
```
public static final int PdfA1a
```


PDF/A-1a Standard. Diese Stufe beinhaltet alle Anforderungen von PDF/A-1b und verlangt zusätzlich, dass die Dokumentenstruktur enthalten ist
(auch als "tagged" bekannt), mit dem Ziel sicherzustellen, dass Dokumentinhalte durchsucht und wiederverwendet werden können.

<br />

*** ** * ** ***

Beachten Sie, dass das Exportieren der Dokumentenstruktur den Speicherverbrauch erheblich erhöht, insbesondere bei großen Dokumenten.

<br />



### PdfA1b {#PdfA1b}
```
public static final int PdfA1b
```


PDF/A-1b (ISO 19005-1). PDF/A-1b hat das Ziel, eine zuverlässige Reproduktion des visuellen Erscheinungsbildes des Dokuments sicherzustellen.


### PdfA2a {#PdfA2a}
```
public static final int PdfA2a
```


PDF/A-2a (ISO 19005-2) Standard. Diese Stufe beinhaltet alle Anforderungen von PDF/A-2u und verlangt zusätzlich, dass die Dokumentenstruktur enthalten ist (auch als "tagged" bekannt), mit dem Ziel, dass Dokumentinhalte durchsucht und wiederverwendet werden können.

<br />

*** ** * ** ***

Beachten Sie, dass das Exportieren der Dokumentenstruktur den Speicherverbrauch erheblich erhöht, insbesondere bei großen Dokumenten.

<br />



### PdfA2u {#PdfA2u}
```
public static final int PdfA2u
```


PDF/A-2u (ISO 19005-2) Standard. PDF/A-2u hat das Ziel, das statische visuelle Erscheinungsbild des Dokuments über die Zeit hinweg zu bewahren, unabhängig von den Werkzeugen und Systemen, die zum Erstellen, Speichern oder Rendern der Dateien verwendet werden. Zusätzlich kann jeder im Dokument enthaltene Text zuverlässig als Reihe von Unicode‑Codepunkten extrahiert werden.


### PdfUa1 {#PdfUa1}
```
public static final int PdfUa1
```


PDF/UA-1 (ISO 14289-1) Standard. Der Hauptzweck von PDF/UA besteht darin, zu definieren, wie elektronische Dokumente im PDF-Format dargestellt werden, sodass die Datei zugänglich ist.


