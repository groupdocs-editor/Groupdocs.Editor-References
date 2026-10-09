---
title: "XmlEditOptions"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Permet de spécifier des options personnalisées pour le chargement de documents XML eXtensible Markup Language et leur conversion en HTML"
type: docs
weight: 51
url: /fr/nodejs-java/com.groupdocs.editor.options/xmleditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlEditOptions implements IEditOptions
```

Permet de spécifier des options personnalisées pour le chargement du XML (eXtensible Markup Language)
documents et leur conversion en HTML

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [XmlEditOptions()](#XmlEditOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Encodage des caractères du document texte, qui sera appliqué à son |
ouverture.
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Encodage des caractères du document texte, qui sera appliqué à son |
ouverture.
|
|  | [getFixIncorrectStructure()](#getFixIncorrectStructure--) | Permet d'activer ou de désactiver le mécanisme de correction d'une structure XML corrompue. |
|
|  | [setFixIncorrectStructure(boolean value)](#setFixIncorrectStructure-boolean-) | Permet d'activer ou de désactiver le mécanisme de correction d'une structure XML corrompue. |
|
|  | [getRecognizeUris()](#getRecognizeUris--) | Permet d'activer l'algorithme de reconnaissance d'URI |
|
|  | [setRecognizeUris(boolean value)](#setRecognizeUris-boolean-) | Permet d'activer l'algorithme de reconnaissance d'URI |
|
|  | [getRecognizeEmails()](#getRecognizeEmails--) | Permet d'activer l'algorithme de reconnaissance des adresses e-mail dans les attributs |
valeurs
|
|  | [setRecognizeEmails(boolean value)](#setRecognizeEmails-boolean-) | Permet d'activer l'algorithme de reconnaissance des adresses e-mail dans les attributs |
valeurs
|
|  | [getTrimTrailingWhitespaces()](#getTrimTrailingWhitespaces--) | Permet d'activer la troncature des espaces de fin dans la balise interne |
texte.
|
|  | [setTrimTrailingWhitespaces(boolean value)](#setTrimTrailingWhitespaces-boolean-) | Permet d'activer la troncature des espaces de fin dans la balise interne |
texte.
|
|  | [getAttributeValuesQuoteType()](#getAttributeValuesQuoteType--) | Permet de spécifier le type de guillemets (simples ou doubles) pour les valeurs d'attribut. |
|
|  | [setAttributeValuesQuoteType(QuoteType value)](#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Permet de spécifier le type de guillemets (simples ou doubles) pour les valeurs d'attribut. |
|
|  | [getHighlightOptions()](#getHighlightOptions--) | Permet d'ajuster la mise en évidence du XML, qui sera appliquée à la structure XML lorsqu'elle est représentée en HTML. |
|
|  | [getFormatOptions()](#getFormatOptions--) | Permet d'ajuster le formatage du XML, qui sera appliqué à la structure XML lorsqu'elle est représentée en HTML. |
|
### XmlEditOptions() {#XmlEditOptions--}
```
public XmlEditOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Encodage des caractères du document texte, qui sera appliqué à son
ouverture. Par défaut, il est nul \\u2014 l'encodage interne du document sera appliqué.


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Encodage des caractères du document texte, qui sera appliqué à son
ouverture. Par défaut, il est nul \\u2014 l'encodage interne du document sera appliqué.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.nio.charset.Charset |  |

### getFixIncorrectStructure() {#getFixIncorrectStructure--}
```
public final boolean getFixIncorrectStructure()
```


Permet d'activer ou de désactiver le mécanisme de correction d'une structure XML corrompue.
Par défaut, il est désactivé (false).

*** ** * ** ***


Par défaut, seuls les documents XML correctement valides et bien formés sont
acceptables. Lorsque cette option est activée, GroupDocs.Editor essaiera de corriger
la structure XML corrompue si possible.


**Returns:**
booléen
### setFixIncorrectStructure(boolean value) {#setFixIncorrectStructure-boolean-}
```
public final void setFixIncorrectStructure(boolean value)
```


Permet d'activer ou de désactiver le mécanisme de correction d'une structure XML corrompue.
Par défaut, il est désactivé (false).

*** ** * ** ***


Par défaut, seuls les documents XML correctement valides et bien formés sont
acceptables. Lorsque cette option est activée, GroupDocs.Editor essaiera de corriger
la structure XML corrompue si possible.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getRecognizeUris() {#getRecognizeUris--}
```
public final boolean getRecognizeUris()
```


Permet d'activer l'algorithme de reconnaissance d'URI


**Returns:**
booléen
### setRecognizeUris(boolean value) {#setRecognizeUris-boolean-}
```
public final void setRecognizeUris(boolean value)
```


Permet d'activer l'algorithme de reconnaissance d'URI


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getRecognizeEmails() {#getRecognizeEmails--}
```
public final boolean getRecognizeEmails()
```


Permet d'activer l'algorithme de reconnaissance des adresses e-mail dans les attributs
valeurs


**Returns:**
booléen
### setRecognizeEmails(boolean value) {#setRecognizeEmails-boolean-}
```
public final void setRecognizeEmails(boolean value)
```


Permet d'activer l'algorithme de reconnaissance des adresses e-mail dans les attributs
valeurs


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getTrimTrailingWhitespaces() {#getTrimTrailingWhitespaces--}
```
public final boolean getTrimTrailingWhitespaces()
```


Permet d'activer la troncature des espaces de fin dans la balise interne
texte. Par défaut, il est désactivé (false) \\u2014 les espaces de fin seront
conservés.


**Returns:**
booléen
### setTrimTrailingWhitespaces(boolean value) {#setTrimTrailingWhitespaces-boolean-}
```
public final void setTrimTrailingWhitespaces(boolean value)
```


Permet d'activer la troncature des espaces de fin dans la balise interne
texte. Par défaut, il est désactivé (false) \\u2014 les espaces de fin seront
conservés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getAttributeValuesQuoteType() {#getAttributeValuesQuoteType--}
```
public final QuoteType getAttributeValuesQuoteType()
```


Permet de spécifier le type de guillemets (guillemets simples ou doubles) pour les valeurs d'attribut. Les guillemets doubles sont la valeur par défaut.


**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
### setAttributeValuesQuoteType(QuoteType value) {#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final void setAttributeValuesQuoteType(QuoteType value)
```


Permet de spécifier le type de guillemets (guillemets simples ou doubles) pour les valeurs d'attribut. Les guillemets doubles sont la valeur par défaut.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) |  |

### getHighlightOptions() {#getHighlightOptions--}
```
public final XmlHighlightOptions getHighlightOptions()
```


Permet d'ajuster la mise en évidence XML, qui sera appliquée à la structure XML lorsqu'elle est représentée en HTML. La mise en évidence par défaut est utilisée et est ajustable. Ne peut pas être nul.


**Returns:**
[XmlHighlightOptions](../../com.groupdocs.editor.options/xmlhighlightoptions)
### getFormatOptions() {#getFormatOptions--}
```
public final XmlFormatOptions getFormatOptions()
```


Permet d'ajuster le formatage XML, qui sera appliqué à la structure XML lorsqu'elle est représentée en HTML. Le formatage par défaut est utilisé et est ajustable. Ne peut pas être nul.


**Returns:**
[XmlFormatOptions](../../com.groupdocs.editor.options/xmlformatoptions)
