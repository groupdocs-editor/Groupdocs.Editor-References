---
title: "WmfImage"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Représente une image vectorielle au format WMF Windows MetaFile avec ses métadonnées et ses méthodes supplémentaires"
type: docs
weight: 14
url: /fr/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/wmfimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase), [com.groupdocs.editor.htmlcss.resources.images.vector.MetaImageBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase)
```
public final class WmfImage extends MetaImageBase
```

Représente une image vectorielle au format WMF (Windows MetaFile) avec ses
métadonnées et méthodes supplémentaires

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [WmfImage(String name, String contentInBase64)](#WmfImage-java.lang.String-java.lang.String-) | Crée une nouvelle instance de WmfImage à partir du contenu, représenté en base64 |
chaîne, et avec le nom spécifié
|
|  | [WmfImage(String name, InputStream binaryContent)](#WmfImage-java.lang.String-java.io.InputStream-) | Crée une nouvelle instance de WmfImage à partir du contenu, représenté sous forme de flux d'octets, |
et avec le nom spécifié
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Vérifie si le flux spécifié est une image WMF valide |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Vérifie si la chaîne encodée en base64 spécifiée est une image WMF valide |
|
|  | [getType()](#getType--) | Renvoie ImageType.Wmf |
|
|  | [getByteContent()](#getByteContent--) | Renvoie le contenu de cette image WMF sous forme de flux binaire |
|
|  | [getTextContent()](#getTextContent--) | Renvoie le contenu de cette image WMF sous forme de texte brut |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Enregistre cette image WMF dans le fichier |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Enregistre cette image vectorielle WMF en image PNG raster |
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | Enregistre cette image vectorielle WMF en image SVG vectorielle |
|
|  | [dispose()](#dispose--) | Dispose de cette image WMF en libérant son contenu et en rendant la plupart de ses |
méthodes et propriétés non fonctionnelles
|
### WmfImage(String name, String contentInBase64) {#WmfImage-java.lang.String-java.lang.String-}
```
public WmfImage(String name, String contentInBase64)
```


Crée une nouvelle instance de WmfImage à partir du contenu, représenté en base64
chaîne, et avec le nom spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | name | java.lang.String | Nom de l'image WMF. Ne peut pas être nul, vide ou contenir uniquement des espaces. |
|
|  | contentInBase64 | java.lang.String | Contenu sous forme de chaîne encodée en base64. Ne peut pas être nul, vide ou contenir uniquement des espaces. Si ce n'est pas un contenu WMF, une exception sera levée. |
|

### WmfImage(String name, InputStream binaryContent) {#WmfImage-java.lang.String-java.io.InputStream-}
```
public WmfImage(String name, InputStream binaryContent)
```


Crée une nouvelle instance de WmfImage à partir du contenu, représenté sous forme de flux d'octets,
et avec le nom spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | name | java.lang.String | Nom de l'image WMF. Ne peut pas être nul, vide ou contenir uniquement des espaces. |
|
|  | binaryContent | java.io.InputStream | Contenu sous forme de flux d'octets. La lecture commence à partir de la position d'origine. Ne peut pas être nul. Doit être lisible et recherchable. Si cette instance est libérée, ce flux sera également libéré. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Vérifie si le flux spécifié est une image WMF valide


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flux d'octets d'entrée. Ne peut pas être NULL, doit prendre en charge la lecture et le positionnement. |
|

**Returns:**
booléen - True si le flux spécifié contient une image WMF valide, false sinon

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Vérifie si la chaîne encodée en base64 spécifiée est une image WMF valide


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Chaîne d'entrée, où le contenu de l'image WMF est stocké en encodage base64. Ne peut pas être NULL ou vide. |
|

**Returns:**
booléen - True si la chaîne spécifiée contient une image WMF valide, false sinon

### getType() {#getType--}
```
public ImageType getType()
```


Renvoie ImageType.Wmf


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Renvoie le contenu de cette image WMF sous forme de flux binaire


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Renvoie le contenu de cette image WMF sous forme de texte brut


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Enregistre cette image WMF dans le fichier


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Chemin complet du fichier, qui sera créé (s'il n'existe pas) ou écrasé (s'il existe) avec le contenu de cette image WMF |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


Enregistre cette image vectorielle WMF en image PNG raster


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Flux de sortie, dans lequel le contenu de l'image PNG sera écrit. Ne peut pas être NULL et doit être accessible en écriture. |
|

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public void saveToSvg(OutputStream outputSvgContent)
```


Enregistre cette image vectorielle WMF en image SVG vectorielle


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | Flux de sortie, dans lequel le contenu de l'image SVG sera écrit. Ne peut pas être NULL et doit être accessible en écriture. |
|

### dispose() {#dispose--}
```
public void dispose()
```


Dispose de cette image WMF en libérant son contenu et en rendant la plupart de ses
méthodes et propriétés non fonctionnelles


