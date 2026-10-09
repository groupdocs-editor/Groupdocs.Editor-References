---
title: "XmlHighlightOptions"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Contiene opciones que permiten personalizar el resaltado XML durante la conversión de XML a HTML"
type: docs
weight: 53
url: /es/nodejs-java/com.groupdocs.editor.options/xmlhighlightoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class XmlHighlightOptions implements IEditOptions
```

Contiene opciones que permiten personalizar el resaltado XML durante la conversión de XML a HTML.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getXmlTagsFontSettings()](#getXmlTagsFontSettings--) | Responsable de representar la fuente de las etiquetas XML (corchetes angulares con nombres de etiqueta) |
|
|  | [getAttributeNamesFontSettings()](#getAttributeNamesFontSettings--) | Responsable de representar la fuente de los nombres de atributos |
|
|  | [getAttributeValuesFontSettings()](#getAttributeValuesFontSettings--) | Responsable de representar la fuente de los valores de atributos |
|
|  | [getInnerTextFontSettings()](#getInnerTextFontSettings--) | Responsable de representar la fuente del texto interno de la etiqueta |
|
|  | [getHtmlCommentsFontSettings()](#getHtmlCommentsFontSettings--) | Responsable de representar la fuente de los comentarios HTML (incluyendo el par de etiquetas de apertura y cierre) |
|
|  | [getCDataFontSettings()](#getCDataFontSettings--) | Responsable de representar la fuente de las secciones CDATA (incluyendo el par de etiquetas de apertura y cierre) |
|
|  | [isDefault()](#isDefault--) | Determina si este objeto de opciones de resaltado XML tiene una configuración de fuente predeterminada |
|
|  | [resetToDefault()](#resetToDefault--) | Restablece la configuración de fuente actual a sus valores predeterminados |
|
### getXmlTagsFontSettings() {#getXmlTagsFontSettings--}
```
public final WebFont getXmlTagsFontSettings()
```


Responsable de representar la fuente de las etiquetas XML (corchetes angulares con nombres de etiqueta)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeNamesFontSettings() {#getAttributeNamesFontSettings--}
```
public final WebFont getAttributeNamesFontSettings()
```


Responsable de representar la fuente de los nombres de atributos


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeValuesFontSettings() {#getAttributeValuesFontSettings--}
```
public final WebFont getAttributeValuesFontSettings()
```


Responsable de representar la fuente de los valores de atributos


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getInnerTextFontSettings() {#getInnerTextFontSettings--}
```
public final WebFont getInnerTextFontSettings()
```


Responsable de representar la fuente del texto interno de la etiqueta


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getHtmlCommentsFontSettings() {#getHtmlCommentsFontSettings--}
```
public final WebFont getHtmlCommentsFontSettings()
```


Responsable de representar la fuente de los comentarios HTML (incluyendo el par de etiquetas de apertura y cierre)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getCDataFontSettings() {#getCDataFontSettings--}
```
public final WebFont getCDataFontSettings()
```


Responsable de representar la fuente de las secciones CDATA (incluyendo el par de etiquetas de apertura y cierre)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Determina si este objeto de opciones de resaltado XML tiene una configuración de fuente predeterminada


**Returns:**
booleano
### resetToDefault() {#resetToDefault--}
```
public final void resetToDefault()
```


Restablece la configuración de fuente actual a sus valores predeterminados


