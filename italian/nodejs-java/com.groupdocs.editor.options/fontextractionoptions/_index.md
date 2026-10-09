---
title: "FontExtractionOptions"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Le opzioni di estrazione dei caratteri controllano quali caratteri devono essere estratti e da dove"
type: docs
weight: 18
url: /it/nodejs-java/com.groupdocs.editor.options/fontextractionoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontExtractionOptions
```

Le opzioni di estrazione dei caratteri controllano quali caratteri devono essere estratti e da
dove

## Campi

| Campo | Descrizione |
| --- | --- |
|  | [NotExtract](#NotExtract) | Non estrae alcuna risorsa di carattere né dal documento né dal |
sistema.
|
|  | [ExtractAllEmbedded](#ExtractAllEmbedded) | Estrae tutte le risorse di carattere, che sono incorporate nel Word di input |
documento, indipendentemente da cosa siano: personalizzati o di sistema.
|
|  | [ExtractEmbeddedWithoutSystem](#ExtractEmbeddedWithoutSystem) | Estrae solo le risorse di font incorporate che sono personalizzate (non |
di sistema)
|
|  | [ExtractAll](#ExtractAll) | Cerca di estrarre tutti i font che sono usati nel WordProcessing di input |
documento, includendo i font di sistema.
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFontExtractionOptions()](#getFontExtractionOptions--) |  |
### NotExtract {#NotExtract}
```
public static final int NotExtract
```


Non estrae alcuna risorsa di carattere né dal documento né dal
di sistema. Valore predefinito.


### ExtractAllEmbedded {#ExtractAllEmbedded}
```
public static final int ExtractAllEmbedded
```


Estrae tutte le risorse di carattere, che sono incorporate nel Word di input
documento, indipendentemente da cosa siano: personalizzati o di sistema.


*** ** * ** ***

Il convertitore trova ed estrae tutte le risorse di font al 100% che sono incorporate nel documento WordProcessing di input, ma non determina se siano di sistema o personalizzate; non tocca affatto il Registro di Windows né le cartelle di sistema.

<br />



### ExtractEmbeddedWithoutSystem {#ExtractEmbeddedWithoutSystem}
```
public static final int ExtractEmbeddedWithoutSystem
```


Estrae solo le risorse di font incorporate che sono personalizzate (non
di sistema)


*** ** * ** ***

Il convertitore trova ed estrae tutte le risorse di font incorporate, quindi tenta di determinare quali di questi font siano di sistema e quali no. Per farlo, il convertitore cerca di ottenere un elenco di tutti i font di sistema usando il Registro di Windows e le cartelle di sistema, e poi confronta questo elenco con l'insieme dei font incorporati. Come risultato, verrà restituito solo il sottoinsieme di quei font incorporati che non sono stati trovati nel sistema.

<br />



### ExtractAll {#ExtractAll}
```
public static final int ExtractAll
```


Cerca di estrarre tutti i font che sono usati nel WordProcessing di input
documento, includendo i font di sistema.


*** ** * ** ***

Il convertitore sta analizzando un documento WordProcessing di input e trova tutti i font utilizzati. Se tutti questi font sono incorporati nel documento di input, il convertitore li estrae e li restituisce. Altrimenti, se una raccolta di font incorporati non copre tutti i font usati nel documento, o è vuota, il convertitore tenta di estrarre queste risorse di font dal sistema, usando il Registro di Windows e le cartelle di sistema.

<br />



### getFontExtractionOptions() {#getFontExtractionOptions--}
```
public static int[] getFontExtractionOptions()
```




**Returns:**
int[]
