# VWA-Notebook

In diesem Repository ist ein Python-Programm zur Akkorderkennung zu finden, das ich zum Thema meiner VWA - "Music Information Retrieval" - entwickelt habe. Ich habe dafür als Entwicklungsumgebung die Open-Source-Software *Jupyter Notebook* gewählt. In dieser webbasierten, interaktiven Umgebung ist es möglich, Programmcode und Ausgabe in einen Beschreibungstext einzubetten. 

Das Ziel des Programms ist es, auf der Gitarre gespielte Akkorde aus drei Tönen aufzunehmen und zu verarbeiten. Das Programm soll dann ausgeben, um welchen Akkord es sich handelt, z.B. „C-Dur“ oder „D-Moll“. 

Die verschiedenen Schritte, die dafür nötig sind, werden hier schematisch dargestellt:

![Schritte zur Akkorderkennung](https://user-images.githubusercontent.com/88315284/216824755-51514ea1-1cb2-4bb2-a1d6-99ef1a21f5c0.png)

Diesen Schritten entsprechend ist die Implementierung in Jupyter Notebook in *Aufnahme*, *Erkennen der Tonhöhe* (Fourier-Transformation und Erkennen der Töne) und *Akkorderkennung* gegliedert. Zusätzlich ist der Abschnitt Synthetisierung Teil der Implementierung, worin einzelne Töne mit bestimmter Frequenz oder Akkorde erzeugt und abgespielt werden können.

Die einzelnen Schritte sind in Jupyter Notebook mit Texterklärungen versehen, wodurch der jeweilige Schritt nachvollzogen werden kann. Damit das Hauptnotebook "VWA - Jupyter Notebook.ipynb" übersichtlich bleibt, sind einige Methoden und das Verzeichnis der Akkorde in andere Notebooks ausgelagert. 
