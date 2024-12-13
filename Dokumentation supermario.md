# Dokumentation: Super Mario 2D in C#

## Projektübersicht
Das Ziel dieses Projekts ist es, ein 2D-Plattformspiel ähnlich wie das klassische "Super Mario" zu entwickeln. Der Spieler steuert die Spielfigur Mario durch verschiedene Levels, sammelt Münzen, springt über Hindernisse und bekämpft Gegner. Dieses Spiel wird in C# mit der Spieleentwicklungsbibliothek MonoGame entwickelt. Das Projekt bietet die Möglichkeit, Konzepte wie Objektorientierung, Animation, Kollisionserkennung und Spiellogik zu erlernen.

Funktionen und Features

Spielsteuerung:

Bewegung nach links und rechts mit den Pfeiltasten oder A/D-Tasten.

Springen mit der Leertaste.

Spielobjekte:

Mario (Spieler): Die Hauptfigur, die der Spieler steuert.

Plattformen: Feste Objekte, auf denen Mario laufen und springen kann.

Gegner: Feinde, die Mario vermeiden oder besiegen muss.

Münzen: Sammelbare Objekte, die Punkte bringen.

Power-Ups: Objekte, die Mario spezielle Fähigkeiten verleihen (z. B. Feuerblume).

Levelsystem:

Jedes Level hat eine einzigartige Anordnung von Plattformen, Münzen und Gegnern.

Spieler kann durch ein "Level Complete"-Tor ins nächste Level wechseln.

Sound und Grafik:

Soundeffekte für Sprünge, Münzen und Kollisionen.

Animierte Sprites für Mario und Gegner (z. B. Laufanimationen).

Punkte- und Lebenssystem:

Münzen erhöhen die Punktzahl.

Mario hat eine begrenzte Anzahl von Leben, die bei Kollisionen mit Gegnern oder bei Stürzen in Lücken verloren gehen.

Hauptmenü:

Startbildschirm mit Optionen wie "Neues Spiel" und "Beenden".

Technische Details

Entwicklungsumgebung: Visual Studio mit MonoGame-Framework.

Programmiersprache: C#.

Klassenstruktur:

Game1: Die Hauptklasse, die das Spiel steuert.

Player: Enthält die Logik für Bewegung, Sprünge und Kollisionen.

Enemy: Logik für die Bewegung und das Verhalten von Gegnern.

Level: Verwaltet die Plattformen, Gegner und Münzen des aktuellen Levels.

Platform: Repräsentiert die Plattformen, auf denen Mario laufen kann.

Grafiken und Sounds:

Spritesheets für Mario, Gegner und Umgebungen.

Sounddateien im WAV- oder MP3-Format für Effekte.

Wichtige Konzepte

Kollisionserkennung:

Die Kollisionen zwischen Mario, Plattformen, Gegnern und Münzen werden durch "Bounding Boxes" (Rechtecke) überprüft.

Wenn Marios "Bounding Box" eine Münze berührt, wird die Münze entfernt und die Punktzahl erhöht.

Wenn Mario mit einem Gegner kollidiert, verliert er ein Leben.

Animation:

Mario’s Bewegungen werden durch die Wechselfolgen von Bildern (Sprites) dargestellt, sodass er beim Laufen, Springen und Stehen verschiedene Posen hat.

Ereignissteuerung:

Spieleraktionen wie das Drücken der Leertaste (Sprung) oder der Pfeiltasten (Bewegung) lösen entsprechende Aktionen im Spiel aus.

Levelwechsel:

Beim Erreichen des "Level Complete"-Tores lädt das Spiel das nächste Level.

Zukünftige Verbesserungen

Mehrere Level mit erhöhtem Schwierigkeitsgrad.

Zusätzliche Power-Ups, wie das Wachsen von Mario, wenn er einen Pilz isst.

Boss-Kämpfe am Ende von Levels.

Speicherfunktion, damit der Spieler seinen Fortschritt speichern und fortsetzen kann.


Zuerst schauen ob ich mit MonoGame klar komme
