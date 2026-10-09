---
title: "TextType"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Représente un type de ressource textuelle pris en charge"
type: docs
weight: 12
url: /fr/nodejs-java/com.groupdocs.editor.htmlcss.resources.textual/texttype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class TextType implements IResourceType
```

Représente un type de ressource textuelle pris en charge

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextType()](#TextType--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | Valeur spéciale, qui indique un texte indéfini, inconnu ou non pris en charge |
ressource
|
|  | [getCss()](#getCss--) | Type CSS de la ressource textuelle |
|
|  | [getXml()](#getXml--) | Type XML de la ressource textuelle |
|
|  | [getFormalName()](#getFormalName--) | Renvoie un nom officiel de ce type de ressource textuelle |
|
|  | [getFileExtension()](#getFileExtension--) | Extension de fichier (sans le caractère point initial) d'un texte particulier |
ressource
|
|  | [getMimeCode()](#getMimeCode--) | Code MIME d'un type de ressource textuelle particulier |
|
|  | [equals(TextType other)](#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | Détermine si cette instance est égale à la "TextType" spécifiée |
instance
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Détermine si cette instance est égale à l'objet non converti spécifié, |
qui est probablement une autre instance de "TextType"
|
|  | [op_Equality(TextType first, TextType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | Définit si deux instances spécifiques de "TextType" sont égales |
|
|  | [op_Inequality(TextType first, TextType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | Définit si deux instances spécifiques de "TextType" ne sont pas égales |
|
|  | [hashCode()](#hashCode--) | Renvoie un code de hachage, qui est un nombre constant pour cette valeur spécifique |
type
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Renvoie la valeur TextType, qui équivaut à l'extension de nom de fichier, extraite du nom de fichier spécifié avec extension ou de l'extension pure |
|
### TextType() {#TextType--}
```
public TextType()
```


### getUndefined() {#getUndefined--}
```
public static TextType getUndefined()
```


Valeur spéciale, qui indique un texte indéfini, inconnu ou non pris en charge
ressource


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getCss() {#getCss--}
```
public static TextType getCss()
```


Type CSS de la ressource textuelle


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getXml() {#getXml--}
```
public static TextType getXml()
```


Type XML de la ressource textuelle


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Renvoie un nom officiel de ce type de ressource textuelle


**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Extension de fichier (sans le caractère point initial) d'un texte particulier
ressource


**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


Code MIME d'un type de ressource textuelle particulier


**Returns:**
java.lang.String
### equals(TextType other) {#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public final boolean equals(TextType other)
```


Détermine si cette instance est égale à la "TextType" spécifiée
instance


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Autre instance de TextType, qui doit être comparée à celle-ci pour l'égalité |
|

**Returns:**
booléen - Renvoie true si elles sont égales ou false si elles sont différentes

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si cette instance est égale à l'objet non converti spécifié,
qui est probablement une autre instance de "TextType"


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | obj | java.lang.Object | Autre instance de TextType, qui est encapsulée dans un objet |
|

**Returns:**
booléen - Renvoie true si elles sont égales ou false si elles sont différentes

### op_Equality(TextType first, TextType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Equality(TextType first, TextType second)
```


Définit si deux instances spécifiques de "TextType" sont égales


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Première instance de TextType |
|
|  | second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Deuxième instance de TextType |
|

**Returns:**
booléen - Renvoie true si elles sont égales ou false si elles sont différentes

### op_Inequality(TextType first, TextType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Inequality(TextType first, TextType second)
```


Définit si deux instances spécifiques de "TextType" ne sont pas égales


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Première instance de TextType |
|
|  | second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Deuxième instance de TextType |
|

**Returns:**
booléen - Renvoie true si elles sont différentes ou false si elles sont égales

### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage, qui est un nombre constant pour cette valeur spécifique
type


**Returns:**
int - Nombre entier signé de 4 octets. Renvoie 0 si cette instance a la valeur par défaut.

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static TextType parseFromFilenameWithExtension(String filename)
```


Renvoie la valeur TextType, qui équivaut à l'extension de nom de fichier, extraite du nom de fichier spécifié avec extension ou de l'extension pure


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | nom de fichier | java.lang.String | Nom de fichier avec extension, peut être un chemin relatif ou absolu, ou l'extension pure elle-même |
|

**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) - Parsed TextType instance on success or TextType.Undefined on failure

