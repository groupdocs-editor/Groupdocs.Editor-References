---
title: "XmlHighlightOptions"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Innehåller alternativ som möjliggör anpassning av XML-markering under XML-till-HTML-konvertering"
type: docs
weight: 53
url: /sv/java/com.groupdocs.editor.options/xmlhighlightoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class XmlHighlightOptions implements IEditOptions
```

Innehåller alternativ som tillåter att anpassa XML-markering under XML-till-HTML-konvertering

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getXmlTagsFontSettings()](#getXmlTagsFontSettings--) | Ansvarig för att representera teckensnittet för XML-taggar (vinkelparenteser med taggnamn) |
|
|  | [getAttributeNamesFontSettings()](#getAttributeNamesFontSettings--) | Ansvarig för att representera teckensnittet för attributnamn |
|
|  | [getAttributeValuesFontSettings()](#getAttributeValuesFontSettings--) | Ansvarig för att representera teckensnittet för attributvärden |
|
|  | [getInnerTextFontSettings()](#getInnerTextFontSettings--) | Ansvarig för att representera teckensnittet för text innanför tagg |
|
|  | [getHtmlCommentsFontSettings()](#getHtmlCommentsFontSettings--) | Ansvarig för att representera teckensnittet för HTML-kommentarer (inklusive par av öppnings- och stängningstaggar) |
|
|  | [getCDataFontSettings()](#getCDataFontSettings--) | Ansvarig för att representera teckensnittet för CDATA-sektioner (inklusive par av öppnings- och stängningstaggar) |
|
|  | [isDefault()](#isDefault--) | Bestämmer om detta XML Highlight-alternativobjekt har standardteckensnittinställningar |
|
|  | [resetToDefault()](#resetToDefault--) | Återställer de aktuella teckensnittsinställningarna till deras standardvärden |
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


Ansvarig för att representera teckensnittet för text innanför tagg


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


Bestämmer om detta XML Highlight-alternativobjekt har standardteckensnittinställningar


**Returns:**
boolean
### resetToDefault() {#resetToDefault--}
```
public final void resetToDefault()
```


Återställer de aktuella teckensnittsinställningarna till deras standardvärden


