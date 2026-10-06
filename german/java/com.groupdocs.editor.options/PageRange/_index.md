---
title: "PageRange"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Kapselt einen Seitenbereich, der offene oder geschlossene Grenzen haben kann."
type: docs
weight: 27
url: /de/java/com.groupdocs.editor.options/pagerange/
---
**Inheritance:**
java.lang.Object
```
public class PageRange
```

Kapselt einen Seitenbereich, der offene oder geschlossene Grenzen haben kann. Standardmäßig ist er "vollständig offen" – er umfasst alle vorhandenen Seiten. Die Seitennummerierung beginnt bei 1, nicht bei 0.

<br />

*** ** * ** ***

Unveränderliche Struktur, die einen Seitenbereich kapselt, der nicht mit einem bestimmten Dokument verknüpft ist und einen Seitenbereich für jedes Dokument darstellen kann.

<br />


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PageRange()](#PageRange--) |  |
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [AllPages](#AllPages) | Stellt alle vorhandenen Seiten eines Dokuments dar. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getStartNumber()](#getStartNumber--) | Inklusive Startseitennummer, von der dieser Seitenbereich beginnt. |
|
|  | [getEndNumber()](#getEndNumber--) | Exklusive Endseitennummer, bis zu der dieser Seitenbereich fortgesetzt wird und an der er ausschließlich endet. |
|
|  | [getCount()](#getCount--) | Seitennummern innerhalb des Bereichs. |
|
|  | [isDefault()](#isDefault--) | Gibt an, ob diese Instanz einen standardmäßigen "vollständig offenen" Seitenbereich darstellt, d. h. |
|
|  | [equals(PageRange other)](#equals-com.groupdocs.editor.options.PageRange-) | Ermittelt, ob diese Instanz von PageRange gleich dem angegebenen ist |
|
|  | [fromBeginningWithCount(int pageCount)](#fromBeginningWithCount-int-) | Erstellt einen Seitenbereich, der bei der ersten Seite beginnt und eine angegebene Anzahl von Seiten hat |
|
|  | [fromStartPageTillEnd(int startPageNumber)](#fromStartPageTillEnd-int-) | Erstellt einen Seitenbereich, der bei der angegebenen Seitennummer beginnt und bis zum Ende des Dokuments fortsetzt |
|
|  | [fromStartPageWithCount(int startPageNumber, int pageCount)](#fromStartPageWithCount-int-int-) | Erstellt einen Seitenbereich, der bei der angegebenen Seitennummer beginnt und eine angegebene Anzahl von Seiten hat, oder eine unbegrenzte Seitenzahl (bis zum Ende) |
|
|  | [fromStartPageTillEndPage(int startPageNumber, int endPageNumber)](#fromStartPageTillEndPage-int-int-) | Erstellt einen Seitenbereich, der bei der angegebenen Seitennummer (inklusive) beginnt und bis zur angegebenen Seitennummer (exklusiv) fortsetzt |
|
### PageRange() {#PageRange--}
```
public PageRange()
```


### AllPages {#AllPages}
```
public static final PageRange AllPages
```


Stellt alle vorhandenen Seiten eines Dokuments dar. Standardwert.


### getStartNumber() {#getStartNumber--}
```
public final int getStartNumber()
```


Inklusive Startseitennummer, von der aus dieser Seitenbereich beginnt. Wenn 1 – der Seitenbereich beginnt mit der ersten Seite eines Dokuments


**Returns:**
int
### getEndNumber() {#getEndNumber--}
```
public final int getEndNumber()
```


Exklusive Endseitennummer, bis zu der dieser Seitenbereich fortgesetzt wird und an der er ausschließlich endet. Wenn 0 – erstreckt sich der Seitenbereich bis zum Ende des Dokuments


**Returns:**
int
### getCount() {#getCount--}
```
public final int getCount()
```


Anzahl der Seiten im Bereich. Wenn 0 – erstreckt sich der Seitenbereich bis zum Ende des Dokuments, unabhängig davon, wie viele Seiten er enthält


**Returns:**
int
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Gibt an, ob diese Instanz einen Standard‑„vollständig offenen“ Seitenbereich darstellt, d. h. er umfasst alle Seiten eines Dokuments


**Returns:**
boolean
### equals(PageRange other) {#equals-com.groupdocs.editor.options.PageRange-}
```
public final boolean equals(PageRange other)
```


Ermittelt, ob diese Instanz von PageRange gleich dem angegebenen ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [PageRange](../../com.groupdocs.editor.options/pagerange) | Andere PageRange‑Instanz zum Vergleich auf Gleichheit |
|

**Returns:**
boolescher Wert – true bedeutet gleich; false bedeutet ungleich

### fromBeginningWithCount(int pageCount) {#fromBeginningWithCount-int-}
```
public static PageRange fromBeginningWithCount(int pageCount)
```


Erstellt einen Seitenbereich, der bei der ersten Seite beginnt und eine angegebene Anzahl von Seiten hat


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | pageCount | int | Anzahl der Seiten, muss strikt größer als Null sein |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageTillEnd(int startPageNumber) {#fromStartPageTillEnd-int-}
```
public static PageRange fromStartPageTillEnd(int startPageNumber)
```


Erstellt einen Seitenbereich, der bei der angegebenen Seitennummer beginnt und bis zum Ende des Dokuments fortsetzt


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | startPageNumber | int | Seitennummer, von der der Seitenbereich inklusiv beginnt. Seitennummern beginnen bei 1, daher muss sie strikt größer als Null sein |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageWithCount(int startPageNumber, int pageCount) {#fromStartPageWithCount-int-int-}
```
public static PageRange fromStartPageWithCount(int startPageNumber, int pageCount)
```


Erstellt einen Seitenbereich, der bei der angegebenen Seitennummer beginnt und eine angegebene Anzahl von Seiten hat, oder eine unbegrenzte Seitenzahl (bis zum Ende)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | startPageNumber | int | Seitennummer, von der der Seitenbereich inklusiv beginnt. Seitennummern beginnen bei 1, daher muss sie strikt größer als Null sein |
|
|  | pageCount | int | Anzahl der Seiten, muss strikt größer als Null sein. Wenn Null – bedeutet das alle Seiten bis zum Ende eines Dokuments |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageTillEndPage(int startPageNumber, int endPageNumber) {#fromStartPageTillEndPage-int-int-}
```
public static PageRange fromStartPageTillEndPage(int startPageNumber, int endPageNumber)
```


Erstellt einen Seitenbereich, der bei der angegebenen Seitennummer (inklusive) beginnt und bis zur angegebenen Seitennummer (exklusiv) fortsetzt


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | startPageNumber | int | Seitennummer, von der der Seitenbereich inklusiv beginnt. Seitennummern beginnen bei 1, daher muss sie strikt größer als Null sein |
|
|  | endPageNumber | int | Seitennummer, bis zu der der Seitenbereich exklusiv fortgesetzt wird. Seitennummern beginnen bei 1, daher muss sie strikt größer als Null sein und außerdem strikt größer als startPageNumber |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - 
