---
title: "TextResourceBase"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Classe de base pour toute ressource texte prise en charge avec un contenu texte et un encodage"
type: docs
weight: 11
url: /fr/java/com.groupdocs.editor.htmlcss.resources.textual/textresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class TextResourceBase implements IHtmlResource
```

Classe de base pour toute ressource texte prise en charge avec un contenu texte et un encodage

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [TextResourceBase(String name, String textualContent, Charset originalEncoding)](#TextResourceBase-java.lang.String-java.lang.String-java.nio.charset.Charset-) | Crée une nouvelle ressource texte à partir du contenu textuel spécifié avec encodage |
|
|  | [TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)](#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-) | Crée une nouvelle ressource texte à partir du flux d'octets spécifié et de l'encodage |
|
## Champs

| Champ | Description |
| --- | --- |
| [Disposed](#Disposed) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getName()](#getName--) | Renvoie le nom de cette ressource texte sans extension de fichier |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Renvoie le nom de fichier correct de cette ressource texte, qui consiste en le nom |
et l'extension
|
|  | [getEncoding()](#getEncoding--) | Renvoie l'encodage de cette ressource textuelle. |
|
|  | [getByteContent()](#getByteContent--) | Renvoie le contenu de cette ressource texte sous forme de flux d'octets avec l'original |
encodage
|
|  | [getTextContent()](#getTextContent--) | Renvoie le contenu de cette ressource texte sous forme de chaîne standard |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Enregistre cette ressource texte dans le fichier spécifié |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Vérifie cette instance avec le spécifié pour l'égalité. |
|
|  | [dispose()](#dispose--) | Libère cette ressource texte, libérant son contenu et rendant la plupart |
les méthodes et propriétés non fonctionnelles.
|
|  | [isDisposed()](#isDisposed--) | Détermine si cette ressource texte est libérée ou non |
|
|  | [getType()](#getType--) | Dans le type implémentant, il faut renvoyer des informations sur le type du texte |
ressource
|
### TextResourceBase(String name, String textualContent, Charset originalEncoding) {#TextResourceBase-java.lang.String-java.lang.String-java.nio.charset.Charset-}
```
public TextResourceBase(String name, String textualContent, Charset originalEncoding)
```


Crée une nouvelle ressource texte à partir du contenu textuel spécifié avec encodage


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | name | java.lang.String | Nom obligatoire de la ressource, qui sert d'identifiant unique. Il s'agit généralement d'un nom de fichier. |
|
|  | textualContent | java.lang.String | Contenu textuel de la ressource, ne peut pas être NULL ou vide |
|
|  | originalEncoding | java.nio.charset.Charset | Encodage original de la ressource, ne peut pas être NULL ou vide |
|

### TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding) {#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-}
```
public TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)
```


Crée une nouvelle ressource texte à partir du flux d'octets spécifié et de l'encodage


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | name | java.lang.String | Nom obligatoire de la ressource, qui sert d'identifiant unique. Il s'agit généralement d'un nom de fichier. |
|
|  | binaryContent | java.io.InputStream | Contenu binaire d'une ressource sous forme de flux d'octets. Ne peut pas être NULL, libéré, doit être lisible et recherchable. |
|
|  | originalEncoding | java.nio.charset.Charset | Encodage original de la ressource, ne peut pas être NULL ou vide |
|

### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


Renvoie le nom de cette ressource texte sans extension de fichier


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Renvoie le nom de fichier correct de cette ressource texte, qui consiste en le nom
et l'extension


**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Renvoie l'encodage de cette ressource textuelle. Retourne généralement UTF-8.


**Returns:**
java.nio.charset.Charset -
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Renvoie le contenu de cette ressource texte sous forme de flux d'octets avec l'original
encodage


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Renvoie le contenu de cette ressource texte sous forme de chaîne standard


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Enregistre cette ressource texte dans le fichier spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Chemin complet du fichier, qui sera créé ou réécrit s'il existe déjà |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Vérifie cette instance avec le spécifié pour l'égalité.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Autre ressource HTML de type inconnu, qui est également probablement un héritier de TextResourceBase |
|

**Returns:**
boolean - Renvoie true si elles sont égales, ou false si elles sont différentes

### dispose() {#dispose--}
```
public final void dispose()
```


Libère cette ressource texte, libérant son contenu et rendant la plupart
méthodes et propriétés non fonctionnelles. Tolérant aux appels multiples.


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Détermine si cette ressource texte est libérée ou non


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract TextType getType()
```


Dans le type implémentant, il faut renvoyer des informations sur le type du texte
ressource


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
