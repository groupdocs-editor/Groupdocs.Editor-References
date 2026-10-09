---
title: "FontExtractionOptions"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Font-Extraktionsoptionen steuern, welche Schriftarten extrahiert werden sollen und von wo."
type: docs
weight: 18
url: /de/nodejs-java/com.groupdocs.editor.options/fontextractionoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontExtractionOptions
```

Font-Extraktionsoptionen steuern, welche Schriftarten extrahiert werden sollen und von
wo

## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [NotExtract](#NotExtract) | Extrahiert keine Schriftartressource, weder aus dem Dokument noch aus dem |
System.
|
|  | [ExtractAllEmbedded](#ExtractAllEmbedded) | Extrahiert alle Schriftartressourcen, die in das Eingabe‑Word eingebettet sind |
Dokument, unabhängig davon, ob sie benutzerdefiniert oder systemseitig sind.
|
|  | [ExtractEmbeddedWithoutSystem](#ExtractEmbeddedWithoutSystem) | Extrahiert nur jene eingebetteten Schriftartressourcen, die benutzerdefiniert sind (nicht |
system)
|
|  | [ExtractAll](#ExtractAll) | Versucht, alle Schriftarten zu extrahieren, die im Eingabe‑WordProcessing verwendet werden |
Dokument, einschließlich Systemschriftarten.
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFontExtractionOptions()](#getFontExtractionOptions--) |  |
### NotExtract {#NotExtract}
```
public static final int NotExtract
```


Extrahiert keine Schriftartressource, weder aus dem Dokument noch aus dem
System. Standardwert.


### ExtractAllEmbedded {#ExtractAllEmbedded}
```
public static final int ExtractAllEmbedded
```


Extrahiert alle Schriftartressourcen, die in das Eingabe‑Word eingebettet sind
Dokument, unabhängig davon, ob sie benutzerdefiniert oder systemseitig sind.


*** ** * ** ***

Der Konverter findet und extrahiert alle 100 % Schriftartressourcen, die in das Eingabe‑WordProcessing‑Dokument eingebettet sind, bestimmt jedoch nicht, ob sie systemseitig oder benutzerdefiniert sind; er greift überhaupt nicht auf die Windows‑Registry oder Systemordner zu.

<br />



### ExtractEmbeddedWithoutSystem {#ExtractEmbeddedWithoutSystem}
```
public static final int ExtractEmbeddedWithoutSystem
```


Extrahiert nur jene eingebetteten Schriftartressourcen, die benutzerdefiniert sind (nicht
system)


*** ** * ** ***

Der Konverter findet und extrahiert alle eingebetteten Schriftartressourcen und versucht anschließend zu bestimmen, welche dieser Schriftarten systemseitig und welche nicht sind. Um dies zu erreichen, versucht der Konverter, eine Liste aller Systemschriftarten mithilfe der Windows‑Registry und Systemordner zu erhalten und vergleicht diese Liste anschließend mit dem Satz eingebetteter Schriftarten. Infolgedessen wird nur die Teilmenge jener eingebetteten Schriftarten zurückgegeben, die im System nicht gefunden wurden.

<br />



### ExtractAll {#ExtractAll}
```
public static final int ExtractAll
```


Versucht, alle Schriftarten zu extrahieren, die im Eingabe‑WordProcessing verwendet werden
Dokument, einschließlich Systemschriftarten.


*** ** * ** ***

Der Konverter analysiert ein Eingabe‑WordProcessing‑Dokument und findet alle dort verwendeten Schriftarten. Wenn alle diese Schriftarten in das Eingabedokument eingebettet sind, extrahiert und gibt der Konverter sie zurück. Andernfalls, wenn eine Sammlung eingebetteter Schriftarten nicht alle im Dokument verwendeten Schriftarten abdeckt oder leer ist, versucht der Konverter, diese Schriftartressourcen aus dem System zu extrahieren, indem er die Windows‑Registry und Systemordner verwendet.

<br />



### getFontExtractionOptions() {#getFontExtractionOptions--}
```
public static int[] getFontExtractionOptions()
```




**Returns:**
int[]
