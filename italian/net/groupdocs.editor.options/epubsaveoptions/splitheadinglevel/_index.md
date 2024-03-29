---
title: SplitHeadingLevel
second_title: GroupDocs.Editor per Riferimento API .NET
description: Specifica il livello massimo di intestazioni a cui suddividere il file ePub. Il valore predefinito è2 . Impostandolo su0 disabiliterà la suddivisione quindi tutto il contenuto dellebook verrà incorporato in un unico pacchetto allinterno dellePub.
type: docs
weight: 30
url: /it/net/groupdocs.editor.options/epubsaveoptions/splitheadinglevel/
---
## EpubSaveOptions.SplitHeadingLevel property

Specifica il livello massimo di intestazioni a cui suddividere il file ePub. Il valore predefinito è`2` . Impostandolo su`0` disabiliterà la suddivisione, quindi tutto il contenuto dell'e-book verrà incorporato in un unico pacchetto all'interno dell'ePub.

```csharp
public int SplitHeadingLevel { get; set; }
```

### Osservazioni

Quando questa proprietà è impostata su un valore compreso tra 1 e 9, il documento verrà suddiviso in paragrafi formattati utilizzando **Titolo 1** ,**Titolo 2** ,**Titolo 3** ecc. stili fino al livello di intestazione specificato.

Per impostazione predefinita, solo**Titolo 1** E**Titolo 2** i paragrafi causano la divisione del documento. L'impostazione di questa proprietà su zero farà sì che il documento non venga affatto diviso in corrispondenza dei paragrafi di intestazione.

### Guarda anche

* class [EpubSaveOptions](../../epubsaveoptions)
* spazio dei nomi [GroupDocs.Editor.Options](../../epubsaveoptions)
* assemblea [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
