---
title: TextResourceBase
second_title: GroupDocs.Editor per Riferimento API .NET
description: Classe base per qualsiasi risorsa di testo supportata con contenuto di testo e codifica
type: docs
weight: 640
url: /it/net/groupdocs.editor.htmlcss.resources.textual/textresourcebase/
---
## TextResourceBase class

Classe base per qualsiasi risorsa di testo supportata con contenuto di testo e codifica

```csharp
public abstract class TextResourceBase : IHtmlResource
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/bytecontent) { get; } | Restituisce il contenuto di questa risorsa di testo come flusso di byte con codifica originale |
| [Encoding](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/encoding) { get; } | Restituisce la codifica di questa risorsa testuale. Di solito restituisce UTF-8. |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/filenamewithextension) { get; } | Restituisce il nome file corretto di questa risorsa di testo, composto da nome ed estensione |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/isdisposed) { get; } | Determina se questa risorsa di testo è eliminata o meno |
| [Name](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/name) { get; } | Restituisce il nome di questa risorsa di testo senza estensione file |
| [TextContent](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/textcontent) { get; } | Restituisce il contenuto di questa risorsa di testo come stringa standard |
| abstract [Type](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/type) { get; } | Nell'implementazione del tipo dovrebbe restituire informazioni sul tipo della risorsa di testo |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/dispose)() | Elimina questa risorsa di testo, eliminandone il contenuto e rendendo la maggior parte dei metodi e delle proprietà non funzionanti. Tollerante a più chiamate. |
| [Equals](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/equals#equals)(IHtmlResource) | Controlla questa istanza con l'uguaglianza specificata. |
| [Save](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/save)(string) | Salva questa risorsa di testo nel file specificato |

## Eventi

| Nome | Descrizione |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/disposed) | Evento che si verifica quando questa risorsa di testo viene eliminata |

### Guarda anche

* interface [IHtmlResource](../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* spazio dei nomi [GroupDocs.Editor.HtmlCss.Resources.Textual](../../groupdocs.editor.htmlcss.resources.textual)
* assemblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
