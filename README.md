# pctest
Public Domain-Anwendung, um RS232-Schnittstellen und Kabel zu testen. Auf realen DOS-PC (i386 oder kompatibel mit DOS) untersucht es die Hardware. In DOSBox macht es dasgleiche mit dem virtuellen Schnittstellencontroller und dem realen Kabel (z.B. an einem über USB angeschlossenen Adapter). Mit anderen DOS-Emulatoren wurde die Anwendung noch nicht getestet. Softwareseitig kompatible Schnittstellen wie RS422 und entsprechende Kabel können ebenfalls getestet werden.

Grundsätzliches / Lizenz
------------------------
Die Anwendung wird als ausführbares DOS-Programm kostenlos zur Verfügung gestellt. In dieser Form darf sie frei verwendet werden. Die Verwendung und ihre Folgen liegen allein in der Verantwortung des Benutzers. Die fehlerfreie Funktion kann vom Autor der Software und der Dokumentation nicht garantiert werden, weil er keinen Einfluß darauf hat, wie Geräte, auf denen die Anwendung eingesetzt wird, beschaffen und konfiguriert sind und weil es ihm nicht möglich ist, alle Varianten von Betriebsumgebungen zu kennen und zu prüfen. Angegebene Betriebsbedingungen beziehen sich auf Beispielkonfigurationen, die der Autor verwendet hat und können nur eine Orientierung für den Anwender sein. Bei Problemen kann der Autor unverbindlich beratend tätig werden.

Bedienung
---------
Hier noch nicht beschriebene Funktionen sind noch nicht fertig oder veraltet. Ihre Aktivierung führt zu nicht vorhersehbaren Reaktionen.
Das Menü kann mit der Funktionstaste F10 aktiviert werden. Eine Option kann durch Verschieben der Markierung mit den Pfeiltasten ausgewählt und dann mit der Eingabetaste aktiviert werden. 
Mit der Maus navigiert man durch Klicken auf eine anzuwendende Option, die ggf. sofort aktiviert wird. In der Statuszeile können kontextbezogen weitere Optionen angezeigt werden, die mit der Maus oder durch Anwendung der angezeigten Taste(nkombination) aktiviert werden können. Außerdem zeigt die Statuszeilen Zustände an, die sich bei der Ausführung von Menüopionen ergeben.
Auf dem Desktop (Bereich zwischen Hauptmenü und Statuszeile) werden Fenster zur Anzeige oder Eingabe von Daten angezeigt. Modale Fenster (Dialogfenster) werden in der Regel geschlossen, wenn man eine Schaltfläche betätigt. Ein solches Fenster muß geschlossen werden, bevor man andere Teile der Anwendung bedienen kann. Außerdem können Fenster auf ihrem Rand Symbole zum Schließen, Vergrößern, Verkleinern usw. haben. Verschieben, vergrößern und Verkleinern mancher Fenster ist auch mit der Maus durch Ziehen am Rand bzw. an der rechten unteren Ecke möglich.
Das Hauptmenü bietet die Optionen "Serielle Schnittstellen" und "Parallele Schnittstellen". Bezogen auf diese Optionen können die Untermenüs folgende Optionen enthalten:
Adressen: zeigt die I/O-Adressen der Schnittstellen an, wie sie im BIOS gespeichert sind
Das Menü Serielle Schnittstellen hat außerdem folgende nützliche Optionen:
COM-Port öffnen öffnet eine im folgenden Dialog auszuwählende serielle Schnittstelle für Ein-und Ausgaben durch die Anwendung
UART-Test       ruft die Loop-Testfunktion eines UART-Controllers auf. Wenn sie vorhanden ist und funktioniert, wird nach einiger Zeit ein positives Testergebnis angezeigt, sonst eine Fehlermeldung. Während der Test läuft, sollten keine anderen Aktionen mit der zu testenden Schnittstelle ausgeführt werden
Leitungstest    Wenn an die Schnittstelle eine Leitung angeschlossen ist, deren Sendeader mit der Empfangsader am anderen Ende verbunden ist, wird ein Datenstrom gesendet und wieder empfangen. Die empfangenen Daten werden mit den gesendeten verglichen. Der Test ist erfolgreich, wenn Gleichheit festgestellt wird.

Anwendungserfahrung
-------------------
Die beschriebenen Tests konnten bisher mit folgenden Anwendungsumgebungen erfolgreich durchgeführt werden:
- IBM-PC oder kompatibler mit i386-CPU oder kompatibler und MS-DOS
- verschiedene mobile und immobile PC mit Linux und DOSBox
- Raspberry Pi mit Linux und DOSBox

Weitere getestete Konfigurationen sind im Info-Dialog der Anwendung beschrieben.
