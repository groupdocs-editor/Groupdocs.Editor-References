---
title: "PdfSaveOptions"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Permet de spécifier des options personnalisées pour la génération et l'enregistrement de documents PDF Portable Document Format"
type: docs
weight: 31
url: /fr/nodejs-java/com.groupdocs.editor.options/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PdfSaveOptions implements ISaveOptions
```

Permet de spécifier des options personnalisées pour la génération et l'enregistrement de PDF (Portable
Document Format) documents

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getPassword()](#getPassword--) | Mot de passe, qui sera appliqué au document PDF généré en tant que mot de passe utilisateur, requis pour l'ouverture. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Mot de passe, qui sera appliqué au document PDF généré en tant que mot de passe utilisateur, requis pour l'ouverture. |
|
|  | [getCompliance()](#getCompliance--) | Spécifie le niveau de conformité aux normes PDF pour les documents de sortie. |
|
|  | [setCompliance(int value)](#setCompliance-int-) | Spécifie le niveau de conformité aux normes PDF pour les documents de sortie. |
|
|  | [getFontEmbedding()](#getFontEmbedding--) | Responsable de l'intégration des ressources de police dans le document PDF résultant, qui sont utilisées dans le document original. |
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | Responsable de l'intégration des ressources de police dans le document PDF résultant, qui sont utilisées dans le document original. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Active les mécanismes d'optimisation de la mémoire lors de la génération de documents à partir de HTML, ce qui dégrade les performances en contrepartie d'une réduction de l'utilisation de la mémoire. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Active les mécanismes d'optimisation de la mémoire lors de la génération de documents à partir de HTML, ce qui dégrade les performances en contrepartie d'une réduction de l'utilisation de la mémoire. |
|
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Mot de passe, qui sera appliqué au document PDF généré en tant que mot de passe utilisateur, requis pour l'ouverture.
Si NULL ou vide, aucun mot de passe ne sera appliqué au document. Sinon, le document sera chiffré avec RC4 (longueur de clé de 128 bits).
Par défaut, il est NULL \\u2014 le mot de passe n'est pas appliqué.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Mot de passe, qui sera appliqué au document PDF généré en tant que mot de passe utilisateur, requis pour l'ouverture.
Si NULL ou vide, aucun mot de passe ne sera appliqué au document. Sinon, le document sera chiffré avec RC4 (longueur de clé de 128 bits).
Par défaut, il est NULL \\u2014 le mot de passe n'est pas appliqué.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```


Spécifie le niveau de conformité aux normes PDF pour les documents de sortie. La valeur par défaut est PdfCompliance.Pdf17.


**Returns:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```


Spécifie le niveau de conformité aux normes PDF pour les documents de sortie. La valeur par défaut est PdfCompliance.Pdf17.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final int getFontEmbedding()
```


Responsable de l'intégration des ressources de polices dans le document PDF résultant, qui sont utilisées dans le document original. Par défaut, aucune police n'est intégrée (NotEmbed).


**Returns:**
int
### setFontEmbedding(int value) {#setFontEmbedding-int-}
```
public final void setFontEmbedding(int value)
```


Responsable de l'intégration des ressources de polices dans le document PDF résultant, qui sont utilisées dans le document original. Par défaut, aucune police n'est intégrée (NotEmbed).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Active les mécanismes d'optimisation de la mémoire lors de la génération de documents à partir de HTML, ce qui dégrade les performances en contrepartie d'une réduction de l'utilisation de la mémoire.
Activer cette option (true) peut réduire considérablement la consommation de mémoire lors de la génération de gros documents au prix d'un temps d'enregistrement plus lent.
La valeur par défaut est false (l'optimisation de la mémoire est désactivée pour de meilleures performances).


**Returns:**
booléen
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Active les mécanismes d'optimisation de la mémoire lors de la génération de documents à partir de HTML, ce qui dégrade les performances en contrepartie d'une réduction de l'utilisation de la mémoire.
Activer cette option (true) peut réduire considérablement la consommation de mémoire lors de la génération de gros documents au prix d'un temps d'enregistrement plus lent.
La valeur par défaut est false (l'optimisation de la mémoire est désactivée pour de meilleures performances).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

