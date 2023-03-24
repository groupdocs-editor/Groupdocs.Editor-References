---
title: Editor
second_title: GroupDocs.Editor για Αναφορά API .NET
description: Κύρια κλάση η οποία ενσωματώνει μεθόδους μετατροπής. Η κλάση Editor παρέχει μεθόδους για τη φόρτωση την επεξεργασία και την αποθήκευση εγγράφων όλων των υποστηριζόμενων μορφών. Είναι μίας χρήσης γι αυτό χρησιμοποιήστε μια οδηγία χρήσης ή διαθέστε τους πόρους της με μη αυτόματο τρόπο μέσω της κλήσης της μεθόδου Dispose. Η φόρτωση εγγράφων πραγματοποιείται μέσω κατασκευαστών. Επεξεργασία εγγράφου  μέσω της μεθόδου Επεξεργασία και αποθήκευση πίσω στο έγγραφο που προκύπτει μετά την επεξεργασία  μέσω της μεθόδου Αποθήκευση.
type: docs
weight: 20
url: /el/net/groupdocs.editor/editor/
---
## Editor class

Κύρια κλάση, η οποία ενσωματώνει μεθόδους μετατροπής. Η κλάση Editor παρέχει μεθόδους για τη φόρτωση, την επεξεργασία και την αποθήκευση εγγράφων όλων των υποστηριζόμενων μορφών. Είναι μίας χρήσης, γι' αυτό χρησιμοποιήστε μια οδηγία 'χρήσης' ή διαθέστε τους πόρους της με μη αυτόματο τρόπο μέσω της κλήσης της μεθόδου 'Dispose()'. Η φόρτωση εγγράφων πραγματοποιείται μέσω κατασκευαστών. Επεξεργασία εγγράφου - μέσω της μεθόδου "Επεξεργασία" και αποθήκευση πίσω στο έγγραφο που προκύπτει μετά την επεξεργασία - μέσω της μεθόδου "Αποθήκευση".

```csharp
public sealed class Editor : IAuxDisposable
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [Editor](editor#constructor)(Func&lt;Stream&gt;) | Αρχικοποιεί νέα παρουσία του Editor με καθορισμένο έγγραφο εισόδου (ως ροή) |
| [Editor](editor#constructor_2)(string) | Αρχικοποιεί νέα παρουσία του Editor με καθορισμένο έγγραφο εισόδου (ως πλήρη διαδρομή αρχείου) |
| [Editor](editor#constructor_1)(Func&lt;Stream&gt;, Func&lt;ILoadOptions&gt;) | Αρχικοποιεί νέα παρουσία του Editor με καθορισμένο έγγραφο εισόδου (ως ροή) με τις επιλογές φόρτωσης |
| [Editor](editor#constructor_3)(string, Func&lt;ILoadOptions&gt;) | Αρχικοποιεί νέα παρουσία του Editor με καθορισμένο έγγραφο εισόδου (ως πλήρη διαδρομή αρχείου) με τις επιλογές φόρτωσης |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [IsDisposed](../../groupdocs.editor/editor/isdisposed) { get; } | Υποδεικνύει εάν αυτή η παρουσία του προγράμματος επεξεργασίας είχε ήδη απορριφθεί και δεν μπορεί να χρησιμοποιηθεί πλέον (true) ή δεν είχε απορριφθεί ακόμα και επομένως είναι ενεργή (false) |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [Dispose](../../groupdocs.editor/editor/dispose)() | Απορρίπτει αυτήν την παρουσία του Editor, έτσι ώστε να απελευθερώνει όλους τους εσωτερικούς πόρους και να μην είναι διαθέσιμος για περαιτέρω χρήση |
| [Edit](../../groupdocs.editor/editor/edit#edit)() | Ανοίγει ένα έγγραφο που έχει φορτωθεί προηγουμένως για επεξεργασία χρησιμοποιώντας τις προεπιλεγμένες επιλογές, δημιουργώντας και επιστρέφοντας μια παρουσία του '[`EditableDocument`](../editabledocument) κλάση, η οποία, με τη σειρά της, περιέχει μεθόδους για την παραγωγή σήμανσης HTML και σχετικούς πόρους. |
| [Edit](../../groupdocs.editor/editor/edit#edit_1)(IEditOptions) | Ανοίγει ένα έγγραφο που έχει φορτωθεί προηγουμένως για επεξεργασία χρησιμοποιώντας συγκεκριμένες επιλογές για συγκεκριμένη μορφή, δημιουργώντας και επιστρέφοντας μια παρουσία του '[`EditableDocument`](../editabledocument) κλάση, η οποία, με τη σειρά της, περιέχει μεθόδους για την παραγωγή σήμανσης HTML και σχετικούς πόρους. |
| [GetDocumentInfo](../../groupdocs.editor/editor/getdocumentinfo)(string) | Επιστρέφει μεταδεδομένα σχετικά με το έγγραφο, που φορτώθηκε σε αυτό το "Editor" instance |
| [Save](../../groupdocs.editor/editor/save#save)(EditableDocument, Stream, ISaveOptions) | Μετατρέπει το καθορισμένο επεξεργασμένο έγγραφο, που αναπαρίσταται ως παράδειγμα του '[`EditableDocument`](../editabledocument) , στο έγγραφο που προκύπτει με καθορισμένη μορφή και αποθηκεύει το περιεχόμενό του σε καθορισμένη ροή |
| [Save](../../groupdocs.editor/editor/save#save_1)(EditableDocument, string, ISaveOptions) | Μετατρέπει το καθορισμένο επεξεργασμένο έγγραφο, που αναπαρίσταται ως παράδειγμα του '[`EditableDocument`](../editabledocument) , στο προκύπτον έγγραφο καθορισμένης μορφής και αποθηκεύει το περιεχόμενό του σε αρχείο κατά καθορισμένο αρχείο path |

## Εκδηλώσεις

| Ονομα | Περιγραφή |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editor/disposed) | Συμβάν, το οποίο συμβαίνει όταν αυτό το στιγμιότυπο του Editor απορρίπτεται με όλους τους εσωτερικούς του πόρους |

### Παρατηρήσεις

Η κλάση Editor πρέπει να θεωρείται ως σημείο εισόδου και το ριζικό αντικείμενο του GroupDocs.Editor. Όλες οι λειτουργίες εκτελούνται χρησιμοποιώντας αυτήν την κλάση. Η τυπική χρήση της κλάσης Editor για την εκτέλεση πλήρους διοχέτευσης επεξεργασίας εγγράφων είναι η εξής:

1. Φορτώστε ένα έγγραφο στην παρουσία του Editor μέσω του κατασκευαστή του.
2. Προαιρετικά, εντοπίστε έναν τύπο εγγράφου χρησιμοποιώντας ένα[`GetDocumentInfo`](./getdocumentinfo) μέθοδος.
3. Ανοίξτε ένα έγγραφο για επεξεργασία καλώντας ένα[`Edit`](./edit)μέθοδο και λήψη ενός στιγμιότυπου του[`EditableDocument`](../editabledocument) τάξη από αυτό.
4. Επεξεργασία περιεχομένου εγγράφου στην πλευρά του πελάτη χρησιμοποιώντας οποιοδήποτε πρόγραμμα επεξεργασίας HTML WYSIWYG.
5. Δημιουργία νέας παρουσίας του[`EditableDocument`](../editabledocument) από το περιεχόμενο του επεξεργασμένου εγγράφου.
6. Αποθήκευση ενός επεξεργασμένου εγγράφου σε κάποια μορφή εξόδου καλώντας a[`Save`](./save) μέθοδος.
7. Απόρριψη μιας παρουσίας της κλάσης Editor μέσω του τελεστή 'using' ή χειροκίνητα.

### Δείτε επίσης

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* χώρος ονομάτων [GroupDocs.Editor](../../groupdocs.editor)
* συνέλευση [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->