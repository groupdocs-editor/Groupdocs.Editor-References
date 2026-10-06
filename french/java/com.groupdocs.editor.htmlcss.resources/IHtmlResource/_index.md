---
title: "IHtmlResource"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Représente une instance de la ressource HTML inconnue raster ou vecteur image feuille de style police texte ressource CSS XML etc."
type: docs
weight: 12
url: /fr/java/com.groupdocs.editor.htmlcss.resources/ihtmlresource/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public interface IHtmlResource extends IAuxDisposable
```

Représente une instance de la ressource HTML inconnue (raster ou vecteur image,
feuille de style, police, ressource texte (CSS, XML) etc.)

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getName()](#getName--) | Nom de la ressource HTML |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Nom de fichier correct de la ressource spécifiée avec le fichier approprié |
extension
|
|  | [getType()](#getType--) | Type de la ressource HTML |
|
|  | [getByteContent()](#getByteContent--) | Contenu de la ressource HTML sous forme de flux d'octets |
|
|  | [getTextContent()](#getTextContent--) | Contenu de la ressource HTML sous forme de chaîne texte encodée en base64 |
pour les ressources binaires ou un texte simple pour les ressources textuelles
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Enregistre une ressource actuelle dans le fichier spécifié |
|
### getName() {#getName--}
```
public abstract String getName()
```


Nom de la ressource HTML


**Returns:**
java.lang.String -
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public abstract String getFilenameWithExtension()
```


Nom de fichier correct de la ressource spécifiée avec le fichier approprié
extension


**Returns:**
java.lang.String -
### getType() {#getType--}
```
public abstract IResourceType getType()
```


Type de la ressource HTML


**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) - 
### getByteContent() {#getByteContent--}
```
public abstract InputStream getByteContent()
```


Contenu de la ressource HTML sous forme de flux d'octets


**Returns:**
java.io.InputStream
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


Contenu de la ressource HTML sous forme de chaîne texte encodée en base64
pour les ressources binaires ou un texte simple pour les ressources textuelles


**Returns:**
java.lang.String
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


Enregistre une ressource actuelle dans le fichier spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Chemin complet du fichier, qui sera créé ou réécrit avec le contenu d'une ressource actuelle |
|

