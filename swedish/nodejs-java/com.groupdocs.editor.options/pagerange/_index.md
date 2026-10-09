---
title: "PageRange"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Inkapslar ett sidintervall som kan ha öppna eller stängda gränser."
type: docs
weight: 27
url: /sv/nodejs-java/com.groupdocs.editor.options/pagerange/
---
**Inheritance:**
java.lang.Object
```
public class PageRange
```

Inkapslar ett sidintervall, som kan ha öppna eller stängda gränser. Som standard är det "fullt öppet" – det inkluderar alla befintliga sidor. Sidnumrering börjar från 1, inte från 0.

<br />

*** ** * ** ***

Oföränderlig struct som inkapslar ett sidintervall, vilket inte är kopplat till något specifikt dokument och kan representera ett sidintervall för vilket dokument som helst.

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
|  | [isDefault()](#isDefault--) | Indikerar om detta objekt representerar ett standard "fullt öppet" sidintervall, dvs. |
|
|  | [equals(PageRange other)](#equals-com.groupdocs.editor.options.PageRange-) | Detekterar om detta PageRange‑objekt är lika med det angivna |
|
|  | [fromBeginningWithCount(int pageCount)](#fromBeginningWithCount-int-) | Skapar ett sidintervall som börjar från den första sidan och har ett specificerat antal sidor |
|
|  | [fromStartPageTillEnd(int startPageNumber)](#fromStartPageTillEnd-int-) | Skapar ett sidintervall som börjar från det specificerade sidnumret och fortsätter till slutet av dokumentet |
|
|  | [fromStartPageWithCount(int startPageNumber, int pageCount)](#fromStartPageWithCount-int-int-) | Skapar ett sidintervall som börjar från det specificerade sidnumret och har ett specificerat antal sidor, eller obegränsat sidantal (till slutet) |
|
|  | [fromStartPageTillEndPage(int startPageNumber, int endPageNumber)](#fromStartPageTillEndPage-int-int-) | Skapar ett sidintervall som börjar från det specificerade sidnumret (inkluderande) och fortsätter tills det specificerade sidnumret (exklusivt) |
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


Inkluderande startsidnummer, från vilket detta sidintervall börjar. Om 1 – sidintervallet börjar från den första sidan i ett dokument


**Returns:**
int
### getEndNumber() {#getEndNumber--}
```
public final int getEndNumber()
```


Exklusivt slutsidnummer, tills vilket detta sidintervall fortsätter och på vilket det slutar exklusivt. Om 0 – sidintervallet sträcker sig till slutet av dokumentet


**Returns:**
int
### getCount() {#getCount--}
```
public final int getCount()
```


Antal sidor inom intervallet. Om 0 – sidintervallet sträcker sig till slutet av dokumentet oavsett hur många sidor det består av


**Returns:**
int
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Indikerar om detta objekt representerar ett standard "fullt öppet" sidintervall, dvs. det består av alla sidor i ett dokument


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
|  | other | [PageRange](../../com.groupdocs.editor.options/pagerange) | Annat PageRange‑objekt att kontrollera för likhet |
|

**Returns:**
bool - true betyder lika; false betyder olika

### fromBeginningWithCount(int pageCount) {#fromBeginningWithCount-int-}
```
public static PageRange fromBeginningWithCount(int pageCount)
```


Skapar ett sidintervall som börjar från den första sidan och har ett specificerat antal sidor


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


Skapar ett sidintervall som börjar från det specificerade sidnumret och fortsätter till slutet av dokumentet


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | startPageNumber | int | Sidnummer, från vilket sidintervallet börjar, inkluderande. Sidnummer är 1‑baserade, så de måste vara strikt större än noll |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageWithCount(int startPageNumber, int pageCount) {#fromStartPageWithCount-int-int-}
```
public static PageRange fromStartPageWithCount(int startPageNumber, int pageCount)
```


Skapar ett sidintervall som börjar från det specificerade sidnumret och har ett specificerat antal sidor, eller obegränsat sidantal (till slutet)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | startPageNumber | int | Sidnummer, från vilket sidintervallet börjar, inkluderande. Sidnummer är 1‑baserade, så de måste vara strikt större än noll |
|
|  | pageCount | int | Antal sidor, måste vara strikt större än noll. Om noll - betyder det alla sidor till slutet av ett dokument |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageTillEndPage(int startPageNumber, int endPageNumber) {#fromStartPageTillEndPage-int-int-}
```
public static PageRange fromStartPageTillEndPage(int startPageNumber, int endPageNumber)
```


Skapar ett sidintervall som börjar från det specificerade sidnumret (inkluderande) och fortsätter tills det specificerade sidnumret (exklusivt)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | startPageNumber | int | Sidnummer, från vilket sidintervallet börjar, inkluderande. Sidnummer är 1‑baserade, så de måste vara strikt större än noll |
|
|  | endPageNumber | int | Sidnummer, tills vilket sidintervall fortsätter, exklusivt. Sidnummer är 1-baserade, så de måste vara strikt större än noll, och också strikt större än startPageNumber |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - 
