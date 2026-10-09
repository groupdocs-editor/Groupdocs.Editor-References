---
title: "Mp3Audio"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Représente une ressource audio d'un format arbitraire"
type: docs
weight: 11
url: /fr/nodejs-java/com.groupdocs.editor.htmlcss.resources.audio/mp3audio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public final class Mp3Audio implements IHtmlResource
```

Représente une ressource audio d'un format arbitraire

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen)](#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-) | Crée une nouvelle classe Mp3Audio à partir du contenu MP3, représenté sous forme de flux d'octets, et avec le nom spécifié |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [isValid(System.IO.Stream binaryContent)](#isValid-com.aspose.ms.System.IO.Stream-) | Vérifie si le flux spécifié est un contenu MP3 valide |
|
|  | [getName()](#getName--) | Renvoie le nom de ce contenu MP3. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Renvoie le nom de fichier correct de ce contenu MP3, qui se compose du nom et de l'extension. |
|
|  | [getType()](#getType--) | Renvoie un AudioFormat.Mp3 (satisfait également IHtmlResource.getFormat() via un retour covariant) |
|
|  | [getByteContent()](#getByteContent--) | Renvoie le contenu de cette police sous forme de flux d'octets |
|
|  | [getByteContentInternal()](#getByteContentInternal--) | Renvoie le contenu de cette ressource audio MP3 sous forme de flux d'octets avec la position d'origine |
|
|  | [getTextContent()](#getTextContent--) | Renvoie le contenu de cette ressource MP3 sous forme de chaîne encodée en base64. |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Enregistre cette ressource MP3 dans le fichier spécifié |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Vérifie cette instance avec la ressource HTML spécifiée pour l'égalité de référence |
|
|  | [equals(Mp3Audio other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-) | Vérifie cette instance avec la ressource de police spécifiée pour l'égalité de référence |
|
|  | [dispose()](#dispose--) | Libère cette ressource MP3, libérant son contenu et rendant la plupart des méthodes et propriétés non fonctionnelles |
|
|  | [isDisposed()](#isDisposed--) | Détermine si le contenu de ce MP3 est libéré ou non |
|
| [addDisposedListener(EventHandler value)](#addDisposedListener-com.groupdocs.editor.handler.EventHandler-) |  |
| [removeDisposedListener(EventHandler value)](#removeDisposedListener-com.groupdocs.editor.handler.EventHandler-) |  |
### Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen) {#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-}
```
public Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen)
```


Crée une nouvelle classe Mp3Audio à partir du contenu MP3, représenté sous forme de flux d'octets, et avec le nom spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | name | java.lang.String | Nom du contenu MP3. Ne peut pas être nul, vide ou contenir uniquement des espaces. |
|
|  | binaryContent | com.aspose.ms.System.IO.Stream | Contenu sous forme de flux d'octets. La lecture commence à partir de la position d'origine. Ne peut pas être nul. Doit être lisible et recherchable. Si cette instance est libérée, ce flux sera également libéré. |
|
|  | leaveOpen | booléen | Détermine s'il faut libérer ou non le flux spécifié lorsque l'instance Mp3Audio est libérée |
|

### isValid(System.IO.Stream binaryContent) {#isValid-com.aspose.ms.System.IO.Stream-}
```
public static boolean isValid(System.IO.Stream binaryContent)
```


Vérifie si le flux spécifié est un contenu MP3 valide


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | binaryContent | com.aspose.ms.System.IO.Stream | Flux d'octets, qui contient probablement un contenu MP3 |
|

**Returns:**
booléen - Vrai si le flux spécifié contient un contenu MP3 valide, faux sinon

### getName() {#getName--}
```
public String getName()
```


Renvoie le nom de ce contenu MP3. Ne contient généralement pas l'extension du nom de fichier et peut théoriquement différer du nom de fichier.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public String getFilenameWithExtension()
```


Renvoie le nom de fichier correct de ce contenu MP3, qui se compose du nom et de l'extension. Théoriquement, il peut différer du nom.


**Returns:**
java.lang.String
### getType() {#getType--}
```
public AudioType getType()
```


Renvoie un AudioFormat.Mp3 (satisfait également IHtmlResource.getFormat() via un retour covariant)


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Renvoie le contenu de cette police sous forme de flux d'octets


**Returns:**
java.io.InputStream
### getByteContentInternal() {#getByteContentInternal--}
```
public System.IO.Stream getByteContentInternal()
```


Renvoie le contenu de cette ressource audio MP3 sous forme de flux d'octets avec la position d'origine


**Returns:**
com.aspose.ms.System.IO.Stream
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Renvoie le contenu de cette ressource MP3 sous forme de chaîne encodée en base64. Cette valeur est mise en cache après le premier appel.


**Returns:**
java.lang.String
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Enregistre cette ressource MP3 dans le fichier spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Chemin complet du fichier, qui sera créé ou réécrit |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public boolean equals(IHtmlResource other)
```


Vérifie cette instance avec la ressource HTML spécifiée pour l'égalité de référence


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Autre implémentation de l'interface IHtmlResource |
|

**Returns:**
booléen - Vrai si égaux, faux si différents

### equals(Mp3Audio other) {#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-}
```
public boolean equals(Mp3Audio other)
```


Vérifie cette instance avec la ressource de police spécifiée pour l'égalité de référence


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [Mp3Audio](../../com.groupdocs.editor.htmlcss.resources.audio/mp3audio) | Autre instance de la classe Mp3Audio |
|

**Returns:**
booléen - Vrai si égaux, faux si différents

### dispose() {#dispose--}
```
public void dispose()
```


Libère cette ressource MP3, libérant son contenu et rendant la plupart des méthodes et propriétés non fonctionnelles


### isDisposed() {#isDisposed--}
```
public boolean isDisposed()
```


Détermine si le contenu de ce MP3 est libéré ou non


**Returns:**
booléen
### addDisposedListener(EventHandler value) {#addDisposedListener-com.groupdocs.editor.handler.EventHandler-}
```
public void addDisposedListener(EventHandler value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EventHandler](../../com.groupdocs.editor.handler/eventhandler) |  |

### removeDisposedListener(EventHandler value) {#removeDisposedListener-com.groupdocs.editor.handler.EventHandler-}
```
public void removeDisposedListener(EventHandler value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EventHandler](../../com.groupdocs.editor.handler/eventhandler) |  |

