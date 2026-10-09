---
title: "WordProcessingEditOptions"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Ermöglicht das Angeben benutzerdefinierter Optionen zum Bearbeiten von Dokumenten aller unterstützten WordProcessing‑Words‑konformen Formate wie DOCX, RTF, ODT usw."
type: docs
weight: 44
url: /de/nodejs-java/com.groupdocs.editor.options/wordprocessingeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class WordProcessingEditOptions implements IEditOptions
```

Ermöglicht das Angeben benutzerdefinierter Optionen zum Bearbeiten von Dokumenten aller unterstützten
WordProcessing‑ (Words‑konforme) Formate wie DOC(X), RTF, ODT usw.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [WordProcessingEditOptions()](#WordProcessingEditOptions--) | Erstellt und gibt eine neue Instanz von WordProcessingEditOptions zurück. |
Klasse, bei der alle Optionen auf ihre Standardwerte gesetzt sind.
|
|  | [WordProcessingEditOptions(boolean enablePagination)](#WordProcessingEditOptions-boolean-) | Erstellt und gibt eine neue Instanz von WordProcessingEditOptions zurück. |
Klasse mit festgelegter Paginierung und allen anderen Optionen auf Standardwerten.
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Ermöglicht das Aktivieren oder Deaktivieren der Seitennummerierung im resultierenden HTML-Dokument. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Ermöglicht das Aktivieren oder Deaktivieren der Seitennummerierung im resultierenden HTML-Dokument. |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | Gibt an, ob Sprachinformationen in das HTML‑Markup exportiert werden |
in Form von 'lang'-HTML‑Attributen.
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | Gibt an, ob Sprachinformationen in das HTML‑Markup exportiert werden |
in Form von 'lang'-HTML‑Attributen.
|
|  | [getExtractOnlyUsedFont()](#getExtractOnlyUsedFont--) | Liest oder setzt einen Wert, der angibt, ob nur Schriftressourcen extrahiert werden, die |
im Textinhalt des Dokuments verwendet werden.
|
|  | [setExtractOnlyUsedFont(boolean value)](#setExtractOnlyUsedFont-boolean-) | Liest oder setzt einen Wert, der angibt, ob nur Schriftressourcen extrahiert werden, die |
im Textinhalt des Dokuments verwendet werden.
|
|  | [getFontExtraction()](#getFontExtraction--) | Verantwortlich für das Extrahieren von Schriftressourcen, die in der Eingabe |
WordProcessing‑Dokument.
|
|  | [setFontExtraction(int value)](#setFontExtraction-int-) | Verantwortlich für das Extrahieren von Schriftressourcen, die in der Eingabe |
WordProcessing‑Dokument.
|
|  | [getInputControlsClassName()](#getInputControlsClassName--) | Ermöglicht die Angabe eines Klassennamens, der dem Attribut 'class' zugewiesen wird |
Attribute in jedem HTML-Element, das ein Feld in der Eingabe darstellt
WordProcessing‑Dokument.
|
|  | [setInputControlsClassName(String value)](#setInputControlsClassName-java.lang.String-) | Ermöglicht die Angabe eines Klassennamens, der dem Attribut 'class' zugewiesen wird |
Attribute in jedem HTML-Element, das ein Feld in der Eingabe darstellt
WordProcessing‑Dokument.
|
|  | [getUseInlineStyles()](#getUseInlineStyles--) | Steuert, wo die Stil- und Formatierungsdaten des Eingabe‑WordProcessing‑Dokuments gespeichert werden: in externem Stylesheet ( |
false
) oder als Inline‑Styles im HTML‑Markup (
true
).
|
|  | [setUseInlineStyles(boolean value)](#setUseInlineStyles-boolean-) | Steuert, wo die Stil- und Formatierungsdaten des Eingabe‑WordProcessing‑Dokuments gespeichert werden: in externem Stylesheet ( |
false
) oder als Inline‑Styles im HTML‑Markup (
true
).
|
### WordProcessingEditOptions() {#WordProcessingEditOptions--}
```
public WordProcessingEditOptions()
```


Erstellt und gibt eine neue Instanz von WordProcessingEditOptions zurück.
Klasse, bei der alle Optionen auf ihre Standardwerte gesetzt sind.


### WordProcessingEditOptions(boolean enablePagination) {#WordProcessingEditOptions-boolean-}
```
public WordProcessingEditOptions(boolean enablePagination)
```


Erstellt und gibt eine neue Instanz von WordProcessingEditOptions zurück.
Klasse mit festgelegter Paginierung und allen anderen Optionen auf Standardwerten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | enablePagination | boolesch | Paginierungs‑Flag, das die HTML‑Ausgabe für den Seitenmodus aktiviert |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Ermöglicht das Aktivieren oder Deaktivieren der Seitennummerierung im resultierenden HTML-Dokument. Durch
Standard ist deaktiviert (false).


**Returns:**
boolesch
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Ermöglicht das Aktivieren oder Deaktivieren der Seitennummerierung im resultierenden HTML-Dokument. Durch
Standard ist deaktiviert (false).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


Gibt an, ob Sprachinformationen in das HTML‑Markup exportiert werden
eine Form von 'lang'-HTML‑Attributen. Diese Option kann für Round‑Trip nützlich sein
Konvertierung von mehrsprachigen Dokumenten. Standardmäßig ist sie deaktiviert
(false).


**Returns:**
boolesch
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


Gibt an, ob Sprachinformationen in das HTML‑Markup exportiert werden
eine Form von 'lang'-HTML‑Attributen. Diese Option kann für Round‑Trip nützlich sein
Konvertierung von mehrsprachigen Dokumenten. Standardmäßig ist sie deaktiviert
(false).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### getExtractOnlyUsedFont() {#getExtractOnlyUsedFont--}
```
public final boolean getExtractOnlyUsedFont()
```


Liest oder setzt einen Wert, der angibt, ob nur Schriftressourcen extrahiert werden, die
im Textinhalt des Dokuments verwendet werden.
Wert:  true  wenn nur jene Schriftartressourcen extrahiert werden sollen, die im Textinhalt des Dokuments verwendet werden; andernfalls  false . Standardwert ist  false .


*** ** * ** ***

Nicht alle im WordProcessing‑Dokument verwendeten Schriftarten werden zu 100 % direkt (auf Text) angewendet. Es kann vorkommen, dass eine Schriftart im Dokument referenziert und sogar eingebettet ist, aber auf keinen Textteil angewendet wird. Zum Beispiel kann eine Schriftart an einen Stil gebunden sein, dieser Stil jedoch auf keinen Textabschnitt angewendet werden. Diese Option steuert, wie solche Fälle verarbeitet werden.

<br />



**Returns:**
boolesch
### setExtractOnlyUsedFont(boolean value) {#setExtractOnlyUsedFont-boolean-}
```
public final void setExtractOnlyUsedFont(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob nur Schriftressourcen extrahiert werden, die
im Textinhalt des Dokuments verwendet werden.
Wert:  true  wenn nur jene Schriftartressourcen extrahiert werden sollen, die im Textinhalt des Dokuments verwendet werden; andernfalls  false . Standardwert ist  false .


*** ** * ** ***

Nicht alle im WordProcessing‑Dokument verwendeten Schriftarten werden zu 100 % direkt (auf Text) angewendet. Es kann vorkommen, dass eine Schriftart im Dokument referenziert und sogar eingebettet ist, aber auf keinen Textteil angewendet wird. Zum Beispiel kann eine Schriftart an einen Stil gebunden sein, dieser Stil jedoch auf keinen Textabschnitt angewendet werden. Diese Option steuert, wie solche Fälle verarbeitet werden.

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### getFontExtraction() {#getFontExtraction--}
```
public final int getFontExtraction()
```


Verantwortlich für das Extrahieren von Schriftressourcen, die in der Eingabe
WordProcessing‑Dokument. Standardmäßig werden keine Schriftarten extrahiert
(NotExtract).


**Returns:**
int
### setFontExtraction(int value) {#setFontExtraction-int-}
```
public final void setFontExtraction(int value)
```


Verantwortlich für das Extrahieren von Schriftressourcen, die in der Eingabe
WordProcessing‑Dokument. Standardmäßig werden keine Schriftarten extrahiert
(NotExtract).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getInputControlsClassName() {#getInputControlsClassName--}
```
public final String getInputControlsClassName()
```


Ermöglicht die Angabe eines Klassennamens, der dem Attribut 'class' zugewiesen wird
Attribute in jedem HTML-Element, das ein Feld in der Eingabe darstellt
WordProcessing‑Dokument. Standardmäßig ist NULL – 'class'-Attribute werden nicht
angewendet.


*** ** * ** ***

Fast alle Formate der WordProcessing‑Formatfamilie enthalten Felder \u2014 spezifische Dokumenten‑Entitäten, die es ermöglichen, Eingabedaten von Benutzern zu erhalten. Es gibt eine große Vielfalt an Feldern: Textfelder, Kontrollkästchen, Kombinationsfelder, Dropdown‑Listen, Schaltflächen, Datums‑/Uhrzeit‑Picker usw. All diese werden in die am besten geeigneten HTML‑Strukturen und -Elemente übersetzt, wobei die eingegebenen Benutzerdaten erhalten bleiben, falls sie im Eingabedokument vorhanden sind. In bestimmten Anwendungsfällen ist es erforderlich, nur die eingegebenen Daten clientseitig zu sammeln, anstatt den gesamten Dokumentinhalt zu bearbeiten. Dafür muss man die Eingabesteuerelemente auf irgendeine Weise identifizieren, um sie clientseitig mit ihren Daten abzurufen. Diese Eigenschaft ermöglicht die Angabe eines Klassennamens, der für jedes Eingabesteuerelement im HTML‑Markup angewendet wird, sodass der Client‑Code die HTML‑Dokumentstruktur durchlaufen und die Daten sammeln kann.

<br />



**Returns:**
java.lang.String
### setInputControlsClassName(String value) {#setInputControlsClassName-java.lang.String-}
```
public final void setInputControlsClassName(String value)
```


Ermöglicht die Angabe eines Klassennamens, der dem Attribut 'class' zugewiesen wird
Attribute in jedem HTML-Element, das ein Feld in der Eingabe darstellt
WordProcessing‑Dokument. Standardmäßig ist NULL – 'class'-Attribute werden nicht
angewendet.


*** ** * ** ***

Fast alle Formate der WordProcessing‑Formatfamilie enthalten Felder \u2014 spezifische Dokumenten‑Entitäten, die es ermöglichen, Eingabedaten von Benutzern zu erhalten. Es gibt eine große Vielfalt an Feldern: Textfelder, Kontrollkästchen, Kombinationsfelder, Dropdown‑Listen, Schaltflächen, Datums‑/Uhrzeit‑Picker usw. All diese werden in die am besten geeigneten HTML‑Strukturen und -Elemente übersetzt, wobei die eingegebenen Benutzerdaten erhalten bleiben, falls sie im Eingabedokument vorhanden sind. In bestimmten Anwendungsfällen ist es erforderlich, nur die eingegebenen Daten clientseitig zu sammeln, anstatt den gesamten Dokumentinhalt zu bearbeiten. Dafür muss man die Eingabesteuerelemente auf irgendeine Weise identifizieren, um sie clientseitig mit ihren Daten abzurufen. Diese Eigenschaft ermöglicht die Angabe eines Klassennamens, der für jedes Eingabesteuerelement im HTML‑Markup angewendet wird, sodass der Client‑Code die HTML‑Dokumentstruktur durchlaufen und die Daten sammeln kann.

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
) oder als Inline‑Styles im HTML‑Markup (
true
). Standardmäßig werden externe Styles verwendet (
false
).


**Returns:**
boolesch
### setUseInlineStyles(boolean value) {#setUseInlineStyles-boolean-}
```
public final void setUseInlineStyles(boolean value)
```


Steuert, wo die Stil- und Formatierungsdaten des Eingabe‑WordProcessing‑Dokuments gespeichert werden: in externem Stylesheet (
false
) oder als Inline‑Styles im HTML‑Markup (
true
). Standardmäßig werden externe Styles verwendet (
false
).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

