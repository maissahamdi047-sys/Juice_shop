# 🔐 Rapport de Sécurité — OWASP Top 10 (2021) sur Juice Shop

> Travail académique réalisé dans le cadre du cursus SSIR à TEK-UP University (2025–2026)  
> Auteurs : **Hamdi Maissa** · **Reguigui Aymen**

---

## 📋 Description

Ce dépôt contient un rapport de pentest applicatif complet sur **OWASP Juice Shop**, une application web volontairement vulnérable conçue pour la formation à la sécurité.

L'analyse couvre les **10 catégories de risques** du classement OWASP Top 10 2021, avec pour chaque vulnérabilité :
- Une description du vecteur d'attaque
- Une preuve d'exploitation (screenshots Burp Suite, terminal Kali)
- L'impact potentiel
- Les recommandations de remédiation

---

## 🎯 Vulnérabilités couvertes

| # | ID OWASP | Vulnérabilité | Sévérité | CVSS |
|---|----------|---------------|----------|------|
| 1 | A01:2021 | Contrôle d'accès défaillant | 🔴 Critique | 9.8 |
| 2 | A02:2021 | Défaillances cryptographiques | 🟠 Élevé | 7.5 |
| 3 | A03:2021 | Injection (SQLi, XSS) | 🔴 Critique | 9.8 |
| 4 | A04:2021 | Conception non sécurisée | 🟠 Élevé | 7.2 |
| 5 | A05:2021 | Mauvaise configuration de sécurité | 🟠 Élevé | 7.5 |
| 6 | A06:2021 | Composants vulnérables et obsolètes | 🟠 Élevé | 7.5 |
| 7 | A07:2021 | Authentification défaillante | 🔴 Critique | 8.8 |
| 8 | A08:2021 | Défaillances d'intégrité des données | 🟠 Élevé | 7.2 |
| 9 | A09:2021 | Défaillances de journalisation/surveillance | 🟡 Moyen | 5.4 |
| 10 | A10:2021 | SSRF (Server-Side Request Forgery) | 🟠 Élevé | 7.5 |

---

## 🛠️ Outils utilisés

- **Burp Suite Community Edition** — interception et manipulation de requêtes HTTP
- **Kali Linux** — environnement de test
- **Gobuster** — énumération de répertoires
- **Hashcat** — cassage de hash MD5
- **Webhook.site** — démonstration SSRF
- **JWT.io** — analyse et manipulation de jetons JWT

---

## 📁 Contenu du dépôt

```
📄 owasp_juice_shop_report.pdf   → Rapport complet (PDF)
📄 README.md                     → Ce fichier
```

---

## ⚠️ Avertissement légal

> Ce rapport est réalisé **à des fins pédagogiques uniquement** dans un environnement contrôlé.  
> OWASP Juice Shop est une application **volontairement vulnérable** prévue pour la formation.  
> **Ne reproduire aucune de ces techniques sur des systèmes sans autorisation explicite.**

---

## 📚 Références

- [OWASP Top 10 2021](https://owasp.org/Top10/)
- [OWASP Juice Shop](https://owasp.org/www-project-juice-shop/)
- [Burp Suite Documentation](https://portswigger.net/burp/documentation)

---


