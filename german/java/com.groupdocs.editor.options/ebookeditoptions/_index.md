---
title: "EbookEditOptions"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Ermöglicht das Angeben und Anpassen benutzerdefinierter Optionen zum Bearbeiten von E‑Book‑Dokumenten in allen unterstützten Formaten ePub, MOBI und AZW3."
type: docs
weight: 12
url: /de/java/com.groupdocs.editor.options/ebookeditoptions/
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
|  | [EbookEditOptions(boolean enablePagination)](#EbookEditOptions-boolean-) | Initialisiert eine neue Instanz der Klasse [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) mit dem angegebenen Paginierungsmodus. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Ermöglicht das Aktivieren oder Deaktivieren der Seitennummerierung im resultierenden HTML-Dokument. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Ermöglicht das Aktivieren oder Deaktivieren der Seitennummerierung im resultierenden HTML-Dokument. |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | Gibt an, ob Sprachinformationen in Form von 'lang'-HTML-Attributen in das HTML-Markup exportiert werden. |
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | Gibt an, ob Sprachinformationen in Form von 'lang'-HTML-Attributen in das HTML-Markup exportiert werden. |
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


Initialisiert eine neue Instanz der Klasse [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) mit dem angegebenen Paginierungsmodus.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | enablePagination | boolean | Aktiviert ( true ) oder deaktiviert ( false ) die Paginierung des E‑Book‑Inhalts im resultierenden HTML-Dokument. Standardmäßig ist sie deaktiviert ( false ). |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Ermöglicht das Aktivieren oder Deaktivieren der Paginierung im resultierenden HTML-Dokument. Standardmäßig ist sie deaktiviert (
false
).

<br />

*** ** * ** ***

Im Kern sind die meisten E‑Book‑Formate intern ein Fließformat wie Office Open XML, bei dem der Inhalt ein zusammenhängendes Ganzes ist und in Kapitel, nicht jedoch in Seiten, aufgeteilt wird. Es enthält jedoch einige seitenbezogene Informationen wie Seitenzahlen, Fußnoten, Kopf‑/Fußzeilen usw. Einige E‑Book‑Reader teilen den E‑Book‑Inhalt in Seiten auf, während andere (insbesondere mobil) \\u2014 nicht. Diese Option ermöglicht es, zu steuern, wie der E‑Book‑Inhalt beim Bearbeiten in HTML/CSS dargestellt werden soll \\u2014 im Fließ‑ ( false ) oder im paginierten ( true ) Modus.

<br />



**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Ermöglicht das Aktivieren oder Deaktivieren der Paginierung im resultierenden HTML-Dokument. Standardmäßig ist sie deaktiviert (
false
).

<br />

*** ** * ** ***

Im Kern sind die meisten E‑Book‑Formate intern ein Fließformat wie Office Open XML, bei dem der Inhalt ein zusammenhängendes Ganzes ist und in Kapitel, nicht jedoch in Seiten, aufgeteilt wird. Es enthält jedoch einige seitenbezogene Informationen wie Seitenzahlen, Fußnoten, Kopf‑/Fußzeilen usw. Einige E‑Book‑Reader teilen den E‑Book‑Inhalt in Seiten auf, während andere (insbesondere mobil) \\u2014 nicht. Diese Option ermöglicht es, zu steuern, wie der E‑Book‑Inhalt beim Bearbeiten in HTML/CSS dargestellt werden soll \\u2014 im Fließ‑ ( false ) oder im paginierten ( true ) Modus.

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


Gibt an, ob Sprachinformationen in Form von 'lang'-HTML-Attributen in das HTML-Markup exportiert werden.
Diese Option kann für die Rundreise‑Konvertierung mehrsprachiger Dokumente nützlich sein. Standardmäßig ist sie deaktiviert (
false
).


**Returns:**
boolean
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


Gibt an, ob Sprachinformationen in Form von 'lang'-HTML-Attributen in das HTML-Markup exportiert werden.
Diese Option kann für die Rundreise‑Konvertierung mehrsprachiger Dokumente nützlich sein. Standardmäßig ist sie deaktiviert (
false
).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

