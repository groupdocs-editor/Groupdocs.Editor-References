---
title: "XmlHighlightOptions"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Contient des options qui permettent de personnaliser la mise en évidence XML lors de la conversion XML-vers-HTML"
type: docs
weight: 53
url: /fr/java/com.groupdocs.editor.options/xmlhighlightoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class XmlHighlightOptions implements IEditOptions
```

Contient des options qui permettent de personnaliser la mise en évidence XML lors de la conversion XML-vers-HTML.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getXmlTagsFontSettings()](#getXmlTagsFontSettings--) | Responsable de la représentation de la police des balises XML (chevrons avec les noms de balises) |
|
|  | [getAttributeNamesFontSettings()](#getAttributeNamesFontSettings--) | Responsable de la représentation de la police des noms d'attributs |
|
|  | [getAttributeValuesFontSettings()](#getAttributeValuesFontSettings--) | Responsable de la représentation de la police des valeurs d'attributs |
|
|  | [getInnerTextFontSettings()](#getInnerTextFontSettings--) | Responsable de la représentation de la police du texte des balises internes |
|
|  | [getHtmlCommentsFontSettings()](#getHtmlCommentsFontSettings--) | Responsable de la représentation de la police des commentaires HTML (y compris la paire de balises d'ouverture et de fermeture) |
|
|  | [getCDataFontSettings()](#getCDataFontSettings--) | Responsable de la représentation de la police des sections CDATA (y compris la paire de balises d'ouverture et de fermeture) |
|
|  | [isDefault()](#isDefault--) | Détermine si cet objet d'options de mise en évidence XML possède des paramètres de police par défaut |
|
|  | [resetToDefault()](#resetToDefault--) | Réinitialise les paramètres de police actuels à leurs valeurs par défaut |
|
### getXmlTagsFontSettings() {#getXmlTagsFontSettings--}
```
public final WebFont getXmlTagsFontSettings()
```


Responsable de la représentation de la police des balises XML (chevrons avec les noms de balises)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeNamesFontSettings() {#getAttributeNamesFontSettings--}
```
public final WebFont getAttributeNamesFontSettings()
```


Responsable de la représentation de la police des noms d'attributs


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeValuesFontSettings() {#getAttributeValuesFontSettings--}
```
public final WebFont getAttributeValuesFontSettings()
```


Responsable de la représentation de la police des valeurs d'attributs


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getInnerTextFontSettings() {#getInnerTextFontSettings--}
```
public final WebFont getInnerTextFontSettings()
```


Responsable de la représentation de la police du texte des balises internes


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getHtmlCommentsFontSettings() {#getHtmlCommentsFontSettings--}
```
public final WebFont getHtmlCommentsFontSettings()
```


Responsable de la représentation de la police des commentaires HTML (y compris la paire de balises d'ouverture et de fermeture)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getCDataFontSettings() {#getCDataFontSettings--}
```
public final WebFont getCDataFontSettings()
```


Responsable de la représentation de la police des sections CDATA (y compris la paire de balises d'ouverture et de fermeture)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Détermine si cet objet d'options de mise en évidence XML possède des paramètres de police par défaut


**Returns:**
boolean
### resetToDefault() {#resetToDefault--}
```
public final void resetToDefault()
```


Réinitialise les paramètres de police actuels à leurs valeurs par défaut


