---
title: "WordProcessingEditOptions"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Ermöglicht das Angeben benutzerdefinierter Optionen zum Bearbeiten von Dokumenten aller unterstützten WordProcessing Words-konformen Formate wie DOCX, RTF, ODT usw."
type: docs
weight: 44
url: /de/java/com.groupdocs.editor.options/wordprocessingeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class WordProcessingEditOptions implements IEditOptions
```

Ermöglicht das Angeben benutzerdefinierter Optionen zum Bearbeiten von Dokumenten aller unterstützten
WordProcessing (Words-konforme) Formate wie DOC(X), RTF, ODT usw.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [WordProcessingEditOptions()](#WordProcessingEditOptions--) | Erstellt und gibt eine neue Instanz von WordProcessingEditOptions zurück |
Klasse, bei der alle Optionen auf ihre Standardwerte gesetzt sind
|
|  | [WordProcessingEditOptions(boolean enablePagination)](#WordProcessingEditOptions-boolean-) | Erstellt und gibt eine neue Instanz von WordProcessingEditOptions zurück |
Klasse mit festgelegter Pagination und allen anderen Optionen auf Standardwerten
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Ermöglicht das Aktivieren oder Deaktivieren der Seitennummerierung im resultierenden HTML-Dokument. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Ermöglicht das Aktivieren oder Deaktivieren der Seitennummerierung im resultierenden HTML-Dokument. |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | Gibt an, ob Sprachinformationen in das HTML-Markup exportiert werden |
in Form von 'lang'-HTML-Attributen.
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | Gibt an, ob Sprachinformationen in das HTML-Markup exportiert werden |
in Form von 'lang'-HTML-Attributen.
|
|  | [getExtractOnlyUsedFont()](#getExtractOnlyUsedFont--) | Liest oder setzt einen Wert, der angibt, ob nur Schriftressourcen extrahiert werden, die |
im Textinhalt des Dokuments verwendet werden.
|
|  | [setExtractOnlyUsedFont(boolean value)](#setExtractOnlyUsedFont-boolean-) | Liest oder setzt einen Wert, der angibt, ob nur Schriftressourcen extrahiert werden, die |
im Textinhalt des Dokuments verwendet werden.
|
|  | [getFontExtraction()](#getFontExtraction--) | Verantwortlich für das Extrahieren von Schriftressourcen, die in der Eingabe |
WordProcessing-Dokument.
|
|  | [setFontExtraction(int value)](#setFontExtraction-int-) | Verantwortlich für das Extrahieren von Schriftressourcen, die in der Eingabe |
WordProcessing-Dokument.
|
|  | [getInputControlsClassName()](#getInputControlsClassName--) | Ermöglicht das Angeben eines Klassennamens, der in das 'class'-Attribut eingefügt wird |
Attribute jedes HTML-Elements, das ein Feld in der Eingabe darstellt
WordProcessing-Dokument.
|
|  | [setInputControlsClassName(String value)](#setInputControlsClassName-java.lang.String-) | Ermöglicht das Angeben eines Klassennamens, der in das 'class'-Attribut eingefügt wird |
Attribute jedes HTML-Elements, das ein Feld in der Eingabe darstellt
WordProcessing-Dokument.
|
|  | [getUseInlineStyles()](#getUseInlineStyles--) | Steuert, wo die Stil- und Formatierungsdaten des Eingabe‑WordProcessing‑Dokuments gespeichert werden: in externem Stylesheet ( |
false
) oder als Inline‑Stile im HTML-Markup (
true
).
|
|  | [setUseInlineStyles(boolean value)](#setUseInlineStyles-boolean-) | Steuert, wo die Stil- und Formatierungsdaten des Eingabe‑WordProcessing‑Dokuments gespeichert werden: in externem Stylesheet ( |
false
) oder als Inline‑Stile im HTML-Markup (
true
).
|
### WordProcessingEditOptions() {#WordProcessingEditOptions--}
```
public WordProcessingEditOptions()
```


Erstellt und gibt eine neue Instanz von WordProcessingEditOptions zurück
Klasse, bei der alle Optionen auf ihre Standardwerte gesetzt sind


### WordProcessingEditOptions(boolean enablePagination) {#WordProcessingEditOptions-boolean-}
```
public WordProcessingEditOptions(boolean enablePagination)
```


Erstellt und gibt eine neue Instanz von WordProcessingEditOptions zurück
Klasse mit festgelegter Pagination und allen anderen Optionen auf Standardwerten


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | enablePagination | boolean | Pagination-Flag, das HTML-Ausgabe aktiviert, angepasst für den Seitenmodus |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Ermöglicht das Aktivieren oder Deaktivieren der Seitennummerierung im resultierenden HTML‑Dokument. Durch
Standard ist deaktiviert (false).


**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Ermöglicht das Aktivieren oder Deaktivieren der Seitennummerierung im resultierenden HTML‑Dokument. Durch
Standard ist deaktiviert (false).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


Gibt an, ob Sprachinformationen in das HTML-Markup exportiert werden
in Form von 'lang'-HTML-Attributen. Diese Option kann für roundtrip nützlich sein
Konvertierung der mehrsprachigen Dokumente. Standardmäßig ist sie deaktiviert
(false).


**Returns:**
boolean
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


Gibt an, ob Sprachinformationen in das HTML-Markup exportiert werden
in Form von 'lang'-HTML-Attributen. Diese Option kann für roundtrip nützlich sein
Konvertierung der mehrsprachigen Dokumente. Standardmäßig ist sie deaktiviert
(false).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getExtractOnlyUsedFont() {#getExtractOnlyUsedFont--}
```
public final boolean getExtractOnlyUsedFont()
```


Liest oder setzt einen Wert, der angibt, ob nur Schriftressourcen extrahiert werden, die
im Textinhalt des Dokuments verwendet werden.
Wert:  true  wenn nur jene Schriftressourcen extrahiert werden sollen, die im Textinhalt des Dokuments verwendet werden; andernfalls  false . Der Standardwert ist  false .


*** ** * ** ***

Nicht alle Schriften, die im WordProcessing-Dokument verwendet werden, werden zu 100 % direkt (auf Text angewendet) genutzt. Es kann vorkommen, dass eine Schrift im Dokument referenziert und sogar eingebettet ist, aber auf keinen Textteil angewendet wird. Zum Beispiel kann eine Schrift an einen Stil angehängt sein, dieser Stil jedoch auf keinen Textteil angewendet werden. Diese Option steuert, wie solche Fälle verarbeitet werden.

<br />



**Returns:**
boolean
### setExtractOnlyUsedFont(boolean value) {#setExtractOnlyUsedFont-boolean-}
```
public final void setExtractOnlyUsedFont(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob nur Schriftressourcen extrahiert werden, die
im Textinhalt des Dokuments verwendet werden.
Wert:  true  wenn nur jene Schriftressourcen extrahiert werden sollen, die im Textinhalt des Dokuments verwendet werden; andernfalls  false . Der Standardwert ist  false .


*** ** * ** ***

Nicht alle Schriften, die im WordProcessing-Dokument verwendet werden, werden zu 100 % direkt (auf Text angewendet) genutzt. Es kann vorkommen, dass eine Schrift im Dokument referenziert und sogar eingebettet ist, aber auf keinen Textteil angewendet wird. Zum Beispiel kann eine Schrift an einen Stil angehängt sein, dieser Stil jedoch auf keinen Textteil angewendet werden. Diese Option steuert, wie solche Fälle verarbeitet werden.

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getFontExtraction() {#getFontExtraction--}
```
public final int getFontExtraction()
```


Verantwortlich für das Extrahieren von Schriftressourcen, die in der Eingabe
WordProcessing-Dokument. Standardmäßig werden keine Schriften extrahiert
(NotExtract).


**Returns:**
int
### setFontExtraction(int value) {#setFontExtraction-int-}
```
public final void setFontExtraction(int value)
```


Verantwortlich für das Extrahieren von Schriftressourcen, die in der Eingabe
WordProcessing-Dokument. Standardmäßig werden keine Schriften extrahiert
(NotExtract).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getInputControlsClassName() {#getInputControlsClassName--}
```
public final String getInputControlsClassName()
```


Ermöglicht das Angeben eines Klassennamens, der in das 'class'-Attribut eingefügt wird
Attribute jedes HTML-Elements, das ein Feld in der Eingabe darstellt
WordProcessing-Dokument. Standardmäßig ist NULL – 'class'-Attribute sind nicht
angewendet.


*** ** * ** ***

Fast alle Formate aus der WordProcessing-Formatfamilie enthalten Felder \\u2014 spezifische Dokumenten‑Entitäten, die es ermöglichen, Eingabedaten von Benutzern zu erhalten. Es gibt eine große Vielfalt an Feldern: Textfelder, Kontrollkästchen, Kombinationsfelder, Dropdown‑Listen, Schaltflächen, Datums‑/Uhrzeit‑Auswähler usw. Alle werden in die am besten geeigneten HTML‑Strukturen und -Elemente übersetzt, wobei die eingegebenen Benutzerdaten erhalten bleiben, falls sie im Eingabedokument vorhanden sind. In bestimmten Anwendungsfällen ist es erforderlich, nur die eingegebenen Daten clientseitig zu sammeln, anstatt den gesamten Dokumentinhalt zu bearbeiten. Dafür muss man die Eingabesteuerelemente auf irgendeine Weise identifizieren, um sie mit ihren Daten clientseitig abzurufen. Diese Eigenschaft ermöglicht die Angabe eines Klassennamens, der für jedes Eingabesteuerelement im HTML‑Markup angewendet wird, sodass der Client‑Code die HTML‑Dokumentstruktur traversieren und Daten sammeln kann.

<br />



**Returns:**
java.lang.String
### setInputControlsClassName(String value) {#setInputControlsClassName-java.lang.String-}
```
public final void setInputControlsClassName(String value)
```


Ermöglicht das Angeben eines Klassennamens, der in das 'class'-Attribut eingefügt wird
Attribute jedes HTML-Elements, das ein Feld in der Eingabe darstellt
WordProcessing-Dokument. Standardmäßig ist NULL – 'class'-Attribute sind nicht
angewendet.


*** ** * ** ***

Fast alle Formate aus der WordProcessing-Formatfamilie enthalten Felder \\u2014 spezifische Dokumenten‑Entitäten, die es ermöglichen, Eingabedaten von Benutzern zu erhalten. Es gibt eine große Vielfalt an Feldern: Textfelder, Kontrollkästchen, Kombinationsfelder, Dropdown‑Listen, Schaltflächen, Datums‑/Uhrzeit‑Auswähler usw. Alle werden in die am besten geeigneten HTML‑Strukturen und -Elemente übersetzt, wobei die eingegebenen Benutzerdaten erhalten bleiben, falls sie im Eingabedokument vorhanden sind. In bestimmten Anwendungsfällen ist es erforderlich, nur die eingegebenen Daten clientseitig zu sammeln, anstatt den gesamten Dokumentinhalt zu bearbeiten. Dafür muss man die Eingabesteuerelemente auf irgendeine Weise identifizieren, um sie mit ihren Daten clientseitig abzurufen. Diese Eigenschaft ermöglicht die Angabe eines Klassennamens, der für jedes Eingabesteuerelement im HTML‑Markup angewendet wird, sodass der Client‑Code die HTML‑Dokumentstruktur traversieren und Daten sammeln kann.

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getUseInlineStyles() {#getUseInlineStyles--}
```
public final boolean getUseInlineStyles()
```


Steuert, wo die Stil- und Formatierungsdaten des Eingabe‑WordProcessing‑Dokuments gespeichert werden: in externem Stylesheet (
false
) oder als Inline‑Stile im HTML-Markup (
true
). Standardmäßig werden externe Stile verwendet (
false
).


**Returns:**
boolean
### setUseInlineStyles(boolean value) {#setUseInlineStyles-boolean-}
```
public final void setUseInlineStyles(boolean value)
```


Steuert, wo die Stil- und Formatierungsdaten des Eingabe‑WordProcessing‑Dokuments gespeichert werden: in externem Stylesheet (
false
) oder als Inline‑Stile im HTML-Markup (
true
). Standardmäßig werden externe Stile verwendet (
false
).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

