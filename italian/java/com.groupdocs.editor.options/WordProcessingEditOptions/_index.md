---
title: "WordProcessingEditOptions"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Consente di specificare opzioni personalizzate per modificare documenti di tutti i formati compatibili con WordProcessing Words, come DOCX, RTF, ODT, ecc."
type: docs
weight: 44
url: /it/java/com.groupdocs.editor.options/wordprocessingeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class WordProcessingEditOptions implements IEditOptions
```

Consente di specificare opzioni personalizzate per la modifica di tutti i documenti supportati
Formati WordProcessing (compatibili con Words) come DOC(X), RTF, ODT ecc.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [WordProcessingEditOptions()](#WordProcessingEditOptions--) | Crea e restituisce una nuova istanza di WordProcessingEditOptions |
classe, in cui tutte le opzioni sono impostate ai valori predefiniti
|
|  | [WordProcessingEditOptions(boolean enablePagination)](#WordProcessingEditOptions-boolean-) | Crea e restituisce una nuova istanza di WordProcessingEditOptions |
classe con paginazione specificata e tutte le altre opzioni impostate ai valori predefiniti
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Consente di abilitare o disabilitare l'impaginazione nel documento HTML risultante. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Consente di abilitare o disabilitare l'impaginazione nel documento HTML risultante. |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | Specifica se le informazioni sulla lingua vengono esportate nel markup HTML in |
una forma di attributi HTML 'lang'.
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | Specifica se le informazioni sulla lingua vengono esportate nel markup HTML in |
una forma di attributi HTML 'lang'.
|
|  | [getExtractOnlyUsedFont()](#getExtractOnlyUsedFont--) | Ottiene o imposta un valore che indica se estrarre solo le risorse di carattere che |
sono utilizzate nel contenuto testuale del documento.
|
|  | [setExtractOnlyUsedFont(boolean value)](#setExtractOnlyUsedFont-boolean-) | Ottiene o imposta un valore che indica se estrarre solo le risorse di carattere che |
sono utilizzate nel contenuto testuale del documento.
|
|  | [getFontExtraction()](#getFontExtraction--) | Responsabile dell'estrazione delle risorse di carattere, che sono utilizzate nell'input |
documento WordProcessing.
|
|  | [setFontExtraction(int value)](#setFontExtraction-int-) | Responsabile dell'estrazione delle risorse di carattere, che sono utilizzate nell'input |
documento WordProcessing.
|
|  | [getInputControlsClassName()](#getInputControlsClassName--) | Consente di specificare un nome di classe, che verrà inserito nell'attributo 'class' |
degli attributi in ogni elemento HTML, che rappresenta qualche campo nell'input
documento WordProcessing.
|
|  | [setInputControlsClassName(String value)](#setInputControlsClassName-java.lang.String-) | Consente di specificare un nome di classe, che verrà inserito nell'attributo 'class' |
degli attributi in ogni elemento HTML, che rappresenta qualche campo nell'input
documento WordProcessing.
|
|  | [getUseInlineStyles()](#getUseInlineStyles--) | Controlla dove memorizzare i dati di stile e formattazione del documento WordProcessing di input: in un foglio di stile esterno ( |
false
)
true
 oppure come stili in linea nel markup HTML (", ").
|
|  | [setUseInlineStyles(boolean value)](#setUseInlineStyles-boolean-) | Controlla dove memorizzare i dati di stile e formattazione del documento WordProcessing di input: in un foglio di stile esterno ( |
false
)
true
 oppure come stili in linea nel markup HTML (", ").
|
### WordProcessingEditOptions() {#WordProcessingEditOptions--}
```
public WordProcessingEditOptions()
```


Crea e restituisce una nuova istanza di WordProcessingEditOptions
classe, in cui tutte le opzioni sono impostate ai valori predefiniti


### WordProcessingEditOptions(boolean enablePagination) {#WordProcessingEditOptions-boolean-}
```
public WordProcessingEditOptions(boolean enablePagination)
```


Crea e restituisce una nuova istanza di WordProcessingEditOptions
classe con paginazione specificata e tutte le altre opzioni impostate ai valori predefiniti


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | enablePagination | boolean | Flag di paginazione, che abilita l'output HTML, adattato per la modalità paginata |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Consente di abilitare o disabilitare l'impaginazione nel documento HTML risultante. By
Il valore predefinito è disabilitato (false).


**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Consente di abilitare o disabilitare l'impaginazione nel documento HTML risultante. By
Il valore predefinito è disabilitato (false).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


Specifica se le informazioni sulla lingua vengono esportate nel markup HTML in
una forma di attributi HTML 'lang'. Questa opzione può essere utile per il roundtrip
conversione dei documenti multilingua. Per impostazione predefinita è disabilitata
(false).


**Returns:**
boolean
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


Specifica se le informazioni sulla lingua vengono esportate nel markup HTML in
una forma di attributi HTML 'lang'. Questa opzione può essere utile per il roundtrip
conversione dei documenti multilingua. Per impostazione predefinita è disabilitata
(false).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getExtractOnlyUsedFont() {#getExtractOnlyUsedFont--}
```
public final boolean getExtractOnlyUsedFont()
```


Ottiene o imposta un valore che indica se estrarre solo le risorse di carattere che
sono utilizzate nel contenuto testuale del documento.
Valore:  true  se è necessario estrarre solo quelle risorse di carattere, che sono utilizzate nel contenuto testuale del documento; altrimenti,  false . Il valore predefinito è  false .


*** ** * ** ***

Non tutti i caratteri, utilizzati nel documento WordProcessing, sono utilizzati al 100% direttamente (applicati a del testo). Potrebbe verificarsi una situazione in cui il carattere è referenziato nel documento e può anche essere incorporato, ma non è applicato a nessuna porzione di testo. Ad esempio, un carattere può essere associato a uno stile, ma questo stile non è applicato a nessuna parte del testo. Questa opzione controlla come gestire tali casi.

<br />



**Returns:**
boolean
### setExtractOnlyUsedFont(boolean value) {#setExtractOnlyUsedFont-boolean-}
```
public final void setExtractOnlyUsedFont(boolean value)
```


Ottiene o imposta un valore che indica se estrarre solo le risorse di carattere che
sono utilizzate nel contenuto testuale del documento.
Valore:  true  se è necessario estrarre solo quelle risorse di carattere, che sono utilizzate nel contenuto testuale del documento; altrimenti,  false . Il valore predefinito è  false .


*** ** * ** ***

Non tutti i caratteri, utilizzati nel documento WordProcessing, sono utilizzati al 100% direttamente (applicati a del testo). Potrebbe verificarsi una situazione in cui il carattere è referenziato nel documento e può anche essere incorporato, ma non è applicato a nessuna porzione di testo. Ad esempio, un carattere può essere associato a uno stile, ma questo stile non è applicato a nessuna parte del testo. Questa opzione controlla come gestire tali casi.

<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getFontExtraction() {#getFontExtraction--}
```
public final int getFontExtraction()
```


Responsabile dell'estrazione delle risorse di carattere, che sono utilizzate nell'input
Documento WordProcessing. Per impostazione predefinita non estrae alcun carattere
(NotExtract).


**Returns:**
int
### setFontExtraction(int value) {#setFontExtraction-int-}
```
public final void setFontExtraction(int value)
```


Responsabile dell'estrazione delle risorse di carattere, che sono utilizzate nell'input
Documento WordProcessing. Per impostazione predefinita non estrae alcun carattere
(NotExtract).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getInputControlsClassName() {#getInputControlsClassName--}
```
public final String getInputControlsClassName()
```


Consente di specificare un nome di classe, che verrà inserito nell'attributo 'class'
degli attributi in ogni elemento HTML, che rappresenta qualche campo nell'input
Documento WordProcessing. Per impostazione predefinita è NULL - gli attributi 'class' non sono
applicati.


*** ** * ** ***

Quasi tutti i formati della famiglia di formati WordProcessing contengono campi \\u2014 entità specifiche del documento, che consentono di ottenere dati di input dagli utenti. Esiste un'ampia varietà di campi: caselle di testo, caselle di controllo, caselle combinate, elenchi a discesa, pulsanti, selettori data/ora, ecc. Tutti vengono tradotti nelle strutture e negli elementi HTML più appropriati, preservando i dati inseriti dall'utente, se presenti nel documento di input. In casi d'uso specifici è necessario raccogliere solo i dati inseriti sul lato client invece di modificare l'intero contenuto del documento. Per questo caso è necessario identificare i controlli di input in qualche modo per recuperarli con i loro dati sul lato client. Questa proprietà consente di specificare un nome di classe, che verrà applicato a ogni controllo di input nel markup HTML, così il codice client potrà attraversare la struttura del documento HTML e raccogliere i dati.

<br />



**Returns:**
java.lang.String
### setInputControlsClassName(String value) {#setInputControlsClassName-java.lang.String-}
```
public final void setInputControlsClassName(String value)
```


Consente di specificare un nome di classe, che verrà inserito nell'attributo 'class'
degli attributi in ogni elemento HTML, che rappresenta qualche campo nell'input
Documento WordProcessing. Per impostazione predefinita è NULL - gli attributi 'class' non sono
applicati.


*** ** * ** ***

Quasi tutti i formati della famiglia di formati WordProcessing contengono campi \\u2014 entità specifiche del documento, che consentono di ottenere dati di input dagli utenti. Esiste un'ampia varietà di campi: caselle di testo, caselle di controllo, caselle combinate, elenchi a discesa, pulsanti, selettori data/ora, ecc. Tutti vengono tradotti nelle strutture e negli elementi HTML più appropriati, preservando i dati inseriti dall'utente, se presenti nel documento di input. In casi d'uso specifici è necessario raccogliere solo i dati inseriti sul lato client invece di modificare l'intero contenuto del documento. Per questo caso è necessario identificare i controlli di input in qualche modo per recuperarli con i loro dati sul lato client. Questa proprietà consente di specificare un nome di classe, che verrà applicato a ogni controllo di input nel markup HTML, così il codice client potrà attraversare la struttura del documento HTML e raccogliere i dati.

<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getUseInlineStyles() {#getUseInlineStyles--}
```
public final boolean getUseInlineStyles()
```


Controlla dove memorizzare i dati di stile e formattazione del documento WordProcessing di input: in un foglio di stile esterno (
false
)
true
). Per impostazione predefinita vengono utilizzati gli stili esterni (
false
 oppure come stili in linea nel markup HTML (", ").


**Returns:**
boolean
### setUseInlineStyles(boolean value) {#setUseInlineStyles-boolean-}
```
public final void setUseInlineStyles(boolean value)
```


Controlla dove memorizzare i dati di stile e formattazione del documento WordProcessing di input: in un foglio di stile esterno (
false
)
true
). Per impostazione predefinita vengono utilizzati gli stili esterni (
false
 oppure come stili in linea nel markup HTML (", ").


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

