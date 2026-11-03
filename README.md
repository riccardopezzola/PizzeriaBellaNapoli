# 🍕PizzeriaBellaNapoli

https://riccardopezzola.github.io/PizzeriaBellaNapoli/

**Il gusto della tradizione, online.**

Pizzeria Bella Napoli è un sito web realizzato per presentare il locale e permettere ai clienti di consultare facilmente il menu attraverso un'interfaccia semplice, intuitiva e accessibile da qualsiasi dispositivo.

Il progetto nasce con l'obiettivo di valorizzare la presenza online della pizzeria, offrendo una vetrina digitale in cui prodotti, ingredienti e prezzi sono organizzati in modo chiaro e ordinato.

## ✨ Funzionalità principali

- **Homepage:** presentazione della Pizzeria Bella Napoli e navigazione tra le diverse sezioni.
- **Menu digitale:** consultazione dell'offerta gastronomica del locale.
- **Sezione pizze:** elenco delle pizze con ingredienti e relativi prezzi.
- **Sezione bevande:** panoramica delle bevande disponibili.
- **Sezione dolci:** presentazione dei dessert disponibili.
- **Navigazione intuitiva:** collegamenti semplici tra le diverse pagine.
- **Design responsive:** interfaccia progettata per adattarsi a smartphone, tablet e computer.

## 🎯 Vantaggi

- **Presenza online:** una vetrina digitale per far conoscere il locale.
- **Menu sempre accessibile:** i clienti possono consultare l'offerta in qualsiasi momento.
- **Informazioni chiare:** prodotti, ingredienti e prezzi presentati in modo organizzato.
- **Esperienza intuitiva:** navigazione semplice e immediata.
- **Accessibilità multipiattaforma:** consultazione da diversi dispositivi.

## 🛠️ Tecnologie utilizzate

| Tecnologia | Utilizzo |
|---|---|
| HTML5 | Struttura e organizzazione delle pagine web |
| CSS3 | Stile grafico, layout e adattabilità ai dispositivi |

## 📁 Struttura del progetto

```text
Pizzeria-Bella-Napoli/
│
├── index.html       # Homepage
├── style.css        # Foglio di stile comune
├── pizze.html       # Menu delle pizze
├── bevande.html     # Menu delle bevande
└── dolci.html       # Menu dei dolci
```

## 🎨 Identità e personalizzazione

Il sito è strutturato per rappresentare l'identità della Pizzeria Bella Napoli attraverso una grafica coordinata e contenuti facilmente consultabili.

La struttura può essere personalizzata attraverso:

- Logo e identità visiva.
- Palette di colori e tipografia.
- Immagini dei prodotti.
- Descrizioni, ingredienti e prezzi.
- Informazioni e contatti del locale.

## 🚀 Installazione e avvio

Per visualizzare il progetto in locale:

1. Clonare la repository GitHub:

   ```bash
   git clone URL_DELLA_REPOSITORY
   ```

2. Accedere alla cartella del progetto:

   ```bash
   cd Pizzeria-Bella-Napoli
   ```

3. Aprire il file `index.html` tramite un browser.

Non sono necessarie installazioni di dipendenze o configurazioni di ambienti di sviluppo.

---

# 👨‍💻 Guida per gli sviluppatori

Questa sezione definisce le regole di collaborazione e organizzazione del codice, con l'obiettivo di mantenere il progetto ordinato, coerente e facilmente aggiornabile.

## 📁 Organizzazione dei file

| File | Responsabilità |
|---|---|
| `index.html` | Homepage del sito. Non modificare senza autorizzazione. |
| `style.css` | Stile grafico comune a tutte le pagine. Le modifiche devono essere concordate con il responsabile. |
| `pizze.html` | Pagina dedicata alle pizze. |
| `bevande.html` | Pagina dedicata alle bevande. |
| `dolci.html` | Pagina dedicata ai dolci. |

## 📋 Assegnazione delle attività

Ogni sviluppatore deve scegliere una delle seguenti sezioni:

- Pizze (`pizze.html`)
- Bevande (`bevande.html`)
- Dolci (`dolci.html`)

Ogni componente del gruppo è responsabile esclusivamente del file assegnato, salvo diversa autorizzazione del responsabile del progetto.

## 📝 Regole di sviluppo

Per ogni prodotto inserito devono essere presenti:

- Nome del prodotto.
- Descrizione o ingredienti.
- Prezzo.
- Eventuale immagine, se disponibile.

Durante lo sviluppo è necessario:

- Utilizzare HTML5 con una struttura semantica corretta.
- Riutilizzare le classi CSS già definite.
- Mantenere uno stile grafico uniforme tra le pagine.
- Verificare il corretto funzionamento dei collegamenti.
- Controllare la visualizzazione su dispositivi di diverse dimensioni.
- Mantenere il codice leggibile e organizzato.

**Importante:** non modificare file assegnati ad altri componenti senza aver prima concordato la modifica.

## 🌿 Gestione dei branch

Ogni sviluppatore deve lavorare su un branch personale creato a partire dal branch `main`.

I branch da utilizzare sono:

- `pizze`
- `bevande`
- `dolci`

Esempio di creazione del branch per la sezione pizze:

```bash
# Aggiornare il branch principale
git checkout main
git pull origin main

# Creare il proprio branch
git checkout -b pizze

# Verificare il branch corrente
git branch
```

## 💾 Commit e pubblicazione delle modifiche

Una volta completato il lavoro, lo sviluppatore dovrà registrare le modifiche:

```bash
# Aggiungere il file modificato
git add pizze.html

# Creare un commit
git commit -m "Add pizzas section"

# Caricare il branch su GitHub
git push -u origin pizze
```

Il nome del file e del branch dovranno essere adattati alla propria sezione.

## 🔄 Pull Request e revisione

Dopo aver pubblicato il branch su GitHub, ogni sviluppatore dovrà:

1. Aprire una Pull Request verso `main`.
2. Descrivere le modifiche effettuate.
3. Verificare che non siano presenti conflitti.
4. Attendere la revisione del responsabile.
5. Procedere con il merge solo dopo l'approvazione.

**Non è consentito effettuare modifiche direttamente sul branch `main`.**

## ✅ Controlli prima della Pull Request

Prima di aprire una Pull Request, verificare che:

- [ ] Tutti i prodotti abbiano nome, descrizione e prezzo.
- [ ] Le immagini siano correttamente visualizzate.
- [ ] La struttura HTML sia valida.
- [ ] Le classi CSS siano coerenti con quelle del progetto.
- [ ] I collegamenti tra le pagine funzionino.
- [ ] La pagina sia leggibile anche da smartphone.
- [ ] Non siano stati modificati file non assegnati.

---

## 📌 Progetto

**Pizzeria Bella Napoli**

*Tradizione, qualità e passione per la pizza.*
