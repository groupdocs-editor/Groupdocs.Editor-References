---
title: "HtmlSaveOptions"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Tillåter att ange anpassade alternativ för att spara  instansen till HTML-formatet"
type: docs
weight: 19
url: /sv/java/com.groupdocs.editor.options/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object
```
public final class HtmlSaveOptions
```

Tillåter att ange anpassade alternativ för att spara [EditableDocument](../../com.groupdocs.editor/editabledocument) instansen till HTML-formatet

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [HtmlSaveOptions()](#HtmlSaveOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getHtmlTagCase()](#getHtmlTagCase--) | Styr hur HTML-taggnamnen kommer att visas i HTML-markup: Alla gemener (standardvärde), Alla versaler eller Första bokstaven versal |
|
|  | [setHtmlTagCase(int value)](#setHtmlTagCase-int-) | Styr hur HTML-taggnamnen kommer att visas i HTML-markup: Alla gemener (standardvärde), Alla versaler eller Första bokstaven versal |
|
|  | [getAttributeValueDelimiter()](#getAttributeValueDelimiter--) | Styr vilket avgränsningstecken runt attributvärden i HTML-element som kommer att användas: enkelfnutt (standardvärde) eller dubbelfnutt |
|
|  | [setAttributeValueDelimiter(int value)](#setAttributeValueDelimiter-int-) | Styr vilket avgränsningstecken runt attributvärden i HTML-element som kommer att användas: enkelfnutt (standardvärde) eller dubbelfnutt |
|
|  | [getEmbedStylesheetsIntoMarkup()](#getEmbedStylesheetsIntoMarkup--) | Styr var CSS-stilmallen/-arna ska lagras: som externa resurser ( |
false
), eller bädda in dem i HTML-markupen, inuti STYLE-elementet i HTML-\>HEAD-sektionen (
true
)
|
|  | [setEmbedStylesheetsIntoMarkup(boolean value)](#setEmbedStylesheetsIntoMarkup-boolean-) | Styr var CSS-stilmallen/-arna ska lagras: som externa resurser ( |
false
), eller bädda in dem i HTML-markupen, inuti STYLE-elementet i HTML-\>HEAD-sektionen (
true
)
|
|  | [getSavingCallback()](#getSavingCallback--) | Gränssnitt, som måste implementeras av slutanvändaren för att spara alla externa HTML-resurser |
|
|  | [setSavingCallback(IHtmlSavingCallback value)](#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-) | Gränssnitt, som måste implementeras av slutanvändaren för att spara alla externa HTML-resurser |
|
### HtmlSaveOptions() {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```


### getHtmlTagCase() {#getHtmlTagCase--}
```
public final int getHtmlTagCase()
```


Styr hur HTML-taggnamnen kommer att visas i HTML-markup: Alla gemener (standardvärde), Alla versaler eller Första bokstaven versal


**Returns:**
int
### setHtmlTagCase(int value) {#setHtmlTagCase-int-}
```
public final void setHtmlTagCase(int value)
```


Styr hur HTML-taggnamnen kommer att visas i HTML-markup: Alla gemener (standardvärde), Alla versaler eller Första bokstaven versal


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getAttributeValueDelimiter() {#getAttributeValueDelimiter--}
```
public final int getAttributeValueDelimiter()
```


Styr vilket avgränsningstecken runt attributvärden i HTML-element som kommer att användas: enkelfnutt (standardvärde) eller dubbelfnutt


**Returns:**
int
### setAttributeValueDelimiter(int value) {#setAttributeValueDelimiter-int-}
```
public final void setAttributeValueDelimiter(int value)
```


Styr vilket avgränsningstecken runt attributvärden i HTML-element som kommer att användas: enkelfnutt (standardvärde) eller dubbelfnutt


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getEmbedStylesheetsIntoMarkup() {#getEmbedStylesheetsIntoMarkup--}
```
public final boolean getEmbedStylesheetsIntoMarkup()
```


Styr var CSS-stilmallen/-arna ska lagras: som externa resurser (
false
), eller bädda in dem i HTML-markupen, inuti STYLE-elementet i HTML-\>HEAD-sektionen (
true
)


**Returns:**
boolean
### setEmbedStylesheetsIntoMarkup(boolean value) {#setEmbedStylesheetsIntoMarkup-boolean-}
```
public final void setEmbedStylesheetsIntoMarkup(boolean value)
```


Styr var CSS-stilmallen/-arna ska lagras: som externa resurser (
false
), eller bädda in dem i HTML-markupen, inuti STYLE-elementet i HTML-\>HEAD-sektionen (
true
)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getSavingCallback() {#getSavingCallback--}
```
public final IHtmlSavingCallback getSavingCallback()
```


Gränssnitt, som måste implementeras av slutanvändaren för att spara alla externa HTML-resurser


**Returns:**
[IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback)
### setSavingCallback(IHtmlSavingCallback value) {#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-}
```
public final void setSavingCallback(IHtmlSavingCallback value)
```


Gränssnitt, som måste implementeras av slutanvändaren för att spara alla externa HTML-resurser


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback) |  |

