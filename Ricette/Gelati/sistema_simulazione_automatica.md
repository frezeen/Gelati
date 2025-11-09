# SISTEMA SIMULAZIONE AUTOMATICA - GELATI NINJA CREAMI DELUXE

## STRUTTURA TEMPLATE UNIVERSALE

Ogni simulazione deve contenere esattamente questi 11 elementi:

### 1. HEADER CON ANIMAZIONI
- Titolo gelato specifico
- Sottotitolo "Analisi Predittiva Gelato [NOME] - Ninja Creami Deluxe"
- CSS identico con animazioni backgroundShift, float, pulse

### 2. GRIGLIA SENSORIALE (6 carte)
- **Dolcezza Percepita**: Descrizione + intensità personalizzata
- **Cremosità**: Texture specifica del gelato
- **Intensità Aromatica**: Note caratteristiche del gusto
- **Complessità**: Livello di sofisticazione sensoriale
- **Spatolabilità**: PAC e comportamento a freddo
- **Qualità Complessiva**: Valutazione finale

### 3. ANALISI TECNICA PREDITTIVA
- POD Calcolato (dalla ricetta)
- PAC Finale (dalla ricetta)
- Solidi Totali (dalla ricetta)
- Grassi Totali (dalla ricetta)
- Temp. Servizio Ottimale (-12°C standard)
- Conservazione Ottimale (variabile per tipo)

### 4. PROFILO AROMATICO DETTAGLIATO
8 note aromatiche specifiche per il gusto:
- Nota dominante
- Base cremosa
- Note secondarie (4-5)
- Persistenza

### 5. GUIDA TEMPERATURE DI SERVIZIO
Scala fissa: -18°C → -14°C → -12°C → -8°C
Con descrizioni standard

### 6. PREVISIONI SENSORIALI AVANZATE
4 sezioni fisse:
- **Sensazione in Bocca**: Ingresso, sviluppo, finale
- **Profilo Olfattivo**: Aroma immediato, note, retrolfatto
- **Bilanciamento**: Equilibrio dolce/amaro/salato/acido
- **Persistenza**: Durata e evoluzione

### 7. CHECKLIST PRE-PRODUZIONE COMPLETA
4 sezioni:
- **Ingredienti da Preparare**: Lista dalla ricetta
- **Attrezzature Necessarie**: Standard Ninja Creami
- **Tempi di Maturazione**: Specifici per tipo gelato
- **Controlli Qualità**: Parametri di verifica

### 8. SUGGERIMENTI PER MIGLIORAMENTI
4 carte con ottimizzazioni:
- **Ottimizzazione Texture**: Modifiche PAC/POD
- **Intensificazione Aroma**: Aggiunte specifiche
- **Variazione Gourmet**: Upgrade premium
- **Presentazione**: Servizio e decorazione

### 9. VARIANTI STAGIONALI
4 stagioni con modifiche specifiche:
- **Primavera**: Ingredienti freschi, floreali
- **Estate**: Agrumi, rinfrescanti
- **Autunno**: Spezie, caldi
- **Inverno**: Ricchi, festivi

### 10. ABBINAMENTI CONSIGLIATI
4 categorie:
- **Abbinamenti Alcolici**: Distillati, spumanti, vini, liquori
- **Dolci di Accompagnamento**: Biscotti, pasticceria, cioccolato, crostate
- **Bevande Calde**: Caffè, tè, cioccolata, tisane
- **Occasioni Speciali**: Compleanni, matrimoni, feste, cene

### 11. ANALISI TECNICA PROFESSIONALE FINALE
- **Parametri Biochimici**: POD, PAC, Overrun, Densità
- **Valutazione Sensoriale**: Descrizione finale + punteggi

## DATABASE CONTENUTI PER TIPO GELATO

### CREME CLASSICHE
**Caratteristiche comuni:**
- Base: Latte + Panna + Gran Base
- POD: 15.0-15.5%
- PAC: 110-120
- Conservazione: 5-7 giorni
- Overrun: 15-20%

**Variazioni per gusto:**
- **Vaniglia**: Note floreali, eleganza, abbinamenti classici
- **Pistacchio**: Intensità siciliana, note tostate, abbinamenti mediterranei
- **Nocciola**: Cremosità piemontese, note burrose, abbinamenti autunnali
- **Caffè**: Intensità arabica, note amare, abbinamenti energetici

### GELATI ALLA FRUTTA
**Caratteristiche comuni:**
- Base: Latte + Panna + Purea frutta
- POD: 14.5-15.5%
- PAC: 120-130
- Conservazione: 3-5 giorni
- Overrun: 15-25%

### SORBETTI
**Caratteristiche comuni:**
- Base: Acqua + Zuccheri + Frutta
- POD: 18-20%
- PAC: 220-260
- Conservazione: 2-4 giorni
- Overrun: 10-15%

### GELATI SPECIALI
**Caratteristiche comuni:**
- Ingredienti particolari (alcol, spezie, salati)
- Parametri variabili
- Conservazione: 2-7 giorni
- Overrun: 10-25%

## REGOLE AUTOMATIZZAZIONE

### RICONOSCIMENTO AUTOMATICO TIPO
1. **Analizza ingredienti principali** dalla ricetta HTML
2. **Classifica automaticamente**:
   - Se contiene latte+panna+aromi → Crema
   - Se contiene latte+panna+frutta → Gelato frutta
   - Se contiene solo acqua+zuccheri+frutta → Sorbetto
   - Se contiene ingredienti particolari → Speciale

### GENERAZIONE CONTENUTI SPECIFICI
1. **Estrai parametri tecnici** dalla ricetta (POD, PAC, ingredienti, pesi)
2. **Applica template specifico** per il tipo riconosciuto
3. **Personalizza descrizioni** basate sul gusto principale
4. **Genera abbinamenti** coerenti con il profilo aromatico
5. **Crea varianti stagionali** appropriate

### IMMAGINI AUTOMATICHE
1. **Cerca immagini Unsplash** specifiche per il gusto
2. **Fallback su placeholder** tematici
3. **Pattern di ricerca**:
   - "[nome gelato] ice cream unsplash"
   - "[ingrediente principale] dessert"
   - "[origine geografica] [ingrediente]"

## TEMPLATE CSS UNIVERSALE

Usare sempre lo stesso CSS della simulazione Zuppa Inglese:
- Animazioni: backgroundShift, float, pulse, shimmer
- Colori: Gradienti moderni e attraenti
- Layout: Grid responsive
- Effetti: Hover, transform, box-shadow
- Font: Poppins da Google Fonts

## PROCESSO AUTOMATICO

### INPUT
- File ricetta HTML esistente

### PROCESSO
1. **Estrazione dati** dalla ricetta
2. **Riconoscimento tipo** gelato
3. **Applicazione template** appropriato
4. **Generazione contenuti** specifici
5. **Creazione file** simulazione completo

### OUTPUT
- File simulazione HTML identico come struttura alla Zuppa Inglese
- Contenuti completamente personalizzati per il gelato specifico
- Collegamenti bidirezionali ricetta ↔ simulazione

## ESEMPI IMPLEMENTATI

✅ **Zuppa Inglese**: Template completo di riferimento
✅ **Pistacchio**: Primo esempio automatizzato

## PROSSIMI DA IMPLEMENTARE

🔄 **Sistema automatico** per nuove ricette
🔄 **Database contenuti** espanso
🔄 **Riconoscimento intelligente** ingredienti
🔄 **Generazione automatica** varianti stagionali