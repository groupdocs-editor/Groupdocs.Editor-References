---
title: "WordProcessingLoadOptions"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "DOCX, RTF, ODT vb. gibi WordProcessing Word uyumlu belgeleri yüklemek için seçenekler içerir."
type: docs
weight: 45
url: /tr/java/com.groupdocs.editor.options/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class WordProcessingLoadOptions implements ILoadOptions
```

WordProcessing (Word uyumlu) belgeleri yüklemek için seçenekler içerir gibi
DOC(X), RTF, ODT vb. Editor sınıfına

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPassword()](#getPassword--) | Şifreyi belirtmeye, değiştirmeye ve elde etmeye olanak tanır, bu şifre |
kodlanmışsa WordProcessing belgesini açma.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Şifreyi belirtmeye, değiştirmeye ve elde etmeye olanak tanır, bu şifre |
kodlanmışsa WordProcessing belgesini açma.
|
### WordProcessingLoadOptions() {#WordProcessingLoadOptions--}
```
public WordProcessingLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Şifreyi belirtmeye, değiştirmeye ve elde etmeye olanak tanır, bu şifre
kodlanmışsa WordProcessing belgesini açma. NULL veya boş olarak ayarlayın
parola kullanılmaması için dize (varsayılan değer).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Şifreyi belirtmeye, değiştirmeye ve elde etmeye olanak tanır, bu şifre
kodlanmışsa WordProcessing belgesini açma. NULL veya boş olarak ayarlayın
parola kullanılmaması için dize (varsayılan değer).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

