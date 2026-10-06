---
title: "JpegImage"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Représente une image au format JPEG Joint Photographic Experts Group avec ses métadonnées et méthodes supplémentaires"
type: docs
weight: 13
url: /fr/java/com.groupdocs.editor.htmlcss.resources.images.raster/jpegimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class JpegImage extends RasterImageResourceBase
```

Représente une image au format JPEG (Joint Photographic Experts Group) avec
ses métadonnées et méthodes supplémentaires

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [JpegImage(String name, String contentInBase64)](#JpegImage-java.lang.String-java.lang.String-) | Crée une nouvelle instance JpegImage à partir du contenu, représentée sous forme de |
chaîne encodée en base64, et avec le nom spécifié
|
|  | [JpegImage(String name, InputStream binaryContent)](#JpegImage-java.lang.String-java.io.InputStream-) | Crée une nouvelle instance JpegImage à partir du contenu, représentée sous forme de flux d'octets, |
et avec le nom spécifié
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Vérifie si le flux spécifié est une image JPEG valide |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Vérifie si la chaîne encodée en base64 spécifiée est une image JPEG valide |
|
|  | [getType()](#getType--) | Renvoie ImageType.Jpeg |
|
### JpegImage(String name, String contentInBase64) {#JpegImage-java.lang.String-java.lang.String-}
```
public JpegImage(String name, String contentInBase64)
```


Crée une nouvelle instance JpegImage à partir du contenu, représentée sous forme de
chaîne encodée en base64, et avec le nom spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | name | java.lang.String | Nom de l'image JPEG. Ne peut pas être nul, vide ou contenir uniquement des espaces. |
|
|  | contentInBase64 | java.lang.String | Contenu sous forme de chaîne encodée en base64. Ne peut pas être nul, vide ou contenir uniquement des espaces. Si ce n'est pas un contenu JPEG, une exception sera levée. |
|

### JpegImage(String name, InputStream binaryContent) {#JpegImage-java.lang.String-java.io.InputStream-}
```
public JpegImage(String name, InputStream binaryContent)
```


Crée une nouvelle instance JpegImage à partir du contenu, représentée sous forme de flux d'octets,
et avec le nom spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | name | java.lang.String | Nom de l'image JPEG. Ne peut pas être nul, vide ou contenir uniquement des espaces. |
|
|  | binaryContent | java.io.InputStream | Contenu sous forme de flux d'octets. La lecture commence à partir de la position d'origine. Ne peut pas être nul. Doit être lisible et recherchable. Si cette instance est libérée, ce flux sera également libéré. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Vérifie si le flux spécifié est une image JPEG valide


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flux d'octets, qui contient probablement une image JPEG |
|

**Returns:**
boolean - Vrai si le flux spécifié contient une image JPEG valide, faux sinon

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Vérifie si la chaîne encodée en base64 spécifiée est une image JPEG valide


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Contenu de l'image JPEG supposée sous forme de chaîne encodée en base64 |
|

**Returns:**
boolean - Vrai si la chaîne spécifiée contient une image JPEG valide, faux sinon

### getType() {#getType--}
```
public ImageType getType()
```


Renvoie ImageType.Jpeg


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
