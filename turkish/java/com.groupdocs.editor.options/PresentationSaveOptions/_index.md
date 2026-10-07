---
title: "PresentationSaveOptions"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Presentation PowerPoint uyumlu belgeleri oluşturmak ve kaydetmek için özel seçenekleri belirtmeye olanak tanır."
type: docs
weight: 34
url: /tr/java/com.groupdocs.editor.options/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PresentationSaveOptions implements ISaveOptions
```

Presentation oluşturmak ve kaydetmek için özel seçenekleri belirtmeye olanak tanır.
(PowerPoint uyumlu) belgeler

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [PresentationSaveOptions()](#PresentationSaveOptions--) | Bu parametresiz yapıcı, PPTX çıktı formatı ile yeni bir PresentationSaveOptions örneği oluşturur (daha sonra şu şekilde değiştirilebilir |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)) özelliği)
|
|  | [PresentationSaveOptions(PresentationFormats outputFormat)](#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-) | Belirtilen ile yeni bir PresentationSaveOptions örneği oluşturur |
zorunlu Presentation çıktı formatı, diğer tüm parametreler ise
varsayılan
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPassword()](#getPassword--) | Şifreyi belirtmeye, değiştirmeye ve elde etmeye olanak tanır, bu şifre |
sonuç Presentation belgesini kodlarken.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Sonuç Presentation belgesini kodlamak için kullanılacak şifreyi belirtmeye, değiştirmeye ve almaya olanak tanır. |
|
|  | [getSlideNumber()](#getSlideNumber--) | Yeni tek slaytlı bir sunum oluşturmak yerine düzenlenmiş slaytı mevcut sunuma eklemeye olanak tanır (varsayılan davranış). |
|
|  | [setSlideNumber(int value)](#setSlideNumber-int-) | Yeni tek slaytlı bir sunum oluşturmak yerine düzenlenmiş slaytı mevcut sunuma eklemeye olanak tanır (varsayılan davranış). |
|
|  | [getInsertAsNewSlide()](#getInsertAsNewSlide--) | Düzenlenmiş slaytın, orijinal sunumdaki mevcut slaytı belirtilen konumda değiştirip değiştirmeyeceğini belirten Boolean bayrağı, konumu şu şekilde belirten |
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) özelliği, ya da mevcut slayt ile öncekisi arasına, içeriğini değiştirmeden eklenmelidir.
|
|  | [setInsertAsNewSlide(boolean value)](#setInsertAsNewSlide-boolean-) | Düzenlenmiş slaytın, orijinal sunumdaki mevcut slaytı belirtilen konumda değiştirip değiştirmeyeceğini belirten Boolean bayrağı, konumu şu şekilde belirten |
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) özelliği, ya da mevcut slayt ile öncekisi arasına, içeriğini değiştirmeden eklenmelidir.
|
|  | [getOutputFormat()](#getOutputFormat--) | Belgeyi kaydetmek için kullanılacak bir Presentation formatını belirtmeye olanak tanır |
|
|  | [setOutputFormat(PresentationFormats value)](#setOutputFormat-com.groupdocs.editor.formats.PresentationFormats-) | Belgeyi kaydetmek için kullanılacak bir Presentation formatını belirtmeye olanak tanır |
|
|  | [getSlideNumbersToDelete()](#getSlideNumbersToDelete--) | Düzenlenmiş slayt mevcut sunuma eklendiğinde, kaydetme sırasında sunumdan silinmesi gereken 1 tabanlı slayt numaralarını içeren bir dizi belirtmeye olanak tanır. |
|
|  | [setSlideNumbersToDelete(int[] value)](#setSlideNumbersToDelete-int---) | Düzenlenmiş slayt mevcut sunuma eklendiğinde, kaydetme sırasında sunumdan silinmesi gereken 1 tabanlı slayt numaralarını içeren bir dizi belirtmeye olanak tanır. |
|
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


Bu parametresiz yapıcı, PPTX çıktı formatı ile yeni bir PresentationSaveOptions örneği oluşturur (daha sonra şu şekilde değiştirilebilir
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)) özelliği)


### PresentationSaveOptions(PresentationFormats outputFormat) {#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-}
```
public PresentationSaveOptions(PresentationFormats outputFormat)
```


Belirtilen ile yeni bir PresentationSaveOptions örneği oluşturur
zorunlu Presentation çıktı formatı, diğer tüm parametreler ise
varsayılan


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | outputFormat | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) | Presentation belgesinin kaydedileceği zorunlu çıktı formatı |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Şifreyi belirtmeye, değiştirmeye ve elde etmeye olanak tanır, bu şifre
sonuç Presentation belgesini kodlarken. Varsayılan olarak NULL -
parola ayarlanmayacak. Kaldırmak için NULL veya boş bir dizeye ayarlayın
parola, daha önce ayarlanmışsa.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Sonuç Presentation belgesini kodlamak için kullanılacak şifreyi belirtmeye, değiştirmeye ve almaya olanak tanır.
Varsayılan olarak NULL'dur - parola ayarlanmayacak. Parolayı kaldırmak için NULL veya boş bir dizeye ayarlayın, daha önce ayarlanmışsa.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


Yeni tek slaytlı bir sunum oluşturmak yerine düzenlenmiş slaytı mevcut sunuma eklemeye olanak tanır (varsayılan davranış).
Slayt numarası, Editor sınıfına yüklenen sunumda bir slaytın 1 tabanlı numarasıdır. 0 ise (varsayılan değer), yeni sunum tek düzenlenmiş slayt ile oluşturulacaktır. Sıfırdan büyük veya küçük bir değer ise ve Editor sınıfına yüklenmiş geçerli bir sunum varsa, giriş EditableDocument örneği içinde depolanan düzenlenmiş slayt bu sunuma eklenecektir.

<br />

*** ** * ** ***

> ```
> Given presentation has 5 slides:
>  SlideNumber  = 0; \u2014 ignore given presentation, create a new presentation and put edited slide into it.
>  SlideNumber  = 1; \u2014 replace the first slide with edited
>  SlideNumber  = 2; \u2014 replace the second slide with edited
>  SlideNumber  = 5; \u2014 replace the last (5th) slide with edited
>  SlideNumber  = 6; \u2014 replace the last (5th) slide with edited, because 6 is greater then 5 and thus is adjusted
>  SlideNumber = -1; \u2014 replace the last (5th) slide with edited, because "-1" means "last existing"
>  SlideNumber = -2; \u2014 replace the 4th slide with edited
>  SlideNumber = -3; \u2014 replace the 3rd slide with edited
>  SlideNumber = -4; \u2014 replace the 2nd slide with edited
>  SlideNumber = -5; \u2014 replace the first slide with edited
>  SlideNumber = -6; \u2014 replace the first slide with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />

<br />

*** ** * ** ***

 *SlideNumber*  integer property, if it is not in default state (reserved value '0'), represents a slide number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last slide. Negative values are also allowed and count slides from end. For example, "-1" implies last slide in a presentation, "-2" \\u2014 last but one, etc. Like with positive values, when negative slide number exceeds the total count of slides in the given presentation, it will be adjusted to the first slide. The  InsertAsNewSlide (#getInsertAsNewSlide.getInsertAsNewSlide/#setInsertAsNewSlide(boolean).setInsertAsNewSlide(boolean)) boolean property is tightly coupled with this one.

<br />



**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


Yeni tek slaytlı bir sunum oluşturmak yerine düzenlenmiş slaytı mevcut sunuma eklemeye olanak tanır (varsayılan davranış).
Slayt numarası, Editor sınıfına yüklenen sunumda bir slaytın 1 tabanlı numarasıdır. 0 ise (varsayılan değer), yeni sunum tek düzenlenmiş slayt ile oluşturulacaktır. Sıfırdan büyük veya küçük bir değer ise ve Editor sınıfına yüklenmiş geçerli bir sunum varsa, giriş EditableDocument örneği içinde depolanan düzenlenmiş slayt bu sunuma eklenecektir.

<br />

*** ** * ** ***

> ```
> Given presentation has 5 slides:
>  SlideNumber  = 0; \u2014 ignore given presentation, create a new presentation and put edited slide into it.
>  SlideNumber  = 1; \u2014 replace the first slide with edited
>  SlideNumber  = 2; \u2014 replace the second slide with edited
>  SlideNumber  = 5; \u2014 replace the last (5th) slide with edited
>  SlideNumber  = 6; \u2014 replace the last (5th) slide with edited, because 6 is greater then 5 and thus is adjusted
>  SlideNumber = -1; \u2014 replace the last (5th) slide with edited, because "-1" means "last existing"
>  SlideNumber = -2; \u2014 replace the 4th slide with edited
>  SlideNumber = -3; \u2014 replace the 3rd slide with edited
>  SlideNumber = -4; \u2014 replace the 2nd slide with edited
>  SlideNumber = -5; \u2014 replace the first slide with edited
>  SlideNumber = -6; \u2014 replace the first slide with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />

<br />

*** ** * ** ***

 *SlideNumber*  integer property, if it is not in default state (reserved value '0'), represents a slide number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last slide. Negative values are also allowed and count slides from end. For example, "-1" implies last slide in a presentation, "-2" \\u2014 last but one, etc. Like with positive values, when negative slide number exceeds the total count of slides in the given presentation, it will be adjusted to the first slide. The  InsertAsNewSlide (#getInsertAsNewSlide.getInsertAsNewSlide/#setInsertAsNewSlide(boolean).setInsertAsNewSlide(boolean)) boolean property is tightly coupled with this one.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getInsertAsNewSlide() {#getInsertAsNewSlide--}
```
public final boolean getInsertAsNewSlide()
```


Düzenlenmiş slaytın, orijinal sunumdaki mevcut slaytı belirtilen konumda değiştirip değiştirmeyeceğini belirten Boolean bayrağı, konumu şu şekilde belirten
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) özelliği, ya da mevcut slayt ile öncekisi arasına, içeriğini değiştirmeden eklenmelidir.
Varsayılan olarak false \u2014 mevcut slayt değiştirilecektir. Bu özellik, değerinin
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) özelliği '0' olarak ayarlanmışsa.

<br />

*** ** * ** ***

Varsayılan olarak slayt değiştirilir. Bu, verilen sunumda 5 slayt varsa ve SlideNumber (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))=4 ise, 4. slayt yeni düzenlenmiş slayt ile değiştirilecek ve sunumdaki toplam slayt sayısı (5) aynı kalacaktır. Ancak, bu özelliğin değeri *true* olarak ayarlanırsa, yeni düzenlenmiş slayt 4. slayt olarak eklenir ve sonraki tüm slaytlar sona doğru kaydırılır: "eski" 4. slayt 5. olur, 5. slayt 6. olur ve sunumdaki toplam slayt sayısı bir artarak 6 olur.

<br />



**Returns:**
boolean
### setInsertAsNewSlide(boolean value) {#setInsertAsNewSlide-boolean-}
```
public final void setInsertAsNewSlide(boolean value)
```


Düzenlenmiş slaytın, orijinal sunumdaki mevcut slaytı belirtilen konumda değiştirip değiştirmeyeceğini belirten Boolean bayrağı, konumu şu şekilde belirten
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) özelliği, ya da mevcut slayt ile öncekisi arasına, içeriğini değiştirmeden eklenmelidir.
Varsayılan olarak false \u2014 mevcut slayt değiştirilecektir. Bu özellik, değerinin
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) özelliği '0' olarak ayarlanmışsa.

<br />

*** ** * ** ***

Varsayılan olarak slayt değiştirilir. Bu, verilen sunumda 5 slayt varsa ve SlideNumber (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))=4 ise, 4. slayt yeni düzenlenmiş slayt ile değiştirilecek ve sunumdaki toplam slayt sayısı (5) aynı kalacaktır. Ancak, bu özelliğin değeri *true* olarak ayarlanırsa, yeni düzenlenmiş slayt 4. slayt olarak eklenir ve sonraki tüm slaytlar sona doğru kaydırılır: "eski" 4. slayt 5. olur, 5. slayt 6. olur ve sunumdaki toplam slayt sayısı bir artarak 6 olur.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final PresentationFormats getOutputFormat()
```


Belgeyi kaydetmek için kullanılacak bir Presentation formatını belirtmeye olanak tanır

<br />

*** ** * ** ***

Çıktı formatı genellikle bu sınıfın yapıcı metodunda ayarlanır, çünkü zorunludur. Bu özellik, [PresentationSaveOptions](../../com.groupdocs.editor.options/presentationsaveoptions) sınıfının bir örneği zaten oluşturulmuşken çıktı formatını daha sonra elde etmeye veya değiştirmeye olanak tanır.

<br />



**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)
### setOutputFormat(PresentationFormats value) {#setOutputFormat-com.groupdocs.editor.formats.PresentationFormats-}
```
public final void setOutputFormat(PresentationFormats value)
```


Belgeyi kaydetmek için kullanılacak bir Presentation formatını belirtmeye olanak tanır

<br />

*** ** * ** ***

Çıktı formatı genellikle bu sınıfın yapıcı metodunda ayarlanır, çünkü zorunludur. Bu özellik, [PresentationSaveOptions](../../com.groupdocs.editor.options/presentationsaveoptions) sınıfının bir örneği zaten oluşturulmuşken çıktı formatını daha sonra elde etmeye veya değiştirmeye olanak tanır.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) |  |

### getSlideNumbersToDelete() {#getSlideNumbersToDelete--}
```
public final int[] getSlideNumbersToDelete()
```


Düzenlenmiş slayt mevcut bir sunuma eklendiğinde, kaydedilirken sunumdan silinmesi gereken slaytların 1 tabanlı numaralarını içeren bir dizi belirtmeye olanak tanır. Düzenlenmiş slayt yeni tek‑slaytlık bir sunum olarak (varsayılan davranış) kaydedilmek yerine mevcut bir sunuya (#getSlideNumber().getSlideNumber() / #setSlideNumber(int).setSlideNumber(int) kullanılarak) kaydedildiğinde, bu dizide numaralarını belirterek belirli slaytları da silebilirsiniz. Varsayılan olarak bu dizi null \u2014 hiçbir slayt silinmez. Ancak dizi null değil ve boş değilse ve en az bir geçerli slayt numarası içeriyorsa, düzenlenmiş slayt içeriğiyle çıktı Presentation belgesi oluşturulduktan sonra, belirtilen numaralı slaytlar içeriği çıktı akışına veya dosyasına yazılmadan hemen önce sunumdan silinir. Bu dizideki slayt numaraları 1 tabanlıdır, 0 tabanlı değildir. Geçersiz numaralar (1'den küçük veya toplam slayt sayısından büyük) yok sayılır.


**Returns:**
int[] - Silinecek 1 tabanlı slayt numaralarının dizisi, ya da hiçbir şey silinmeyecekse null.

### setSlideNumbersToDelete(int[] value) {#setSlideNumbersToDelete-int---}
```
public final void setSlideNumbersToDelete(int[] value)
```


Düzenlenmiş slayt mevcut bir sunuma eklendiğinde, kaydedilirken silinmesi gereken slaytların 1 tabanlı numaralarını içeren bir dizi belirtmeye olanak tanır. Bu dizideki slayt numaraları 1 tabanlıdır. Geçersiz numaralar yok sayılır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int[] | Silinecek 1 tabanlı slayt numaralarının dizisi (null veya boş olabilir). |
|

