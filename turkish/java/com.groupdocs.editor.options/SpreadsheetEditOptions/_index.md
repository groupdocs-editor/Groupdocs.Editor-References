---
title: "SpreadsheetEditOptions"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Tüm desteklenen Spreadsheet Excel uyumlu formatlarındaki belgeleri düzenlemek için özel seçenekler belirtmeye olanak tanır."
type: docs
weight: 35
url: /tr/java/com.groupdocs.editor.options/spreadsheeteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class SpreadsheetEditOptions implements IEditOptions
```

Desteklenen tüm belgeleri düzenlemek için özel seçenekler belirtmeye izin verir
Spreadsheet (Excel uyumlu) formatları

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SpreadsheetEditOptions()](#SpreadsheetEditOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Girişin çalışma sayfasının (sekmesinin) 0 tabanlı indeksini belirtmeye olanak tanır |
HTML'ye dönüştürülmesi gereken Spreadsheet belgesi (bkz.
notlar).
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Girişin çalışma sayfasının (sekmesinin) 0 tabanlı indeksini belirtmeye olanak tanır |
HTML'ye dönüştürülmesi gereken Spreadsheet belgesi (bkz.
notlar).
|
|  | [getExcludeHiddenWorksheets()](#getExcludeHiddenWorksheets--) | Giriş Spreadsheet belgesindeki gizli çalışma sayfalarını dışlamaya olanak tanır, böylece |
tamamen göz ardı edilecekler.
|
|  | [setExcludeHiddenWorksheets(boolean value)](#setExcludeHiddenWorksheets-boolean-) | Giriş Spreadsheet belgesindeki gizli çalışma sayfalarını dışlamaya olanak tanır, böylece |
tamamen göz ardı edilecekler.
|
|  | [getMergeEmptyAdjacentCells()](#getMergeEmptyAdjacentCells--) | Etkinleştirildiğinde, giriş Spreadsheet belgesindeki boş bitişik yatay hücreler |
düzenlenebilir HTML belgesinde karşılık gelen
colspan niteliğiyle tek bir hücreye birleştirilmiş olarak temsil edilir.
|
| [setMergeEmptyAdjacentCells(boolean value)](#setMergeEmptyAdjacentCells-boolean-) |  |
|  | [getExportBogusRowData()](#getExportBogusRowData--) | Etkinleştirildiğinde, üretilen HTML belgesindeki HTML tablosu, alt kısmında boş bir gizli satır içerir |
sıfır yüksekliğe ve sadece genişliği belirtilen boş hücrelere sahiptir.
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


Girişin çalışma sayfasının (sekmesinin) 0 tabanlı indeksini belirtmeye olanak tanır
HTML'ye dönüştürülmesi gereken Spreadsheet belgesi (bkz.
notlar).


*** ** * ** ***

Çoğu Spreadsheet belgesi sekme kavramını destekler, yani çok sekmeli olabilir. Öte yandan, HTML formatı bu yapıyı desteklemez. Bu nedenle GroupDocs.Editor, giriş belgesinin yalnızca belirli bir sekmesini HTML'ye dönüştürebilir ve bu seçenek onu belirtmeye olanak tanır. Sekme indeksi 0 tabanlıdır, negatif değerler yasaktır. Belirtilen indeks tüm sekme sayısını aşarsa bir istisna fırlatılır. Giriş Spreadsheet belgesi yalnızca bir sekme içeriyorsa bu seçenek yoksayılır. Varsayılan değer 0'dır (ilk sekme).

<br />



**Returns:**
int
### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Girişin çalışma sayfasının (sekmesinin) 0 tabanlı indeksini belirtmeye olanak tanır
HTML'ye dönüştürülmesi gereken Spreadsheet belgesi (bkz.
notlar).


*** ** * ** ***

Çoğu Spreadsheet belgesi sekme kavramını destekler, yani çok sekmeli olabilir. Öte yandan, HTML formatı bu yapıyı desteklemez. Bu nedenle GroupDocs.Editor, giriş belgesinin yalnızca belirli bir sekmesini HTML'ye dönüştürebilir ve bu seçenek onu belirtmeye olanak tanır. Sekme indeksi 0 tabanlıdır, negatif değerler yasaktır. Belirtilen indeks tüm sekme sayısını aşarsa bir istisna fırlatılır. Giriş Spreadsheet belgesi yalnızca bir sekme içeriyorsa bu seçenek yoksayılır. Varsayılan değer 0'dır (ilk sekme).

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getExcludeHiddenWorksheets() {#getExcludeHiddenWorksheets--}
```
public final boolean getExcludeHiddenWorksheets()
```


Giriş Spreadsheet belgesindeki gizli çalışma sayfalarını dışlamaya olanak tanır, böylece
tamamen göz ardı edilecekler. Varsayılan değer false - gizli çalışma sayfaları
mevcut ve normal şekilde işlenir.


*** ** * ** ***

Birçok ikili Spreadsheet formatı (XLSX gibi) gizli çalışma sayfaları (sekme) kavramını destekler. Bu formatta bir belge, birden fazla çalışma sayfasına sahipse ek gizli çalışma sayfaları içerebilir. Varsayılan olarak bu gizli çalışma sayfaları işleme için mevcuttur, ancak bu seçenekle onları yok sayabilir, sanki bu gizli çalışma sayfaları bulunmuyormuş gibi davranabilirsiniz. Bu seçenek etkinleştirildiğinde, ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))' özelliğiyle gizli çalışma sayfası seçilemez.

<br />



**Returns:**
boolean
### setExcludeHiddenWorksheets(boolean value) {#setExcludeHiddenWorksheets-boolean-}
```
public final void setExcludeHiddenWorksheets(boolean value)
```


Giriş Spreadsheet belgesindeki gizli çalışma sayfalarını dışlamaya olanak tanır, böylece
tamamen göz ardı edilecekler. Varsayılan değer false - gizli çalışma sayfaları
mevcut ve normal şekilde işlenir.


*** ** * ** ***

Birçok ikili Spreadsheet formatı (XLSX gibi) gizli çalışma sayfaları (sekme) kavramını destekler. Bu formatta bir belge, birden fazla çalışma sayfasına sahipse ek gizli çalışma sayfaları içerebilir. Varsayılan olarak bu gizli çalışma sayfaları işleme için mevcuttur, ancak bu seçenekle onları yok sayabilir, sanki bu gizli çalışma sayfaları bulunmuyormuş gibi davranabilirsiniz. Bu seçenek etkinleştirildiğinde, ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))' özelliğiyle gizli çalışma sayfası seçilemez.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getMergeEmptyAdjacentCells() {#getMergeEmptyAdjacentCells--}
```
public boolean getMergeEmptyAdjacentCells()
```


Etkinleştirildiğinde, giriş Spreadsheet belgesindeki boş bitişik yatay hücreler
düzenlenebilir HTML belgesinde karşılık gelen
colspan niteliği. Varsayılan olarak devre dışıdır (false).


Varsayılan olarak GroupDocs.Editor, giriş Spreadsheet belgesindeki bir tabloyu çıktıya dönüştürür
HTML belgesine her hücreyi koruyarak. Ancak, Spreadsheet belgeleri seyrek olabilir \\u2014 onlar
çok sayıda hücrenin boş olduğu \"empty areas\" içerebilir. Bu seçenek,
etkinleştirildiğinde, bu boş hücreleri TD öğesinde colspan niteliğiyle tek bir hücreye birleştirir,
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


Etkinleştirildiğinde, üretilen HTML belgesindeki HTML tablosu, alt kısmında boş bir gizli satır içerir
sıfır yükseklik ve yalnızca genişliğin belirtildiği boş hücreler. Boş hücreli bu satır şunları içerir
her sütun için kesin genişlik değerleri ve HTML'den Elektronik Tablo'ya geri dönüşümü iyileştirir. By
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

