---
title: "WordProcessingSaveOptions"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Consente di specificare opzioni personalizzate per generare e salvare documenti conformi a WordProcessing dopo che sono stati modificati"
type: docs
weight: 48
url: /it/nodejs-java/com.groupdocs.editor.options/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class WordProcessingSaveOptions implements ISaveOptions
```

Consente di specificare opzioni personalizzate per la generazione e il salvataggio
Documenti conformi a WordProcessing dopo essere stati modificati


*** ** * ** ***

WordProcessingSaveOptions viene applicato in situazioni in cui esiste un'istanza della classe EditableDocument, che contiene il contenuto di un documento modificato, ed è necessario salvare questo contenuto nel nuovo documento in formato WordProcessing.

<br />


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | Questo costruttore senza parametri crea una nuova istanza di WordProcessingSaveOptions con formato di output DOCX (può essere modificato successivamente tramite |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats)) proprietà)
|
|  | [WordProcessingSaveOptions(WordProcessingFormats outputFormat)](#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-) | Crea una nuova istanza di WordProcessingSaveOptions con specificato |
formato di output WordProcessing obbligatorio, mentre tutti gli altri parametri sono
predefinito
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Consente di abilitare o disabilitare l'impaginazione che verrà utilizzata per il salvataggio del |
documento.
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Consente di abilitare o disabilitare l'impaginazione che verrà utilizzata per il salvataggio del |
documento.
|
|  | [getPassword()](#getPassword--) | Consente di specificare, modificare, ottenere o rimuovere una password, che sarà |
utilizzata per codificare il documento WordProcessing generato.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Consente di specificare, modificare, ottenere o rimuovere una password, che sarà |
utilizzata per codificare il documento WordProcessing generato.
|
|  | [getOutputFormat()](#getOutputFormat--) | Consente di specificare un formato WordProcessing, che sarà utilizzato per il salvataggio |
del documento
|
|  | [setOutputFormat(WordProcessingFormats value)](#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-) | Consente di specificare un formato WordProcessing, che sarà utilizzato per il salvataggio |
del documento
|
|  | [getLocale()](#getLocale--) | Consente di impostare la sovrascrittura della locale predefinita (lingua) per il WordProcessing |
documento, che verrà applicato durante la sua creazione.
|
|  | [setLocale(Locale value)](#setLocale-java.util.Locale-) | Consente di impostare la sovrascrittura della locale predefinita (lingua) per il WordProcessing |
documento, che verrà applicato durante la sua creazione.
|
|  | [getLocaleBi()](#getLocaleBi--) | Consente di impostare la sovrascrittura della locale (lingua) per il documento WordProcessing |
per il testo RTL (da destra a sinistra), che sarà applicato durante il suo
creazione.
|
|  | [setLocaleBi(Locale value)](#setLocaleBi-java.util.Locale-) | Consente di impostare la sovrascrittura della locale (lingua) per il documento WordProcessing |
per il testo RTL (da destra a sinistra), che sarà applicato durante il suo
creazione.
|
|  | [getLocaleFarEast()](#getLocaleFarEast--) | Consente di sovrascrivere la locale (lingua) per il documento WordProcessing |
per il testo East-Asian, che sarà applicato durante la sua creazione.
|
|  | [setLocaleFarEast(Locale value)](#setLocaleFarEast-java.util.Locale-) | Consente di sovrascrivere la locale (lingua) per il documento WordProcessing |
per il testo East-Asian, che sarà applicato durante la sua creazione.
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Abilita i meccanismi di ottimizzazione della memoria durante la generazione del documento da |
HTML, che degrada le prestazioni come costo della riduzione dell'uso della memoria.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Abilita i meccanismi di ottimizzazione della memoria durante la generazione del documento da |
HTML, che degrada le prestazioni come costo della riduzione dell'uso della memoria.
|
|  | [getProtection()](#getProtection--) | Consente di controllare e applicare le opzioni di protezione del documento per il |
documento WordProcessing di qualsiasi formato, che supporta la protezione del documento
di protezione.
|
|  | [setProtection(WordProcessingProtection value)](#setProtection-com.groupdocs.editor.options.WordProcessingProtection-) | Consente di controllare e applicare le opzioni di protezione del documento per il |
documento WordProcessing di qualsiasi formato, che supporta la protezione del documento
di protezione.
|
|  | [getFontEmbedding()](#getFontEmbedding--) | Responsabile dell'incorporamento delle risorse di carattere nell'output WordProcessing |
documento.
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | Responsabile dell'incorporamento delle risorse di carattere nell'output WordProcessing |
documento.
|
|  | [deepClone()](#deepClone--) | Crea e restituisce una copia completa di questa istanza di |
classe WordProcessingSaveOptions
|
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


Questo costruttore senza parametri crea una nuova istanza di WordProcessingSaveOptions con formato di output DOCX (può essere modificato successivamente tramite
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats)) proprietà)


### WordProcessingSaveOptions(WordProcessingFormats outputFormat) {#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public WordProcessingSaveOptions(WordProcessingFormats outputFormat)
```


Crea una nuova istanza di WordProcessingSaveOptions con specificato
formato di output WordProcessing obbligatorio, mentre tutti gli altri parametri sono
predefinito


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | outputFormat | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) | Formato di output obbligatorio, nel quale il documento WordProcessing dovrebbe essere salvato |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Consente di abilitare o disabilitare l'impaginazione che verrà utilizzata per il salvataggio del
documento. Se il documento originale è stato aperto e modificato in modalità impaginazione
modalità, questa opzione dovrebbe essere abilitata. Per impostazione predefinita è disabilitata.


**Returns:**
boolean -
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Consente di abilitare o disabilitare l'impaginazione che verrà utilizzata per il salvataggio del
documento. Se il documento originale è stato aperto e modificato in modalità impaginazione
modalità, questa opzione dovrebbe essere abilitata. Per impostazione predefinita è disabilitata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Consente di specificare, modificare, ottenere o rimuovere una password, che sarà
usato per codificare il documento WordProcessing generato. Specificare NULL o
stringa vuota per rimuovere (pulire) la password.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Consente di specificare, modificare, ottenere o rimuovere una password, che sarà
usato per codificare il documento WordProcessing generato. Specificare NULL o
stringa vuota per rimuovere (pulire) la password.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getOutputFormat() {#getOutputFormat--}
```
public final WordProcessingFormats getOutputFormat()
```


Consente di specificare un formato WordProcessing, che sarà utilizzato per il salvataggio
del documento


**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - 
### setOutputFormat(WordProcessingFormats value) {#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public final void setOutputFormat(WordProcessingFormats value)
```


Consente di specificare un formato WordProcessing, che sarà utilizzato per il salvataggio
del documento


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) |  |

### getLocale() {#getLocale--}
```
public final Locale getLocale()
```


Consente di impostare la sovrascrittura della locale predefinita (lingua) per il WordProcessing
documento, che verrà applicato durante la sua creazione. Quando non è
specificato (valore predefinito), MS Word (o altro programma) rileverà (o
sceglierà) la lingua del documento in base alle proprie impostazioni o ad altri
fattori.


*** ** * ** ***

Questa opzione applica forzatamente la lingua specificata all'intero testo nel documento. Non usarla se il documento contiene diverse parti di testo scritte in lingue differenti.

<br />



**Returns:**
java.util.Locale -
### setLocale(Locale value) {#setLocale-java.util.Locale-}
```
public final void setLocale(Locale value)
```


Consente di impostare la sovrascrittura della locale predefinita (lingua) per il WordProcessing
documento, che verrà applicato durante la sua creazione. Quando non è
specificato (valore predefinito), MS Word (o altro programma) rileverà (o
sceglierà) la lingua del documento in base alle proprie impostazioni o ad altri
fattori.

*** ** * ** ***


Questa opzione applica forzatamente la lingua specificata all'intero testo in
il documento. Non usarla se il documento contiene diverse parti di
testo, che sono scritte in lingue diverse.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.Locale |  |

### getLocaleBi() {#getLocaleBi--}
```
public final Locale getLocaleBi()
```


Consente di impostare la sovrascrittura della locale (lingua) per il documento WordProcessing
per il testo RTL (da destra a sinistra), che sarà applicato durante il suo
creazione. Quando non è specificato (valore predefinito), MS Word (o altro
programma) rileverà (o sceglierà) la lingua RTL del documento in base alle proprie
impostazioni o ad altri fattori.

*** ** * ** ***


Questa opzione applica forzatamente la lingua specificata all'intero testo RTL
nel documento. Non usarla se il documento contiene diverse parti di
testo, che sono scritte in lingue diverse.


**Returns:**
java.util.Locale -
### setLocaleBi(Locale value) {#setLocaleBi-java.util.Locale-}
```
public final void setLocaleBi(Locale value)
```


Consente di impostare la sovrascrittura della locale (lingua) per il documento WordProcessing
per il testo RTL (da destra a sinistra), che sarà applicato durante il suo
creazione. Quando non è specificato (valore predefinito), MS Word (o altro
programma) rileverà (o sceglierà) la lingua RTL del documento in base alle proprie
impostazioni o ad altri fattori.

*** ** * ** ***


Questa opzione applica forzatamente la lingua specificata all'intero testo RTL
nel documento. Non usarla se il documento contiene diverse parti di
testo, che sono scritte in lingue diverse.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.Locale |  |

### getLocaleFarEast() {#getLocaleFarEast--}
```
public final Locale getLocaleFarEast()
```


Consente di sovrascrivere la locale (lingua) per il documento WordProcessing
per il testo East-Asian, che verrà applicato durante la sua creazione. Quando
non è specificato (valore predefinito), MS Word (o altro programma) rileverà
(o sceglierà) la lingua East-Asian del documento in base alle proprie impostazioni
o altri fattori.

*** ** * ** ***


Questa opzione applica forzatamente la localizzazione specificata a livello complessivo
Testo est-asiatico nel documento. Non usarlo, se il documento contiene
diverse parti di testo, scritte in diverse
lingue.


**Returns:**
java.util.Locale -
### setLocaleFarEast(Locale value) {#setLocaleFarEast-java.util.Locale-}
```
public final void setLocaleFarEast(Locale value)
```


Consente di sovrascrivere la locale (lingua) per il documento WordProcessing
per il testo East-Asian, che verrà applicato durante la sua creazione. Quando
non è specificato (valore predefinito), MS Word (o altro programma) rileverà
(o sceglierà) la lingua East-Asian del documento in base alle proprie impostazioni
o altri fattori.

*** ** * ** ***


Questa opzione applica forzatamente la localizzazione specificata a livello complessivo
Testo est-asiatico nel documento. Non usarlo, se il documento contiene
diverse parti di testo, scritte in diverse
lingue.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.Locale |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Abilita i meccanismi di ottimizzazione della memoria durante la generazione del documento da
HTML, che degrada le prestazioni come costo della riduzione dell'uso della memoria.
Impostare questa opzione su true può ridurre significativamente il consumo di memoria
durante la generazione di documenti di grandi dimensioni a costo di tempi di salvataggio più lenti.
Il valore predefinito è false (l'ottimizzazione della memoria è disabilitata per ottenere una migliore
prestazione).


**Returns:**
boolean -
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Abilita i meccanismi di ottimizzazione della memoria durante la generazione del documento da
HTML, che degrada le prestazioni come costo della riduzione dell'uso della memoria.
Impostare questa opzione su true può ridurre significativamente il consumo di memoria
durante la generazione di documenti di grandi dimensioni a costo di tempi di salvataggio più lenti.
Il valore predefinito è false (l'ottimizzazione della memoria è disabilitata per ottenere una migliore
prestazione).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getProtection() {#getProtection--}
```
public final WordProcessingProtection getProtection()
```


Consente di controllare e applicare le opzioni di protezione del documento per il
documento WordProcessing di qualsiasi formato, che supporta la protezione del documento
protezione. Per impostazione predefinita è NULL - la protezione del documento non verrà utilizzata.


**Returns:**
[WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) - 
### setProtection(WordProcessingProtection value) {#setProtection-com.groupdocs.editor.options.WordProcessingProtection-}
```
public final void setProtection(WordProcessingProtection value)
```


Consente di controllare e applicare le opzioni di protezione del documento per il
documento WordProcessing di qualsiasi formato, che supporta la protezione del documento
protezione. Per impostazione predefinita è NULL - la protezione del documento non verrà utilizzata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final int getFontEmbedding()
```


Responsabile dell'incorporamento delle risorse di carattere nell'output WordProcessing
documento. Per impostazione predefinita non incorpora alcun font (NotEmbed).


**Returns:**
int -
### setFontEmbedding(int value) {#setFontEmbedding-int-}
```
public final void setFontEmbedding(int value)
```


Responsabile dell'incorporamento delle risorse di carattere nell'output WordProcessing
documento. Per impostazione predefinita non incorpora alcun font (NotEmbed).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### deepClone() {#deepClone--}
```
public final WordProcessingSaveOptions deepClone()
```


Crea e restituisce una copia completa di questa istanza di
classe WordProcessingSaveOptions


**Returns:**
[WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) - New WordProcessingSaveOptions instance

