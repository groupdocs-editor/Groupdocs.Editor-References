---
title: "PageRange"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Innesluter ett sidintervall som kan ha öppna eller stängda gränser."
type: docs
weight: 27
url: /sv/java/com.groupdocs.editor.options/pagerange/
---
**Inheritance:**
java.lang.Object
```
public class PageRange
```

Innesluter ett sidintervall som kan ha öppna eller stängda gränser. Som standard är det \"fullt öppet\" – det inkluderar alla befintliga sidor. Sidnumrering börjar från 1, inte från 0.

<br />

*** ** * ** ***

Oföränderlig struct som innesluter ett sidintervall, vilket inte är kopplat till något specifikt dokument och kan representera ett sidintervall för vilket dokument som helst.

<br />


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PageRange()](#PageRange--) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [AllPages](#AllPages) | Representerar alla befintliga sidor i ett dokument. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getStartNumber()](#getStartNumber--) | Inkluderande startsidnummer, från vilket detta sidintervall börjar. |
|
|  | [getEndNumber()](#getEndNumber--) | Exklusivt slutsidnummer, tills vilket detta sidintervall fortsätter och på vilket det slutar exklusivt. |
|
|  | [getCount()](#getCount--) | Antal sidor inom intervallet. |
|
|  | [isDefault()](#isDefault--) | Indikerar om detta objekt representerar ett standard \"fullt öppet\" sidintervall, dvs. |
|
|  | [equals(PageRange other)](#equals-com.groupdocs.editor.options.PageRange-) | Detekterar om detta PageRange‑objekt är lika med det angivna |
|
|  | [fromBeginningWithCount(int pageCount)](#fromBeginningWithCount-int-) | Skapar ett sidintervall som startar från den första sidan och har ett specificerat antal sidor |
|
|  | [fromStartPageTillEnd(int startPageNumber)](#fromStartPageTillEnd-int-) | Skapar ett sidintervall som startar från det angivna sidnumret och fortsätter till dokumentets slut |
|
|  | [fromStartPageWithCount(int startPageNumber, int pageCount)](#fromStartPageWithCount-int-int-) | Skapar ett sidintervall som startar från det angivna sidnumret och har ett specificerat antal sidor, eller obegränsat sidantal (till slutet) |
|
|  | [fromStartPageTillEndPage(int startPageNumber, int endPageNumber)](#fromStartPageTillEndPage-int-int-) | Skapar ett sidintervall som startar från det angivna sidnumret (inkluderande) och fortsätter tills det angivna sidnumret (exklusivt) |
|
### PageRange() {#PageRange--}
```
public PageRange()
```


### AllPages {#AllPages}
```
public static final PageRange AllPages
```


Representerar alla befintliga sidor i ett dokument. Standardvärde.


### getStartNumber() {#getStartNumber--}
```
public final int getStartNumber()
```


Inkluderande startsidnummer, från vilket detta sidintervall börjar. Om 1 – sidintervallet startar från den första sidan i ett dokument


**Returns:**
int
### getEndNumber() {#getEndNumber--}
```
public final int getEndNumber()
```


Exklusivt slutsidnummer, tills vilket detta sidintervall fortsätter och på vilket det slutar exklusivt. Om 0 – sidintervallet sträcker sig till dokumentets slut


**Returns:**
int
### getCount() {#getCount--}
```
public final int getCount()
```


Antal sidor inom intervallet. Om 0 – sidintervallet sträcker sig till dokumentets slut oavsett hur många sidor det består av


**Returns:**
int
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Anger om den här instansen representerar ett standard "fullt öppet" sidintervall, dvs. den består av alla sidor i ett dokument


**Returns:**
boolean
### equals(PageRange other) {#equals-com.groupdocs.editor.options.PageRange-}
```
public final boolean equals(PageRange other)
```


Detekterar om detta PageRange‑objekt är lika med det angivna


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [PageRange](../../com.groupdocs.editor.options/pagerange) | Annan PageRange-instans för att kontrollera likhet |
|

**Returns:**
boolean - true betyder lika; false betyder olika

### fromBeginningWithCount(int pageCount) {#fromBeginningWithCount-int-}
```
public static PageRange fromBeginningWithCount(int pageCount)
```


Skapar ett sidintervall som startar från den första sidan och har ett specificerat antal sidor


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | pageCount | int | Antal sidor, måste vara strikt större än noll |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageTillEnd(int startPageNumber) {#fromStartPageTillEnd-int-}
```
public static PageRange fromStartPageTillEnd(int startPageNumber)
```


Skapar ett sidintervall som startar från det angivna sidnumret och fortsätter till dokumentets slut


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | startPageNumber | int | Sidnummer, från vilket sidintervall startar, inklusivt. Sidnummer är 1-baserade, så de måste vara strikt större än noll |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageWithCount(int startPageNumber, int pageCount) {#fromStartPageWithCount-int-int-}
```
public static PageRange fromStartPageWithCount(int startPageNumber, int pageCount)
```


Skapar ett sidintervall som startar från det angivna sidnumret och har ett specificerat antal sidor, eller obegränsat sidantal (till slutet)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | startPageNumber | int | Sidnummer, från vilket sidintervall startar, inklusivt. Sidnummer är 1-baserade, så de måste vara strikt större än noll |
|
|  | pageCount | int | Antal sidor, måste vara strikt större än noll. Om noll - betyder det alla sidor till slutet av ett dokument |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageTillEndPage(int startPageNumber, int endPageNumber) {#fromStartPageTillEndPage-int-int-}
```
public static PageRange fromStartPageTillEndPage(int startPageNumber, int endPageNumber)
```


Skapar ett sidintervall som startar från det angivna sidnumret (inkluderande) och fortsätter tills det angivna sidnumret (exklusivt)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | startPageNumber | int | Sidnummer, från vilket sidintervall startar, inklusivt. Sidnummer är 1-baserade, så de måste vara strikt större än noll |
|
|  | endPageNumber | int | Sidnummer, tills vilket sidintervall fortsätter, exklusivt. Sidnummer är 1-baserade, så de måste vara strikt större än noll, och också strikt större än startPageNumber |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - 
