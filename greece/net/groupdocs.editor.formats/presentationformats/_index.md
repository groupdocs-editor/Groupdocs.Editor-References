---
title: "PresentationFormats"
second_title: "GroupDocs.Editor για .NET αναφορά API"
description: "Περιλαμβάνει όλες τις μορφές Παρουσίασης. Συμπεριλαμβάνει τις ακόλουθες μορφές"
type: docs
weight: 120
url: /el/net/groupdocs.editor.formats/presentationformats/
---
## PresentationFormats class

Περιλαμβάνει όλες τις μορφές Παρουσίασης. Συμπεριλαμβάνει τις ακόλουθες μορφές:

* [`Odp`](./odp)
* [`Otp`](./otp)
* [`Pot`](./pot)
* [`Potm`](./potm)
* [`Potx`](./potx)
* [`Pps`](./pps)
* [`Ppsm`](./ppsm)
* [`Ppsx`](./ppsx)
* [`Ppt`](./ppt)
* [`Ppt95`](./ppt95)
* [`Pptm`](./pptm)
* [`Pptx`](./pptx)

Μάθετε περισσότερα για τις μορφές Παρουσίασης [εδώ](https://wiki.fileformat.com/presentation).

```csharp
public class PresentationFormats : DocumentFormatBase
```

## Properties

| Name | Περιγραφή |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Λαμβάνει την επέκταση αρχείου της μορφής εγγράφου. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Λαμβάνει την οικογένεια μορφής στην οποία ανήκει η μορφή εγγράφου. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Λαμβάνει το μοναδικό αναγνωριστικό για την οικογένεια μορφής. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Λαμβάνει τον τύπο MIME της μορφής εγγράφου. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Λαμβάνει το όνομα της οικογένειας μορφής. |
| static [All](../../groupdocs.editor.formats/presentationformats/all) { get; } | Λαμβάνει μια συλλογή με δυνατότητα επανάληψης όλων των [`PresentationFormats`](../presentationformats). |

## Methods

| Name | Περιγραφή |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/presentationformats/fromextension)(string) | Ανακτά ένα στιγμιότυπο του καθορισμένου τύπου [`PresentationFormats`](../presentationformats) που έχει την καθορισμένη επέκταση αρχείου. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Καθορίζει εάν αυτό το παράδειγμα είναι ίσο με το καθορισμένο παράδειγμα [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Καθορίζει εάν αυτό το παράδειγμα είναι ίσο με το καθορισμένο παράδειγμα [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Καθορίζει εάν αυτό το παράδειγμα είναι ίσο με το καθορισμένο παράδειγμα [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Επιστρέφει έναν κωδικό κατακερματισμού για το τρέχον αντικείμενο. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο. |
| [explicit operator](../../groupdocs.editor.formats/presentationformats/op_explicit) | Μετατρέπει μια συμβολοσειρά που αντιπροσωπεύει επέκταση αρχείου σε αντικείμενο [`PresentationFormats`](../presentationformats). |

## Πεδία

| Name | Περιγραφή |
| --- | --- |
| static readonly [Odp](../../groupdocs.editor.formats/presentationformats/odp) | OpenDocument Presentation (ODP). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/presentation/odp). |
| static readonly [Otp](../../groupdocs.editor.formats/presentationformats/otp) | OpenDocument Presentation template (OTP). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/presentation/otp). |
| static readonly [Pot](../../groupdocs.editor.formats/presentationformats/pot) | Microsoft PowerPoint 97-2003 Presentation Template (POT). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/presentation/pot). |
| static readonly [Potm](../../groupdocs.editor.formats/presentationformats/potm) | Microsoft Office Open XML PresentationML Macro-Enabled Template (POTM). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/presentation/potm). |
| static readonly [Potx](../../groupdocs.editor.formats/presentationformats/potx) | Microsoft Office Open XML PresentationML Macro-Free Template (POTX). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/presentation/potx). |
| static readonly [Pps](../../groupdocs.editor.formats/presentationformats/pps) | Microsoft PowerPoint 97-2003 SlideShow (PPS). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/presentation/pps). |
| static readonly [Ppsm](../../groupdocs.editor.formats/presentationformats/ppsm) | Microsoft Office Open XML PresentationML Macro-Enabled SlideShow (PPSM). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/presentation/ppsm). |
| static readonly [Ppsx](../../groupdocs.editor.formats/presentationformats/ppsx) | Microsoft Office Open XML PresentationML Macro-Free SlideShow (PPSX). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/presentation/ppsx). |
| static readonly [Ppt](../../groupdocs.editor.formats/presentationformats/ppt) | Microsoft PowerPoint 97-2003 Presentation (PPT). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/presentation/ppt). |
| static readonly [Ppt95](../../groupdocs.editor.formats/presentationformats/ppt95) | Παρουσίαση Microsoft PowerPoint 95 (PPT). |
| static readonly [Pptm](../../groupdocs.editor.formats/presentationformats/pptm) | Έγγραφο Microsoft Office Open XML PresentationML με ενεργοποιημένα μακροεντολές (PPTM). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/presentation/pptm). |
| static readonly [Pptx](../../groupdocs.editor.formats/presentationformats/pptx) | Έγγραφο Microsoft Office Open XML PresentationML χωρίς μακροεντολές (PPTX). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/presentation/pptx). |

### Δείτε επίσης

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
