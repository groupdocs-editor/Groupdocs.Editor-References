---
title: "EbookEditOptions"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Consente di specificare e regolare opzioni personalizzate per la modifica di documenti E-book in tutti i formati supportati ePub, MOBI e AZW3."
type: docs
weight: 12
url: /it/nodejs-java/com.groupdocs.editor.options/ebookeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EbookEditOptions implements IEditOptions
```

Consente di specificare e regolare opzioni personalizzate per la modifica di documenti E-book in tutti i formati supportati: ePub, MOBI e AZW3.

<br />

*** ** * ** ***

Formati e-Book supportati:

1. [ePub](../https://docs.fileformat.com/ebook/epub/) (Pubblicazione elettronica)
2. [MOBI](../https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](../https://docs.fileformat.com/ebook/azw3/) (Kindle Format 8t)

<br />


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [EbookEditOptions()](#EbookEditOptions--) | Inizializza una nuova istanza della classe [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions), in cui tutte le opzioni sono impostate ai valori predefiniti |
|
|  | [EbookEditOptions(boolean enablePagination)](#EbookEditOptions-boolean-) | Inizializza una nuova istanza della classe [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) con la modalità di paginazione specificata |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Consente di abilitare o disabilitare l'impaginazione nel documento HTML risultante. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Consente di abilitare o disabilitare l'impaginazione nel documento HTML risultante. |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | Specifica se le informazioni sulla lingua vengono esportate nel markup HTML sotto forma di attributi HTML 'lang'. |
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | Specifica se le informazioni sulla lingua vengono esportate nel markup HTML sotto forma di attributi HTML 'lang'. |
|
### EbookEditOptions() {#EbookEditOptions--}
```
public EbookEditOptions()
```


Inizializza una nuova istanza della classe [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions), in cui tutte le opzioni sono impostate ai valori predefiniti


### EbookEditOptions(boolean enablePagination) {#EbookEditOptions-boolean-}
```
public EbookEditOptions(boolean enablePagination)
```


Inizializza una nuova istanza della classe [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) con la modalità di paginazione specificata


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | enablePagination | boolean | Abilita ( true ) o disabilita ( false ) la paginazione del contenuto dell'e-book nel documento HTML risultante. Per impostazione predefinita è disabilitata ( false ). |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Consente di abilitare o disabilitare l'impaginazione nel documento HTML risultante. Per impostazione predefinita è disabilitata (
false
).

<br />

*** ** * ** ***

In sostanza la maggior parte dei formati e‑book è internamente un formato di flusso come Office Open XML, dove il contenuto è un blocco unico e viene suddiviso in capitoli ma non in pagine. Tuttavia, contiene alcune informazioni specifiche di pagina come i numeri di pagina, le note a piè di pagina, intestazioni/piedi di pagina e così via. Alcuni lettori e‑book eseguono una suddivisione del contenuto dell'e‑book in pagine, mentre altri (soprattutto mobile) — no. Questa opzione consente di controllare come il contenuto dell'e‑book deve essere rappresentato in HTML/CSS durante la modifica — nella visualizzazione a flusso ( false ) o impaginata ( true ).

<br />



**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Consente di abilitare o disabilitare l'impaginazione nel documento HTML risultante. Per impostazione predefinita è disabilitata (
false
).

<br />

*** ** * ** ***

In sostanza la maggior parte dei formati e‑book è internamente un formato di flusso come Office Open XML, dove il contenuto è un blocco unico e viene suddiviso in capitoli ma non in pagine. Tuttavia, contiene alcune informazioni specifiche di pagina come i numeri di pagina, le note a piè di pagina, intestazioni/piedi di pagina e così via. Alcuni lettori e‑book eseguono una suddivisione del contenuto dell'e‑book in pagine, mentre altri (soprattutto mobile) — no. Questa opzione consente di controllare come il contenuto dell'e‑book deve essere rappresentato in HTML/CSS durante la modifica — nella visualizzazione a flusso ( false ) o impaginata ( true ).

<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


Specifica se le informazioni sulla lingua vengono esportate nel markup HTML sotto forma di attributi HTML 'lang'.
Questa opzione può essere utile per la conversione roundtrip dei documenti multilingua. Per impostazione predefinita è disabilitata (
false
).


**Returns:**
boolean
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


Specifica se le informazioni sulla lingua vengono esportate nel markup HTML sotto forma di attributi HTML 'lang'.
Questa opzione può essere utile per la conversione roundtrip dei documenti multilingua. Per impostazione predefinita è disabilitata (
false
).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

