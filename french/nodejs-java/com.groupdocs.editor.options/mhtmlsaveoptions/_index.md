---
title: "MhtmlSaveOptions"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Permet de spécifier des options personnalisées pour générer et enregistrer l'encapsulation MIME MHTML de documents HTML agrégés documents"
type: docs
weight: 26
url: /fr/nodejs-java/com.groupdocs.editor.options/mhtmlsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MhtmlSaveOptions implements ISaveOptions
```

Permet de spécifier des options personnalisées pour générer et enregistrer les documents MHTML (encapsulation MIME de documents HTML agrégés)

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MhtmlSaveOptions()](#MhtmlSaveOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getExportCidUrls()](#getExportCidUrls--) | Spécifie s'il faut utiliser des URL CID (Content-ID) pour référencer les ressources (images, polices, CSS) incluses dans les documents MHTML. |
|
|  | [setExportCidUrls(boolean value)](#setExportCidUrls-boolean-) | Spécifie s'il faut utiliser des URL CID (Content-ID) pour référencer les ressources (images, polices, CSS) incluses dans les documents MHTML. |
|
|  | [getExportDocumentProperties()](#getExportDocumentProperties--) | Spécifie s'il faut exporter les propriétés de document intégrées et personnalisées vers MHTML. |
|
|  | [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | Spécifie s'il faut exporter les propriétés de document intégrées et personnalisées vers MHTML. |
|
|  | [getExportLanguageInformation()](#getExportLanguageInformation--) | Spécifie si les informations de langue sont exportées vers MHTML. |
|
|  | [setExportLanguageInformation(boolean value)](#setExportLanguageInformation-boolean-) | Spécifie si les informations de langue sont exportées vers MHTML. |
|
### MhtmlSaveOptions() {#MhtmlSaveOptions--}
```
public MhtmlSaveOptions()
```


### getExportCidUrls() {#getExportCidUrls--}
```
public final boolean getExportCidUrls()
```


Spécifie s'il faut utiliser des URL CID (Content-ID) pour référencer les ressources (images, polices, CSS) incluses dans les documents MHTML. La valeur par défaut est
false
.

<br />

*** ** * ** ***


Par défaut, les ressources dans les documents MHTML sont référencées par le nom de fichier (par exemple, "image.png"), qui sont comparés aux en-têtes "Content-Location" des parties MIME. Cette option active une méthode alternative, où les références aux fichiers de ressources sont écrites sous forme d'URL CID (Content-ID) (par exemple, "cid:image.png") et sont comparées aux en-têtes "Content-ID".


En théorie, il ne devrait y avoir aucune différence entre les deux méthodes de référencement et chacune d'elles devrait fonctionner correctement dans n'importe quel navigateur ou agent de messagerie. En pratique, cependant, certains agents ne parviennent pas à récupérer les ressources par nom de fichier. Si votre navigateur ou agent de messagerie refuse de charger les ressources incluses dans un document MTHML (n'affiche pas les images ou ne charge pas les styles CSS), essayez d'exporter le document avec des URL CID.

<br />



**Returns:**
booléen
### setExportCidUrls(boolean value) {#setExportCidUrls-boolean-}
```
public final void setExportCidUrls(boolean value)
```


Spécifie s'il faut utiliser des URL CID (Content-ID) pour référencer les ressources (images, polices, CSS) incluses dans les documents MHTML. La valeur par défaut est
false
.

<br />

*** ** * ** ***


Par défaut, les ressources dans les documents MHTML sont référencées par le nom de fichier (par exemple, "image.png"), qui sont comparés aux en-têtes "Content-Location" des parties MIME. Cette option active une méthode alternative, où les références aux fichiers de ressources sont écrites sous forme d'URL CID (Content-ID) (par exemple, "cid:image.png") et sont comparées aux en-têtes "Content-ID".


En théorie, il ne devrait y avoir aucune différence entre les deux méthodes de référencement et chacune d'elles devrait fonctionner correctement dans n'importe quel navigateur ou agent de messagerie. En pratique, cependant, certains agents ne parviennent pas à récupérer les ressources par nom de fichier. Si votre navigateur ou agent de messagerie refuse de charger les ressources incluses dans un document MTHML (n'affiche pas les images ou ne charge pas les styles CSS), essayez d'exporter le document avec des URL CID.

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getExportDocumentProperties() {#getExportDocumentProperties--}
```
public final boolean getExportDocumentProperties()
```


Spécifie s'il faut exporter les propriétés de document intégrées et personnalisées vers MHTML. La valeur par défaut est
false
.


**Returns:**
booléen
### setExportDocumentProperties(boolean value) {#setExportDocumentProperties-boolean-}
```
public final void setExportDocumentProperties(boolean value)
```


Spécifie s'il faut exporter les propriétés de document intégrées et personnalisées vers MHTML. La valeur par défaut est
false
.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getExportLanguageInformation() {#getExportLanguageInformation--}
```
public final boolean getExportLanguageInformation()
```


Spécifie si les informations de langue sont exportées vers MHTML. La valeur par défaut est
false
.

<br />

*** ** * ** ***

Lorsque cette propriété est définie sur  true , le GroupDocs.Editor émet l'attribut HTML  lang  sur les éléments du document qui spécifient la langue. Cela peut être nécessaire pour préserver la sémantique liée à la langue.

<br />



**Returns:**
booléen
### setExportLanguageInformation(boolean value) {#setExportLanguageInformation-boolean-}
```
public final void setExportLanguageInformation(boolean value)
```


Spécifie si les informations de langue sont exportées vers MHTML. La valeur par défaut est
false
.

<br />

*** ** * ** ***

Lorsque cette propriété est définie sur  true , le GroupDocs.Editor émet l'attribut HTML  lang  sur les éléments du document qui spécifient la langue. Cela peut être nécessaire pour préserver la sémantique liée à la langue.

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

