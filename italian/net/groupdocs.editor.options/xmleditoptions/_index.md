---
title: XmlEditOptions
second_title: GroupDocs.Editor per Riferimento API .NET
description: Consente di specificare opzioni personalizzate per la modifica di documenti XML eXtensible Markup Language e la loro conversione in HTML
type: docs
weight: 1270
url: /it/net/groupdocs.editor.options/xmleditoptions/
---
## XmlEditOptions class

Consente di specificare opzioni personalizzate per la modifica di documenti XML (eXtensible Markup Language) e la loro conversione in HTML

```csharp
public sealed class XmlEditOptions : IEditOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [XmlEditOptions](xmleditoptions)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AttributeValuesQuoteType](../../groupdocs.editor.options/xmleditoptions/attributevaluesquotetype) { get; set; } | Consente di specificare il tipo di virgolette (virgolette singole o doppie) per i valori degli attributi. Le virgolette doppie sono predefinite. |
| [Encoding](../../groupdocs.editor.options/xmleditoptions/encoding) { get; set; } | Codifica dei caratteri del documento di testo, che verrà applicata per la sua apertura. Per impostazione predefinita è null: verrà applicata la codifica interna del documento. |
| [FixIncorrectStructure](../../groupdocs.editor.options/xmleditoptions/fixincorrectstructure) { get; set; } | Consente di abilitare o disabilitare il meccanismo per correggere la struttura XML danneggiata. Di default è disabilitato (false). |
| [FormatOptions](../../groupdocs.editor.options/xmleditoptions/formatoptions) { get; } | Consente di regolare la formattazione XML, che verrà applicata alla struttura XML, quando viene rappresentata in HTML. Viene utilizzata la formattazione predefinita ed è regolabile. Non può essere nullo. |
| [HighlightOptions](../../groupdocs.editor.options/xmleditoptions/highlightoptions) { get; } | Consente di regolare l'evidenziazione XML, che verrà applicata alla struttura XML, quando viene rappresentata in HTML. Viene utilizzata l'evidenziazione predefinita ed è regolabile. Non può essere nullo. |
| [RecognizeEmails](../../groupdocs.editor.options/xmleditoptions/recognizeemails) { get; set; } | Consente di abilitare l'algoritmo di riconoscimento per gli indirizzi email nei valori degli attributi |
| [RecognizeUris](../../groupdocs.editor.options/xmleditoptions/recognizeuris) { get; set; } | Consente di abilitare l'algoritmo di riconoscimento URI |
| [TrimTrailingWhitespaces](../../groupdocs.editor.options/xmleditoptions/trimtrailingwhitespaces) { get; set; } | Consente di abilitare il troncamento degli spazi bianchi finali nel testo del tag interno. Per impostazione predefinita è disabilitato (false) — gli spazi bianchi finali verranno preservati. |

### Guarda anche

* interface [IEditOptions](../ieditoptions)
* spazio dei nomi [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assemblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
