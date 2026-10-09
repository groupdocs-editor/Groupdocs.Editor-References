---
title: "DocumentFormatBase"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Représente la classe de base pour les formats de documents offrant des fonctionnalités communes aux instances de format."
type: docs
weight: 10
url: /fr/nodejs-java/com.groupdocs.editor.formats.abstraction/documentformatbase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)

**All Implemented Interfaces:**
[com.groupdocs.editor.formats.abstraction.IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat)
```
public abstract class DocumentFormatBase extends FormatFamilyBase implements IDocumentFormat
```

Représente la classe de base pour les formats de documents, offrant une fonctionnalité commune aux instances de format.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getMime()](#getMime--) | Obtient le type MIME du format de document. |
|
|  | [getExtension()](#getExtension--) | Obtient l'extension de fichier du format de document. |
|
|  | [getFormatFamily()](#getFormatFamily--) | Obtient la famille de format à laquelle le format de document appartient. |
|
|  | [<T>fromMime(Class<T> clazz, String mime)](#-T-fromMime-java.lang.Class-T--java.lang.String-) | Récupère une instance du type spécifié |
T
qui possède le type MIME spécifié.
|
|  | [hashCode()](#hashCode--) | Renvoie un code de hachage pour l'objet actuel. |
|
|  | [equals(IDocumentFormat other)](#equals-com.groupdocs.editor.formats.abstraction.IDocumentFormat-) | Détermine si cette instance est égale à l'instance [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) spécifiée. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Détermine si cette instance est égale à l'instance [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) spécifiée. |
|
|  | [toString(DocumentFormatBase extension)](#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | Convertit implicitement une instance [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) en chaîne. |
|
### getMime() {#getMime--}
```
public final String getMime()
```


Obtient le type MIME du format de document.


**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Obtient l'extension de fichier du format de document.


**Returns:**
java.lang.String
### getFormatFamily() {#getFormatFamily--}
```
public final FormatFamilies getFormatFamily()
```


Obtient la famille de format à laquelle le format de document appartient.


**Returns:**
[FormatFamilies](../../com.groupdocs.editor.formats/formatfamilies)
### <T>fromMime(Class<T> clazz, String mime) {#-T-fromMime-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromMime(Class<T> clazz, String mime)
```


Récupère une instance du type spécifié
T
qui possède le type MIME spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | mime | java.lang.String | Le type MIME du format de document. |


T
: Le type de format de document.
|

**Returns:**
T - Une instance du type spécifié T avec le type MIME spécifié.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour l'objet actuel.


**Returns:**
int - Un code de hachage pour l'objet actuel, combinant les codes de hachage de l'objet de base, du type MIME, de l'extension de fichier et de la famille de format.

### equals(IDocumentFormat other) {#equals-com.groupdocs.editor.formats.abstraction.IDocumentFormat-}
```
public final boolean equals(IDocumentFormat other)
```


Détermine si cette instance est égale à l'instance [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) spécifiée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) | L'instance [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) à comparer avec l'instance actuelle. |
|

**Returns:**
boolean -  true  si l'[IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) spécifié est égal à l'instance actuelle ; sinon,  false .

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si cette instance est égale à l'instance [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) spécifiée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | obj | java.lang.Object | L'instance [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) à comparer avec l'instance actuelle. |
|

**Returns:**
boolean -  true  si le [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) spécifié est égal à l'instance actuelle ; sinon,  false .

### toString(DocumentFormatBase extension) {#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public static String toString(DocumentFormatBase extension)
```


Convertit implicitement une instance [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) en chaîne.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | extension | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) | L'instance [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) à convertir. |
|

**Returns:**
java.lang.String - L'extension de fichier de l'instance [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase).

