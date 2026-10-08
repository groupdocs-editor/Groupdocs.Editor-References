---
title: "EditableDocument"
second_title: "GroupDocs.Editor για .NET αναφορά API"
description: "Ενδιάμεσο έγγραφο που περιέχει περιεχόμενο πριν και μετά την επεξεργασία"
type: docs
weight: 10
url: /el/net/groupdocs.editor/editabledocument/
---
## EditableDocument class

Ενδιάμεσο έγγραφο, που περιέχει περιεχόμενο πριν και μετά την επεξεργασία

```csharp
public sealed class EditableDocument : IAuxDisposable
```

## Properties

| Name | Περιγραφή |
| --- | --- |
| [AllResources](../../groupdocs.editor/editabledocument/allresources) { get; } | Επιστρέφει μια λίστα με όλους τους υπάρχοντες πόρους: όλα τα φύλλα στυλ, εικόνες από το HTML και όλα τα φύλλα στυλ, γραμματοσειρές, ήχο |
| [Audio](../../groupdocs.editor/editabledocument/audio) { get; } | Επιστρέφει μια λίστα με πόρους ήχου |
| [Css](../../groupdocs.editor/editabledocument/css) { get; } | Επιτρέπει την απόκτηση πόρων φύλλων στυλ (CSS) (εξωτερικών και ενσωματωμένων, αλλά όχι inline), που χρησιμοποιούνται από αυτό το έγγραφο HTML |
| [Fonts](../../groupdocs.editor/editabledocument/fonts) { get; } | Επιτρέπει την απόκτηση εξωτερικών πόρων γραμματοσειρών, που χρησιμοποιούνται από αυτό το έγγραφο HTML |
| [Images](../../groupdocs.editor/editabledocument/images) { get; } | Επιτρέπει την απόκτηση εξωτερικών πόρων εικόνας (raster και vector εικόνες), που χρησιμοποιούνται από αυτό το έγγραφο HTML |
| [IsDisposed](../../groupdocs.editor/editabledocument/isdisposed) { get; } | Καθορίζει εάν αυτό το EditableDocument έχει ήδη καταστραφεί (true) ή όχι (false) |

## Methods

| Name | Περιγραφή |
| --- | --- |
| static [FromFile](../../groupdocs.editor/editabledocument/fromfile)(string, string) | Στατική κατασκευή, η οποία δημιουργεί ένα αντικείμενο EditableDocument από ένα αρχείο HTML, το οποίο καθορίζεται από τη διαδρομή προς το ίδιο το αρχείο *.html και έναν φάκελο με συνδεδεμένους πόρους |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup#frommarkup)(string) | Στατική κατασκευή, η οποία δημιουργεί ένα αντικείμενο [`EditableDocument`](../editabledocument) από το καθορισμένο σήμανση HTML |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup#frommarkup_1)(string, IEnumerable&lt;IHtmlResource&gt;) | Στατική κατασκευή, η οποία δημιουργεί ένα αντικείμενο EditableDocument από το καθορισμένο σήμανση HTML και ένα σύνολο αντίστοιχων συνδεδεμένων πόρων |
| static [FromMarkupAndResourceFolder](../../groupdocs.editor/editabledocument/frommarkupandresourcefolder)(string, string) | Στατική κατασκευή, η οποία δημιουργεί ένα αντικείμενο EditableDocument από το καθορισμένο σήμανση HTML και από πόρους, που βρίσκονται στον φάκελο, καθορισμένο με την πλήρη διαδρομή |
| [Dispose](../../groupdocs.editor/editabledocument/dispose)() | Καταστρέφει αυτή την παρουσία EditableDocument, καταστρέφοντας το περιεχόμενό της και καθιστώντας τις μεθόδους και τις ιδιότητές της μη λειτουργικές |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent)() | Επιστρέφει το σώμα του εγγράφου HTML (εσωτερικό περιεχόμενο μεταξύ των ανοίγματος και κλεισίματος ετικετών BODY χωρίς αυτές τις ετικέτες) ως συμβολοσειρά. |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent_1)(string) | Επιστρέφει το σώμα του εγγράφου HTML (εσωτερικό περιεχόμενο μεταξύ των ανοίγματος και κλεισίματος ετικετών BODY χωρίς αυτές τις ετικέτες) ως συμβολοσειρά, όπου οι σύνδεσμοι προς τους εξωτερικούς πόρους περιέχουν το καθορισμένο πρότυπο με σύμβολα κράτησης θέσης. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent)() | Επιστρέφει το συνολικό περιεχόμενο του εγγράφου HTML ως συμβολοσειρά. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent_1)(string, string) | Επιστρέφει το συνολικό περιεχόμενο του εγγράφου HTML ως συμβολοσειρά, όπου οι σύνδεσμοι προς τους εξωτερικούς πόρους περιέχουν το καθορισμένο πρότυπο με σύμβολα κράτησης θέσης. |
| [GetContent&lt;TStream&gt;](../../groupdocs.editor/editabledocument/getcontent#getcontent_2)(TStream, Encoding) | Επιστρέφει το συνολικό περιεχόμενο του εγγράφου HTML ως ροή byte γράφοντας αυτό το περιεχόμενο σε καθορισμένη ροή με το καθορισμένο κωδικοποίηση κειμένου |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent)() | Επιστρέφει το περιεχόμενο όλων των εξωτερικών φύλλων στυλ ως λίστα συμβολοσειρών, όπου μια συμβολοσειρά αντιπροσωπεύει ένα φύλλο στυλ. Επιστρέφει κενή λίστα, εάν δεν υπάρχει CSS για αυτό το έγγραφο. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent_1)(string, string) | Επιστρέφει το περιεχόμενο όλων των εξωτερικών φύλλων στυλ ως λίστα συμβολοσειρών, όπου μια συμβολοσειρά αντιπροσωπεύει ένα φύλλο στυλ. Το καθορισμένο πρόθεμα θα εφαρμοστεί σε κάθε σύνδεσμο προς τον εξωτερικό πόρο σε κάθε παραγόμενο φύλλο στυλ. Επιστρέφει κενή λίστα, εάν δεν υπάρχει CSS για αυτό το έγγραφο. |
| [GetEmbeddedHtml](../../groupdocs.editor/editabledocument/getembeddedhtml)() | Επιστρέφει όλο το περιεχόμενο αυτού του εγγράφου HTML με όλους τους σχετικούς πόρους σε μορφή μιας μόνο συμβολοσειράς, όπου όλοι οι πόροι είναι ενσωματωμένοι μέσα στο σήμανση HTML σε κωδικοποίηση base64. |
| [Save](../../groupdocs.editor/editabledocument/save#save_1)(string) | Αποθηκεύει αυτό το έγγραφο HTML στο αρχείο στην καθορισμένη διαδρομή, όπου θα αποθηκευτεί το σήμανση HTML, και στον συνοδευτικό φάκελο με τους πόρους. |
| [Save](../../groupdocs.editor/editabledocument/save#save_2)(string, string) | Αποθηκεύει αυτό το έγγραφο HTML στο αρχείο στην καθορισμένη διαδρομή, όπου θα αποθηκευτεί το σήμανση HTML, και στον συνοδευτικό φάκελο με τους πόρους, ο οποίος βρίσκεται στην καθορισμένη διαδρομή. |
| [Save](../../groupdocs.editor/editabledocument/save#save)(TextWriter, HtmlSaveOptions) | Αποθηκεύει το περιεχόμενο αυτού του [`EditableDocument`](../editabledocument) ως έγγραφο HTML στον καθορισμένο συγγραφέα κειμένου, ενώ η δεύτερη παράμετρος επιλογών επιτρέπει την προσαρμογή της διαδικασίας αποθήκευσης και τον καθορισμό της κλήσης επιστροφής αποθήκευσης πόρων |

## Συμβάντα

| Name | Περιγραφή |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editabledocument/disposed) | Συμβάν, που συμβαίνει όταν αυτό το Editable document διαγράφεται, αμέσως μετά την ολοκλήρωση της διαδικασίας διαγραφής |

### Σχόλια

Ένα στιγμιότυπο της κλάσης `EditableDocument` μπορεί να παραχθεί από τη μέθοδο '[`Edit`](../editor/edit)' ή να δημιουργηθεί από τον χρήστη χρησιμοποιώντας στατικές εργοστασιακές μεθόδους. Το `EditableDocument` αποθηκεύει εσωτερικά το έγγραφο σε δικό του κλειστό μορφότυπο, ο οποίος είναι συμβατός (μετατρέψιμος) με όλες τις μορφές εισαγωγής και εξαγωγής που υποστηρίζει το GroupDocs.Editor. Προκειμένου το έγγραφο να είναι επεξεργάσιμο σε οποιονδήποτε επεξεργαστή WYSIWYG στην πλευρά του πελάτη (όπως CKEditor ή TinyMCE), το `EditableDocument` παρέχει μεθόδους για τη δημιουργία HTML markup και την παραγωγή πόρων, που μπορούν να γίνουν αποδεκτοί από τον χρήστη.

### Δείτε επίσης

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* namespace [GroupDocs.Editor](../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
