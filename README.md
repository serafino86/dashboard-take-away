# 🏪 Dashboard Esercente - Ready for Netlify

## 🎯 Deploy Veloce (2 minuti)

### Opzione 1: Netlify Drop (FACILE)
```
1. Vai su: https://app.netlify.com/drop
2. Drag & drop questa intera cartella "dashboard"
3. Deploy automatico!
4. ✅ URL: https://random-name-789012.netlify.app
```

### Opzione 2: Netlify CLI
```bash
npm install -g netlify-cli
cd dashboard
netlify deploy --prod
```

---

## ✅ Cosa Contiene

```
dashboard/
└── index.html  (39KB)
    ✅ API_URL configurato
    ✅ Gestione ordini
    ✅ Gestione menu
    ✅ Stats real-time
    ✅ Filtri pranzo/cena
    ✅ Mobile-optimized
```

---

## 🎨 Features

- 📊 **Stats Dashboard**: Ordini oggi, totale, clienti VIP
- 📋 **Gestione Ordini**: Filtri pranzo/cena, stampa PDF
- 🍝 **Gestione Menu**: Aggiungi, modifica, elimina prodotti
- 🎯 **Disponibilità**: Imposta per giorno settimana
- 📱 **Mobile-First**: Funziona su smartphone
- 🎨 **UI Moderna**: Bottom nav, cards, colori vivaci

---

## 🔗 API Configurato

```javascript
API_URL = 'https://script.google.com/macros/s/AKfycbxyn6Owkm0c2isMGmv9lxEh0mXbPkD7izz-ymJqdqo/exec'
```

✅ Già configurato e pronto!

---

## 🔐 Protezione Password

### ⚠️ IMPORTANTE: Dashboard è pubblica!

Chiunque con URL può accedere. Proteggi con:

#### Opzione A: Password Netlify (Veloce)
```
1. Netlify Dashboard → Site settings
2. Access control → Password protection
3. Imposta password
4. Solo chi ha password accede
```

#### Opzione B: Sistema Auth Login (Avanzato)
```
Implementa sistema login con:
- AUTENTICAZIONE-ADMIN.md
- Session token
- Password in Script Properties
```

---

## 📋 Dopo Deploy

1. **Proteggi Subito**
   ```
   Netlify → Password protection → ON
   ```

2. **Test Dashboard**
   ```
   - Login (se protetta)
   - Vedi stats ordini
   - Tab Menu → Gestione prodotti
   - Prova aggiungere prodotto
   - Check traduzioni automatiche
   ```

3. **Custom Domain (Opzionale)**
   ```
   Netlify Dashboard → Domain settings
   Esempio: admin.tuoristorante.com
   ```

---

## 🎯 URL Suggeriti

- `admin.tuoristorante.com`
- `dashboard.tuoristorante.com`
- `gestione.tuoristorante.com`
- `esercente.tuoristorante.com`

---

## 📱 Workflow Giornaliero

### Mattina (5 minuti)
```
1. Apri dashboard da smartphone
2. Tab Menu
3. Imposta disponibilità "OGGI" per prodotti del giorno
4. Salva
5. Clienti vedono menu aggiornato!
```

### Durante Servizio
```
1. Tab Ordini
2. Filtro "Pranzo" (<15:00) o "Cena" (≥15:00)
3. Vedi ordini in tempo reale
4. Stampa PDF per cucina
```

### Sera
```
1. Vedi totale giornata
2. Check clienti VIP (prossimi a omaggio)
3. Prepara menu domani
```

---

## 💡 Tips

- 📱 Salva URL nei bookmark smartphone
- 🔔 Attiva notifiche browser per nuovi ordini
- 📊 Check stats ogni mattina
- 🍝 Aggiorna menu 1 volta/settimana

---

Made with ❤️ by SERAFINO RÉSOUT
