---
title: "EmailSaveOptions"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Elektronik posta belgelerini oluşturmak ve kaydetmek için özel seçenekler belirtmeye olanak tanır."
type: docs
weight: 15
url: /tr/java/com.groupdocs.editor.options/emailsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EmailSaveOptions implements ISaveOptions
```

Elektronik posta (email) belgelerini oluşturma ve kaydetme için özel seçenekleri belirtmeye izin verir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [EmailSaveOptions()](#EmailSaveOptions--) | Tüm seçeneklerin varsayılan değerlere ayarlandığı [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) sınıfının yeni bir örneğini başlatır. |
|
|  | [EmailSaveOptions(int mailMessageOutput)](#EmailSaveOptions-int-) | [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) sınıfının yeni bir örneğini şu seçeneklerle başlatır |
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) parametresi
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | Çıktı e-posta belgesine hangi bölümlerin teslim edileceğini kontrol etmeye olanak tanır; bu belge, [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) yöntemiyle oluşturulup kaydedilecektir. |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | Çıktı e-posta belgesine hangi bölümlerin teslim edileceğini kontrol etmeye olanak tanır; bu belge, [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) yöntemiyle oluşturulup kaydedilecektir. |
|
### EmailSaveOptions() {#EmailSaveOptions--}
```
public EmailSaveOptions()
```


Tüm seçeneklerin varsayılan değerlere ayarlandığı [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) sınıfının yeni bir örneğini başlatır.


### EmailSaveOptions(int mailMessageOutput) {#EmailSaveOptions-int-}
```
public EmailSaveOptions(int mailMessageOutput)
```


[EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) sınıfının yeni bir örneğini şu seçeneklerle başlatır
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


Çıktı e-posta belgesine hangi bölümlerin teslim edileceğini kontrol etmeye olanak tanır; bu belge, [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) yöntemiyle oluşturulup kaydedilecektir.
Değer: İşlenmesi gereken posta mesajı bölümlerini kontrol eden işaretli enum. Varsayılan değer MailMessageOutput.All'dir


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


Çıktı e-posta belgesine hangi bölümlerin teslim edileceğini kontrol etmeye olanak tanır; bu belge, [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) yöntemiyle oluşturulup kaydedilecektir.
Değer: İşlenmesi gereken posta mesajı bölümlerini kontrol eden işaretli enum. Varsayılan değer MailMessageOutput.All'dir


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

