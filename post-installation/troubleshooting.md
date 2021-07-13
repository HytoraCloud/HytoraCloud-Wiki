# ❌ Troubleshooting

Du hast Probleme bei der Installation von HytoraCloud? Nun, falls ja, dann tut es uns leid. Falls du in diesem Guide keine Lösung für dein Problem findest, würden wir dir empfehlen dem Discord-Server beizutreten oder auf GitHub ein Issue zu eröffnen.

### Problem: Java nicht gefunden

Falls dieser Fehler auftritt, hast du höchstwahrscheinlich einfach nur vergessen Java zu installieren.

#### Problembehebung

Folge [diesem Guide](../installation/installation-von-java.md) um Java zu installieren.



### Problem: screen nicht gefunden

Falls dieser Fehler auftritt, hast du vergessen `screen` auf deinem Server zu installieren.

#### Problembehebung

Führe diesen Befehl in deinem Terminal aus:

```text
$ sudo apt-get install screen
```



### Problem: NullPointerException beim Start

Der Grund für dieses Problem ist, dass du höchstwahrscheinlich den Guide nicht vollständig beachtet hast und den Auto-Updater angelassen hast.

#### Problembehebung

Öffne `local/config.json` mit dem Editor deiner Wahl und setze die Variable `autoUpdater` auf `false`.

