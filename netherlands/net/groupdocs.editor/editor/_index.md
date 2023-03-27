---
title: Editor
second_title: GroupDocs.Editor voor .NET API-referentie
description: Hoofdklasse die conversiemethoden bevat. Editorklasse biedt methoden voor het laden bewerken en opslaan van documenten van alle ondersteunde indelingen. Het is wegwerpbaar dus gebruik een usingrichtlijn of verwijder de bronnen handmatig via de Disposemethodeaanroep. Het laden van documenten wordt uitgevoerd via constructors. Documentbewerking  via de methode Bewerken en na bewerking terug opslaan in het resulterende document  via de methode Opslaan.
type: docs
weight: 20
url: /nl/net/groupdocs.editor/editor/
---
## Editor class

Hoofdklasse, die conversiemethoden bevat. Editor-klasse biedt methoden voor het laden, bewerken en opslaan van documenten van alle ondersteunde indelingen. Het is wegwerpbaar, dus gebruik een 'using'-richtlijn of verwijder de bronnen handmatig via de 'Dispose()'-methodeaanroep. Het laden van documenten wordt uitgevoerd via constructors. Documentbewerking - via de methode 'Bewerken', en na bewerking terug opslaan in het resulterende document - via de methode 'Opslaan'.

```csharp
public sealed class Editor : IAuxDisposable
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [Editor](editor#constructor)(Func&lt;Stream&gt;) | Initialiseert nieuwe Editor-instantie met opgegeven invoerdocument (als een stream) |
| [Editor](editor#constructor_2)(string) | Initialiseert nieuwe Editor-instantie met opgegeven invoerdocument (als een volledig bestandspad) |
| [Editor](editor#constructor_1)(Func&lt;Stream&gt;, Func&lt;ILoadOptions&gt;) | Initialiseert nieuwe Editor-instantie met opgegeven invoerdocument (als een stream) met zijn laadopties |
| [Editor](editor#constructor_3)(string, Func&lt;ILoadOptions&gt;) | Initialiseert nieuwe Editor-instantie met opgegeven invoerdocument (als een volledig bestandspad) met zijn laadopties |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [IsDisposed](../../groupdocs.editor/editor/isdisposed) { get; } | Geeft aan of deze Editor-instantie al is verwijderd en niet meer kan worden gebruikt (true) of nog niet is verwijderd en dus actief is (false) |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Dispose](../../groupdocs.editor/editor/dispose)() | Verwijdert dit exemplaar van Editor, zodat het alle interne bronnen vrijgeeft en niet meer beschikbaar is voor verder gebruik |
| [Edit](../../groupdocs.editor/editor/edit#edit)() | Opent een eerder geladen document voor bewerking met behulp van standaardopties door een instantie van ' te genereren en terug te sturen[`EditableDocument`](../editabledocument) class, die op zijn beurt methoden bevat voor het produceren van HTML-opmaak en bijbehorende bronnen. |
| [Edit](../../groupdocs.editor/editor/edit#edit_1)(IEditOptions) | Opent een eerder geladen document voor bewerking met behulp van gespecificeerde formaatspecifieke opties door een instantie van ' te genereren en terug te sturen[`EditableDocument`](../editabledocument) class, die op zijn beurt methoden bevat voor het produceren van HTML-opmaak en bijbehorende bronnen. |
| [GetDocumentInfo](../../groupdocs.editor/editor/getdocumentinfo)(string) | Retourneert metadata over het document dat in deze 'Editor'-instantie is geladen |
| [Save](../../groupdocs.editor/editor/save#save)(EditableDocument, Stream, ISaveOptions) | Converteert gespecificeerd bewerkt document, weergegeven als instantie van '[`EditableDocument`](../editabledocument) , naar het resulterende document met een opgegeven indeling en slaat de inhoud op in de opgegeven stream |
| [Save](../../groupdocs.editor/editor/save#save_1)(EditableDocument, string, ISaveOptions) | Converteert gespecificeerd bewerkt document, weergegeven als instantie van '[`EditableDocument`](../editabledocument) , naar het resulterende document met een opgegeven indeling en slaat de inhoud op in een bestand met het opgegeven bestandspad |

## Evenementen

| Naam | Beschrijving |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editor/disposed) | Gebeurtenis, die optreedt wanneer deze Editor-instantie wordt verwijderd met al zijn interne bronnen |

### Opmerkingen

De klasse Editor moet worden beschouwd als een ingangspunt en het hoofdobject van GroupDocs.Editor. Alle bewerkingen worden uitgevoerd met deze klasse. Typisch gebruik van de Editor-klasse voor het uitvoeren van een volledige documentbewerkingspijplijn is de volgende:

1. Laad een document in de Editor-instantie via de constructor.
2. Detecteer optioneel een documenttype met behulp van een[`GetDocumentInfo`](./getdocumentinfo) methode.
3. Open een document om te bewerken door een[`Edit`](./edit)methode en het verkrijgen van een instantie van[`EditableDocument`](../editabledocument) klasse ervan.
4. De inhoud van een document aan de clientzijde bewerken met behulp van een WYSIWYG HTML-editor.
5. Een nieuw exemplaar van maken[`EditableDocument`](../editabledocument) van bewerkte documentinhoud.
6. Een bewerkt document opslaan in een uitvoerformaat door een[`Save`](./save) methode.
7. Een instantie van de klasse Editor verwijderen via de operator 'using' of handmatig.

### Zie ook

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* naamruimte [GroupDocs.Editor](../../groupdocs.editor)
* montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
