---
title: "XmlFormatOptions"
second_title: "GroupDocs.Editor for Java API 참조"
description: "XML 문서가 HTML로 표시될 때 형식을 조정할 수 있는 옵션을 포함합니다."
type: docs
weight: 52
url: /ko/java/com.groupdocs.editor.options/xmlformatoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlFormatOptions implements IEditOptions
```

XML 문서를 HTML로 표시할 때 서식을 조정할 수 있는 옵션을 포함합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getEachAttributeFromNewline()](#getEachAttributeFromNewline--) | 활성화되면 모든 XML 요소의 모든 속성-값 쌍이 새 줄에 배치됩니다. |
|
|  | [setEachAttributeFromNewline(boolean value)](#setEachAttributeFromNewline-boolean-) | 활성화되면 모든 XML 요소의 모든 속성-값 쌍이 새 줄에 배치됩니다. |
|
|  | [getLeafTextNodesOnNewline()](#getLeafTextNodesOnNewline--) | 활성화되면 리프 텍스트 노드(자식이 없는 XML 요소 내부의 �스트 내용)가 더 큰 왼쪽 들여쓰기로 새 줄에 표시됩니다. |
|
|  | [setLeafTextNodesOnNewline(boolean value)](#setLeafTextNodesOnNewline-boolean-) | 활성화되면 리프 텍스트 노드(자식이 없는 XML 요소 내부의 �스트 내용)가 더 큰 왼쪽 들여쓰기로 새 줄에 표시됩니다. |
|
|  | [getLeftIndent()](#getLeftIndent--) | 각 새 줄의 왼쪽 들여쓰기 오프셋을 지정할 수 있습니다. |
|
|  | [setLeftIndent(Length value)](#setLeftIndent-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | 각 새 줄의 왼쪽 들여쓰기 오프셋을 지정할 수 있습니다. |
|
|  | [isDefault()](#isDefault--) | 이 XML 서식 옵션 인스턴스에 기본값이 있는지 여부를 나타냅니다. |
|
### getEachAttributeFromNewline() {#getEachAttributeFromNewline--}
```
public final boolean getEachAttributeFromNewline()
```


활성화되면 모든 XML 요소의 모든 속성-값 쌍이 새 줄에 배치됩니다.
기본값은 false(비활성화) \\u2014 모든 속성-값 쌍이 한 줄에 배치됩니다.


**Returns:**
boolean
### setEachAttributeFromNewline(boolean value) {#setEachAttributeFromNewline-boolean-}
```
public final void setEachAttributeFromNewline(boolean value)
```


활성화되면 모든 XML 요소의 모든 속성-값 쌍이 새 줄에 배치됩니다.
기본값은 false(비활성화) \\u2014 모든 속성-값 쌍이 한 줄에 배치됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getLeafTextNodesOnNewline() {#getLeafTextNodesOnNewline--}
```
public final boolean getLeafTextNodesOnNewline()
```


활성화되면 리프 텍스트 노드(자식이 없는 XML 요소 내부의 �스트 내용)가 더 큰 왼쪽 들여쓰기로 새 줄에 표시됩니다.
기본값은 false(비활성화) \\u2014 리프 텍스트 노드가 부모와 같은 줄에 배치되며 새로운 들여쓰기가 없습니다.


**Returns:**
boolean
### setLeafTextNodesOnNewline(boolean value) {#setLeafTextNodesOnNewline-boolean-}
```
public final void setLeafTextNodesOnNewline(boolean value)
```


활성화되면 리프 텍스트 노드(자식이 없는 XML 요소 내부의 �스트 내용)가 더 큰 왼쪽 들여쓰기로 새 줄에 표시됩니다.
기본값은 false(비활성화) \\u2014 리프 텍스트 노드가 부모와 같은 줄에 배치되며 새로운 들여쓰기가 없습니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getLeftIndent() {#getLeftIndent--}
```
public final Length getLeftIndent()
```


각 새 줄의 왼쪽 들여쓰기 오프셋을 지정할 수 있습니다. 단위가 없는 0이 아닌 값은 허용되지 않습니다. 기본값은 10pt입니다.


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### setLeftIndent(Length value) {#setLeftIndent-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public final void setLeftIndent(Length value)
```


각 새 줄의 왼쪽 들여쓰기 오프셋을 지정할 수 있습니다. 단위가 없는 0이 아닌 값은 허용되지 않습니다. 기본값은 10pt입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


이 XML 서식 옵션 인스턴스에 기본값이 있는지 여부를 나타냅니다.


**Returns:**
boolean
