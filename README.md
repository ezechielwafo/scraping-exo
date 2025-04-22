# Test de Rattrapage — JavaScript / Node.js

## 🎯 Objectif

Créer un **script Node.js** capable de scraper un site web en utilisant la librairie **Cheerio**, sans utiliser d’outil d’intelligence artificielle.

---

## ⏱️ Temps imparti

**10 minutes maximum**.

---

## 🧪 Consigne

1. Écris un script Node.js (`index.js`) qui :
   - Récupère les livres présents sur la page d’accueil de [https://books.toscrape.com](https://books.toscrape.com)
   - Pour chaque livre, extrait les informations suivantes :
     - `img_url` : URL complète de l’image du livre
     - `title` : titre du livre
     - `price` : prix affiché
     - `inStock` : disponibilité (ex. "In stock")
     - `rate` : note (One, Two, Three, Four, Five)

2. Le résultat devra être affiché dans la console sous forme de tableau (optionnel mais recommandé : `console.table()`).

---

## 📦 Structure de l’objet attendu

```js
{
  img_url: "https://...",
  title: "Nom du livre",
  price: "£xx.xx",
  inStock: "In stock",
  rate: "Three"
}
```

---

## 📏 Règles du test

⚠️ **Toute infraction entraînera l'annulation immédiate du test.**

### ❌ Interdictions strictes :

- **Aucune IA autorisée** :
  - ❌ ChatGPT
  - ❌ DeepSeek
  - ❌ Copilot
  - ❌ Google Gemini
  - ❌ Bing AI ou toute autre aide automatisée

- **Aucune messagerie** :
  - ❌ WhatsApp
  - ❌ Messenger
  - ❌ Discord
  - ❌ Signal, Telegram, etc.

- **Aucune recherche en ligne** autre que les sites spécifiés ci-dessous.

---

### ✅ Seules ressources autorisées :

- 🔗 Le site à scraper : [https://books.toscrape.com](https://books.toscrape.com)
- 📘 La documentation officielle de Cheerio : [https://cheerio.js.org](https://cheerio.js.org)

---

## 🔧 Outils autorisés

- Node.js
- Cheerio
- `console.log()` ou `console.table()`

---

## ✅ Ce que j’évaluerai

| Critère                        | Points |
|-------------------------------|--------|
| Le script fonctionne          |   5    |
| Structure d’objet correcte    |   2    |
| Résultat affiché proprement   |   1    |
| Code lisible et clair         |   1    |
| Respect des contraintes       |   1    |

**Total : 10 points**

---

## 📁 Fichier attendu

- `index.js` (pas de sous-dossier, pas de dépendances non utilisées)

---

Bonne chance 💪
