---
title: "XpsSaveOptions"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Permet de spécifier des options personnalisées pour générer et enregistrer des documents XPS XML Paper Specifications"
type: docs
weight: 54
url: /fr/nodejs-java/com.groupdocs.editor.options/xpssaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class XpsSaveOptions implements ISaveOptions
```

Permet de spécifier des options personnalisées pour la génération et l’enregistrement de documents XPS (XML Paper Specifications).

<br />

*** ** * ** ***

Un fichier XPS représente des fichiers de mise en page basés sur les XML Paper Specifications créées par Microsoft. Il a été développé comme remplacement du format de fichier EMF et est similaire au format de fichier PDF, mais utilise du XML pour la mise en page, l'apparence et les informations d'impression d'un document.

<br />


## Constructeurs

| Constructeur | Description |
| --- | --- |
| [XpsSaveOptions()](#XpsSaveOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getFontEmbedding()](#getFontEmbedding--) | Responsable de l'incorporation des ressources de police dans le document Xps résultant, qui sont utilisées dans le document original. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Active les mécanismes d'optimisation de la mémoire lors de la génération de documents à partir de HTML, ce qui dégrade les performances en contrepartie d'une réduction de l'utilisation de la mémoire. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Active les mécanismes d'optimisation de la mémoire lors de la génération de documents à partir de HTML, ce qui dégrade les performances en contrepartie d'une réduction de l'utilisation de la mémoire. |
|
### XpsSaveOptions() {#XpsSaveOptions--}
```
public XpsSaveOptions()
```


### getFontEmbedding() {#getFontEmbedding--}
```
public final byte getFontEmbedding()
```


Responsable de l'incorporation des ressources de police dans le document Xps résultant, qui sont utilisées dans le document original.
Par défaut, aucune police n'est incorporée (NotEmbed).


**Returns:**
byte
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

