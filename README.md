# Vergabetool (VgV)

Ein webbasiertes Tool zur Verwaltung von Teilnahmeanträgen und Vergabeprozessen gemäß dem Verfahren nach VgV (Vergabeverordnung).

## ✨ Ziel

Ziel des Projekts ist es, die digitale Bearbeitung und Bewertung von Teilnahmeanträgen zu unterstützen – effizient, übersichtlich und strukturiert.

## ⚙️ Funktionen

### Für Bieter:
- Projektauswahl
- Ausfüllen und Einreichen von Formularen
- Upload von Nachweisen mit Formatprüfung
- Empfang einer Eingangsbestätigung

### Für Vergabestellen:
- Übersicht aller Bewerbungen
- Automatisierte Bewertungslogik
- Unterstützung bei der Entscheidungsfindung
- Export von Daten (JSON, PDF)

## ✅ Mehrwert

- Vermeidung fehleranfälliger Excel-Lösungen
- Einheitlicher und digitaler Prozess
- Rechtssicherheit und Nachvollziehbarkeit
- Benutzerfreundliche Oberfläche

## 🛠️ Tech Stack

- **Backend:** Python, Django
- **Frontend:** HTML/CSS (Django Templates)
- **Datenbank:** SQLite (entwicklungsseitig)
- **Containerisierung:** Docker

## 🚀 Lokale Nutzung

```bash
git clone https://github.com/NeleDumler/VgVFinal.git
cd VgVFinal
python manage.py runserver
