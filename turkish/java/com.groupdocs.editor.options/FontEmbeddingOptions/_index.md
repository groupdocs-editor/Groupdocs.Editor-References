---
title: "FontEmbeddingOptions"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Yazı tipi gömme seçenekleri, hangi yazı tipi kaynaklarının çıktı WordProcessing belgesine gömülmesi gerektiğini kontrol eder"
type: docs
weight: 17
url: /tr/java/com.groupdocs.editor.options/fontembeddingoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontEmbeddingOptions
```

Yazı tipi gömme seçenekleri, hangi yazı tipi kaynaklarının gömülmesi gerektiğini kontrol eder
çıktı WordProcessing belgesi


*** ** * ** ***

Yazı tipi gömme seçenekleri, belge kaydedilirken (ara EditableDocument'tan çıktı WordProcessing formatına) uygulanır, bu enum WordProcessingSaveOptions içinde bir özellik olarak bulunur ve oradan kullanılmalıdır

<br />


## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [NotEmbed](#NotEmbed) | Herhangi bir yazı tipi kaynağı, EditableDocument'tan ya da |
sistemden.
|
|  | [EmbedAll](#EmbedAll) | Giriş EditableDocument'tan belge içeriğini analiz edin, kullanılan tüm yazı tiplerini bulun |
ve bunları çıktı WordProcessing belgesine gömün.
|
|  | [EmbedWithoutSystem](#EmbedWithoutSystem) | Tam olarak [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), ancak bu yazı tiplerini hariç tut, |
İşletim sistemi tarafından sistem yazı tipleri olarak kabul edilen
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFontEmbeddingOptions()](#getFontEmbeddingOptions--) |  |
### NotEmbed {#NotEmbed}
```
public static final int NotEmbed
```


Herhangi bir yazı tipi kaynağı, EditableDocument'tan ya da
sistem. Varsayılan değer.


### EmbedAll {#EmbedAll}
```
public static final int EmbedAll
```


Giriş EditableDocument'tan belge içeriğini analiz edin, kullanılan tüm yazı tiplerini bulun
ve bunları çıktı WordProcessing belgesine göm. İlk olarak
GroupDocs.Editor, EditableDocument içindeki yazı tipi kaynaklarından yazı tiplerini alır.
Eğer yetersiz veya eksikse, GroupDocs.Editor yazı tiplerini alır
işletim sisteminden.


*** ** * ** ***

İlk olarak GroupDocs.Editor, EditableDocument içeriğini analiz eder ve kullanılan tüm yazı tiplerinin bir listesini oluşturur. Daha sonra bu yazı tipleri, EditableDocument'in yazı tipi kaynaklarında aranır. EditableDocument, belge içeriğinde kullanılmayan bazı yazı tipi kaynakları içeriyorsa, bu kaynaklar göz ardı edilir. Belge içeriğinde kullanılan ve EditableDocument içinde karşılık gelen yazı tipi kaynağı bulunmayan yazı tipleri varsa, GroupDocs.Editor bunları işletim sisteminde bulmaya çalışır. Bu seçenek, Microsoft Word 2007 ve üzerindeki tüm alt seçenekleri kapalı olan \"Embed fonts in the file\" seçeneğine benzer.

<br />



### EmbedWithoutSystem {#EmbedWithoutSystem}
```
public static final int EmbedWithoutSystem
```


Tam olarak [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), ancak bu yazı tiplerini hariç tut,
İşletim sistemi tarafından sistem yazı tipleri olarak kabul edilen


*** ** * ** ***

MS Windows, Windows'un kendisi tarafından en temel ve en çok kullanılan yazı tipleri olan sistem yazı tipleri kavramına sahiptir. Bu seçeneği kullanırken, GroupDocs.Editor [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll) durumunda olduğu gibi davranır, ancak sonunda elde edilen yazı tipleri setini gözden geçirir ve işletim sistemi tarafından sistem yazı tipleri olarak kabul edilenleri hariç tutar. Bu seçenek, Microsoft Word 2007 ve üzerindeki \"Embed fonts in the file\" + \"Do not embed common system fonts\" seçeneklerine benzer.

<br />



### getFontEmbeddingOptions() {#getFontEmbeddingOptions--}
```
public static int[] getFontEmbeddingOptions()
```




**Returns:**
int[]
