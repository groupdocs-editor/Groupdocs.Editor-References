---
title: "FontExtractionOptions"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Le opzioni di estrazione dei font controllano quali font devono essere estratti e da dove"
type: docs
weight: 18
url: /it/java/com.groupdocs.editor.options/fontextractionoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontExtractionOptions
```

Le opzioni di estrazione dei font controllano quali font devono essere estratti e da
da dove

## Campi

| Campo | Descrizione |
| --- | --- |
|  | [NotExtract](#NotExtract) | Non estrae alcuna risorsa di font né dal documento né dal |
sistema.
|
|  | [ExtractAllEmbedded](#ExtractAllEmbedded) | Estrae tutte le risorse di font, che sono incorporate nel Word di input |
documento, indipendentemente dal tipo: personalizzato o di sistema.
|
|  | [ExtractEmbeddedWithoutSystem](#ExtractEmbeddedWithoutSystem) | Estrae solo quelle risorse di font incorporate, che sono personalizzate (non |
di sistema)
|
|  | [ExtractAll](#ExtractAll) | Cerca di estrarre tutti i font, che sono usati nel WordProcessing di input |
documento, inclusi i font di sistema.
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFontExtractionOptions()](#getFontExtractionOptions--) |  |
### NotExtract {#NotExtract}
```
public static final int NotExtract
```


Non estrae alcuna risorsa di font né dal documento né dal
sistema. Valore predefinito.


### ExtractAllEmbedded {#ExtractAllEmbedded}
```
public static final int ExtractAllEmbedded
```


Estrae tutte le risorse di font, che sono incorporate nel Word di input
documento, indipendentemente dal tipo: personalizzato o di sistema.


*** ** * ** ***

Converter trova ed estrae tutte le risorse di carattere al 100%, che sono incorporate nel documento WordProcessing di input, ma non determina se siano di sistema o personalizzate; non tocca affatto il Registro di Windows né le cartelle di sistema.

<br />



### ExtractEmbeddedWithoutSystem {#ExtractEmbeddedWithoutSystem}
```
public static final int ExtractEmbeddedWithoutSystem
```


Estrae solo quelle risorse di font incorporate, che sono personalizzate (non
di sistema)


*** ** * ** ***

Converter trova ed estrae tutte le risorse di carattere incorporate, quindi tenta di determinare quali di questi caratteri siano di sistema e quali no. Per raggiungere questo obiettivo, Converter cerca di ottenere un elenco di tutti i caratteri di sistema utilizzando il Registro di Windows e le cartelle di sistema, e poi confronta questo elenco con l'insieme dei caratteri incorporati. Di conseguenza, verrà restituito solo il sottoinsieme di quei caratteri incorporati che non sono stati trovati nel sistema.

<br />



### ExtractAll {#ExtractAll}
```
public static final int ExtractAll
```


Cerca di estrarre tutti i font, che sono usati nel WordProcessing di input
documento, inclusi i font di sistema.


*** ** * ** ***

Converter sta analizzando un documento WordProcessing di input e trova tutti i caratteri utilizzati. Se tutti questi caratteri sono incorporati nel documento di input, Converter li estrae e li restituisce. Altrimenti, se la raccolta di caratteri incorporati non copre tutti i caratteri usati nel documento, o è vuota, Converter tenta di estrarre queste risorse di carattere dal sistema, utilizzando il Registro di Windows e le cartelle di sistema.

<br />



### getFontExtractionOptions() {#getFontExtractionOptions--}
```
public static int[] getFontExtractionOptions()
```




**Returns:**
int[]
