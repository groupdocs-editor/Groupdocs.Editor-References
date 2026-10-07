---
title: "XmlHighlightOptions"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Bevat opties die het mogelijk maken om de XML-markering aan te passen tijdens de XML-naar-HTML-conversie"
type: docs
weight: 53
url: /nl/java/com.groupdocs.editor.options/xmlhighlightoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class XmlHighlightOptions implements IEditOptions
```

Bevat opties die toelaten de XML-markering aan te passen tijdens de XML-naar-HTML-conversie

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getXmlTagsFontSettings()](#getXmlTagsFontSettings--) | Verantwoordelijk voor het weergeven van het lettertype van XML-tags (hoekige haakjes met tagnamen) |
|
|  | [getAttributeNamesFontSettings()](#getAttributeNamesFontSettings--) | Verantwoordelijk voor het weergeven van het lettertype van attribuutnamen |
|
|  | [getAttributeValuesFontSettings()](#getAttributeValuesFontSettings--) | Verantwoordelijk voor het weergeven van het lettertype van attribuutwaarden |
|
|  | [getInnerTextFontSettings()](#getInnerTextFontSettings--) | Verantwoordelijk voor het weergeven van het lettertype van inner-tag-tekst |
|
|  | [getHtmlCommentsFontSettings()](#getHtmlCommentsFontSettings--) | Verantwoordelijk voor het weergeven van het lettertype van HTML-commentaren (inclusief paar van openings- en sluitings-tags) |
|
|  | [getCDataFontSettings()](#getCDataFontSettings--) | Verantwoordelijk voor het weergeven van het lettertype van CDATA-secties (inclusief paar van openings- en sluitings-tags) |
|
|  | [isDefault()](#isDefault--) | Bepaalt of dit XML Highlight-optiesobject standaard lettertype-instellingen heeft |
|
|  | [resetToDefault()](#resetToDefault--) | Herstelt de huidige lettertype-instellingen naar hun standaardwaarden |
|
### getXmlTagsFontSettings() {#getXmlTagsFontSettings--}
```
public final WebFont getXmlTagsFontSettings()
```


Verantwoordelijk voor het weergeven van het lettertype van XML-tags (hoekige haakjes met tagnamen)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeNamesFontSettings() {#getAttributeNamesFontSettings--}
```
public final WebFont getAttributeNamesFontSettings()
```


Verantwoordelijk voor het weergeven van het lettertype van attribuutnamen


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeValuesFontSettings() {#getAttributeValuesFontSettings--}
```
public final WebFont getAttributeValuesFontSettings()
```


Verantwoordelijk voor het weergeven van het lettertype van attribuutwaarden


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getInnerTextFontSettings() {#getInnerTextFontSettings--}
```
public final WebFont getInnerTextFontSettings()
```


Verantwoordelijk voor het weergeven van het lettertype van inner-tag-tekst


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getHtmlCommentsFontSettings() {#getHtmlCommentsFontSettings--}
```
public final WebFont getHtmlCommentsFontSettings()
```


Verantwoordelijk voor het weergeven van het lettertype van HTML-commentaren (inclusief paar van openings- en sluitings-tags)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getCDataFontSettings() {#getCDataFontSettings--}
```
public final WebFont getCDataFontSettings()
```


Verantwoordelijk voor het weergeven van het lettertype van CDATA-secties (inclusief paar van openings- en sluitings-tags)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Bepaalt of dit XML Highlight-optiesobject standaard lettertype-instellingen heeft


**Returns:**
boolean
### resetToDefault() {#resetToDefault--}
```
public final void resetToDefault()
```


Herstelt de huidige lettertype-instellingen naar hun standaardwaarden


