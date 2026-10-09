---
title: "PageRange"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Encapsule une plage de pages qui peut avoir des limites ouvertes ou fermées."
type: docs
weight: 27
url: /fr/nodejs-java/com.groupdocs.editor.options/pagerange/
---
**Inheritance:**
java.lang.Object
```
public class PageRange
```

Encapsule une plage de pages, qui peut avoir des limites ouvertes ou fermées. Par défaut, elle est "entièrement ouverte" – elle inclut toutes les pages existantes. La numérotation des pages commence à 1, pas à 0.

<br />

*** ** * ** ***

Structure immuable qui encapsule une plage de pages, qui n'est liée à aucun document spécifique, et peut représenter une plage de pages pour n'importe quel document.

<br />


## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PageRange()](#PageRange--) |  |
## Champs

| Champ | Description |
| --- | --- |
|  | [AllPages](#AllPages) | Représente toutes les pages existantes d'un document. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getStartNumber()](#getStartNumber--) | Numéro de page de début inclusif, à partir duquel cette plage de pages commence. |
|
|  | [getEndNumber()](#getEndNumber--) | Numéro de page de fin exclusif, jusqu'auquel cette plage de pages continue et s'arrête de manière exclusive. |
|
|  | [getCount()](#getCount--) | Nombre de pages dans la plage. |
|
|  | [isDefault()](#isDefault--) | Indique si cette instance représente une plage de pages par défaut "entièrement ouverte" c.-à-d. |
|
|  | [equals(PageRange other)](#equals-com.groupdocs.editor.options.PageRange-) | Détecte si cette instance de PageRange est égale à celle spécifiée |
|
|  | [fromBeginningWithCount(int pageCount)](#fromBeginningWithCount-int-) | Crée une plage de pages qui commence à la première page et possède le nombre de pages spécifié |
|
|  | [fromStartPageTillEnd(int startPageNumber)](#fromStartPageTillEnd-int-) | Crée une plage de pages qui commence au numéro de page spécifié et se poursuit jusqu'à la fin du document |
|
|  | [fromStartPageWithCount(int startPageNumber, int pageCount)](#fromStartPageWithCount-int-int-) | Crée une plage de pages qui commence au numéro de page spécifié et possède le nombre de pages indiqué, ou un nombre illimité de pages (jusqu'à la fin) |
|
|  | [fromStartPageTillEndPage(int startPageNumber, int endPageNumber)](#fromStartPageTillEndPage-int-int-) | Crée une plage de pages qui commence au numéro de page spécifié (inclusivement) et se poursuit jusqu'au numéro de page spécifié (exclusivement) |
|
### PageRange() {#PageRange--}
```
public PageRange()
```


### AllPages {#AllPages}
```
public static final PageRange AllPages
```


Représente toutes les pages existantes d'un document. Valeur par défaut.


### getStartNumber() {#getStartNumber--}
```
public final int getStartNumber()
```


Numéro de page de début inclusif, à partir duquel cette plage de pages commence. Si 1 - la plage de pages commence à la première page d'un document


**Returns:**
int
### getEndNumber() {#getEndNumber--}
```
public final int getEndNumber()
```


Numéro de page de fin exclusif, jusqu'auquel cette plage de pages continue et s'arrête de manière exclusive. Si 0 - la plage de pages s'étend jusqu'à la fin du document


**Returns:**
int
### getCount() {#getCount--}
```
public final int getCount()
```


Nombre de pages dans la plage. Si 0 - la plage de pages s'étend jusqu'à la fin du document quel que soit le nombre de pages qu'elle contient


**Returns:**
int
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Indique si cette instance représente une plage de pages par défaut "entièrement ouverte" c.-à-d. qu'elle comprend toutes les pages d'un document


**Returns:**
booléen
### equals(PageRange other) {#equals-com.groupdocs.editor.options.PageRange-}
```
public final boolean equals(PageRange other)
```


Détecte si cette instance de PageRange est égale à celle spécifiée


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [PageRange](../../com.groupdocs.editor.options/pagerange) | Autre instance de PageRange à vérifier pour l'égalité |
|

**Returns:**
booléen - true si égaux ; false si différents

### fromBeginningWithCount(int pageCount) {#fromBeginningWithCount-int-}
```
public static PageRange fromBeginningWithCount(int pageCount)
```


Crée une plage de pages qui commence à la première page et possède le nombre de pages spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | pageCount | int | Nombre de pages, doit être strictement supérieur à zéro |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageTillEnd(int startPageNumber) {#fromStartPageTillEnd-int-}
```
public static PageRange fromStartPageTillEnd(int startPageNumber)
```


Crée une plage de pages qui commence au numéro de page spécifié et se poursuit jusqu'à la fin du document


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | startPageNumber | int | Numéro de page, à partir duquel la plage de pages commence, inclusivement. Les numéros de page sont basés sur 1, donc doivent être strictement supérieurs à zéro |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageWithCount(int startPageNumber, int pageCount) {#fromStartPageWithCount-int-int-}
```
public static PageRange fromStartPageWithCount(int startPageNumber, int pageCount)
```


Crée une plage de pages qui commence au numéro de page spécifié et possède le nombre de pages indiqué, ou un nombre illimité de pages (jusqu'à la fin)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | startPageNumber | int | Numéro de page, à partir duquel la plage de pages commence, inclusivement. Les numéros de page sont basés sur 1, donc doivent être strictement supérieurs à zéro |
|
|  | pageCount | int | Nombre de pages, doit être strictement supérieur à zéro. Si zéro - cela signifie toutes les pages jusqu'à la fin d'un document |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageTillEndPage(int startPageNumber, int endPageNumber) {#fromStartPageTillEndPage-int-int-}
```
public static PageRange fromStartPageTillEndPage(int startPageNumber, int endPageNumber)
```


Crée une plage de pages qui commence au numéro de page spécifié (inclusivement) et se poursuit jusqu'au numéro de page spécifié (exclusivement)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | startPageNumber | int | Numéro de page, à partir duquel la plage de pages commence, inclusivement. Les numéros de page sont basés sur 1, donc doivent être strictement supérieurs à zéro |
|
|  | endPageNumber | int | Numéro de page, jusqu'auquel la plage de pages continue, exclusivement. Les numéros de page sont basés sur 1, donc doivent être strictement supérieurs à zéro, et également strictement supérieurs à startPageNumber |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - 
