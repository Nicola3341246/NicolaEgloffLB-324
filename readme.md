# LB 324

## Wichtiges
URL: [azurewebsites.net](nicolaeglofflbm324.azurewebsites.net) (Ich habe die F1-Serviceplan verwendet, es könnte einen kleinen Moment dauern.)
Passwort: Sicherheit123

## Aufgabe 2
Um die `pre-commit` zu verwenden müssen diese zuerst installiert werden. Nachdem alle `requirements` installiert wurden, muss folgender Kommand ausgeführt werden:
```
pre-commit install --hook-type pre-commit --hook-type pre-push
```

## Aufgabe 4
Ich habe das Passwort als eine Umgebungsvariable eingestellt. Diese Einstellung ist bei Azure im Konfigurationstab ersichtlich. Dort muss man auf `Neue Anwendungseinstellung` klicken und kann folgendes eingebe:

![grafik](https://github.com/Nicola3341246/NicolaEgloffLB-324/assets/89132258/0514d6cf-c2cd-4edc-a199-f575c1fa1eb3)

Nachher muss man nur noch speichern und die Einstellung ist getätigt.
