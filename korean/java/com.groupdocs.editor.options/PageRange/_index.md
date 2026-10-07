---
title: "PageRange"
second_title: "GroupDocs.Editor for Java API 참조"
description: "하나의 페이지 범위를 캡슐화하며, 해당 범위는 열린 경계 또는 닫힌 경계를 가질 수 있습니다."
type: docs
weight: 27
url: /ko/java/com.groupdocs.editor.options/pagerange/
---
**Inheritance:**
java.lang.Object
```
public class PageRange
```

하나의 페이지 범위를 캡슐화하며, 해당 범위는 열린 경계 또는 닫힌 경계를 가질 수 있습니다. 기본값은 "완전 개방"이며 - 모든 기존 페이지를 포함합니다. 페이지 번호는 0이 아니라 1부터 시작합니다.

<br />

*** ** * ** ***

불변 구조체로, 특정 문서와 관련되지 않은 페이지 범위를 캡슐화하며, 모든 문서에 대한 페이지 범위를 나타낼 수 있습니다.

<br />


## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PageRange()](#PageRange--) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
|  | [AllPages](#AllPages) | 문서의 모든 기존 페이지를 나타냅니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getStartNumber()](#getStartNumber--) | 포함되는 시작 페이지 번호로, 이 페이지 범위가 시작되는 번호입니다. |
|
|  | [getEndNumber()](#getEndNumber--) | 배제되는 종료 페이지 번호로, 이 페이지 범위가 계속되며 해당 번호에서 독점적으로 종료됩니다. |
|
|  | [getCount()](#getCount--) | 범위 내 페이지 수. |
|
|  | [isDefault()](#isDefault--) | 이 인스턴스가 기본 "완전 개방" 페이지 범위를 나타내는지 여부를 표시합니다. |
|
|  | [equals(PageRange other)](#equals-com.groupdocs.editor.options.PageRange-) | 이 PageRange 인스턴스가 지정된 것과 같은지 감지합니다. |
|
|  | [fromBeginningWithCount(int pageCount)](#fromBeginningWithCount-int-) | 첫 페이지부터 시작하고 지정된 페이지 수를 갖는 페이지 범위를 생성합니다. |
|
|  | [fromStartPageTillEnd(int startPageNumber)](#fromStartPageTillEnd-int-) | 지정된 페이지 번호부터 시작하여 문서 끝까지 계속되는 페이지 범위를 생성합니다. |
|
|  | [fromStartPageWithCount(int startPageNumber, int pageCount)](#fromStartPageWithCount-int-int-) | 지정된 페이지 번호부터 시작하고 지정된 페이지 수를 갖거나, 무제한 페이지 수(문서 끝까지)를 갖는 페이지 범위를 생성합니다. |
|
|  | [fromStartPageTillEndPage(int startPageNumber, int endPageNumber)](#fromStartPageTillEndPage-int-int-) | 지정된 페이지 번호(포함)부터 시작하여 지정된 페이지 번호(배제)까지 계속되는 페이지 범위를 생성합니다. |
|
### PageRange() {#PageRange--}
```
public PageRange()
```


### AllPages {#AllPages}
```
public static final PageRange AllPages
```


문서의 모든 기존 페이지를 나타냅니다. 기본값.


### getStartNumber() {#getStartNumber--}
```
public final int getStartNumber()
```


포함되는 시작 페이지 번호로, 이 페이지 범위가 시작되는 번호입니다. 1인 경우 - 페이지 범위가 문서의 첫 페이지부터 시작합니다.


**Returns:**
int
### getEndNumber() {#getEndNumber--}
```
public final int getEndNumber()
```


배제되는 종료 페이지 번호로, 이 페이지 범위가 계속되며 해당 번호에서 독점적으로 종료됩니다. 0인 경우 - 페이지 범위가 문서 끝까지 확장됩니다.


**Returns:**
int
### getCount() {#getCount--}
```
public final int getCount()
```


범위 내 페이지 수. 0인 경우 - 페이지 범위는 문서 끝까지 확장되며, 포함된 페이지 수에 관계없이 적용됩니다.


**Returns:**
int
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


이 인스턴스가 기본 "완전 개방" 페이지 범위를 나타내는지 여부를 표시합니다. 즉, 문서의 모든 페이지를 포함합니다.


**Returns:**
boolean
### equals(PageRange other) {#equals-com.groupdocs.editor.options.PageRange-}
```
public final boolean equals(PageRange other)
```


이 PageRange 인스턴스가 지정된 것과 같은지 감지합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | other | [PageRange](../../com.groupdocs.editor.options/pagerange) | 동등성을 확인할 다른 PageRange 인스턴스 |
|

**Returns:**
boolean - true는 동일함을 의미하고; false는 다름을 의미합니다.

### fromBeginningWithCount(int pageCount) {#fromBeginningWithCount-int-}
```
public static PageRange fromBeginningWithCount(int pageCount)
```


첫 페이지부터 시작하고 지정된 페이지 수를 갖는 페이지 범위를 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | pageCount | int | 페이지 수이며, 0보다 크게 엄격히 지정되어야 합니다. |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageTillEnd(int startPageNumber) {#fromStartPageTillEnd-int-}
```
public static PageRange fromStartPageTillEnd(int startPageNumber)
```


지정된 페이지 번호부터 시작하여 문서 끝까지 계속되는 페이지 범위를 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | startPageNumber | int | 페이지 범위가 시작되는 페이지 번호(포함). 페이지 번호는 1부터 시작하므로 0보다 커야 합니다. |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageWithCount(int startPageNumber, int pageCount) {#fromStartPageWithCount-int-int-}
```
public static PageRange fromStartPageWithCount(int startPageNumber, int pageCount)
```


지정된 페이지 번호부터 시작하고 지정된 페이지 수를 갖거나, 무제한 페이지 수(문서 끝까지)를 갖는 페이지 범위를 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | startPageNumber | int | 페이지 범위가 시작되는 페이지 번호(포함). 페이지 번호는 1부터 시작하므로 0보다 커야 합니다. |
|
|  | pageCount | int | 페이지 수는 0보다 커야 합니다. 0인 경우 - 문서 끝까지 모든 페이지를 의미합니다. |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageTillEndPage(int startPageNumber, int endPageNumber) {#fromStartPageTillEndPage-int-int-}
```
public static PageRange fromStartPageTillEndPage(int startPageNumber, int endPageNumber)
```


지정된 페이지 번호(포함)부터 시작하여 지정된 페이지 번호(배제)까지 계속되는 페이지 범위를 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | startPageNumber | int | 페이지 범위가 시작되는 페이지 번호(포함). 페이지 번호는 1부터 시작하므로 0보다 커야 합니다. |
|
|  | endPageNumber | int | 페이지 범위가 끝나는 페이지 번호(포함되지 않음). 페이지 번호는 1부터 시작하므로 0보다 커야 하며, 또한 startPageNumber보다 커야 합니다. |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - 
