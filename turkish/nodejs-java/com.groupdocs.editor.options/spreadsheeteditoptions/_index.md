---
title: "SpreadsheetEditOptions"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Desteklenen tüm Elektronik Tablo Excel uyumlu formatlarındaki belgeleri düzenlemek için özel seçenekler belirtmenize izin verir"
type: docs
weight: 35
url: /tr/nodejs-java/com.groupdocs.editor.options/spreadsheeteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class SpreadsheetEditOptions implements IEditOptions
```

Desteklenen tüm belgeleri düzenlemek için özel seçenekler belirtmeye izin verir.
Elektronik Tablo (Excel uyumlu) formatları

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SpreadsheetEditOptions()](#SpreadsheetEditOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Girişin çalışma sayfasının (sekme) 0 tabanlı dizinini belirtmenize izin verir |
HTML'ye dönüştürülmesi gereken elektronik tablo belgesi (bkz.
notlar).
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Girişin çalışma sayfasının (sekme) 0 tabanlı dizinini belirtmenize izin verir |
HTML'ye dönüştürülmesi gereken elektronik tablo belgesi (bkz.
notlar).
|
|  | [getExcludeHiddenWorksheets()](#getExcludeHiddenWorksheets--) | Giriş elektronik tablo belgesindeki gizli çalışma sayfalarını dışlamanıza izin verir, böylece |
tamamen göz ardı edileceklerdir.
|
|  | [setExcludeHiddenWorksheets(boolean value)](#setExcludeHiddenWorksheets-boolean-) | Giriş elektronik tablo belgesindeki gizli çalışma sayfalarını dışlamanıza izin verir, böylece |
tamamen göz ardı edileceklerdir.
|
|  | [getMergeEmptyAdjacentCells()](#getMergeEmptyAdjacentCells--) | Etkinleştirildiğinde, giriş elektronik tablo belgesindeki boş yan yana yatay hücreler |
düzenlenebilir HTML belgesinde tek bir hücreye birleştirilmiş olarak temsil edilir ve ilgili
colspan özniteliği.
|
| [setMergeEmptyAdjacentCells(boolean value)](#setMergeEmptyAdjacentCells-boolean-) |  |
|  | [getExportBogusRowData()](#getExportBogusRowData--) | Etkinleştirildiğinde, üretilen HTML belgesindeki HTML tablosu aşağıda boş bir gizli satır içerir ve |
sıfır yüksekliğe ve boş hücrelere sahiptir; yalnızca genişlik belirtilir.
|
| [setExportBogusRowData(boolean value)](#setExportBogusRowData-boolean-) |  |
### SpreadsheetEditOptions() {#SpreadsheetEditOptions--}
```
public SpreadsheetEditOptions()
```


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


Girişin çalışma sayfasının (sekme) 0 tabanlı dizinini belirtmenize izin verir
HTML'ye dönüştürülmesi gereken elektronik tablo belgesi (bkz.
notlar).


*** ** * ** ***

Çoğu elektronik tablo belgesi sekme kavramını destekler, yani çoklu sekmeli olabilir. Öte yandan, HTML formatı bu yapıyı desteklemez. Bu nedenle GroupDocs.Editor, giriş belgesinin yalnızca belirli bir sekmesini HTML'ye dönüştürebilir ve bu seçenek onu belirtmenizi sağlar. Sekme indeksi 0 tabanlıdır, negatif değerler yasaktır. Belirtilen indeks tüm sekme sayısını aşarsa bir istisna fırlatılır. Giriş elektronik tablo belgesi yalnızca bir sekme içeriyorsa bu seçenek yok sayılır. Varsayılan değer 0 (ilk sekme).

<br />



**Returns:**
int
### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Girişin çalışma sayfasının (sekme) 0 tabanlı dizinini belirtmenize izin verir
HTML'ye dönüştürülmesi gereken elektronik tablo belgesi (bkz.
notlar).


*** ** * ** ***

Çoğu elektronik tablo belgesi sekme kavramını destekler, yani çoklu sekmeli olabilir. Öte yandan, HTML formatı bu yapıyı desteklemez. Bu nedenle GroupDocs.Editor, giriş belgesinin yalnızca belirli bir sekmesini HTML'ye dönüştürebilir ve bu seçenek onu belirtmenizi sağlar. Sekme indeksi 0 tabanlıdır, negatif değerler yasaktır. Belirtilen indeks tüm sekme sayısını aşarsa bir istisna fırlatılır. Giriş elektronik tablo belgesi yalnızca bir sekme içeriyorsa bu seçenek yok sayılır. Varsayılan değer 0 (ilk sekme).

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getExcludeHiddenWorksheets() {#getExcludeHiddenWorksheets--}
```
public final boolean getExcludeHiddenWorksheets()
```


Giriş elektronik tablo belgesindeki gizli çalışma sayfalarını dışlamanıza izin verir, böylece
tamamen göz ardı edileceklerdir. Varsayılan değer false - gizli çalışma sayfaları
mevcut ve normal şekilde işlenir.


*** ** * ** ***

XLSX gibi bazı ikili Elektronik Tablo formatları gizli çalışma sayfaları (sekme) kavramını destekler. Bu formatta bir belge birden fazla çalışma sayfasına sahipse ek gizli çalışma sayfaları içerebilir. Varsayılan olarak bu gizli çalışma sayfaları işleme açıktır, ancak bu seçenekle onları yok sayabilirsiniz; yani bu gizli çalışma sayfaları mevcut değilmiş gibi davranılır. Bu seçenek etkinleştirildiğinde, ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))' özelliğiyle gizli çalışma sayfasını seçemezsiniz.

<br />



**Returns:**
boolean
### setExcludeHiddenWorksheets(boolean value) {#setExcludeHiddenWorksheets-boolean-}
```
public final void setExcludeHiddenWorksheets(boolean value)
```


Giriş elektronik tablo belgesindeki gizli çalışma sayfalarını dışlamanıza izin verir, böylece
tamamen göz ardı edileceklerdir. Varsayılan değer false - gizli çalışma sayfaları
mevcut ve normal şekilde işlenir.


*** ** * ** ***

XLSX gibi bazı ikili Elektronik Tablo formatları gizli çalışma sayfaları (sekme) kavramını destekler. Bu formatta bir belge birden fazla çalışma sayfasına sahipse ek gizli çalışma sayfaları içerebilir. Varsayılan olarak bu gizli çalışma sayfaları işleme açıktır, ancak bu seçenekle onları yok sayabilirsiniz; yani bu gizli çalışma sayfaları mevcut değilmiş gibi davranılır. Bu seçenek etkinleştirildiğinde, ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))' özelliğiyle gizli çalışma sayfasını seçemezsiniz.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getMergeEmptyAdjacentCells() {#getMergeEmptyAdjacentCells--}
```
public boolean getMergeEmptyAdjacentCells()
```


Etkinleştirildiğinde, giriş elektronik tablo belgesindeki boş yan yana yatay hücreler
düzenlenebilir HTML belgesinde tek bir hücreye birleştirilmiş olarak temsil edilir ve ilgili
colspan özniteliği. Varsayılan olarak devredışı (false).


Varsayılan olarak GroupDocs.Editor, giriş elektronik tablo belgesindeki bir tabloyu çıktıya
her hücreyi koruyarak HTML belgesine dönüştürür. Ancak, elektronik tablo belgeleri seyrek olabilir \\u2014 bunlar
çok sayıda "boş alan" içerebilir; burada birçok hücre boştur. Bu seçenek,
etkinleştirildiğinde, bu boş hücreleri TD öğesinde colspan özniteliğiyle tek bir hücreye birleştirir,
ve böylece üretilen HTML işaretlemesinin boyutunu önemli ölçüde azaltabilir.


**Returns:**
boolean
### setMergeEmptyAdjacentCells(boolean value) {#setMergeEmptyAdjacentCells-boolean-}
```
public void setMergeEmptyAdjacentCells(boolean value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getExportBogusRowData() {#getExportBogusRowData--}
```
public boolean getExportBogusRowData()
```


Etkinleştirildiğinde, üretilen HTML belgesindeki HTML tablosu aşağıda boş bir gizli satır içerir ve
sıfır yükseklik ve boş hücreler, yalnızca genişlik belirtilen. Boş hücreli bu satır şunları içerir
her sütun için kesin genişlik değerleri ve HTML'den Elektronik Tablo'ya geri dönüşümünü iyileştirir. By
varsayılan olarak etkin (true).


**Returns:**
boolean
### setExportBogusRowData(boolean value) {#setExportBogusRowData-boolean-}
```
public void setExportBogusRowData(boolean value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

