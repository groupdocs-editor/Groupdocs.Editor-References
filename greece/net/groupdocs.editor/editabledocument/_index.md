---
title: EditableDocument
second_title: GroupDocs.Editor για Αναφορά API .NET
description: Ενδιάμεσο έγγραφο που περιέχει περιεχόμενο πριν και μετά την επεξεργασία
type: docs
weight: 10
url: /el/net/groupdocs.editor/editabledocument/
---
## EditableDocument class

Ενδιάμεσο έγγραφο, που περιέχει περιεχόμενο πριν και μετά την επεξεργασία

```csharp
public sealed class EditableDocument : IAuxDisposable
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [AllResources](../../groupdocs.editor/editabledocument/allresources) { get; } | Επιστρέφει μια λίστα με όλους τους υπάρχοντες πόρους: όλα τα φύλλα στυλ, εικόνες από HTML και όλα τα φύλλα στυλ, γραμματοσειρές, audio |
| [Audio](../../groupdocs.editor/editabledocument/audio) { get; } | Επιστρέφει μια λίστα πόρων ήχου |
| [Css](../../groupdocs.editor/editabledocument/css) { get; } | Επιστρέφει μια λίστα πόρων CSS |
| [Fonts](../../groupdocs.editor/editabledocument/fonts) { get; } | Επιτρέπει τη λήψη εξωτερικών πόρων γραμματοσειράς, οι οποίοι χρησιμοποιούνται από αυτό το έγγραφο HTML |
| [Images](../../groupdocs.editor/editabledocument/images) { get; } | Επιτρέπει τη λήψη εξωτερικών πόρων εικόνας (εικόνες ράστερ και διανυσματικά), που χρησιμοποιούνται από αυτό το έγγραφο HTML |
| [IsDisposed](../../groupdocs.editor/editabledocument/isdisposed) { get; } | Καθορίζει εάν αυτό το επεξεργάσιμο έγγραφο είχε ήδη διατεθεί (αληθές) ή όχι (ψευδή) |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| static [FromFile](../../groupdocs.editor/editabledocument/fromfile)(string, string) | Στατικό εργοστάσιο, που δημιουργεί μια παρουσία του EditableDocument από ένα αρχείο HTML, που καθορίζεται από μια διαδρομή προς το ίδιο το αρχείο *.html και έναν φάκελο με συνδεδεμένους πόρων |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup)(string, IEnumerable&lt;IHtmlResource&gt;) | Στατικό εργοστάσιο, που δημιουργεί μια παρουσία του EditableDocument από καθορισμένη σήμανση HTML και ένα σύνολο αντίστοιχων συνδεδεμένων πόρων |
| static [FromMarkupAndResourceFolder](../../groupdocs.editor/editabledocument/frommarkupandresourcefolder)(string, string) | Στατικό εργοστάσιο, που δημιουργεί μια παρουσία του EditableDocument από μια καθορισμένη σήμανση HTML και από πόρους, που βρίσκονται στο φάκελο, που καθορίζονται από την πλήρη διαδρομή |
| [Dispose](../../groupdocs.editor/editabledocument/dispose)() | Απορρίπτει αυτήν την επεξεργάσιμη παρουσία εγγράφου, απορρίπτοντας το περιεχόμενό της και καθιστώντας τις μεθόδους και τις ιδιότητές του μη λειτουργικές |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent)() | Επιστρέφει ένα σώμα του εγγράφου HTML (εσωτερικό περιεχόμενο μεταξύ ανοίγματος και κλεισίματος ετικετών BODY χωρίς αυτές τις ετικέτες) ως συμβολοσειρά. |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent_1)(string) | Επιστρέφει ένα σώμα του εγγράφου HTML (εσωτερικό περιεχόμενο μεταξύ ανοίγματος και κλεισίματος ετικετών BODY χωρίς αυτές τις ετικέτες) ως συμβολοσειρά, όπου οι σύνδεσμοι προς τους εξωτερικούς πόρους περιέχουν καθορισμένο πρόθεμα. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent)() | Επιστρέφει το συνολικό περιεχόμενο του εγγράφου HTML ως συμβολοσειρά. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent_1)(string, string) | Επιστρέφει το συνολικό περιεχόμενο του εγγράφου HTML ως συμβολοσειρά, όπου οι σύνδεσμοι προς τους εξωτερικούς πόρους περιέχουν καθορισμένο πρόθεμα. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent)() | Επιστρέφει το περιεχόμενο όλων των εξωτερικών φύλλων στυλ ως λίστα συμβολοσειρών, όπου μια συμβολοσειρά αντιπροσωπεύει ένα φύλλο στυλ. Επιστρέφει κενή λίστα, εάν δεν υπάρχει CSS για αυτό το έγγραφο. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent_1)(string, string) | Επιστρέφει το περιεχόμενο όλων των εξωτερικών φύλλων στυλ ως λίστα συμβολοσειρών, όπου μια συμβολοσειρά αντιπροσωπεύει ένα φύλλο στυλ. Το καθορισμένο πρόθεμα θα εφαρμόζεται σε κάθε σύνδεσμο προς τον εξωτερικό πόρο σε κάθε φύλλο στυλ που προκύπτει. Επιστρέφει κενή λίστα, εάν δεν υπάρχει CSS για αυτό έγγραφο. |
| [GetEmbeddedHtml](../../groupdocs.editor/editabledocument/getembeddedhtml)() | Επιστρέφει όλο το περιεχόμενο αυτού του εγγράφου HTML με όλους τους σχετικούς πόρους σε μια μορφή μιας συμβολοσειράς, όπου όλοι οι πόροι είναι ενσωματωμένοι μέσα στη σήμανση HTML σε μια κωδικοποιημένη μορφή βάσης64. |
| [Save](../../groupdocs.editor/editabledocument/save#save)(string) | Αποθηκεύει αυτό το έγγραφο HTML στο αρχείο σε καθορισμένη διαδρομή, όπου θα αποθηκευτεί η σήμανση HTML, και στον συνοδευτικό φάκελο με πόρους. |
| [Save](../../groupdocs.editor/editabledocument/save#save_1)(string, string) | Αποθηκεύει αυτό το έγγραφο HTML στο αρχείο σε καθορισμένη διαδρομή, όπου θα αποθηκευτεί η σήμανση HTML, και στον συνοδευτικό φάκελο με πόρους, που βρίσκεται σε καθορισμένη διαδρομή. |

## Εκδηλώσεις

| Ονομα | Περιγραφή |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editabledocument/disposed) | Συμβάν, το οποίο συμβαίνει όταν αυτό το επεξεργάσιμο έγγραφο απορρίπτεται, αμέσως μετά την ολοκλήρωση της διαδικασίας απόρριψης |

### Παρατηρήσεις

Η παρουσία της κλάσης EditableDocument μπορεί να παραχθεί από το "[`Edit`](../editor/edit) μέθοδο ή δημιουργήθηκε από τον ίδιο τον χρήστη χρησιμοποιώντας στατικά εργοστάσια. Το EditableDocument αποθηκεύει εσωτερικά το έγγραφο στη δική του κλειστή μορφή, η οποία είναι συμβατή (μετατρέψιμη) με όλες τις μορφές εισαγωγής και εξαγωγής, που υποστηρίζει το GroupDocs.Editor. Προκειμένου να καταστεί το έγγραφο επεξεργάσιμο σε οποιοδήποτε πρόγραμμα-πελάτη WYSIWYG (όπως το CKEditor ή το TinyMCE), το EditableDocument παρέχει μεθόδους για τη δημιουργία σήμανσης HTML και την παραγωγή πόρων, που μπορούν να γίνουν αποδεκτοί από τον χρήστη.

### Δείτε επίσης

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* χώρος ονομάτων [GroupDocs.Editor](../../groupdocs.editor)
* συνέλευση [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
