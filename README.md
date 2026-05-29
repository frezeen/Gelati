# 🍨 Catalogo Ricette Gelati - Ninja Creami Deluxe

Benvenuto nel repository ufficiale del **Catalogo Ricette Gelati per Ninja Creami Deluxe**! Questo progetto raccoglie ricette professionali, altamente bilanciate dal punto di vista chimico e ottimizzate specificamente per i cestelli Deluxe da **709 ml**.

Il catalogo è accessibile localmente e offre un'interfaccia grafica moderna in stile *Glassmorphic* con sfondi animati cangianti, schede interattive e un sistema di stampa ottimizzato per la cucina.

---

## 🚀 Caratteristiche Uniche del Progetto

1. **Bilanciamento Chimico Avanzato**: Tutte le ricette sono calcolate scientificamente rispettando i parametri ottimali di:
   * **POD (Potere Dolcificante)**: Target ~15% per le creme e ~19% per i sorbetti.
   * **PAC (Potere Anticongelante)**: Target ~115-130 per garantire una consistenza setosa e perfettamente spatolabile direttamente dal freezer a -18°C.
   * **Solidi Totali**: Ottimizzati tra il 34% e il 40% per sopperire al basso overrun (incorporamento di aria) del Ninja Creami.
2. **Struttura Base Professionale**: Utilizzo combinato di latte intero, panna fresca (Panna LA 35 Trevalli), zuccheri calibrati (Saccarosio, Destrosio, Eritritolo) e **Gran Base Pregel** come stabilizzante/emulsionante.
3. **Doppia Anima per Ogni Gusto**:
   * **`*_Ricetta.html`**: Pagina tecnica con ingredienti esatti, valori nutrizionali, note e istruzioni dettagliate per la preparazione con il robot **Monsieur Cuisine (Smart/Connect)**. Include un tasto `🖨️ Stampa Ricetta A4` che formatta la ricetta su un unico foglio, rimuovendo gli elementi grafici superflui per l'uso in cucina.
   * **`*_Simulazione.html`**: Simulatore sensoriale predittivo interattivo in 11 sezioni che stima dolcezza, spatolabilità, corpo e comportamento a diverse temperature.
4. **Interfaccia Web Premium**: Una *landing page* interattiva (`index.html`) per navigare agevolmente tra le categorie e monitorare le statistiche del catalogo.

---

## 📂 Struttura del Progetto

Il progetto è organizzato in modo modulare per dividere le categorie e le ricette:

```text
├── index.html                                        # Pagina iniziale (Landing Page del catalogo)
├── GEMINI.md                                         # Master Prompt & Singola Fonte di Verità per l'IA
├── Gestione Pratica Gelati Ninja Creami...txt       # Manuale di conservazione e controllo qualità
├── README.md                                         # Questa guida
└── Ricette/
    └── Gelati/
        ├── index.html                                # Indice della navigazione interna
        ├── database_contenuti_simulazioni.md         # Database tecnico dei parametri sensoriali
        ├── link_checker.html                         # Utility di controllo integrità dei link
        ├── link_checker_report.html                  # Report di validazione dei link
        ├── NAVIGATION_SYSTEM.md                      # Specifiche del sistema di navigazione
        ├── NAVIGATION_VERIFICATION_REPORT.md         # Report di verifica della navigazione
        ├── sistema_simulazione_automatica.md         # Algoritmo di simulazione
        │
        ├── Creme/                                    # Categoria Gelati alle Creme
        │   ├── index.html                            # Indice delle ricette alle creme
        │   ├── Creme_Caffe_Ricetta.html
        │   ├── Creme_Caffe_Simulazione.html
        │   ├── Creme_Nocciola_Ricetta.html
        │   ├── Creme_Nocciola_Simulazione.html
        │   ├── Creme_Pistacchio_Ricetta.html
        │   ├── Creme_Pistacchio_Simulazione.html
        │   ├── Creme_Ricotta_Vaniglia_Ricetta.html
        │   ├── Creme_Ricotta_Vaniglia_Simulazione.html
        │   ├── Creme_Zuppa_Inglese_Ricetta.html
        │   └── Creme_Zuppa_Inglese_Simulazione.html
        │
        ├── Frutta/                                   # Categoria Gelati alla Frutta
        │   ├── index.html                            # Indice delle ricette alla frutta
        │   ├── Frutta_Fragola_Ricetta.html
        │   └── Frutta_Fragola_Simulazione.html
        │
        ├── Sorbetti/                                 # Categoria Sorbetti (Prossimamente)
        ├── Cioccolato/                               # Categoria Cioccolato (Prossimamente)
        └── Speciali/                                 # Categoria Speciali (Prossimamente)
```

---

## 🍨 Ricette Attualmente Disponibili

| Gusto | Categoria | Volume | Robot da Cucina | Pagine Correlate |
| :--- | :--- | :--- | :--- | :--- |
| **☕ Caffè Costa d'Oro** | Creme | 709 ml (Deluxe) | Monsieur Cuisine | [Ricetta](file:///Ricette/Gelati/Creme/Creme_Caffe_Ricetta.html) \| [Simulazione](file:///Ricette/Gelati/Creme/Creme_Caffe_Simulazione.html) |
| **🌰 Nocciola 99% Pregel** | Creme | 709 ml (Deluxe) | Monsieur Cuisine | [Ricetta](file:///Ricette/Gelati/Creme/Creme_Nocciola_Ricetta.html) \| [Simulazione](file:///Ricette/Gelati/Creme/Creme_Nocciola_Simulazione.html) |
| **🟢 Pistacchissimo 100% Pregel** | Creme | 709 ml (Deluxe) | Monsieur Cuisine | [Ricetta](file:///Ricette/Gelati/Creme/Creme_Pistacchio_Ricetta.html) \| [Simulazione](file:///Ricette/Gelati/Creme/Creme_Pistacchio_Simulazione.html) |
| **🍦 Ricotta & Vaniglia Antica** | Creme | 709 ml (Deluxe) | Monsieur Cuisine | [Ricetta](file:///Ricette/Gelati/Creme/Creme_Ricotta_Vaniglia_Ricetta.html) \| [Simulazione](file:///Ricette/Gelati/Creme/Creme_Ricotta_Vaniglia_Simulazione.html) |
| **🍰 Zuppa Inglese Premium** | Creme | 709 ml (Deluxe) | Monsieur Cuisine | [Ricetta](file:///Ricette/Gelati/Creme/Creme_Zuppa_Inglese_Ricetta.html) \| [Simulazione](file:///Ricette/Gelati/Creme/Creme_Zuppa_Inglese_Simulazione.html) |
| **🍓 Fragola Classica** | Frutta | 709 ml (Deluxe) | Monsieur Cuisine | [Ricetta](file:///Ricette/Gelati/Frutta/Frutta_Fragola_Ricetta.html) \| [Simulazione](file:///Ricette/Gelati/Frutta/Frutta_Fragola_Simulazione.html) |

---

## 🛠️ Come Utilizzare il Progetto

### 1. Navigare il Catalogo
Per iniziare, è sufficiente aprire il file principale **`index.html`** in un qualsiasi browser web (Chrome, Edge, Firefox, Safari). 
Dalla home page potrai accedere alle singole categorie e visualizzare le schede delle ricette o le simulazioni.

### 2. Preparazione con Monsieur Cuisine
Ogni ricetta descrive i passaggi di miscelazione e pastorizzazione ottimizzati per il robot da cucina Monsieur Cuisine, garantendo l'emulsione perfetta degli stabilizzanti e la pastorizzazione di sicurezza degli ingredienti.

### 3. Stampa per la Cucina
All'interno di ciascuna pagina Ricetta, troverai un pulsante **`🖨️ Stampa Ricetta A4`**. Cliccandoci, la pagina si aprirà nella finestra di stampa del browser pre-configurata per:
* Adattare tutti i contenuti essenziali su **un unico foglio A4**.
* Rimuovere sfondi colorati, pulsanti e foto per risparmiare inchiostro.
* Offrire la massima leggibilità (testo nero ad alto contrasto su fondo bianco) durante la preparazione.

---

## 📝 Contributi e Linee Guida per Nuovi Gusti
Se si desidera aggiungere un nuovo gusto al catalogo, fare riferimento al file **`GEMINI.md`**, che funge da modello operativo per mantenere coerenti il design, il bilanciamento chimico e i fogli di stile del progetto.
