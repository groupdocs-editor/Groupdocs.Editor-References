---
title: "PngImage"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Représente une image au format PNG Portable Network Graphics avec ses métadonnées et méthodes supplémentaires"
type: docs
weight: 14
url: /fr/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/pngimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class PngImage extends RasterImageResourceBase
```

Représente une image au format PNG (Portable Network Graphics) avec ses
métadonnées et méthodes supplémentaires

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [PngImage(String name, String contentInBase64)](#PngImage-java.lang.String-java.lang.String-) | Crée une nouvelle instance de PngImage à partir du contenu, représentée sous forme encodée en base64 |
chaîne, et avec le nom spécifié
|
|  | [PngImage(String name, InputStream binaryContent)](#PngImage-java.lang.String-java.io.InputStream-) | Crée une nouvelle instance de PngImage à partir du contenu, représentée sous forme de flux d'octets, |
et avec le nom spécifié
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Vérifie si le flux spécifié est une image PNG valide |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Vérifie si la chaîne encodée en base64 spécifiée est une image PNG valide |
|
|  | [getType()](#getType--) | Renvoie ImageType.Png |
|
### PngImage(String name, String contentInBase64) {#PngImage-java.lang.String-java.lang.String-}
```
public PngImage(String name, String contentInBase64)
```


Crée une nouvelle instance de PngImage à partir du contenu, représentée sous forme encodée en base64
chaîne, et avec le nom spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | name | java.lang.String | Nom de l'image PNG. Ne peut pas être nul, vide ou contenir uniquement des espaces. |
|
|  | contentInBase64 | java.lang.String | Contenu sous forme de chaîne encodée en base64. Ne peut pas être nul, vide ou contenir uniquement des espaces. Si ce n'est pas un contenu PNG, une exception sera levée. |
|

### PngImage(String name, InputStream binaryContent) {#PngImage-java.lang.String-java.io.InputStream-}
```
public PngImage(String name, InputStream binaryContent)
```


Crée une nouvelle instance de PngImage à partir du contenu, représentée sous forme de flux d'octets,
et avec le nom spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | name | java.lang.String | Nom de l'image PNG. Ne peut pas être nul, vide ou contenir uniquement des espaces. |
|
|  | binaryContent | java.io.InputStream | Contenu sous forme de flux d'octets. La lecture commence à partir de la position d'origine. Ne peut pas être nul. Doit être lisible et recherchable. Si cette instance est libérée, ce flux sera également libéré. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Vérifie si le flux spécifié est une image PNG valide


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flux d'octets, qui contient probablement une image PNG |
|

**Returns:**
booléen - Vrai si le flux spécifié contient une image PNG valide, sinon faux

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Vérifie si la chaîne encodée en base64 spécifiée est une image PNG valide


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Contenu de l'image PNG supposée sous forme de chaîne encodée en base64 |
|

**Returns:**
booléen - Vrai si la chaîne spécifiée contient une image PNG valide, sinon faux

### getType() {#getType--}
```
public ImageType getType()
```


Renvoie ImageType.Png


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
