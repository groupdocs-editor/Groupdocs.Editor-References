---
title: "Dimensioni"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Rappresenta le dimensioni lineari larghezza e altezza di un'immagine raster rettangolare in unità arbitraria."
type: docs
weight: 10
url: /it/java/com.groupdocs.editor.htmlcss.resources.images/dimensions/
---
**Inheritance:**
java.lang.Object
```
public class Dimensions
```

Rappresenta le dimensioni lineari (larghezza e altezza) di un raster rettangolare
immagine in unità arbitraria. Struttura immutabile.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [Dimensions(int width, int height)](#Dimensions-int-int-) | Crea una nuova istanza a partire da larghezza e altezza specificate |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getWidth()](#getWidth--) | Restituisce la larghezza dell'immagine |
|
|  | [getHeight()](#getHeight--) | Restituisce l'altezza dell'immagine |
|
|  | [isSquare()](#isSquare--) | Determina se le 'Dimensions' specificate rappresentano un quadrato, cioè. |
|
|  | [getArea()](#getArea--) | Restituisce un'area (Larghezza x Altezza) |
|
|  | [isEmpty()](#isEmpty--) | Determina se questa istanza "Dimensions" è vuota e predefinita, cioè. |
|
|  | [getAspectRatio()](#getAspectRatio--) | Rapporto d'aspetto di queste dimensioni come larghezza/altezza |
|
|  | [proportionallyResizeForNewWidth(int targetWidth)](#proportionallyResizeForNewWidth-int-) | Crea e restituisce una nuova istanza "Dimensions", che è proporzionalmente |
ridimensionata dall'attuale, basata sulla larghezza specificata
|
|  | [proportionallyResizeForNewHeight(int targetHeight)](#proportionallyResizeForNewHeight-int-) | Crea e restituisce una nuova istanza "Dimensions", che è proporzionalmente |
ridimensionata dall'attuale, basata sull'altezza specificata
|
|  | [equals(Dimensions other)](#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Determina se questa istanza è uguale alla "Dimensions" specificata |
istanza
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Determina se questa istanza è uguale all'oggetto non convertito specificato, |
che presumibilmente è un'altra istanza "Dimensions"
|
|  | [hashCode()](#hashCode--) | Restituisce un hashcode per questa istanza, che non può essere modificato durante il suo |
ciclo di vita
|
|  | [op_Equality(Dimensions first, Dimensions second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Verifica se due valori "Dimensions" sono uguali, cioè. |
|
|  | [op_Inequality(Dimensions first, Dimensions second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Verifica se due valori "Dimensions" non sono uguali, cioè. |
|
|  | [toString()](#toString--) | Restituisce una rappresentazione stringa di questa "Dimensions" |
|
|  | [deepClone()](#deepClone--) | Restituisce una copia completa di questa istanza |
|
|  | [getEmpty()](#getEmpty--) | Restituisce un'istanza Dimensions vuota |
|
### Dimensions(int width, int height) {#Dimensions-int-int-}
```
public Dimensions(int width, int height)
```


Crea una nuova istanza a partire da larghezza e altezza specificate


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | larghezza | int | Larghezza dell'immagine |
|
|  | altezza | int | Altezza dell'immagine |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Restituisce la larghezza dell'immagine


**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Restituisce l'altezza dell'immagine


**Returns:**
int
### isSquare() {#isSquare--}
```
public final boolean isSquare()
```


Determina se le 'Dimensions' specificate rappresentano un quadrato, cioè se
la larghezza è uguale all'altezza


**Returns:**
boolean
### getArea() {#getArea--}
```
public final long getArea()
```


Restituisce un'area (Larghezza x Altezza)


**Returns:**
long
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Determina se questa istanza "Dimensions" è vuota e predefinita, cioè.
non memorizza correttamente larghezza e altezza


**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Rapporto d'aspetto di queste dimensioni come larghezza/altezza


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### proportionallyResizeForNewWidth(int targetWidth) {#proportionallyResizeForNewWidth-int-}
```
public final Dimensions proportionallyResizeForNewWidth(int targetWidth)
```


Crea e restituisce una nuova istanza "Dimensions", che è proporzionalmente
ridimensionata dall'attuale, basata sulla larghezza specificata


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | targetWidth | int | Nuova larghezza target, che sarà presente nella Dimension |
|

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target width and proportionally resized height

### proportionallyResizeForNewHeight(int targetHeight) {#proportionallyResizeForNewHeight-int-}
```
public final Dimensions proportionallyResizeForNewHeight(int targetHeight)
```


Crea e restituisce una nuova istanza "Dimensions", che è proporzionalmente
ridimensionata dall'attuale, basata sull'altezza specificata


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | targetHeight | int | Nuova altezza target, che sarà presente nella Dimension |
|

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target height and proportionally resized width

### equals(Dimensions other) {#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public final boolean equals(Dimensions other)
```


Determina se questa istanza è uguale alla "Dimensions" specificata
istanza


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Altra istanza di "Dimensions" da verificare per uguaglianza |
|

**Returns:**
boolean - True se sono uguali, false se non lo sono

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se questa istanza è uguale all'oggetto non convertito specificato,
che presumibilmente è un'altra istanza "Dimensions"


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | obj | java.lang.Object | Altro oggetto, presumibilmente di tipo "Dimensions", che dovrebbe essere verificato per uguaglianza con questo |
|

**Returns:**
boolean - True se sono uguali, false se non lo sono

### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un hashcode per questa istanza, che non può essere modificato durante il suo
ciclo di vita


**Returns:**
int - Codice hash immutabile (per questa istanza) come intero con segno a 4 byte

### op_Equality(Dimensions first, Dimensions second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Equality(Dimensions first, Dimensions second)
```


Verifica se due valori "Dimensions" sono uguali, cioè hanno uguali
larghezza e altezza, o entrambi sono vuoti


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Prima istanza da verificare |
|
|  | second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Seconda istanza da verificare |
|

**Returns:**
boolean - True se sono uguali, false se non lo sono

### op_Inequality(Dimensions first, Dimensions second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Inequality(Dimensions first, Dimensions second)
```


Verifica se due valori "Dimensions" non sono uguali, cioè i loro
larghezza e/o altezza corrispondenti sono diversi


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Prima istanza da verificare |
|
|  | second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Seconda istanza da verificare |
|

**Returns:**
boolean - True se sono diversi, false se sono uguali

### toString() {#toString--}
```
public String toString()
```


Restituisce una rappresentazione stringa di questa "Dimensions"

*** ** * ** ***


> ```
> W640×H480
> ```

<br />



**Returns:**
java.lang.String - Istanza di String, che contiene una larghezza e un'altezza nel formato W:(width)×H:(height)

### deepClone() {#deepClone--}
```
public final Dimensions deepClone()
```


Restituisce una copia completa di questa istanza


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New instance, that is a full and deep copy of this one

### getEmpty() {#getEmpty--}
```
public static Dimensions getEmpty()
```


Restituisce un'istanza Dimensions vuota


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
