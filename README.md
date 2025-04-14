# 🤖 Bot Trading OMega V4

**Bot de trading asynchrone multi-paires avec stratégie RSI/ATR, notifications Telegram et journalisation automatique.**

> ⚠️ Projet à usage éducatif. Toute utilisation commerciale sans accord explicite est strictement interdite. Voir [LICENSE](./LICENSE) pour plus d'informations.

---

## 🔍 Aperçu

Ce bot permet de :
- 📈 Trader automatiquement plusieurs paires crypto via l’API Binance.
- 🧠 Appliquer des stratégies RSI simples ou combinées avec ATR.
- 💬 Recevoir des notifications Telegram en temps réel.
- 🧾 Journaliser les trades dans une base SQLite.
- 📊 Exporter l’historique des transactions en CSV.
- ⏱ Fonctionner de façon 100% asynchrone pour une gestion fluide des paires.

---

## ⚙️ Technologies

- `Python 3.8+`
- `asyncio`
- `ta` (technical analysis)
- `Binance API`
- `telegram`
- `Stable logging & DB via SQLite`
- `Tenacity` (retries)
- `Pandas` pour le traitement des données

---

## 📦 Installation

1. **Clone le repo :**

```bash
git clone https://github.com/tonpseudo/Bot-Trading-OMega-V4.git
cd Bot-Trading-OMega-V4

Installe les dépendances :

bash
Copier
Modifier
pip install -r requirements.txt
Configure tes clés dans config.json :

json
Copier
Modifier
{
  "BINANCE_API_KEY": "ta_clé",
  "BINANCE_API_SECRET": "ton_secret",
  "TELEGRAM_TOKEN": "token_bot",
  "TELEGRAM_CHAT_ID": "id_du_chat"
}
Tu peux aussi utiliser des variables d’environnement.

Lancer le bot 🚀 :

bash
Copier
Modifier
python bot_omega_v4.py
🔧 Personnalisation
Tu peux choisir entre deux stratégies :

RSIOnlyStrategy

RSI_ATR_Strategy

Modifie les paramètres dans config.json :

RSI d’achat/vente

Paires à trader

Montants

Fréquence de rafraîchissement

🔐 Sécurité & API
✅ Tu peux utiliser le testnet Binance pour éviter de risquer de l'argent réel.
⚠️ Ne jamais commit tes clés API sur un dépôt public.

📤 Exports
À l’arrêt du bot :

📁 Les trades sont exportés automatiquement dans trades_export_v3_improved.csv.

🛡️ Licence

Ce projet est protégé par une licence personnalisée :

🔒 Usage commercial interdit sans autorisation.

📚 Usage personnel et éducatif autorisé.

✍️ Respect obligatoire de l’auteur (attribution).

Voir LICENSE pour tous les détails.

🙌 Remerciements
Merci à la communauté Python, Binance, et aux contributeurs d’open-source.
Ce projet est né d’une envie de créer un bot puissant, éthique, et transparent.

