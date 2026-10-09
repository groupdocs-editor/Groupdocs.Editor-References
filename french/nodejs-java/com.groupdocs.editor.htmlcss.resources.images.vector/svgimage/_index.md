---
title: "SvgImage"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Représente une image vectorielle au format SVG Scalable Vector Graphics avec ses métadonnées et méthodes supplémentaires"
type: docs
weight: 12
url: /fr/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/svgimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)
```
public final class SvgImage extends VectorImageResourceBase
```

Représente une image vectorielle au format SVG (Scalable Vector Graphics) avec ses
métadonnées et méthodes supplémentaires

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [SvgImage(String name, String content)](#SvgImage-java.lang.String-java.lang.String-) | Crée une nouvelle instance SvgImage à partir du contenu, représenté sous forme de chaîne habituelle, |
et avec le nom spécifié
|
|  | [SvgImage(String name, InputStream binaryContent)](#SvgImage-java.lang.String-java.io.InputStream-) | Crée une nouvelle instance SvgImage à partir du contenu, représenté sous forme de flux d'octets, |
et avec le nom spécifié
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [isValid(String content)](#isValid-java.lang.String-) | Effectue une vérification de surface pour déterminer si le contenu textuel spécifié est conforme à XML |
représente une image SVG
|
|  | [getType()](#getType--) | Renvoie ImageType.Svg |
|
|  | [getByteContent()](#getByteContent--) | Renvoie le contenu de cette image SVG sous forme de flux binaire |
|
|  | [getTextContent()](#getTextContent--) | Renvoie le contenu de cette image SVG sous forme de texte brut (au format XML) |
|
|  | [getXmlContent()](#getXmlContent--) | Renvoie le contenu de cette image SVG dans son format XML d'origine conforme |
forme textuelle
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Enregistre cette image SVG dans le fichier |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Enregistre cette image SVG vectorielle en image PNG raster |
|
|  | [dispose()](#dispose--) | Libère cette image raster, libérant son contenu et rendant la plupart des méthodes |
et propriétés non fonctionnelles
|
### SvgImage(String name, String content) {#SvgImage-java.lang.String-java.lang.String-}
```
public SvgImage(String name, String content)
```


Crée une nouvelle instance SvgImage à partir du contenu, représenté sous forme de chaîne habituelle,
et avec le nom spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | name | java.lang.String | Nom de l'image SVG. Ne peut pas être nul, vide ou contenir uniquement des espaces. |
|
|  | contenu | java.lang.String | Contenu sous forme de chaîne habituelle, qui contient un contenu XML valide conforme de l'image SVG. Ne peut pas être nul, vide ou contenir uniquement des espaces. Si ce n'est pas un contenu SVG, une exception sera levée. |
|

### SvgImage(String name, InputStream binaryContent) {#SvgImage-java.lang.String-java.io.InputStream-}
```
public SvgImage(String name, InputStream binaryContent)
```


Crée une nouvelle instance SvgImage à partir du contenu, représenté sous forme de flux d'octets,
et avec le nom spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | name | java.lang.String | Nom de l'image SVG. Ne peut pas être nul, vide ou contenir uniquement des espaces. |
|
|  | binaryContent | java.io.InputStream | Contenu sous forme de flux d'octets. La lecture commence à partir de la position d'origine. Ne peut pas être nul. Doit être lisible et recherchable. Si cette instance est libérée, ce flux sera également libéré. |
|

### isValid(String content) {#isValid-java.lang.String-}
```
public static boolean isValid(String content)
```


Effectue une vérification de surface pour déterminer si le contenu textuel spécifié est conforme à XML
représente une image SVG


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | contenu | java.lang.String | Contenu XML d'une image SVG sous forme de texte simple, pas un contenu encodé en base64 |
|

**Returns:**
booléen - True si la chaîne spécifiée peut être considérée comme un SVG valide à première vue, false si ce n'est certainement pas un SVG

### getType() {#getType--}
```
public ImageType getType()
```


Renvoie ImageType.Svg


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Renvoie le contenu de cette image SVG sous forme de flux binaire


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Renvoie le contenu de cette image SVG sous forme de texte brut (au format XML)


**Returns:**
java.lang.String -
### getXmlContent() {#getXmlContent--}
```
public final String getXmlContent()
```


Renvoie le contenu de cette image SVG dans son format XML d'origine conforme
forme textuelle


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Enregistre cette image SVG dans le fichier


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Chemin complet du fichier, qui sera créé (s'il n'existe pas) ou écrasé (s'il existe) avec le contenu de cette image SVG |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


Enregistre cette image SVG vectorielle en image PNG raster


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Flux de sortie, dans lequel le contenu de l'image PNG sera écrit. Ne peut pas être NULL et doit être accessible en écriture. |
|

### dispose() {#dispose--}
```
public void dispose()
```


Libère cette image raster, libérant son contenu et rendant la plupart des méthodes
et propriétés non fonctionnelles


