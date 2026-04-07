# ⚔️ SEPDuell
**Fullstack Multiplayer Card Game mit Echtzeit-Duellen, Chat & 2FA-Security**
Fullstack Web-App (React · Spring Boot · PostgreSQL · WebSockets)

![Java](https://img.shields.io/badge/Java-21-blue)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-brightgreen)
![React](https://img.shields.io/badge/React-Vite-blue)
![WebSocket](https://img.shields.io/badge/WebSocket-RealTime-orange)

---

## 📸 Screenshots & Features

### 🔐 Registrierung & Login + 2FA
<p align="center">
  <img src="docs/images/login.png" width="900">
</p>

### 🏠 Dashboard / Startseite
<p align="center">
  <img src="docs/images/dashboard.png" width="900">
</p>

### 🃏 Deck Management
<p align="center">
  <img src="docs/images/deck.png" width="900">
</p>

### 👥 Freundesliste & Profile
<p align="center">
  <img src="docs/images/friends.png" width="900">
</p>

### ⚔️ Live Duell-System
<p align="center">
  <img src="docs/images/duel.png" width="900">
</p>

### 💬 Echtzeit Chat
<p align="center">
  <img src="docs/images/chat.png" width="900">
</p>

---

## 🚀 Projektübersicht

SEP-Duell ist eine **Fullstack Multiplayer-Webanwendung**, in der Nutzer strategische Kartenspiele gegeneinander spielen können.

Das System kombiniert:

- Benutzerverwaltung mit Sicherheitsmechanismen
- Deckbuilding & Kartenmanagement
- Echtzeit-Duelle zwischen Spielern
- Chat- und Social-Funktionen
- Leaderboard & Rankingsystem

👉 Ziel:  
Eine **skalierbare, interaktive Multiplayer-Plattform** für strategische Duelle.

---

## ⭐ Kernfeatures

### 🔐 Authentifizierung & Sicherheit
- Registrierung & Login-System
- **2-Faktor-Authentifizierung per E-Mail**
- Fallback über Sicherheitscode
- Rollen-System (Admin / User)

---

### 🃏 Karten- & Decksystem
- Erstellung eigener Decks (max. 3 Decks / User)
- Kartenverwaltung (max. 30 Karten pro Deck)
- Kartenattribute:
  - Angriff / Verteidigung
  - Seltenheit (Normal / Rare / Legendary)
  - Beschreibung + Bild
- Admin-Upload von Kartentypen via CSV

---

### ⚔️ Duell-System (Core Feature)
- Spieler können sich gegenseitig herausfordern
- Live-Duell mit:
  - Lebenspunkten
  - Angriff / Verteidigungssystem
  - Kartenzügen & Spielzügen
- Countdown-basierte Duell-Anfragen
- Ergebnis- & Statistikanzeige

---

### 👥 Social Features
- Freundesliste
- Freundschaftsanfragen (inkl. E-Mail Notification)
- Profilansicht anderer Nutzer
- Privatsphäre-Einstellungen

---

### 💬 Echtzeit-Kommunikation
- Private Chats
- Gruppen-Chats
- Nachrichten senden, bearbeiten, löschen
- **Realtime Messaging (WebSockets)**

---

### 🏆 Leaderboard
- Ranking aller Spieler
- Suche nach Usern
- Statusanzeige:
  - Online / Offline / Im Duell
- Echtzeit-Updates

---

### 🎁 Erweiterungen (Advanced Features)
- Lootbox-System (Kartenbelohnungen)
- SEP-Coins als Spielwährung
- Duplikat-Handling
- Statistiksystem nach Duellen

---

## 🧠 Technische Highlights (WICHTIG FÜR INTERVIEW)

👉 basiert direkt auf eurer Projektmappe:

- 2FA-System mit Token + Mail-Service
- REST-API + modulare Service-Struktur  
- Echtzeit-Kommunikation via WebSockets  
- komplexe Game-Logik (Züge, Angriffe, Zustände)  
- Trennung von Frontend & Backend  

---

## 🧱 Technologie-Stack

### Frontend
- React (Vite)
- CSS / UI Components
- Axios (API Calls)
- WebSockets (Realtime)

### Backend
- Java 21
- Spring Boot
- Spring Security
- REST API
- Mail Service (2FA)

### Datenbank
- PostgreSQL
- JPA / Hibernate

---

## 🏛️ Softwarearchitektur

- Schichtenarchitektur:
  - Controller
  - Service
  - Repository
- REST-basierte Kommunikation
- Realtime-Komponenten via WebSocket Layer
- Modulare Game-Engine (Duell-Logik)

---

🎯 Ziele & Mehrwert
Für Nutzer

✔ Strategisches Gameplay
✔ Realtime Multiplayer Experience
✔ Social Interaction + Competition

Technisch

✔ Fullstack Architektur
✔ Realtime Systeme
✔ Security (2FA)
✔ Skalierbare Struktur

---

📜 Lizenz

MIT License – Nutzung für Studium & private Projekte erlaubt.

---

🎓 Universität Duisburg-Essen – SEP Projekt

---

## 👥 Team

| Name         | Rolle                                          |
|--------------|------------------------------------------------|
| Özgürcan     | Backend (Auth, 2FA, Leaderboard, Duell-System) |
| Soufian      | Backend (Game Logic, Deck System)              |
| Danny        | Chat-System & Social Features                  |
| Beyza        | Frontend & Duell UI                            |
| Enes         | Gameplay & UX                                  |
| Saman        | UI / Interaction Design                        |


