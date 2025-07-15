# Redirect intelligente verso Feedly (App o Web)

Questa semplice pagina HTML tenta di aprire automaticamente l'app **Feedly** tramite schema URL (`feedly://`).  
Se l'app non è installata o il browser non consente il redirect, reindirizza alla versione web: [https://feedly.com/i/](https://feedly.com/i/)

## 🔧 Funzionamento

1. Al caricamento della pagina, il browser tenta di aprire l'app con `feedly://`.
2. Dopo **500 millisecondi**, se l'app non si è aperta, viene eseguito un redirect automatico al sito web di Feedly.
3. In alternativa, l’utente può cliccare manualmente sul link di fallback.

## 🧪 Utilizzi consigliati

- Aggiungi questa pagina tra i **preferiti del browser** per aprire Feedly dall'app se disponibile.
- Funziona bene in browser come **Safari**, **Firefox**, **Brave** e **DuckDuckGo** (salvo blocchi sullo schema URL).
- Utile in ambienti dove non si vogliono usare shortcut iOS ma si desidera un'apertura diretta dell'app.

## 💡 Hosting

Puoi pubblicare questa pagina gratuitamente su:
- [GitHub Pages](https://pages.github.com/)
- [Netlify](https://www.netlify.com/)
- Qualsiasi servizio di hosting statico

## 📁 File

- `index.html`: la pagina HTML con il redirect intelligente verso Feedly

## ✅ Esempio di uso

Se pubblichi la pagina su `https://ilmiosito.it/apri-feedly`, puoi:
- Aggiungere `https://ilmiosito.it/apri-feedly` ai preferiti
- Aprire Feedly direttamente con un solo clic

---

### Licenza

Questo progetto è rilasciato sotto licenza MIT. Sentiti libero di modificarlo per adattarlo ad altre app (es. Spotify, YouTube, Telegram, ecc.).
