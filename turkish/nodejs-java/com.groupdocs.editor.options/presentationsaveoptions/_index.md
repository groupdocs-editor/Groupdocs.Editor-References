---
title: "PresentationSaveOptions"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Allows to specify custom options for generating and saving Presentation PowerPoint-compatible documents"
type: docs
weight: 34
url: /tr/nodejs-java/com.groupdocs.editor.options/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PresentationSaveOptions implements ISaveOptions
```

Allows to specify custom options for generating and saving Presentation
(PowerPoint-compatible) documents

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [PresentationSaveOptions()](#PresentationSaveOptions--) | This parameterless constructor creates a new instance of PresentationSaveOptions with PPTX output format (can be modified then through |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)) özelliği)
|
|  | [PresentationSaveOptions(PresentationFormats outputFormat)](#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-) | Creates a new instance of PresentationSaveOptions with specified |
mandatory Presentation output format, while all other parameters are
default
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPassword()](#getPassword--) | Şifreyi belirtmeye, değiştirmeye ve almaya izin verir; bu şifre |
encoding the resultant Presentation document.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Allows to specify, modify and obtain the password, which will be used for encoding the resultant Presentation document. |
|
|  | [getSlideNumber()](#getSlideNumber--) | Allows to insert edited slide into existing presentation instead of creating a new single-slide presentation (default behavior). |
|
|  | [setSlideNumber(int value)](#setSlideNumber-int-) | Allows to insert edited slide into existing presentation instead of creating a new single-slide presentation (default behavior). |
|
|  | [getInsertAsNewSlide()](#getInsertAsNewSlide--) | Boolean flag, which specifies whether edited slide should replace the existing slide in original presentation on the position, specified by the |
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) özelliği, ya da mevcut slayt ile bir önceki slayt arasına, içeriğini değiştirmeden eklenmelidir.
|
|  | [setInsertAsNewSlide(boolean value)](#setInsertAsNewSlide-boolean-) | Boolean flag, which specifies whether edited slide should replace the existing slide in original presentation on the position, specified by the |
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) özelliği, ya da mevcut slayt ile bir önceki slayt arasına, içeriğini değiştirmeden eklenmelidir.
|
|  | [getOutputFormat()](#getOutputFormat--) | Allows to specify a Presentation format, which will be used for saving the document |
|
|  | [setOutputFormat(PresentationFormats value)](#setOutputFormat-com.groupdocs.editor.formats.PresentationFormats-) | Allows to specify a Presentation format, which will be used for saving the document |
|
|  | [getSlideNumbersToDelete()](#getSlideNumbersToDelete--) | Allows to specify an array with 1-based numbers of slides that should be deleted from the presentation during its saving, in case when the edited slide is inserted into existing presentation. |
|
|  | [setSlideNumbersToDelete(int[] value)](#setSlideNumbersToDelete-int---) | Allows to specify an array with 1-based numbers of slides that should be deleted from the presentation during its saving, in case when the edited slide is inserted into existing presentation. |
|
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


This parameterless constructor creates a new instance of PresentationSaveOptions with PPTX output format (can be modified then through
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)) özelliği)


### PresentationSaveOptions(PresentationFormats outputFormat) {#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-}
```
public PresentationSaveOptions(PresentationFormats outputFormat)
```


Creates a new instance of PresentationSaveOptions with specified
mandatory Presentation output format, while all other parameters are
default


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | outputFormat | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) | Mandatory output format, in which the Presentation document should be saved |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Şifreyi belirtmeye, değiştirmeye ve almaya izin verir; bu şifre
encoding the resultant Presentation document. By default is NULL -
password will not be set. Set to NULL or empty string in order to remove
the password, if it was set previously.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Allows to specify, modify and obtain the password, which will be used for encoding the resultant Presentation document.
Varsayılan olarak NULL'dur - şifre ayarlanmaz. Şifre daha önce ayarlanmışsa kaldırmak için NULL veya boş bir dizeye ayarlayın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


Allows to insert edited slide into existing presentation instead of creating a new single-slide presentation (default behavior).
Slayt numarası, Editor sınıfında yüklü sunumdaki slaytın 1 tabanlı numarasıdır. 0 ise (varsayılan değer), yeni sunum tek düzenlenmiş slayt ile oluşturulur. Sıfırdan büyük veya küçük ise ve Editor sınıfında geçerli bir sunum yüklüyse, giriş EditableDocument örneği içinde depolanan düzenlenmiş slayt bu sunuma eklenecektir.

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


Allows to insert edited slide into existing presentation instead of creating a new single-slide presentation (default behavior).
Slayt numarası, Editor sınıfında yüklü sunumdaki slaytın 1 tabanlı numarasıdır. 0 ise (varsayılan değer), yeni sunum tek düzenlenmiş slayt ile oluşturulur. Sıfırdan büyük veya küçük ise ve Editor sınıfında geçerli bir sunum yüklüyse, giriş EditableDocument örneği içinde depolanan düzenlenmiş slayt bu sunuma eklenecektir.

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


Boolean flag, which specifies whether edited slide should replace the existing slide in original presentation on the position, specified by the
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) özelliği, ya da mevcut slayt ile bir önceki slayt arasına, içeriğini değiştirmeden eklenmelidir.
Varsayılan olarak false'dur — mevcut slayt değiştirilecektir. Bu özellik, değerinin
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) özelliği '0' olarak ayarlandığında.

<br />

*** ** * ** ***

Varsayılan olarak slayt değiştirilir. Bu, verilen sunumda 5 slayt varsa ve SlideNumber (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))=4 ise, 4. slayt yeni düzenlenmiş slayt ile değiştirilir ve sunumdaki toplam slayt sayısı (5) aynı kalır. Ancak, bu özelliğin değeri *true* olarak ayarlanırsa, yeni düzenlenmiş slayt 4. slayt olarak eklenir ve sonraki tüm slaytlar sona doğru kaydırılır: "eski" 4. slayt 5. olur, 5. slayt 6. olur ve sunumdaki toplam slayt sayısı bir artarak 6 olur.

<br />



**Returns:**
boolean
### setInsertAsNewSlide(boolean value) {#setInsertAsNewSlide-boolean-}
```
public final void setInsertAsNewSlide(boolean value)
```


Boolean flag, which specifies whether edited slide should replace the existing slide in original presentation on the position, specified by the
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) özelliği, ya da mevcut slayt ile bir önceki slayt arasına, içeriğini değiştirmeden eklenmelidir.
Varsayılan olarak false'dur — mevcut slayt değiştirilecektir. Bu özellik, değerinin
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) özelliği '0' olarak ayarlandığında.

<br />

*** ** * ** ***

Varsayılan olarak slayt değiştirilir. Bu, verilen sunumda 5 slayt varsa ve SlideNumber (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))=4 ise, 4. slayt yeni düzenlenmiş slayt ile değiştirilir ve sunumdaki toplam slayt sayısı (5) aynı kalır. Ancak, bu özelliğin değeri *true* olarak ayarlanırsa, yeni düzenlenmiş slayt 4. slayt olarak eklenir ve sonraki tüm slaytlar sona doğru kaydırılır: "eski" 4. slayt 5. olur, 5. slayt 6. olur ve sunumdaki toplam slayt sayısı bir artarak 6 olur.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final PresentationFormats getOutputFormat()
```


Allows to specify a Presentation format, which will be used for saving the document

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


Allows to specify a Presentation format, which will be used for saving the document

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


Düzenlenmiş slayt mevcut bir sunuma eklendiğinde, kaydetme sırasında sunumdan silinmesi gereken slaytların 1 tabanlı numaralarını içeren bir dizi belirtmeye olanak tanır. Düzenlenmiş slayt yeni tek‑slaytlık bir sunum olarak kaydedilmek yerine (varsayılan davranış), bir mevcut sunuma (#getSlideNumber().getSlideNumber() / #setSlideNumber(int).setSlideNumber(int)) kullanılarak kaydedildiğinde, bu dizi içinde numaraları belirterek bu sunumdan belirli slaytları da silebilirsiniz. Varsayılan olarak bu dizi null’dır — hiçbir slayt silinmez. Ancak dizi null değil ve boş değilse ve en az bir geçerli slayt numarası içeriyorsa, düzenlenmiş slaytın içeriğiyle çıktı Presentation belgesi oluşturulduktan sonra, belirtilen numaralı slaytlar içeriği çıktı akışına veya dosyasına yazılmadan hemen önce sunumdan silinir. Bu dizideki slayt numaraları 1 tabanlıdır, 0 tabanlı değildir. Geçersiz numaralar (1’den küçük veya toplam slayt sayısından büyük) yok sayılır.


**Returns:**
int[] - Silinecek 1 tabanlı slayt numaralarının dizisi, ya da hiçbir şey silinmeyecekse  null .

### setSlideNumbersToDelete(int[] value) {#setSlideNumbersToDelete-int---}
```
public final void setSlideNumbersToDelete(int[] value)
```


Düzenlenmiş slayt mevcut bir sunuma eklendiğinde, kaydetme sırasında sunumdan silinmesi gereken slaytların 1 tabanlı numaralarını içeren bir dizi belirtmeye olanak tanır. Bu dizideki slayt numaraları 1 tabanlıdır. Geçersiz numaralar yok sayılır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int[] | Silinecek 1 tabanlı slayt numaralarının dizisi (null  veya boş olabilir). |
|

