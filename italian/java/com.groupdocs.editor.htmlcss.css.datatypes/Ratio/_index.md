---
title: "Rapporto"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Rappresenta un tipo di dato CSS ratio che viene utilizzato per descrivere i rapporti d'aspetto nelle media query e per le immagini raster, indicando la proporzione tra due valori senza unità chiamati numeratore e denominatore."
type: docs
weight: 14
url: /it/java/com.groupdocs.editor.htmlcss.css.datatypes/ratio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Ratio implements ICssDataType
```

Rappresenta un tipo di dato CSS \"ratio\", che viene utilizzato per descrivere l'aspetto
rapporti nelle media query e per le immagini raster indicando la proporzione
tra due valori senza unità chiamati \"numeratore\" e \"denominatore\". Immutabile
struct.


*** ** * ** ***

https://developer.mozilla.org/en-US/docs/Web/CSS/ratio

<br />


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Ratio()](#Ratio--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Single](#Single) | Rapporto predefinito singolo 1/1 |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getNumerator()](#getNumerator--) | Restituisce il numeratore di questo rapporto |
|
|  | [getDenominator()](#getDenominator--) | Restituisce il denominatore di questo rapporto |
|
|  | [calculate()](#calculate--) | Calcola e restituisce questo rapporto come un singolo numero a virgola mobile |
|
|  | [getInverseRatio()](#getInverseRatio--) | Genera e restituisce un rapporto inverso (reciproco) per questo rapporto |
|
|  | [serializeDefault()](#serializeDefault--) | Serializza questo rapporto in una stringa e lo restituisce |
|
|  | [toString()](#toString--) | Restituisce una rappresentazione stringa di questo rapporto; uguale a |
\"SerializeDefault()\"
|
|  | [isDefault()](#isDefault--) | Determina se questo rapporto ha valore predefinito o è un \"1/1\" (Singolo) |
|
|  | [deepClone()](#deepClone--) | Restituisce una copia completa di questo rapporto |
|
|  | [equals(Ratio other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Determina se questa istanza è uguale all'istanza \"Ratio\" specificata |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Determina se questa istanza è uguale all'oggetto non convertito specificato, |
che presumibilmente è un'altra istanza "Ratio"
|
|  | [op_Equality(Ratio left, Ratio right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Confronta due rapporti e restituisce un valore booleano che indica se i due corrispondono. |
|
|  | [op_Inequality(Ratio left, Ratio right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Confronta due rapporti e restituisce un valore booleano che indica se i due non |
corrispondono.
|
|  | [hashCode()](#hashCode--) | Restituisce un hashcode per questa istanza, che non può essere modificato durante il suo |
ciclo di vita
|
|  | [create(int numerator, int denominator)](#create-int-int-) | Crea e restituisce un'istanza Ratio a partire dal numeratore e |
denominatore
|
### Ratio() {#Ratio--}
```
public Ratio()
```


### Single {#Single}
```
public static final Ratio Single
```


Rapporto predefinito singolo 1/1


### getNumerator() {#getNumerator--}
```
public final int getNumerator()
```


Restituisce il numeratore di questo rapporto


**Returns:**
int
### getDenominator() {#getDenominator--}
```
public final int getDenominator()
```


Restituisce il denominatore di questo rapporto


**Returns:**
int
### calculate() {#calculate--}
```
public final double calculate()
```


Calcola e restituisce questo rapporto come un singolo numero a virgola mobile


**Returns:**
double - Numero a virgola mobile a doppia precisione

### getInverseRatio() {#getInverseRatio--}
```
public final Ratio getInverseRatio()
```


Genera e restituisce un rapporto inverso (reciproco) per questo rapporto


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is an inverse ratio for this one

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Serializza questo rapporto in una stringa e lo restituisce


**Returns:**
java.lang.String - Stringa nel formato "numeratore/denominatore"

### toString() {#toString--}
```
public String toString()
```


Restituisce una rappresentazione stringa di questo rapporto; uguale a
\"SerializeDefault()\"


**Returns:**
java.lang.String - Stringa nel formato "numeratore/denominatore"

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Determina se questo rapporto ha valore predefinito o è un \"1/1\" (Singolo)


**Returns:**
boolean
### deepClone() {#deepClone--}
```
public final Ratio deepClone()
```


Restituisce una copia completa di questo rapporto


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is a full and deep copy of this one

### equals(Ratio other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public final boolean equals(Ratio other)
```


Determina se questa istanza è uguale all'istanza \"Ratio\" specificata


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Altra istanza Ratio da verificare per uguaglianza con questa |
|

**Returns:**
boolean - True se sono uguali, false se sono diversi

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Determina se questa istanza è uguale all'oggetto non convertito specificato,
che presumibilmente è un'altra istanza "Ratio"


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | altro | java.lang.Object | Altra istanza System.Object, presumibilmente di tipo Ratio, da verificare per uguaglianza con questa |
|

**Returns:**
boolean - True se sono uguali, false se sono diversi

### op_Equality(Ratio left, Ratio right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Equality(Ratio left, Ratio right)
```


Confronta due rapporti e restituisce un valore booleano che indica se i due corrispondono.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Il primo rapporto da utilizzare. |
|
|  | right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Il secondo rapporto da utilizzare. |
|

**Returns:**
boolean - Vero se entrambi i rapporti sono uguali, altrimenti falso.

### op_Inequality(Ratio left, Ratio right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Inequality(Ratio left, Ratio right)
```


Confronta due rapporti e restituisce un valore booleano che indica se i due non
corrispondono.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Il primo rapporto da utilizzare. |
|
|  | right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Il secondo rapporto da utilizzare. |
|

**Returns:**
boolean - Vero se entrambi i rapporti non sono uguali, altrimenti falso.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un hashcode per questa istanza, che non può essere modificato durante il suo
ciclo di vita


**Returns:**
int - Intero con segno a 4 byte, immutabile per questa istanza

### create(int numerator, int denominator) {#create-int-int-}
```
public static Ratio create(int numerator, int denominator)
```


Crea e restituisce un'istanza Ratio a partire dal numeratore e
denominatore


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | numeratore | int | Numeratore per il rapporto. Deve essere un numero intero strettamente positivo. |
|
|  | denominatore | int | Denominatore per il rapporto. Deve essere un numero intero strettamente positivo. |
|

**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance

