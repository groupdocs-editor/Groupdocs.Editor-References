---
title: "MetaImageBase"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Classe abstraite de base pour les formats d'images WMF et EMF"
type: docs
weight: 11
url: /fr/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)
```
public abstract class MetaImageBase extends VectorImageResourceBase
```

Classe abstraite de base pour les formats d'images WMF et EMF

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [MetaImageBase(String name, String contentInBase64, boolean isWmf)](#MetaImageBase-java.lang.String-java.lang.String-boolean-) | Constructeur commun, qui prépare la création d'une instance WMF ou EMF à partir de |
chaîne encodée en base64
|
|  | [MetaImageBase(String name, InputStream binaryContent, boolean isWmf)](#MetaImageBase-java.lang.String-java.io.InputStream-boolean-) | Constructeur commun, qui prépare la création d'une instance WMF ou EMF à partir de |
flux d'octets
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [isValidWmf(InputStream binaryContent)](#isValidWmf-java.io.InputStream-) | Détermine si le flux d'octets spécifié contient une image WMF valide |
|
|  | [isValidWmf(String contentInBase64)](#isValidWmf-java.lang.String-) | Détermine si la chaîne spécifiée contient une image WMF valide, qui est |
encodée en base64
|
|  | [isValidEmf(InputStream binaryContent)](#isValidEmf-java.io.InputStream-) | Détermine si le flux d'octets spécifié contient une image EMF valide |
|
|  | [isValidEmf(String contentInBase64)](#isValidEmf-java.lang.String-) | Détermine si la chaîne spécifiée contient une image EMF valide, qui est |
encodée en base64
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | Dans le type implémentant, il faut enregistrer la méta-image vectorielle actuelle dans le |
format SVG vectoriel dans le flux d'octets spécifié
|
### MetaImageBase(String name, String contentInBase64, boolean isWmf) {#MetaImageBase-java.lang.String-java.lang.String-boolean-}
```
public MetaImageBase(String name, String contentInBase64, boolean isWmf)
```


Constructeur commun, qui prépare la création d'une instance WMF ou EMF à partir de
chaîne encodée en base64


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | name | java.lang.String | Nom obligatoire |
|
|  | contentInBase64 | java.lang.String | Contenu sous forme de chaîne base64. Ne doit pas être NULL ou vide. |
|
|  | isWmf | booléen | true pour WMF, false pour EMF |
|

### MetaImageBase(String name, InputStream binaryContent, boolean isWmf) {#MetaImageBase-java.lang.String-java.io.InputStream-boolean-}
```
public MetaImageBase(String name, InputStream binaryContent, boolean isWmf)
```


Constructeur commun, qui prépare la création d'une instance WMF ou EMF à partir de
flux d'octets


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | name | java.lang.String | Nom obligatoire |
|
|  | binaryContent | java.io.InputStream | Contenu sous forme de flux d'octets. Doit être valide. |
|
|  | isWmf | booléen | true pour WMF, false pour EMF |
|

### isValidWmf(InputStream binaryContent) {#isValidWmf-java.io.InputStream-}
```
public static boolean isValidWmf(InputStream binaryContent)
```


Détermine si le flux d'octets spécifié contient une image WMF valide


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flux d'octets d'entrée. Doit être valide. |
|

**Returns:**
booléen - Retourne 'true' si valide et 'false' si invalide

### isValidWmf(String contentInBase64) {#isValidWmf-java.lang.String-}
```
public static boolean isValidWmf(String contentInBase64)
```


Détermine si la chaîne spécifiée contient une image WMF valide, qui est
encodée en base64


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Chaîne, supposée contenir une image WMF encodée en base64 |
|

**Returns:**
booléen - Retourne 'true' si valide et 'false' si invalide

### isValidEmf(InputStream binaryContent) {#isValidEmf-java.io.InputStream-}
```
public static boolean isValidEmf(InputStream binaryContent)
```


Détermine si le flux d'octets spécifié contient une image EMF valide


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flux d'octets d'entrée. Doit être valide. |
|

**Returns:**
booléen - Retourne 'true' si valide et 'false' si invalide

### isValidEmf(String contentInBase64) {#isValidEmf-java.lang.String-}
```
public static boolean isValidEmf(String contentInBase64)
```


Détermine si la chaîne spécifiée contient une image EMF valide, qui est
encodée en base64


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Chaîne, supposée contenir une image EMF encodée en base64 |
|

**Returns:**
booléen - Retourne 'true' si valide et 'false' si invalide

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public abstract void saveToSvg(OutputStream outputSvgContent)
```


Dans le type implémentant, il faut enregistrer la méta-image vectorielle actuelle dans le
format SVG vectoriel dans le flux d'octets spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | Flux d'octets, dans lequel la version SVG de cette méta-image vectorielle sera stockée. Ne doit pas être NULL et doit prendre en charge l'écriture. |
|

