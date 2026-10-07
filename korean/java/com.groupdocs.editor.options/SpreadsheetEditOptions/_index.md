---
title: "SpreadsheetEditOptions"
second_title: "GroupDocs.Editor for Java API 참조"
description: "지원되는 모든 Spreadsheet Excel 호환 형식 문서를 편집하기 위한 사용자 지정 옵션을 지정할 수 있습니다."
type: docs
weight: 35
url: /ko/java/com.groupdocs.editor.options/spreadsheeteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class SpreadsheetEditOptions implements IEditOptions
```

DOCX, RTF, ODT 등 지원 가능한 모든 WordProcessing Words 호환 형식의 문서를 편집하기 위한 사용자 지정 옵션을 지정할 수 있습니다.
Spreadsheet (Excel 호환) 형식

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [SpreadsheetEditOptions()](#SpreadsheetEditOptions--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | 입력 워크시트(탭)의 0 기반 인덱스를 지정할 수 있습니다. |
HTML로 변환되어야 하는 Spreadsheet 문서(참조
remarks).
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | 입력 워크시트(탭)의 0 기반 인덱스를 지정할 수 있습니다. |
HTML로 변환되어야 하는 Spreadsheet 문서(참조
remarks).
|
|  | [getExcludeHiddenWorksheets()](#getExcludeHiddenWorksheets--) | 입력 Spreadsheet 문서에서 숨겨진 워크시트를 제외할 수 있으므로 |
해당 워크시트는 완전히 무시됩니다.
|
|  | [setExcludeHiddenWorksheets(boolean value)](#setExcludeHiddenWorksheets-boolean-) | 입력 Spreadsheet 문서에서 숨겨진 워크시트를 제외할 수 있으므로 |
해당 워크시트는 완전히 무시됩니다.
|
|  | [getMergeEmptyAdjacentCells()](#getMergeEmptyAdjacentCells--) | 활성화하면, 입력 Spreadsheet 문서의 인접한 빈 가로 셀은 |
편집 가능한 HTML 문서에서 해당 셀과 연결된 하나의 셀로 병합되어 표시됩니다.
colspan 속성.
|
| [setMergeEmptyAdjacentCells(boolean value)](#setMergeEmptyAdjacentCells-boolean-) |  |
|  | [getExportBogusRowData()](#getExportBogusRowData--) | 활성화하면, 생성된 HTML 문서의 HTML 테이블에 빈 하단 숨김 행이 포함되며 |
높이가 0이고 셀은 비어 있으며, 너비만 지정됩니다.
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


입력 워크시트(탭)의 0 기반 인덱스를 지정할 수 있습니다.
HTML로 변환되어야 하는 Spreadsheet 문서(참조
remarks).


*** ** * ** ***

대부분의 Spreadsheet 문서는 탭 개념을 지원하므로 다중 탭을 가질 수 있습니다. 반면 HTML 형식은 이러한 구조를 지원하지 않습니다. 따라서 GroupDocs.Editor는 입력 문서의 특정 탭 하나만 HTML로 변환할 수 있으며, 이 옵션을 통해 해당 탭을 지정할 수 있습니다. 탭 인덱스는 0 기반이며, 음수 값은 허용되지 않습니다. 지정된 인덱스가 전체 탭 수를 초과하면 예외가 발생합니다. 입력 Spreadsheet 문서에 탭이 하나만 있는 경우 이 옵션은 무시됩니다. 기본값은 0(첫 번째 탭)입니다.

<br />



**Returns:**
int
### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


입력 워크시트(탭)의 0 기반 인덱스를 지정할 수 있습니다.
HTML로 변환되어야 하는 Spreadsheet 문서(참조
remarks).


*** ** * ** ***

대부분의 Spreadsheet 문서는 탭 개념을 지원하므로 다중 탭을 가질 수 있습니다. 반면 HTML 형식은 이러한 구조를 지원하지 않습니다. 따라서 GroupDocs.Editor는 입력 문서의 특정 탭 하나만 HTML로 변환할 수 있으며, 이 옵션을 통해 해당 탭을 지정할 수 있습니다. 탭 인덱스는 0 기반이며, 음수 값은 허용되지 않습니다. 지정된 인덱스가 전체 탭 수를 초과하면 예외가 발생합니다. 입력 Spreadsheet 문서에 탭이 하나만 있는 경우 이 옵션은 무시됩니다. 기본값은 0(첫 번째 탭)입니다.

<br />



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getExcludeHiddenWorksheets() {#getExcludeHiddenWorksheets--}
```
public final boolean getExcludeHiddenWorksheets()
```


입력 Spreadsheet 문서에서 숨겨진 워크시트를 제외할 수 있으므로
해당 워크시트는 완전히 무시됩니다. 기본값은 false이며 - 숨겨진 워크시트는
사용 가능하고 정상적으로 처리됩니다.


*** ** * ** ***

XLSX와 같은 일부 바이너리 Spreadsheet 형식은 숨겨진 워크시트(탭) 개념을 지원합니다. 이러한 형식의 문서는 워크시트가 하나 이상인 경우 추가 숨겨진 워크시트를 포함할 수 있습니다. 기본적으로 이러한 숨겨진 워크시트는 처리 가능하지만, 이 옵션을 사용하면 해당 워크시트가 존재하지 않는 것처럼 무시할 수 있습니다. 이 옵션이 활성화되면 'WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))' 속성을 사용하여 숨겨진 워크시트를 선택할 수 없습니다.

<br />



**Returns:**
boolean
### setExcludeHiddenWorksheets(boolean value) {#setExcludeHiddenWorksheets-boolean-}
```
public final void setExcludeHiddenWorksheets(boolean value)
```


입력 Spreadsheet 문서에서 숨겨진 워크시트를 제외할 수 있으므로
해당 워크시트는 완전히 무시됩니다. 기본값은 false이며 - 숨겨진 워크시트는
사용 가능하고 정상적으로 처리됩니다.


*** ** * ** ***

XLSX와 같은 일부 바이너리 Spreadsheet 형식은 숨겨진 워크시트(탭) 개념을 지원합니다. 이러한 형식의 문서는 워크시트가 하나 이상인 경우 추가 숨겨진 워크시트를 포함할 수 있습니다. 기본적으로 이러한 숨겨진 워크시트는 처리 가능하지만, 이 옵션을 사용하면 해당 워크시트가 존재하지 않는 것처럼 무시할 수 있습니다. 이 옵션이 활성화되면 'WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))' 속성을 사용하여 숨겨진 워크시트를 선택할 수 없습니다.

<br />



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getMergeEmptyAdjacentCells() {#getMergeEmptyAdjacentCells--}
```
public boolean getMergeEmptyAdjacentCells()
```


활성화하면, 입력 Spreadsheet 문서의 인접한 빈 가로 셀은
편집 가능한 HTML 문서에서 해당 셀과 연결된 하나의 셀로 병합되어 표시됩니다.
colspan 속성. 기본값은 비활성화(false)입니다.


기본적으로 GroupDocs.Editor는 입력 Spreadsheet 문서의 테이블을 출력으로 변환합니다.
각 셀을 보존하면서 HTML 문서로 변환합니다. 그러나 Spreadsheet 문서는 희소할 수 있습니다 —
많은 셀들이 비어 있는 \"empty areas\"이 대량으로 존재할 수 있습니다. 이 옵션은,
활성화되면, 이러한 빈 셀들을 TD 요소의 colspan 속성을 가진 하나의 셀로 병합합니다,
그 결과 생성된 HTML 마크업의 크기를 크게 줄일 수 있습니다.


**Returns:**
boolean
### setMergeEmptyAdjacentCells(boolean value) {#setMergeEmptyAdjacentCells-boolean-}
```
public void setMergeEmptyAdjacentCells(boolean value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getExportBogusRowData() {#getExportBogusRowData--}
```
public boolean getExportBogusRowData()
```


활성화하면, 생성된 HTML 문서의 HTML 테이블에 빈 하단 숨김 행이 포함되며
높이가 0이고 셀은 비어 있으며, 너비만 지정됩니다. 이 빈 셀을 가진 행은
각 열에 대한 정확한 너비 값을 포함하고 HTML에서 Spreadsheet로의 역변환을 개선합니다. 기본적으로
기본값은 활성화(true)입니다.


**Returns:**
boolean
### setExportBogusRowData(boolean value) {#setExportBogusRowData-boolean-}
```
public void setExportBogusRowData(boolean value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

