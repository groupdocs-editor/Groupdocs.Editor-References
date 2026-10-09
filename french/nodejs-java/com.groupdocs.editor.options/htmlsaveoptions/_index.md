---
title: "HtmlSaveOptions"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Permet de spécifier des options personnalisées pour enregistrer l'instance au format HTML"
type: docs
weight: 19
url: /fr/nodejs-java/com.groupdocs.editor.options/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object
```
public final class HtmlSaveOptions
```

Permet de spécifier des options personnalisées pour enregistrer l'instance [EditableDocument](../../com.groupdocs.editor/editabledocument) au format HTML

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [HtmlSaveOptions()](#HtmlSaveOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getHtmlTagCase()](#getHtmlTagCase--) | Contrôle la façon dont les noms de balises HTML seront présentés dans le balisage HTML : tout en minuscules (valeur par défaut), tout en majuscules, ou première lettre en majuscule |
|
|  | [setHtmlTagCase(int value)](#setHtmlTagCase-int-) | Contrôle la façon dont les noms de balises HTML seront présentés dans le balisage HTML : tout en minuscules (valeur par défaut), tout en majuscules, ou première lettre en majuscule |
|
|  | [getAttributeValueDelimiter()](#getAttributeValueDelimiter--) | Contrôle le délimiteur autour des valeurs d'attributs dans les éléments HTML qui sera utilisé : apostrophe simple (valeur par défaut) ou guillemet double |
|
|  | [setAttributeValueDelimiter(int value)](#setAttributeValueDelimiter-int-) | Contrôle le délimiteur autour des valeurs d'attributs dans les éléments HTML qui sera utilisé : apostrophe simple (valeur par défaut) ou guillemet double |
|
|  | [getEmbedStylesheetsIntoMarkup()](#getEmbedStylesheetsIntoMarkup--) | Contrôle où stocker les feuilles de style CSS : en tant que ressources externes ( |
false
) ou les intégrer dans le balisage HTML, à l'intérieur de l'élément STYLE dans la section HTML-\>HEAD (
true
)
|
|  | [setEmbedStylesheetsIntoMarkup(boolean value)](#setEmbedStylesheetsIntoMarkup-boolean-) | Contrôle où stocker les feuilles de style CSS : en tant que ressources externes ( |
false
) ou les intégrer dans le balisage HTML, à l'intérieur de l'élément STYLE dans la section HTML-\>HEAD (
true
)
|
|  | [getSavingCallback()](#getSavingCallback--) | Interface qui doit être implémentée par l'utilisateur final pour enregistrer toutes les ressources HTML externes |
|
|  | [setSavingCallback(IHtmlSavingCallback value)](#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-) | Interface qui doit être implémentée par l'utilisateur final pour enregistrer toutes les ressources HTML externes |
|
### HtmlSaveOptions() {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```


### getHtmlTagCase() {#getHtmlTagCase--}
```
public final int getHtmlTagCase()
```


Contrôle la façon dont les noms de balises HTML seront présentés dans le balisage HTML : tout en minuscules (valeur par défaut), tout en majuscules, ou première lettre en majuscule


**Returns:**
int
### setHtmlTagCase(int value) {#setHtmlTagCase-int-}
```
public final void setHtmlTagCase(int value)
```


Contrôle la façon dont les noms de balises HTML seront présentés dans le balisage HTML : tout en minuscules (valeur par défaut), tout en majuscules, ou première lettre en majuscule


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getAttributeValueDelimiter() {#getAttributeValueDelimiter--}
```
public final int getAttributeValueDelimiter()
```


Contrôle le délimiteur autour des valeurs d'attributs dans les éléments HTML qui sera utilisé : apostrophe simple (valeur par défaut) ou guillemet double


**Returns:**
int
### setAttributeValueDelimiter(int value) {#setAttributeValueDelimiter-int-}
```
public final void setAttributeValueDelimiter(int value)
```


Contrôle le délimiteur autour des valeurs d'attributs dans les éléments HTML qui sera utilisé : apostrophe simple (valeur par défaut) ou guillemet double


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getEmbedStylesheetsIntoMarkup() {#getEmbedStylesheetsIntoMarkup--}
```
public final boolean getEmbedStylesheetsIntoMarkup()
```


Contrôle où stocker les feuilles de style CSS : en tant que ressources externes (
false
) ou les intégrer dans le balisage HTML, à l'intérieur de l'élément STYLE dans la section HTML-\>HEAD (
true
)


**Returns:**
booléen
### setEmbedStylesheetsIntoMarkup(boolean value) {#setEmbedStylesheetsIntoMarkup-boolean-}
```
public final void setEmbedStylesheetsIntoMarkup(boolean value)
```


Contrôle où stocker les feuilles de style CSS : en tant que ressources externes (
false
) ou les intégrer dans le balisage HTML, à l'intérieur de l'élément STYLE dans la section HTML-\>HEAD (
true
)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getSavingCallback() {#getSavingCallback--}
```
public final IHtmlSavingCallback getSavingCallback()
```


Interface qui doit être implémentée par l'utilisateur final pour enregistrer toutes les ressources HTML externes


**Returns:**
[IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback)
### setSavingCallback(IHtmlSavingCallback value) {#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-}
```
public final void setSavingCallback(IHtmlSavingCallback value)
```


Interface qui doit être implémentée par l'utilisateur final pour enregistrer toutes les ressources HTML externes


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback) |  |

