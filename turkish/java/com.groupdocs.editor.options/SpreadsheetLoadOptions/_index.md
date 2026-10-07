---
title: "SpreadsheetLoadOptions"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "XLSX, ODS vb. gibi Excel uyumlu ikili Spreadsheet Cells belgelerini yüklemek için seçenekler içerir."
type: docs
weight: 36
url: /tr/java/com.groupdocs.editor.options/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class SpreadsheetLoadOptions implements ILoadOptions
```

İkili Spreadsheet (Cells, Excel uyumlu) yüklemek için seçenekler içerir
XLS(X), ODS vb. gibi belgeleri Editor sınıfına

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | Parametresiz varsayılan yapıcı - tüm parametrelerin varsayılan değerleri vardır |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPassword()](#getPassword--) | Şifreyi belirtmeye, değiştirmeye ve elde etmeye olanak tanır, bu şifre |
Spreadsheet belgesi açılırken, eğer kodlanmışsa.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Şifreyi belirtmeye, değiştirmeye ve elde etmeye olanak tanır, bu şifre |
Spreadsheet belgesi açılırken, eğer kodlanmışsa.
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Girdi belge işleme sırasında bellek optimizasyon mekanizmalarını etkinleştirir, |
bu, bazı özel durumlarda performansı düşürebilir, ancak diğer yandan
elle bellek kullanımını azalt.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Girdi belge işleme sırasında bellek optimizasyon mekanizmalarını etkinleştirir, |
bu, bazı özel durumlarda performansı düşürebilir, ancak diğer yandan
elle bellek kullanımını azalt.
|
### SpreadsheetLoadOptions() {#SpreadsheetLoadOptions--}
```
public SpreadsheetLoadOptions()
```


Parametresiz varsayılan yapıcı - tüm parametrelerin varsayılan değerleri vardır


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Şifreyi belirtmeye, değiştirmeye ve elde etmeye olanak tanır, bu şifre
Spreadsheet belgesi açılırken, eğer kodlanmışsa. NULL veya boş olarak ayarlayın.
parola kullanılmaması için dize (varsayılan değer).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Şifreyi belirtmeye, değiştirmeye ve elde etmeye olanak tanır, bu şifre
Spreadsheet belgesi açılırken, eğer kodlanmışsa. NULL veya boş olarak ayarlayın.
parola kullanılmaması için dize (varsayılan değer).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Girdi belge işleme sırasında bellek optimizasyon mekanizmalarını etkinleştirir,
bu, bazı özel durumlarda performansı düşürebilir, ancak diğer yandan
elle bellek kullanımını azalt. Büyük belgeler işlenirken faydalıdır ve
OutOfMemoryException ile karşılaşıldığında. Varsayılan değer false'tur (bellek optimizasyonu
daha iyi performans için devre dışı bırakılmıştır).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Girdi belge işleme sırasında bellek optimizasyon mekanizmalarını etkinleştirir,
bu, bazı özel durumlarda performansı düşürebilir, ancak diğer yandan
elle bellek kullanımını azalt. Büyük belgeler işlenirken faydalıdır ve
OutOfMemoryException ile karşılaşıldığında. Varsayılan değer false'tur (bellek optimizasyonu
daha iyi performans için devre dışı bırakılmıştır).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

