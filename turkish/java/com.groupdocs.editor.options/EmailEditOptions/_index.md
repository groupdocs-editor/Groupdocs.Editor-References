---
title: "EmailEditOptions"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Farklı elektronik posta formatlarında belgeleri düzenlemek için özel seçenekler belirtmeye olanak tanır"
type: docs
weight: 14
url: /tr/java/com.groupdocs.editor.options/emaileditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EmailEditOptions implements IEditOptions
```

Farklı elektronik posta (email) formatlarında belgeleri düzenlemek için özel seçenekleri belirtmeye izin verir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [EmailEditOptions()](#EmailEditOptions--) | Tüm seçeneklerin varsayılan değerlere ayarlandığı [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) sınıfının yeni bir örneğini başlatır |
|
|  | [EmailEditOptions(int mailMessageOutput)](#EmailEditOptions-int-) | Yeni bir [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) sınıfı örneğini şu ile başlatır |
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) parametresi
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | Posta mesajının hangi bölümlerinin çıktı [EditableDocument](../../com.groupdocs.editor/editabledocument) olarak teslim edileceğini ve ardından oluşturulan HTML'e gönderileceğini kontrol etmeye olanak tanır |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | Posta mesajının hangi bölümlerinin çıktı [EditableDocument](../../com.groupdocs.editor/editabledocument) olarak teslim edileceğini ve ardından oluşturulan HTML'e gönderileceğini kontrol etmeye olanak tanır |
|
### EmailEditOptions() {#EmailEditOptions--}
```
public EmailEditOptions()
```


Tüm seçeneklerin varsayılan değerlere ayarlandığı [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) sınıfının yeni bir örneğini başlatır


### EmailEditOptions(int mailMessageOutput) {#EmailEditOptions-int-}
```
public EmailEditOptions(int mailMessageOutput)
```


Yeni bir [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) sınıfı örneğini şu ile başlatır
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) parametresi


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | mailMessageOutput | int | Özellik aracılığıyla da belirtilebilen posta mesajı çıktısı |
|

### getMailMessageOutput() {#getMailMessageOutput--}
```
public final int getMailMessageOutput()
```


Posta mesajının hangi bölümlerinin çıktı [EditableDocument](../../com.groupdocs.editor/editabledocument) olarak teslim edileceğini ve ardından oluşturulan HTML'e gönderileceğini kontrol etmeye olanak tanır
Değer: İşlenmesi gereken posta mesajı bölümlerini kontrol eden işaretli enum. Varsayılan değer MailMessageOutput.All'dir


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


Posta mesajının hangi bölümlerinin çıktı [EditableDocument](../../com.groupdocs.editor/editabledocument) olarak teslim edileceğini ve ardından oluşturulan HTML'e gönderileceğini kontrol etmeye olanak tanır
Değer: İşlenmesi gereken posta mesajı bölümlerini kontrol eden işaretli enum. Varsayılan değer MailMessageOutput.All'dir


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

