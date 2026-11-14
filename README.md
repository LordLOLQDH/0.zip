# 0.zip

**0.zip ist ein verschachteltes ZIP-Experiment.**

Das Archiv besteht aus mehreren ineinander verschachtelten ZIP-Ebenen. Wenn man sich Ebene für Ebene hindurch entpackt, landet man schließlich bei der untersten Ebene: Textdateien, deren Inhalt ausschließlich aus Nullen (`0`) besteht.

Der Name **0.zip** bezieht sich also auf den Inhalt ganz unten im Archiv.

## So öffnest du das Archiv

1. Lade [0.zip](https://github.com/LordLOLQDH/0.zip/raw/refs/heads/main/0.zip) herunter.
2. Entpacke die äußere ZIP-Datei.
3. Gib als Passwort **`0`** ein.
4. Im entpackten Ordner findest du die eigentliche ZIP-Datei.
5. Diese innere ZIP-Datei enthält die verschachtelten Archive, die bis zu den Textdateien aus Nullen führen.

**Wichtig:** Die äußerste ZIP-Datei ist nur eine passwortgeschützte Hülle. Sie enthält die eigentliche ZIP-Datei. Sie startet kein Programm, führt keine Befehle aus und verändert nicht selbstständig etwas am Computer. Das Passwort `0` gilt für diese äußere ZIP-Datei.

## Aufbau

```text
0.zip                  ← äußere Hülle, Passwort: 0
└── eigentliche ZIP
    └── weitere verschachtelte Archive
        └── ...
            └── Textdateien
                └── 000000000000000000000000...
```

Die Darstellung ist schematisch. Die genaue Anzahl der inneren Ebenen wird hier bewusst nicht angegeben.

## Website

Die Projektwebsite liegt in [index.html](./index.html). Sie kann über GitHub Pages veröffentlicht werden.

## Download

[0.zip herunterladen](https://github.com/LordLOLQDH/0.zip/raw/refs/heads/main/0.zip)

## Sicherheitshinweis

Die äußere ZIP-Datei dient als passwortgeschützte Hülle. Das bedeutet nicht automatisch, dass jede Datei im inneren Archiv sicher ist. Prüfe die innere ZIP-Datei und ihre Inhalte, bevor du sie weiter entpackst oder verwendest.

© 2026 Adam Kraus
