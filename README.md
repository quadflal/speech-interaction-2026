# Evaluation eines Verifier Models mit openWakeWord

**Speech Interaction - Abschlussprojekt**

Es handelt sich um ein Uni-Projekt im Modul **Speech Interaction** (SS 2026) im Studiengang
Medieninformatik an der Hochschule der Medien Stuttgart.

**Team**
- Sophie Barke (sb324) 
- Alex Quadflieg (aq004) 
- Julia Herold (jh308) 

## Abstract

Sprachassistenten wie Amazon Alexa reagieren auf ein Wake Word, 
unabhängig davon wer es ausspricht. Dieses Projekt untersucht, 
ob ein Verifier Model in der Lage ist, zuverlässig 
zwischen der gesetzten Zielperson und fremden Sprechern zu 
unterscheiden. Dazu wurden mit dem Open-Source-Framework 
[openWakeWord](https://github.com/dscripka/openWakeWord) mehrere 
Verifier Modelle trainiert und unter verschiedenen Bedingungen 
evaluiert. Als Messgrößen dienten die False-Accept-Rate und die 
False-Reject-Rate. Die Ergebnisse zeigen, dass Verifier Modelle 
Fehlalarme sinnvoll reduzieren können, jedoch nicht als alleinige 
Sicherheitsmaßnahme geeignet sind.

## Durchführung

Die gesamte ÄImplementierung und Auswertung läuft in einem Google Colab Notbook [Linktext](Evaluation.ipynb).
Um die Ergebnisse nachzuvollziehen oder selber zu reproduzieren, muss das Notebook geöffnet und ausgeführt werden.

#### Schritte

1. Google Colab öffnen: [colab.research.google.com](https://colab.research.google.com)
2. Das Notebook aus diesem Repository laden: [Linktext](Evaluation.ipynb)
3. Google Drive einbinden (Anleitung im Notebooke enthalten)
4. Alle Zeilen von oben nach unten ausführen: `Laufzeit → Alle ausführen`

> [!NOTE]
> Das Notebook muss mit einer **T4 GPU** ausgeführt werden.  
> Einstellung: `Laufzeit → Laufzeittyp ändern → T4 GPU`

> [!NOTE]
> Bei jedem Neustart der Colab-Session müssen alle Zellen 
> erneut ausgeführt werden, da Installationen nicht 
> gespeichert bleiben.

## Dokumentation

Die vollständige Dokumentation ist hier verfügbar:

- 🇩🇪 [Dokumentation (Deutsch)](Documentation.md)
- 🇬🇧 [Documentation (English)](Documentation_English.md)


## Quellen

- dscripka, *openWakeWord* – [GitHub](https://github.com/dscripka/openWakeWord)
- Ferro Filho et al. (2024). *Implementation and Applications of 
  WakeWords Integrated with Speaker Recognition.* arXiv:2407.18985
- Du Bois et al., *Santa Barbara Corpus of Spoken American English*, 
  UC Santa Barbara / Linguistic Data Consortium

