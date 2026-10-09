---
title: "CheckBoxForm"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Représente un champ de formulaire qui affiche une case à cocher."
type: docs
weight: 10
url: /fr/nodejs-java/com.groupdocs.editor.words.fieldmanagement/checkboxform/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class CheckBoxForm implements IFormField
```

Représente un champ de formulaire qui affiche une case à cocher.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [CheckBoxForm(String stylesheet, String name)](#CheckBoxForm-java.lang.String-java.lang.String-) | Initialise une nouvelle instance de la classe [CheckBoxForm](../../com.groupdocs.editor.words.fieldmanagement/checkboxform) avec la feuille de style et le nom spécifiés. |
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
|  | [getType()](#getType--) | Obtient le type du champ de formulaire, qui est toujours FormFieldType.CheckBox pour cette classe. |
|
|  | [getLocaleId()](#getLocaleId--) | Obtient ou définit l'ID de paramètres régionaux du champ de formulaire, qui représente la culture ou les paramètres régionaux associés au champ de formulaire. |
|
|  | [setLocaleId(int value)](#setLocaleId-int-) | Obtient ou définit l'ID de paramètres régionaux du champ de formulaire, qui représente la culture ou les paramètres régionaux associés au champ de formulaire. |
|
|  | [getStatusText()](#getStatusText--) | Obtient ou définit le texte d'état associé au champ de formulaire, la source du texte affiché dans la barre d'état lorsque le champ de formulaire a le focus. |
|
|  | [setStatusText(HelpText value)](#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Obtient ou définit le texte d'état associé au champ de formulaire, la source du texte affiché dans la barre d'état lorsque le champ de formulaire a le focus. |
|
|  | [getHelpText()](#getHelpText--) | Obtient ou définit le texte d'aide associé au champ de formulaire, la source du texte affiché dans une boîte de dialogue lorsque le champ de formulaire a le focus et que l'utilisateur appuie sur F1. |
|
|  | [setHelpText(HelpText value)](#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Obtient ou définit le texte d'aide associé au champ de formulaire, la source du texte affiché dans une boîte de dialogue lorsque le champ de formulaire a le focus et que l'utilisateur appuie sur F1. |
|
|  | [getValue()](#getValue--) | Obtient ou définit la valeur du champ de formulaire, qui représente l'état de la case à cocher. |
|
|  | [setValue(boolean value)](#setValue-boolean-) | Obtient ou définit la valeur du champ de formulaire, qui représente l'état de la case à cocher. |
|
### CheckBoxForm(String stylesheet, String name) {#CheckBoxForm-java.lang.String-java.lang.String-}
```
public CheckBoxForm(String stylesheet, String name)
```


Initialise une nouvelle instance de la classe [CheckBoxForm](../../com.groupdocs.editor.words.fieldmanagement/checkboxform) avec la feuille de style et le nom spécifiés.


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
booléen
### setReadonly(boolean value) {#setReadonly-boolean-}
```
public final void setReadonly(boolean value)
```


Obtient ou définit une valeur indiquant si le champ de formulaire est en lecture seule.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getName() {#getName--}
```
public final String getName()
```


Obtient le nom du champ de formulaire.


**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


Obtient le type du champ de formulaire, qui est toujours FormFieldType.CheckBox pour cette classe.


**Returns:**
int
### getLocaleId() {#getLocaleId--}
```
public final int getLocaleId()
```


Obtient ou définit l'ID de paramètres régionaux du champ de formulaire, qui représente la culture ou les paramètres régionaux associés au champ de formulaire.

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set the LocaleId property:
>   Set the LocaleId to represent the English (United States) culture
>  checkBoxField.LocaleId = new CultureInfo("en-US").LCID;
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


Obtient ou définit l'ID de paramètres régionaux du champ de formulaire, qui représente la culture ou les paramètres régionaux associés au champ de formulaire.

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set the LocaleId property:
>   Set the LocaleId to represent the English (United States) culture
>  checkBoxField.LocaleId = new CultureInfo("en-US").LCID;
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

Si réglé sur  false , le texte d'état ne sera pas appliqué.

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

Si réglé sur  false , le texte d'état ne sera pas appliqué.

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getHelpText() {#getHelpText--}
```
public final HelpText getHelpText()
```


Obtient ou définit le texte d'aide associé au champ de formulaire, la source du texte affiché dans une boîte de dialogue lorsque le champ de formulaire a le focus et que l'utilisateur appuie sur F1.

<br />

*** ** * ** ***

Si réglé sur  false , le texte d'aide ne sera pas appliqué.

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setHelpText(HelpText value) {#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setHelpText(HelpText value)
```


Obtient ou définit le texte d'aide associé au champ de formulaire, la source du texte affiché dans une boîte de dialogue lorsque le champ de formulaire a le focus et que l'utilisateur appuie sur F1.

<br />

*** ** * ** ***

Si réglé sur  false , le texte d'aide ne sera pas appliqué.

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getValue() {#getValue--}
```
public final boolean getValue()
```


Obtient ou définit la valeur du champ de formulaire, qui représente l'état de la case à cocher.


**Returns:**
booléen
### setValue(boolean value) {#setValue-boolean-}
```
public final void setValue(boolean value)
```


Obtient ou définit la valeur du champ de formulaire, qui représente l'état de la case à cocher.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

