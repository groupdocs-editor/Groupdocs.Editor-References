---
title: "DropDownFormField"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Représente un champ de formulaire qui affiche une liste déroulante."
type: docs
weight: 14
url: /fr/java/com.groupdocs.editor.words.fieldmanagement/dropdownformfield/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class DropDownFormField implements IFormField
```

Représente un champ de formulaire qui affiche une liste déroulante.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [DropDownFormField(String stylesheet, String name)](#DropDownFormField-java.lang.String-java.lang.String-) | Initialise une nouvelle instance de la classe [DropDownFormField](../../com.groupdocs.editor.words.fieldmanagement/dropdownformfield) avec la feuille de style et le nom spécifiés. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getStylesheet()](#getStylesheet--) | Obtient la feuille de style appliquée au champ de formulaire. |
|
|  | [getReadonly()](#getReadonly--) | Obtient ou définit une valeur indiquant si le champ de formulaire est en lecture seule. |
|
|  | [setReadonly(boolean value)](#setReadonly-boolean-) | Obtient ou définit une valeur indiquant si le champ de formulaire est en lecture seule. |
|
|  | [getName()](#getName--) | Obtient le nom du champ de formulaire. |
|
|  | [getSelectedIndex()](#getSelectedIndex--) | Obtient ou définit l'index de l'élément sélectionné dans la liste déroulante. |
|
|  | [setSelectedIndex(int value)](#setSelectedIndex-int-) | Obtient ou définit l'index de l'élément sélectionné dans la liste déroulante. |
|
|  | [getType()](#getType--) | Obtient le type du champ de formulaire, qui est toujours FormFieldType.DropDown pour cette classe. |
|
|  | [getLocaleId()](#getLocaleId--) | Obtient ou définit l'ID de paramètre régional du champ de formulaire, qui représente la culture ou les paramètres régionaux associés au champ de formulaire. |
|
|  | [setLocaleId(int value)](#setLocaleId-int-) | Obtient ou définit l'ID de paramètre régional du champ de formulaire, qui représente la culture ou les paramètres régionaux associés au champ de formulaire. |
|
|  | [getStatusText()](#getStatusText--) | Obtient ou définit le texte d'état associé au champ de formulaire, la source du texte affiché dans la barre d'état lorsque le champ de formulaire a le focus. |
|
|  | [setStatusText(HelpText value)](#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Obtient ou définit le texte d'état associé au champ de formulaire, la source du texte affiché dans la barre d'état lorsque le champ de formulaire a le focus. |
|
|  | [getHelpText()](#getHelpText--) | Obtient ou définit le texte d'aide associé au champ de formulaire, source du texte affiché dans une boîte de dialogue lorsqu'un champ de formulaire a le focus et que l'utilisateur appuie sur F1. |
|
|  | [setHelpText(HelpText value)](#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Obtient ou définit le texte d'aide associé au champ de formulaire, source du texte affiché dans une boîte de dialogue lorsqu'un champ de formulaire a le focus et que l'utilisateur appuie sur F1. |
|
|  | [getValue()](#getValue--) | Obtient ou définit la valeur du champ de formulaire, qui représente la liste des options dans la liste déroulante. |
|
|  | [setValue(List<String> value)](#setValue-java.util.List-java.lang.String--) | Obtient ou définit la valeur du champ de formulaire, qui représente la liste des options dans la liste déroulante. |
|
### DropDownFormField(String stylesheet, String name) {#DropDownFormField-java.lang.String-java.lang.String-}
```
public DropDownFormField(String stylesheet, String name)
```


Initialise une nouvelle instance de la classe [DropDownFormField](../../com.groupdocs.editor.words.fieldmanagement/dropdownformfield) avec la feuille de style et le nom spécifiés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | feuille de style | java.lang.String | La feuille de style à appliquer au champ de formulaire. |
|
|  | name | java.lang.String | Le nom du champ de formulaire. |
|

### getStylesheet() {#getStylesheet--}
```
public final String getStylesheet()
```


Obtient la feuille de style appliquée au champ de formulaire.


**Returns:**
java.lang.String
### getReadonly() {#getReadonly--}
```
public final boolean getReadonly()
```


Obtient ou définit une valeur indiquant si le champ de formulaire est en lecture seule.


**Returns:**
boolean
### setReadonly(boolean value) {#setReadonly-boolean-}
```
public final void setReadonly(boolean value)
```


Obtient ou définit une valeur indiquant si le champ de formulaire est en lecture seule.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getName() {#getName--}
```
public final String getName()
```


Obtient le nom du champ de formulaire.


**Returns:**
java.lang.String
### getSelectedIndex() {#getSelectedIndex--}
```
public final int getSelectedIndex()
```


Obtient ou définit l'index de l'élément sélectionné dans la liste déroulante.


**Returns:**
int
### setSelectedIndex(int value) {#setSelectedIndex-int-}
```
public final void setSelectedIndex(int value)
```


Obtient ou définit l'index de l'élément sélectionné dans la liste déroulante.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getType() {#getType--}
```
public final int getType()
```


Obtient le type du champ de formulaire, qui est toujours FormFieldType.DropDown pour cette classe.


**Returns:**
int
### getLocaleId() {#getLocaleId--}
```
public final int getLocaleId()
```


Obtient ou définit l'ID de paramètre régional du champ de formulaire, qui représente la culture ou les paramètres régionaux associés au champ de formulaire.

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set the LocaleId property:
>   Set the LocaleId to represent the English (United States) culture
>  dropDownField.LocaleId = new CultureInfo("en-US").LCID;
>  
>  
> ```

<br />

<br />

*** ** * ** ***

La propriété LocaleId spécifie un identifiant de paramètre régional (LCID) qui correspond à une culture ou une région particulière.

<br />



**Returns:**
int
### setLocaleId(int value) {#setLocaleId-int-}
```
public final void setLocaleId(int value)
```


Obtient ou définit l'ID de paramètre régional du champ de formulaire, qui représente la culture ou les paramètres régionaux associés au champ de formulaire.

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set the LocaleId property:
>   Set the LocaleId to represent the English (United States) culture
>  dropDownField.LocaleId = new CultureInfo("en-US").LCID;
>  
>  
> ```

<br />

<br />

*** ** * ** ***

La propriété LocaleId spécifie un identifiant de paramètre régional (LCID) qui correspond à une culture ou une région particulière.

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getStatusText() {#getStatusText--}
```
public final HelpText getStatusText()
```


Obtient ou définit le texte d'état associé au champ de formulaire, la source du texte affiché dans la barre d'état lorsque le champ de formulaire a le focus.

<br />

*** ** * ** ***

Si elle est définie sur  false , le texte d'état ne sera pas appliqué.

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setStatusText(HelpText value) {#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setStatusText(HelpText value)
```


Obtient ou définit le texte d'état associé au champ de formulaire, la source du texte affiché dans la barre d'état lorsque le champ de formulaire a le focus.

<br />

*** ** * ** ***

Si elle est définie sur  false , le texte d'état ne sera pas appliqué.

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getHelpText() {#getHelpText--}
```
public final HelpText getHelpText()
```


Obtient ou définit le texte d'aide associé au champ de formulaire, source du texte affiché dans une boîte de dialogue lorsqu'un champ de formulaire a le focus et que l'utilisateur appuie sur F1.

<br />

*** ** * ** ***

Si elle est définie sur  false , le texte d'aide ne sera pas appliqué.

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setHelpText(HelpText value) {#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setHelpText(HelpText value)
```


Obtient ou définit le texte d'aide associé au champ de formulaire, source du texte affiché dans une boîte de dialogue lorsqu'un champ de formulaire a le focus et que l'utilisateur appuie sur F1.

<br />

*** ** * ** ***

Si elle est définie sur  false , le texte d'aide ne sera pas appliqué.

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getValue() {#getValue--}
```
public final List<String> getValue()
```


Obtient ou définit la valeur du champ de formulaire, qui représente la liste des options dans la liste déroulante.


**Returns:**
java.util.List<java.lang.String>
### setValue(List<String> value) {#setValue-java.util.List-java.lang.String--}
```
public final void setValue(List<String> value)
```


Obtient ou définit la valeur du champ de formulaire, qui représente la liste des options dans la liste déroulante.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.List<java.lang.String> |  |

