---
title: "OtfFont"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Représente une police dans le format OTF Open Type Format"
type: docs
weight: 13
url: /fr/java/com.groupdocs.editor.htmlcss.resources.fonts/otffont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class OtfFont extends FontResourceBase
```

Représente une police au format OTF (Open Type Format).

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [OtfFont(String name, String contentInBase64)](#OtfFont-java.lang.String-java.lang.String-) | Crée une nouvelle classe OtfFont à partir du contenu, représenté en base64 |
chaîne, et avec le nom spécifié
|
|  | [OtfFont(String name, InputStream binaryContent)](#OtfFont-java.lang.String-java.io.InputStream-) | Crée une nouvelle classe OtfFont à partir du contenu, représenté sous forme de flux d'octets, et |
avec le nom spécifié
|
## Champs

| Champ | Description |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Taille de l'en-tête OTF (en octets), requise pour sa validation |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Vérifie si le flux spécifié est une police OTF valide |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Vérifie si la chaîne encodée en base64 spécifiée est une police OTF valide |
|
|  | [getType()](#getType--) | Renvoie |
FontType.Otf
([FontType.getOtf](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype#getOtf))
|
### OtfFont(String name, String contentInBase64) {#OtfFont-java.lang.String-java.lang.String-}
```
public OtfFont(String name, String contentInBase64)
```


Crée une nouvelle classe OtfFont à partir du contenu, représenté en base64
chaîne, et avec le nom spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | name | java.lang.String | Nom de la police OTF. Ne peut pas être nul, vide ou contenir uniquement des espaces. |
|
|  | contentInBase64 | java.lang.String | Contenu sous forme de chaîne encodée en base64. Ne peut pas être nul, vide ou contenir uniquement des espaces. Si ce n'est pas un contenu OTF, une exception sera levée. |
|

### OtfFont(String name, InputStream binaryContent) {#OtfFont-java.lang.String-java.io.InputStream-}
```
public OtfFont(String name, InputStream binaryContent)
```


Crée une nouvelle classe OtfFont à partir du contenu, représenté sous forme de flux d'octets, et
avec le nom spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | name | java.lang.String | Nom de la police OTF. Ne peut pas être nul, vide ou contenir uniquement des espaces. |
|
|  | binaryContent | java.io.InputStream | Contenu sous forme de flux d'octets. La lecture commence à partir de la position d'origine. Ne peut pas être nul. Doit être lisible et recherchable. Si cette instance est libérée, ce flux sera également libéré. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Taille de l'en-tête OTF (en octets), requise pour sa validation


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Vérifie si le flux spécifié est une police OTF valide


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flux d'octets, qui contient probablement une ressource OTF |
|

**Returns:**
boolean - Vrai si le flux spécifié contient une police OTF valide, faux sinon

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Vérifie si la chaîne encodée en base64 spécifiée est une police OTF valide


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Contenu de la police OTF supposée sous forme de chaîne encodée en base64 |
|

**Returns:**
boolean - Vrai si la chaîne spécifiée contient une police OTF valide, faux sinon

### getType() {#getType--}
```
public FontType getType()
```


Renvoie
FontType.Otf
([FontType.getOtf](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype#getOtf))


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
