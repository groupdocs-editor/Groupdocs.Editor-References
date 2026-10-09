---
title: "Abmessungen"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Stellt die linearen Abmessungen Breite und Höhe eines rasterförmigen rechteckigen Bildes in einer beliebigen Einheit dar."
type: docs
weight: 10
url: /de/nodejs-java/com.groupdocs.editor.htmlcss.resources.images/dimensions/
---
**Inheritance:**
java.lang.Object
```
public class Dimensions
```

Stellt die linearen Abmessungen (Breite und Höhe) eines rasterförmigen rechteckigen
Bild in einer beliebigen Einheit. Unveränderliche Struktur.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [Dimensions(int width, int height)](#Dimensions-int-int-) | Erstellt eine neue Instanz aus der angegebenen Breite und Höhe |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getWidth()](#getWidth--) | Gibt die Breite des Bildes zurück |
|
|  | [getHeight()](#getHeight--) | Gibt die Höhe des Bildes zurück |
|
|  | [isSquare()](#isSquare--) | Bestimmt, ob die angegebene 'Dimensions' ein Quadrat darstellt, d. h. |
|
|  | [getArea()](#getArea--) | Gibt eine Fläche zurück (Breite x Höhe) |
|
|  | [isEmpty()](#isEmpty--) | Bestimmt, ob diese "Dimensions"-Instanz leer und standardmäßig ist, d. h. |
|
|  | [getAspectRatio()](#getAspectRatio--) | Seitenverhältnis dieser Dimensionen als Breite/Höhe |
|
|  | [proportionallyResizeForNewWidth(int targetWidth)](#proportionallyResizeForNewWidth-int-) | Erstellt und gibt eine neue "Dimensions"-Instanz zurück, die proportional ist |
Aus der aktuellen Größe basierend auf der angegebenen Breite skaliert
|
|  | [proportionallyResizeForNewHeight(int targetHeight)](#proportionallyResizeForNewHeight-int-) | Erstellt und gibt eine neue "Dimensions"-Instanz zurück, die proportional ist |
Aus der aktuellen Größe basierend auf der angegebenen Höhe skaliert
|
|  | [equals(Dimensions other)](#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Bestimmt, ob diese Instanz gleich der angegebenen "Dimensions" ist |
Instanz
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob diese Instanz mit dem angegebenen nicht gecasteten Objekt gleich ist, |
die vermutlich eine andere "Dimensions"-Instanz ist
|
|  | [hashCode()](#hashCode--) | Gibt einen Hashcode für diese Instanz zurück, der während ihrer |
Lebensdauer
|
|  | [op_Equality(Dimensions first, Dimensions second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Prüft, ob zwei "Dimensions"-Werte gleich sind, d. h. |
|
|  | [op_Inequality(Dimensions first, Dimensions second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Prüft, ob zwei "Dimensions"-Werte ungleich sind, d. h. |
|
|  | [toString()](#toString--) | Gibt eine String-Darstellung dieser "Dimensions" zurück |
|
|  | [deepClone()](#deepClone--) | Gibt eine vollständige Kopie dieser Instanz zurück |
|
|  | [getEmpty()](#getEmpty--) | Gibt eine leere Dimensions-Instanz zurück |
|
### Dimensions(int width, int height) {#Dimensions-int-int-}
```
public Dimensions(int width, int height)
```


Erstellt eine neue Instanz aus der angegebenen Breite und Höhe


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Breite | int | Breite des Bildes |
|
|  | Höhe | int | Höhe des Bildes |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Gibt die Breite des Bildes zurück


**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Gibt die Höhe des Bildes zurück


**Returns:**
int
### isSquare() {#isSquare--}
```
public final boolean isSquare()
```


Bestimmt, ob das angegebene 'Dimensions' ein Quadrat darstellt, d. h. wenn
Breite ist gleich Höhe


**Returns:**
boolesch
### getArea() {#getArea--}
```
public final long getArea()
```


Gibt eine Fläche zurück (Breite x Höhe)


**Returns:**
long
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Bestimmt, ob diese "Dimensions"-Instanz leer und standardmäßig ist, d. h.
es speichert nicht die korrekte Breite und Höhe


**Returns:**
boolesch
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Seitenverhältnis dieser Dimensionen als Breite/Höhe


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### proportionallyResizeForNewWidth(int targetWidth) {#proportionallyResizeForNewWidth-int-}
```
public final Dimensions proportionallyResizeForNewWidth(int targetWidth)
```


Erstellt und gibt eine neue "Dimensions"-Instanz zurück, die proportional ist
Aus der aktuellen Größe basierend auf der angegebenen Breite skaliert


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | targetWidth | int | Neue Zielbreite, die im resultierenden Dimension vorhanden sein wird |
|

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target width and proportionally resized height

### proportionallyResizeForNewHeight(int targetHeight) {#proportionallyResizeForNewHeight-int-}
```
public final Dimensions proportionallyResizeForNewHeight(int targetHeight)
```


Erstellt und gibt eine neue "Dimensions"-Instanz zurück, die proportional ist
Aus der aktuellen Größe basierend auf der angegebenen Höhe skaliert


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | targetHeight | int | Neue Zielhöhe, die im resultierenden Dimension vorhanden sein wird |
|

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target height and proportionally resized width

### equals(Dimensions other) {#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public final boolean equals(Dimensions other)
```


Bestimmt, ob diese Instanz gleich der angegebenen "Dimensions" ist
Instanz


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Andere "Dimensions"-Instanz zum Prüfen auf Gleichheit |
|

**Returns:**
boolescher Wert - wahr, wenn gleich, falsch, wenn ungleich

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob diese Instanz mit dem angegebenen nicht gecasteten Objekt gleich ist,
die vermutlich eine andere "Dimensions"-Instanz ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | obj | java.lang.Object | Anderes Objekt, das vermutlich vom Typ "Dimensions" ist und auf Gleichheit mit diesem geprüft werden sollte |
|

**Returns:**
boolescher Wert - wahr, wenn gleich, falsch, wenn ungleich

### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode für diese Instanz zurück, der während ihrer
Lebensdauer


**Returns:**
int – Unveränderlicher (für diese Instanz) Hashcode als vorzeichenbehaftete 4‑Byte‑Ganzzahl

### op_Equality(Dimensions first, Dimensions second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Equality(Dimensions first, Dimensions second)
```


Überprüft, ob zwei "Dimensions"‑Werte gleich sind, d. h. sie haben gleiche
Breite und Höhe, oder beide sind leer


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Erste zu prüfende Instanz |
|
|  | second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Zweite zu prüfende Instanz |
|

**Returns:**
boolescher Wert - wahr, wenn gleich, falsch, wenn ungleich

### op_Inequality(Dimensions first, Dimensions second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Inequality(Dimensions first, Dimensions second)
```


Überprüft, ob zwei "Dimensions"‑Werte ungleich sind, d. h. ihre
entsprechende Breite und/oder Höhe unterschiedlich sind


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Erste zu prüfende Instanz |
|
|  | second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Zweite zu prüfende Instanz |
|

**Returns:**
boolescher Wert – True, wenn ungleich, false, wenn gleich

### toString() {#toString--}
```
public String toString()
```


Gibt eine String-Darstellung dieser "Dimensions" zurück

*** ** * ** ***


> ```
> W640×H480
> ```

<br />



**Returns:**
java.lang.String – String‑Instanz, die eine Breite und Höhe im Format W:(width)×H:(height) enthält

### deepClone() {#deepClone--}
```
public final Dimensions deepClone()
```


Gibt eine vollständige Kopie dieser Instanz zurück


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New instance, that is a full and deep copy of this one

### getEmpty() {#getEmpty--}
```
public static Dimensions getEmpty()
```


Gibt eine leere Dimensions-Instanz zurück


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
