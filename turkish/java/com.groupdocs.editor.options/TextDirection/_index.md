---
title: "TextDirection"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Düz metin belgelerinde metin yönünün nasıl ele alınacağına dair 3 olası varyantı temsil eder."
type: docs
weight: 38
url: /tr/java/com.groupdocs.editor.options/textdirection/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextDirection extends System.Enum
```

Düz metinde metin yönünün nasıl ele alınacağına dair 3 olası varyantı temsil eder.
belgeler

## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [LeftToRight](#LeftToRight) | Soldan sağa yön, normal metin, varsayılan değer. |
|
|  | [RightToLeft](#RightToLeft) | Sağdan sola yön |
|
|  | [Auto](#Auto) | Yönü otomatik algıla. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTextDirection()](#getTextDirection--) |  |
### LeftToRight {#LeftToRight}
```
public static final int LeftToRight
```


Soldan sağa yön, normal metin, varsayılan değer.


### RightToLeft {#RightToLeft}
```
public static final int RightToLeft
```


Sağdan sola yön


### Auto {#Auto}
```
public static final int Auto
```


Yönü otomatik algıla. Bu seçenek seçildiğinde ve metin içerdiğinde
RTL betiklerine ait karakterler, belge yönü ayarlanacaktır
otomatik olarak RTL'ye.


### getTextDirection() {#getTextDirection--}
```
public static int[] getTextDirection()
```




**Returns:**
int[]
