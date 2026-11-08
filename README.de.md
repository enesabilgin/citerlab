# CiterLab
[Türkçe](README.md) · [English](README.en.md) · [Deutsch](README.de.md) · [العربية](README.ar.md)

**Vielseitiges akademisches Softwarepaket**

CiterLab ist eine Windows-Desktopanwendung für Quellenarbeit, ein persönliches Zitatarchiv, statistische Analysen und Dokumentwerkzeuge.

Dieses Repository ist die offizielle Produktvorstellung von CiterLab. Es enthält weder den Quellcode der Anwendung noch ein ausführbares Installationspaket.

Die Veröffentlichung wird vorbereitet. Aktuelle Downloads und Verkaufsinformationen finden Sie auf der offiziellen Website.

![CiterLab](images/og.png)

## Vier echte Arbeitsbeispiele

**28 Tab-Typen und 1 Dialog zur VCF-Konvertierung: insgesamt 29 Werkzeuge.**

Jedes Werkzeug wird mit seinem Anwendungssymbol und einer echten Arbeitsansicht gezeigt. Meine Projekte gehört zur Übersicht; das VCF-Werkzeug öffnet einen eigenen Dialog.

Die Bildschirmfotos zeigen die türkische Oberfläche mit dem tatsächlichen Anwendungsthema bei 125 % Windows-Skalierung. Demonstrationsdaten und Rechenbeispiele sind keine Forschungsergebnisse. Bewerten Sie Ergebnisse zusammen mit Daten, Methode und Quellenabdeckung.

<table>
<tr>
<td><a href="#module-excel_analiz"><img src="images/gallery/excel_analiz.webp" alt="Berechnete ANOVA-Ergebnisse im Arbeitsbereich für quantitative Analyse von CiterLab" width="360"></a><br><a href="#module-excel_analiz"><strong>Quantitative Analyse</strong></a></td>
<td><a href="#module-bib"><img src="images/gallery/bib.webp" alt="Publikationssuchergebnisse und Quellenangaben im Literaturrecherche-Tab von CiterLab" width="360"></a><br><a href="#module-bib"><strong>Literaturrecherche</strong></a></td>
</tr>
<tr>
<td><a href="#module-bibliometric"><img src="images/gallery/bibliometric.webp" alt="Aus Publikationsdaten berechnete Ergebnisse in der bibliometrischen Analyse von CiterLab" width="360"></a><br><a href="#module-bibliometric"><strong>Bibliometrische Analyse</strong></a></td>
<td><a href="#module-calc"><img src="images/gallery/calc.webp" alt="Die im Arbeitsbereich Graphen und Geometrie von CiterLab gezeichnete Exponentialfunktion e hoch x" width="360"></a><br><a href="#module-calc"><strong>Graphen und Geometrie</strong></a></td>
</tr>
</table>

<a id="tool-overview"></a>

## Alle Werkzeuge auf einen Blick

| Symbol | Werkzeug | Besondere Funktionen |
| --- | --- | --- |
| <img src="images/gallery/icon-excel_analiz.png" alt="" width="32" height="32"> | [Quantitative Analyse](#module-excel_analiz) | Gruppen mit ANOVA vergleichen<br>Variablenrollen klar festlegen<br>Ergebnisse in den Bericht übernehmen |
| <img src="images/gallery/icon-qda.png" alt="" width="32" height="32"> | [Qualitative Analyse](#module-qda) | Textpassagen direkt codieren<br>Quellen und Codes gemeinsam sehen<br>Themen mit Matrizen untersuchen |
| <img src="images/gallery/icon-bib.png" alt="" width="32" height="32"> | [Literaturrecherche](#module-bib) | Publikationen in einer Liste prüfen<br>Zu Originalabstracts wechseln<br>Suchergebnisse exportieren |
| <img src="images/gallery/icon-bibliometric.png" alt="" width="32" height="32"> | [Bibliometrische Analyse](#module-bibliometric) | Publikationen nach Jahren betrachten<br>Autoren und Quellen vergleichen<br>Datenqualität prüfen |
| <img src="images/gallery/icon-calc.png" alt="" width="32" height="32"> | [Graphen und Geometrie](#module-calc) | Die eˣ-Kurve sehen<br>Ableitungen und Integrale erkunden<br>Geometrische Objekte konstruieren |
| <img src="images/gallery/icon-desing.png" alt="" width="32" height="32"> | [Forschungsdesign](#module-desing) | Designs mit Erläuterungen erkunden<br>Variablenrollen planen<br>Analyseoptionen abwägen |
| <img src="images/gallery/icon-concept_library.png" alt="" width="32" height="32"> | [Begriffsbibliothek](#module-concept_library) | Definitionen mit Quellen lesen<br>Verwandten Begriffen folgen<br>Belegte Inhalte in Texte übernehmen |
| <img src="images/gallery/icon-databank.png" alt="" width="32" height="32"> | [Datenbank für Forschungsdaten](#module-databank) | Datenquellen erkunden<br>Lokale Dateien importieren<br>Tabellen filtern und prüfen |
| <img src="images/gallery/icon-cheatsheets.png" alt="" width="32" height="32"> | [Nachschlagehilfen](#module-cheatsheets) | Schnell zwischen Themen wechseln<br>Formeln mit Beispielen betrachten<br>Leitfäden als PDF oder DOCX exportieren |
| <img src="images/gallery/icon-library.png" alt="" width="32" height="32"> | [Quellenarchiv](#module-library) | Das Archiv durchsuchen<br>Quellenangaben prüfen<br>Gespeicherte Dokumente wieder öffnen |
| <img src="images/gallery/icon-bibliography_check.png" alt="" width="32" height="32"> | [Zitationsprüfung](#module-bibliography_check) | Zitate und Literaturangaben abgleichen<br>Zuordnungen gemeinsam prüfen<br>Den Prüfbericht öffnen |
| <img src="images/gallery/icon-lo_docx.png" alt="" width="32" height="32"> | [DOCX](#module-lo_docx) | Texte formatieren<br>Tabellen und Bilder ergänzen<br>Im Arbeitsbereich bearbeiten |
| <img src="images/gallery/icon-lo_xlsx.png" alt="" width="32" height="32"> | [XLSX](#module-lo_xlsx) | Zellen direkt bearbeiten<br>Mit Formeln rechnen<br>Arbeitsmappen speichern |
| <img src="images/gallery/icon-lo_pptx.png" alt="" width="32" height="32"> | [Präsentation](#module-lo_pptx) | Folien bearbeiten<br>Texte und Bilder verbinden<br>Präsentationen speichern |
| <img src="images/gallery/icon-lo_draw.png" alt="" width="32" height="32"> | [Zeichnungsdokument](#module-lo_draw) | Mit Formen erklären<br>Texte und Bilder anordnen<br>Zeichnungsdokumente speichern |
| <img src="images/gallery/icon-lo_math.png" alt="" width="32" height="32"> | [Formeleditor](#module-lo_math) | Formeln im eigenen Tab bearbeiten<br>Mathematische Notation gestalten<br>Formeldokumente speichern |
| <img src="images/gallery/icon-lo_base.png" alt="" width="32" height="32"> | [Datenbankeditor](#module-lo_base) | Datenbankdokumente öffnen<br>Im eigenen Tab arbeiten<br>Dokumente speichern |
| <img src="images/gallery/icon-text.png" alt="" width="32" height="32"> | [Texteditor](#module-text) | Direkt Notizen schreiben<br>Klartext bearbeiten<br>Texte als Datei speichern |
| <img src="images/gallery/icon-tex.png" alt="" width="32" height="32"> | [TeX Studio](#module-tex) | LaTeX-Quelltext bearbeiten<br>Compiler-Ausgabe prüfen<br>Mit Dokumentvorschau arbeiten |
| <img src="images/gallery/icon-pdf.png" alt="" width="32" height="32"> | [PDF-Editor](#module-pdf) | Zwischen Seiten navigieren<br>Dokumenttext durchsuchen<br>Die Leseansicht anpassen |
| <img src="images/gallery/icon-paint.png" alt="" width="32" height="32"> | [Skizzenbuch](#module-paint) | Frei zeichnen<br>Farben und Stifte wählen<br>Visuelle Entwürfe erstellen |
| <img src="images/gallery/icon-epub.png" alt="" width="32" height="32"> | [EPUB-Reader](#module-epub) | Über das Inhaltsverzeichnis navigieren<br>Im Buch suchen<br>Die Schriftgröße anpassen |
| <img src="images/gallery/icon-web.png" alt="" width="32" height="32"> | [Webbrowser](#module-web) | Seiten per Adresse öffnen<br>Zwischen Seiten navigieren<br>Quellen nebeneinander prüfen |
| <img src="images/gallery/icon-media.png" alt="" width="32" height="32"> | [Mediaplayer](#module-media) | Audio und Video öffnen<br>Auf der Zeitleiste navigieren<br>Die Wiedergabe steuern |
| <img src="images/gallery/icon-automation.png" alt="" width="32" height="32"> | [Dokumentwerkzeuge](#module-automation) | Dateien in einer Liste sammeln<br>Eine Dokumentaktion wählen<br>Den Verarbeitungsstatus verfolgen |
| <img src="images/gallery/icon-mini_calc.png" alt="" width="32" height="32"> | [Taschenrechner](#module-mini_calc) | Grundrechenarten ausführen<br>Ergebnisse sofort sehen<br>Den Rechenverlauf prüfen |
| <img src="images/gallery/icon-signature.png" alt="" width="32" height="32"> | [Signaturverwaltung](#module-signature) | Eine Unterschrift zeichnen<br>Das Bild zuschneiden und bearbeiten<br>Die transparente Vorschau prüfen |
| <img src="images/gallery/icon-projects.png" alt="" width="32" height="32"> | [Meine Projekte](#module-projects) | Projekte in einer Liste sehen<br>Zu Dokumenten zurückkehren<br>Projektnotizen zusammenhalten |
| <img src="images/gallery/icon-contacts_vcf.png" alt="" width="32" height="32"> | [Excel → Kontakte (VCF)](#module-contacts_vcf) | Eine Kontakttabelle wählen<br>Felder eindeutig zuordnen<br>Eine VCF-Datei erstellen |

## Die Werkzeuge im Detail

<a id="module-excel_analiz"></a>

<details>
<summary><img src="images/gallery/icon-excel_analiz.png" alt="" width="24" height="24"> <strong>Quantitative Analyse</strong> · Tab</summary>

### Von Daten zu Erkenntnissen

Wählen Sie Variablen, führen Sie eine passende Analyse aus und prüfen Sie die berechneten Ergebnisse im Bericht.

- Gruppen mit ANOVA vergleichen
- Variablenrollen klar festlegen
- Ergebnisse in den Bericht übernehmen

<img src="images/gallery/excel_analiz.webp" alt="Berechnete ANOVA-Ergebnisse im Arbeitsbereich für quantitative Analyse von CiterLab" width="1100">

[Vollständiges Bildschirmfoto öffnen](images/gallery/excel_analiz.webp) · [Zur Werkzeugliste](#tool-overview)

</details>

<a id="module-qda"></a>

<details>
<summary><img src="images/gallery/icon-qda.png" alt="" width="24" height="24"> <strong>Qualitative Analyse</strong> · Tab</summary>

### Bedeutung sichtbar machen

Codieren Sie Quelltexte und untersuchen Sie ausgewählte Passagen, Notizen und Beziehungen zwischen Themen.

- Textpassagen direkt codieren
- Quellen und Codes gemeinsam sehen
- Themen mit Matrizen untersuchen

<img src="images/gallery/qda.webp" alt="Quelltext, Codebaum und codierte Passagen in der qualitativen Analyse von CiterLab" width="1100">

[Vollständiges Bildschirmfoto öffnen](images/gallery/qda.webp) · [Zur Werkzeugliste](#tool-overview)

</details>

<a id="module-bib"></a>

<details>
<summary><img src="images/gallery/icon-bib.png" alt="" width="24" height="24"> <strong>Literaturrecherche</strong> · Tab</summary>

### Der Forschungsfrage folgen

Durchsuchen Sie wissenschaftliche Quellen und prüfen Sie Publikationen, Originalabstracts und ausgewählte Sätze in geordneten Ansichten.

- Publikationen in einer Liste prüfen
- Zu Originalabstracts wechseln
- Suchergebnisse exportieren

<img src="images/gallery/bib.webp" alt="Publikationssuchergebnisse und Quellenangaben im Literaturrecherche-Tab von CiterLab" width="1100">

[Vollständiges Bildschirmfoto öffnen](images/gallery/bib.webp) · [Zur Werkzeugliste](#tool-overview)

</details>

<a id="module-bibliometric"></a>

<details>
<summary><img src="images/gallery/icon-bibliometric.png" alt="" width="24" height="24"> <strong>Bibliometrische Analyse</strong> · Tab</summary>

### Muster in der Literatur entdecken

Analysieren Sie Jahre, Autoren, Quellen und Begriffe in Publikationsdaten, um Ihr Forschungsfeld genauer zu verstehen.

- Publikationen nach Jahren betrachten
- Autoren und Quellen vergleichen
- Datenqualität prüfen

<img src="images/gallery/bibliometric.webp" alt="Aus Publikationsdaten berechnete Ergebnisse in der bibliometrischen Analyse von CiterLab" width="1100">

[Vollständiges Bildschirmfoto öffnen](images/gallery/bibliometric.webp) · [Zur Werkzeugliste](#tool-overview)

</details>

<a id="module-calc"></a>

<details>
<summary><img src="images/gallery/icon-calc.png" alt="" width="24" height="24"> <strong>Graphen und Geometrie</strong> · Tab</summary>

### Mathematik zeichnend entdecken

Zeichnen Sie Funktionen, fügen Sie mathematische Objekte hinzu und erkunden Sie Geometrie im selben Koordinatensystem.

- Die eˣ-Kurve sehen
- Ableitungen und Integrale erkunden
- Geometrische Objekte konstruieren

<img src="images/gallery/calc.webp" alt="Die im Arbeitsbereich Graphen und Geometrie von CiterLab gezeichnete Exponentialfunktion e hoch x" width="1100">

[Vollständiges Bildschirmfoto öffnen](images/gallery/calc.webp) · [Zur Werkzeugliste](#tool-overview)

</details>

<a id="module-desing"></a>

<details>
<summary><img src="images/gallery/icon-desing.png" alt="" width="24" height="24"> <strong>Forschungsdesign</strong> · Tab</summary>

### Von der Frage zur Methode

Erkunden Sie Forschungsdesigns und ordnen Sie Variablen und Analyseoptionen in einem klaren Plan.

- Designs mit Erläuterungen erkunden
- Variablenrollen planen
- Analyseoptionen abwägen

<img src="images/gallery/desing.webp" alt="Ausgewähltes Forschungsdesign mit methodischer Erläuterung im Forschungsdesign-Bereich von CiterLab" width="1100">

[Vollständiges Bildschirmfoto öffnen](images/gallery/desing.webp) · [Zur Werkzeugliste](#tool-overview)

</details>

<a id="module-concept_library"></a>

<details>
<summary><img src="images/gallery/icon-concept_library.png" alt="" width="24" height="24"> <strong>Begriffsbibliothek</strong> · Tab</summary>

### Begriffe im Kontext verstehen

Entdecken Sie Begriffe mit Definitionen und Quellen, folgen Sie verwandten Begriffen und übernehmen Sie belegte Inhalte in Ihren Text.

- Definitionen mit Quellen lesen
- Verwandten Begriffen folgen
- Belegte Inhalte in Texte übernehmen

<img src="images/gallery/concept_library.webp" alt="Definition, verwandte Begriffe und Quellen in der Begriffsbibliothek von CiterLab" width="1100">

[Vollständiges Bildschirmfoto öffnen](images/gallery/concept_library.webp) · [Zur Werkzeugliste](#tool-overview)

</details>

<a id="module-databank"></a>

<details>
<summary><img src="images/gallery/icon-databank.png" alt="" width="24" height="24"> <strong>Datenbank für Forschungsdaten</strong> · Tab</summary>

### Daten mit Forschung verbinden

Erkunden Sie Datenquellen oder öffnen Sie eine lokale Datei und filtern Sie Tabellen nach den benötigten Beobachtungen.

- Datenquellen erkunden
- Lokale Dateien importieren
- Tabellen filtern und prüfen

<img src="images/gallery/databank.webp" alt="Datentabelle und Filterwerkzeuge im Forschungsdaten-Bereich von CiterLab" width="1100">

[Vollständiges Bildschirmfoto öffnen](images/gallery/databank.webp) · [Zur Werkzeugliste](#tool-overview)

</details>

<a id="module-cheatsheets"></a>

<details>
<summary><img src="images/gallery/icon-cheatsheets.png" alt="" width="24" height="24"> <strong>Nachschlagehilfen</strong> · Tab</summary>

### Wissen schnell zur Hand

Lesen Sie Themenleitfäden mit Formeln und Beispielen, durchsuchen Sie Inhalte und exportieren Sie den gewählten Leitfaden.

- Schnell zwischen Themen wechseln
- Formeln mit Beispielen betrachten
- Leitfäden als PDF oder DOCX exportieren

<img src="images/gallery/cheatsheets.webp" alt="Themenliste und Leitfadenseite mit Formeln in den Nachschlagehilfen von CiterLab" width="1100">

[Vollständiges Bildschirmfoto öffnen](images/gallery/cheatsheets.webp) · [Zur Werkzeugliste](#tool-overview)

</details>

<a id="module-library"></a>

<details>
<summary><img src="images/gallery/icon-library.png" alt="" width="24" height="24"> <strong>Quellenarchiv</strong> · Tab</summary>

### Quellen wiederfinden

Durchsuchen Sie archivierte Publikationen und Dokumente und prüfen Sie Quellenangaben und gespeicherte Inhalte zu Ihrer Forschung.

- Das Archiv durchsuchen
- Quellenangaben prüfen
- Gespeicherte Dokumente wieder öffnen

<img src="images/gallery/library.webp" alt="Suchergebnisse und ausgewählter Quelleneintrag im Quellenarchiv von CiterLab" width="1100">

[Vollständiges Bildschirmfoto öffnen](images/gallery/library.webp) · [Zur Werkzeugliste](#tool-overview)

</details>

<a id="module-bibliography_check"></a>

<details>
<summary><img src="images/gallery/icon-bibliography_check.png" alt="" width="24" height="24"> <strong>Zitationsprüfung</strong> · Tab</summary>

### Zitationsspuren prüfen

Prüfen Sie die Zuordnung von Zitaten und Literaturverzeichniseinträgen; der Bericht zeigt Treffer und zu prüfende Stellen.

- Zitate und Literaturangaben abgleichen
- Zuordnungen gemeinsam prüfen
- Den Prüfbericht öffnen

<img src="images/gallery/bibliography_check.webp" alt="Ergebnisse des Abgleichs von Zitaten und Literaturverzeichnis in der Zitationsprüfung von CiterLab" width="1100">

[Vollständiges Bildschirmfoto öffnen](images/gallery/bibliography_check.webp) · [Zur Werkzeugliste](#tool-overview)

</details>

<a id="module-lo_docx"></a>

<details>
<summary><img src="images/gallery/icon-lo_docx.png" alt="" width="24" height="24"> <strong>DOCX</strong> · Tab</summary>

### Erkenntnisse in Worte fassen

Schreiben Sie Ihr Forschungsdokument im Arbeitsbereich, gestalten Sie es mit Überschriften, Tabellen und Bildern und speichern Sie es.

- Texte formatieren
- Tabellen und Bilder ergänzen
- Im Arbeitsbereich bearbeiten

<img src="images/gallery/lo_docx.webp" alt="Ein formatiertes DOCX-Forschungsdokument, geöffnet in CiterLab" width="1100">

[Vollständiges Bildschirmfoto öffnen](images/gallery/lo_docx.webp) · [Zur Werkzeugliste](#tool-overview)

</details>

<a id="module-lo_xlsx"></a>

<details>
<summary><img src="images/gallery/icon-lo_xlsx.png" alt="" width="24" height="24"> <strong>XLSX</strong> · Tab</summary>

### Daten übersichtlich ordnen

Öffnen Sie Ihre Tabelle im Arbeitsbereich und bearbeiten Sie Zellen, Formeln und Tabellenlayout direkt.

- Zellen direkt bearbeiten
- Mit Formeln rechnen
- Arbeitsmappen speichern

<img src="images/gallery/lo_xlsx.webp" alt="Eine mit Daten gefüllte XLSX-Tabelle, geöffnet in CiterLab" width="1100">

[Vollständiges Bildschirmfoto öffnen](images/gallery/lo_xlsx.webp) · [Zur Werkzeugliste](#tool-overview)

</details>

<a id="module-lo_pptx"></a>

<details>
<summary><img src="images/gallery/icon-lo_pptx.png" alt="" width="24" height="24"> <strong>Präsentation</strong> · Tab</summary>

### Forschung anschaulich präsentieren

Bearbeiten Sie Folien im Arbeitsbereich und erzählen Sie Ihre Forschung mit Texten und Bildern.

- Folien bearbeiten
- Texte und Bilder verbinden
- Präsentationen speichern

<img src="images/gallery/lo_pptx.webp" alt="Eine Forschungsfolie im Präsentationseditor von CiterLab" width="1100">

[Vollständiges Bildschirmfoto öffnen](images/gallery/lo_pptx.webp) · [Zur Werkzeugliste](#tool-overview)

</details>

<a id="module-lo_draw"></a>

<details>
<summary><img src="images/gallery/icon-lo_draw.png" alt="" width="24" height="24"> <strong>Zeichnungsdokument</strong> · Tab</summary>

### Ideen visuell ordnen

Verbinden Sie Formen, Texte und Bilder in einem Zeichnungsdokument zu anschaulichen Erklärungen.

- Mit Formen erklären
- Texte und Bilder anordnen
- Zeichnungsdokumente speichern

<img src="images/gallery/lo_draw.webp" alt="Eine Zeichnungsseite mit Formen und Text im Zeichnungseditor von CiterLab" width="1100">

[Vollständiges Bildschirmfoto öffnen](images/gallery/lo_draw.webp) · [Zur Werkzeugliste](#tool-overview)

</details>

<a id="module-lo_math"></a>

<details>
<summary><img src="images/gallery/icon-lo_math.png" alt="" width="24" height="24"> <strong>Formeleditor</strong> · Tab</summary>

### Mathematische Ausdrücke gestalten

Erstellen Sie ein Formeldokument in einem eigenen Tab, bearbeiten Sie die mathematische Notation und speichern Sie Ihre Arbeit.

- Formeln im eigenen Tab bearbeiten
- Mathematische Notation gestalten
- Formeldokumente speichern

<img src="images/gallery/lo_math.webp" alt="Ein mathematischer Ausdruck im Formeleditor von CiterLab" width="1100">

[Vollständiges Bildschirmfoto öffnen](images/gallery/lo_math.webp) · [Zur Werkzeugliste](#tool-overview)

</details>

<a id="module-lo_base"></a>

<details>
<summary><img src="images/gallery/icon-lo_base.png" alt="" width="24" height="24"> <strong>Datenbankeditor</strong> · Tab</summary>

### Platz für Datenbankarbeit

Öffnen Sie Datenbankdokumente in einem eigenen Tab und arbeiten Sie mit dem Datenbankeditor.

- Datenbankdokumente öffnen
- Im eigenen Tab arbeiten
- Dokumente speichern

<img src="images/gallery/lo_base.webp" alt="Der Editor für Datenbankdokumente in CiterLab" width="1100">

[Vollständiges Bildschirmfoto öffnen](images/gallery/lo_base.webp) · [Zur Werkzeugliste](#tool-overview)

</details>

<a id="module-text"></a>

<details>
<summary><img src="images/gallery/icon-text.png" alt="" width="24" height="24"> <strong>Texteditor</strong> · Tab</summary>

### Gedanken sofort festhalten

Schreiben und bearbeiten Sie einfache Textnotizen in einem Dokument-Tab und speichern Sie sie als Datei.

- Direkt Notizen schreiben
- Klartext bearbeiten
- Texte als Datei speichern

<img src="images/gallery/text.webp" alt="Forschungsnotizen im Texteditor-Tab von CiterLab" width="1100">

[Vollständiges Bildschirmfoto öffnen](images/gallery/text.webp) · [Zur Werkzeugliste](#tool-overview)

</details>

<a id="module-tex"></a>

<details>
<summary><img src="images/gallery/icon-tex.png" alt="" width="24" height="24"> <strong>TeX Studio</strong> · Tab</summary>

### Wissenschaftliche Texte sorgfältig setzen

Bearbeiten Sie TeX- und LaTeX-Quelltext, prüfen Sie die Compiler-Ausgabe und verfeinern Sie Ihre Arbeit mit der Dokumentvorschau.

- LaTeX-Quelltext bearbeiten
- Compiler-Ausgabe prüfen
- Mit Dokumentvorschau arbeiten

<img src="images/gallery/tex.webp" alt="LaTeX-Quelltext und Dokumentvorschau in CiterLab TeX Studio" width="1100">

[Vollständiges Bildschirmfoto öffnen](images/gallery/tex.webp) · [Zur Werkzeugliste](#tool-overview)

</details>

<a id="module-pdf"></a>

<details>
<summary><img src="images/gallery/icon-pdf.png" alt="" width="24" height="24"> <strong>PDF-Editor</strong> · Tab</summary>

### Lesen mit Forschung verbinden

Navigieren Sie durch PDF-Seiten, suchen Sie Text und prüfen Sie Dokumente im selben Arbeitsbereich wie Ihre Forschungswerkzeuge.

- Zwischen Seiten navigieren
- Dokumenttext durchsuchen
- Die Leseansicht anpassen

<img src="images/gallery/pdf.webp" alt="Ein Forschungsdokument mit Seitenwerkzeugen im PDF-Arbeitsbereich von CiterLab" width="1100">

[Vollständiges Bildschirmfoto öffnen](images/gallery/pdf.webp) · [Zur Werkzeugliste](#tool-overview)

</details>

<a id="module-paint"></a>

<details>
<summary><img src="images/gallery/icon-paint.png" alt="" width="24" height="24"> <strong>Skizzenbuch</strong> · Tab</summary>

### Die erste Idee zeichnen

Skizzieren Sie frei, denken Sie in Farben und verwandeln Sie Ihre Forschungsidee in einen visuellen Entwurf.

- Frei zeichnen
- Farben und Stifte wählen
- Visuelle Entwürfe erstellen

<img src="images/gallery/paint.webp" alt="Zeichenfläche und Stiftwerkzeuge im Skizzenbuch von CiterLab" width="1100">

[Vollständiges Bildschirmfoto öffnen](images/gallery/paint.webp) · [Zur Werkzeugliste](#tool-overview)

</details>

<a id="module-epub"></a>

<details>
<summary><img src="images/gallery/icon-epub.png" alt="" width="24" height="24"> <strong>EPUB-Reader</strong> · Tab</summary>

### Bücher bequem erschließen

Öffnen Sie ein EPUB-Buch und finden Sie benötigte Abschnitte über Inhaltsverzeichnis, Textsuche und Leseeinstellungen.

- Über das Inhaltsverzeichnis navigieren
- Im Buch suchen
- Die Schriftgröße anpassen

<img src="images/gallery/epub.webp" alt="Buchkapitel und Inhaltsverzeichnis im EPUB-Reader von CiterLab" width="1100">

[Vollständiges Bildschirmfoto öffnen](images/gallery/epub.webp) · [Zur Werkzeugliste](#tool-overview)

</details>

<a id="module-web"></a>

<details>
<summary><img src="images/gallery/icon-web.png" alt="" width="24" height="24"> <strong>Webbrowser</strong> · Tab</summary>

### Webrecherche in Reichweite

Öffnen Sie Webseiten in einem Arbeitsbereich-Tab und prüfen Sie Quellen neben Ihren Dokumenten.

- Seiten per Adresse öffnen
- Zwischen Seiten navigieren
- Quellen nebeneinander prüfen

<img src="images/gallery/web.webp" alt="Eine Rechercheseite im Webbrowser-Tab von CiterLab" width="1100">

[Vollständiges Bildschirmfoto öffnen](images/gallery/web.webp) · [Zur Werkzeugliste](#tool-overview)

</details>

<a id="module-media"></a>

<details>
<summary><img src="images/gallery/icon-media.png" alt="" width="24" height="24"> <strong>Mediaplayer</strong> · Tab</summary>

### Ton und Video untersuchen

Öffnen Sie Audio oder Video im Arbeitsbereich und untersuchen Sie relevante Abschnitte mit Wiedergabesteuerung und Zeitleiste.

- Audio und Video öffnen
- Auf der Zeitleiste navigieren
- Die Wiedergabe steuern

<img src="images/gallery/media.webp" alt="Video mit Wiedergabezeitleiste im Mediaplayer von CiterLab" width="1100">

[Vollständiges Bildschirmfoto öffnen](images/gallery/media.webp) · [Zur Werkzeugliste](#tool-overview)

</details>

<a id="module-automation"></a>

<details>
<summary><img src="images/gallery/icon-automation.png" alt="" width="24" height="24"> <strong>Dokumentwerkzeuge</strong> · Tab</summary>

### Dokumentaufgaben zusammenführen

Fügen Sie Dateien einer Verarbeitungsliste hinzu und wählen Sie Optionen zum Konvertieren, Zusammenführen oder Aufteilen.

- Dateien in einer Liste sammeln
- Eine Dokumentaktion wählen
- Den Verarbeitungsstatus verfolgen

<img src="images/gallery/automation.webp" alt="Dateiliste und Verarbeitungsoptionen in den Dokumentwerkzeugen von CiterLab" width="1100">

[Vollständiges Bildschirmfoto öffnen](images/gallery/automation.webp) · [Zur Werkzeugliste](#tool-overview)

</details>

<a id="module-mini_calc"></a>

<details>
<summary><img src="images/gallery/icon-mini_calc.png" alt="" width="24" height="24"> <strong>Taschenrechner</strong> · Tab</summary>

### Kleine Rechnungen schnell lösen

Erledigen Sie alltägliche Berechnungen und prüfen Sie frühere Schritte im Rechenverlauf.

- Grundrechenarten ausführen
- Ergebnisse sofort sehen
- Den Rechenverlauf prüfen

<img src="images/gallery/mini_calc.webp" alt="Zahlenergebnis und Rechenverlauf im Taschenrechner von CiterLab" width="1100">

[Vollständiges Bildschirmfoto öffnen](images/gallery/mini_calc.webp) · [Zur Werkzeugliste](#tool-overview)

</details>

<a id="module-signature"></a>

<details>
<summary><img src="images/gallery/icon-signature.png" alt="" width="24" height="24"> <strong>Signaturverwaltung</strong> · Tab</summary>

### Ein Unterschriftsbild vorbereiten

Zeichnen Sie eine Unterschrift oder bearbeiten Sie ein Unterschriftsbild und bereiten Sie es mit Vorschau zum Einfügen vor.

- Eine Unterschrift zeichnen
- Das Bild zuschneiden und bearbeiten
- Die transparente Vorschau prüfen

<img src="images/gallery/signature.webp" alt="Gezeichnete Beispielunterschrift und Bildvorschau in der Signaturverwaltung von CiterLab" width="1100">

[Vollständiges Bildschirmfoto öffnen](images/gallery/signature.webp) · [Zur Werkzeugliste](#tool-overview)

</details>

<a id="module-projects"></a>

<details>
<summary><img src="images/gallery/icon-projects.png" alt="" width="24" height="24"> <strong>Meine Projekte</strong> · Tab</summary>

### Die Forschung wieder aufnehmen

Sehen Sie Arbeitsbereiche und Projektdokumente gemeinsam und setzen Sie Ihre Arbeit mit Projektdetails und Notizen fort.

- Projekte in einer Liste sehen
- Zu Dokumenten zurückkehren
- Projektnotizen zusammenhalten

<img src="images/gallery/projects.webp" alt="Projektliste, Dokumente und Projektdetails im Bereich Meine Projekte von CiterLab" width="1100">

[Vollständiges Bildschirmfoto öffnen](images/gallery/projects.webp) · [Zur Werkzeugliste](#tool-overview)

</details>

<a id="module-contacts_vcf"></a>

<details>
<summary><img src="images/gallery/icon-contacts_vcf.png" alt="" width="24" height="24"> <strong>Excel → Kontakte (VCF)</strong> · Dialog</summary>

### Von der Tabelle zu Kontakten

Ordnen Sie Kontaktfelder einer Excel-Tabelle zu und erstellen Sie eine VCF-Datei für den Import in ein Adressbuch.

- Eine Kontakttabelle wählen
- Felder eindeutig zuordnen
- Eine VCF-Datei erstellen

<img src="images/gallery/contacts_vcf.webp" alt="Zuordnung der Kontaktfelder im Excel-zu-VCF-Dialog von CiterLab" width="1100">

[Vollständiges Bildschirmfoto öffnen](images/gallery/contacts_vcf.webp) · [Zur Werkzeugliste](#tool-overview)

</details>

## Bildquellen und Kontext

Die Quellenbeschreibungen und Hinweise der bisherigen Produktvorstellung bleiben unten erhalten. Artikellizenz und Bildnachweise stehen in [ATTRIBUTIONS.txt](ATTRIBUTIONS.txt).

- [**Diagrammstudio**](images/screen-charts.png) — In der echten Anwendung aus synthetischen Beispieldaten erzeugte Diagramme; keine Forschungsergebnisse.
- [**Begriffsatlas**](images/screen-concepts.png) — Quellenangaben und Hinweise zum Prüfstatus der Übersetzungen bleiben sichtbar.
- [**Literaturprüfung**](images/screen-citations.png) — Innenseite eines echten Open-Access-Artikels. Titelseite ausgeblendet, Filter für zugeordnete Zitate gewählt. Die Ergebnisse sind algorithmische Zuordnungen und keine Prüfung der Originalveröffentlichungen.

## Umfang und Nutzung

Lokale Werkzeuge und heruntergeladene Bibliotheks- und Modellkomponenten funktionieren offline. Erstaktivierung, Downloads und Online-Quellenabfragen benötigen eine Verbindung. Unterstützte Dateien und Analysen hängen vom Vorgang ab. Zuordnungen, statistische Annahmen und KI-Ausgaben müssen überprüft werden.

## Offizielle Links

- [Website](https://citerlab.com)
- Support: [info@citerlab.com](mailto:info@citerlab.com)

## Rechte und Bildquellen

NOTICE.md enthält den Rechtehinweis zu eigenem CiterLab-Material. Für fremde Artikel und Quellen gelten deren Lizenzen; siehe ATTRIBUTIONS.txt. Diese Vorstellung ist kein Nachweis des Quellcodeeigentums oder vertrauenswürdiger Zeitstempel.

Datum der Produktvorstellung: 2026-11-08.
