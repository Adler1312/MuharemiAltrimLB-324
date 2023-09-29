# LB 324

## Aufgabe 2
Schritt 1: Installation von pre-commit

pip install pre-commit

Schritt 2: Überprüfung der Installation

pre-commit --version

Schritt 3: Konfigurationsdatei

.pre-commit-config.yaml Datei muss erstellt werden im Ordner

Schritt 4: Hooks installieren

pre-commit install

Schritt 5: Hooks manuell ausführen

pre-commit run --all-files

## Aufgabe 4
muharemialtrimlb-324.azurewebsites.net

Schritt 1: Ressourcengruppe und App Service erstellen

Logge dich in dein Azure-Konto ein und erstelle eine Ressourcengruppe.

Klicke auf "App Services" in deinem Azure-Portal.

Schritt 2: Anwendungs-Einstellungen konfigurieren

Wähle deine erstellte App Service-Instanz aus.

Klicke auf "Konfiguration" unter den Einstellungen.

Gehe zu "Anwendungs-Einstellungen" und klicke auf "Hinzufügen".

Füge das geheime Passwort aus deiner .env-Datei als Schlüssel-Wert-Paar hinzu.

Schritt 3: Automatische Auslieferung einrichten

Gehe zurück zu deinem App Service und klicke auf "Deployment Center".

Wähle GitHub als Quelle aus und verbinde dein GitHub-Repository mit deiner App Service-Anwendung.
