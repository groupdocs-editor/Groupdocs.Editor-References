---
title: "SpreadsheetEditOptions"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Permet de spécifier des options personnalisées pour l'édition des documents de tous les formats de feuille de calcul compatibles Excel pris en charge"
type: docs
weight: 35
url: /fr/nodejs-java/com.groupdocs.editor.options/spreadsheeteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class SpreadsheetEditOptions implements IEditOptions
```

Permet de spécifier des options personnalisées pour l’édition de documents de tous les formats pris en charge
Formats de feuille de calcul (compatibles Excel)

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SpreadsheetEditOptions()](#SpreadsheetEditOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Permet de spécifier l'indice basé sur zéro de la feuille de calcul (onglet) d'entrée |
Document de feuille de calcul qui doit être converti en HTML (voir
remarques).
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Permet de spécifier l'indice basé sur zéro de la feuille de calcul (onglet) d'entrée |
Document de feuille de calcul qui doit être converti en HTML (voir
remarques).
|
|  | [getExcludeHiddenWorksheets()](#getExcludeHiddenWorksheets--) | Permet d'exclure les feuilles de calcul cachées dans le document de feuille de calcul d'entrée, afin que |
elles soient totalement ignorées.
|
|  | [setExcludeHiddenWorksheets(boolean value)](#setExcludeHiddenWorksheets-boolean-) | Permet d'exclure les feuilles de calcul cachées dans le document de feuille de calcul d'entrée, afin que |
elles soient totalement ignorées.
|
|  | [getMergeEmptyAdjacentCells()](#getMergeEmptyAdjacentCells--) | Lorsqu'elle est activée, les cellules horizontales adjacentes vides du document de feuille de calcul d'entrée seront |
représentées dans le document HTML éditable comme fusionnées en une seule cellule avec le
attribut colspan.
|
| [setMergeEmptyAdjacentCells(boolean value)](#setMergeEmptyAdjacentCells-boolean-) |  |
|  | [getExportBogusRowData()](#getExportBogusRowData--) | Lorsqu'elle est activée, le tableau HTML dans le document HTML produit contient une ligne cachée vide en bas avec |
une hauteur nulle et des cellules vides, où seule la largeur est spécifiée.
|
| [setExportBogusRowData(boolean value)](#setExportBogusRowData-boolean-) |  |
### SpreadsheetEditOptions() {#SpreadsheetEditOptions--}
```
public SpreadsheetEditOptions()
```


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


Permet de spécifier l'indice basé sur zéro de la feuille de calcul (onglet) d'entrée
Document de feuille de calcul qui doit être converti en HTML (voir
remarques).


*** ** * ** ***

La plupart des documents de feuille de calcul prennent en charge le concept d'onglets, c'est‑à‑dire qu'ils peuvent être multi‑onglets. En revanche, le format HTML ne supporte pas cette structure. En raison de cela, GroupDocs.Editor ne peut convertir en HTML qu'un seul onglet spécifique du document d'entrée, et cette option permet de le spécifier. L'indice d'onglet est basé sur zéro, les valeurs négatives sont interdites. Si l'indice spécifié dépasse le nombre total d'onglets, une exception sera levée. Si le document de feuille de calcul d'entrée ne contient qu'un seul onglet, cette option sera ignorée. La valeur par défaut est 0 (premier onglet).

<br />



**Returns:**
int
### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Permet de spécifier l'indice basé sur zéro de la feuille de calcul (onglet) d'entrée
Document de feuille de calcul qui doit être converti en HTML (voir
remarques).


*** ** * ** ***

La plupart des documents de feuille de calcul prennent en charge le concept d'onglets, c'est‑à‑dire qu'ils peuvent être multi‑onglets. En revanche, le format HTML ne supporte pas cette structure. En raison de cela, GroupDocs.Editor ne peut convertir en HTML qu'un seul onglet spécifique du document d'entrée, et cette option permet de le spécifier. L'indice d'onglet est basé sur zéro, les valeurs négatives sont interdites. Si l'indice spécifié dépasse le nombre total d'onglets, une exception sera levée. Si le document de feuille de calcul d'entrée ne contient qu'un seul onglet, cette option sera ignorée. La valeur par défaut est 0 (premier onglet).

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getExcludeHiddenWorksheets() {#getExcludeHiddenWorksheets--}
```
public final boolean getExcludeHiddenWorksheets()
```


Permet d'exclure les feuilles de calcul cachées dans le document de feuille de calcul d'entrée, afin que
elles seront totalement ignorées. La valeur par défaut est false - les feuilles de calcul cachées sont
disponibles et traitées normalement.


*** ** * ** ***

Plusieurs formats binaires de feuille de calcul (comme XLSX) prennent en charge le concept de feuilles de calcul cachées (onglets). Un document de ce format, s'il possède plus d'une feuille, peut contenir des feuilles cachées supplémentaires. Par défaut, ces feuilles cachées sont disponibles pour le traitement, mais avec cette option il est possible de les ignorer, comme si ces feuilles cachées étaient absentes et n'existaient pas. Lorsque cette option est activée, vous ne pouvez pas sélectionner une feuille cachée avec la propriété ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))'.

<br />



**Returns:**
booléen
### setExcludeHiddenWorksheets(boolean value) {#setExcludeHiddenWorksheets-boolean-}
```
public final void setExcludeHiddenWorksheets(boolean value)
```


Permet d'exclure les feuilles de calcul cachées dans le document de feuille de calcul d'entrée, afin que
elles seront totalement ignorées. La valeur par défaut est false - les feuilles de calcul cachées sont
disponibles et traitées normalement.


*** ** * ** ***

Plusieurs formats binaires de feuille de calcul (comme XLSX) prennent en charge le concept de feuilles de calcul cachées (onglets). Un document de ce format, s'il possède plus d'une feuille, peut contenir des feuilles cachées supplémentaires. Par défaut, ces feuilles cachées sont disponibles pour le traitement, mais avec cette option il est possible de les ignorer, comme si ces feuilles cachées étaient absentes et n'existaient pas. Lorsque cette option est activée, vous ne pouvez pas sélectionner une feuille cachée avec la propriété ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))'.

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getMergeEmptyAdjacentCells() {#getMergeEmptyAdjacentCells--}
```
public boolean getMergeEmptyAdjacentCells()
```


Lorsqu'elle est activée, les cellules horizontales adjacentes vides du document de feuille de calcul d'entrée seront
représentées dans le document HTML éditable comme fusionnées en une seule cellule avec le
attribut colspan. Par défaut, il est désactivé (false).


Par défaut, le GroupDocs.Editor convertit un tableau du document de feuille de calcul d'entrée vers la sortie
document HTML en préservant chaque cellule. Cependant, les documents de feuille de calcul peuvent être clairsemés \\u2014 ils
peuvent contenir une énorme quantité de \"zones vides\", où de nombreuses cellules sont vides. Cette option, lorsqu'elle
est activée, fusionne ces cellules vides en une seule avec l'attribut colspan dans l'élément TD,
et ainsi peut réduire considérablement la taille du balisage HTML produit.


**Returns:**
booléen
### setMergeEmptyAdjacentCells(boolean value) {#setMergeEmptyAdjacentCells-boolean-}
```
public void setMergeEmptyAdjacentCells(boolean value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getExportBogusRowData() {#getExportBogusRowData--}
```
public boolean getExportBogusRowData()
```


Lorsqu'elle est activée, le tableau HTML dans le document HTML produit contient une ligne cachée vide en bas avec
hauteur nulle et cellules vides, où seule la largeur est spécifiée. Cette ligne avec des cellules vides contient
des valeurs de largeur exactes pour chaque colonne et améliore la conversion inverse de HTML vers Spreadsheet. Par
la valeur par défaut est activée (true).


**Returns:**
booléen
### setExportBogusRowData(boolean value) {#setExportBogusRowData-boolean-}
```
public void setExportBogusRowData(boolean value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

