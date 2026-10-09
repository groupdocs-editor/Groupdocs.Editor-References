---
title: "PdfCompliance"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Spécifie le niveau de conformité aux normes PDF"
type: docs
weight: 28
url: /fr/nodejs-java/com.groupdocs.editor.options/pdfcompliance/
---
**Inheritance:**
java.lang.Object
```
public final class PdfCompliance
```

Spécifie le niveau de conformité aux normes PDF

## Champs

| Champ | Description |
| --- | --- |
|  | [Pdf17](#Pdf17) | Norme PDF 1.7 (ISO 32000-1) |
|
|  | [Pdf20](#Pdf20) | Norme PDF 2.0 (ISO 32000-2) |
|
|  | [PdfA1a](#PdfA1a) | Norme PDF/A-1a. |
|
|  | [PdfA1b](#PdfA1b) | PDF/A-1b (ISO 19005-1). |
|
|  | [PdfA2a](#PdfA2a) | Norme PDF/A-2a (ISO 19005-2). |
|
|  | [PdfA2u](#PdfA2u) | Norme PDF/A-2u (ISO 19005-2). |
|
|  | [PdfUa1](#PdfUa1) | Norme PDF/UA-1 (ISO 14289-1). |
|
### Pdf17 {#Pdf17}
```
public static final int Pdf17
```


Norme PDF 1.7 (ISO 32000-1)


### Pdf20 {#Pdf20}
```
public static final int Pdf20
```


Norme PDF 2.0 (ISO 32000-2)


### PdfA1a {#PdfA1a}
```
public static final int PdfA1a
```


Norme PDF/A-1a. Ce niveau inclut toutes les exigences de PDF/A-1b et requiert en outre que la structure du document soit incluse
(également connu sous le nom de « tagged »), dans le but de garantir que le contenu du document puisse être recherché et réutilisé.

<br />

*** ** * ** ***

Notez que l’exportation de la structure du document augmente considérablement la consommation de mémoire, en particulier pour les gros documents.

<br />



### PdfA1b {#PdfA1b}
```
public static final int PdfA1b
```


PDF/A-1b (ISO 19005-1). PDF/A-1b a pour objectif d’assurer une reproduction fiable de l’apparence visuelle du document.


### PdfA2a {#PdfA2a}
```
public static final int PdfA2a
```


Norme PDF/A-2a (ISO 19005-2). Ce niveau inclut toutes les exigences de PDF/A-2u et requiert en outre que la structure du document soit incluse (également connu sous le nom de « tagged »), dans le but de garantir que le contenu du document puisse être recherché et réutilisé.

<br />

*** ** * ** ***

Notez que l’exportation de la structure du document augmente considérablement la consommation de mémoire, en particulier pour les gros documents.

<br />



### PdfA2u {#PdfA2u}
```
public static final int PdfA2u
```


Norme PDF/A-2u (ISO 19005-2). PDF/A-2u a pour objectif de préserver l’apparence visuelle statique du document dans le temps, indépendamment des outils et systèmes utilisés pour créer, stocker ou rendre les fichiers. De plus, tout texte contenu dans le document peut être extrait de manière fiable sous forme d’une série de points de code Unicode.


### PdfUa1 {#PdfUa1}
```
public static final int PdfUa1
```


Norme PDF/UA-1 (ISO 14289-1). Le principal objectif de PDF/UA est de définir comment représenter les documents électroniques au format PDF de manière à rendre le fichier accessible.


