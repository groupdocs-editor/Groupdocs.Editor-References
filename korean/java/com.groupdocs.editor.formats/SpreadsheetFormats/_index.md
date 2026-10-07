---
title: "SpreadsheetFormats"
second_title: "GroupDocs.Editor for Java API 참조"
description: "워크북을 저장할 수 있는 CSV, TSV, 세미콜론 구분 등 구분자 기반 텍스트 형식을 제외하고, 모든 이진 XML 및 텍스트 스프레드시트 형식을 캡슐화합니다."
type: docs
weight: 15
url: /ko/java/com.groupdocs.editor.formats/spreadsheetformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class SpreadsheetFormats extends DocumentFormatBase
```

워크북을 저장할 수 있는 모든 이진, XML 및 텍스트 스프레드시트 형식을 캡슐화합니다(CSV, TSV, 세미콜론 구분 등 구분자를 사용하는 모든 텍스트 형식은 제외).
다음 형식이 포함됩니다:
[Dif](../../com.groupdocs.editor.formats/spreadsheetformats#Dif),
[Fods](../../com.groupdocs.editor.formats/spreadsheetformats#Fods),
[Ods](../../com.groupdocs.editor.formats/spreadsheetformats#Ods),
[Sxc](../../com.groupdocs.editor.formats/spreadsheetformats#Sxc),
[Xlam](../../com.groupdocs.editor.formats/spreadsheetformats#Xlam),
[Xls](../../com.groupdocs.editor.formats/spreadsheetformats#Xls),
[Xlsb](../../com.groupdocs.editor.formats/spreadsheetformats#Xlsb),
[Xlsm](../../com.groupdocs.editor.formats/spreadsheetformats#Xlsm),
[Xlsx](../../com.groupdocs.editor.formats/spreadsheetformats#Xlsx),
[Xlt](../../com.groupdocs.editor.formats/spreadsheetformats#Xlt),
[Xltm](../../com.groupdocs.editor.formats/spreadsheetformats#Xltm),
[Xltx](../../com.groupdocs.editor.formats/spreadsheetformats#Xltx).
스프레드시트 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/spreadsheet)에서 확인하세요.

## 필드

| 필드 | 설명 |
| --- | --- |
|  | [Xls](#Xls) | Excel 97-2003 이진 파일 형식 (XLS). |
|
|  | [Xlt](#Xlt) | Excel 97-2003 템플릿 (XLT). |
|
|  | [Xlsx](#Xlsx) | Office Open XML 워크북 매크로 없음 (XLSX). |
|
|  | [Xlsm](#Xlsm) | Office Open XML 워크북 매크로 사용 (XLSM). |
|
|  | [Xlsb](#Xlsb) | Excel 이진 워크북 (XLSB). |
|
|  | [Xltx](#Xltx) | Office Open XML 템플릿 매크로 없음 (XLTX). |
|
|  | [Xltm](#Xltm) | Office Open XML 템플릿 매크로 포함 (XLTM). |
|
|  | [Xlam](#Xlam) | Excel 추가 기능 (XLAM). |
|
|  | [SpreadsheetML](#SpreadsheetML) | SpreadsheetML — Microsoft Office Excel 2002 및 Excel 2003 XML 형식. |
|
|  | [Ods](#Ods) | OpenDocument 스프레드시트 (ODS). |
|
|  | [Fods](#Fods) | Flat OpenDocument 스프레드시트 (FODS). |
|
|  | [Sxc](#Sxc) | StarOffice 또는 OpenOffice.org Calc XML 스프레드시트 (SXC). |
|
|  | [Dif](#Dif) | 데이터 교환 형식 (DIF). |
|
|  | [Csv](#Csv) | 쉼표로 구분된 값 (CSV). |
|
|  | [Tsv](#Tsv) | 탭으로 구분된 값 (TSV). |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getAll()](#getAll--) | 모든 [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats)의 열거 가능한 컬렉션을 가져옵니다. |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | 지정된 파일 확장자를 가진 지정된 유형 [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats)의 인스턴스를 검색합니다. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | 파일 확장자를 나타내는 문자열을 [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) 객체로 변환합니다. |
|
### Xls {#Xls}
```
public static final SpreadsheetFormats Xls
```


Excel 97-2003 이진 파일 형식 (XLS).
이 파일 형식에 대해 자세히 알아보세요
[here](../https://wiki.fileformat.com/spreadsheet/xls)
.


### Xlt {#Xlt}
```
public static final SpreadsheetFormats Xlt
```


Excel 97-2003 템플릿 (XLT).
이 파일 형식에 대해 자세히 알아보세요
[here](../https://wiki.fileformat.com/spreadsheet/xlt)
.


### Xlsx {#Xlsx}
```
public static final SpreadsheetFormats Xlsx
```


Office Open XML 워크북 매크로 없음 (XLSX).
이 파일 형식에 대해 자세히 알아보세요
[here](../https://wiki.fileformat.com/spreadsheet/xlsx)
.


### Xlsm {#Xlsm}
```
public static final SpreadsheetFormats Xlsm
```


Office Open XML 워크북 매크로 사용 (XLSM).
이 파일 형식에 대해 자세히 알아보세요
[here](../https://wiki.fileformat.com/spreadsheet/xlsm)
.


### Xlsb {#Xlsb}
```
public static final SpreadsheetFormats Xlsb
```


Excel 이진 워크북 (XLSB).
이 파일 형식에 대해 자세히 알아보세요
[here](../https://wiki.fileformat.com/spreadsheet/xlsb)
.


### Xltx {#Xltx}
```
public static final SpreadsheetFormats Xltx
```


Office Open XML 템플릿 매크로 없음 (XLTX).
이 파일 형식에 대해 자세히 알아보세요
[here](../https://wiki.fileformat.com/spreadsheet/xltx)
.


### Xltm {#Xltm}
```
public static final SpreadsheetFormats Xltm
```


Office Open XML 템플릿 매크로 포함 (XLTM).
이 파일 형식에 대해 자세히 알아보세요
[here](../https://wiki.fileformat.com/spreadsheet/xltm)
.


### Xlam {#Xlam}
```
public static final SpreadsheetFormats Xlam
```


Excel 추가 기능 (XLAM).


### SpreadsheetML {#SpreadsheetML}
```
public static final SpreadsheetFormats SpreadsheetML
```


SpreadsheetML — Microsoft Office Excel 2002 및 Excel 2003 XML 형식.


### Ods {#Ods}
```
public static final SpreadsheetFormats Ods
```


OpenDocument 스프레드시트 (ODS).
이 파일 형식에 대해 자세히 알아보세요
[here](../https://wiki.fileformat.com/spreadsheet/ods)
.


### Fods {#Fods}
```
public static final SpreadsheetFormats Fods
```


Flat OpenDocument 스프레드시트 (FODS).


### Sxc {#Sxc}
```
public static final SpreadsheetFormats Sxc
```


StarOffice 또는 OpenOffice.org Calc XML 스프레드시트 (SXC).


### Dif {#Dif}
```
public static final SpreadsheetFormats Dif
```


데이터 교환 형식 (DIF).


### Csv {#Csv}
```
public static final SpreadsheetFormats Csv
```


쉼표로 구분된 값 (CSV).
이 파일 형식에 대해 자세히 알아보세요
[here](../https://docs.fileformat.com/spreadsheet/csv/)
.


### Tsv {#Tsv}
```
public static final SpreadsheetFormats Tsv
```


탭으로 구분된 값 (TSV).
이 파일 형식에 대해 자세히 알아보세요
[here](../https://docs.fileformat.com/spreadsheet/tsv/)
.


### getAll() {#getAll--}
```
public static List<SpreadsheetFormats> getAll()
```


모든 [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats)의 열거 가능한 컬렉션을 가져옵니다.
값: 모든 [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) 인스턴스를 포함하는 IEnumerable{SpreadsheetFormats}.


**Returns:**
java.util.List<com.groupdocs.editor.formats.SpreadsheetFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static SpreadsheetFormats fromExtension(String extension)
```


지정된 파일 확장자를 가진 지정된 유형 [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats)의 인스턴스를 검색합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 확장자 | java.lang.String | 문서 형식의 파일 확장자입니다. |
|

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - An instance of the specified type [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static SpreadsheetFormats fromString(String extension)
```


파일 확장자를 나타내는 문자열을 [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) 객체로 변환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 확장자 | java.lang.String | 변환할 파일 확장자입니다. 확장자에 마침표가 여러 개 포함된 경우, 마지막 마침표 이후의 부분이 사용됩니다. |
|

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - A [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) object corresponding to the specified file extension.

