---
title: "XmlHighlightOptions"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Innehåller alternativ som möjliggör anpassning av XML‑markering under XML‑till‑HTML‑konvertering"
type: docs
weight: 53
url: /sv/nodejs-java/com.groupdocs.editor.options/xmlhighlightoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class XmlHighlightOptions implements IEditOptions
```

Innehåller alternativ som tillåter att anpassa XML-markering under XML-till-HTML-konvertering.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getXmlTagsFontSettings()](#getXmlTagsFontSettings--) | Ansvarig för att representera teckensnittet för XML-taggar (vinkelparenteser med taggnamn) |
|
|  | [getAttributeNamesFontSettings()](#getAttributeNamesFontSettings--) | Ansvarig för att representera teckensnittet för attributnamn |
|
|  | [getAttributeValuesFontSettings()](#getAttributeValuesFontSettings--) | Ansvarig för att representera teckensnittet för attributvärden |
|
|  | [getInnerTextFontSettings()](#getInnerTextFontSettings--) | Ansvarig för att representera teckensnittet för text inom taggar |
|
|  | [getHtmlCommentsFontSettings()](#getHtmlCommentsFontSettings--) | Ansvarig för att representera teckensnittet för HTML-kommentarer (inklusive par av öppnings- och stängningstaggar) |
|
|  | [getCDataFontSettings()](#getCDataFontSettings--) | Ansvarig för att representera teckensnittet för CDATA-sektioner (inklusive par av öppnings- och stängningstaggar) |
|
|  | [isDefault()](#isDefault--) | Bestämmer om detta XML Highlight-alternativobjekt har standardinställningar för teckensnitt |
|
|  | [resetToDefault()](#resetToDefault--) | Återställer de aktuella teckensnittinställningarna till deras standardvärden |
|
### getXmlTagsFontSettings() {#getXmlTagsFontSettings--}
```
public final WebFont getXmlTagsFontSettings()
```


Ansvarig för att representera teckensnittet för XML-taggar (vinkelparenteser med taggnamn)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeNamesFontSettings() {#getAttributeNamesFontSettings--}
```
public final WebFont getAttributeNamesFontSettings()
```


Ansvarig för att representera teckensnittet för attributnamn


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeValuesFontSettings() {#getAttributeValuesFontSettings--}
```
public final WebFont getAttributeValuesFontSettings()
```


Ansvarig för att representera teckensnittet för attributvärden


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getInnerTextFontSettings() {#getInnerTextFontSettings--}
```
public final WebFont getInnerTextFontSettings()
```


Ansvarig för att representera teckensnittet för text inom taggar


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getHtmlCommentsFontSettings() {#getHtmlCommentsFontSettings--}
```
public final WebFont getHtmlCommentsFontSettings()
```


Ansvarig för att representera teckensnittet för HTML-kommentarer (inklusive par av öppnings- och stängningstaggar)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getCDataFontSettings() {#getCDataFontSettings--}
```
public final WebFont getCDataFontSettings()
```


Ansvarig för att representera teckensnittet för CDATA-sektioner (inklusive par av öppnings- och stängningstaggar)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Bestämmer om detta XML Highlight-alternativobjekt har standardinställningar för teckensnitt


**Returns:**
boolean
### resetToDefault() {#resetToDefault--}
```
public final void resetToDefault()
```


Återställer de aktuella teckensnittinställningarna till deras standardvärden


