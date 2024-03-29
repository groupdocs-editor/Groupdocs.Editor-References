---
title: FontResourceBase
second_title: GroupDocs.Editor για Αναφορά API .NET
description: Βασική κλάση για οποιονδήποτε υποστηριζόμενο τύπο γραμματοσειράς ως πόρος για το έγγραφο HTML με όλες τις ιδιότητες του
type: docs
weight: 370
url: /el/net/groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/
---
## FontResourceBase class

Βασική κλάση για οποιονδήποτε υποστηριζόμενο τύπο γραμματοσειράς ως πόρος για το έγγραφο HTML με όλες τις ιδιότητες του

```csharp
public abstract class FontResourceBase : IEquatable<FontResourceBase>, IHtmlResource
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/bytecontent) { get; } | Επιστρέφει το περιεχόμενο αυτής της γραμματοσειράς ως byte stream |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/filenamewithextension) { get; } | Επιστρέφει το σωστό όνομα αρχείου αυτού του πόρου γραμματοσειράς, το οποίο αποτελείται από όνομα και επέκταση. Θεωρητικά μπορεί να διαφέρει από το όνομα. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/isdisposed) { get; } | Καθορίζει εάν αυτή η γραμματοσειρά είναι απορρίπτεται ή όχι |
| [Name](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/name) { get; } | Επιστρέφει το όνομα αυτού του πόρου γραμματοσειράς. Συνήθως δεν περιέχει επέκταση ονόματος αρχείου και θεωρητικά μπορεί να διαφέρει από το όνομα αρχείου. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/textcontent) { get; } | Επιστρέφει το περιεχόμενο αυτής της γραμματοσειράς ως συμβολοσειρά με κωδικοποίηση base64. Αυτή η τιμή αποθηκεύεται στην κρυφή μνήμη μετά την πρώτη κλήση. |
| abstract [Type](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/type) { get; } | Κατά την υλοποίηση του τύπου θα πρέπει να επιστρέψει πληροφορίες σχετικά με τον τύπο συγκεκριμένης γραμματοσειράς resource ως μια παρουσία συγκεκριμένου τύπου FontType, ο οποίος ενσωματώνει όλες τις info |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/dispose)() | Απορρίπτει αυτόν τον πόρο γραμματοσειράς, απορρίπτοντας το περιεχόμενό του και καθιστώντας τις περισσότερες μεθόδους και ιδιότητες μη λειτουργικές |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals#equals)(FontResourceBase) | Ελέγχει αυτήν την παρουσία με καθορισμένο πόρο γραμματοσειράς στην αναφορά equality |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals#equals_1)(IHtmlResource) | Ελέγχει αυτήν την παρουσία με καθορισμένο πόρο HTML στην αναφορά equality |
| [Save](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/save)(string) | Αποθηκεύει αυτήν τη γραμματοσειρά στο καθορισμένο αρχείο |

## Εκδηλώσεις

| Ονομα | Περιγραφή |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/disposed) | Συμβάν, το οποίο συμβαίνει όταν αυτή η γραμματοσειρά είναι disposed |

### Δείτε επίσης

* interface [IHtmlResource](../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* χώρος ονομάτων [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* συνέλευση [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
