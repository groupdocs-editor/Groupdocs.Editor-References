---
title: "MhtmlSaveOptions"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Consente di specificare opzioni personalizzate per generare e salvare l'incapsulamento MIME MHTML di documenti HTML aggregati documenti"
type: docs
weight: 26
url: /it/java/com.groupdocs.editor.options/mhtmlsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MhtmlSaveOptions implements ISaveOptions
```

Consente di specificare opzioni personalizzate per la generazione e il salvataggio dei documenti MHTML (incapsulamento MIME di documenti HTML aggregati)

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MhtmlSaveOptions()](#MhtmlSaveOptions--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getExportCidUrls()](#getExportCidUrls--) | Specifica se utilizzare URL CID (Content-ID) per fare riferimento alle risorse (immagini, font, CSS) incluse nei documenti MHTML. |
|
|  | [setExportCidUrls(boolean value)](#setExportCidUrls-boolean-) | Specifica se utilizzare URL CID (Content-ID) per fare riferimento alle risorse (immagini, font, CSS) incluse nei documenti MHTML. |
|
|  | [getExportDocumentProperties()](#getExportDocumentProperties--) | Specifica se esportare le proprietà del documento integrate e personalizzate in MHTML. |
|
|  | [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | Specifica se esportare le proprietà del documento integrate e personalizzate in MHTML. |
|
|  | [getExportLanguageInformation()](#getExportLanguageInformation--) | Specifica se le informazioni sulla lingua vengono esportate in MHTML. |
|
|  | [setExportLanguageInformation(boolean value)](#setExportLanguageInformation-boolean-) | Specifica se le informazioni sulla lingua vengono esportate in MHTML. |
|
### MhtmlSaveOptions() {#MhtmlSaveOptions--}
```
public MhtmlSaveOptions()
```


### getExportCidUrls() {#getExportCidUrls--}
```
public final boolean getExportCidUrls()
```


Specifica se utilizzare URL CID (Content-ID) per fare riferimento alle risorse (immagini, font, CSS) incluse nei documenti MHTML. Il valore predefinito è
false
.

<br />

*** ** * ** ***


Per impostazione predefinita, le risorse nei documenti MHTML sono referenziate per nome file (ad esempio, "image.png"), che vengono confrontate con le intestazioni "Content-Location" delle parti MIME. Questa opzione abilita un metodo alternativo, in cui i riferimenti ai file delle risorse sono scritti come URL CID (Content-ID) (ad esempio, "cid:image.png") e vengono confrontati con le intestazioni "Content-ID".


In teoria, non dovrebbe esserci alcuna differenza tra i due metodi di riferimento e ciascuno di essi dovrebbe funzionare correttamente in qualsiasi browser o client di posta. In pratica, tuttavia, alcuni client non riescono a recuperare le risorse per nome file. Se il tuo browser o client di posta rifiuta di caricare le risorse incluse in un documento MTHML (non mostra le immagini o non carica gli stili CSS), prova a esportare il documento con URL CID.

<br />



**Returns:**
boolean
### setExportCidUrls(boolean value) {#setExportCidUrls-boolean-}
```
public final void setExportCidUrls(boolean value)
```


Specifica se utilizzare URL CID (Content-ID) per fare riferimento alle risorse (immagini, font, CSS) incluse nei documenti MHTML. Il valore predefinito è
false
.

<br />

*** ** * ** ***


Per impostazione predefinita, le risorse nei documenti MHTML sono referenziate per nome file (ad esempio, "image.png"), che vengono confrontate con le intestazioni "Content-Location" delle parti MIME. Questa opzione abilita un metodo alternativo, in cui i riferimenti ai file delle risorse sono scritti come URL CID (Content-ID) (ad esempio, "cid:image.png") e vengono confrontati con le intestazioni "Content-ID".


In teoria, non dovrebbe esserci alcuna differenza tra i due metodi di riferimento e ciascuno di essi dovrebbe funzionare correttamente in qualsiasi browser o client di posta. In pratica, tuttavia, alcuni client non riescono a recuperare le risorse per nome file. Se il tuo browser o client di posta rifiuta di caricare le risorse incluse in un documento MTHML (non mostra le immagini o non carica gli stili CSS), prova a esportare il documento con URL CID.

<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getExportDocumentProperties() {#getExportDocumentProperties--}
```
public final boolean getExportDocumentProperties()
```


Specifica se esportare le proprietà del documento integrate e personalizzate in MHTML. Il valore predefinito è
false
.


**Returns:**
boolean
### setExportDocumentProperties(boolean value) {#setExportDocumentProperties-boolean-}
```
public final void setExportDocumentProperties(boolean value)
```


Specifica se esportare le proprietà del documento integrate e personalizzate in MHTML. Il valore predefinito è
false
.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getExportLanguageInformation() {#getExportLanguageInformation--}
```
public final boolean getExportLanguageInformation()
```


Specifica se le informazioni sulla lingua vengono esportate in MHTML. Il valore predefinito è
false
.

<br />

*** ** * ** ***

Quando questa proprietà è impostata su  true , il GroupDocs.Editor emette l'attributo HTML  lang  sugli elementi del documento che specificano la lingua. Questo può essere necessario per preservare la semantica legata alla lingua.

<br />



**Returns:**
boolean
### setExportLanguageInformation(boolean value) {#setExportLanguageInformation-boolean-}
```
public final void setExportLanguageInformation(boolean value)
```


Specifica se le informazioni sulla lingua vengono esportate in MHTML. Il valore predefinito è
false
.

<br />

*** ** * ** ***

Quando questa proprietà è impostata su  true , il GroupDocs.Editor emette l'attributo HTML  lang  sugli elementi del documento che specificano la lingua. Questo può essere necessario per preservare la semantica legata alla lingua.

<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

