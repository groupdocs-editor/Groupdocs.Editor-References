---
title: "EbookEditOptions"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Ermöglicht das Festlegen und Anpassen benutzerdefinierter Optionen zum Bearbeiten von E‑Book‑Dokumenten in allen unterstützten Formaten ePub, MOBI und AZW3."
type: docs
weight: 12
url: /de/nodejs-java/com.groupdocs.editor.options/ebookeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EbookEditOptions implements IEditOptions
```

Ermöglicht das Angeben und Anpassen benutzerdefinierter Optionen zum Bearbeiten von E‑Book‑Dokumenten in allen unterstützten Formaten: ePub, MOBI und AZW3.

<br />

*** ** * ** ***

Unterstützte E‑Book‑Formate:

1. [ePub](../https://docs.fileformat.com/ebook/epub/) (Elektronische Publikation)
2. [MOBI](../https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](../https://docs.fileformat.com/ebook/azw3/) (Kindle‑Format 8t)

<br />


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [EbookEditOptions()](#EbookEditOptions--) | Initialisiert eine neue Instanz der Klasse [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions), bei der alle Optionen auf ihre Standardwerte gesetzt sind. |
|
|  | [EbookEditOptions(boolean enablePagination)](#EbookEditOptions-boolean-) | Initialisiert eine neue Instanz der Klasse [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) mit dem angegebenen Seitennummerierungsmodus. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Ermöglicht das Aktivieren oder Deaktivieren der Seitennummerierung im resultierenden HTML-Dokument. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Ermöglicht das Aktivieren oder Deaktivieren der Seitennummerierung im resultierenden HTML-Dokument. |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | Gibt an, ob Sprachinformationen in Form von 'lang'-HTML‑Attributen in das HTML‑Markup exportiert werden. |
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | Gibt an, ob Sprachinformationen in Form von 'lang'-HTML‑Attributen in das HTML‑Markup exportiert werden. |
|
### EbookEditOptions() {#EbookEditOptions--}
```
public EbookEditOptions()
```


Initialisiert eine neue Instanz der Klasse [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions), bei der alle Optionen auf ihre Standardwerte gesetzt sind.


### EbookEditOptions(boolean enablePagination) {#EbookEditOptions-boolean-}
```
public EbookEditOptions(boolean enablePagination)
```


Initialisiert eine neue Instanz der Klasse [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) mit dem angegebenen Seitennummerierungsmodus.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | enablePagination | boolesch | Aktiviert ( true ) oder deaktiviert ( false ) die Seitennummerierung des E‑Book‑Inhalts im resultierenden HTML‑Dokument. Standardmäßig ist sie deaktiviert ( false ). |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Ermöglicht das Aktivieren oder Deaktivieren der Seitennummerierung im resultierenden HTML‑Dokument. Standardmäßig ist sie deaktiviert (
false
).

<br />

*** ** * ** ***

Im Kern sind die meisten e‑Book‑Formate intern ein Fließformat wie Office Open XML, bei dem der Inhalt ein zusammenhängender Block ist und in Kapitel, nicht in Seiten, aufgeteilt wird. Es enthält jedoch einige seitenspezifische Informationen wie Seitenzahlen, Fußnoten, Kopf‑/Fußzeilen usw. Einige e‑Book‑Reader teilen den Inhalt in Seiten auf, während andere (insbesondere mobile) — nicht. Diese Option ermöglicht die Kontrolle, wie der e‑Book‑Inhalt beim Bearbeiten in HTML/CSS dargestellt werden soll — im Fließ‑ (false) oder paginierten (true) Modus.

<br />



**Returns:**
boolesch
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Ermöglicht das Aktivieren oder Deaktivieren der Seitennummerierung im resultierenden HTML‑Dokument. Standardmäßig ist sie deaktiviert (
false
).

<br />

*** ** * ** ***

Im Kern sind die meisten e‑Book‑Formate intern ein Fließformat wie Office Open XML, bei dem der Inhalt ein zusammenhängender Block ist und in Kapitel, nicht in Seiten, aufgeteilt wird. Es enthält jedoch einige seitenspezifische Informationen wie Seitenzahlen, Fußnoten, Kopf‑/Fußzeilen usw. Einige e‑Book‑Reader teilen den Inhalt in Seiten auf, während andere (insbesondere mobile) — nicht. Diese Option ermöglicht die Kontrolle, wie der e‑Book‑Inhalt beim Bearbeiten in HTML/CSS dargestellt werden soll — im Fließ‑ (false) oder paginierten (true) Modus.

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


Gibt an, ob Sprachinformationen in Form von 'lang'-HTML‑Attributen in das HTML‑Markup exportiert werden.
Diese Option kann für die Rundreise‑Konvertierung von mehrsprachigen Dokumenten nützlich sein. Standardmäßig ist sie deaktiviert (
false
).


**Returns:**
boolesch
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


Gibt an, ob Sprachinformationen in Form von 'lang'-HTML‑Attributen in das HTML‑Markup exportiert werden.
Diese Option kann für die Rundreise‑Konvertierung von mehrsprachigen Dokumenten nützlich sein. Standardmäßig ist sie deaktiviert (
false
).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

