---
title: "TiffImage"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Représente une image au format TIFF Tagged Image File Format avec ses métadonnées et méthodes supplémentaires"
type: docs
weight: 16
url: /fr/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/tiffimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class TiffImage extends RasterImageResourceBase
```

Représente une image au format TIFF (Tagged Image File Format) avec ses
métadonnées et méthodes supplémentaires


*** ** * ** ***

Voir https://en.wikipedia.org/wiki/TIFF pour plus de détails. Dans de très rares cas, le TIFF est présent dans les documents WordProcessing.

<br />


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [TiffImage(String name, String contentInBase64)](#TiffImage-java.lang.String-java.lang.String-) | Crée une nouvelle instance de TiffImage à partir du contenu, représentée sous forme de |
chaîne encodée en base64, et avec le nom spécifié
|
|  | [TiffImage(String name, InputStream binaryContent)](#TiffImage-java.lang.String-java.io.InputStream-) | Crée une nouvelle instance GifImage à partir du contenu, représenté sous forme de flux d'octets, |
et avec le nom spécifié
|
| [TiffImage(String name, System.IO.Stream binaryContent)](#TiffImage-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Vérifie si le flux spécifié est une image TIFF valide |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Vérifie si la chaîne encodée en base64 spécifiée est une image TIFF valide |
|
|  | [getType()](#getType--) | Renvoie ImageType.Tiff |
|
|  | [getFramesCount()](#getFramesCount--) | Renvoie le nombre de cadres (images) dans cette image TIFF. |
|
### TiffImage(String name, String contentInBase64) {#TiffImage-java.lang.String-java.lang.String-}
```
public TiffImage(String name, String contentInBase64)
```


Crée une nouvelle instance de TiffImage à partir du contenu, représentée sous forme de
chaîne encodée en base64, et avec le nom spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | name | java.lang.String | Nom de l'image TIFF. Ne peut pas être nul, vide ou contenir uniquement des espaces. |
|
|  | contentInBase64 | java.lang.String | Contenu sous forme de chaîne encodée en base64. Ne peut pas être nul, vide ou contenir uniquement des espaces. Si ce n'est pas un contenu TIFF, une exception sera levée. |
|

### TiffImage(String name, InputStream binaryContent) {#TiffImage-java.lang.String-java.io.InputStream-}
```
public TiffImage(String name, InputStream binaryContent)
```


Crée une nouvelle instance GifImage à partir du contenu, représenté sous forme de flux d'octets,
et avec le nom spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | name | java.lang.String | Nom de l'image GIF. Ne peut pas être nul, vide ou contenir uniquement des espaces. |
|
|  | binaryContent | java.io.InputStream | Contenu sous forme de flux d'octets. La lecture commence à partir de la position d'origine. Ne peut pas être nul. Doit être lisible et recherchable. Si cette instance est libérée, ce flux sera également libéré. |
|

### TiffImage(String name, System.IO.Stream binaryContent) {#TiffImage-java.lang.String-com.aspose.ms.System.IO.Stream-}
```
public TiffImage(String name, System.IO.Stream binaryContent)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |
| binaryContent | com.aspose.ms.System.IO.Stream |  |

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Vérifie si le flux spécifié est une image TIFF valide


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flux d'octets, qui contient probablement une image TIFF |
|

**Returns:**
booléen - Vrai si le flux spécifié contient une image TIFF valide, faux sinon

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Vérifie si la chaîne encodée en base64 spécifiée est une image TIFF valide


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Contenu de l'image TIFF supposée sous forme de chaîne encodée en base64 |
|

**Returns:**
booléen - Vrai si la chaîne spécifiée contient une image TIFF valide, faux sinon

### getType() {#getType--}
```
public ImageType getType()
```


Renvoie ImageType.Tiff


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getFramesCount() {#getFramesCount--}
```
public final int getFramesCount()
```


Renvoie le nombre de cadres (images) dans cette image TIFF. Ne peut pas être
inférieur à 1.


**Returns:**
int -
