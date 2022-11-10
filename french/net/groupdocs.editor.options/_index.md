---
title: GroupDocs.Editor.Options
second_title: Référence de l'API GroupDocs.Editor pour .NET
description: Lespace de noms GroupDocs.Editor.Options fournit des interfaces pour les options de chargement et denregistrement.
type: docs
weight: 130
url: /fr/net/groupdocs.editor.options/
---
L'espace de noms GroupDocs.Editor.Options fournit des interfaces pour les options de chargement et d'enregistrement.

## Des classes

| Classer | La description |
| --- | --- |
| [Azw3SaveOptions](./azw3saveoptions) | Permet de spécifier des options personnalisées pour générer et enregistrer les livres électroniques AZW3, également connus sous le nom de Kindle Format 8 (KF8) |
| [DelimitedTextEditOptions](./delimitedtexteditoptions) | Options de chargement de documents de feuille de calcul à base de texte (CSV, basés sur des onglets, etc.), qui utilisent un séparateur (délimiteur) |
| [DelimitedTextSaveOptions](./delimitedtextsaveoptions) | Contient des options pour générer et enregistrer des documents de feuille de calcul à base de texte (CSV, basés sur des onglets, etc.), qui utilisent un séparateur (délimiteur) |
| [EbookEditOptions](./ebookeditoptions) | Permet de spécifier et d'ajuster les options personnalisées pour l'édition de documents de livre électronique dans tous les formats pris en charge : ePub, MOBI et AZW3. |
| [EmailEditOptions](./emaileditoptions) | Permet de spécifier des options personnalisées pour l'édition de documents dans les différents formats de courrier électronique (email) |
| [EmailSaveOptions](./emailsaveoptions) | Permet de spécifier des options personnalisées pour générer et enregistrer des documents de courrier électronique (e-mail) |
| [EpubSaveOptions](./epubsaveoptions) | Permet de spécifier des options personnalisées pour générer et enregistrer les documents IDPF EPUB (norme ouverte pour les livres électroniques créés par l'International Digital Publishing Forum) |
| [FixedLayoutEditOptionsBase](./fixedlayouteditoptionsbase) | Classe abstraite de base pour les options de tous les documents de formats à mise en page fixe tels que PDF et XPS |
| [MhtmlSaveOptions](./mhtmlsaveoptions) | Permet de spécifier des options personnalisées pour générer et enregistrer les documents MHTML (encapsulation MIME des documents HTML agrégés) |
| [PdfEditOptions](./pdfeditoptions) | Permet de spécifier des options personnalisées pour l'édition de documents PDF |
| [PdfLoadOptions](./pdfloadoptions) | Contient des options pour charger des documents PDF dans la classe Editor |
| [PdfSaveOptions](./pdfsaveoptions) | Permet de spécifier des options personnalisées pour générer et enregistrer des documents PDF (Portable Document Format) |
| [PresentationEditOptions](./presentationeditoptions) | Permet de spécifier des options personnalisées pour l'édition de documents de tous les formats de présentation pris en charge (compatibles PowerPoint) |
| [PresentationLoadOptions](./presentationloadoptions) | Permet de spécifier des options personnalisées pour le chargement de documents de tous les formats de présentation pris en charge tels que PPT(X), PPTM, PPS(X) etc. |
| [PresentationSaveOptions](./presentationsaveoptions) | Permet de spécifier des options personnalisées pour générer et enregistrer des documents de présentation (compatibles PowerPoint) |
| [SpreadsheetEditOptions](./spreadsheeteditoptions) | Permet de spécifier des options personnalisées pour l'édition de documents de tous les formats de feuille de calcul pris en charge (compatible Excel) |
| [SpreadsheetLoadOptions](./spreadsheetloadoptions) | Contient des options pour charger des documents de tableur binaires (Cellules, compatibles Excel) tels que XLS(X), ODS, etc. dans la classe Editor |
| [SpreadsheetSaveOptions](./spreadsheetsaveoptions) | Permet de spécifier des options personnalisées pour générer et enregistrer des documents de feuille de calcul (conformes à Excel) |
| [TextEditOptions](./texteditoptions) | Permet de spécifier des options personnalisées pour le chargement de documents en texte brut (TXT) |
| [TextSaveOptions](./textsaveoptions) | Permet de spécifier des options personnalisées pour générer et enregistrer des documents en texte brut (TXT) |
| [WordProcessingEditOptions](./wordprocessingeditoptions) | Permet de spécifier des options personnalisées pour l'édition de documents de tous les formats de traitement de texte pris en charge (conformes à Words) tels que DOC(X), RTF, ODT, etc. |
| [WordProcessingLoadOptions](./wordprocessingloadoptions) | Contient des options pour charger des documents WordProcessing (compatibles Word) tels que DOC(X), RTF, ODT, etc. dans la classe Editor |
| [WordProcessingProtection](./wordprocessingprotection) | Encapsule les options de protection de document pour le document WordProcessing, qui est généré à partir de HTML |
| [WordProcessingSaveOptions](./wordprocessingsaveoptions) | Permet de spécifier des options personnalisées pour générer et enregistrer des documents compatibles avec WordProcessing après leur modification |
| [WorksheetProtection](./worksheetprotection) | Encapsule les options de protection de feuille de calcul, qui permettent de protéger une feuille de calcul dans le document de feuille de calcul de sortie contre la modification du type spécifié avec un mot de passe spécifié. |
| [XmlEditOptions](./xmleditoptions) | Permet de spécifier des options personnalisées pour charger des documents XML (eXtensible Markup Language) et les convertir au format HTML |
| [XmlHighlightOptions](./xmlhighlightoptions) | Contient des options permettant de personnaliser la mise en surbrillance XML lors de la conversion XML vers HTML |
| [XpsEditOptions](./xpseditoptions) | Permet de spécifier des options personnalisées pour l'édition (spécifications papier XML) des documents |
| [XpsSaveOptions](./xpssaveoptions) | Permet de spécifier des options personnalisées pour générer et enregistrer des documents XPS (XML Paper Specifications) |
## Ouvrages

| Structure | La description |
| --- | --- |
| [PageRange](./pagerange) | Encapsule une plage de pages, qui peut avoir des limites ouvertes ou fermées. Par défaut, est "entièrement ouvert" - il inclut toutes les pages existantes. La numérotation des pages commence à partir de 1, et non de 0. |
## Interfaces

| Interface | La description |
| --- | --- |
| [IEditOptions](./ieditoptions) | Interface commune pour toutes les options, qui sont responsables des conversions de document en HTML. Ne déclare aucun membre. |
| [ILoadOptions](./iloadoptions) | Interface commune pour toutes les classes d'options, responsable du chargement des documents de différents types de formats |
| [ISaveOptions](./isaveoptions) | Interface pour toutes les options d'enregistrement pour tous les types de documents. Ne déclare aucun membre. |
## Énumération

| Énumération | La description |
| --- | --- |
| [FontEmbeddingOptions](./fontembeddingoptions) | Les options d'incorporation de polices contrôlent les ressources de police à incorporer dans le document de sortie WordProcessing ou PDF |
| [FontExtractionOptions](./fontextractionoptions) | Les options d'extraction de polices contrôlent quelles polices doivent être extraites et d'où |
| [MailMessageOutput](./mailmessageoutput) | Contrôle quelles parties du message électronique doivent être livrées à la sortie processing |
| [PdfCompliance](./pdfcompliance) | Spécifie le niveau de conformité aux normes PDF |
| [TextDirection](./textdirection) | Représente 3 variantes possibles pour traiter la direction du texte dans les documents en texte brut |
| [TextLeadingSpacesOptions](./textleadingspacesoptions) | Contient les options disponibles pour la gestion de l'espace de tête lors de l'ouverture d'un document en texte brut (TXT) |
| [TextTrailingSpacesOptions](./texttrailingspacesoptions) | Contient les options disponibles pour la gestion des espaces de fin lors de l'ouverture d'un document en texte brut (TXT) |
| [WordProcessingProtectionType](./wordprocessingprotectiontype) | Représente tous les types de protection disponibles du document WordProcessing |
| [WorksheetProtectionType](./worksheetprotectiontype) | Représente les types de protection de feuille de calcul (onglet) de feuille de calcul |

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
