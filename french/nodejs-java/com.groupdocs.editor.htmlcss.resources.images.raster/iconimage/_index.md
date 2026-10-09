---
title: "IconImage"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Représente une image au format ICON avec ses métadonnées et méthodes supplémentaires"
type: docs
weight: 12
url: /fr/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/iconimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class IconImage extends RasterImageResourceBase
```

Représente une image au format ICON avec ses métadonnées et méthodes supplémentaires

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [IconImage(String name, String contentInBase64)](#IconImage-java.lang.String-java.lang.String-) | Crée une nouvelle instance IconImage à partir du contenu, représenté en tant que |
chaîne encodée en base64, et avec le nom spécifié
|
|  | [IconImage(String name, InputStream binaryContent)](#IconImage-java.lang.String-java.io.InputStream-) | Crée une nouvelle instance IconImage à partir du contenu, représenté sous forme de flux d’octets, |
et avec le nom spécifié
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Vérifie si le flux spécifié est une image ICON valide |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Vérifie si la chaîne encodée en base64 spécifiée est une image ICON valide |
|
|  | [getType()](#getType--) | Renvoie ImageType.Icon |
|
|  | [getNumberOfImages()](#getNumberOfImages--) | Renvoie le nombre d’images présentes dans ce fichier ICON |
|
### IconImage(String name, String contentInBase64) {#IconImage-java.lang.String-java.lang.String-}
```
public IconImage(String name, String contentInBase64)
```


Crée une nouvelle instance IconImage à partir du contenu, représenté en tant que
chaîne encodée en base64, et avec le nom spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | name | java.lang.String | Nom de l’image ICON. Ne peut pas être nul, vide ou composé d’espaces. |
|
|  | contentInBase64 | java.lang.String | Contenu sous forme de chaîne encodée en base64. Ne peut pas être nul, vide ou composé d’espaces. Si ce n’est pas un contenu ICON, une exception sera levée. |
|

### IconImage(String name, InputStream binaryContent) {#IconImage-java.lang.String-java.io.InputStream-}
```
public IconImage(String name, InputStream binaryContent)
```


Crée une nouvelle instance IconImage à partir du contenu, représenté sous forme de flux d’octets,
et avec le nom spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | name | java.lang.String | Nom de l’image ICON. Ne peut pas être nul, vide ou composé d’espaces. |
|
|  | binaryContent | java.io.InputStream | Contenu sous forme de flux d'octets. La lecture commence à partir de la position d'origine. Ne peut pas être nul. Doit être lisible et recherchable. Si cette instance est libérée, ce flux sera également libéré. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Vérifie si le flux spécifié est une image ICON valide


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flux d'octets, qui contient probablement une image ICON |
|

**Returns:**
booléen - Vrai si le flux spécifié contient une image ICON valide, faux sinon

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Vérifie si la chaîne encodée en base64 spécifiée est une image ICON valide


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Contenu de l'image ICON supposée sous forme de chaîne encodée en base64 |
|

**Returns:**
booléen - Vrai si la chaîne spécifiée contient une image ICON valide, faux sinon

### getType() {#getType--}
```
public ImageType getType()
```


Renvoie ImageType.Icon


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getNumberOfImages() {#getNumberOfImages--}
```
public final int getNumberOfImages()
```


Renvoie le nombre d’images présentes dans ce fichier ICON


**Returns:**
int
