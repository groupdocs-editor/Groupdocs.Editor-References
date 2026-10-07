---
title: "XmlFormatOptions"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Contiene opzioni che consentono di regolare la formattazione del documento XML quando è rappresentato come HTML"
type: docs
weight: 52
url: /it/java/com.groupdocs.editor.options/xmlformatoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlFormatOptions implements IEditOptions
```

Contiene opzioni che consentono di regolare la formattazione del documento XML quando è rappresentato come HTML

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getEachAttributeFromNewline()](#getEachAttributeFromNewline--) | Quando abilitato, ogni coppia attributo-valore in ogni elemento XML verrà posizionata su una nuova riga. |
|
|  | [setEachAttributeFromNewline(boolean value)](#setEachAttributeFromNewline-boolean-) | Quando abilitato, ogni coppia attributo-valore in ogni elemento XML verrà posizionata su una nuova riga. |
|
|  | [getLeafTextNodesOnNewline()](#getLeafTextNodesOnNewline--) | Quando abilitato, i nodi di testo foglia (contenuto testuale all'interno degli elementi XML, che non hanno figli) verranno renderizzati su una nuova riga con un'indentazione sinistra più ampia. |
|
|  | [setLeafTextNodesOnNewline(boolean value)](#setLeafTextNodesOnNewline-boolean-) | Quando abilitato, i nodi di testo foglia (contenuto testuale all'interno degli elementi XML, che non hanno figli) verranno renderizzati su una nuova riga con un'indentazione sinistra più ampia. |
|
|  | [getLeftIndent()](#getLeftIndent--) | Consente di specificare un offset per l'indentazione sinistra di ogni nuova riga. |
|
|  | [setLeftIndent(Length value)](#setLeftIndent-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Consente di specificare un offset per l'indentazione sinistra di ogni nuova riga. |
|
|  | [isDefault()](#isDefault--) | Indica se questa istanza delle opzioni di formattazione XML ha un valore predefinito |
|
### getEachAttributeFromNewline() {#getEachAttributeFromNewline--}
```
public final boolean getEachAttributeFromNewline()
```


Quando abilitato, ogni coppia attributo-valore in ogni elemento XML verrà posizionata su una nuova riga.
Per impostazione predefinita è false (disabilitato) \u2014 tutte le coppie attributo-valore sono posizionate in un'unica riga.


**Returns:**
boolean
### setEachAttributeFromNewline(boolean value) {#setEachAttributeFromNewline-boolean-}
```
public final void setEachAttributeFromNewline(boolean value)
```


Quando abilitato, ogni coppia attributo-valore in ogni elemento XML verrà posizionata su una nuova riga.
Per impostazione predefinita è false (disabilitato) \u2014 tutte le coppie attributo-valore sono posizionate in un'unica riga.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getLeafTextNodesOnNewline() {#getLeafTextNodesOnNewline--}
```
public final boolean getLeafTextNodesOnNewline()
```


Quando abilitato, i nodi di testo foglia (contenuto testuale all'interno degli elementi XML, che non hanno figli) verranno renderizzati su una nuova riga con un'indentazione sinistra più ampia.
Per impostazione predefinita è false (disabilitato) \u2014 i nodi di testo foglia sono posizionati sulla stessa riga dei loro genitori, senza nuova indentazione.


**Returns:**
boolean
### setLeafTextNodesOnNewline(boolean value) {#setLeafTextNodesOnNewline-boolean-}
```
public final void setLeafTextNodesOnNewline(boolean value)
```


Quando abilitato, i nodi di testo foglia (contenuto testuale all'interno degli elementi XML, che non hanno figli) verranno renderizzati su una nuova riga con un'indentazione sinistra più ampia.
Per impostazione predefinita è false (disabilitato) \u2014 i nodi di testo foglia sono posizionati sulla stessa riga dei loro genitori, senza nuova indentazione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getLeftIndent() {#getLeftIndent--}
```
public final Length getLeftIndent()
```


Consente di specificare un offset per l'indentazione sinistra di ogni nuova riga. Non può essere un valore senza unità diverso da zero. Per impostazione predefinita è 10pt


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### setLeftIndent(Length value) {#setLeftIndent-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public final void setLeftIndent(Length value)
```


Consente di specificare un offset per l'indentazione sinistra di ogni nuova riga. Non può essere un valore senza unità diverso da zero. Per impostazione predefinita è 10pt


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Indica se questa istanza delle opzioni di formattazione XML ha un valore predefinito


**Returns:**
boolean
