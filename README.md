# Aggiungiamo un file README.md al progetto esistente

readme_content = """
# Social Publisher – Facebook & Instagram via Meta API

Questa è una semplice applicazione **Flask** che consente di pubblicare post (immagine + didascalia) su **Facebook** e **Instagram** utilizzando la **Meta Graph API**.

## 🚀 Funzionalità
- Interfaccia web per inserire testo e URL immagine
- Pubblicazione automatica su:
  - Facebook Page
  - Instagram Business Account collegato
- Pronto per il deploy su Heroku

## 🗂️ Struttura

## 🛠️ Configurazione ambiente
Imposta le seguenti variabili d'ambiente su Heroku:

- `ACCESS_TOKEN` → il token di accesso Meta valido
- `PAGE_ID` → l'ID della Pagina Facebook
- `IG_USER_ID` → l'ID dell'account Instagram Business

## 🧪 Esecuzione locale
```bash
pip install -r requirements.txt
python app.py
