---
title: "XmlHighlightOptions"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Enthält Optionen, die die Anpassung der XML‑Hervorhebung während der XML-zu-HTML-Konvertierung ermöglichen"
type: docs
weight: 53
url: /de/java/com.groupdocs.editor.options/xmlhighlightoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class XmlHighlightOptions implements IEditOptions
```

Enthält Optionen, die es ermöglichen, die XML‑Hervorhebung während der XML‑zu‑HTML‑Konvertierung anzupassen.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getXmlTagsFontSettings()](#getXmlTagsFontSettings--) | Verantwortlich für die Darstellung der Schriftart von XML‑Tags (spitze Klammern mit Tag‑Namen) |
|
|  | [getAttributeNamesFontSettings()](#getAttributeNamesFontSettings--) | Verantwortlich für die Darstellung der Schriftart von Attributnamen |
|
|  | [getAttributeValuesFontSettings()](#getAttributeValuesFontSettings--) | Verantwortlich für die Darstellung der Schriftart von Attributwerten |
|
|  | [getInnerTextFontSettings()](#getInnerTextFontSettings--) | Verantwortlich für die Darstellung der Schriftart von Text innerhalb von Tags |
|
|  | [getHtmlCommentsFontSettings()](#getHtmlCommentsFontSettings--) | Verantwortlich für die Darstellung der Schriftart von HTML-Kommentaren (einschließlich des Paars von öffnenden und schließenden Tags) |
|
|  | [getCDataFontSettings()](#getCDataFontSettings--) | Verantwortlich für die Darstellung der Schriftart von CDATA-Abschnitten (einschließlich des Paars von öffnenden und schließenden Tags) |
|
|  | [isDefault()](#isDefault--) | Bestimmt, ob dieses XML Highlight Optionen-Objekt über standardmäßige Schriftarteinstellungen verfügt |
|
|  | [resetToDefault()](#resetToDefault--) | Setzt die aktuellen Schriftarteinstellungen auf ihre Standardwerte zurück |
|
### getXmlTagsFontSettings() {#getXmlTagsFontSettings--}
```
public final WebFont getXmlTagsFontSettings()
```


Verantwortlich für die Darstellung der Schriftart von XML‑Tags (spitze Klammern mit Tag‑Namen)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeNamesFontSettings() {#getAttributeNamesFontSettings--}
```
public final WebFont getAttributeNamesFontSettings()
```


Verantwortlich für die Darstellung der Schriftart von Attributnamen


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeValuesFontSettings() {#getAttributeValuesFontSettings--}
```
public final WebFont getAttributeValuesFontSettings()
```


Verantwortlich für die Darstellung der Schriftart von Attributwerten


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getInnerTextFontSettings() {#getInnerTextFontSettings--}
```
public final WebFont getInnerTextFontSettings()
```


Verantwortlich für die Darstellung der Schriftart von Text innerhalb von Tags


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getHtmlCommentsFontSettings() {#getHtmlCommentsFontSettings--}
```
public final WebFont getHtmlCommentsFontSettings()
```


Verantwortlich für die Darstellung der Schriftart von HTML-Kommentaren (einschließlich des Paars von öffnenden und schließenden Tags)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getCDataFontSettings() {#getCDataFontSettings--}
```
public final WebFont getCDataFontSettings()
```


Verantwortlich für die Darstellung der Schriftart von CDATA-Abschnitten (einschließlich des Paars von öffnenden und schließenden Tags)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Bestimmt, ob dieses XML Highlight Optionen-Objekt über standardmäßige Schriftarteinstellungen verfügt


**Returns:**
boolean
### resetToDefault() {#resetToDefault--}
```
public final void resetToDefault()
```


Setzt die aktuellen Schriftarteinstellungen auf ihre Standardwerte zurück


