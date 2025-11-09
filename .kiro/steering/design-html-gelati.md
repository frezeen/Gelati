---
inclusion: always
---

# DESIGN HTML GELATI - REGOLE ASSOLUTE

## PROBLEMI DA EVITARE SEMPRE

**LEGGIBILITÀ CRITICA:**
- ❌ MAI testo bianco su sfondo bianco
- ❌ MAI testo poco contrastato
- ✅ SEMPRE testo NERO (#333) su sfondo BIANCO nelle tabelle
- ✅ SEMPRE verificare contrasto colori

**DESIGN MODERNO OBBLIGATORIO:**
- Font: Google Fonts Poppins (importare sempre)
- Background: gradienti animati
- Hover effects su tutti gli elementi
- Transizioni smooth (0.3s ease)
- Box-shadow per profondità
- Border-radius per modernità

## IMMAGINI OBBLIGATORIE

**FONTI LIBERE DA COPYRIGHT:**
- Unsplash.com (sempre libere)
- Formato: `https://images.unsplash.com/photo-[ID]?w=400&h=250&fit=crop&crop=center`
- Fallback: placeholder colorati con testo

**POSIZIONAMENTO:**
- Header: immagine principale del gelato
- Sezioni: immagini correlate agli ingredienti
- Sempre con alt text descrittivo
- Sempre con onerror fallback

## ANIMAZIONI CSS OBBLIGATORIE

**Background animato:**
```css
@keyframes backgroundShift {
    0% { background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); }
    100% { background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%); }
}
```

**Elementi fluttuanti:**
```css
@keyframes float {
    0%, 100% { transform: translateY(0px) rotate(0deg); }
    50% { transform: translateY(-20px) rotate(180deg); }
}
```

**Hover effects:**
- Transform: translateY(-5px)
- Box-shadow: 0 15px 30px rgba(0,0,0,0.2)
- Transition: all 0.3s ease

## EMOJI OBBLIGATORIE PER INGREDIENTI

- 🥛 Latte e panna
- 🍯 Zuccheri (saccarosio, destrosio)
- ⚗️ Stabilizzanti (Gran Base)
- 🌟 Aromi e paste
- 🍷 Liquori
- 🍫 Cioccolato e cacao
- 💧 Acqua
- 🍪 Biscotti e dolci
- 🍓 Frutta (specifica per tipo)

## COLORI MODERNI

**Gradienti sezioni:**
- Ingredienti: `linear-gradient(135deg, #667eea, #764ba2)`
- Istruzioni: `linear-gradient(135deg, #f093fb, #f5576c)`
- Parametri: `linear-gradient(135deg, #4facfe, #00f2fe)`
- Note: `linear-gradient(135deg, #43e97b, #38f9d7)`

**Tabelle:**
- Background: rgba(255,255,255,0.95)
- Testo: #333 (nero leggibile)
- Header: rgba(0,0,0,0.8) con testo bianco
- Hover: #e3f2fd con transizione

## SISTEMA CATALOGAZIONE AUTOMATICA

**ANALISI AUTOMATICA TIPO GELATO:**
1. Analizza ingredienti principali della richiesta
2. Classifica automaticamente in categoria
3. Crea struttura directory appropriata
4. Genera file ricetta + simulazione collegati

**CATEGORIE AUTOMATICHE:**
- `/Ricette/Gelati/Creme/` → contiene latte+panna+aromi (vaniglia, nocciola, pistacchio, caffè, zuppa inglese)
- `/Ricette/Gelati/Frutta/` → contiene frutta fresca (fragola, pesca, limone, frutti di bosco)
- `/Ricette/Gelati/Sorbetti/` → base acqua+zuccheri+frutta (senza latte/panna)
- `/Ricette/Gelati/Speciali/` → ingredienti particolari (alcol, spezie, salati)
- `/Ricette/Gelati/Cioccolato/` → base cioccolato/cacao (fondente, latte, bianco)

**NOMI FILE AUTOMATICI:**
- Ricetta: `[Categoria]_[NomeGusto]_Ricetta.html`
- Simulazione: `[Categoria]_[NomeGusto]_Simulazione.html`
- Collegamento bidirezionale con pulsanti di navigazione

**AGGIORNAMENTO INDEX AUTOMATICO:**
- Ogni nuova ricetta aggiorna automaticamente gli index
- Contatori ricette sempre aggiornati
- Ordine alfabetico mantenuto automaticamente
- Template card standardizzato per coerenza visiva
- Navigazione sempre funzionante e completa

## RICERCA IMMAGINI INTELLIGENTE

**RICERCA SPECIFICA PER GUSTO:**
1. Cerca sempre "[nome gelato] ice cream unsplash" 
2. Cerca ingredienti specifici: "alchermes savoiardi trifle"
3. Cerca varianti: "italian dessert [nome]"
4. Usa ID Unsplash specifici quando trovati
5. Fallback su placeholder tematici

**IMMAGINI COERENTI OBBLIGATORIE:**
- Header: gelato del gusto specifico (non generico)
- Ingredienti: ingredienti tradizionali del dolce
- Processo: preparazione o risultato finale
- SEMPRE cercare online prima di usare generiche

## CONTROLLI QUALITÀ OBBLIGATORI

Prima di fornire HTML, verificare:
- ✅ Testo tabelle è NERO e leggibile
- ✅ Immagini specifiche per il gusto (non generiche)
- ✅ Immagini hanno src Unsplash validi e coerenti
- ✅ Immagini hanno fallback onerror tematici
- ✅ Font Poppins è importato
- ✅ Animazioni CSS sono presenti
- ✅ Hover effects funzionano
- ✅ Emoji sono presenti negli ingredienti
- ✅ Gradienti sono moderni e attraenti
- ✅ Directory categoria creata correttamente
- ✅ File ricetta e simulazione collegati
- ✅ Pulsanti navigazione funzionanti

**SE ANCHE SOLO UN CONTROLLO FALLISCE → RIFARE TUTTO!**