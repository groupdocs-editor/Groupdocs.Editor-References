---
title: "WordProcessingSaveOptions"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Permet de spécifier des options personnalisées pour générer et enregistrer des documents conformes à WordProcessing après leur édition"
type: docs
weight: 48
url: /fr/nodejs-java/com.groupdocs.editor.options/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class WordProcessingSaveOptions implements ISaveOptions
```

Permet de spécifier des options personnalisées pour la génération et l’enregistrement
Documents conformes à WordProcessing après leur édition


*** ** * ** ***

WordProcessingSaveOptions est appliqué dans les situations où il existe une instance de la classe EditableDocument, qui contient le contenu d’un document édité, et il est nécessaire d’enregistrer ce contenu dans un nouveau document au format WordProcessing.

<br />


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | Ce constructeur sans paramètres crée une nouvelle instance de WordProcessingSaveOptions avec le format de sortie DOCX (peut ensuite être modifié via |
OutputFormat
(propriété #getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats))
|
|  | [WordProcessingSaveOptions(WordProcessingFormats outputFormat)](#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-) | Crée une nouvelle instance de WordProcessingSaveOptions avec le |
format de sortie WordProcessing obligatoire, tandis que tous les autres paramètres sont
par défaut
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Permet d’activer ou de désactiver la pagination qui sera utilisée pour l’enregistrement du |
document.
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Permet d’activer ou de désactiver la pagination qui sera utilisée pour l’enregistrement du |
document.
|
|  | [getPassword()](#getPassword--) | Permet de spécifier, modifier, obtenir ou supprimer un mot de passe, qui sera |
utilisé pour encoder le document WordProcessing généré.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Permet de spécifier, modifier, obtenir ou supprimer un mot de passe, qui sera |
utilisé pour encoder le document WordProcessing généré.
|
|  | [getOutputFormat()](#getOutputFormat--) | Permet de spécifier un format WordProcessing, qui sera utilisé pour l’enregistrement |
du document
|
|  | [setOutputFormat(WordProcessingFormats value)](#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-) | Permet de spécifier un format WordProcessing, qui sera utilisé pour l’enregistrement |
du document
|
|  | [getLocale()](#getLocale--) | Permet de définir le remplacement de la locale par défaut (langue) pour le WordProcessing |
document, qui sera appliqué lors de sa création.
|
|  | [setLocale(Locale value)](#setLocale-java.util.Locale-) | Permet de définir le remplacement de la locale par défaut (langue) pour le WordProcessing |
document, qui sera appliqué lors de sa création.
|
|  | [getLocaleBi()](#getLocaleBi--) | Permet de définir le remplacement de la locale (langue) pour le document WordProcessing |
pour le texte RTL (de droite à gauche), qui sera appliqué pendant son
création.
|
|  | [setLocaleBi(Locale value)](#setLocaleBi-java.util.Locale-) | Permet de définir le remplacement de la locale (langue) pour le document WordProcessing |
pour le texte RTL (de droite à gauche), qui sera appliqué pendant son
création.
|
|  | [getLocaleFarEast()](#getLocaleFarEast--) | Permet de remplacer la locale (langue) pour le document WordProcessing |
pour le texte est-asiatique, qui sera appliqué lors de sa création.
|
|  | [setLocaleFarEast(Locale value)](#setLocaleFarEast-java.util.Locale-) | Permet de remplacer la locale (langue) pour le document WordProcessing |
pour le texte est-asiatique, qui sera appliqué lors de sa création.
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Active les mécanismes d’optimisation de la mémoire lors de la génération de documents à partir de |
HTML, ce qui dégrade les performances en contrepartie d’une réduction de l’utilisation de la mémoire.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Active les mécanismes d’optimisation de la mémoire lors de la génération de documents à partir de |
HTML, ce qui dégrade les performances en contrepartie d’une réduction de l’utilisation de la mémoire.
|
|  | [getProtection()](#getProtection--) | Permet de contrôler et d’appliquer les options de protection du document pour le |
document WordProcessing de tout format, qui prend en charge la
protection.
|
|  | [setProtection(WordProcessingProtection value)](#setProtection-com.groupdocs.editor.options.WordProcessingProtection-) | Permet de contrôler et d’appliquer les options de protection du document pour le |
document WordProcessing de tout format, qui prend en charge la
protection.
|
|  | [getFontEmbedding()](#getFontEmbedding--) | Responsable de l’intégration des ressources de police dans le WordProcessing de sortie |
document.
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | Responsable de l’intégration des ressources de police dans le WordProcessing de sortie |
document.
|
|  | [deepClone()](#deepClone--) | Crée et renvoie une copie complète de cette instance de |
classe WordProcessingSaveOptions
|
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


Ce constructeur sans paramètres crée une nouvelle instance de WordProcessingSaveOptions avec le format de sortie DOCX (peut ensuite être modifié via
OutputFormat
(propriété #getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats))


### WordProcessingSaveOptions(WordProcessingFormats outputFormat) {#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public WordProcessingSaveOptions(WordProcessingFormats outputFormat)
```


Crée une nouvelle instance de WordProcessingSaveOptions avec le
format de sortie WordProcessing obligatoire, tandis que tous les autres paramètres sont
par défaut


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | outputFormat | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) | Format de sortie obligatoire, dans lequel le document WordProcessing doit être enregistré |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Permet d’activer ou de désactiver la pagination qui sera utilisée pour l’enregistrement du
document. Si le document original a été ouvert et modifié en pagination
mode, cette option doit également être activée. Désactivée par défaut.


**Returns:**
booléen -
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Permet d’activer ou de désactiver la pagination qui sera utilisée pour l’enregistrement du
document. Si le document original a été ouvert et modifié en pagination
mode, cette option doit également être activée. Désactivée par défaut.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Permet de spécifier, modifier, obtenir ou supprimer un mot de passe, qui sera
utilisé pour encoder le document WordProcessing généré. Spécifiez NULL ou
chaîne vide pour supprimer (nettoyer) le mot de passe.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Permet de spécifier, modifier, obtenir ou supprimer un mot de passe, qui sera
utilisé pour encoder le document WordProcessing généré. Spécifiez NULL ou
chaîne vide pour supprimer (nettoyer) le mot de passe.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getOutputFormat() {#getOutputFormat--}
```
public final WordProcessingFormats getOutputFormat()
```


Permet de spécifier un format WordProcessing, qui sera utilisé pour l’enregistrement
du document


**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - 
### setOutputFormat(WordProcessingFormats value) {#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public final void setOutputFormat(WordProcessingFormats value)
```


Permet de spécifier un format WordProcessing, qui sera utilisé pour l’enregistrement
du document


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) |  |

### getLocale() {#getLocale--}
```
public final Locale getLocale()
```


Permet de définir le remplacement de la locale par défaut (langue) pour le WordProcessing
document, qui sera appliqué lors de sa création. Lorsque n'est pas
spécifié (valeur par défaut), MS Word (ou autre programme) détectera (ou
choisira) la locale du document selon ses propres paramètres ou d'autres
facteurs.


*** ** * ** ***

Cette option applique de force la locale spécifiée à l'ensemble du texte du document. Ne l'utilisez pas si le document contient différentes parties de texte rédigées dans différentes langues.

<br />



**Returns:**
java.util.Locale -
### setLocale(Locale value) {#setLocale-java.util.Locale-}
```
public final void setLocale(Locale value)
```


Permet de définir le remplacement de la locale par défaut (langue) pour le WordProcessing
document, qui sera appliqué lors de sa création. Lorsque n'est pas
spécifié (valeur par défaut), MS Word (ou autre programme) détectera (ou
choisira) la locale du document selon ses propres paramètres ou d'autres
facteurs.

*** ** * ** ***


Cette option applique de force la locale spécifiée à l'ensemble du texte dans
le document. Ne l'utilisez pas si le document contient différentes parties de
texte, qui sont rédigées dans différentes langues.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.Locale |  |

### getLocaleBi() {#getLocaleBi--}
```
public final Locale getLocaleBi()
```


Permet de définir le remplacement de la locale (langue) pour le document WordProcessing
pour le texte RTL (de droite à gauche), qui sera appliqué pendant son
création. Lorsque n'est pas spécifié (valeur par défaut), MS Word (ou autre
programme) détectera (ou choisira) la locale RTL du document selon ses
propres paramètres ou d'autres facteurs.

*** ** * ** ***


Cette option applique de force la locale spécifiée à l'ensemble du texte RTL
dans le document. Ne l'utilisez pas si le document contient différentes parties de
texte, qui sont rédigées dans différentes langues.


**Returns:**
java.util.Locale -
### setLocaleBi(Locale value) {#setLocaleBi-java.util.Locale-}
```
public final void setLocaleBi(Locale value)
```


Permet de définir le remplacement de la locale (langue) pour le document WordProcessing
pour le texte RTL (de droite à gauche), qui sera appliqué pendant son
création. Lorsque n'est pas spécifié (valeur par défaut), MS Word (ou autre
programme) détectera (ou choisira) la locale RTL du document selon ses
propres paramètres ou d'autres facteurs.

*** ** * ** ***


Cette option applique de force la locale spécifiée à l'ensemble du texte RTL
dans le document. Ne l'utilisez pas si le document contient différentes parties de
texte, qui sont rédigées dans différentes langues.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.Locale |  |

### getLocaleFarEast() {#getLocaleFarEast--}
```
public final Locale getLocaleFarEast()
```


Permet de remplacer la locale (langue) pour le document WordProcessing
pour le texte est-asiatique, qui sera appliqué lors de sa création. Lorsque
n'est pas spécifié (valeur par défaut), MS Word (ou autre programme) détectera
(ou choisira) la locale est-asiatique du document selon ses propres paramètres
ou d'autres facteurs.

*** ** * ** ***


Cette option applique de force la locale spécifiée à l'ensemble
Texte est-asiatique dans le document. Ne l'utilisez pas si le document contient
différentes parties de texte, qui sont écrites sur différents
langues.


**Returns:**
java.util.Locale -
### setLocaleFarEast(Locale value) {#setLocaleFarEast-java.util.Locale-}
```
public final void setLocaleFarEast(Locale value)
```


Permet de remplacer la locale (langue) pour le document WordProcessing
pour le texte est-asiatique, qui sera appliqué lors de sa création. Lorsque
n'est pas spécifié (valeur par défaut), MS Word (ou autre programme) détectera
(ou choisira) la locale est-asiatique du document selon ses propres paramètres
ou d'autres facteurs.

*** ** * ** ***


Cette option applique de force la locale spécifiée à l'ensemble
Texte est-asiatique dans le document. Ne l'utilisez pas si le document contient
différentes parties de texte, qui sont écrites sur différents
langues.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.Locale |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Active les mécanismes d’optimisation de la mémoire lors de la génération de documents à partir de
HTML, ce qui dégrade les performances en contrepartie d’une réduction de l’utilisation de la mémoire.
Définir cette option sur true peut réduire considérablement la consommation de mémoire
lors de la génération de gros documents au prix d'un temps d'enregistrement plus lent.
La valeur par défaut est false (l'optimisation de la mémoire est désactivée afin d'améliorer
les performances).


**Returns:**
booléen -
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Active les mécanismes d’optimisation de la mémoire lors de la génération de documents à partir de
HTML, ce qui dégrade les performances en contrepartie d’une réduction de l’utilisation de la mémoire.
Définir cette option sur true peut réduire considérablement la consommation de mémoire
lors de la génération de gros documents au prix d'un temps d'enregistrement plus lent.
La valeur par défaut est false (l'optimisation de la mémoire est désactivée afin d'améliorer
les performances).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getProtection() {#getProtection--}
```
public final WordProcessingProtection getProtection()
```


Permet de contrôler et d’appliquer les options de protection du document pour le
document WordProcessing de tout format, qui prend en charge la
protection. Par défaut, c'est NULL - la protection du document ne sera pas utilisée.


**Returns:**
[WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) - 
### setProtection(WordProcessingProtection value) {#setProtection-com.groupdocs.editor.options.WordProcessingProtection-}
```
public final void setProtection(WordProcessingProtection value)
```


Permet de contrôler et d’appliquer les options de protection du document pour le
document WordProcessing de tout format, qui prend en charge la
protection. Par défaut, c'est NULL - la protection du document ne sera pas utilisée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final int getFontEmbedding()
```


Responsable de l’intégration des ressources de police dans le WordProcessing de sortie
document. Par défaut, aucune police n'est incorporée (NotEmbed).


**Returns:**
int -
### setFontEmbedding(int value) {#setFontEmbedding-int-}
```
public final void setFontEmbedding(int value)
```


Responsable de l’intégration des ressources de police dans le WordProcessing de sortie
document. Par défaut, aucune police n'est incorporée (NotEmbed).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### deepClone() {#deepClone--}
```
public final WordProcessingSaveOptions deepClone()
```


Crée et renvoie une copie complète de cette instance de
classe WordProcessingSaveOptions


**Returns:**
[WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) - New WordProcessingSaveOptions instance

