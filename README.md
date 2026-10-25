# Studio Faraj — Email Template per Brevo (Target: Aziende Senza Sito Web)

Questa cartella contiene i template HTML pronti per essere importati con **copia e incolla** su Brevo (Sendinblue) per campagne destinate ad **aziende e professionisti che non hanno ancora un sito web**.

Una volta copiato il codice nel tuo account Brevo, **puoi eliminare l'intera cartella `email-template/`** dal repository.

---

## 🎯 Strategia del Messaggio (Target: Chi non ha ancora un sito)

Il messaggio affronta direttamente il dubbio tipico di chi non ha un sito:
1. **La perdita silenziosa di clienti**: senza un sito web, chiunque cerchi i loro servizi su Google finisce dai concorrenti (perdendo il 100% delle ricerche locali).
2. **Il rischio dei template fai-da-te (Wix / WordPress)**: chi parte da zero viene spesso attratto da template a basso costo, che si rivelano invisibili su Google, lenti a caricare su smartphone e complicati da gestire.
3. **Il valore del codice su misura (Next.js, React, Cloud)**:
   - Posizionamento in **Top 10 su Google** fin dal primo giorno (Core Web Vitals e caricamento <0.8s).
   - Fino al **+35% di contatti e clienti in più** con canali diretti (telefono, WhatsApp, form personalizzati).
   - Soluzione chiavi in mano con **codice 100% di proprietà**, senza abbonamenti a piattaforme terze.
4. **Recensioni reali 5.0 Google**: testimonianze verificate di clienti (come *Olio di Valeria*, che ha lanciato il suo primo e-commerce con Studio Faraj, e *Daniel Kls*).
5. **Logo ufficiale Studio Faraj**: incorporato direttamente dal link live del sito (`https://studiofaraj.it/assets/logo-mail.png`).
6. **Pulsante di Disiscrizione dedicato**: card stilizzata nel footer con pulsante ben visibile per la disiscrizione sicura via Brevo (`{{ unsubscribe }}`).

---

## 📁 File inclusi

1. **`brevo-studio-faraj-promo.html`** *(Consigliato / Principale in Italiano)*
   - Ottimizzato per imprenditori, commercianti, artigiani e professionisti italiani (Padova, Veneto e nazionale) che non hanno ancora un sito.
2. **`brevo-studio-faraj-promo-en.html`** *(Versione Internazionale in Inglese)*
   - Per contatti internazionali con lo stesso approccio di conversione.

---

## 🚀 Come usarlo su Brevo (Passo-passo)

1. **Accedi a Brevo** (https://app.brevo.com).
2. Vai su **Campagne (Campaigns)** → **Template (Templates)** → Clicca su **Nuovo template**.
   *(Oppure crea direttamente una nuova Campagna Email e vai al passaggio di Progettazione/Design)*.
3. Seleziona **"Usa il tuo codice"** o **"Incolla il tuo codice" (Paste Your Code / Raw HTML)**.
4. Apri `brevo-studio-faraj-promo.html`, seleziona tutto (`Ctrl + A`), copia (`Ctrl + C`) e incolla (`Ctrl + V`) nell'editor di Brevo.
5. **Oggetti consigliati per l'email su Brevo:**
   - Opzione 1: *Perché la tua attività sta perdendo clienti ogni giorno senza un sito web*
   - Opzione 2: *Cosa cercano su Google i tuoi clienti (e perché trovano solo i concorrenti)*
   - Opzione 3: *Creare il tuo primo sito: perché evitare i template e scegliere il codice su misura*
6. **Preheader consigliato:**
   - *Senza un sito web, ogni giorno decine di persone cercano i tuoi servizi su Google e finiscono dai concorrenti. Ecco come acquisire nuovi clienti con codice su misura.*
7. **Invia un'email di prova:**
   - Usa il pulsante **"Invia una prova"** di Brevo sul tuo indirizzo email per verificare la visualizzazione perfetta sia su smartphone che su desktop.
8. **Eliminazione cartella:**
   - Una volta salvato il template su Brevo, cancella questa cartella `email-template/` con il comando:
     ```powershell
     Remove-Item -Recurse -Force email-template
     ```

---

## ⚙️ Tag Brevo utilizzati

- `{{ mirror }}`: Genera automaticamente il link *"Visualizza online"*.
- `{{ unsubscribe }}`: Genera il link e aziona il **pulsante dedicato di disiscrizione** inserito nella card in fondo all'email, garantendo conformità al 100% con le norme GDPR e antispam.
