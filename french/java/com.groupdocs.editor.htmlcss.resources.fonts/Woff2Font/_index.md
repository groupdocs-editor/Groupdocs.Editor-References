---
title: "Woff2Font"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Représente une police dans le format WOFF2 Web Open Font Format"
type: docs
weight: 16
url: /fr/java/com.groupdocs.editor.htmlcss.resources.fonts/woff2font/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class Woff2Font extends FontResourceBase
```

Représente une police au format WOFF2 (Web Open Font Format).

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [Woff2Font(String name, String contentInBase64)](#Woff2Font-java.lang.String-java.lang.String-) | Crée une nouvelle classe Woff2Font à partir du contenu, représenté en base64 |
chaîne, et avec le nom spécifié
|
|  | [Woff2Font(String name, InputStream binaryContent)](#Woff2Font-java.lang.String-java.io.InputStream-) | Crée une nouvelle classe Woff2Font à partir du contenu, représenté sous forme de flux d'octets, et |
avec le nom spécifié
|
## Champs

| Champ | Description |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Taille de l'en-tête WOFF2 (en octets), requise pour sa validation |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Vérifie si le flux spécifié est une police WOFF2 valide |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Vérifie si la chaîne encodée en base64 spécifiée est une police WOFF2 valide |
|
|  | [getType()](#getType--) | Renvoie FontType.Woff2 |
|
### Woff2Font(String name, String contentInBase64) {#Woff2Font-java.lang.String-java.lang.String-}
```
public Woff2Font(String name, String contentInBase64)
```


Crée une nouvelle classe Woff2Font à partir du contenu, représenté en base64
chaîne, et avec le nom spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | name | java.lang.String | Nom de la police WOFF2. Ne peut pas être nul, vide ou composé d'espaces. |
|
|  | contentInBase64 | java.lang.String | Contenu sous forme de chaîne encodée en base64. Ne peut pas être nul, vide ou composé d'espaces. Si ce n'est pas un contenu WOFF2, une exception sera levée. |
|

### Woff2Font(String name, InputStream binaryContent) {#Woff2Font-java.lang.String-java.io.InputStream-}
```
public Woff2Font(String name, InputStream binaryContent)
```


Crée une nouvelle classe Woff2Font à partir du contenu, représenté sous forme de flux d'octets, et
avec le nom spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | name | java.lang.String | Nom de la police WOFF2. Ne peut pas être nul, vide ou composé d'espaces. |
|
|  | binaryContent | java.io.InputStream | Contenu sous forme de flux d'octets. La lecture commence à la position d'origine. Ne peut pas être nul. Doit être lisible et déplaçable. Si cette instance est libérée, ce flux sera également libéré. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Taille de l'en-tête WOFF2 (en octets), requise pour sa validation


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Vérifie si le flux spécifié est une police WOFF2 valide


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flux d'octets, qui contient probablement une ressource WOFF2 |
|

**Returns:**
booléen - Vrai si le flux spécifié contient une police WOFF2 valide, faux sinon

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Vérifie si la chaîne encodée en base64 spécifiée est une police WOFF2 valide


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Contenu de la police WOFF2 supposée sous forme de chaîne encodée en base64 |
|

**Returns:**
booléen - Vrai si la chaîne spécifiée contient une police WOFF2 valide, faux sinon

### getType() {#getType--}
```
public FontType getType()
```


Renvoie FontType.Woff2


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
