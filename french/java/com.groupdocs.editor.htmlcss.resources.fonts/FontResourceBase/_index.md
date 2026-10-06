---
title: "FontResourceBase"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Classe de base pour tout type de police pris en charge en tant que ressource du document HTML avec toutes ses propriétés"
type: docs
weight: 11
url: /fr/java/com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class FontResourceBase implements IHtmlResource
```

Classe de base pour tout type de police pris en charge en tant que ressource du document HTML
avec toutes ses propriétés

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FontResourceBase()](#FontResourceBase--) |  |
## Champs

| Champ | Description |
| --- | --- |
|  | [Disposed](#Disposed) | Événement qui se produit lorsque cette police est libérée |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getName()](#getName--) | Renvoie le nom de cette ressource de police. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Renvoie le nom de fichier correct de cette ressource de police, qui se compose du nom |
et de l'extension.
|
|  | [getByteContent()](#getByteContent--) | Renvoie le contenu de cette police sous forme de flux d'octets |
|
|  | [getTextContent()](#getTextContent--) | Renvoie le contenu de cette police sous forme de chaîne encodée en base64. |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Enregistre cette police dans le fichier spécifié |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Vérifie cette instance avec la ressource HTML spécifiée par égalité de référence |
|
|  | [equals(FontResourceBase other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-) | Vérifie cette instance avec la ressource de police spécifiée par égalité de référence |
|
|  | [dispose()](#dispose--) | Libère cette ressource de police, en libérant son contenu et en rendant la plupart |
méthodes et propriétés non fonctionnelles
|
|  | [isDisposed()](#isDisposed--) | Détermine si cette police est libérée ou non |
|
|  | [getType()](#getType--) | Dans le type implémentant, il faut renvoyer des informations sur le type de |
ressource de police en tant qu'instance d'un type FontType spécifique, qui
encapsule toutes les informations spécifiques au type
|
### FontResourceBase() {#FontResourceBase--}
```
public FontResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


Événement qui se produit lorsque cette police est libérée


### getName() {#getName--}
```
public final String getName()
```


Renvoie le nom de cette ressource de police. Habituellement, il ne contient pas le nom de fichier
extension et théoriquement peut différer du nom de fichier.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Renvoie le nom de fichier correct de cette ressource de police, qui se compose du nom
et l'extension. Théoriquement, cela peut différer du nom.


**Returns:**
java.lang.String
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Renvoie le contenu de cette police sous forme de flux d'octets


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Renvoie le contenu de cette police sous forme de chaîne encodée en base64. Cette valeur est
mise en cache après le premier appel.


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Enregistre cette police dans le fichier spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Chemin complet du fichier, qui sera créé ou réécrit. |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Vérifie cette instance avec la ressource HTML spécifiée par égalité de référence


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Autre implémentation de l'interface IHtmlResource. |
|

**Returns:**
booléen - True si égaux, false si différents

### equals(FontResourceBase other) {#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-}
```
public final boolean equals(FontResourceBase other)
```


Vérifie cette instance avec la ressource de police spécifiée par égalité de référence


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase) | Autre héritier de la classe abstraite FontResourceBase |
|

**Returns:**
booléen - True si égaux, false si différents

### dispose() {#dispose--}
```
public final void dispose()
```


Libère cette ressource de police, en libérant son contenu et en rendant la plupart
méthodes et propriétés non fonctionnelles


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Détermine si cette police est libérée ou non


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract FontType getType()
```


Dans le type implémentant, il faut renvoyer des informations sur le type de
ressource de police en tant qu'instance d'un type FontType spécifique, qui
encapsule toutes les informations spécifiques au type


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
