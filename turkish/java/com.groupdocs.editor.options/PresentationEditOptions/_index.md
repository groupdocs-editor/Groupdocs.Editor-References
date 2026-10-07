---
title: "PresentationEditOptions"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Desteklenen tüm Sunum PowerPoint uyumlu formatlarındaki belgeleri düzenlemek için özel seçenekler belirtmeye izin verir"
type: docs
weight: 32
url: /tr/java/com.groupdocs.editor.options/presentationeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class PresentationEditOptions implements IEditOptions
```

Desteklenen tüm belgeleri düzenlemek için özel seçenekler belirtmeye izin verir
Sunum (PowerPoint uyumlu) formatları

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PresentationEditOptions()](#PresentationEditOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getSlideNumber()](#getSlideNumber--) | Düzenleme için açılması gereken slayt numaralarını belirtmeye izin verir |
|
|  | [setSlideNumber(int value)](#setSlideNumber-int-) | Düzenleme için açılması gereken slayt numaralarını belirtmeye izin verir |
|
|  | [getShowHiddenSlides()](#getShowHiddenSlides--) | Gizli slaytların dahil edilip edilmeyeceğini belirtir. |
|
|  | [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Gizli slaytların dahil edilip edilmeyeceğini belirtir. |
|
### PresentationEditOptions() {#PresentationEditOptions--}
```
public PresentationEditOptions()
```


### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


Düzenleme için açılması gereken slayt numaralarını belirtmeye izin verir


*** ** * ** ***

Slayt numarası, bir slaytın sıfır tabanlı indeksidir ve bir sunumdan düzenlemek için belirli bir slaytı seçmeye olanak tanır. 0'dan küçükse, ilk slayt seçilir (SlideNumber = 0 ile aynı). Sunumdaki toplam slayt sayısından büyükse, son slayt seçilir. Giriş sunumu yalnızca tek bir slayt içeriyorsa, bu seçenek yoksayılır ve bu tek slayt düzenlenir. Gizli bir slaytı düzenleme amacıyla açmaya çalışılırken, ShowHiddenSlides (#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)) seçeneği 'false' olarak ayarlanmışsa, bir istisna fırlatılır.

<br />



**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


Düzenleme için açılması gereken slayt numaralarını belirtmeye izin verir


*** ** * ** ***

Slayt numarası, bir slaytın sıfır tabanlı indeksidir ve bir sunumdan düzenlemek için belirli bir slaytı seçmeye olanak tanır. 0'dan küçükse, ilk slayt seçilir (SlideNumber = 0 ile aynı). Sunumdaki toplam slayt sayısından büyükse, son slayt seçilir. Giriş sunumu yalnızca tek bir slayt içeriyorsa, bu seçenek yoksayılır ve bu tek slayt düzenlenir. Gizli bir slaytı düzenleme amacıyla açmaya çalışılırken, ShowHiddenSlides (#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)) seçeneği 'false' olarak ayarlanmışsa, bir istisna fırlatılır.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Gizli slaytların dahil edilip edilmeyeceğini belirtir. Varsayılan değer
false - gizli slaytlar gösterilmez ve istisna fırlatılırken
onları düzenlemeye çalışırken.


**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Gizli slaytların dahil edilip edilmeyeceğini belirtir. Varsayılan değer
false - gizli slaytlar gösterilmez ve istisna fırlatılırken
onları düzenlemeye çalışırken.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

