---
title: "Dimensies"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt de lineaire afmetingen breedte en hoogte van één raster rechthoekige afbeelding voor in een willekeurige eenheid."
type: docs
weight: 10
url: /nl/java/com.groupdocs.editor.htmlcss.resources.images/dimensions/
---
**Inheritance:**
java.lang.Object
```
public class Dimensions
```

Stelt de lineaire afmetingen (breedte en hoogte) van één raster rechthoekig voor
afbeelding in willekeurige eenheid. Immutable struct.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [Dimensions(int width, int height)](#Dimensions-int-int-) | Maakt een nieuw exemplaar aan op basis van opgegeven breedte en hoogte |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getWidth()](#getWidth--) | Geeft de breedte van de afbeelding terug |
|
|  | [getHeight()](#getHeight--) | Geeft de hoogte van de afbeelding terug |
|
|  | [isSquare()](#isSquare--) | Bepaalt of de opgegeven 'Dimensions' een vierkant vertegenwoordigt, d.w.z. |
|
|  | [getArea()](#getArea--) | Geeft een oppervlakte terug (Breedte x Hoogte) |
|
|  | [isEmpty()](#isEmpty--) | Bepaalt of deze "Dimensions"-instantie leeg en standaard is, d.w.z. |
|
|  | [getAspectRatio()](#getAspectRatio--) | Beeldverhouding van deze afmetingen als breedte/hoogte |
|
|  | [proportionallyResizeForNewWidth(int targetWidth)](#proportionallyResizeForNewWidth-int-) | Maakt een nieuwe "Dimensions"-instantie aan en retourneert deze, die proportioneel |
geschaald vanaf de huidige, gebaseerd op opgegeven breedte
|
|  | [proportionallyResizeForNewHeight(int targetHeight)](#proportionallyResizeForNewHeight-int-) | Maakt een nieuwe "Dimensions"-instantie aan en retourneert deze, die proportioneel |
geschaald vanaf de huidige, gebaseerd op opgegeven hoogte
|
|  | [equals(Dimensions other)](#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Bepaalt of deze instantie gelijk is aan de opgegeven "Dimensions" |
instantie
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of deze instantie gelijk is aan het opgegeven niet-gecastte object, |
wat vermoedelijk een andere "Dimensions"-instantie is
|
|  | [hashCode()](#hashCode--) | Retourneert een hashcode voor deze instantie, die niet kan worden gewijzigd tijdens zijn |
levensduur
|
|  | [op_Equality(Dimensions first, Dimensions second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Controleert of twee "Dimensions"-waarden gelijk zijn, d.w.z. |
|
|  | [op_Inequality(Dimensions first, Dimensions second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Controleert of twee "Dimensions"-waarden niet gelijk zijn, d.w.z. |
|
|  | [toString()](#toString--) | Geeft een tekenreeksrepresentatie van deze "Dimensions" terug |
|
|  | [deepClone()](#deepClone--) | Geeft een volledige kopie van deze instantie terug |
|
|  | [getEmpty()](#getEmpty--) | Geeft een lege Dimensions‑instantie terug |
|
### Dimensions(int width, int height) {#Dimensions-int-int-}
```
public Dimensions(int width, int height)
```


Maakt een nieuw exemplaar aan op basis van opgegeven breedte en hoogte


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | breedte | int | Breedte van afbeelding |
|
|  | hoogte | int | Hoogte van afbeelding |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Geeft de breedte van de afbeelding terug


**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Geeft de hoogte van de afbeelding terug


**Returns:**
int
### isSquare() {#isSquare--}
```
public final boolean isSquare()
```


Bepaalt of de opgegeven 'Dimensions' een vierkant vertegenwoordigt, d.w.z. als
breedte is gelijk aan hoogte


**Returns:**
boolean
### getArea() {#getArea--}
```
public final long getArea()
```


Geeft een oppervlakte terug (Breedte x Hoogte)


**Returns:**
long
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Bepaalt of deze "Dimensions"-instantie leeg en standaard is, d.w.z.
het slaat geen correcte breedte en hoogte op


**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Beeldverhouding van deze afmetingen als breedte/hoogte


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### proportionallyResizeForNewWidth(int targetWidth) {#proportionallyResizeForNewWidth-int-}
```
public final Dimensions proportionallyResizeForNewWidth(int targetWidth)
```


Maakt een nieuwe "Dimensions"-instantie aan en retourneert deze, die proportioneel
geschaald vanaf de huidige, gebaseerd op opgegeven breedte


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | targetWidth | int | Nieuwe doelbreedte, die aanwezig zal zijn in de resulterende Dimension |
|

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target width and proportionally resized height

### proportionallyResizeForNewHeight(int targetHeight) {#proportionallyResizeForNewHeight-int-}
```
public final Dimensions proportionallyResizeForNewHeight(int targetHeight)
```


Maakt een nieuwe "Dimensions"-instantie aan en retourneert deze, die proportioneel
geschaald vanaf de huidige, gebaseerd op opgegeven hoogte


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | targetHeight | int | Nieuwe doelhoogte, die aanwezig zal zijn in de resulterende Dimension |
|

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target height and proportionally resized width

### equals(Dimensions other) {#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public final boolean equals(Dimensions other)
```


Bepaalt of deze instantie gelijk is aan de opgegeven "Dimensions"
instantie


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Andere "Dimensions"-instantie om op gelijkheid te controleren |
|

**Returns:**
boolean - True als ze gelijk zijn, false als ze niet gelijk zijn

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of deze instantie gelijk is aan het opgegeven niet-gecastte object,
wat vermoedelijk een andere "Dimensions"-instantie is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | obj | java.lang.Object | Ander object, dat vermoedelijk van het type "Dimensions" is, dat op gelijkheid met dit moet worden gecontroleerd |
|

**Returns:**
boolean - True als ze gelijk zijn, false als ze niet gelijk zijn

### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert een hashcode voor deze instantie, die niet kan worden gewijzigd tijdens zijn
levensduur


**Returns:**
int - Onveranderlijke (voor deze instantie) hashcode als ondertekende 4-byte integer

### op_Equality(Dimensions first, Dimensions second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Equality(Dimensions first, Dimensions second)
```


Controleert of twee "Dimensions"-waarden gelijk zijn, d.w.z. ze hebben gelijke
breedte en hoogte, of beide zijn leeg


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Eerste instantie om te controleren |
|
|  | second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Tweede instantie om te controleren |
|

**Returns:**
boolean - True als ze gelijk zijn, false als ze niet gelijk zijn

### op_Inequality(Dimensions first, Dimensions second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Inequality(Dimensions first, Dimensions second)
```


Controleert of twee "Dimensions"-waarden niet gelijk zijn, d.w.z. hun
bijbehorende breedte en/of hoogte verschillen


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Eerste instantie om te controleren |
|
|  | second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Tweede instantie om te controleren |
|

**Returns:**
boolean - True als ze ongelijk zijn, false als ze gelijk zijn

### toString() {#toString--}
```
public String toString()
```


Geeft een tekenreeksrepresentatie van deze "Dimensions" terug

*** ** * ** ***


> ```
> W640×H480
> ```

<br />



**Returns:**
java.lang.String - String‑instantie, die een breedte en hoogte bevat in het formaat W:(width)×H:(height)

### deepClone() {#deepClone--}
```
public final Dimensions deepClone()
```


Geeft een volledige kopie van deze instantie terug


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New instance, that is a full and deep copy of this one

### getEmpty() {#getEmpty--}
```
public static Dimensions getEmpty()
```


Geeft een lege Dimensions‑instantie terug


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
