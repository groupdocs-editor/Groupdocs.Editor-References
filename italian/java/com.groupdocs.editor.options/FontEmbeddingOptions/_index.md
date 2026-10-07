---
title: "FontEmbeddingOptions"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Le opzioni di incorporamento dei font controllano quali risorse di font devono essere incorporate nel documento WordProcessing di output"
type: docs
weight: 17
url: /it/java/com.groupdocs.editor.options/fontembeddingoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontEmbeddingOptions
```

Le opzioni di incorporamento dei font controllano quali risorse di font devono essere incorporate in
il documento WordProcessing di output


*** ** * ** ***

Le opzioni di incorporamento dei font vengono applicate durante il salvataggio del documento (da EditableDocument intermedio al formato WordProcessing di output), questa enumerazione è inclusa come proprietà in WordProcessingSaveOptions, da cui dovrebbe essere utilizzata

<br />


## Campi

| Campo | Descrizione |
| --- | --- |
|  | [NotEmbed](#NotEmbed) | Non incorporare alcuna risorsa di font né da EditableDocument né da |
sistema.
|
|  | [EmbedAll](#EmbedAll) | Analizza il contenuto del documento dall'EditableDocument di input, trova tutti i font utilizzati |
e incorporali nel documento WordProcessing di output.
|
|  | [EmbedWithoutSystem](#EmbedWithoutSystem) | Esatto a [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), ma escludi quei font, |
che sono trattati dal sistema operativo come font di sistema
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFontEmbeddingOptions()](#getFontEmbeddingOptions--) |  |
### NotEmbed {#NotEmbed}
```
public static final int NotEmbed
```


Non incorporare alcuna risorsa di font né da EditableDocument né da
sistema. Valore predefinito.


### EmbedAll {#EmbedAll}
```
public static final int EmbedAll
```


Analizza il contenuto del documento dall'EditableDocument di input, trova tutti i font utilizzati
e incorporali nel documento WordProcessing di output. In primo luogo
GroupDocs.Editor prende i font dalle risorse dei font all'interno di EditableDocument.
Se sono insufficienti o mancanti, allora GroupDocs.Editor prende i font
dal sistema operativo.


*** ** * ** ***

Prima di tutto GroupDocs.Editor analizza il contenuto di EditableDocument e forma un elenco di tutti i font utilizzati. Quindi questi font vengono cercati nelle risorse dei font di EditableDocument. Se EditableDocument contiene alcune risorse di font che non sono coinvolte nel contenuto del documento, tali risorse vengono ignorate. Se ci sono dei font usati nel contenuto del documento che non hanno risorse di font corrispondenti in EditableDocument, allora GroupDocs.Editor tenta di trovarli nel sistema operativo. Questa opzione assomiglia all'opzione \"Embed fonts in the file\" con tutte le sotto‑opzioni disattivate in Microsoft Word 2007 e successive

<br />



### EmbedWithoutSystem {#EmbedWithoutSystem}
```
public static final int EmbedWithoutSystem
```


Esatto a [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), ma escludi quei font,
che sono trattati dal sistema operativo come font di sistema


*** ** * ** ***

MS Windows ha un concetto di font di sistema, che sono i font più basilari e utilizzati da Windows stesso. Quando si utilizza questa opzione, GroupDocs.Editor si comporta come nel caso [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), ma alla fine esamina l'insieme dei font ottenuti ed esclude quelli che sono trattati dal sistema operativo come font di sistema. Questa opzione assomiglia alle opzioni \"Embed fonts in the file\" + \"Do not embed common system fonts\" in Microsoft Word 2007 e successive

<br />



### getFontEmbeddingOptions() {#getFontEmbeddingOptions--}
```
public static int[] getFontEmbeddingOptions()
```




**Returns:**
int[]
