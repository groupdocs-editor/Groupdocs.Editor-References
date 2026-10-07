---
title: "ArgbColor"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Rappresenta un valore di colore in formato ARGB con convertitori e serializzatori"
type: docs
weight: 10
url: /it/java/com.groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class ArgbColor extends Struct<ArgbColor> implements ICssDataType
```

Rappresenta un valore di colore in formato ARGB con convertitori e serializzatori

<br />

*** ** * ** ***

Questo tipo è progettato per essere utile per (ma non limitato a) operazioni CSS. Vedi di più: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

<br />


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ArgbColor()](#ArgbColor--) |  |
| [ArgbColor(int r, int g, int b)](#ArgbColor-int-int-int-) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [fromRgba(int red, int green, int blue, int alpha)](#fromRgba-int-int-int-int-) | Crea un valore [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) da canali Rosso, Verde, Blu e Alfa specificati |
|
|  | [fromRgb(int red, int green, int blue)](#fromRgb-int-int-int-) | Crea un valore [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) da canali Rosso, Verde, Blu specificati, mentre il canale Alfa è completamente opaco |
|
|  | [fromSingleValueRgb(byte value)](#fromSingleValueRgb-byte-) | Crea un colore completamente opaco (A=255) da un singolo valore, che verrà applicato a tutti i canali |
|
|  | [fromColor(Color color)](#fromColor-java.awt.Color-) | Crea un valore [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) da [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) specificato |
|
|  | [getValue()](#getValue--) | Ottiene il valore Int32 del colore. |
|
|  | [getA()](#getA--) | Ottiene la parte alfa del colore. |
|
|  | [getAlpha()](#getAlpha--) | Ottiene la parte alfa del colore in percentuale (0..1). |
|
|  | [getR()](#getR--) | Ottiene la parte rossa del colore. |
|
|  | [getG()](#getG--) | Ottiene la parte verde del colore. |
|
|  | [getB()](#getB--) | Ottiene la parte blu del colore. |
|
|  | [isEmpty()](#isEmpty--) | Colore non inizializzato - tutti i 4 canali sono impostati a 0. |
|
|  | [isDefault()](#isDefault--) | Indica se questa istanza di [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) è predefinita (Transparent) - tutti i 4 canali sono impostati a 0 |
|
|  | [isFullyTransparent()](#isFullyTransparent--) | Indica se questa istanza di [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) è completamente trasparente - il suo canale Alfa ha il valore minimo (0), quindi gli altri canali R, G e B non hanno effetto visibile. |
|
|  | [isTranslucent()](#isTranslucent--) | Indica se questa istanza di [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) è traslucida (non completamente trasparente, ma neanche completamente opaca) |
|
|  | [isFullyOpaque()](#isFullyOpaque--) | Indica se questa istanza di [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) è completamente opaca, senza trasparenza (il suo canale Alfa ha il valore massimo) |
|
|  | [toSystemColor()](#toSystemColor--) | Converte un valore di questa istanza di [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) in un'istanza di [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) e la restituisce |
|
|  | [toRGBA()](#toRGBA--) | Serializza questa istanza di [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) nella notazione della funzione CSS 'rgba' |
|
|  | [toRGB()](#toRGB--) | Serializza questa istanza di [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) nella notazione della funzione CSS 'rgb' |
|
|  | [serializeDefault()](#serializeDefault--) | Serializza questa istanza di [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) nella notazione della funzione CSS più appropriata in base alla traslucenza |
|
|  | [toString()](#toString--) | Stesso di #serializeDefault.serializeDefault |
|
|  | [op_Equality(ArgbColor left, ArgbColor right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Confronta due colori e restituisce un booleano che indica se i due corrispondono. |
|
|  | [op_Inequality(ArgbColor left, ArgbColor right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Confronta due colori e restituisce un booleano che indica se i due non corrispondono. |
|
|  | [equals(ArgbColor other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Controlla due colori [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) per l'uguaglianza |
|
|  | [equals(ICssDataType other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-) | Controlla due colori [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) per l'uguaglianza |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Verifica se un altro oggetto è uguale a questa istanza di [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor). |
|
|  | [hashCode()](#hashCode--) | Restituisce un codice hash che definisce il colore corrente. |
|
### ArgbColor() {#ArgbColor--}
```
public ArgbColor()
```


### ArgbColor(int r, int g, int b) {#ArgbColor-int-int-int-}
```
public ArgbColor(int r, int g, int b)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| r | int |  |
| g | int |  |
| b | int |  |

### fromRgba(int red, int green, int blue, int alpha) {#fromRgba-int-int-int-int-}
```
public static ArgbColor fromRgba(int red, int green, int blue, int alpha)
```


Crea un valore [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) da canali Rosso, Verde, Blu e Alfa specificati


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | rosso | int | Valore del canale rosso |
|
|  | verde | int | Valore del canale verde |
|
|  | blu | int | Valore del canale blu |
|
|  | alpha | int | Valore del canale alpha |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value

### fromRgb(int red, int green, int blue) {#fromRgb-int-int-int-}
```
public static ArgbColor fromRgb(int red, int green, int blue)
```


Crea un valore [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) da canali Rosso, Verde, Blu specificati, mentre il canale Alfa è completamente opaco


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | rosso | int | Valore del canale rosso |
|
|  | verde | int | Valore del canale verde |
|
|  | blu | int | Valore del canale blu |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value

### fromSingleValueRgb(byte value) {#fromSingleValueRgb-byte-}
```
public static ArgbColor fromSingleValueRgb(byte value)
```


Crea un colore completamente opaco (A=255) da un singolo valore, che verrà applicato a tutti i canali


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | byte | Un valore byte, uguale per i canali Rosso, Verde e Blu |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance

### fromColor(Color color) {#fromColor-java.awt.Color-}
```
public static ArgbColor fromColor(Color color)
```


Crea un valore [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) da [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colore | java.awt.Color |  |

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - 
### getValue() {#getValue--}
```
public final int getValue()
```


Ottiene il valore Int32 del colore.


**Returns:**
int
### getA() {#getA--}
```
public final int getA()
```


Ottiene la parte alfa del colore.


**Returns:**
int
### getAlpha() {#getAlpha--}
```
public final double getAlpha()
```


Ottiene la parte alfa del colore in percentuale (0..1).


**Returns:**
double
### getR() {#getR--}
```
public final int getR()
```


Ottiene la parte rossa del colore.


**Returns:**
int
### getG() {#getG--}
```
public final int getG()
```


Ottiene la parte verde del colore.


**Returns:**
int
### getB() {#getB--}
```
public final int getB()
```


Ottiene la parte blu del colore.


**Returns:**
int
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Colore non inizializzato - tutti i 4 canali sono impostati a 0. Stesso di Default e Transparent.


**Returns:**
boolean
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Indica se questa istanza di [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) è predefinita (Transparent) - tutti i 4 canali sono impostati a 0


**Returns:**
boolean
### isFullyTransparent() {#isFullyTransparent--}
```
public final boolean isFullyTransparent()
```


Indica se questa istanza di [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) è completamente trasparente - il suo canale Alfa ha il valore minimo (0), quindi gli altri canali R, G e B non hanno effetto visibile.


**Returns:**
boolean
### isTranslucent() {#isTranslucent--}
```
public final boolean isTranslucent()
```


Indica se questa istanza di [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) è traslucida (non completamente trasparente, ma neanche completamente opaca)


**Returns:**
boolean
### isFullyOpaque() {#isFullyOpaque--}
```
public final boolean isFullyOpaque()
```


Indica se questa istanza di [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) è completamente opaca, senza trasparenza (il suo canale Alfa ha il valore massimo)


**Returns:**
boolean
### toSystemColor() {#toSystemColor--}
```
public final Color toSystemColor()
```


Converte un valore di questa istanza di [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) in un'istanza di [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) e la restituisce


**Returns:**
[Color](../../java.awt/color) - New [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) instance

### toRGBA() {#toRGBA--}
```
public final String toRGBA()
```


Serializza questa istanza di [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) nella notazione della funzione CSS 'rgba'


**Returns:**
java.lang.String - Una stringa con formato 'rgba(r, g, b, a)'

### toRGB() {#toRGB--}
```
public final String toRGB()
```


Serializza questa istanza di [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) nella notazione della funzione CSS 'rgb'


**Returns:**
java.lang.String - Una stringa con formato 'rgb(r, g, b)'

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Serializza questa istanza di [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) nella notazione della funzione CSS più appropriata in base alla traslucenza


**Returns:**
java.lang.String - Una stringa con formato 'rgba(r, g, b, a)' o 'rgb(r, g, b)'

### toString() {#toString--}
```
public String toString()
```


Stesso di #serializeDefault.serializeDefault


**Returns:**
java.lang.String - Stesso valore di ritorno di #serializeDefault.serializeDefault

### op_Equality(ArgbColor left, ArgbColor right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public static boolean op_Equality(ArgbColor left, ArgbColor right)
```


Confronta due colori e restituisce un booleano che indica se i due corrispondono.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | left | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Il primo colore da utilizzare. |
|
|  | right | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Il secondo colore da utilizzare. |
|

**Returns:**
boolean - Vero se entrambi i colori sono uguali, altrimenti falso.

### op_Inequality(ArgbColor left, ArgbColor right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public static boolean op_Inequality(ArgbColor left, ArgbColor right)
```


Confronta due colori e restituisce un booleano che indica se i due non corrispondono.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | left | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Il primo colore da utilizzare. |
|
|  | right | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Il secondo colore da utilizzare. |
|

**Returns:**
boolean - Vero se entrambi i colori non sono uguali, altrimenti falso.

### equals(ArgbColor other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public final boolean equals(ArgbColor other)
```


Controlla due colori [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) per l'uguaglianza


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | L'altro colore [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) |
|

**Returns:**
boolean - Vero se entrambi i colori sono uguali, altrimenti falso.

### equals(ICssDataType other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-}
```
public final boolean equals(ICssDataType other)
```


Controlla due colori [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) per l'uguaglianza


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype) | L'altro colore [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor), convertito al tipo ICssDataType |
|

**Returns:**
boolean - Vero se entrambi i colori sono uguali, altrimenti falso.

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Verifica se un altro oggetto è uguale a questa istanza di [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | altro | java.lang.Object | L'oggetto con cui testare. |
|

**Returns:**
boolean - Vero se i due oggetti sono uguali, altrimenti falso.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un codice hash che definisce il colore corrente.


**Returns:**
int - Il valore intero dell'hashcode.

