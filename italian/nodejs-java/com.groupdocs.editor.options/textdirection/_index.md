---
title: "TextDirection"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Rappresenta 3 possibili varianti su come trattare la direzione del testo nei documenti di testo semplice"
type: docs
weight: 38
url: /it/nodejs-java/com.groupdocs.editor.options/textdirection/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextDirection extends System.Enum
```

Rappresenta 3 possibili varianti su come trattare la direzione del testo nel testo semplice
documenti

## Campi

| Campo | Descrizione |
| --- | --- |
|  | [LeftToRight](#LeftToRight) | Direzione da sinistra a destra, testo usuale, valore predefinito. |
|
|  | [RightToLeft](#RightToLeft) | Direzione da destra a sinistra |
|
|  | [Auto](#Auto) | Rileva automaticamente la direzione. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getTextDirection()](#getTextDirection--) |  |
### LeftToRight {#LeftToRight}
```
public static final int LeftToRight
```


Direzione da sinistra a destra, testo usuale, valore predefinito.


### RightToLeft {#RightToLeft}
```
public static final int RightToLeft
```


Direzione da destra a sinistra


### Auto {#Auto}
```
public static final int Auto
```


Rileva automaticamente la direzione. Quando questa opzione è selezionata e il testo contiene
caratteri appartenenti a script RTL, la direzione del documento verrà impostata
automaticamente a RTL.


### getTextDirection() {#getTextDirection--}
```
public static int[] getTextDirection()
```




**Returns:**
int[]
