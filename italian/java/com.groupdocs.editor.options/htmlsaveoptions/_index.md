---
title: "HtmlSaveOptions"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Consente di specificare opzioni personalizzate per salvare l'istanza al formato HTML"
type: docs
weight: 19
url: /it/java/com.groupdocs.editor.options/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object
```
public final class HtmlSaveOptions
```

Consente di specificare opzioni personalizzate per salvare l'istanza [EditableDocument](../../com.groupdocs.editor/editabledocument) al formato HTML

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [HtmlSaveOptions()](#HtmlSaveOptions--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getHtmlTagCase()](#getHtmlTagCase--) | Controlla come i nomi dei tag HTML saranno presenti nel markup HTML: tutti minuscoli (valore predefinito), tutti maiuscoli o la prima lettera maiuscola |
|
|  | [setHtmlTagCase(int value)](#setHtmlTagCase-int-) | Controlla come i nomi dei tag HTML saranno presenti nel markup HTML: tutti minuscoli (valore predefinito), tutti maiuscoli o la prima lettera maiuscola |
|
|  | [getAttributeValueDelimiter()](#getAttributeValueDelimiter--) | Controlla quale delimitatore intorno ai valori degli attributi negli elementi HTML verrà utilizzato: apice singolo (valore predefinito) o virgolette doppie |
|
|  | [setAttributeValueDelimiter(int value)](#setAttributeValueDelimiter-int-) | Controlla quale delimitatore intorno ai valori degli attributi negli elementi HTML verrà utilizzato: apice singolo (valore predefinito) o virgolette doppie |
|
|  | [getEmbedStylesheetsIntoMarkup()](#getEmbedStylesheetsIntoMarkup--) | Controlla dove memorizzare i fogli di stile CSS: come risorse esterne ( |
false
), o incorporarle nel markup HTML, all'interno dell'elemento STYLE nella sezione HTML-\>HEAD (
true
)
|
|  | [setEmbedStylesheetsIntoMarkup(boolean value)](#setEmbedStylesheetsIntoMarkup-boolean-) | Controlla dove memorizzare i fogli di stile CSS: come risorse esterne ( |
false
), o incorporarle nel markup HTML, all'interno dell'elemento STYLE nella sezione HTML-\>HEAD (
true
)
|
|  | [getSavingCallback()](#getSavingCallback--) | Interfaccia, che deve essere implementata dall'utente finale per salvare tutte le risorse HTML esterne |
|
|  | [setSavingCallback(IHtmlSavingCallback value)](#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-) | Interfaccia, che deve essere implementata dall'utente finale per salvare tutte le risorse HTML esterne |
|
### HtmlSaveOptions() {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```


### getHtmlTagCase() {#getHtmlTagCase--}
```
public final int getHtmlTagCase()
```


Controlla come i nomi dei tag HTML saranno presenti nel markup HTML: tutti minuscoli (valore predefinito), tutti maiuscoli o la prima lettera maiuscola


**Returns:**
int
### setHtmlTagCase(int value) {#setHtmlTagCase-int-}
```
public final void setHtmlTagCase(int value)
```


Controlla come i nomi dei tag HTML saranno presenti nel markup HTML: tutti minuscoli (valore predefinito), tutti maiuscoli o la prima lettera maiuscola


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getAttributeValueDelimiter() {#getAttributeValueDelimiter--}
```
public final int getAttributeValueDelimiter()
```


Controlla quale delimitatore intorno ai valori degli attributi negli elementi HTML verrà utilizzato: apice singolo (valore predefinito) o virgolette doppie


**Returns:**
int
### setAttributeValueDelimiter(int value) {#setAttributeValueDelimiter-int-}
```
public final void setAttributeValueDelimiter(int value)
```


Controlla quale delimitatore intorno ai valori degli attributi negli elementi HTML verrà utilizzato: apice singolo (valore predefinito) o virgolette doppie


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getEmbedStylesheetsIntoMarkup() {#getEmbedStylesheetsIntoMarkup--}
```
public final boolean getEmbedStylesheetsIntoMarkup()
```


Controlla dove memorizzare i fogli di stile CSS: come risorse esterne (
false
), o incorporarle nel markup HTML, all'interno dell'elemento STYLE nella sezione HTML-\>HEAD (
true
)


**Returns:**
boolean
### setEmbedStylesheetsIntoMarkup(boolean value) {#setEmbedStylesheetsIntoMarkup-boolean-}
```
public final void setEmbedStylesheetsIntoMarkup(boolean value)
```


Controlla dove memorizzare i fogli di stile CSS: come risorse esterne (
false
), o incorporarle nel markup HTML, all'interno dell'elemento STYLE nella sezione HTML-\>HEAD (
true
)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getSavingCallback() {#getSavingCallback--}
```
public final IHtmlSavingCallback getSavingCallback()
```


Interfaccia, che deve essere implementata dall'utente finale per salvare tutte le risorse HTML esterne


**Returns:**
[IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback)
### setSavingCallback(IHtmlSavingCallback value) {#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-}
```
public final void setSavingCallback(IHtmlSavingCallback value)
```


Interfaccia, che deve essere implementata dall'utente finale per salvare tutte le risorse HTML esterne


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback) |  |

