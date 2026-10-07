---
title: "MarkdownSaveOptions"
second_title: "GroupDocs.Editor for Java API 참조"
description: "Markdown 문서를 생성 및 저장하기 위한 사용자 지정 옵션을 지정할 수 있습니다."
type: docs
weight: 24
url: /ko/java/com.groupdocs.editor.options/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MarkdownSaveOptions implements ISaveOptions
```

Markdown 문서를 생성 및 저장하기 위한 사용자 지정 옵션을 지정할 수 있습니다.

<br />

*** ** * ** ***

EditableDocument 클래스의 인스턴스가 존재하고 편집된 문서 내용이 포함되어 있으며, 해당 내용을 Markdown 형식의 새 문서로 저장해야 할 경우 사용자가 MarkdownSaveOptions 클래스를 적용해야 합니다.

<br />


## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | HTML에서 문서를 생성하는 동안 메모리 사용량을 감소시키는 대가로 성능이 저하되는 메모리 최적화 메커니즘을 활성화합니다. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | HTML에서 문서를 생성하는 동안 메모리 사용량을 감소시키는 대가로 성능이 저하되는 메모리 최적화 메커니즘을 활성화합니다. |
|
|  | [getTableContentAlignment()](#getTableContentAlignment--) | Allow는 Markdown 형식으로 내보낼 때 표의 내용 정렬 방식을 지정합니다. |
|
|  | [setTableContentAlignment(int value)](#setTableContentAlignment-int-) | Allow는 Markdown 형식으로 내보낼 때 표의 내용 정렬 방식을 지정합니다. |
|
|  | [getImagesFolder()](#getImagesFolder--) | 문서를 내보낼 때 이미지가 저장되는 물리적 폴더를 지정합니다. |
Markdown 형식.
|
|  | [setImagesFolder(String value)](#setImagesFolder-java.lang.String-) | 문서를 내보낼 때 이미지가 저장되는 물리적 폴더를 지정합니다. |
Markdown 형식.
|
|  | [getExportImagesAsBase64()](#getExportImagesAsBase64--) | 이미지를 출력 파일에 Base64 형식으로 저장할지 여부를 지정합니다. |
|
|  | [setExportImagesAsBase64(boolean value)](#setExportImagesAsBase64-boolean-) | 이미지를 출력 파일에 Base64 형식으로 저장할지 여부를 지정합니다. |
|
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```


### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


HTML에서 문서를 생성하는 동안 메모리 사용량을 감소시키는 대가로 성능이 저하되는 메모리 최적화 메커니즘을 활성화합니다.
이 옵션을
또는 HTML 마크업에 삽입하여 HTML-\>HEAD 섹션의 STYLE 요소 내부에 포함합니다 (
대형 문서를 생성하는 동안 메모리 사용량을 크게 줄일 수 있지만 저장 시간이 느려지는 대가가 있습니다.
기본값은
false
(성능 향상을 위해 메모리 최적화가 비활성화됩니다).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


HTML에서 문서를 생성하는 동안 메모리 사용량을 감소시키는 대가로 성능이 저하되는 메모리 최적화 메커니즘을 활성화합니다.
이 옵션을
또는 HTML 마크업에 삽입하여 HTML-\>HEAD 섹션의 STYLE 요소 내부에 포함합니다 (
대형 문서를 생성하는 동안 메모리 사용량을 크게 줄일 수 있지만 저장 시간이 느려지는 대가가 있습니다.
기본값은
false
(성능 향상을 위해 메모리 최적화가 비활성화됩니다).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getTableContentAlignment() {#getTableContentAlignment--}
```
public final int getTableContentAlignment()
```


Allow는 Markdown 형식으로 내보낼 때 표의 내용 정렬 방식을 지정합니다.
기본값은 [MarkdownTableContentAlignment.Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment#Auto)입니다.
값: 표 내용 정렬


**Returns:**
int
### setTableContentAlignment(int value) {#setTableContentAlignment-int-}
```
public final void setTableContentAlignment(int value)
```


Allow는 Markdown 형식으로 내보낼 때 표의 내용 정렬 방식을 지정합니다.
기본값은 [MarkdownTableContentAlignment.Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment#Auto)입니다.
값: 표 내용 정렬


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getImagesFolder() {#getImagesFolder--}
```
public final String getImagesFolder()
```


문서를 내보낼 때 이미지가 저장되는 물리적 폴더를 지정합니다.
Markdown 형식. 기본값은 null입니다.

<br />

*** ** * ** ***

사용자가 ImagesFolder(#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String))와 ExportImagesAsBase64(#getExportImagesAsBase64.getExportImagesAsBase64/#setExportImagesAsBase64(boolean).setExportImagesAsBase64(boolean)) 중 어느 것도 지정하지 않으면, GroupDocs.Editor가 스스로 ImagesFolder(#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String))를 판단하여 성공 시 적용합니다.

<br />



**Returns:**
java.lang.String
### setImagesFolder(String value) {#setImagesFolder-java.lang.String-}
```
public final void setImagesFolder(String value)
```


문서를 내보낼 때 이미지가 저장되는 물리적 폴더를 지정합니다.
Markdown 형식. 기본값은 null입니다.

<br />

*** ** * ** ***

사용자가 ImagesFolder(#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String))와 ExportImagesAsBase64(#getExportImagesAsBase64.getExportImagesAsBase64/#setExportImagesAsBase64(boolean).setExportImagesAsBase64(boolean)) 중 어느 것도 지정하지 않으면, GroupDocs.Editor가 스스로 ImagesFolder(#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String))를 판단하여 성공 시 적용합니다.

<br />



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getExportImagesAsBase64() {#getExportImagesAsBase64--}
```
public final boolean getExportImagesAsBase64()
```


이미지를 출력 파일에 Base64 형식으로 저장할지 여부를 지정합니다. 기본값은
false
.

<br />

*** ** * ** ***

이 속성이 true 로 설정되면 이미지 데이터가 ![](../) 이미지 요소에 직접 내보내지며 별도의 파일이 생성되지 않습니다. 이 속성이 true 로 설정된 경우, MarkdownSaveOptions.ImagesFolder(#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) 속성보다 높은 우선순위를 가집니다.

<br />



**Returns:**
boolean
### setExportImagesAsBase64(boolean value) {#setExportImagesAsBase64-boolean-}
```
public final void setExportImagesAsBase64(boolean value)
```


이미지를 출력 파일에 Base64 형식으로 저장할지 여부를 지정합니다. 기본값은
false
.

<br />

*** ** * ** ***

이 속성이 true 로 설정되면 이미지 데이터가 ![](../) 이미지 요소에 직접 내보내지며 별도의 파일이 생성되지 않습니다. 이 속성이 true 로 설정된 경우, MarkdownSaveOptions.ImagesFolder(#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) 속성보다 높은 우선순위를 가집니다.

<br />



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

