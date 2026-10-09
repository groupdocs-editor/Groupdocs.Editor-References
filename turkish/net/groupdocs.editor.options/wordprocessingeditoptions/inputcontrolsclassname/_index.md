---
title: "InputControlsClassName"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Giriş WordProcessing belgesindeki bir alanı temsil eden her HTML öğesinin class özniteliklerine yerleştirilecek bir sınıf adını belirtmeye izin verir. Varsayılan olarak NULL'dur; class öznitelikleri uygulanmaz."
type: docs
weight: 60
url: /tr/net/groupdocs.editor.options/wordprocessingeditoptions/inputcontrolsclassname/
---
## WordProcessingEditOptions.InputControlsClassName property

Giriş WordProcessing belgesindeki bir alanı temsil eden her HTML öğesine 'class' özniteliklerine yerleştirilecek bir sınıf adı belirtmeye olanak tanır. Varsayılan olarak NULL'dır - 'class' öznitelikleri uygulanmaz.

```csharp
public string InputControlsClassName { get; set; }
```

### Açıklamalar

WordProcessing format ailesinin neredeyse tüm formatları alanlar içerir — kullanıcıdan giriş verisi almayı sağlayan belirli belge varlıkları. Metin kutuları, onay kutuları, açılır kutular, düşen listeler, düğmeler, tarih/saat seçiciler vb. gibi çok çeşitli alanlar vardır. Bunların tümü, giriş belgesinde mevcutsa girilen kullanıcı verisini koruyarak en uygun HTML yapıları ve öğelerine dönüştürülür. Belirli kullanım senaryolarında tüm belge içeriğini düzenlemek yerine yalnızca istemci tarafında girilen verileri toplamak gerekir. Böyle bir durumda, istemci tarafında verileriyle birlikte bu giriş kontrollerini bir şekilde tanımlamak gerekir. Bu özellik, HTML işaretlemesindeki her giriş kontrolüne uygulanacak bir sınıf adını belirtmeye olanak tanır, böylece istemci kodu HTML belge yapısında dolaşarak verileri toplayabilir.

### Ayrıca Bakınız

* class [WordProcessingEditOptions](../../wordprocessingeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
