---
title: "XmlHighlightOptions"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Contiene opzioni che consentono di personalizzare l'evidenziazione XML durante la conversione da XML a HTML"
type: docs
weight: 53
url: /it/nodejs-java/com.groupdocs.editor.options/xmlhighlightoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class XmlHighlightOptions implements IEditOptions
```

Contiene opzioni che consentono di personalizzare l'evidenziazione XML durante la conversione XML-to-HTML

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getXmlTagsFontSettings()](#getXmlTagsFontSettings--) | Responsabile della rappresentazione del carattere dei tag XML (parentesi angolari con i nomi dei tag) |
|
|  | [getAttributeNamesFontSettings()](#getAttributeNamesFontSettings--) | Responsabile della rappresentazione del carattere dei nomi degli attributi |
|
|  | [getAttributeValuesFontSettings()](#getAttributeValuesFontSettings--) | Responsabile della rappresentazione del carattere dei valori degli attributi |
|
|  | [getInnerTextFontSettings()](#getInnerTextFontSettings--) | Responsabile della rappresentazione del carattere del testo interno ai tag |
|
|  | [getHtmlCommentsFontSettings()](#getHtmlCommentsFontSettings--) | Responsabile della rappresentazione del carattere dei commenti HTML (inclusa la coppia di tag di apertura e chiusura) |
|
|  | [getCDataFontSettings()](#getCDataFontSettings--) | Responsabile della rappresentazione del carattere delle sezioni CDATA (inclusa la coppia di tag di apertura e chiusura) |
|
|  | [isDefault()](#isDefault--) | Determina se questo oggetto di opzioni di evidenziazione XML ha impostazioni di carattere predefinite |
|
|  | [resetToDefault()](#resetToDefault--) | Ripristina le impostazioni di carattere correnti ai loro valori predefiniti |
|
### getXmlTagsFontSettings() {#getXmlTagsFontSettings--}
```
public final WebFont getXmlTagsFontSettings()
```


Responsabile della rappresentazione del carattere dei tag XML (parentesi angolari con i nomi dei tag)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeNamesFontSettings() {#getAttributeNamesFontSettings--}
```
public final WebFont getAttributeNamesFontSettings()
```


Responsabile della rappresentazione del carattere dei nomi degli attributi


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeValuesFontSettings() {#getAttributeValuesFontSettings--}
```
public final WebFont getAttributeValuesFontSettings()
```


Responsabile della rappresentazione del carattere dei valori degli attributi


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getInnerTextFontSettings() {#getInnerTextFontSettings--}
```
public final WebFont getInnerTextFontSettings()
```


Responsabile della rappresentazione del carattere del testo interno ai tag


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getHtmlCommentsFontSettings() {#getHtmlCommentsFontSettings--}
```
public final WebFont getHtmlCommentsFontSettings()
```


Responsabile della rappresentazione del carattere dei commenti HTML (inclusa la coppia di tag di apertura e chiusura)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getCDataFontSettings() {#getCDataFontSettings--}
```
public final WebFont getCDataFontSettings()
```


Responsabile della rappresentazione del carattere delle sezioni CDATA (inclusa la coppia di tag di apertura e chiusura)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Determina se questo oggetto di opzioni di evidenziazione XML ha impostazioni di carattere predefinite


**Returns:**
boolean
### resetToDefault() {#resetToDefault--}
```
public final void resetToDefault()
```


Ripristina le impostazioni di carattere correnti ai loro valori predefiniti


