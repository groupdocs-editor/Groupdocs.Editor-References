---
title: "SpreadsheetSaveOptions"
second_title: "GroupDocs.Editor for Java API 참조"
description: "Spreadsheet Excel 호환 문서를 생성하고 저장하기 위한 사용자 지정 옵션을 지정할 수 있습니다"
type: docs
weight: 37
url: /ko/java/com.groupdocs.editor.options/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class SpreadsheetSaveOptions implements ISaveOptions
```

Spreadsheet을 생성하고 저장하기 위한 사용자 지정 옵션을 지정할 수 있습니다
(Excel 호환) 문서

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | 이 매개변수 없는 생성자는 XLSX 출력 형식으로 SpreadsheetSaveOptions의 새 인스턴스를 생성합니다(그 후 다음을 통해 수정할 수 있음 |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) property)
|
|  | [SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)](#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-) | 지정된 필수 항목으로 SpreadsheetSaveOptions의 새 인스턴스를 생성합니다 |
Spreadsheet 출력 형식이며, 다른 모든 매개변수는 기본값입니다
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPassword()](#getPassword--) | 비밀번호를 지정, 수정, 획득 또는 제거할 수 있으며, 이는 |
생성된 Spreadsheet 문서를 인코딩하는 데 사용되며, 해당 문서 형식이
비밀번호 보호를 지원합니다.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 비밀번호를 지정, 수정, 획득 또는 제거할 수 있으며, 이는 |
생성된 Spreadsheet 문서를 인코딩하는 데 사용되며, 해당 문서 형식이
비밀번호 보호를 지원합니다.
|
|  | [getWorksheetNumber()](#getWorksheetNumber--) | 편집된 워크시트를 기존 스프레드시트 복사본에 삽입할 수 있습니다 |
새 단일 워크시트 스프레드시트를 생성하는 대신 (기본값
동작).
|
|  | [setWorksheetNumber(int value)](#setWorksheetNumber-int-) | 편집된 워크시트를 기존 스프레드시트 복사본에 삽입할 수 있습니다 |
새 단일 워크시트 스프레드시트를 생성하는 대신 (기본값
동작).
|
|  | [getInsertAsNewWorksheet()](#getInsertAsNewWorksheet--) | 편집된 워크시트를 교체할지 여부를 지정하는 부울 플래그 |
원본 스프레드시트에서 지정된 위치에 있는 기존 워크시트
그

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
속성, 또는 기존 워크시트와 사이에 삽입되어야 합니다
이전 워크시트 사이에 삽입되며, 내용을 교체하지 않습니다.
|
|  | [setInsertAsNewWorksheet(boolean value)](#setInsertAsNewWorksheet-boolean-) | 편집된 워크시트를 교체할지 여부를 지정하는 부울 플래그 |
원본 스프레드시트에서 지정된 위치에 있는 기존 워크시트
그

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
속성, 또는 기존 워크시트와 사이에 삽입되어야 합니다
이전 워크시트 사이에 삽입되며, 내용을 교체하지 않습니다.
|
|  | [getOutputFormat()](#getOutputFormat--) | 저장에 사용할 Spreadsheet 형식을 지정할 수 있습니다 |
문서
|
|  | [setOutputFormat(SpreadsheetFormats value)](#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-) | 저장에 사용할 Spreadsheet 형식을 지정할 수 있습니다 |
문서
|
|  | [getWorksheetProtection()](#getWorksheetProtection--) | 출력 Spreadsheet에 워크시트 보호를 활성화할 수 있습니다 |
문서.
|
|  | [setWorksheetProtection(WorksheetProtection value)](#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-) | 출력 Spreadsheet에 워크시트 보호를 활성화할 수 있습니다 |
문서.
|
|  | [getWorksheetNumbersToDelete()](#getWorksheetNumbersToDelete--) | 편집된 워크시트가 기존 스프레드시트에 삽입될 경우, 저장 중에 스프레드시트에서 삭제해야 할 1 기반 워크시트 번호 배열을 지정할 수 있습니다 |
|
|  | [setWorksheetNumbersToDelete(int[] value)](#setWorksheetNumbersToDelete-int---) | 편집된 워크시트가 기존 스프레드시트에 삽입될 경우, 저장 중에 스프레드시트에서 삭제해야 할 1 기반 워크시트 번호 배열을 지정할 수 있습니다 |
|
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


이 매개변수 없는 생성자는 XLSX 출력 형식으로 SpreadsheetSaveOptions의 새 인스턴스를 생성합니다(그 후 다음을 통해 수정할 수 있음
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) property)


### SpreadsheetSaveOptions(SpreadsheetFormats outputFormat) {#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)
```


지정된 필수 항목으로 SpreadsheetSaveOptions의 새 인스턴스를 생성합니다
Spreadsheet 출력 형식이며, 다른 모든 매개변수는 기본값입니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | outputFormat | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) | Spreadsheet 문서를 저장해야 하는 필수 출력 형식 |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


비밀번호를 지정, 수정, 획득 또는 제거할 수 있으며, 이는
생성된 Spreadsheet 문서를 인코딩하는 데 사용되며, 해당 문서 형식이
비밀번호 보호를 지원합니다. 제거하려면 NULL 또는 빈 문자열을 지정하십시오
(cleaning) 비밀번호.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


비밀번호를 지정, 수정, 획득 또는 제거할 수 있으며, 이는
생성된 Spreadsheet 문서를 인코딩하는 데 사용되며, 해당 문서 형식이
비밀번호 보호를 지원합니다. 제거하려면 NULL 또는 빈 문자열을 지정하십시오
(cleaning) 비밀번호.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getWorksheetNumber() {#getWorksheetNumber--}
```
public final int getWorksheetNumber()
```


편집된 워크시트를 기존 스프레드시트 복사본에 삽입할 수 있습니다
새 단일 워크시트 스프레드시트를 생성하는 대신 (기본값
behavior). WorksheetNumber는 워크시트의 1부터 시작하는 번호입니다.
스프레드시트, Editor 클래스에 로드됩니다. 값이 0(기본값)인 경우, the
새 스프레드시트가 단일 편집 워크시트와 함께 생성됩니다. If it is
0보다 크거나 작고, 유효한 스프레드시트가 로드된
Editor 클래스에서, 입력에 의해 표현되는 편집된 워크시트
EditableDocument 인스턴스가 이 스프레드시트에 삽입됩니다.


*** ** * ** ***

> ```
> Given spreadsheet has 5 worksheets:
>  WorksheetNumber  = 0; \u2014 ignore given spreadsheet, create a new spreadsheet and put edited worksheet into it.
>  WorksheetNumber  = 1; \u2014 replace the first worksheet with edited
>  WorksheetNumber  = 2; \u2014 replace the second worksheet with edited
>  WorksheetNumber  = 5; \u2014 replace the last (5th) worksheet with edited
>  WorksheetNumber  = 6; \u2014 replace the last (5th) worksheet with edited, because 6 is greater then 5 and thus is adjusted
>  WorksheetNumber = -1; \u2014 replace the last (5th) worksheet with edited, because "-1" means "last existing"
>  WorksheetNumber = -2; \u2014 replace the 4th worksheet with edited
>  WorksheetNumber = -3; \u2014 replace the 3rd worksheet with edited
>  WorksheetNumber = -4; \u2014 replace the 2nd worksheet with edited
>  WorksheetNumber = -5; \u2014 replace the first worksheet with edited
>  WorksheetNumber = -6; \u2014 replace the first worksheet with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />


*** ** * ** ***

 *WorksheetNumber*  integer property, if it is not in default state (reserved value '0'), represents a worksheet number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last worksheet. Negative values are also allowed and count worksheets from end. For example, "-1" implies last worksheet in a spreadsheet, "-2" \\u2014 last but one, etc. Like with positive values, when negative worksheet number exceeds the total count of worksheets in the given spreadsheet, it will be adjusted to the first worksheet. The  InsertAsNewWorksheet (#getInsertAsNewWorksheet.getInsertAsNewWorksheet/#setInsertAsNewWorksheet(boolean).setInsertAsNewWorksheet(boolean)) boolean property is tightly coupled with this one.

<br />



**Returns:**
int -
### setWorksheetNumber(int value) {#setWorksheetNumber-int-}
```
public final void setWorksheetNumber(int value)
```


편집된 워크시트를 기존 스프레드시트 복사본에 삽입할 수 있습니다
새 단일 워크시트 스프레드시트를 생성하는 대신 (기본값
behavior). WorksheetNumber는 워크시트의 1부터 시작하는 번호입니다.
스프레드시트, Editor 클래스에 로드됩니다. 값이 0(기본값)인 경우, the
새 스프레드시트가 단일 편집 워크시트와 함께 생성됩니다. If it is
0보다 크거나 작고, 유효한 스프레드시트가 로드된
Editor 클래스에서, 입력에 의해 표현되는 편집된 워크시트
EditableDocument 인스턴스가 이 스프레드시트에 삽입됩니다.


*** ** * ** ***

> ```
> Given spreadsheet has 5 worksheets:
>  WorksheetNumber  = 0; \u2014 ignore given spreadsheet, create a new spreadsheet and put edited worksheet into it.
>  WorksheetNumber  = 1; \u2014 replace the first worksheet with edited
>  WorksheetNumber  = 2; \u2014 replace the second worksheet with edited
>  WorksheetNumber  = 5; \u2014 replace the last (5th) worksheet with edited
>  WorksheetNumber  = 6; \u2014 replace the last (5th) worksheet with edited, because 6 is greater then 5 and thus is adjusted
>  WorksheetNumber = -1; \u2014 replace the last (5th) worksheet with edited, because "-1" means "last existing"
>  WorksheetNumber = -2; \u2014 replace the 4th worksheet with edited
>  WorksheetNumber = -3; \u2014 replace the 3rd worksheet with edited
>  WorksheetNumber = -4; \u2014 replace the 2nd worksheet with edited
>  WorksheetNumber = -5; \u2014 replace the first worksheet with edited
>  WorksheetNumber = -6; \u2014 replace the first worksheet with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />


*** ** * ** ***

 *WorksheetNumber*  integer property, if it is not in default state (reserved value '0'), represents a worksheet number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last worksheet. Negative values are also allowed and count worksheets from end. For example, "-1" implies last worksheet in a spreadsheet, "-2" \\u2014 last but one, etc. Like with positive values, when negative worksheet number exceeds the total count of worksheets in the given spreadsheet, it will be adjusted to the first worksheet. The  InsertAsNewWorksheet (#getInsertAsNewWorksheet.getInsertAsNewWorksheet/#setInsertAsNewWorksheet(boolean).setInsertAsNewWorksheet(boolean)) boolean property is tightly coupled with this one.

<br />



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getInsertAsNewWorksheet() {#getInsertAsNewWorksheet--}
```
public final boolean getInsertAsNewWorksheet()
```


편집된 워크시트를 교체할지 여부를 지정하는 부울 플래그
원본 스프레드시트에서 지정된 위치에 있는 기존 워크시트
그

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
속성, 또는 기존 워크시트와 사이에 삽입되어야 합니다
이전 워크시트이며, 내용을 교체하지 않습니다. 기본값은 false \\u2014
기존 워크시트가 교체됩니다. 이 속성은 값이
의

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
속성이 '0'으로 설정됩니다.


*** ** * ** ***

기본적으로 워크시트가 교체됩니다. 이는 주어진 스프레드시트에 워크시트가 5개 있고, WorksheetNumber (#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))=4인 경우, 4번째 워크시트가 새로운 편집 워크시트로 교체되며, 스프레드시트의 전체 워크시트 수(5)는 변하지 않음을 의미합니다. 그러나 이 속성의 값이  *true* 로 설정되면, 새로운 편집 워크시트가 4번째 워크시트로 삽입되고, 이후의 모든 워크시트가 끝으로 이동합니다: \"old\" 4번째 워크시트는 5번째가 되고, 5번째는 6번째가 되며, 스프레드시트의 전체 워크시트 수는 하나 증가하여 6이 됩니다.

<br />



**Returns:**
boolean -
### setInsertAsNewWorksheet(boolean value) {#setInsertAsNewWorksheet-boolean-}
```
public final void setInsertAsNewWorksheet(boolean value)
```


편집된 워크시트를 교체할지 여부를 지정하는 부울 플래그
원본 스프레드시트에서 지정된 위치에 있는 기존 워크시트
그

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
속성, 또는 기존 워크시트와 사이에 삽입되어야 합니다
이전 워크시트이며, 내용을 교체하지 않습니다. 기본값은 false \\u2014
기존 워크시트가 교체됩니다. 이 속성은 값이
의

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
속성이 '0'으로 설정됩니다.


*** ** * ** ***

기본적으로 워크시트가 교체됩니다. 이는 주어진 스프레드시트에 워크시트가 5개 있고, WorksheetNumber (#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))=4인 경우, 4번째 워크시트가 새로운 편집 워크시트로 교체되며, 스프레드시트의 전체 워크시트 수(5)는 변하지 않음을 의미합니다. 그러나 이 속성의 값이  *true* 로 설정되면, 새로운 편집 워크시트가 4번째 워크시트로 삽입되고, 이후의 모든 워크시트가 끝으로 이동합니다: \"old\" 4번째 워크시트는 5번째가 되고, 5번째는 6번째가 되며, 스프레드시트의 전체 워크시트 수는 하나 증가하여 6이 됩니다.

<br />



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final SpreadsheetFormats getOutputFormat()
```


저장에 사용할 Spreadsheet 형식을 지정할 수 있습니다
문서


**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - 
### setOutputFormat(SpreadsheetFormats value) {#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public final void setOutputFormat(SpreadsheetFormats value)
```


저장에 사용할 Spreadsheet 형식을 지정할 수 있습니다
문서


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) |  |

### getWorksheetProtection() {#getWorksheetProtection--}
```
public final WorksheetProtection getWorksheetProtection()
```


출력 Spreadsheet에 워크시트 보호를 활성화할 수 있습니다
문서. 기본값은 NULL이며, 보호가 적용되지 않습니다. 모든 형식이
워크시트 보호를 지원합니다.


**Returns:**
[WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) - 
### setWorksheetProtection(WorksheetProtection value) {#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-}
```
public final void setWorksheetProtection(WorksheetProtection value)
```


출력 Spreadsheet에 워크시트 보호를 활성화할 수 있습니다
문서. 기본값은 NULL이며, 보호가 적용되지 않습니다. 모든 형식이
워크시트 보호를 지원합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) |  |

### getWorksheetNumbersToDelete() {#getWorksheetNumbersToDelete--}
```
public final int[] getWorksheetNumbersToDelete()
```


편집된 워크시트가 기존 스프레드시트에 삽입되는 경우, 저장 중에 스프레드시트에서 삭제해야 할 워크시트의 1부터 시작하는 번호 배열을 지정할 수 있습니다. 편집된 워크시트를 새로운 단일 워크시트 스프레드시트(기본 동작)로 저장하는 대신 기존 스프레드시트에 저장할 때(#getWorksheetNumber().getWorksheetNumber() / #setWorksheetNumber(int).setWorksheetNumber(int) 사용), 이 배열에 번호를 지정하여 해당 스프레드시트의 특정 워크시트를 삭제할 수도 있습니다. 기본적으로 이 배열은  null  \\u2014 워크시트가 삭제되지 않습니다. 그러나 이 배열이 null이 아니고 비어 있지 않으며 최소 하나의 유효한 워크시트 번호를 포함하는 경우, 편집 워크시트의 내용으로 출력 스프레드시트 문서가 생성된 후, 지정된 번호의 워크시트가 스프레드시트에서 삭제되고, 내용이 출력 스트림이나 파일에 기록되기 직전에 적용됩니다. 이 배열의 워크시트 번호는 1부터 시작하며 0부터 시작하지 않습니다. 유효하지 않은 번호(1보다 작거나 전체 워크시트 수보다 큰)는 무시됩니다.


**Returns:**
int[] - 삭제할 1부터 시작하는 워크시트 번호 배열, 또는 삭제할 것이 없으면  null 

### setWorksheetNumbersToDelete(int[] value) {#setWorksheetNumbersToDelete-int---}
```
public final void setWorksheetNumbersToDelete(int[] value)
```


편집된 워크시트가 기존 스프레드시트에 삽입되는 경우, 저장 중에 스프레드시트에서 삭제해야 할 워크시트의 1부터 시작하는 번호 배열을 지정할 수 있습니다. 이 배열의 워크시트 번호는 1부터 시작합니다. 유효하지 않은 번호는 무시됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | int[] | 삭제할 1부터 시작하는 워크시트 번호 배열 (null이거나 비어 있을 수 있음). |
|

