---
title: "PageRange"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Incapsula un intervallo di pagine che può avere limiti aperti o chiusi."
type: docs
weight: 27
url: /it/nodejs-java/com.groupdocs.editor.options/pagerange/
---
**Inheritance:**
java.lang.Object
```
public class PageRange
```

Incapsula un intervallo di pagine, che può avere limiti aperti o chiusi. Per impostazione predefinita è "completamente aperto" - include tutte le pagine esistenti. La numerazione delle pagine inizia da 1, non da 0.

<br />

*** ** * ** ***

Struttura immutabile che incapsula un intervallo di pagine, non correlato a nessun documento specifico, e può rappresentare un intervallo di pagine per qualsiasi documento.

<br />


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PageRange()](#PageRange--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [AllPages](#AllPages) | Rappresenta tutte le pagine esistenti di un documento. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getStartNumber()](#getStartNumber--) | Numero di pagina iniziale inclusivo, da cui inizia questo intervallo di pagine. |
|
|  | [getEndNumber()](#getEndNumber--) | Numero di pagina finale esclusivo, fino al quale questo intervallo di pagine continua e si ferma esclusivamente. |
|
|  | [getCount()](#getCount--) | Numero di pagine all'interno dell'intervallo. |
|
|  | [isDefault()](#isDefault--) | Indica se questa istanza rappresenta un intervallo di pagine predefinito "completamente aperto", cioè. |
|
|  | [equals(PageRange other)](#equals-com.groupdocs.editor.options.PageRange-) | Rileva se questa istanza di PageRange è uguale a quella specificata |
|
|  | [fromBeginningWithCount(int pageCount)](#fromBeginningWithCount-int-) | Crea un intervallo di pagine, che inizia dalla prima pagina e ha una quantità specificata di pagine |
|
|  | [fromStartPageTillEnd(int startPageNumber)](#fromStartPageTillEnd-int-) | Crea un intervallo di pagine, che inizia dal numero di pagina specificato e continua fino alla fine del documento |
|
|  | [fromStartPageWithCount(int startPageNumber, int pageCount)](#fromStartPageWithCount-int-int-) | Crea un intervallo di pagine, che inizia dal numero di pagina specificato e ha una quantità specificata di pagine, o un conteggio illimitato di pagine (fino alla fine) |
|
|  | [fromStartPageTillEndPage(int startPageNumber, int endPageNumber)](#fromStartPageTillEndPage-int-int-) | Crea un intervallo di pagine, che inizia dal numero di pagina specificato (inclusivamente) e continua fino al numero di pagina specificato (esclusivamente) |
|
### PageRange() {#PageRange--}
```
public PageRange()
```


### AllPages {#AllPages}
```
public static final PageRange AllPages
```


Rappresenta tutte le pagine esistenti di un documento. Valore predefinito.


### getStartNumber() {#getStartNumber--}
```
public final int getStartNumber()
```


Numero di pagina iniziale inclusivo, da cui inizia questo intervallo di pagine. Se 1 - l'intervallo di pagine inizia dalla prima pagina di un documento


**Returns:**
int
### getEndNumber() {#getEndNumber--}
```
public final int getEndNumber()
```


Numero di pagina finale esclusivo, fino al quale questo intervallo di pagine continua e si ferma esclusivamente. Se 0 - l'intervallo di pagine si estende fino alla fine del documento


**Returns:**
int
### getCount() {#getCount--}
```
public final int getCount()
```


Numero di pagine all'interno dell'intervallo. Se 0 - l'intervallo di pagine si estende fino alla fine del documento indipendentemente dal numero di pagine che contiene


**Returns:**
int
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Indica se questa istanza rappresenta un intervallo di pagine predefinito "completamente aperto", cioè contiene tutte le pagine di un documento


**Returns:**
boolean
### equals(PageRange other) {#equals-com.groupdocs.editor.options.PageRange-}
```
public final boolean equals(PageRange other)
```


Rileva se questa istanza di PageRange è uguale a quella specificata


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [PageRange](../../com.groupdocs.editor.options/pagerange) | Altra istanza di PageRange da verificare per l'uguaglianza |
|

**Returns:**
boolean - true se sono uguali; false se sono diversi

### fromBeginningWithCount(int pageCount) {#fromBeginningWithCount-int-}
```
public static PageRange fromBeginningWithCount(int pageCount)
```


Crea un intervallo di pagine, che inizia dalla prima pagina e ha una quantità specificata di pagine


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | pageCount | int | Numero di pagine, deve essere strettamente maggiore di zero |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageTillEnd(int startPageNumber) {#fromStartPageTillEnd-int-}
```
public static PageRange fromStartPageTillEnd(int startPageNumber)
```


Crea un intervallo di pagine, che inizia dal numero di pagina specificato e continua fino alla fine del documento


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | startPageNumber | int | Numero di pagina, da cui inizia l'intervallo di pagine, inclusivamente. I numeri di pagina sono basati su 1, quindi devono essere strettamente maggiori di zero |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageWithCount(int startPageNumber, int pageCount) {#fromStartPageWithCount-int-int-}
```
public static PageRange fromStartPageWithCount(int startPageNumber, int pageCount)
```


Crea un intervallo di pagine, che inizia dal numero di pagina specificato e ha una quantità specificata di pagine, o un conteggio illimitato di pagine (fino alla fine)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | startPageNumber | int | Numero di pagina, da cui inizia l'intervallo di pagine, inclusivamente. I numeri di pagina sono basati su 1, quindi devono essere strettamente maggiori di zero |
|
|  | pageCount | int | Numero di pagine, deve essere strettamente maggiore di zero. Se zero - questo significa tutte le pagine fino alla fine di un documento |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageTillEndPage(int startPageNumber, int endPageNumber) {#fromStartPageTillEndPage-int-int-}
```
public static PageRange fromStartPageTillEndPage(int startPageNumber, int endPageNumber)
```


Crea un intervallo di pagine, che inizia dal numero di pagina specificato (inclusivamente) e continua fino al numero di pagina specificato (esclusivamente)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | startPageNumber | int | Numero di pagina, da cui inizia l'intervallo di pagine, inclusivamente. I numeri di pagina sono basati su 1, quindi devono essere strettamente maggiori di zero |
|
|  | endPageNumber | int | Numero di pagina, fino al quale l'intervallo di pagine continua, esclusivamente. I numeri di pagina sono basati su 1, quindi devono essere strettamente maggiori di zero, e inoltre devono essere strettamente maggiori di startPageNumber |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - 
