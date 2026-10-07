---
title: "Dimensions"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Representerar de linjära dimensionerna bredd och höjd för en rasterrektangulär bild i en godtycklig enhet."
type: docs
weight: 10
url: /sv/java/com.groupdocs.editor.htmlcss.resources.images/dimensions/
---
**Inheritance:**
java.lang.Object
```
public class Dimensions
```

Representerar de linjära dimensionerna (bredd och höjd) för en rasterrektangulär
bild i en godtycklig enhet. Oföränderlig struct.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [Dimensions(int width, int height)](#Dimensions-int-int-) | Skapar en ny instans från angiven bredd och höjd |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getWidth()](#getWidth--) | Returnerar bredden på bilden |
|
|  | [getHeight()](#getHeight--) | Returnerar höjden på bilden |
|
|  | [isSquare()](#isSquare--) | Bestämmer om angiven 'Dimensions' representerar en kvadrat, d.v.s. |
|
|  | [getArea()](#getArea--) | Returnerar en yta (Bredd x Höjd) |
|
|  | [isEmpty()](#isEmpty--) | Bestämmer om detta "Dimensions"-instans är tom och standard, d.v.s. |
|
|  | [getAspectRatio()](#getAspectRatio--) | Bildförhållandet för dessa dimensioner som bredd/höjd |
|
|  | [proportionallyResizeForNewWidth(int targetWidth)](#proportionallyResizeForNewWidth-int-) | Skapar och returnerar en ny "Dimensions"-instans, som är proportionellt |
ändrad storlek från nuvarande, baserat på angiven bredd
|
|  | [proportionallyResizeForNewHeight(int targetHeight)](#proportionallyResizeForNewHeight-int-) | Skapar och returnerar en ny "Dimensions"-instans, som är proportionellt |
ändrad storlek från nuvarande, baserat på angiven höjd
|
|  | [equals(Dimensions other)](#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Bestämmer om denna instans är lika med angiven "Dimensions" |
instans
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om detta objekt är lika med angivet okastat objekt, |
vilket sannolikt är en annan "Dimensions"-instans
|
|  | [hashCode()](#hashCode--) | Returnerar en hashkod för detta objekt, som inte kan ändras under dess |
livstid
|
|  | [op_Equality(Dimensions first, Dimensions second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Kontrollerar om två "Dimensions"-värden är lika, d.v.s. |
|
|  | [op_Inequality(Dimensions first, Dimensions second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Kontrollerar om två "Dimensions"-värden inte är lika, d.v.s. |
|
|  | [toString()](#toString--) | Returnerar en strängrepresentation av detta "Dimensions" |
|
|  | [deepClone()](#deepClone--) | Returnerar en fullständig kopia av denna instans |
|
|  | [getEmpty()](#getEmpty--) | Returnerar en tom Dimensions-instans |
|
### Dimensions(int width, int height) {#Dimensions-int-int-}
```
public Dimensions(int width, int height)
```


Skapar en ny instans från angiven bredd och höjd


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | bredd | int | Bredd på bild |
|
|  | höjd | int | Bildens höjd |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Returnerar bredden på bilden


**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Returnerar höjden på bilden


**Returns:**
int
### isSquare() {#isSquare--}
```
public final boolean isSquare()
```


Bestämmer om angivna 'Dimensions' representerar en kvadrat, d.v.s. om
bredd är lika med höjd


**Returns:**
boolean
### getArea() {#getArea--}
```
public final long getArea()
```


Returnerar en yta (Bredd x Höjd)


**Returns:**
long
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Bestämmer om detta "Dimensions"-instans är tom och standard, d.v.s.
den lagrar inte korrekt bredd och höjd


**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Bildförhållandet för dessa dimensioner som bredd/höjd


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### proportionallyResizeForNewWidth(int targetWidth) {#proportionallyResizeForNewWidth-int-}
```
public final Dimensions proportionallyResizeForNewWidth(int targetWidth)
```


Skapar och returnerar en ny "Dimensions"-instans, som är proportionellt
ändrad storlek från nuvarande, baserat på angiven bredd


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | targetWidth | int | Ny målbredd, som kommer att finnas i resulterande Dimension |
|

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target width and proportionally resized height

### proportionallyResizeForNewHeight(int targetHeight) {#proportionallyResizeForNewHeight-int-}
```
public final Dimensions proportionallyResizeForNewHeight(int targetHeight)
```


Skapar och returnerar en ny "Dimensions"-instans, som är proportionellt
ändrad storlek från nuvarande, baserat på angiven höjd


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | targetHeight | int | Ny målhöjd, som kommer att finnas i resulterande Dimension |
|

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target height and proportionally resized width

### equals(Dimensions other) {#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public final boolean equals(Dimensions other)
```


Bestämmer om denna instans är lika med angiven "Dimensions"
instans


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Annat \"Dimensions\"-objekt att kontrollera för likhet |
|

**Returns:**
boolean - Sant om de är lika, falskt om de inte är lika

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om detta objekt är lika med angivet okastat objekt,
vilket sannolikt är en annan "Dimensions"-instans


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | obj | java.lang.Object | Annat objekt, som förmodligen är av typen \"Dimensions\", som bör kontrolleras för likhet med detta |
|

**Returns:**
boolean - Sant om de är lika, falskt om de inte är lika

### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för detta objekt, som inte kan ändras under dess
livstid


**Returns:**
int - Oföränderlig (för detta objekt) hashkod som signerat 4-byte heltal

### op_Equality(Dimensions first, Dimensions second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Equality(Dimensions first, Dimensions second)
```


Kontrollerar om två \"Dimensions\"-värden är lika, d.v.s. de har lika
bredd och höjd, eller båda är tomma


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Första objektet att kontrollera |
|
|  | second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Andra objektet att kontrollera |
|

**Returns:**
boolean - Sant om de är lika, falskt om de inte är lika

### op_Inequality(Dimensions first, Dimensions second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Inequality(Dimensions first, Dimensions second)
```


Kontrollerar om två \"Dimensions\"-värden inte är lika, d.v.s. deras
motsvarande bredd och/eller höjd är olika


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Första objektet att kontrollera |
|
|  | second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Andra objektet att kontrollera |
|

**Returns:**
boolean - Sant om de är olika, falskt om de är lika

### toString() {#toString--}
```
public String toString()
```


Returnerar en strängrepresentation av detta "Dimensions"

*** ** * ** ***


> ```
> W640×H480
> ```

<br />



**Returns:**
java.lang.String - Stränginstans som innehåller en bredd och höjd i formatet W:(width)×H:(height)

### deepClone() {#deepClone--}
```
public final Dimensions deepClone()
```


Returnerar en fullständig kopia av denna instans


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New instance, that is a full and deep copy of this one

### getEmpty() {#getEmpty--}
```
public static Dimensions getEmpty()
```


Returnerar en tom Dimensions-instans


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
