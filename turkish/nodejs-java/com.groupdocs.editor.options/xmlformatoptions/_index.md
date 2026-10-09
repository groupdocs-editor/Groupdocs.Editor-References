---
title: "XmlFormatOptions"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "XML belgesinin HTML olarak temsil edildiğinde biçimlendirilmesini ayarlamaya izin veren seçenekler içerir"
type: docs
weight: 52
url: /tr/nodejs-java/com.groupdocs.editor.options/xmlformatoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlFormatOptions implements IEditOptions
```

XML belgesi HTML olarak temsil edildiğinde biçimlendirmesini ayarlamayı sağlayan seçenekleri içerir.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getEachAttributeFromNewline()](#getEachAttributeFromNewline--) | Etkinleştirildiğinde, her XML öğesindeki her bir nitelik-değer çifti yeni bir satıra yerleştirilecektir. |
|
|  | [setEachAttributeFromNewline(boolean value)](#setEachAttributeFromNewline-boolean-) | Etkinleştirildiğinde, her XML öğesindeki her bir nitelik-değer çifti yeni bir satıra yerleştirilecektir. |
|
|  | [getLeafTextNodesOnNewline()](#getLeafTextNodesOnNewline--) | Etkinleştirildiğinde, yaprak metin düğümleri (çocukları olmayan XML öğeleri içindeki metin içeriği) daha büyük sol girinti ile yeni bir satıra yerleştirilecektir. |
|
|  | [setLeafTextNodesOnNewline(boolean value)](#setLeafTextNodesOnNewline-boolean-) | Etkinleştirildiğinde, yaprak metin düğümleri (çocukları olmayan XML öğeleri içindeki metin içeriği) daha büyük sol girinti ile yeni bir satıra yerleştirilecektir. |
|
|  | [getLeftIndent()](#getLeftIndent--) | Her yeni satırın sol girintisi için bir ofset belirlemenizi sağlar. |
|
|  | [setLeftIndent(Length value)](#setLeftIndent-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Her yeni satırın sol girintisi için bir ofset belirlemenizi sağlar. |
|
|  | [isDefault()](#isDefault--) | Bu XML biçimlendirme seçenekleri örneğinin varsayılan bir değere sahip olup olmadığını gösterir |
|
### getEachAttributeFromNewline() {#getEachAttributeFromNewline--}
```
public final boolean getEachAttributeFromNewline()
```


Etkinleştirildiğinde, her XML öğesindeki her bir nitelik-değer çifti yeni bir satıra yerleştirilecektir.
Varsayılan olarak yanlıştır (devre dışı) \\u2014 tüm öznitelik-değer çiftleri tek bir satıra yerleştirilir.


**Returns:**
boolean
### setEachAttributeFromNewline(boolean value) {#setEachAttributeFromNewline-boolean-}
```
public final void setEachAttributeFromNewline(boolean value)
```


Etkinleştirildiğinde, her XML öğesindeki her bir nitelik-değer çifti yeni bir satıra yerleştirilecektir.
Varsayılan olarak yanlıştır (devre dışı) \\u2014 tüm öznitelik-değer çiftleri tek bir satıra yerleştirilir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getLeafTextNodesOnNewline() {#getLeafTextNodesOnNewline--}
```
public final boolean getLeafTextNodesOnNewline()
```


Etkinleştirildiğinde, yaprak metin düğümleri (çocukları olmayan XML öğeleri içindeki metin içeriği) daha büyük sol girinti ile yeni bir satıra yerleştirilecektir.
Varsayılan olarak yanlıştır (devre dışı) \\u2014 yaprak metin düğümleri, yeni girinti olmadan, ebeveynleriyle aynı satıra yerleştirilir.


**Returns:**
boolean
### setLeafTextNodesOnNewline(boolean value) {#setLeafTextNodesOnNewline-boolean-}
```
public final void setLeafTextNodesOnNewline(boolean value)
```


Etkinleştirildiğinde, yaprak metin düğümleri (çocukları olmayan XML öğeleri içindeki metin içeriği) daha büyük sol girinti ile yeni bir satıra yerleştirilecektir.
Varsayılan olarak yanlıştır (devre dışı) \\u2014 yaprak metin düğümleri, yeni girinti olmadan, ebeveynleriyle aynı satıra yerleştirilir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getLeftIndent() {#getLeftIndent--}
```
public final Length getLeftIndent()
```


Her yeni satırın sol girintisi için bir kaydırma değeri belirtmeye izin verir. Birimsiz sıfır olmayan bir değer olamaz. Varsayılan olarak 10pt'dir.


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### setLeftIndent(Length value) {#setLeftIndent-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public final void setLeftIndent(Length value)
```


Her yeni satırın sol girintisi için bir kaydırma değeri belirtmeye izin verir. Birimsiz sıfır olmayan bir değer olamaz. Varsayılan olarak 10pt'dir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Bu XML biçimlendirme seçenekleri örneğinin varsayılan bir değere sahip olup olmadığını gösterir


**Returns:**
boolean
