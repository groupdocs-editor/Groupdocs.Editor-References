---
title: "Editor"
second_title: "GroupDocs.Editor voor .NET API-referentie"
description: "Hoofdklaas die conversiemethoden omvat. De Editor-klasse biedt methoden voor het laden, bewerken en opslaan van documenten in alle ondersteunde formaten. Het is wegwerpbaar, dus gebruik een using-directief of maak de bronnen handmatig vrij via een aanroep van de Dispose-methode. Documentladen wordt uitgevoerd via constructors. Documentbewerking via de methode Edit en opslaan van het resulterende document na bewerking via de methode Save."
type: docs
weight: 20
url: /nl/net/groupdocs.editor/editor/
---
## Editor class

Hoofdklasse, die conversiemethoden omvat. De Editor-klasse biedt methoden voor het laden, bewerken en opslaan van documenten in alle ondersteunde formaten. Het is wegwerpbaar, dus gebruik een 'using'-directive of maak de bronnen handmatig vrij via een 'Dispose()'-methodeaanroep. Documentladen wordt uitgevoerd via constructors. Documentbewerking – via de methode 'Edit', en opslaan van het resulterende document na bewerking – via de methode 'Save'.

```csharp
public sealed class Editor : IAuxDisposable
```

## Constructors

| Name | Beschrijving |
| --- | --- |
| [Editor](editor#constructor)(DocumentFormatBase) | Initialiseert een nieuw exemplaar van de [`Editor`](../editor) klasse en maakt een nieuw leeg document aan op basis van het opgegeven formaat. |
| [Editor](editor#constructor_1)(Stream) | Initialiseert een nieuw Editor‑exemplaar met een opgegeven invoerdocument (als een stream). |
| [Editor](editor#constructor_3)(string) | Initialiseert een nieuw Editor‑exemplaar met een opgegeven invoerdocument (als een volledig bestandspad) en Editor‑instellingen. |
| [Editor](editor#constructor_2)(Stream, ILoadOptions) | Initialiseert een nieuw Editor‑exemplaar met een opgegeven invoerdocument (als een stream) met de laadopties. |
| [Editor](editor#constructor_4)(string, ILoadOptions) | Initialiseert een nieuw Editor‑exemplaar met een opgegeven invoerdocument (als een volledig bestandspad) met de laadopties. |

## Properties

| Name | Beschrijving |
| --- | --- |
| [FormFieldManager](../../groupdocs.editor/editor/formfieldmanager) { get; } | Biedt toegang tot functionaliteit voor het beheren van formuliervelden binnen het document. |
| [IsDisposed](../../groupdocs.editor/editor/isdisposed) { get; } | Geeft aan of dit Editor‑exemplaar al is verwijderd en niet meer kan worden gebruikt (true) of nog niet is verwijderd en dus actief is (false). |

## Methods

| Name | Beschrijving |
| --- | --- |
| [Dispose](../../groupdocs.editor/editor/dispose)() | Verwijdert dit exemplaar van Editor, zodat het alle interne bronnen vrijgeeft en niet meer beschikbaar is voor verder gebruik. |
| [Edit](../../groupdocs.editor/editor/edit#edit)() | Opent een eerder geladen document voor bewerking met standaardopties door een exemplaar van de '[`EditableDocument`](../editabledocument)'‑klasse te genereren en terug te geven, die op haar beurt methoden bevat voor het produceren van HTML‑opmaak en bijbehorende bronnen. |
| [Edit](../../groupdocs.editor/editor/edit#edit_1)(IEditOptions) | Opent een eerder geladen document voor bewerking met opgegeven formaat‑specifieke opties door een exemplaar van de '[`EditableDocument`](../editabledocument)'‑klasse te genereren en terug te geven, die op haar beurt methoden bevat voor het produceren van HTML‑opmaak en bijbehorende bronnen. |
| [GetDocumentInfo](../../groupdocs.editor/editor/getdocumentinfo)(string) | Retourneert metadata over het document dat in dit 'Editor'‑exemplaar is geladen. |
| [Save](../../groupdocs.editor/editor/save#save)(Stream) | Sla de huidige documentinhoud op naar de opgegeven uitvoer‑stream. |
| [Save](../../groupdocs.editor/editor/save#save_3)(EditableDocument, string) | Converteert het opgegeven bewerkte document, weergegeven als een exemplaar van '[`EditableDocument`](../editabledocument)', naar het resulterende document van een formaat dat wordt bepaald aan de hand van de bestandsnaamextensie, en slaat de inhoud op naar een bestand via het opgegeven bestandspad. |
| [Save](../../groupdocs.editor/editor/save#save_1)(Stream, WordProcessingSaveOptions) | Converteert het originele document na wijziging (bijvoorbeeld met [`FormFieldManager`](./formfieldmanager)) naar het resulterende document van het opgegeven formaat en slaat de inhoud op naar de opgegeven stream. |
| [Save](../../groupdocs.editor/editor/save#save_2)(EditableDocument, Stream, ISaveOptions) | Converteert het opgegeven bewerkte document, weergegeven als een exemplaar van '[`EditableDocument`](../editabledocument)', naar het resulterende document van het opgegeven formaat en slaat de inhoud op naar de opgegeven stream. |
| [Save](../../groupdocs.editor/editor/save#save_4)(EditableDocument, string, ISaveOptions) | Converteert het opgegeven bewerkte document, weergegeven als een exemplaar van '[`EditableDocument`](../editabledocument)', naar het resulterende document van het opgegeven formaat en slaat de inhoud op naar een bestand via het opgegeven bestandspad. |

## Evenementen

| Name | Beschrijving |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editor/disposed) | Evenement dat optreedt wanneer dit Editor‑exemplaar wordt verwijderd met al zijn interne bronnen. |

### Opmerkingen

De Editor‑klasse moet worden beschouwd als een toegangspunt en het hoofdobject van GroupDocs.Editor. Alle bewerkingen worden uitgevoerd met behulp van deze klasse. Een typisch gebruik van de Editor‑klasse voor het uitvoeren van een volledige documentbewerkings‑pipeline is als volgt:

1. Laad een document in het Editor‑exemplaar via de constructor.
2. Detecteer optioneel een documenttype met behulp van de [`GetDocumentInfo`](./getdocumentinfo)‑methode.
3. Open een document voor bewerking door de [`Edit`](./edit)‑methode aan te roepen en een exemplaar van de [`EditableDocument`](../editabledocument)‑klasse ervan te verkrijgen.
4. Bewerk de documentinhoud aan de client‑zijde met behulp van een willekeurige WYSIWYG HTML‑editor.
5. Maak een nieuw exemplaar van [`EditableDocument`](../editabledocument) aan op basis van de bewerkte documentinhoud.
6. Sla een bewerkt document op naar een bepaald uitvoerformaat door de [`Save`](./save)‑methode aan te roepen.
7. Het vrijgeven van een instantie van de Editor‑klasse via de 'using'-operator of handmatig.

### Zie ook

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* namespace [GroupDocs.Editor](../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
