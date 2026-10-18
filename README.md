# S3VL02-Kommunikation
Repo zu S3 VL02: Kommunikation in verteilten Systemen

## GitHub Codespaces mit lokalem VS Code verwenden

1. Installiere [Visual Studio Code](https://code.visualstudio.com/) und die Erweiterung **GitHub Codespaces**.
2. Melde dich in VS Code bei GitHub an: Öffne das Accounts-Menü und wähle **Sign in with GitHub**.
3. Öffne [dieses Repository auf GitHub](https://github.com/DHBW-VS-Vert-Sys/S3VL02-Kommunikation), wähle **Code → Codespaces → Create codespace** und warte, bis der Codespace gestartet ist.
4. Öffne in VS Code die Befehlspalette (`Ctrl+Shift+P` unter Windows/Linux, `Cmd+Shift+P` unter macOS). Führe **Codespaces: Connect to Codespace** aus und wähle den gestarteten Codespace.
5. Arbeite wie gewohnt in VS Code. Editor, Terminal und Tools verbinden sich mit der Cloud-Umgebung des Codespaces.

# Aufgabe: REST Interaktion (s. Skript)
Docker Container starten mit:
```shell
docker run --name json-server -d -p 3000:3000 ghcr.io/r0wi/dhbw-verteilte-systeme/json-server:latest
```
Abfragen werden per `curl` getätigt:
```shell
curl "http://localhost:3000/posts"
```