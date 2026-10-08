---
title: "Αποθήκευση"
second_title: "GroupDocs.Editor για .NET αναφορά API"
description: "Μετατρέπει το καθορισμένο επεξεργασμένο έγγραφο που αναπαρίσταται ως παρουσία του EditableDocumentgroupdocs.editor/editabledocument στο τελικό έγγραφο του καθορισμένου μορφότυπου και αποθηκεύει το περιεχόμενό του στο καθορισμένο ρεύμα."
type: docs
weight: 80
url: /el/net/groupdocs.editor/editor/save/
---
## Save(EditableDocument, Stream, ISaveOptions) {#save_2}

Μετατρέπει το καθορισμένο επεξεργασμένο έγγραφο, που αναπαρίσταται ως παρουσία του '[`EditableDocument`](../../editabledocument)', στο τελικό έγγραφο του καθορισμένου μορφότυπου και αποθηκεύει το περιεχόμενό του στο καθορισμένο ρεύμα.

```csharp
public void Save(EditableDocument inputDocument, Stream outputDocument, ISaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputDocument | EditableDocument | Έκδοση του εισερχόμενου εγγράφου, που επεξεργάστηκε σε WYSIWYG HTML-editor και αποθηκεύεται ως παρουσία της κλάσης '[`EditableDocument`](../../editabledocument)', η οποία πρέπει να μετατραπεί σε έγγραφο εξόδου κάποιου συγκεκριμένου μορφότυπου. Δεν πρέπει να είναι null ή αποδεσμευμένο. |
| outputDocument | Ρεύμα | Ρεύμα εξόδου, στο οποίο θα καταγραφεί το περιεχόμενο του τελικού εγγράφου. Δεν πρέπει να είναι null, αποδεσμευμένο, και πρέπει να υποστηρίζει εγγραφή. |
| saveOptions | ISaveOptions | Επιλογές αποθήκευσης εγγράφου, που ορίζουν το μορφότυπο του τελικού εγγράφου, καθώς και γενικές και μορφο-συγκεκριμένες επιλογές αποθήκευσης. Δεν πρέπει να είναι null. |

### Σχόλια

**Learn more**

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### Δείτε επίσης

* class [EditableDocument](../../editabledocument)
* interface [ISaveOptions](../../../groupdocs.editor.options/isaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(EditableDocument, string, ISaveOptions) {#save_4}

Μετατρέπει το καθορισμένο επεξεργασμένο έγγραφο, που αναπαρίσταται ως παρουσία του '[`EditableDocument`](../../editabledocument)', στο τελικό έγγραφο του καθορισμένου μορφότυπου και αποθηκεύει το περιεχόμενό του σε αρχείο με τον καθορισμένο διαδρομή αρχείου.

```csharp
public void Save(EditableDocument inputDocument, string filePath, ISaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputDocument | EditableDocument | Έκδοση του εισερχόμενου εγγράφου, που επεξεργάστηκε σε WYSIWYG HTML-editor και αποθηκεύεται ως παρουσία της κλάσης '[`EditableDocument`](../../editabledocument)', η οποία πρέπει να μετατραπεί σε έγγραφο εξόδου κάποιου συγκεκριμένου μορφότυπου. Δεν πρέπει να είναι null ή αποδεσμευμένο. |
| filePath | String | Διαδρομή προς το αρχείο, στο οποίο θα αποθηκευτεί το έγγραφο εξόδου. Εάν υπάρχει αρχείο με το ίδιο όνομα, θα επανεγγραφεί πλήρως. Η συμβολοσειρά με τη διαδρομή δεν πρέπει να είναι null, κενή ή να περιέχει μόνο κενά. |
| saveOptions | ISaveOptions | Επιλογές αποθήκευσης εγγράφου, που ορίζουν το μορφότυπο του τελικού εγγράφου, καθώς και γενικές και μορφο-συγκεκριμένες επιλογές αποθήκευσης. Δεν πρέπει να είναι null. |

### Σχόλια

**Learn more**

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### Δείτε επίσης

* class [EditableDocument](../../editabledocument)
* interface [ISaveOptions](../../../groupdocs.editor.options/isaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(EditableDocument, string) {#save_3}

Μετατρέπει το καθορισμένο επεξεργασμένο έγγραφο, που αντιπροσωπεύεται ως παράδειγμα του '[`EditableDocument`](../../editabledocument)', στο τελικό έγγραφο μορφής που προσδιορίζεται από την επέκταση του ονόματος αρχείου, και αποθηκεύει το περιεχόμενό του σε αρχείο στη συγκεκριμένη διαδρομή αρχείου.

```csharp
public void Save(EditableDocument inputDocument, string filePath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputDocument | EditableDocument | Έκδοση του εισερχόμενου εγγράφου, που επεξεργάστηκε σε WYSIWYG HTML-editor και αποθηκεύεται ως παρουσία της κλάσης '[`EditableDocument`](../../editabledocument)', η οποία πρέπει να μετατραπεί σε έγγραφο εξόδου κάποιου συγκεκριμένου μορφότυπου. Δεν πρέπει να είναι null ή αποδεσμευμένο. |
| filePath | String | Διαδρομή προς το αρχείο, στο οποίο θα αποθηκευτεί το έγγραφο εξόδου. Εάν υπάρχει αρχείο με το ίδιο όνομα, θα ξαναγραφεί πλήρως. Η συμβολοσειρά της διαδρομής δεν πρέπει να είναι null, κενή ή να περιέχει μόνο κενά. Επειδή οι προεπιλεγμένες επιλογές αποθήκευσης και η μορφή εξόδου προσδιορίζονται από αυτό το όνομα αρχείου, πρέπει να έχει έγκυρη επέκταση. |

### Δείτε επίσης

* class [EditableDocument](../../editabledocument)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(Stream, WordProcessingSaveOptions) {#save_1}

Μετατρέπει το αρχικό έγγραφο μετά την τροποποίηση (για παράδειγμα, [`FormFieldManager`](../formfieldmanager)), στο τελικό έγγραφο της καθορισμένης μορφής και αποθηκεύει το περιεχόμενό του στην παρεχόμενη ροή.

```csharp
public Stream Save(Stream outputDocument, WordProcessingSaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| outputDocument | Ρεύμα | Η ροή στην οποία θα αποθηκευτεί το έγγραφο εξόδου. Αυτή η ροή πρέπει να είναι εγγράψιμη και τοποθετημένη στην αρχή του περιεχομένου του εγγράφου. Δεν πρέπει να είναι null. |
| saveOptions | WordProcessingSaveOptions | Επιλογές αποθήκευσης εγγράφου που ορίζουν τη μορφή του τελικού εγγράφου, καθώς και γενικές και ειδικές για τη μορφή επιλογές αποθήκευσης. Δεν πρέπει να είναι null. |

### Τιμή Επιστροφής

Η ροή που περιέχει το αποθηκευμένο περιεχόμενο του εγγράφου.

### Σχόλια

Εάν το *outputDocument* ή το *saveOptions* είναι null, θα εξαχθεί ένα ArgumentNullException. Εάν λείπει το έγγραφο προς αποθήκευση, θα εξαχθεί ένα ArgumentNullException.

Εξαχθεί όταν το *outputDocument* ή το *saveOptions* είναι null, ή όταν λείπει το έγγραφο προς αποθήκευση.**Μάθετε περισσότερα:**

* More about saving documents after modification using GroupDocs.Editor: [How to save documents using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### Δείτε επίσης

* class [WordProcessingSaveOptions](../../../groupdocs.editor.options/wordprocessingsaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(Stream) {#save}

Αποθηκεύει το τρέχον περιεχόμενο του εγγράφου στην καθορισμένη ροή εξόδου.

```csharp
public Stream Save(Stream outputDocument)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| outputDocument | Ρεύμα | Η ροή στην οποία θα αποθηκευτεί το περιεχόμενο του εγγράφου. Αυτό δεν μπορεί να είναι null. |

### Τιμή Επιστροφής

Η ροή με το αποθηκευμένο περιεχόμενο του εγγράφου.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εξαχθεί όταν το *outputDocument* είναι null ή εάν λείπει το περιεχόμενο του εγγράφου. |

### Σχόλια

Αυτή η μέθοδος αντιγράφει το περιεχόμενο από την εσωτερική αναπαράσταση του εγγράφου στην παρεχόμενη ροή εξόδου. Η αρχική θέση της ροής διατηρείται μετά τη λειτουργία αποθήκευσης.

### Δείτε επίσης

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
