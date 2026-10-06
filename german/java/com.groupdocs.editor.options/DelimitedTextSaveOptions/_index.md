---
title: "DelimitedTextSaveOptions"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Enthält Optionen zum Erzeugen und Speichern von textbasierten Tabellenkalkulationsdokumenten (CSV, Tab-​basiert usw.), die einen Trennzeichen-​Delimiter verwenden."
type: docs
weight: 11
url: /de/java/com.groupdocs.editor.options/delimitedtextsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class DelimitedTextSaveOptions implements ISaveOptions
```

Enthält Optionen zum Erzeugen und Speichern von textbasierten Tabellenkalkulationsdokumenten
(CSV, Tab-​basiert usw.), die einen Trennzeichen (Delimiter) verwenden


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [DelimitedTextSaveOptions()](#DelimitedTextSaveOptions--) | Dieser parameterlose Konstruktor erstellt eine neue Instanz von DelimitedTextSaveOptions mit einem Semikolon (;) als Standard-​Trennzeichen (kann anschließend über |
Trennzeichen
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) Eigenschaft)
|
|  | [DelimitedTextSaveOptions(String separator)](#DelimitedTextSaveOptions-java.lang.String-) | Erstellt eine Instanz der Optionsklasse für delimited Text mit obligatorischem |
Trennzeichen (delimiter)
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | Ermöglicht die Angabe eines Zeichenketten‑Trennzeichens (delimiter) für textbasierte |
Tabellenkalkulationsdokumente
|
|  | [setSeparator(String value)](#setSeparator-java.lang.String-) | Ermöglicht die Angabe eines Zeichenketten‑Trennzeichens (delimiter) für textbasierte |
Tabellenkalkulationsdokumente
|
|  | [getEncoding()](#getEncoding--) | Ermöglicht das Festlegen einer Kodierung für das textbasierte Tabellenkalkulationsdokument. |
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Ermöglicht das Festlegen einer Kodierung für das textbasierte Tabellenkalkulationsdokument. |
|
|  | [getTrimLeadingBlankRowAndColumn()](#getTrimLeadingBlankRowAndColumn--) | Gibt an, ob führende leere Zeilen und Spalten wie |
was MS Excel macht
|
|  | [setTrimLeadingBlankRowAndColumn(boolean value)](#setTrimLeadingBlankRowAndColumn-boolean-) | Gibt an, ob führende leere Zeilen und Spalten wie |
was MS Excel macht
|
|  | [getKeepSeparatorsForBlankRow()](#getKeepSeparatorsForBlankRow--) | Gibt an, ob Trennzeichen für leere Zeilen ausgegeben werden sollen. |
|
|  | [setKeepSeparatorsForBlankRow(boolean value)](#setKeepSeparatorsForBlankRow-boolean-) | Gibt an, ob Trennzeichen für leere Zeilen ausgegeben werden sollen. |
|
### DelimitedTextSaveOptions() {#DelimitedTextSaveOptions--}
```
public DelimitedTextSaveOptions()
```


Dieser parameterlose Konstruktor erstellt eine neue Instanz von DelimitedTextSaveOptions mit einem Semikolon (;) als Standard-​Trennzeichen (kann anschließend über
Trennzeichen
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) Eigenschaft)


### DelimitedTextSaveOptions(String separator) {#DelimitedTextSaveOptions-java.lang.String-}
```
public DelimitedTextSaveOptions(String separator)
```


Erstellt eine Instanz der Optionsklasse für delimited Text mit obligatorischem
Trennzeichen (delimiter)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Trennzeichen | java.lang.String | Zeichenketten‑Trennzeichen (Delimiter) für textbasierte Tabellenkalkulationsdokumente |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


Ermöglicht die Angabe eines Zeichenketten‑Trennzeichens (delimiter) für textbasierte
Tabellenkalkulationsdokumente


**Returns:**
java.lang.String -
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


Ermöglicht die Angabe eines Zeichenketten‑Trennzeichens (delimiter) für textbasierte
Tabellenkalkulationsdokumente


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Ermöglicht das Festlegen einer Kodierung für das textbasierte Tabellenkalkulationsdokument. Durch
Standard (und wenn nicht angegeben) ist UTF8.


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Ermöglicht das Festlegen einer Kodierung für das textbasierte Tabellenkalkulationsdokument. Durch
Standard (und wenn nicht angegeben) ist UTF8.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.nio.charset.Charset |  |

### getTrimLeadingBlankRowAndColumn() {#getTrimLeadingBlankRowAndColumn--}
```
public final boolean getTrimLeadingBlankRowAndColumn()
```


Gibt an, ob führende leere Zeilen und Spalten wie
was MS Excel macht


**Returns:**
boolean -
### setTrimLeadingBlankRowAndColumn(boolean value) {#setTrimLeadingBlankRowAndColumn-boolean-}
```
public final void setTrimLeadingBlankRowAndColumn(boolean value)
```


Gibt an, ob führende leere Zeilen und Spalten wie
was MS Excel macht


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getKeepSeparatorsForBlankRow() {#getKeepSeparatorsForBlankRow--}
```
public final boolean getKeepSeparatorsForBlankRow()
```


Gibt an, ob Trennzeichen für leere Zeilen ausgegeben werden sollen. Standard
Der Wert ist false, was bedeutet, dass der Inhalt für leere Zeilen leer sein wird.


**Returns:**
boolean -
### setKeepSeparatorsForBlankRow(boolean value) {#setKeepSeparatorsForBlankRow-boolean-}
```
public final void setKeepSeparatorsForBlankRow(boolean value)
```


Gibt an, ob Trennzeichen für leere Zeilen ausgegeben werden sollen. Standard
Der Wert ist false, was bedeutet, dass der Inhalt für leere Zeilen leer sein wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

