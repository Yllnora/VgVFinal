# 💼 VgV-Verfahren – Digitale Teilnahme & Bewertung

Dieses Projekt unterstützt das Vergabeverfahren nach VgV durch eine webbasierte Django-Anwendung. Es ermöglicht Bieter:innen die digitale Abgabe von Teilnahmeanträgen und Vergabestellen die strukturierte Auswertung.

---

## 🎯 Ziel des Projekts

Ziel ist es, die Anforderungen des VgV-Verfahrens digital abzubilden und eine effiziente, nutzerfreundliche Lösung zu entwickeln. Dabei werden:
- Excel-Formulare ersetzt
- Anträge digital eingereicht
- Nachweise verwaltet
- Bewertungen vorbereitet

---

## 👤 Rollen im System

| Rolle           | Funktion                                                                 |
|----------------|--------------------------------------------------------------------------|
| **Bieter:in**       | Einreichung von Anträgen, Upload von Nachweisen                           |
| **Vergabestelle**   | Sichtung, Bewertung und Verwaltung der Bewerbungen                        |

---

## 🧩 Funktionen

- Upload von Teilnahmeanträgen & Nachweisen
- Automatische Umsatzberechnung Netto/Brutto
- Deadline-Erkennung
- Rollenspezifisches Dashboard
- Bewertungsvorbereitung

---

## 🚀 Lokale Nutzung mit Docker

### 🔽 1. Image von Docker Hub laden

```bash
docker pull yllnora/vgvfinal:latest
docker run -p 8000:8000 yllnora/vgvfinal:latest
http://localhost:8000
