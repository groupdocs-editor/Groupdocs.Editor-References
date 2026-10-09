---
title: "EmailEditOptions"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Farklı elektronik posta formatlarında belgeleri düzenlemek için özel seçenekler belirtmeye izin verir"
type: docs
weight: 14
url: /tr/nodejs-java/com.groupdocs.editor.options/emaileditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EmailEditOptions implements IEditOptions
```

Farklı elektronik posta (email) formatlarındaki belgeleri düzenlemek için özel seçenekleri belirtmeye izin verir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [EmailEditOptions()](#EmailEditOptions--) | Tüm seçeneklerin varsayılan değerlere ayarlandığı [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) sınıfının yeni bir örneğini başlatır |
|
|  | [EmailEditOptions(int mailMessageOutput)](#EmailEditOptions-int-) | [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) sınıfının yeni bir örneğini şu ile başlatır |
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) parametresi
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | Posta mesajının hangi bölümlerinin çıktı [EditableDocument](../../com.groupdocs.editor/editabledocument) içine ve ardından oluşturulan HTML'e gönderileceğini kontrol etmeye izin verir |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | Posta mesajının hangi bölümlerinin çıktı [EditableDocument](../../com.groupdocs.editor/editabledocument) içine ve ardından oluşturulan HTML'e gönderileceğini kontrol etmeye izin verir |
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


[EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) sınıfının yeni bir örneğini şu ile başlatır
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) parametresi


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | mailMessageOutput | int | Posta mesajı çıktısı, ayrıca özellik aracılığıyla da belirtilebilir |
|

### getMailMessageOutput() {#getMailMessageOutput--}
```
public final int getMailMessageOutput()
```


Posta mesajının hangi bölümlerinin çıktı [EditableDocument](../../com.groupdocs.editor/editabledocument) içine ve ardından oluşturulan HTML'e gönderileceğini kontrol etmeye izin verir
Değer: İşlenecek posta mesajı bölümlerini kontrol eden işaretli enum. Varsayılan değer MailMessageOutput.All'dir


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


Posta mesajının hangi bölümlerinin çıktı [EditableDocument](../../com.groupdocs.editor/editabledocument) içine ve ardından oluşturulan HTML'e gönderileceğini kontrol etmeye izin verir
Değer: İşlenecek posta mesajı bölümlerini kontrol eden işaretli enum. Varsayılan değer MailMessageOutput.All'dir


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

