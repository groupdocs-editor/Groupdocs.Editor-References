---
title: "Boyutlar"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Bir raster dikdörtgen görüntünün genişlik ve yükseklik lineer boyutlarını keyfi bir birimde temsil eder."
type: docs
weight: 10
url: /tr/java/com.groupdocs.editor.htmlcss.resources.images/dimensions/
---
**Inheritance:**
java.lang.Object
```
public class Dimensions
```

Bir raster dikdörtgenin (genişlik ve yükseklik) lineer boyutlarını temsil eder
keyfi bir birimde görüntü. Değiştirilemez yapı.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [Dimensions(int width, int height)](#Dimensions-int-int-) | Belirtilen genişlik ve yükseklikten yeni bir örnek oluşturur |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getWidth()](#getWidth--) | Görüntünün genişliğini döndürür |
|
|  | [getHeight()](#getHeight--) | Görüntünün yüksekliğini döndürür |
|
|  | [isSquare()](#isSquare--) | Belirtilen 'Dimensions' öğesinin kare olup olmadığını belirler, yani |
|
|  | [getArea()](#getArea--) | Bir alan döndürür (Genişlik x Yükseklik) |
|
|  | [isEmpty()](#isEmpty--) | Bu "Dimensions" örneğinin boş ve varsayılan olup olmadığını belirler, yani |
|
|  | [getAspectRatio()](#getAspectRatio--) | Bu boyutların en‑boy oranı genişlik/yükseklik olarak |
|
|  | [proportionallyResizeForNewWidth(int targetWidth)](#proportionallyResizeForNewWidth-int-) | Orantılı olarak yeni bir "Dimensions" örneği oluşturur ve döndürür |
Mevcut örnekten, belirtilen genişliğe göre yeniden boyutlandırılır
|
|  | [proportionallyResizeForNewHeight(int targetHeight)](#proportionallyResizeForNewHeight-int-) | Orantılı olarak yeni bir "Dimensions" örneği oluşturur ve döndürür |
Mevcut örnekten, belirtilen yüksekliğe göre yeniden boyutlandırılır
|
|  | [equals(Dimensions other)](#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Bu örneğin belirtilen "Dimensions" ile eşit olup olmadığını belirler |
örnek
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bu örneğin belirtilen tip dönüştürülmemiş nesne ile eşit olup olmadığını belirler, |
muhtemelen başka bir "Dimensions" örneği
|
|  | [hashCode()](#hashCode--) | Bu örnek için bir hashcode döndürür, bu hashcode örnek ömrü boyunca değiştirilemez |
ömür
|
|  | [op_Equality(Dimensions first, Dimensions second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | İki "Dimensions" değerinin eşit olup olmadığını kontrol eder, yani |
|
|  | [op_Inequality(Dimensions first, Dimensions second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | İki "Dimensions" değerinin eşit olmamasını kontrol eder, yani |
|
|  | [toString()](#toString--) | Bu "Dimensions" öğesinin dize temsilini döndürür |
|
|  | [deepClone()](#deepClone--) | Bu örneğin tam bir kopyasını döndürür |
|
|  | [getEmpty()](#getEmpty--) | Boş bir Dimensions örneği döndürür |
|
### Dimensions(int width, int height) {#Dimensions-int-int-}
```
public Dimensions(int width, int height)
```


Belirtilen genişlik ve yükseklikten yeni bir örnek oluşturur


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | genişlik | int | Görüntünün genişliği |
|
|  | yükseklik | int | Görüntünün yüksekliği |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Görüntünün genişliğini döndürür


**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Görüntünün yüksekliğini döndürür


**Returns:**
int
### isSquare() {#isSquare--}
```
public final boolean isSquare()
```


Belirtilen 'Dimensions' öğesinin kare olup olmadığını belirler, yani eğer
genişlik yüksekliğe eşittir


**Returns:**
boolean
### getArea() {#getArea--}
```
public final long getArea()
```


Bir alan döndürür (Genişlik x Yükseklik)


**Returns:**
long
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Bu "Dimensions" örneğinin boş ve varsayılan olup olmadığını belirler, yani
doğru genişlik ve yüksekliği depolamıyor


**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Bu boyutların en‑boy oranı genişlik/yükseklik olarak


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### proportionallyResizeForNewWidth(int targetWidth) {#proportionallyResizeForNewWidth-int-}
```
public final Dimensions proportionallyResizeForNewWidth(int targetWidth)
```


Orantılı olarak yeni bir "Dimensions" örneği oluşturur ve döndürür
Mevcut örnekten, belirtilen genişliğe göre yeniden boyutlandırılır


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | targetWidth | int | Yeni hedef genişlik, sonuçta oluşan Dimension içinde bulunacak |
|

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target width and proportionally resized height

### proportionallyResizeForNewHeight(int targetHeight) {#proportionallyResizeForNewHeight-int-}
```
public final Dimensions proportionallyResizeForNewHeight(int targetHeight)
```


Orantılı olarak yeni bir "Dimensions" örneği oluşturur ve döndürür
Mevcut örnekten, belirtilen yüksekliğe göre yeniden boyutlandırılır


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | targetHeight | int | Yeni hedef yükseklik, sonuçta oluşan Dimension içinde bulunacak |
|

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target height and proportionally resized width

### equals(Dimensions other) {#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public final boolean equals(Dimensions other)
```


Bu örneğin belirtilen "Dimensions" ile eşit olup olmadığını belirler
örnek


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Eşitliği kontrol etmek için diğer "Dimensions" örneği |
|

**Returns:**
boolean - Eşitse true, eşit değilse false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu örneğin belirtilen tip dönüştürülmemiş nesne ile eşit olup olmadığını belirler,
muhtemelen başka bir "Dimensions" örneği


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | obj | java.lang.Object | Bu nesneyle eşitliği kontrol edilmesi gereken, muhtemelen "Dimensions" tipinde olan diğer nesne |
|

**Returns:**
boolean - Eşitse true, eşit değilse false

### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu örnek için bir hashcode döndürür, bu hashcode örnek ömrü boyunca değiştirilemez
ömür


**Returns:**
int - Bu örnek için değiştirilemez (immutable) imzalı 4 baytlık tamsayı hash kodu

### op_Equality(Dimensions first, Dimensions second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Equality(Dimensions first, Dimensions second)
```


İki "Dimensions" değerinin eşit olup olmadığını kontrol eder, yani eşit
genişlik ve yükseklik, ya da ikisi de boş


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Kontrol edilecek ilk örnek |
|
|  | second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Kontrol edilecek ikinci örnek |
|

**Returns:**
boolean - Eşitse true, eşit değilse false

### op_Inequality(Dimensions first, Dimensions second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Inequality(Dimensions first, Dimensions second)
```


İki "Dimensions" değerinin eşit olmamasını kontrol eder, yani onların
ilgili genişlik ve/veya yükseklik farklıdır


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Kontrol edilecek ilk örnek |
|
|  | second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Kontrol edilecek ikinci örnek |
|

**Returns:**
boolean - Eşit değilse true, eşitse false

### toString() {#toString--}
```
public String toString()
```


Bu "Dimensions" öğesinin dize temsilini döndürür

*** ** * ** ***


> ```
> W640×H480
> ```

<br />



**Returns:**
java.lang.String - W:(width)×H:(height) formatında genişlik ve yükseklik içeren String örneği

### deepClone() {#deepClone--}
```
public final Dimensions deepClone()
```


Bu örneğin tam bir kopyasını döndürür


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New instance, that is a full and deep copy of this one

### getEmpty() {#getEmpty--}
```
public static Dimensions getEmpty()
```


Boş bir Dimensions örneği döndürür


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
