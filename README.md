# 🌐 IT Portfolio – Orhan Fevzi Karakas

> Persönliche Portfolio-Website mit tokenbasiertem Zugangssystem, gebaut als Cloudflare Worker. Zeigt Projekte, Werdegang und praktische Erfahrung in einem sauberen, responsiven Design.

![Status](https://img.shields.io/badge/Status-Live-success) ![Platform](https://img.shields.io/badge/Platform-Cloudflare_Workers-F38020?logo=cloudflare&logoColor=white) ![Frontend](https://img.shields.io/badge/Frontend-Tailwind_CSS-38BDF8?logo=tailwindcss&logoColor=white) ![Security](https://img.shields.io/badge/Security-Token_Auth_%2B_CSP-green)

---

## 🖼️ Showcase

<!-- Screenshots hier per Drag & Drop in den GitHub-Editor einfügen -->
<div align="center">
  <img src="https://github.com/user-attachments/assets/95bbb3ea-b356-46a9-b093-e0e9376007c6" width="100%" alt="Login-Seite" />
  <br>
  <p><i>Login-Seite mit tokenbasiertem Zugangssystem.</i></p>
</div>

<img width="100%" alt="Startseite" src="https://github.com/user-attachments/assets/1dcebc6d-1a14-4009-8f27-e79323121d14" />
<img width="100%" alt="Über mich" src="https://github.com/user-attachments/assets/8f983b80-b88d-4729-8647-74de7a82ec13" />
<img width="100%" alt="Bildungsweg" src="https://github.com/user-attachments/assets/84c7134d-aaa0-437b-9d75-e1437ab6d4d6" />
<img width="100%" alt="Erfahrungen" src="https://github.com/user-attachments/assets/7c941133-6ca9-423c-a30d-4f820ed8b016" />
<img width="100%" alt="Kontakt" src="https://github.com/user-attachments/assets/8477f933-5175-40ab-b0ad-bb46a48f2fa9" />

> Persönliche Daten (E-Mail, Telefon, Zugangstoken) sind in den Screenshots bewusst geschwärzt, da dies ein öffentliches Showcase-Repository ist.

### Live ansehen:
🔗 [okarakas.de](https://okarakas.de)

---

## 🎯 Über das Projekt

Das Portfolio dient als zentrale Anlaufstelle für Projektanfragen und Bewerbungen. Statt einer offenen, öffentlich indexierbaren Seite nutzt es ein **individuelles Zugangstoken pro Empfänger** – jeder Interessent (z. B. ein Unternehmen) erhält einen eigenen Zugangscode, über den die Seite personalisiert begrüßt und der Zugriff nachvollzogen wird.

### Features

* **Tokenbasierter Zugang:** Jeder Zugangscode ist einem Empfänger zugeordnet und kann ein individuelles Ablaufdatum haben.
* **Sliding Sessions:** Die Sitzung verlängert sich automatisch bei aktiver Nutzung, statt starr nach fester Zeit abzulaufen.
* **Responsive Design:** Vollständig angepasst für Mobile, Tablet und Desktop – inklusive eigenem mobilen Navigationsmenü.
* **Interaktive Projekt-Galerie:** Bildergalerie mit Swipe-Unterstützung und Lightbox-Ansicht für Screenshots.
* **Strukturierte Accordion-Bereiche:** Übersichtliche, aufklappbare Sektionen für Werdegang und Erfahrungen.

---

## 🛡️ Sicherheit

* **Security Headers:** Strikte Content-Security-Policy, `X-Frame-Options: DENY`, `X-Content-Type-Options: nosniff`.
* **HttpOnly-Cookies:** Session-Handling über sichere, JavaScript-unzugängliche Cookies (`Secure`, `SameSite=Strict`).
* **Server-seitige Validierung:** Token-Prüfung und Ablaufdatum-Kontrolle laufen vollständig serverseitig in der Edge-Function.

---

## 🛠️ Tech Stack

| Bereich | Technologie |
| :--- | :--- |
| **Hosting** | Cloudflare Workers (Edge Computing) |
| **Datenhaltung** | Cloudflare KV (Token- & Session-Daten) |
| **Frontend** | Tailwind CSS, Vanilla JavaScript |
| **Icons** | Font Awesome |
| **Fonts** | Google Fonts (Plus Jakarta Sans) |

---
*Hinweis: Der vollständige Quellcode liegt in einem privaten Repository, da er Zugangs- und Sicherheitslogik enthält. Dieses Repository dient als reines Showcase.*
