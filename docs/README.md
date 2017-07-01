# Badgeprinter

Mit Hilfe eines Etikettendruckers vom Typ "Brother QL-710" oder
"Brother QL-710W" können individuelle Namensschilder gedruckt werden, die sich
die Teilnehmer einer Konferenz oder Messe auf das Hemd kleben können.

![Etikettendrucker](badgeprinter_pam95.jpg)

## Installation

Zunächst muss ein Etikettendrucker unter dem Namen ``Brother_QL-710W`` im 
Betriebssystem installiert werden.

Es werden PySide für die grafische Oberfläche und die "Python Imaging Library"
(PIL) benötigt, welche über den Paketmanager installiert werden können.

    $ sudo apt install python3-pyside python3-pil
    
In der Datei ``view.qml`` kann das Hashtag geändert werden.

Das Logo befindet sich in der Datei ``logo-small.png`` und kann dort angepasst
werden.

## Start

Das Programm kann dann gestartet werden.

    python3 badgeprinter.py

Mit Alt-F4 kann es wieder beendet werden.

## Danke

Das Projekt beruht auf dem [badgeprinter-Projekt der PiAndMore-Konferenz](https://github.com/PiAndMore/badgeprinter). Danke für die Vorarbeiten.