---
title: "FontEmbeddingOptions"
second_title: "GroupDocs.Editor for Java API 참조"
description: "폰트 임베딩 옵션은 출력 WordProcessing 문서에 포함시킬 폰트 리소스를 제어합니다."
type: docs
weight: 17
url: /ko/java/com.groupdocs.editor.options/fontembeddingoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontEmbeddingOptions
```

폰트 임베딩 옵션은 포함시킬 폰트 리소스를 제어합니다.
출력 WordProcessing 문서


*** ** * ** ***

폰트 임베딩 옵션은 문서 저장 중(중간 EditableDocument에서 출력 WordProcessing 형식으로) 적용되며, 이 열거형은 WordProcessingSaveOptions의 속성으로 포함되어 사용됩니다.

<br />


## 필드

| 필드 | 설명 |
| --- | --- |
|  | [NotEmbed](#NotEmbed) | EditableDocument나 시스템에서도 폰트 리소스를 임베드하지 마십시오 |
시스템.
|
|  | [EmbedAll](#EmbedAll) | 입력 EditableDocument의 문서 내용을 분석하고 사용된 모든 폰트를 찾습니다. |
그리고 이를 출력 WordProcessing 문서에 임베드합니다.
|
|  | [EmbedWithoutSystem](#EmbedWithoutSystem) | [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll)과 동일하지만 해당 폰트를 제외합니다, |
운영체제에서 시스템 폰트로 간주되는
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFontEmbeddingOptions()](#getFontEmbeddingOptions--) |  |
### NotEmbed {#NotEmbed}
```
public static final int NotEmbed
```


EditableDocument나 시스템에서도 폰트 리소스를 임베드하지 마십시오
시스템. 기본값.


### EmbedAll {#EmbedAll}
```
public static final int EmbedAll
```


입력 EditableDocument의 문서 내용을 분석하고 사용된 모든 폰트를 찾습니다.
그리고 이를 출력 WordProcessing 문서에 임베드합니다. 우선
GroupDocs.Editor는 EditableDocument 내의 폰트 리소스에서 폰트를 가져옵니다.
폰트가 부족하거나 없을 경우, GroupDocs.Editor는 폰트를 가져옵니다
OS에서.


*** ** * ** ***

먼저 GroupDocs.Editor는 EditableDocument의 내용을 분석하고 사용된 모든 폰트 목록을 작성합니다. 그런 다음 이러한 폰트는 EditableDocument의 폰트 리소스에서 검색됩니다. EditableDocument에 문서 내용에 포함되지 않은 폰트 리소스가 있으면 해당 리소스는 무시됩니다. 문서 내용에 사용된 폰트 중 EditableDocument에 해당 폰트 리소스가 없을 경우, GroupDocs.Editor는 OS에서 이를 찾으려고 시도합니다. 이 옵션은 Microsoft Word 2007 및 그 이후 버전의 모든 하위 옵션을 끈 상태의 "Embed fonts in the file" 옵션과 유사합니다.

<br />



### EmbedWithoutSystem {#EmbedWithoutSystem}
```
public static final int EmbedWithoutSystem
```


[EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll)과 동일하지만 해당 폰트를 제외합니다,
운영체제에서 시스템 폰트로 간주되는


*** ** * ** ***

MS Windows는 시스템 폰트라는 개념을 가지고 있으며, 이는 Windows 자체에서 가장 기본적으로 사용되는 폰트입니다. 이 옵션을 사용할 때 GroupDocs.Editor는 [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll) 경우와 같이 동작하지만, 최종적으로 얻은 폰트 집합을 검토하고 OS에서 시스템 폰트로 간주되는 폰트를 제외합니다. 이 옵션은 Microsoft Word 2007 및 그 이후 버전에서 "Embed fonts in the file" + "Do not embed common system fonts" 옵션과 유사합니다.

<br />



### getFontEmbeddingOptions() {#getFontEmbeddingOptions--}
```
public static int[] getFontEmbeddingOptions()
```




**Returns:**
int[]
