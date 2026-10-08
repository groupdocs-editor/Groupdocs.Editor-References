---
title: "WordProcessingSaveOptions"
second_title: "GroupDocs.Editor για .NET αναφορά API"
description: "Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για τη δημιουργία και αποθήκευση WordProcessingcompliant εγγράφων μετά την επεξεργασία τους"
type: docs
weight: 1240
url: /el/net/groupdocs.editor.options/wordprocessingsaveoptions/
---
## WordProcessingSaveOptions class

Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για τη δημιουργία και αποθήκευση εγγράφων συμβατών με Επεξεργασία Κειμένου μετά την επεξεργασία τους

```csharp
public sealed class WordProcessingSaveOptions : ICloneable, ISaveOptions
```

## Constructors

| Name | Περιγραφή |
| --- | --- |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor)() | Αυτός ο κατασκευαστής χωρίς παραμέτρους δημιουργεί ένα νέο αντικείμενο της κλάσης WordProcessingSaveOptions με μορφή εξόδου DOCX (μπορεί να τροποποιηθεί στη συνέχεια μέσω της ιδιότητας [`OutputFormat`](./outputformat)) |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor_1)(WordProcessingFormats) | Δημιουργεί ένα νέο αντικείμενο της κλάσης WordProcessingSaveOptions με καθορισμένη υποχρεωτική μορφή εξόδου WordProcessing, ενώ όλες οι άλλες παράμετροι είναι προεπιλεγμένες |

## Properties

| Name | Περιγραφή |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/wordprocessingsaveoptions/enablepagination) { get; set; } | Επιτρέπει την ενεργοποίηση ή απενεργοποίηση της σελιδοποίησης που θα χρησιμοποιηθεί για την αποθήκευση του εγγράφου WordProcessing. Εάν το αρχικό έγγραφο ανοίχθηκε και επεξεργάστηκε σε λειτουργία σελιδοποίησης, αυτή η επιλογή πρέπει επίσης να ενεργοποιηθεί. Προεπιλεγμένα είναι απενεργοποιημένη. |
| [FontEmbedding](../../groupdocs.editor.options/wordprocessingsaveoptions/fontembedding) { get; set; } | Υπεύθυνο για την ενσωμάτωση πόρων γραμματοσειρών στο έξοδο του εγγράφου WordProcessing. Προεπιλεγμένα δεν ενσωματώνει καμία γραμματοσειρά (NotEmbed). |
| [Locale](../../groupdocs.editor.options/wordprocessingsaveoptions/locale) { get; set; } | Επιτρέπει τον καθορισμό παράκαμψης της προεπιλεγμένης τοπικής ρύθμισης (γλώσσας) για το έγγραφο WordProcessing, η οποία θα εφαρμοστεί κατά τη δημιουργία του. Εάν δεν καθοριστεί (προεπιλεγμένη τιμή), το MS Word (ή άλλο πρόγραμμα) θα εντοπίσει (ή θα επιλέξει) τη τοπική ρύθμιση του εγγράφου σύμφωνα με τις δικές του ρυθμίσεις ή άλλους παράγοντες. |
| [LocaleBi](../../groupdocs.editor.options/wordprocessingsaveoptions/localebi) { get; set; } | Επιτρέπει τον καθορισμό παράκαμψης της τοπικής ρύθμισης (γλώσσας) για το κείμενο RTL (από δεξιά προς αριστερά), η οποία θα εφαρμοστεί κατά τη δημιουργία του. Εάν δεν καθοριστεί (προεπιλεγμένη τιμή), το MS Word (ή άλλο πρόγραμμα) θα εντοπίσει (ή θα επιλέξει) τη RTL τοπική ρύθμιση του εγγράφου σύμφωνα με τις δικές του ρυθμίσεις ή άλλους παράγοντες. |
| [LocaleFarEast](../../groupdocs.editor.options/wordprocessingsaveoptions/localefareast) { get; set; } | Επιτρέπει την παράκαμψη της τοπικής ρύθμισης (γλώσσας) για το έγγραφο WordProcessing σχετικά με το κείμενο Ανατολικής Ασίας, η οποία θα εφαρμοστεί κατά τη δημιουργία του. Εάν δεν καθοριστεί (προεπιλεγμένη τιμή), το MS Word (ή άλλο πρόγραμμα) θα εντοπίσει (ή θα επιλέξει) τη τοπική ρύθμιση Ανατολικής Ασίας του εγγράφου σύμφωνα με τις δικές του ρυθμίσεις ή άλλους παράγοντες. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/wordprocessingsaveoptions/optimizememoryusage) { get; set; } | Ενεργοποιεί μηχανισμούς βελτιστοποίησης μνήμης κατά τη δημιουργία εγγράφων από HTML, κάτι που μειώνει την απόδοση ως κόστος μείωσης της χρήσης μνήμης. Ορισμός αυτής της επιλογής σε true μπορεί να μειώσει σημαντικά την κατανάλωση μνήμης κατά τη δημιουργία μεγάλων εγγράφων, με το κόστος του πιο αργού χρόνου αποθήκευσης. Η προεπιλογή είναι false (η βελτιστοποίηση μνήμης είναι απενεργοποιημένη για καλύτερη απόδοση). |
| [OutputFormat](../../groupdocs.editor.options/wordprocessingsaveoptions/outputformat) { get; set; } | Επιτρέπει τον καθορισμό μιας μορφής WordProcessing, η οποία θα χρησιμοποιηθεί για την αποθήκευση του εγγράφου |
| [Password](../../groupdocs.editor.options/wordprocessingsaveoptions/password) { get; set; } | Επιτρέπει τον καθορισμό, την τροποποίηση, την απόκτηση ή την αφαίρεση ενός κωδικού πρόσβασης, ο οποίος θα χρησιμοποιηθεί για την κωδικοποίηση του παραγόμενου εγγράφου WordProcessing. Καθορίστε NULL ή κενή συμβολοσειρά για την αφαίρεση (καθαρισμό) του κωδικού. |
| [Protection](../../groupdocs.editor.options/wordprocessingsaveoptions/protection) { get; set; } | Επιτρέπει τον έλεγχο και την εφαρμογή των επιλογών προστασίας εγγράφου για το έγγραφο WordProcessing οποιασδήποτε μορφής, η οποία υποστηρίζει προστασία εγγράφου. Προεπιλεγμένα είναι NULL - η προστασία εγγράφου δεν θα χρησιμοποιηθεί. |

## Methods

| Name | Περιγραφή |
| --- | --- |
| [Clone](../../groupdocs.editor.options/wordprocessingsaveoptions/clone)() | Δημιουργεί και επιστρέφει ένα πλήρες αντίγραφο αυτής της παρουσίας της κλάσης WordProcessingSaveOptions |

### Σχόλια

Το WordProcessingSaveOptions εφαρμόζεται σε περιπτώσεις όπου υπάρχει μια παρουσία της κλάσης EditableDocument, η οποία περιέχει το περιεχόμενο ενός επεξεργασμένου εγγράφου, και απαιτείται η αποθήκευση αυτού του περιεχομένου σε νέο έγγραφο μορφής WordProcessing.

### Δείτε επίσης

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
