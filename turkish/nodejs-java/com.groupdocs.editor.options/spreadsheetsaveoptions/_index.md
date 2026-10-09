---
title: "SpreadsheetSaveOptions"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Spreadsheet Excel uyumlu belgeleri oluşturmak ve kaydetmek için özel seçenekleri belirtmeye izin verir"
type: docs
weight: 37
url: /tr/nodejs-java/com.groupdocs.editor.options/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class SpreadsheetSaveOptions implements ISaveOptions
```

Spreadsheet oluşturmak ve kaydetmek için özel seçenekleri belirtmeye izin verir
(Excel uyumlu) belgeler

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | Bu parametresiz yapıcı, XLSX çıktı formatı ile bir SpreadsheetSaveOptions örneği oluşturur (daha sonra şu şekilde değiştirilebilir |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) özelliği)
|
|  | [SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)](#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-) | Belirtilen zorunlu ile bir SpreadsheetSaveOptions örneği oluşturur |
Spreadsheet çıktı formatı, diğer tüm parametreler varsayılan iken
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPassword()](#getPassword--) | Şifreyi belirtmeye, değiştirmeye, almaya veya kaldırmaya izin verir, bu |
oluşturulan Spreadsheet belgesini kodlamak için kullanılır, eğer bu belge formatı
parola korumasını destekler.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Şifreyi belirtmeye, değiştirmeye, almaya veya kaldırmaya izin verir, bu |
oluşturulan Spreadsheet belgesini kodlamak için kullanılır, eğer bu belge formatı
parola korumasını destekler.
|
|  | [getWorksheetNumber()](#getWorksheetNumber--) | Düzenlenmiş çalışma sayfasını mevcut bir spreadsheet'in kopyasına eklemeye izin verir |
yeni tek-çalışma sayfası spreadsheet'i oluşturmak yerine (varsayılan
davranış).
|
|  | [setWorksheetNumber(int value)](#setWorksheetNumber-int-) | Düzenlenmiş çalışma sayfasını mevcut bir spreadsheet'in kopyasına eklemeye izin verir |
yeni tek-çalışma sayfası spreadsheet'i oluşturmak yerine (varsayılan
davranış).
|
|  | [getInsertAsNewWorksheet()](#getInsertAsNewWorksheet--) | Düzenlenmiş çalışma sayfasının orijinal spreadsheet'teki mevcut çalışma sayfasını değiştirmesi gerektiğini belirten Boolean bayrağı |
orijinal spreadsheet'teki mevcut çalışma sayfasını, belirtilen konumda
bu

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
özellik, ya da mevcut çalışma sayfası ile arasında enjekte edilmelidir
öncekini, içeriğini değiştirmeden.
|
|  | [setInsertAsNewWorksheet(boolean value)](#setInsertAsNewWorksheet-boolean-) | Düzenlenmiş çalışma sayfasının orijinal spreadsheet'teki mevcut çalışma sayfasını değiştirmesi gerektiğini belirten Boolean bayrağı |
orijinal spreadsheet'teki mevcut çalışma sayfasını, belirtilen konumda
bu

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
özellik, ya da mevcut çalışma sayfası ile arasında enjekte edilmelidir
öncekini, içeriğini değiştirmeden.
|
|  | [getOutputFormat()](#getOutputFormat--) | Kaydetmek için kullanılacak bir Spreadsheet biçimi belirtmeye izin verir |
belge
|
|  | [setOutputFormat(SpreadsheetFormats value)](#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-) | Kaydetmek için kullanılacak bir Spreadsheet biçimi belirtmeye izin verir |
belge
|
|  | [getWorksheetProtection()](#getWorksheetProtection--) | Çıktı Spreadsheet için bir çalışma sayfası koruması etkinleştirmeye izin verir |
belge.
|
|  | [setWorksheetProtection(WorksheetProtection value)](#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-) | Çıktı Spreadsheet için bir çalışma sayfası koruması etkinleştirmeye izin verir |
belge.
|
|  | [getWorksheetNumbersToDelete()](#getWorksheetNumbersToDelete--) | Düzenlenen çalışma sayfası mevcut bir Spreadsheet'e eklendiğinde, kaydetme sırasında Spreadsheet'ten silinmesi gereken 1 tabanlı çalışma sayfası numaralarını içeren bir dizi belirtmeye izin verir. |
|
|  | [setWorksheetNumbersToDelete(int[] value)](#setWorksheetNumbersToDelete-int---) | Düzenlenen çalışma sayfası mevcut bir Spreadsheet'e eklendiğinde, kaydetme sırasında Spreadsheet'ten silinmesi gereken 1 tabanlı çalışma sayfası numaralarını içeren bir dizi belirtmeye izin verir. |
|
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


Bu parametresiz yapıcı, XLSX çıktı formatı ile bir SpreadsheetSaveOptions örneği oluşturur (daha sonra şu şekilde değiştirilebilir
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) özelliği)


### SpreadsheetSaveOptions(SpreadsheetFormats outputFormat) {#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)
```


Belirtilen zorunlu ile bir SpreadsheetSaveOptions örneği oluşturur
Spreadsheet çıktı formatı, diğer tüm parametreler varsayılan iken


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | outputFormat | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) | Spreadsheet belgesinin kaydedileceği zorunlu çıktı biçimi |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Şifreyi belirtmeye, değiştirmeye, almaya veya kaldırmaya izin verir, bu
oluşturulan Spreadsheet belgesini kodlamak için kullanılır, eğer bu belge formatı
parola korumasını destekler. Kaldırmak için NULL veya boş dize belirtin
(temizleme) parolayı.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Şifreyi belirtmeye, değiştirmeye, almaya veya kaldırmaya izin verir, bu
oluşturulan Spreadsheet belgesini kodlamak için kullanılır, eğer bu belge formatı
parola korumasını destekler. Kaldırmak için NULL veya boş dize belirtin
(temizleme) parolayı.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getWorksheetNumber() {#getWorksheetNumber--}
```
public final int getWorksheetNumber()
```


Düzenlenmiş çalışma sayfasını mevcut bir spreadsheet'in kopyasına eklemeye izin verir
yeni tek-çalışma sayfası spreadsheet'i oluşturmak yerine (varsayılan
davranış). WorksheetNumber, bir çalışma sayfasının 1 tabanlı numarasıdır
Spreadsheet, Editor sınıfında yüklüdür. Eğer 0 (varsayılan değer) ise,
Yeni bir Spreadsheet, tek düzenlenmiş çalışma sayfası ile oluşturulacaktır. Eğer
sıfırdan büyük ya da küçük ve geçerli bir Spreadsheet mevcutsa, yüklü
Editor sınıfında, giriş tarafından temsil edilen düzenlenmiş çalışma sayfası
EditableDocument örneği, bu Spreadsheet'e eklenecektir.


*** ** * ** ***

> ```
> Given spreadsheet has 5 worksheets:
>  WorksheetNumber  = 0; \u2014 ignore given spreadsheet, create a new spreadsheet and put edited worksheet into it.
>  WorksheetNumber  = 1; \u2014 replace the first worksheet with edited
>  WorksheetNumber  = 2; \u2014 replace the second worksheet with edited
>  WorksheetNumber  = 5; \u2014 replace the last (5th) worksheet with edited
>  WorksheetNumber  = 6; \u2014 replace the last (5th) worksheet with edited, because 6 is greater then 5 and thus is adjusted
>  WorksheetNumber = -1; \u2014 replace the last (5th) worksheet with edited, because "-1" means "last existing"
>  WorksheetNumber = -2; \u2014 replace the 4th worksheet with edited
>  WorksheetNumber = -3; \u2014 replace the 3rd worksheet with edited
>  WorksheetNumber = -4; \u2014 replace the 2nd worksheet with edited
>  WorksheetNumber = -5; \u2014 replace the first worksheet with edited
>  WorksheetNumber = -6; \u2014 replace the first worksheet with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />


*** ** * ** ***

 *WorksheetNumber*  integer property, if it is not in default state (reserved value '0'), represents a worksheet number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last worksheet. Negative values are also allowed and count worksheets from end. For example, "-1" implies last worksheet in a spreadsheet, "-2" \\u2014 last but one, etc. Like with positive values, when negative worksheet number exceeds the total count of worksheets in the given spreadsheet, it will be adjusted to the first worksheet. The  InsertAsNewWorksheet (#getInsertAsNewWorksheet.getInsertAsNewWorksheet/#setInsertAsNewWorksheet(boolean).setInsertAsNewWorksheet(boolean)) boolean property is tightly coupled with this one.

<br />



**Returns:**
int -
### setWorksheetNumber(int value) {#setWorksheetNumber-int-}
```
public final void setWorksheetNumber(int value)
```


Düzenlenmiş çalışma sayfasını mevcut bir spreadsheet'in kopyasına eklemeye izin verir
yeni tek-çalışma sayfası spreadsheet'i oluşturmak yerine (varsayılan
davranış). WorksheetNumber, bir çalışma sayfasının 1 tabanlı numarasıdır
Spreadsheet, Editor sınıfında yüklüdür. Eğer 0 (varsayılan değer) ise,
Yeni bir Spreadsheet, tek düzenlenmiş çalışma sayfası ile oluşturulacaktır. Eğer
sıfırdan büyük ya da küçük ve geçerli bir Spreadsheet mevcutsa, yüklü
Editor sınıfında, giriş tarafından temsil edilen düzenlenmiş çalışma sayfası
EditableDocument örneği, bu Spreadsheet'e eklenecektir.


*** ** * ** ***

> ```
> Given spreadsheet has 5 worksheets:
>  WorksheetNumber  = 0; \u2014 ignore given spreadsheet, create a new spreadsheet and put edited worksheet into it.
>  WorksheetNumber  = 1; \u2014 replace the first worksheet with edited
>  WorksheetNumber  = 2; \u2014 replace the second worksheet with edited
>  WorksheetNumber  = 5; \u2014 replace the last (5th) worksheet with edited
>  WorksheetNumber  = 6; \u2014 replace the last (5th) worksheet with edited, because 6 is greater then 5 and thus is adjusted
>  WorksheetNumber = -1; \u2014 replace the last (5th) worksheet with edited, because "-1" means "last existing"
>  WorksheetNumber = -2; \u2014 replace the 4th worksheet with edited
>  WorksheetNumber = -3; \u2014 replace the 3rd worksheet with edited
>  WorksheetNumber = -4; \u2014 replace the 2nd worksheet with edited
>  WorksheetNumber = -5; \u2014 replace the first worksheet with edited
>  WorksheetNumber = -6; \u2014 replace the first worksheet with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />


*** ** * ** ***

 *WorksheetNumber*  integer property, if it is not in default state (reserved value '0'), represents a worksheet number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last worksheet. Negative values are also allowed and count worksheets from end. For example, "-1" implies last worksheet in a spreadsheet, "-2" \\u2014 last but one, etc. Like with positive values, when negative worksheet number exceeds the total count of worksheets in the given spreadsheet, it will be adjusted to the first worksheet. The  InsertAsNewWorksheet (#getInsertAsNewWorksheet.getInsertAsNewWorksheet/#setInsertAsNewWorksheet(boolean).setInsertAsNewWorksheet(boolean)) boolean property is tightly coupled with this one.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getInsertAsNewWorksheet() {#getInsertAsNewWorksheet--}
```
public final boolean getInsertAsNewWorksheet()
```


Düzenlenmiş çalışma sayfasının orijinal spreadsheet'teki mevcut çalışma sayfasını değiştirmesi gerektiğini belirten Boolean bayrağı
orijinal spreadsheet'teki mevcut çalışma sayfasını, belirtilen konumda
bu

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
özellik, ya da mevcut çalışma sayfası ile arasında enjekte edilmelidir
öncekini, içeriğini değiştirmeden. Varsayılan olarak false \u2014
mevcut çalışma sayfası değiştirilecektir. Bu özellik, değer
de

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
özellik '0' olarak ayarlanmışsa.


*** ** * ** ***

Varsayılan olarak çalışma sayfası değiştirilir. Bu, verilen Spreadsheet'in 5 çalışma sayfası olduğu ve WorksheetNumber (#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))=4 olduğu durumda, 4. çalışma sayfasının yeni düzenlenmiş çalışma sayfası ile değiştirileceği, ancak Spreadsheet'teki toplam çalışma sayfası sayısının (5) dokunulmaz kalacağı anlamına gelir. Ancak, bu özelliğin değeri *true* olarak ayarlanırsa, yeni düzenlenmiş çalışma sayfası 4. çalışma sayfası olarak enjekte edilir ve sonraki tüm çalışma sayfaları sona kaydırılır: \"old\" 4. çalışma sayfası 5. olur, 5. çalışma sayfası 6. olur ve Spreadsheet'teki toplam çalışma sayfası sayısı bir artarak 6 olur.

<br />



**Returns:**
boolean -
### setInsertAsNewWorksheet(boolean value) {#setInsertAsNewWorksheet-boolean-}
```
public final void setInsertAsNewWorksheet(boolean value)
```


Düzenlenmiş çalışma sayfasının orijinal spreadsheet'teki mevcut çalışma sayfasını değiştirmesi gerektiğini belirten Boolean bayrağı
orijinal spreadsheet'teki mevcut çalışma sayfasını, belirtilen konumda
bu

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
özellik, ya da mevcut çalışma sayfası ile arasında enjekte edilmelidir
öncekini, içeriğini değiştirmeden. Varsayılan olarak false \u2014
mevcut çalışma sayfası değiştirilecektir. Bu özellik, değer
de

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
özellik '0' olarak ayarlanmışsa.


*** ** * ** ***

Varsayılan olarak çalışma sayfası değiştirilir. Bu, verilen Spreadsheet'in 5 çalışma sayfası olduğu ve WorksheetNumber (#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))=4 olduğu durumda, 4. çalışma sayfasının yeni düzenlenmiş çalışma sayfası ile değiştirileceği, ancak Spreadsheet'teki toplam çalışma sayfası sayısının (5) dokunulmaz kalacağı anlamına gelir. Ancak, bu özelliğin değeri *true* olarak ayarlanırsa, yeni düzenlenmiş çalışma sayfası 4. çalışma sayfası olarak enjekte edilir ve sonraki tüm çalışma sayfaları sona kaydırılır: \"old\" 4. çalışma sayfası 5. olur, 5. çalışma sayfası 6. olur ve Spreadsheet'teki toplam çalışma sayfası sayısı bir artarak 6 olur.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final SpreadsheetFormats getOutputFormat()
```


Kaydetmek için kullanılacak bir Spreadsheet biçimi belirtmeye izin verir
belge


**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - 
### setOutputFormat(SpreadsheetFormats value) {#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public final void setOutputFormat(SpreadsheetFormats value)
```


Kaydetmek için kullanılacak bir Spreadsheet biçimi belirtmeye izin verir
belge


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) |  |

### getWorksheetProtection() {#getWorksheetProtection--}
```
public final WorksheetProtection getWorksheetProtection()
```


Çıktı Spreadsheet için bir çalışma sayfası koruması etkinleştirmeye izin verir
belge. Varsayılan olarak NULL - koruma uygulanmaz. Tüm formatlar
çalışma sayfası korumasını destekler.


**Returns:**
[WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) - 
### setWorksheetProtection(WorksheetProtection value) {#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-}
```
public final void setWorksheetProtection(WorksheetProtection value)
```


Çıktı Spreadsheet için bir çalışma sayfası koruması etkinleştirmeye izin verir
belge. Varsayılan olarak NULL - koruma uygulanmaz. Tüm formatlar
çalışma sayfası korumasını destekler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) |  |

### getWorksheetNumbersToDelete() {#getWorksheetNumbersToDelete--}
```
public final int[] getWorksheetNumbersToDelete()
```


Kaydetme sırasında Spreadsheet'ten silinmesi gereken 1 tabanlı çalışma sayfası numaralarını içeren bir dizi belirtmeye izin verir; bu, düzenlenmiş çalışma sayfası mevcut bir Spreadsheet'e eklendiğinde geçerlidir. Düzenlenmiş çalışma sayfası yeni tek çalışma sayfası Spreadsheet'i olarak (varsayılan davranış) kaydedilmek yerine, mevcut bir Spreadsheet'e (#getWorksheetNumber().getWorksheetNumber() / #setWorksheetNumber(int).setWorksheetNumber(int) kullanılarak) kaydedildiğinde, bu dizi içinde numaraları belirterek bu Spreadsheet'ten belirli çalışma sayfalarını silmek de mümkündür. Varsayılan olarak bu dizi null \u2014 hiçbir çalışma sayfası silinmez. Ancak dizi null değil ve boş değilse ve en az bir geçerli çalışma sayfası numarası içeriyorsa, düzenlenmiş çalışma sayfasının içeriğiyle çıktı Spreadsheet belgesi oluşturulduktan sonra, belirtilen numaralı çalışma sayfaları, içeriği çıktı akışına veya dosyaya yazılmadan hemen önce Spreadsheet'ten silinecektir. Bu dizideki çalışma sayfası numaraları 1 tabanlıdır, 0 tabanlı değildir. Geçersiz numaralar (1'den küçük veya toplam çalışma sayfası sayısından büyük) yok sayılacaktır.


**Returns:**
int[] - Silinecek 1 tabanlı çalışma sayfası numaralarının dizisi, ya da hiçbir şey silinmemesi durumunda  null  .

### setWorksheetNumbersToDelete(int[] value) {#setWorksheetNumbersToDelete-int---}
```
public final void setWorksheetNumbersToDelete(int[] value)
```


Kaydedilirken, düzenlenen çalışma sayfası mevcut bir çalışma sayfasına eklendiğinde, elektronik tablo üzerinden silinmesi gereken 1 tabanlı çalışma sayfası numaralarını içeren bir dizi belirtmeye izin verir. Bu dizideki çalışma sayfası numaraları 1 tabanlıdır. Geçersiz numaralar yok sayılacaktır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int[] | Silinecek 1 tabanlı çalışma sayfası numaralarının dizisi (  null  veya boş olabilir). |
|

