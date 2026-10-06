---
title: "AudioType"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Représente un format de type audio pris en charge"
type: docs
weight: 10
url: /fr/java/com.groupdocs.editor.htmlcss.resources.audio/audiotype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class AudioType implements IResourceType
```

Représente un type audio pris en charge (format).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [AudioType()](#AudioType--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getFormalName()](#getFormalName--) | Nom officiel de ce format audio |
|
|  | [getFileExtension()](#getFileExtension--) | Extension de nom de fichier (sans le caractère point) pour ce format audio |
|
|  | [getMimeCode()](#getMimeCode--) | Code MIME pour ce format audio |
|
|  | [equals(AudioType other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | Détermine si cette instance est égale à l'instance "AudioType" spécifiée |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Détermine si cette instance est égale à l'objet non casté spécifié, qui est vraisemblablement une autre instance "AudioType" |
|
|  | [op_Equality(AudioType first, AudioType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | Vérifie si deux valeurs "AudioType" sont égales |
|
|  | [op_Inequality(AudioType first, AudioType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | Vérifie si deux valeurs "AudioType" ne sont pas égales |
|
|  | [hashCode()](#hashCode--) | Renvoie un code de hachage, qui est un nombre constant pour ce type de valeur spécifique |
|
|  | [getUndefined()](#getUndefined--) | Valeur spéciale, qui indique un format audio indéfini, inconnu ou non pris en charge |
|
|  | [getMp3()](#getMp3--) | Représente un format audio MPEG-1 Audio Layer III |
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Renvoie la valeur AudioType, qui est équivalente à l'extension de nom de fichier, extraite du nom de fichier spécifié |
|
### AudioType() {#AudioType--}
```
public AudioType()
```


### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Nom officiel de ce format audio


**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Extension de nom de fichier (sans le caractère point) pour ce format audio


**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


Code MIME pour ce format audio


**Returns:**
java.lang.String
### equals(AudioType other) {#equals-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public final boolean equals(AudioType other)
```


Détermine si cette instance est égale à l'instance "AudioType" spécifiée


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Autre instance AudioType à vérifier avec celle-ci |
|

**Returns:**
booléen - True si égaux, false si différents

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si cette instance est égale à l'objet non casté spécifié, qui est vraisemblablement une autre instance "AudioType"


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | obj | java.lang.Object | Autre instance probablement de la structure AudioType, qui a été encapsulée dans System.Object |
|

**Returns:**
booléen - True si égaux, false si différents

### op_Equality(AudioType first, AudioType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Equality(AudioType first, AudioType second)
```


Vérifie si deux valeurs "AudioType" sont égales


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Premier AudioType à vérifier |
|
|  | second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Deuxième AudioType à vérifier |
|

**Returns:**
booléen - True si égaux, false si différents

### op_Inequality(AudioType first, AudioType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Inequality(AudioType first, AudioType second)
```


Vérifie si deux valeurs "AudioType" ne sont pas égales


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Premier AudioType à vérifier |
|
|  | second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Deuxième AudioType à vérifier |
|

**Returns:**
booléen - True si égaux, false si différents

### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage, qui est un nombre constant pour ce type de valeur spécifique


**Returns:**
int - entier signé de 4 octets, 0 pour la valeur Undefined

### getUndefined() {#getUndefined--}
```
public static AudioType getUndefined()
```


Valeur spéciale, qui indique un format audio indéfini, inconnu ou non pris en charge


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getMp3() {#getMp3--}
```
public static AudioType getMp3()
```


Représente un format audio MPEG-1 Audio Layer III


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static AudioType parseFromFilenameWithExtension(String filename)
```


Renvoie la valeur AudioType, qui est équivalente à l'extension de nom de fichier, extraite du nom de fichier spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | nom de fichier | java.lang.String | Nom de fichier arbitraire, peut être un chemin relatif ou complet |
|

**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) - AudioType value. Returns AudioType.Undefined, if extension cannot be recognized.

