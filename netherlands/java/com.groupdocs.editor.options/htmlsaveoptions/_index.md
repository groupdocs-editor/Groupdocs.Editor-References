---
title: "HtmlSaveOptions"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Staat toe om aangepaste opties op te geven voor het opslaan van de  instantie naar het HTML-formaat"
type: docs
weight: 19
url: /nl/java/com.groupdocs.editor.options/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object
```
public final class HtmlSaveOptions
```

Staat toe om aangepaste opties op te geven voor het opslaan van de [EditableDocument](../../com.groupdocs.editor/editabledocument) instantie naar het HTML-formaat

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [HtmlSaveOptions()](#HtmlSaveOptions--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getHtmlTagCase()](#getHtmlTagCase--) | Bepaalt hoe de HTML-tag namen worden weergegeven in HTML-markup: allemaal kleine letters (standaardwaarde), allemaal hoofdletters, of eerste letter hoofdletter |
|
|  | [setHtmlTagCase(int value)](#setHtmlTagCase-int-) | Bepaalt hoe de HTML-tag namen worden weergegeven in HTML-markup: allemaal kleine letters (standaardwaarde), allemaal hoofdletters, of eerste letter hoofdletter |
|
|  | [getAttributeValueDelimiter()](#getAttributeValueDelimiter--) | Bepaalt welk scheidingsteken rond de attribuutwaarden in HTML-elementen wordt gebruikt: enkele aanhalingsteken (standaardwaarde) of dubbele aanhalingsteken |
|
|  | [setAttributeValueDelimiter(int value)](#setAttributeValueDelimiter-int-) | Bepaalt welk scheidingsteken rond de attribuutwaarden in HTML-elementen wordt gebruikt: enkele aanhalingsteken (standaardwaarde) of dubbele aanhalingsteken |
|
|  | [getEmbedStylesheetsIntoMarkup()](#getEmbedStylesheetsIntoMarkup--) | Bepaalt waar de CSS-stylesheet(s) worden opgeslagen: als externe bronnen ( |
false
) of embed ze in de HTML-markup, binnen het STYLE-element in de HTML-\>HEAD sectie (
true
)
|
|  | [setEmbedStylesheetsIntoMarkup(boolean value)](#setEmbedStylesheetsIntoMarkup-boolean-) | Bepaalt waar de CSS-stylesheet(s) worden opgeslagen: als externe bronnen ( |
false
) of embed ze in de HTML-markup, binnen het STYLE-element in de HTML-\>HEAD sectie (
true
)
|
|  | [getSavingCallback()](#getSavingCallback--) | Interface, die moet worden geïmplementeerd door de eindgebruiker voor het opslaan van alle externe HTML-resources |
|
|  | [setSavingCallback(IHtmlSavingCallback value)](#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-) | Interface, die moet worden geïmplementeerd door de eindgebruiker voor het opslaan van alle externe HTML-resources |
|
### HtmlSaveOptions() {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```


### getHtmlTagCase() {#getHtmlTagCase--}
```
public final int getHtmlTagCase()
```


Bepaalt hoe de HTML-tag namen worden weergegeven in HTML-markup: allemaal kleine letters (standaardwaarde), allemaal hoofdletters, of eerste letter hoofdletter


**Returns:**
int
### setHtmlTagCase(int value) {#setHtmlTagCase-int-}
```
public final void setHtmlTagCase(int value)
```


Bepaalt hoe de HTML-tag namen worden weergegeven in HTML-markup: allemaal kleine letters (standaardwaarde), allemaal hoofdletters, of eerste letter hoofdletter


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getAttributeValueDelimiter() {#getAttributeValueDelimiter--}
```
public final int getAttributeValueDelimiter()
```


Bepaalt welk scheidingsteken rond de attribuutwaarden in HTML-elementen wordt gebruikt: enkele aanhalingsteken (standaardwaarde) of dubbele aanhalingsteken


**Returns:**
int
### setAttributeValueDelimiter(int value) {#setAttributeValueDelimiter-int-}
```
public final void setAttributeValueDelimiter(int value)
```


Bepaalt welk scheidingsteken rond de attribuutwaarden in HTML-elementen wordt gebruikt: enkele aanhalingsteken (standaardwaarde) of dubbele aanhalingsteken


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getEmbedStylesheetsIntoMarkup() {#getEmbedStylesheetsIntoMarkup--}
```
public final boolean getEmbedStylesheetsIntoMarkup()
```


Bepaalt waar de CSS-stylesheet(s) worden opgeslagen: als externe bronnen (
false
) of embed ze in de HTML-markup, binnen het STYLE-element in de HTML-\>HEAD sectie (
true
)


**Returns:**
boolean
### setEmbedStylesheetsIntoMarkup(boolean value) {#setEmbedStylesheetsIntoMarkup-boolean-}
```
public final void setEmbedStylesheetsIntoMarkup(boolean value)
```


Bepaalt waar de CSS-stylesheet(s) worden opgeslagen: als externe bronnen (
false
) of embed ze in de HTML-markup, binnen het STYLE-element in de HTML-\>HEAD sectie (
true
)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getSavingCallback() {#getSavingCallback--}
```
public final IHtmlSavingCallback getSavingCallback()
```


Interface, die moet worden geïmplementeerd door de eindgebruiker voor het opslaan van alle externe HTML-resources


**Returns:**
[IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback)
### setSavingCallback(IHtmlSavingCallback value) {#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-}
```
public final void setSavingCallback(IHtmlSavingCallback value)
```


Interface, die moet worden geïmplementeerd door de eindgebruiker voor het opslaan van alle externe HTML-resources


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback) |  |

