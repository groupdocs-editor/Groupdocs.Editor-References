---
title: "GroupDocs.Editor.Options"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "L’espace de noms GroupDocs.Editor.Options fournit des interfaces pour les options de chargement et d’enregistrement."
type: docs
weight: 160
url: /fr/net/groupdocs.editor.options/
---
L’espace de noms GroupDocs.Editor.Options fournit des interfaces pour les options de chargement et d’enregistrement.

## Classes

| Classe | Description |
| --- | --- |
| [DelimitedTextEditOptions](./delimitedtexteditoptions) | Options pour charger des documents de feuille de calcul basés sur du texte (CSV, Tab-based etc.), qui utilisent un séparateur (delimiter) |
| [DelimitedTextSaveOptions](./delimitedtextsaveoptions) | Contient des options pour générer et enregistrer des documents de feuille de calcul basés sur du texte (CSV, Tab-based etc.), qui utilisent un séparateur (delimiter) |
| [EbookEditOptions](./ebookeditoptions) | Permet de spécifier et d’ajuster des options personnalisées pour l’édition de documents de livre électronique dans tous les formats pris en charge : ePub, MOBI et AZW3. |
| [EbookSaveOptions](./ebooksaveoptions) | Permet de spécifier des options personnalisées pour générer et enregistrer le document dans tous les formats de livre électronique pris en charge : ePub, MOBI et AZW3. |
| [EmailEditOptions](./emaileditoptions) | Permet de spécifier des options personnalisées pour l’édition de documents dans les différents formats de courrier électronique (email) |
| [EmailSaveOptions](./emailsaveoptions) | Permet de spécifier des options personnalisées pour générer et enregistrer des documents de courrier électronique (email) |
| [FixedLayoutEditOptionsBase](./fixedlayouteditoptionsbase) | Classe abstraite de base pour les options de tous les documents aux formats à mise en page fixe comme PDF et XPS |
| [HtmlSaveOptions](./htmlsaveoptions) | Permet de spécifier des options personnalisées pour enregistrer l’instance [`EditableDocument`](../groupdocs.editor/editabledocument) au format HTML |
| [MarkdownEditOptions](./markdowneditoptions) | Permet de spécifier des options personnalisées pour l’édition de documents au format Markdown (MD) |
| [MarkdownImageLoadArgs](./markdownimageloadargs) | Fournit des données pour l’événement ProcessImage. |
| [MarkdownSaveOptions](./markdownsaveoptions) | Permet de spécifier des options personnalisées pour générer et enregistrer des documents Markdown |
| [MhtmlSaveOptions](./mhtmlsaveoptions) | Permet de spécifier des options personnalisées pour générer et enregistrer les documents MHTML (MIME encapsulation of aggregate HTML documents) |
| [PdfEditOptions](./pdfeditoptions) | Permet de spécifier des options personnalisées pour l’édition de documents PDF |
| [PdfLoadOptions](./pdfloadoptions) | Contient des options pour charger des documents PDF dans la classe Editor |
| [PdfSaveOptions](./pdfsaveoptions) | Permet de spécifier des options personnalisées pour générer et enregistrer des documents PDF (Portable Document Format) |
| [PresentationEditOptions](./presentationeditoptions) | Permet de spécifier des options personnalisées pour l’édition de documents de tous les formats de présentation (PowerPoint-compatible) pris en charge |
| [PresentationLoadOptions](./presentationloadoptions) | Permet de spécifier des options personnalisées pour charger des documents de tous les formats de présentation pris en charge comme PPT(X), PPTM, PPS(X) etc. |
| [PresentationSaveOptions](./presentationsaveoptions) | Permet de spécifier des options personnalisées pour générer et enregistrer des documents de présentation (PowerPoint-compatible) |
| [SpreadsheetEditOptions](./spreadsheeteditoptions) | Permet de spécifier des options personnalisées pour l’édition de documents de tous les formats de feuille de calcul (Excel-compatible) pris en charge |
| [SpreadsheetLoadOptions](./spreadsheetloadoptions) | Contient des options pour charger des documents de feuille de calcul binaires (Cells, Excel-compatible) comme XLS(X), ODS etc. dans la classe Editor |
| [SpreadsheetSaveOptions](./spreadsheetsaveoptions) | Permet de spécifier des options personnalisées pour générer et enregistrer des documents de feuille de calcul (Excel-compliant) |
| [TextEditOptions](./texteditoptions) | Permet de spécifier des options personnalisées pour charger des documents texte brut (TXT) |
| [TextSaveOptions](./textsaveoptions) | Permet de spécifier des options personnalisées pour générer et enregistrer des documents texte brut (TXT) |
| [WebFont](./webfont) | Représente des paramètres de police pour le Web |
| [WordProcessingEditOptions](./wordprocessingeditoptions) | Permet de spécifier des options personnalisées pour l'édition de documents de tous les formats WordProcessing (conformes à Words) pris en charge, tels que DOC(X), RTF, ODT, etc. |
| [WordProcessingLoadOptions](./wordprocessingloadoptions) | Contient des options pour charger des documents WordProcessing (compatibles Word) comme DOC(X), RTF, ODT, etc. dans la classe Editor |
| [WordProcessingProtection](./wordprocessingprotection) | Encapsule les options de protection du document WordProcessing, qui est généré à partir du HTML |
| [WordProcessingSaveOptions](./wordprocessingsaveoptions) | Permet de spécifier des options personnalisées pour générer et enregistrer des documents conformes à WordProcessing après leur édition |
| [WorksheetProtection](./worksheetprotection) | Encapsule les options de protection de la feuille de calcul, qui permettent de protéger une feuille de calcul dans le document Spreadsheet de sortie contre toute modification d'un type spécifié avec un mot de passe donné. |
| [XmlEditOptions](./xmleditoptions) | Permet de spécifier des options personnalisées pour l'édition de documents XML (eXtensible Markup Language) et leur conversion en HTML |
| [XmlFormatOptions](./xmlformatoptions) | Contient des options qui permettent d'ajuster le formatage du document XML lorsqu'il est représenté en HTML |
| [XmlHighlightOptions](./xmlhighlightoptions) | Contient des options qui permettent de personnaliser la mise en évidence du XML lors de la conversion XML vers HTML |
| [XpsSaveOptions](./xpssaveoptions) | Permet de spécifier des options personnalisées pour générer et enregistrer des documents XPS (XML Paper Specifications) |
## Structures

| Structure | Description |
| --- | --- |
| [PageRange](./pagerange) | Encapsule une plage de pages, qui peut avoir des limites ouvertes ou fermées. Par défaut, elle est « entièrement ouverte » – elle inclut toutes les pages existantes. La numérotation des pages commence à 1, pas à 0. |
## Interfaces

| Interface | Description |
| --- | --- |
| [IEditOptions](./ieditoptions) | Interface commune pour toutes les options responsables des conversions document-vers-HTML. Ne déclare aucun membre. |
| [IHtmlSavingCallback](./ihtmlsavingcallback) | Interface utilisée lors de l'enregistrement du  au format HTML et qui doit être implémentée par l'utilisateur final afin d'enregistrer la ressource fournie et de renvoyer un lien vers celle‑ci |
| [ILoadOptions](./iloadoptions) | Interface commune pour toutes les classes d'options, responsable du chargement de documents de différents formats de type |
| [IMarkdownImageLoadCallback](./imarkdownimageloadcallback) | Implémentez cette interface si vous souhaitez contrôler la façon dont GroupDocs.Editor charge les images lors du chargement du fichier au format Markdown |
| [ISaveOptions](./isaveoptions) | Interface pour toutes les options d'enregistrement de tous les types de documents. Ne déclare aucun membre. |
## Énumération

| Énumération | Description |
| --- | --- |
| [FontEmbeddingOptions](./fontembeddingoptions) | Les options d'incorporation de police contrôlent quelles ressources de police doivent être intégrées dans le document WordProcessing ou PDF de sortie |
| [FontExtractionOptions](./fontextractionoptions) | Les options d'extraction de police contrôlent quelles polices doivent être extraites et d'où |
| [MailMessageOutput](./mailmessageoutput) | Contrôle quelles parties du message électronique doivent être transmises au traitement de sortie |
| [MarkdownImageLoadingAction](./markdownimageloadingaction) | Définit le mode de chargement des images lors de l'ouverture du fichier au format Markdown pour l'édition |
| [MarkdownTableContentAlignment](./markdowntablecontentalignment) | Permet de spécifier l'alignement du contenu du tableau à utiliser lors de l'exportation au format Markdown |
| [PdfCompliance](./pdfcompliance) | Spécifie le niveau de conformité aux normes PDF |
| [TextDirection](./textdirection) | Représente 3 variantes possibles pour traiter la direction du texte dans les documents texte brut |
| [TextLeadingSpacesOptions](./textleadingspacesoptions) | Contient les options disponibles pour la gestion des espaces en début de ligne lors de l'ouverture d'un document texte brut (TXT) |
| [TextTrailingSpacesOptions](./texttrailingspacesoptions) | Contient les options disponibles pour la gestion des espaces en fin de ligne lors de l'ouverture d'un document texte brut (TXT) |
| [WordProcessingProtectionType](./wordprocessingprotectiontype) | Représente tous les types de protection disponibles du document WordProcessing |
| [WorksheetProtectionType](./worksheetprotectiontype) | Représente les types de protection des feuilles de calcul (onglet) Spreadsheet |

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
