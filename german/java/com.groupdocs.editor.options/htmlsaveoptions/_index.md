---
title: "HtmlSaveOptions"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Ermöglicht das Angeben benutzerdefinierter Optionen zum Speichern der Instanz im HTML‑Format"
type: docs
weight: 19
url: /de/java/com.groupdocs.editor.options/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object
```
public final class HtmlSaveOptions
```

Ermöglicht das Angeben benutzerdefinierter Optionen zum Speichern der [EditableDocument](../../com.groupdocs.editor/editabledocument)-Instanz im HTML‑Format

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [HtmlSaveOptions()](#HtmlSaveOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getHtmlTagCase()](#getHtmlTagCase--) | Steuert, wie die HTML‑Tag‑Namen im HTML‑Markup dargestellt werden: alles klein (Standardwert), alles groß oder erster Buchstabe groß |
|
|  | [setHtmlTagCase(int value)](#setHtmlTagCase-int-) | Steuert, wie die HTML‑Tag‑Namen im HTML‑Markup dargestellt werden: alles klein (Standardwert), alles groß oder erster Buchstabe groß |
|
|  | [getAttributeValueDelimiter()](#getAttributeValueDelimiter--) | Steuert, welches Trennzeichen um Attributwerte in HTML‑Elementen verwendet wird: einfache Anführungszeichen (Standardwert) oder doppelte Anführungszeichen |
|
|  | [setAttributeValueDelimiter(int value)](#setAttributeValueDelimiter-int-) | Steuert, welches Trennzeichen um Attributwerte in HTML‑Elementen verwendet wird: einfache Anführungszeichen (Standardwert) oder doppelte Anführungszeichen |
|
|  | [getEmbedStylesheetsIntoMarkup()](#getEmbedStylesheetsIntoMarkup--) | Steuert, wo die CSS‑Stylesheet(s) gespeichert werden: als externe Ressourcen ( |
false
), oder bettet sie in das HTML‑Markup ein, innerhalb des STYLE‑Elements im HTML-\\>HEAD‑Abschnitt (
true
)
|
|  | [setEmbedStylesheetsIntoMarkup(boolean value)](#setEmbedStylesheetsIntoMarkup-boolean-) | Steuert, wo die CSS‑Stylesheet(s) gespeichert werden: als externe Ressourcen ( |
false
), oder bettet sie in das HTML‑Markup ein, innerhalb des STYLE‑Elements im HTML-\\>HEAD‑Abschnitt (
true
)
|
|  | [getSavingCallback()](#getSavingCallback--) | Schnittstelle, die vom Endbenutzer implementiert werden muss, um alle externen HTML‑Ressourcen zu speichern |
|
|  | [setSavingCallback(IHtmlSavingCallback value)](#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-) | Schnittstelle, die vom Endbenutzer implementiert werden muss, um alle externen HTML‑Ressourcen zu speichern |
|
### HtmlSaveOptions() {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```


### getHtmlTagCase() {#getHtmlTagCase--}
```
public final int getHtmlTagCase()
```


Steuert, wie die HTML‑Tag‑Namen im HTML‑Markup dargestellt werden: alles klein (Standardwert), alles groß oder erster Buchstabe groß


**Returns:**
int
### setHtmlTagCase(int value) {#setHtmlTagCase-int-}
```
public final void setHtmlTagCase(int value)
```


Steuert, wie die HTML‑Tag‑Namen im HTML‑Markup dargestellt werden: alles klein (Standardwert), alles groß oder erster Buchstabe groß


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getAttributeValueDelimiter() {#getAttributeValueDelimiter--}
```
public final int getAttributeValueDelimiter()
```


Steuert, welches Trennzeichen um Attributwerte in HTML‑Elementen verwendet wird: einfache Anführungszeichen (Standardwert) oder doppelte Anführungszeichen


**Returns:**
int
### setAttributeValueDelimiter(int value) {#setAttributeValueDelimiter-int-}
```
public final void setAttributeValueDelimiter(int value)
```


Steuert, welches Trennzeichen um Attributwerte in HTML‑Elementen verwendet wird: einfache Anführungszeichen (Standardwert) oder doppelte Anführungszeichen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getEmbedStylesheetsIntoMarkup() {#getEmbedStylesheetsIntoMarkup--}
```
public final boolean getEmbedStylesheetsIntoMarkup()
```


Steuert, wo die CSS‑Stylesheet(s) gespeichert werden: als externe Ressourcen (
false
), oder bettet sie in das HTML‑Markup ein, innerhalb des STYLE‑Elements im HTML-\\>HEAD‑Abschnitt (
true
)


**Returns:**
boolean
### setEmbedStylesheetsIntoMarkup(boolean value) {#setEmbedStylesheetsIntoMarkup-boolean-}
```
public final void setEmbedStylesheetsIntoMarkup(boolean value)
```


Steuert, wo die CSS‑Stylesheet(s) gespeichert werden: als externe Ressourcen (
false
), oder bettet sie in das HTML‑Markup ein, innerhalb des STYLE‑Elements im HTML-\\>HEAD‑Abschnitt (
true
)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getSavingCallback() {#getSavingCallback--}
```
public final IHtmlSavingCallback getSavingCallback()
```


Schnittstelle, die vom Endbenutzer implementiert werden muss, um alle externen HTML‑Ressourcen zu speichern


**Returns:**
[IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback)
### setSavingCallback(IHtmlSavingCallback value) {#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-}
```
public final void setSavingCallback(IHtmlSavingCallback value)
```


Schnittstelle, die vom Endbenutzer implementiert werden muss, um alle externen HTML‑Ressourcen zu speichern


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback) |  |

