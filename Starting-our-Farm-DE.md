---
title: Gründung unserer Farm
description: Erstellen Sie einfache Algorithmen mit Funktionsaufrufen, die Zeichenketten als Argumente zur Steuerung eines landwirtschaftlichen Roboters benötigen. Üben Sie rechnerisches Denken anhand verschiedener Beispiele.
---

# Vorbereitung

Der Farmbot muss den Boden für die Bepflanzung vorbereiten. Benutze den Befehl `prepare_soil()`.

## Aufgaben

- Füge den Befehl `prepare_soil` in den Editor ein und drücke auf Run, um zu sehen, was passiert.

## Kode

```py title="solution.py"
prepare_soil()
```

## Konzept-Tags

- Eingeführt: `prepare_soil()`, `return_home()`, `plant()`, Was sind Funktionen, Funktionen aufrufen, Argumente übergeben, Algorithmus

---

# Bereite den Boden vor

## Aufgaben

- Bereite den Boden vor, gehe vorwärts und bereite dann mehr Erde vor

## Kode

```py title="solution.py"
prepare_soil()
move_forward()
prepare_soil()
```

## Konzept-Tags

- Benutze: `prepare_soil()`, `move_forward()`, `return_home()`, `plant()`

---

# Bereite eine Reihe vor

## Aufgaben

- Bereite drei Stück Erde hintereinander vor und kehre dann nach Hause zurück

## Kode

```py title="student.py"
prepare_soil()
move_forward()
prepare_soil()
move_forward()
prepare_soil()
return_home()
```

## Konzept-Tags

- Benutze: `move_forward()`, `prepare_soil()`, `return_home()`

---

# Bepflanzung

Der Farmbot kann mit dem Befehl `plant()` Nutzpflanzen pflanzen

## Aufgaben

- Fügen Sie dem Code die Pflanzenfunktion hinzu und drücken Sie Run. Kannst du herausfinden, wie das funktioniert?

## Kode

```py title="solution.py"
prepare_soil()
plant("tomato")
```

## Konzept-Tags

- Eingeführt: `plant()`
- Beobachtet: `prepare_soil()`

---

# Funktionen

`prepare_soil`, `move_forward` und `plant` sind Beispiele für Funktionen.
**Funktion**: Eine Funktion ist ein Befehl, der eine bestimmte Aktion ausführt, wenn er aufgerufen wird.
**Funktionsaufruf**: Ein Funktionsaufruf weist den Computer an, eine Funktion auszuführen, wobei hinter dem Namen der Funktion offene und schließende Klammern `()` verwendet werden: `move_forward()`, `prepare_soil()` sind beide Funktionsaufrufe.

## Konzept-Tags

- Eingeführt: Was sind Funktionen, Funktionen aufrufen

---

# Welche dieser Aufrufe sind Funktionsaufrufe?

- [x] `prepare_soil()`
- [x] `move_forward()`
- [ ] `"tomato"`
- [ ] `prepare_soil`

## Konzept-Tags

- Identifizieren: Funktionen aufrufen, `prepare_soil()`, `move_forward()`
- Verstehen: Funktionen aufrufen, Was sind Funktionen, Algorithmus

---

# Argumente

Eine Funktion benötigt möglicherweise zusätzliche Informationen, wenn sie aufgerufen wird. Diese können mithilfe eines Arguments bereitgestellt werden.

Im Folgenden sind `„Tomate“` und `„Aubergine“` Argumente, die der Funktion `plant()` übergeben werden.
**Argument**: Ein Argument ist ein Wert, der zwischen den Klammern hinter dem Funktionsnamen steht. Dies kann die Funktionsweise der Funktion ändern.

## Aufgaben

- Füge die Argumente zu den Pflanzenfunktionen hinzu, um eine Aubergine und eine Tomate zu pflanzen.

## Kode

```py title="solution.py"
plant("aubergine")
move_forward()
plant("tomato")
return_home()
```

## Konzept-Tags

- Eingeführt: Argumente übergeben
- Benutze: `plant()`
- Beobachtet: `move_forward()`, `return_home()`

---

# Vorbereiten und pflanzen

## Aufgaben

- Bereite den Boden vor und pflanze eine Tomate

## Kode

```py title="solution.py"
prepare_soil()
plant("tomato")
```

## Konzept-Tags

- Verwendung: `plant()`, `prepare_soil()`

---

# Was ist eine Funktion?

- [x] Eine Funktion ist ein Befehl, der eine bestimmte Aktion ausführt, wenn er aufgerufen wird.
- [ ] Funktionen sind Befehle, mit denen Sie Ihren Code von einer Sprache in eine andere konvertieren können
- [ ] Funktionen sind Wörter, hinter denen immer Klammern stehen
- [ ] Funktionen sind Befehle, die von Anführungszeichen umgeben sind und zwischen Klammern gesetzt werden können

## Konzept-Tags

- Recall: Was sind Funktionen, `move_forward () `, Algorithmus
- Verstehe: Was sind Funktionen

---

# Welcher Funktionsaufruf bringt den Farmbot voran?

- [x] move_forward()
- [ ] moveForward()
- [ ] Move_Forward()
- [ ] move_forward

## Konzept-Tags

- Recall: move_forward()

---

# Eine Reihe Kartoffeln

## Aufgaben

- Pflanzen Sie drei Kartoffeln hintereinander. Denken Sie daran, zuerst den Boden vorzubereiten.
- Kehre zur Home-Plate zurück.

## Kode

```py title="student.py"
prepare_soil()
plant("potato")
move_forward()
prepare_soil()
plant("potato")
move_forward()
prepare_soil()
plant("potato")
return_home()
```

## Konzept-Tags

- Verwendung: `prepare_soil()`, `plant()`, `return_home()`, `move_forward()`

---

# Algorithmen

Du hast in Python geschrieben, um den Farmbot zu programmieren. Im letzten Beispiel haben Sie einen **Algorithmus** erstellt, um eine Reihe von Kartoffeln zu pflanzen.
**Algorithmus**: Ein Algorithmus ist eine Reihe von Befehlen, die zur Ausführung einer bestimmten Aufgabe verwendet werden.

## Konzept-Tags

- Eingeführt: Algorithmus

---

# Was ist ein Algorithmus?

- [x] Ein Algorithmus ist eine Reihe von Befehlen, die zur Ausführung einer bestimmten Aufgabe verwendet werden.
- [ ] Ein Algorithmus ist ein Satz von Anweisungen, die mehr als einmal wiederholt werden müssen
- [ ] Ein Algorithmus ist ein beliebiges Computerprogramm
- [ ] Ein Algorithmus ist ein Befehl, der von Mr. Algo Rhythm erstellt wurde

## Konzept-Tags

- Recall: Algorithmus
- Verstehe: Algorithmus

---

# Zusammenfassung

**Funktionen**: sind Befehle, mit denen Sie eine bestimmte Aktion ausführen können, ohne viel Code schreiben zu müssen
**Funktionsaufruf**: weist den Computer an, eine Funktion auszuführen, indem hinter dem Namen der Funktion offene und schließende Klammern () verwendet werden
**Argument**: ist ein Wert, der zwischen den Klammern hinter dem Funktionsnamen steht
**Algorithmus**: ist eine Reihe von Befehlen, die zur Ausführung einer bestimmten Aufgabe verwendet werden
**prepare_soil()**: ist eine Funktion, die den Farmbot anweist, den Boden vorzubereiten
**plant()**: ist eine Funktion, die ein einzelnes Argument wie „Kartoffel“ verwendet und die angegebene Kulturpflanze pflanzt
**Sequentielle Programmierung**: Sequentielles Programmieren

## Konzept-Tags

- Erinnerung: Was sind Funktionen, Funktionen aufrufen, Argumente übergeben, Algorithmus, `prepare_soil () `, `move_forward ()`, `move_forward () `
