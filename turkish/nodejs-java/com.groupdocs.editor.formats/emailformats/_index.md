---
title: "EmailFormats"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Tüm e-posta formatlarını kapsar."
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.editor.formats/emailformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EmailFormats extends DocumentFormatBase
```

Tüm e-posta formatlarını kapsar. Aşağıdaki dosya türlerini içerir:
[Tnef](../../com.groupdocs.editor.formats/emailformats#Tnef),
[Eml](../../com.groupdocs.editor.formats/emailformats#Eml),
[Emlx](../../com.groupdocs.editor.formats/emailformats#Emlx),
[Msg](../../com.groupdocs.editor.formats/emailformats#Msg),
[Html](../../com.groupdocs.editor.formats/emailformats#Html),
[Mhtml](../../com.groupdocs.editor.formats/emailformats#Mhtml).

<br />

*** ** * ** ***

E-posta formatı hakkında daha fazla bilgi için [here](../https://docs.fileformat.com/email/).

<br />


## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [Tnef](#Tnef) | Transport Neutral Encapsulation Format (TNEF), Mesaj Uygulama Programlama Arayüzü (MAPI) temelli e-posta eklerini kapsüllemek için Microsoft'a ait bir formattır. |
|
|  | [Eml](#Eml) | EML dosya formatı, Outlook ve diğer ilgili uygulamalarla kaydedilen e-posta mesajlarını temsil eder. |
|
|  | [Emlx](#Emlx) | EMLX dosya formatı Apple tarafından uygulanmakta ve geliştirilmektedir. |
|
|  | [Msg](#Msg) | MSG, Microsoft Outlook ve Exchange tarafından e-posta mesajları, kişiler, randevular veya diğer görevleri depolamak için kullanılan bir dosya formatıdır. |
|
|  | [Html](#Html) | HTML biçimlendirilmiş e-postalar. |
|
|  | [Mhtml](#Mhtml) | MHTML, "MIME encapsulation of aggregate HTML documents" ifadesinin kısaltmasıdır. |
|
|  | [Ics](#Ics) | Internet Takvimleme ve Planlama Çekirdek Nesne Özelliği (iCalendar), takvim etkinliklerini ve planlamayı değiştirmek ve dağıtmak için bir internet standardıdır (RFC 2445). |
|
|  | [Vcf](#Vcf) | VCF (Virtual Card Format) ya da vCard, iletişim bilgilerini depolamak için bir dijital dosya formatıdır. |
|
|  | [Pst](#Pst) | .pst uzantılı dosyalar, çeşitli kullanıcı bilgilerini depolayan Outlook Kişisel Depolama Dosyalarını (aynı zamanda Personal Storage Table olarak da adlandırılır) temsil eder. |
|
|  | [Mbox](#Mbox) | MBox dosya formatı, elektronik posta mesajları koleksiyonu için bir kapsayıcıyı temsil eden genel bir terimdir. |
|
|  | [Oft](#Oft) | .oft uzantılı dosyalar, Microsoft Outlook kullanılarak oluşturulan şablon dosyalarıdır. |
|
|  | [Ost](#Ost) | Offline Storage Table (OST) dosyası, Microsoft Outlook kullanarak Exchange Server'a kaydolduktan sonra yerel makinede çevrim dışı modda kullanıcının posta kutusu verilerini temsil eder. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getAll()](#getAll--) | Tüm [EmailFormats](../../com.groupdocs.editor.formats/emailformats) öğelerinin sayılabilir bir koleksiyonunu alır. |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Belirtilen dosya uzantısına sahip belirtilen türdeki [EmailFormats](../../com.groupdocs.editor.formats/emailformats) örneğini getirir. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Dosya uzantısını temsil eden bir dizeyi bir [EmailFormats](../../com.groupdocs.editor.formats/emailformats) nesnesine dönüştürür. |
|
### Tnef {#Tnef}
```
public static final EmailFormats Tnef
```


Transport Neutral Encapsulation Format (TNEF), Mesaj Uygulama Programlama Arayüzü (MAPI) temelli e-posta eklerini kapsüllemek için Microsoft'a ait bir formattır.
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://docs.fileformat.com/email/tnef/)
.


### Eml {#Eml}
```
public static final EmailFormats Eml
```


EML dosya formatı, Outlook ve diğer ilgili uygulamalarla kaydedilen e-posta mesajlarını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://docs.fileformat.com/email/eml/)
.


### Emlx {#Emlx}
```
public static final EmailFormats Emlx
```


EMLX dosya formatı Apple tarafından uygulanmış ve geliştirilmiştir. Apple Mail uygulaması, e-postaları dışa aktarmak için EMLX dosya formatını kullanır.
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://docs.fileformat.com/email/emlx/)
.


### Msg {#Msg}
```
public static final EmailFormats Msg
```


MSG, Microsoft Outlook ve Exchange tarafından e-posta mesajları, kişiler, randevular veya diğer görevleri depolamak için kullanılan bir dosya formatıdır.
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://docs.fileformat.com/email/msg/)
.


### Html {#Html}
```
public static final EmailFormats Html
```


HTML biçimlendirilmiş e-postalar.


### Mhtml {#Mhtml}
```
public static final EmailFormats Mhtml
```


MHTML, "MIME encapsulation of aggregate HTML documents" ifadesinin kısaltmasıdır.


### Ics {#Ics}
```
public static final EmailFormats Ics
```


Internet Takvimleme ve Planlama Çekirdek Nesne Özelliği (iCalendar), takvim etkinliklerini ve planlamayı değiştirmek ve dağıtmak için bir internet standardıdır (RFC 2445).
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://docs.fileformat.com/email/ics/)
.


### Vcf {#Vcf}
```
public static final EmailFormats Vcf
```


VCF (Virtual Card Format) ya da vCard, iletişim bilgilerini depolamak için bir dijital dosya formatıdır.
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://docs.fileformat.com/email/vcf/)
.


### Pst {#Pst}
```
public static final EmailFormats Pst
```


.pst uzantılı dosyalar, çeşitli kullanıcı bilgilerini depolayan Outlook Kişisel Depolama Dosyalarını (aynı zamanda Personal Storage Table olarak da adlandırılır) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://docs.fileformat.com/email/pst/)
.


### Mbox {#Mbox}
```
public static final EmailFormats Mbox
```


MBox dosya formatı, elektronik posta mesajları koleksiyonu için bir kapsayıcıyı temsil eden genel bir terimdir.
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://docs.fileformat.com/email/mbox/)
.


### Oft {#Oft}
```
public static final EmailFormats Oft
```


.oft uzantılı dosyalar, Microsoft Outlook kullanılarak oluşturulan şablon dosyalarıdır.
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://docs.fileformat.com/email/oft/)
.


### Ost {#Ost}
```
public static final EmailFormats Ost
```


Offline Storage Table (OST) dosyası, Microsoft Outlook kullanarak Exchange Server'a kaydolduktan sonra yerel makinede çevrim dışı modda kullanıcının posta kutusu verilerini temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://docs.fileformat.com/email/ost/)
.


### getAll() {#getAll--}
```
public static List<EmailFormats> getAll()
```


Tüm [EmailFormats](../../com.groupdocs.editor.formats/emailformats) öğelerinin sayılabilir bir koleksiyonunu alır.
Değer: Tüm [EmailFormats](../../com.groupdocs.editor.formats/emailformats) örneklerini içeren bir IEnumerable{EmailFormats}.


**Returns:**
java.util.List<com.groupdocs.editor.formats.EmailFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EmailFormats fromExtension(String extension)
```


Belirtilen dosya uzantısına sahip belirtilen türdeki [EmailFormats](../../com.groupdocs.editor.formats/emailformats) örneğini getirir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | uzantı | java.lang.String | Belge formatının dosya uzantısı. |
|

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - An instance of the specified type [EmailFormats](../../com.groupdocs.editor.formats/emailformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static EmailFormats fromString(String extension)
```


Dosya uzantısını temsil eden bir dizeyi bir [EmailFormats](../../com.groupdocs.editor.formats/emailformats) nesnesine dönüştürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | uzantı | java.lang.String | Dönüştürülecek dosya uzantısı. Uzantı birden fazla nokta içeriyorsa, son noktanın sonrasındaki kısım kullanılır. |
|

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - A [EmailFormats](../../com.groupdocs.editor.formats/emailformats) object corresponding to the specified file extension.

