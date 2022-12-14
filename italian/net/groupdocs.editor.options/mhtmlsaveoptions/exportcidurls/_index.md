---
title: ExportCidUrls
second_title: GroupDocs.Editor per Riferimento API .NET
description: Specifica se utilizzare gli URL CID ContentID per fare riferimento alle risorse immagini font CSS incluse nei documenti MHTML. Il valore predefinito èfalso .
type: docs
weight: 20
url: /it/net/groupdocs.editor.options/mhtmlsaveoptions/exportcidurls/
---
## MhtmlSaveOptions.ExportCidUrls property

Specifica se utilizzare gli URL CID (Content-ID) per fare riferimento alle risorse (immagini, font, CSS) incluse nei documenti MHTML. Il valore predefinito è`falso` .

```csharp
public bool ExportCidUrls { get; set; }
```

### Osservazioni

Per impostazione predefinita, le risorse nei documenti MHTML sono referenziate dal nome del file (ad esempio, "image.png"), che viene confrontato con le intestazioni "Content-Location" delle parti MIME. Questa opzione abilita un metodo alternativo, in cui i riferimenti ai file di risorse vengono scritti come URL CID (Content-ID) (ad esempio, "cid:image.png") e confrontati con le intestazioni "Content-ID".

In teoria, non dovrebbero esserci differenze tra i due metodi di referenziazione e uno di essi dovrebbe funzionare correttamente in qualsiasi browser o agente di posta. In pratica, tuttavia, alcuni agenti non riescono a recuperare le risorse in base al nome del file. Se il tuo browser o agente di posta si rifiuta di caricare le risorse incluse in un documento MTHML (non mostra le immagini o non carica gli stili CSS), prova a esportare il documento con gli URL CID.

### Guarda anche

* class [MhtmlSaveOptions](../../mhtmlsaveoptions)
* spazio dei nomi [GroupDocs.Editor.Options](../../mhtmlsaveoptions)
* assemblea [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
