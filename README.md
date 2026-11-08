# CiterLab
[Türkçe](README.md) · [English](README.en.md) · [Deutsch](README.de.md) · [العربية](README.ar.md)

**Çok Amaçlı Akademik Paket Program**

CiterLab; kaynaklarla çalışma, kişisel alıntı arşivi, istatistiksel analiz ve belge araçlarını bir araya getiren Windows masaüstü uygulamasıdır.

Bu depo CiterLab’ın resmî ürün tanıtımıdır. Uygulamanın kaynak kodunu veya çalışan kurulum paketini içermez.

Yayın hazırlığı sürüyor. Güncel indirme ve satış durumu için resmî web sitesini kontrol edin.

![CiterLab](images/og.png)

## Dört gerçek çalışma örneği

**28 sekme türü ve 1 VCF dönüştürme diyaloğu: toplam 29 araç.**

Her araç, uygulamadaki simgesi ve gerçek çalışma ekranıyla gösterilir. Projelerim de bu envantere dahildir; VCF aracı ayrı bir diyalogdur.

Ekranlar Türkçe arayüzden, gerçek uygulama teması altında Windows %125 ölçekte alınmıştır. Örnek veriler ve çalışılmış örnekler araştırma bulgusu değildir. Sonuçları veri, yöntem ve kaynak kapsamıyla birlikte değerlendirin.

<table>
<tr>
<td><a href="#module-excel_analiz"><img src="images/gallery/excel_analiz.webp" alt="CiterLab Nicel Analiz çalışma alanında hesaplanmış ANOVA sonuçları" width="360"></a><br><a href="#module-excel_analiz"><strong>Nicel Analiz</strong></a></td>
<td><a href="#module-bib"><img src="images/gallery/bib.webp" alt="CiterLab Literatür Taraması sekmesinde yayın arama sonuçları ve kaynak bilgileri" width="360"></a><br><a href="#module-bib"><strong>Literatür Taraması</strong></a></td>
</tr>
<tr>
<td><a href="#module-bibliometric"><img src="images/gallery/bibliometric.webp" alt="CiterLab Bibliyometrik Analiz ekranında yayın verilerinden hesaplanan sonuçlar" width="360"></a><br><a href="#module-bibliometric"><strong>Bibliyometrik Analiz</strong></a></td>
<td><a href="#module-calc"><img src="images/gallery/calc.webp" alt="CiterLab Grafik ve Geometri çalışma alanında çizilmiş e üzeri x fonksiyonu" width="360"></a><br><a href="#module-calc"><strong>Grafik ve Geometri</strong></a></td>
</tr>
</table>

<a id="tool-overview"></a>

## Tüm araçlar bir bakışta

| Simge | Araç | Öne çıkan özellikler |
| --- | --- | --- |
| <img src="images/gallery/icon-excel_analiz.png" alt="" width="32" height="32"> | [Nicel Analiz](#module-excel_analiz) | ANOVA ile grupları karşılaştırın<br>Değişken rollerini açıkça belirleyin<br>Bulguları rapora taşıyın |
| <img src="images/gallery/icon-qda.png" alt="" width="32" height="32"> | [Nitel Analiz](#module-qda) | Pasajları doğrudan kodlayın<br>Kaynak ve kodları birlikte görün<br>Temaları matrislerle inceleyin |
| <img src="images/gallery/icon-bib.png" alt="" width="32" height="32"> | [Literatür Taraması](#module-bib) | Yayınları tek listede inceleyin<br>Kaynak özetlerine geçin<br>Arama sonuçlarını dışa aktarın |
| <img src="images/gallery/icon-bibliometric.png" alt="" width="32" height="32"> | [Bibliyometrik Analiz](#module-bibliometric) | Yıllara göre dağılımı görün<br>Yazar ve kaynakları karşılaştırın<br>Veri kalitesini inceleyin |
| <img src="images/gallery/icon-calc.png" alt="" width="32" height="32"> | [Grafik ve Geometri](#module-calc) | eˣ eğrisini görün<br>Türev ve integrali inceleyin<br>Geometri nesneleri oluşturun |
| <img src="images/gallery/icon-desing.png" alt="" width="32" height="32"> | [Araştırma Tasarımı](#module-desing) | Desenleri açıklamalarıyla inceleyin<br>Değişken rollerini planlayın<br>Analiz seçeneklerini değerlendirin |
| <img src="images/gallery/icon-concept_library.png" alt="" width="32" height="32"> | [Kavram Kütüphanesi](#module-concept_library) | Tanımı kaynağıyla okuyun<br>İlişkili kavramlara geçin<br>Metninize kaynaklı içerik ekleyin |
| <img src="images/gallery/icon-databank.png" alt="" width="32" height="32"> | [Veri Bankası](#module-databank) | Veri kaynaklarını keşfedin<br>Yerel dosyanızı içe aktarın<br>Tabloyu süzün ve inceleyin |
| <img src="images/gallery/icon-cheatsheets.png" alt="" width="32" height="32"> | [Başvuru Rehberleri](#module-cheatsheets) | Konular arasında hızla gezinin<br>Formül ve örnekleri birlikte görün<br>Rehberleri PDF veya DOCX alın |
| <img src="images/gallery/icon-library.png" alt="" width="32" height="32"> | [Kaynak Arşivi](#module-library) | Arşivde arama yapın<br>Kaynak bilgilerini inceleyin<br>Kayıtlı belgelere geri dönün |
| <img src="images/gallery/icon-bibliography_check.png" alt="" width="32" height="32"> | [Kaynakça Denetimi](#module-bibliography_check) | Atıf ve kaynakçayı karşılaştırın<br>Eşleşmeleri birlikte inceleyin<br>Denetim raporuna geçin |
| <img src="images/gallery/icon-lo_docx.png" alt="" width="32" height="32"> | [DOCX](#module-lo_docx) | Metninizi biçimlendirin<br>Tablo ve görseller ekleyin<br>Belgenizi çalışma alanında düzenleyin |
| <img src="images/gallery/icon-lo_xlsx.png" alt="" width="32" height="32"> | [XLSX](#module-lo_xlsx) | Hücreleri doğrudan düzenleyin<br>Formüllerle hesaplayın<br>Çalışma kitabınızı kaydedin |
| <img src="images/gallery/icon-lo_pptx.png" alt="" width="32" height="32"> | [SUNUM](#module-lo_pptx) | Slaytları düzenleyin<br>Metin ve görselleri birleştirin<br>Sunumunuzu kaydedin |
| <img src="images/gallery/icon-lo_draw.png" alt="" width="32" height="32"> | [GÖRSEL](#module-lo_draw) | Şekillerle anlatın<br>Metin ve görselleri yerleştirin<br>Çizim belgenizi kaydedin |
| <img src="images/gallery/icon-lo_math.png" alt="" width="32" height="32"> | [FORMÜL](#module-lo_math) | Formülleri ayrı sekmede çalışın<br>Matematiksel gösterimi düzenleyin<br>Formül belgenizi kaydedin |
| <img src="images/gallery/icon-lo_base.png" alt="" width="32" height="32"> | [VERİTABANI](#module-lo_base) | Veritabanı belgesini açın<br>Ayrı sekmede çalışın<br>Belgenizi kaydedin |
| <img src="images/gallery/icon-text.png" alt="" width="32" height="32"> | [TXT Editör](#module-text) | Not almaya başlayın<br>Düz metni doğrudan düzenleyin<br>Metninizi dosyaya kaydedin |
| <img src="images/gallery/icon-tex.png" alt="" width="32" height="32"> | [TeX Studio](#module-tex) | LaTeX kaynağını düzenleyin<br>Derleme çıktısını inceleyin<br>Belge önizlemesiyle ilerleyin |
| <img src="images/gallery/icon-pdf.png" alt="" width="32" height="32"> | [PDF Editör](#module-pdf) | Sayfalar arasında gezinin<br>Belgede metin arayın<br>Okuma görünümünü ayarlayın |
| <img src="images/gallery/icon-paint.png" alt="" width="32" height="32"> | [Karalama Defteri](#module-paint) | Serbestçe çizim yapın<br>Renk ve kalem seçin<br>Görsel taslaklar hazırlayın |
| <img src="images/gallery/icon-epub.png" alt="" width="32" height="32"> | [EPUB Okuyucu](#module-epub) | İçindekilerden bölüme geçin<br>Kitap içinde arama yapın<br>Yazı boyutunu ayarlayın |
| <img src="images/gallery/icon-web.png" alt="" width="32" height="32"> | [Web Tarayıcısı](#module-web) | Adresi sekmede açın<br>Sayfalar arasında gezinin<br>Kaynakları yan yana inceleyin |
| <img src="images/gallery/icon-media.png" alt="" width="32" height="32"> | [Medya Oynatıcı](#module-media) | Ses ve video açın<br>Zaman çizelgesinde gezinin<br>Oynatmayı kontrol edin |
| <img src="images/gallery/icon-automation.png" alt="" width="32" height="32"> | [Belge İşlemleri](#module-automation) | Dosyaları bir listede toplayın<br>Belge işlemini seçin<br>İşlem durumunu izleyin |
| <img src="images/gallery/icon-mini_calc.png" alt="" width="32" height="32"> | [Hesap Makinesi](#module-mini_calc) | Temel işlemleri hesaplayın<br>Sonucu hemen görün<br>İşlem geçmişini izleyin |
| <img src="images/gallery/icon-signature.png" alt="" width="32" height="32"> | [İmza Yöneticisi](#module-signature) | İmzanızı çizerek oluşturun<br>Görseli kırpıp düzenleyin<br>Şeffaf önizlemeyi inceleyin |
| <img src="images/gallery/icon-projects.png" alt="" width="32" height="32"> | [Projelerim](#module-projects) | Projeleri bir listede görün<br>Belgelere yeniden ulaşın<br>Proje notlarını birlikte tutun |
| <img src="images/gallery/icon-contacts_vcf.png" alt="" width="32" height="32"> | [Excel → Telefon Rehberi (VCF)](#module-contacts_vcf) | Kişi tablonuzu seçin<br>Alanları açıkça eşleyin<br>VCF çıktısı hazırlayın |

## Araçları yakından inceleyin

<a id="module-excel_analiz"></a>

<details>
<summary><img src="images/gallery/icon-excel_analiz.png" alt="" width="24" height="24"> <strong>Nicel Analiz</strong> · Sekme</summary>

### Veriden bulguya ilerleyin

Değişkenlerinizi seçin, uygun analizi çalıştırın ve hesaplanan sonuçları raporunuzda inceleyin.

- ANOVA ile grupları karşılaştırın
- Değişken rollerini açıkça belirleyin
- Bulguları rapora taşıyın

<img src="images/gallery/excel_analiz.webp" alt="CiterLab Nicel Analiz çalışma alanında hesaplanmış ANOVA sonuçları" width="1100">

[Tam ekranı aç](images/gallery/excel_analiz.webp) · [Araç listesine dön](#tool-overview)

</details>

<a id="module-qda"></a>

<details>
<summary><img src="images/gallery/icon-qda.png" alt="" width="24" height="24"> <strong>Nitel Analiz</strong> · Sekme</summary>

### Anlamı kodlarla görünür kılın

Kaynak metinlerinizi kodlayın; seçili pasajları, notları ve temalar arasındaki ilişkileri birlikte inceleyin.

- Pasajları doğrudan kodlayın
- Kaynak ve kodları birlikte görün
- Temaları matrislerle inceleyin

<img src="images/gallery/qda.webp" alt="CiterLab Nitel Analiz ekranında kaynak metni, kod ağacı ve kodlanmış pasajlar" width="1100">

[Tam ekranı aç](images/gallery/qda.webp) · [Araç listesine dön](#tool-overview)

</details>

<a id="module-bib"></a>

<details>
<summary><img src="images/gallery/icon-bib.png" alt="" width="24" height="24"> <strong>Literatür Taraması</strong> · Sekme</summary>

### Araştırmanızın izini sürün

Akademik kaynaklarda arama yapın; yayınları, kaynak özetlerini ve seçili cümleleri düzenli görünümlerde inceleyin.

- Yayınları tek listede inceleyin
- Kaynak özetlerine geçin
- Arama sonuçlarını dışa aktarın

<img src="images/gallery/bib.webp" alt="CiterLab Literatür Taraması sekmesinde yayın arama sonuçları ve kaynak bilgileri" width="1100">

[Tam ekranı aç](images/gallery/bib.webp) · [Araç listesine dön](#tool-overview)

</details>

<a id="module-bibliometric"></a>

<details>
<summary><img src="images/gallery/icon-bibliometric.png" alt="" width="24" height="24"> <strong>Bibliyometrik Analiz</strong> · Sekme</summary>

### Literatürün örüntülerini keşfedin

Yayın verilerindeki yılları, yazarları, kaynakları ve terimleri analiz ederek araştırma alanınızı daha yakından tanıyın.

- Yıllara göre dağılımı görün
- Yazar ve kaynakları karşılaştırın
- Veri kalitesini inceleyin

<img src="images/gallery/bibliometric.webp" alt="CiterLab Bibliyometrik Analiz ekranında yayın verilerinden hesaplanan sonuçlar" width="1100">

[Tam ekranı aç](images/gallery/bibliometric.webp) · [Araç listesine dön](#tool-overview)

</details>

<a id="module-calc"></a>

<details>
<summary><img src="images/gallery/icon-calc.png" alt="" width="24" height="24"> <strong>Grafik ve Geometri</strong> · Sekme</summary>

### Matematiği çizerek keşfedin

Fonksiyonları çizin, matematik nesneleri ekleyin ve geometriyi aynı koordinat düzleminde inceleyin.

- eˣ eğrisini görün
- Türev ve integrali inceleyin
- Geometri nesneleri oluşturun

<img src="images/gallery/calc.webp" alt="CiterLab Grafik ve Geometri çalışma alanında çizilmiş e üzeri x fonksiyonu" width="1100">

[Tam ekranı aç](images/gallery/calc.webp) · [Araç listesine dön](#tool-overview)

</details>

<a id="module-desing"></a>

<details>
<summary><img src="images/gallery/icon-desing.png" alt="" width="24" height="24"> <strong>Araştırma Tasarımı</strong> · Sekme</summary>

### Sorudan yöntem planına

Araştırma desenlerini inceleyin; değişkenlerinizi ve analiz seçeneklerinizi açık bir plan etrafında düzenleyin.

- Desenleri açıklamalarıyla inceleyin
- Değişken rollerini planlayın
- Analiz seçeneklerini değerlendirin

<img src="images/gallery/desing.webp" alt="CiterLab Araştırma Tasarımı ekranında seçili araştırma deseni ve yöntem açıklaması" width="1100">

[Tam ekranı aç](images/gallery/desing.webp) · [Araç listesine dön](#tool-overview)

</details>

<a id="module-concept_library"></a>

<details>
<summary><img src="images/gallery/icon-concept_library.png" alt="" width="24" height="24"> <strong>Kavram Kütüphanesi</strong> · Sekme</summary>

### Kavramları bağlamıyla anlayın

Kavramları tanımları ve kaynaklarıyla keşfedin; ilişkili terimler arasında gezinin ve araştırma metninize taşıyın.

- Tanımı kaynağıyla okuyun
- İlişkili kavramlara geçin
- Metninize kaynaklı içerik ekleyin

<img src="images/gallery/concept_library.webp" alt="CiterLab Kavram Kütüphanesi ekranında tanım, ilişkili kavramlar ve kaynaklar" width="1100">

[Tam ekranı aç](images/gallery/concept_library.webp) · [Araç listesine dön](#tool-overview)

</details>

<a id="module-databank"></a>

<details>
<summary><img src="images/gallery/icon-databank.png" alt="" width="24" height="24"> <strong>Veri Bankası</strong> · Sekme</summary>

### Veriyi araştırmanıza bağlayın

Veri kaynaklarını keşfedin veya yerel dosyanızı açın; tabloları süzerek ihtiyaç duyduğunuz gözlemleri inceleyin.

- Veri kaynaklarını keşfedin
- Yerel dosyanızı içe aktarın
- Tabloyu süzün ve inceleyin

<img src="images/gallery/databank.webp" alt="CiterLab Veri Bankası çalışma alanında veri tablosu ve filtreleme araçları" width="1100">

[Tam ekranı aç](images/gallery/databank.webp) · [Araç listesine dön](#tool-overview)

</details>

<a id="module-cheatsheets"></a>

<details>
<summary><img src="images/gallery/icon-cheatsheets.png" alt="" width="24" height="24"> <strong>Başvuru Rehberleri</strong> · Sekme</summary>

### Bilgi elinizin altında

Konu rehberlerini formülleri ve örnekleriyle okuyun; arama yapın ve seçtiğiniz rehberi dışa aktarın.

- Konular arasında hızla gezinin
- Formül ve örnekleri birlikte görün
- Rehberleri PDF veya DOCX alın

<img src="images/gallery/cheatsheets.webp" alt="CiterLab Başvuru Rehberleri ekranında konu listesi ve formüllü rehber sayfası" width="1100">

[Tam ekranı aç](images/gallery/cheatsheets.webp) · [Araç listesine dön](#tool-overview)

</details>

<a id="module-library"></a>

<details>
<summary><img src="images/gallery/icon-library.png" alt="" width="24" height="24"> <strong>Kaynak Arşivi</strong> · Sekme</summary>

### Kaynaklarınıza yeniden ulaşın

Arşivlediğiniz yayın ve belgeleri arayın; kaynak bilgilerini ve kayıtlı içeriklerini araştırmanızla birlikte inceleyin.

- Arşivde arama yapın
- Kaynak bilgilerini inceleyin
- Kayıtlı belgelere geri dönün

<img src="images/gallery/library.webp" alt="CiterLab Kaynak Arşivi ekranında arama sonuçları ve seçili kaynak kaydı" width="1100">

[Tam ekranı aç](images/gallery/library.webp) · [Araç listesine dön](#tool-overview)

</details>

<a id="module-bibliography_check"></a>

<details>
<summary><img src="images/gallery/icon-bibliography_check.png" alt="" width="24" height="24"> <strong>Kaynakça Denetimi</strong> · Sekme</summary>

### Atıfların izini kontrol edin

Belgedeki atıflarla kaynakça kayıtlarının eşleşmesini inceleyin; eşleşenleri ve gözden geçirilmesi gerekenleri raporda görün.

- Atıf ve kaynakçayı karşılaştırın
- Eşleşmeleri birlikte inceleyin
- Denetim raporuna geçin

<img src="images/gallery/bibliography_check.webp" alt="CiterLab Kaynakça Denetimi ekranında belge atıfları ve kaynakça eşleşmelerinin sonuçları" width="1100">

[Tam ekranı aç](images/gallery/bibliography_check.webp) · [Araç listesine dön](#tool-overview)

</details>

<a id="module-lo_docx"></a>

<details>
<summary><img src="images/gallery/icon-lo_docx.png" alt="" width="24" height="24"> <strong>DOCX</strong> · Sekme</summary>

### Bulgularınızı metne dönüştürün

Araştırma belgenizi çalışma alanında yazın; başlıklar, tablolar ve görsellerle düzenleyip kaydedin.

- Metninizi biçimlendirin
- Tablo ve görseller ekleyin
- Belgenizi çalışma alanında düzenleyin

<img src="images/gallery/lo_docx.webp" alt="CiterLab içinde açılmış biçimlendirilmiş DOCX araştırma belgesi" width="1100">

[Tam ekranı aç](images/gallery/lo_docx.webp) · [Araç listesine dön](#tool-overview)

</details>

<a id="module-lo_xlsx"></a>

<details>
<summary><img src="images/gallery/icon-lo_xlsx.png" alt="" width="24" height="24"> <strong>XLSX</strong> · Sekme</summary>

### Verilerinizi düzenli tutun

Hesap tablonuzu çalışma alanında açın; hücreleri, formülleri ve tablo düzenini belge üzerinde düzenleyin.

- Hücreleri doğrudan düzenleyin
- Formüllerle hesaplayın
- Çalışma kitabınızı kaydedin

<img src="images/gallery/lo_xlsx.webp" alt="CiterLab içinde açılmış verilerle dolu XLSX hesap tablosu" width="1100">

[Tam ekranı aç](images/gallery/lo_xlsx.webp) · [Araç listesine dön](#tool-overview)

</details>

<a id="module-lo_pptx"></a>

<details>
<summary><img src="images/gallery/icon-lo_pptx.png" alt="" width="24" height="24"> <strong>SUNUM</strong> · Sekme</summary>

### Araştırmanızı sahneye taşıyın

Sunum slaytlarınızı çalışma alanında düzenleyin; metin ve görsellerle araştırmanızın anlatısını oluşturun.

- Slaytları düzenleyin
- Metin ve görselleri birleştirin
- Sunumunuzu kaydedin

<img src="images/gallery/lo_pptx.webp" alt="CiterLab içindeki sunum düzenleyicisinde araştırma slaydı" width="1100">

[Tam ekranı aç](images/gallery/lo_pptx.webp) · [Araç listesine dön](#tool-overview)

</details>

<a id="module-lo_draw"></a>

<details>
<summary><img src="images/gallery/icon-lo_draw.png" alt="" width="24" height="24"> <strong>GÖRSEL</strong> · Sekme</summary>

### Fikirlerinize görsel düzen verin

Çizim belgesinde şekilleri, metni ve görselleri bir araya getirerek açıklayıcı sayfalar hazırlayın.

- Şekillerle anlatın
- Metin ve görselleri yerleştirin
- Çizim belgenizi kaydedin

<img src="images/gallery/lo_draw.webp" alt="CiterLab görsel belge düzenleyicisinde şekiller ve metin içeren çizim sayfası" width="1100">

[Tam ekranı aç](images/gallery/lo_draw.webp) · [Araç listesine dön](#tool-overview)

</details>

<a id="module-lo_math"></a>

<details>
<summary><img src="images/gallery/icon-lo_math.png" alt="" width="24" height="24"> <strong>FORMÜL</strong> · Sekme</summary>

### Matematiksel ifadeleri düzenleyin

Formül belgenizi ayrı bir sekmede oluşturun; matematiksel gösterimi düzenleyerek çalışmanızı kaydedin.

- Formülleri ayrı sekmede çalışın
- Matematiksel gösterimi düzenleyin
- Formül belgenizi kaydedin

<img src="images/gallery/lo_math.webp" alt="CiterLab formül düzenleyicisinde açık bir matematiksel ifade" width="1100">

[Tam ekranı aç](images/gallery/lo_math.webp) · [Araç listesine dön](#tool-overview)

</details>

<a id="module-lo_base"></a>

<details>
<summary><img src="images/gallery/icon-lo_base.png" alt="" width="24" height="24"> <strong>VERİTABANI</strong> · Sekme</summary>

### Veritabanı belgenize yer açın

Veritabanı belgelerini çalışma alanındaki ayrı bir sekmede açın ve veritabanı düzenleyicisiyle çalışın.

- Veritabanı belgesini açın
- Ayrı sekmede çalışın
- Belgenizi kaydedin

<img src="images/gallery/lo_base.webp" alt="CiterLab içindeki veritabanı belgesi düzenleyicisi" width="1100">

[Tam ekranı aç](images/gallery/lo_base.webp) · [Araç listesine dön](#tool-overview)

</details>

<a id="module-text"></a>

<details>
<summary><img src="images/gallery/icon-text.png" alt="" width="24" height="24"> <strong>TXT Editör</strong> · Sekme</summary>

### Düşüncenizi hemen kaydedin

Düz metin notlarınızı belge sekmesinde yazın, düzenleyin ve dosyaya kaydedin.

- Not almaya başlayın
- Düz metni doğrudan düzenleyin
- Metninizi dosyaya kaydedin

<img src="images/gallery/text.webp" alt="CiterLab TXT Editör sekmesinde araştırma notları" width="1100">

[Tam ekranı aç](images/gallery/text.webp) · [Araç listesine dön](#tool-overview)

</details>

<a id="module-tex"></a>

<details>
<summary><img src="images/gallery/icon-tex.png" alt="" width="24" height="24"> <strong>TeX Studio</strong> · Sekme</summary>

### Bilimsel metni özenle kurun

TeX ve LaTeX kaynağınızı düzenleyin; derleme araçlarıyla üretilen belgeyi önizleyip çalışmanızı geliştirin.

- LaTeX kaynağını düzenleyin
- Derleme çıktısını inceleyin
- Belge önizlemesiyle ilerleyin

<img src="images/gallery/tex.webp" alt="CiterLab TeX Studio ekranında LaTeX kaynak kodu ve belge önizlemesi" width="1100">

[Tam ekranı aç](images/gallery/tex.webp) · [Araç listesine dön](#tool-overview)

</details>

<a id="module-pdf"></a>

<details>
<summary><img src="images/gallery/icon-pdf.png" alt="" width="24" height="24"> <strong>PDF Editör</strong> · Sekme</summary>

### Okumayı araştırmaya bağlayın

PDF sayfalarında gezinin, metin arayın ve belgeyi araştırma araçlarınızla aynı çalışma alanında inceleyin.

- Sayfalar arasında gezinin
- Belgede metin arayın
- Okuma görünümünü ayarlayın

<img src="images/gallery/pdf.webp" alt="CiterLab PDF çalışma alanında açık bir araştırma belgesi ve sayfa araçları" width="1100">

[Tam ekranı aç](images/gallery/pdf.webp) · [Araç listesine dön](#tool-overview)

</details>

<a id="module-paint"></a>

<details>
<summary><img src="images/gallery/icon-paint.png" alt="" width="24" height="24"> <strong>Karalama Defteri</strong> · Sekme</summary>

### Fikrin ilk çizgisini atın

Serbest çizim yapın, renklerle düşünün ve araştırma fikrinizi görsel bir taslağa dönüştürün.

- Serbestçe çizim yapın
- Renk ve kalem seçin
- Görsel taslaklar hazırlayın

<img src="images/gallery/paint.webp" alt="CiterLab Karalama Defteri ekranında çizim tuvali ve kalem araçları" width="1100">

[Tam ekranı aç](images/gallery/paint.webp) · [Araç listesine dön](#tool-overview)

</details>

<a id="module-epub"></a>

<details>
<summary><img src="images/gallery/icon-epub.png" alt="" width="24" height="24"> <strong>EPUB Okuyucu</strong> · Sekme</summary>

### Kitap boyunca rahatça ilerleyin

EPUB kitabınızı açın; içindekiler, metin arama ve okuma ayarlarıyla ihtiyacınız olan bölüme ulaşın.

- İçindekilerden bölüme geçin
- Kitap içinde arama yapın
- Yazı boyutunu ayarlayın

<img src="images/gallery/epub.webp" alt="CiterLab EPUB Okuyucu ekranında kitap bölümü ve içindekiler listesi" width="1100">

[Tam ekranı aç](images/gallery/epub.webp) · [Araç listesine dön](#tool-overview)

</details>

<a id="module-web"></a>

<details>
<summary><img src="images/gallery/icon-web.png" alt="" width="24" height="24"> <strong>Web Tarayıcısı</strong> · Sekme</summary>

### Web araştırmasını yakın tutun

Web sayfalarını çalışma alanınızdaki bir sekmede açın ve kaynakları belgelerinizle yan yana inceleyin.

- Adresi sekmede açın
- Sayfalar arasında gezinin
- Kaynakları yan yana inceleyin

<img src="images/gallery/web.webp" alt="CiterLab Web Tarayıcısı sekmesinde açık bir araştırma sayfası" width="1100">

[Tam ekranı aç](images/gallery/web.webp) · [Araç listesine dön](#tool-overview)

</details>

<a id="module-media"></a>

<details>
<summary><img src="images/gallery/icon-media.png" alt="" width="24" height="24"> <strong>Medya Oynatıcı</strong> · Sekme</summary>

### Ses ve görüntüyü inceleyin

Ses veya video dosyanızı çalışma alanında açın; oynatma ve zaman çizelgesiyle ilgili bölümleri inceleyin.

- Ses ve video açın
- Zaman çizelgesinde gezinin
- Oynatmayı kontrol edin

<img src="images/gallery/media.webp" alt="CiterLab Medya Oynatıcı ekranında açık video ve oynatma zaman çizelgesi" width="1100">

[Tam ekranı aç](images/gallery/media.webp) · [Araç listesine dön](#tool-overview)

</details>

<a id="module-automation"></a>

<details>
<summary><img src="images/gallery/icon-automation.png" alt="" width="24" height="24"> <strong>Belge İşlemleri</strong> · Sekme</summary>

### Belge işlerini bir araya getirin

Dosyalarınızı işlem listesine ekleyin ve dönüştürme, birleştirme ya da ayırma seçenekleriyle çalışın.

- Dosyaları bir listede toplayın
- Belge işlemini seçin
- İşlem durumunu izleyin

<img src="images/gallery/automation.webp" alt="CiterLab Belge İşlemleri ekranında dosya listesi ve belge işlem seçenekleri" width="1100">

[Tam ekranı aç](images/gallery/automation.webp) · [Araç listesine dön](#tool-overview)

</details>

<a id="module-mini_calc"></a>

<details>
<summary><img src="images/gallery/icon-mini_calc.png" alt="" width="24" height="24"> <strong>Hesap Makinesi</strong> · Sekme</summary>

### Küçük hesapları hızla çözün

Günlük hesaplamalarınızı yapın ve işlem geçmişinden önceki adımları gözden geçirin.

- Temel işlemleri hesaplayın
- Sonucu hemen görün
- İşlem geçmişini izleyin

<img src="images/gallery/mini_calc.webp" alt="CiterLab Hesap Makinesi ekranında sayısal sonuç ve işlem geçmişi" width="1100">

[Tam ekranı aç](images/gallery/mini_calc.webp) · [Araç listesine dön](#tool-overview)

</details>

<a id="module-signature"></a>

<details>
<summary><img src="images/gallery/icon-signature.png" alt="" width="24" height="24"> <strong>İmza Yöneticisi</strong> · Sekme</summary>

### Görsel imzanızı hazırlayın

İmza çiziminizi oluşturun veya bir imza görselini düzenleyin; önizleyip belgeye eklemek üzere hazırlayın.

- İmzanızı çizerek oluşturun
- Görseli kırpıp düzenleyin
- Şeffaf önizlemeyi inceleyin

<img src="images/gallery/signature.webp" alt="CiterLab İmza Yöneticisi ekranında çizilmiş örnek imza ve görsel önizlemesi" width="1100">

[Tam ekranı aç](images/gallery/signature.webp) · [Araç listesine dön](#tool-overview)

</details>

<a id="module-projects"></a>

<details>
<summary><img src="images/gallery/icon-projects.png" alt="" width="24" height="24"> <strong>Projelerim</strong> · Sekme</summary>

### Araştırmanıza kaldığınız yerden dönün

Çalışma alanlarınızı ve proje belgelerinizi birlikte görün; proje ayrıntıları ve notlarıyla çalışmanızı sürdürün.

- Projeleri bir listede görün
- Belgelere yeniden ulaşın
- Proje notlarını birlikte tutun

<img src="images/gallery/projects.webp" alt="CiterLab Projelerim ekranında proje listesi, belgeler ve proje ayrıntıları" width="1100">

[Tam ekranı aç](images/gallery/projects.webp) · [Araç listesine dön](#tool-overview)

</details>

<a id="module-contacts_vcf"></a>

<details>
<summary><img src="images/gallery/icon-contacts_vcf.png" alt="" width="24" height="24"> <strong>Excel → Telefon Rehberi (VCF)</strong> · Diyalog</summary>

### Tablodan kişi kartlarına

Excel tablonuzdaki kişi alanlarını eşleyin ve telefon rehberine aktarılabilecek VCF dosyası hazırlayın.

- Kişi tablonuzu seçin
- Alanları açıkça eşleyin
- VCF çıktısı hazırlayın

<img src="images/gallery/contacts_vcf.webp" alt="CiterLab Excel&#x27;den VCF&#x27;ye dönüştürme diyaloğunda kişi alanlarının eşlenmesi" width="1100">

[Tam ekranı aç](images/gallery/contacts_vcf.webp) · [Araç listesine dön](#tool-overview)

</details>

## Görsel kaynakları ve bağlam

Önceki tanıtımın kaynak açıklamaları ve uyarıları aşağıda korunur. Makale lisansı ve görsel kaynakları için [ATTRIBUTIONS.txt](ATTRIBUTIONS.txt) dosyasına bakın.

- [**Grafik stüdyosu**](images/screen-charts.png) — Sentetik örnek verilerden gerçek uygulamada üretilen grafiklerdir; araştırma bulgusu değildir.
- [**Kavram Atlası**](images/screen-concepts.png) — Kaynak ve çeviri inceleme durumları uygulama ekranında korunur.
- [**Kaynakça denetimi**](images/screen-citations.png) — Gerçek açık erişimli makalenin iç sayfasıdır. Başlık sayfası gösterilmez; eşleşenler filtresi seçilidir. Sonuçlar algoritmik eşleşmedir; özgün yayınların doğrulandığı anlamına gelmez.

## Kapsam ve kullanım

Yerel araçlar ve indirilmiş kütüphane/model bileşenleri çevrimdışı kullanılabilir. İlk etkinleştirme, bileşen indirmeleri ve çevrim içi kaynak sorguları bağlantı gerektirir. Desteklenen dosya türleri ve analizlerin kapsamı işlemden işleme değişir. Eşleşmeler, analiz varsayımları ve yapay zeka çıktıları kullanıcı tarafından gözden geçirilmelidir.

## Resmî bağlantılar

- [Web sitesi](https://citerlab.com)
- Destek: [info@citerlab.com](mailto:info@citerlab.com)

## Haklar ve görsel kaynakları

CiterLab özgün içeriğine ilişkin hak bildirimi NOTICE.md içindedir. Üçüncü taraf makale ve kaynaklar kendi lisanslarını korur; ayrıntılar ATTRIBUTIONS.txt içindedir. Bu tanıtım kaydı kaynak kodunun sahipliği veya güvenilir zaman damgası belgesi değildir.

Tanıtım kaydı tarihi: 2026-11-08.
