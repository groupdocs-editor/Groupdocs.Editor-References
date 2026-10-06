---
title: "TtcFont"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Représente une police dans le format TTC TrueType Collection"
type: docs
weight: 14
url: /fr/java/com.groupdocs.editor.htmlcss.resources.fonts/ttcfont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class TtcFont extends FontResourceBase
```

Représente une police au format TTC (TrueType Collection).


Voir plus : https://docs.fileformat.com/font/ttc/

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [TtcFont(String name, String contentInBase64)](#TtcFont-java.lang.String-java.lang.String-) | Crée une nouvelle classe TtcFont à partir du contenu, représenté en base64 |
chaîne, et avec le nom spécifié
|
|  | [TtcFont(String name, InputStream binaryContent)](#TtcFont-java.lang.String-java.io.InputStream-) | Crée une nouvelle classe TtcFont à partir du contenu, représenté sous forme de flux d'octets, et |
avec le nom spécifié
|
## Champs

| Champ | Description |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Taille de l'en-tête TTC (en octets), requise pour sa validation |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Vérifie si le flux spécifié est une police TTC valide |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Vérifie si la chaîne encodée en base64 spécifiée est une police TTC valide |
|
|  | [getType()](#getType--) | Renvoie FontType.Ttc |
|
|  | [getHeaderVersion()](#getHeaderVersion--) | Version de l'en-tête TTC, peut être "1" ou "2" |
|
|  | [getFontsNumber()](#getFontsNumber--) | Nombre de polices dans ce TTC |
|
|  | [getHasDsigTable()](#getHasDsigTable--) | Indique si ce TTC possède une table DSIG. |
|
### TtcFont(String name, String contentInBase64) {#TtcFont-java.lang.String-java.lang.String-}
```
public TtcFont(String name, String contentInBase64)
```


Crée une nouvelle classe TtcFont à partir du contenu, représenté en base64
chaîne, et avec le nom spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | name | java.lang.String | Nom de la police TTC. Ne peut pas être nul, vide ou contenir uniquement des espaces. |
|
|  | contentInBase64 | java.lang.String | Contenu sous forme de chaîne encodée en base64. Ne peut pas être nul, vide ou contenir uniquement des espaces. Si ce n'est pas un contenu TTC, une exception sera levée. |
|

### TtcFont(String name, InputStream binaryContent) {#TtcFont-java.lang.String-java.io.InputStream-}
```
public TtcFont(String name, InputStream binaryContent)
```


Crée une nouvelle classe TtcFont à partir du contenu, représenté sous forme de flux d'octets, et
avec le nom spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | name | java.lang.String | Nom de la police TTC. Ne peut pas être nul, vide ou contenir uniquement des espaces. |
|
|  | binaryContent | java.io.InputStream | Contenu sous forme de flux d'octets. La lecture commence à partir de la position d'origine. Ne peut pas être nul. Doit être lisible et recherchable. Si cette instance est libérée, ce flux sera également libéré. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Taille de l'en-tête TTC (en octets), requise pour sa validation


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Vérifie si le flux spécifié est une police TTC valide


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flux d'octets, qui contient probablement une ressource TTC |
|

**Returns:**
booléen - Vrai si le flux spécifié contient une police TTC valide, faux sinon

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Vérifie si la chaîne encodée en base64 spécifiée est une police TTC valide


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Contenu de la police TTC supposée sous forme de chaîne encodée en base64 |
|

**Returns:**
booléen - Vrai si la chaîne spécifiée contient une police TTC valide, faux sinon

### getType() {#getType--}
```
public FontType getType()
```


Renvoie FontType.Ttc


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
### getHeaderVersion() {#getHeaderVersion--}
```
public byte getHeaderVersion()
```


Version de l'en-tête TTC, peut être "1" ou "2"


**Returns:**
octet
### getFontsNumber() {#getFontsNumber--}
```
public long getFontsNumber()
```


Nombre de polices dans ce TTC


**Returns:**
long
### getHasDsigTable() {#getHasDsigTable--}
```
public boolean getHasDsigTable()
```


Indique si ce TTC possède une table DSIG. La table DSIG peut être présente
uniquement si le TTC a une version d'en-tête 2.0.


**Returns:**
boolean
