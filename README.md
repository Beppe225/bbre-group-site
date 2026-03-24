# bbre-group-site
## SEZIONE 1: HERO (Intestazione Principale)

```html
<div style="background: linear-gradient(135deg, #0A1929 0%, #1a2f42 100%); color: white; padding: 80px 20px; text-align: center; position: relative; overflow: hidden;">
    
    <!-- Background decorativo -->
    <div style="position: absolute; top: -50%; right: -20%; width: 80%; height: 150%; background: radial-gradient(circle, rgba(201, 169, 98, 0.1) 0%, transparent 70%); z-index: 1;"></div>
    
    <div style="position: relative; z-index: 2; max-width: 1200px; margin: 0 auto;">
        
        <!-- Titolo Principale -->
        <h1 style="font-family: Georgia, serif; font-size: 3.5rem; font-weight: 900; margin-bottom: 20px; line-height: 1.1;">
            Il Partner Strategico per i Tuoi 
            <span style="color: #C9A962; display: block; margin-top: 10px;">Investimenti Immobiliari</span>
        </h1>
        
        <!-- Sottotitolo -->
        <p style="font-size: 1.3rem; margin: 30px auto; max-width: 800px; opacity: 0.9; line-height: 1.8;">
            BBRE Group integra expertise immobiliare, finanziaria ed edile per offrire soluzioni complete. 
            Dalla ricerca dell'investimento alla ristrutturazione, dal finanziamento alla gestione patrimoniale.
        </p>
        
        <!-- Bottoni CTA -->
        <div style="margin-top: 40px; display: flex; gap: 20px; justify-content: center; flex-wrap: wrap;">
            <a href="#brands" style="background: #C9A962; color: white; padding: 15px 40px; text-decoration: none; border-radius: 4px; font-weight: 600; font-size: 1rem; display: inline-block;">
                Scopri i Nostri Servizi
            </a>
            <a href="#contact" style="background: transparent; color: white; padding: 15px 40px; text-decoration: none; border-radius: 4px; font-weight: 600; font-size: 1rem; border: 2px solid white; display: inline-block;">
                Contattaci
            </a>
        </div>
        
        <!-- Statistiche -->
        <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; margin-top: 60px;">
            <div style="background: rgba(255, 255, 255, 0.05); padding: 30px; border-radius: 8px; backdrop-filter: blur(10px); border: 1px solid rgba(255, 255, 255, 0.1);">
                <div style="font-family: Georgia, serif; font-size: 3rem; font-weight: 900; color: #C9A962; margin-bottom: 10px;">200+</div>
                <div style="font-size: 1rem;">Progetti Completati</div>
            </div>
            <div style="background: rgba(255, 255, 255, 0.05); padding: 30px; border-radius: 8px; backdrop-filter: blur(10px); border: 1px solid rgba(255, 255, 255, 0.1);">
                <div style="font-family: Georgia, serif; font-size: 3rem; font-weight: 900; color: #C9A962; margin-bottom: 10px;">€50M+</div>
                <div style="font-size: 1rem;">Valore Gestito</div>
            </div>
            <div style="background: rgba(255, 255, 255, 0.05); padding: 30px; border-radius: 8px; backdrop-filter: blur(10px); border: 1px solid rgba(255, 255, 255, 0.1);">
                <div style="font-family: Georgia, serif; font-size: 3rem; font-weight: 900; color: #C9A962; margin-bottom: 10px;">15+</div>
                <div style="font-size: 1rem;">Anni di Esperienza</div>
            </div>
        </div>
        
    </div>
</div>
```

**NOTA:** Dopo aver incollato questa sezione, potrebbe essere necessario adattare le dimensioni dei font per mobile. Google Sites dovrebbe gestirlo automaticamente, ma verifica in preview.

---

## SEZIONE 2: INTESTAZIONE BRAND

```html
<div style="padding: 80px 20px; background: white; text-align: center;">
    <div style="max-width: 800px; margin: 0 auto;">
        <div style="color: #C9A962; font-weight: 600; letter-spacing: 2px; text-transform: uppercase; font-size: 0.9rem; margin-bottom: 15px;">I NOSTRI BRAND</div>
        
        <h2 style="font-family: Georgia, serif; font-size: 3rem; font-weight: 900; color: #0A1929; margin-bottom: 20px;">
            Quattro Divisioni, Un Unico Obiettivo
        </h2>
        
        <p style="font-size: 1.2rem; color: #5A6C7D; line-height: 1.8;">
            Ogni brand BBRE è specializzato in un'area specifica, ma tutti lavorano in sinergia 
            per offrirti un servizio completo e integrato.
        </p>
    </div>
</div>
```

---

## SEZIONE 3: BRAND CARD - BBRE Immobiliare

```html
<div style="background: #FAFBFC; padding: 40px; border-radius: 12px; margin: 20px; border: 2px solid transparent; transition: all 0.3s;">
    
    <!-- Icona -->
    <div style="width: 70px; height: 70px; background: #C9A962; border-radius: 12px; display: flex; align-items: center; justify-content: center; font-size: 2rem; margin-bottom: 25px;">
        🏢
    </div>
    
    <!-- Titolo -->
    <h3 style="font-family: Georgia, serif; font-size: 2rem; font-weight: 700; color: #0A1929; margin-bottom: 15px;">
        BBRE Immobiliare
    </h3>
    
    <!-- Descrizione -->
    <p style="color: #5A6C7D; font-size: 1.05rem; line-height: 1.7; margin-bottom: 25px;">
        Investimenti immobiliari strategici, acquisizione di immobili da valorizzare, 
        sviluppo di progetti residenziali e commerciali su Milano e provincia.
    </p>
    
    <!-- Lista Features -->
    <ul style="list-style: none; padding: 0; margin-bottom: 25px;">
        <li style="padding: 8px 0; color: #2C3E50; display: flex; align-items: center; gap: 10px;">
            <span style="color: #C9A962; font-weight: bold;">✓</span>
            Ricerca opportunità immobiliari
        </li>
        <li style="padding: 8px 0; color: #2C3E50; display: flex; align-items: center; gap: 10px;">
            <span style="color: #C9A962; font-weight: bold;">✓</span>
            Due diligence urbanistica e legale
        </li>
        <li style="padding: 8px 0; color: #2C3E50; display: flex; align-items: center; gap: 10px;">
            <span style="color: #C9A962; font-weight: bold;">✓</span>
            Valutazione ROI e business plan
        </li>
        <li style="padding: 8px 0; color: #2C3E50; display: flex; align-items: center; gap: 10px;">
            <span style="color: #C9A962; font-weight: bold;">✓</span>
            Gestione aste giudiziarie
        </li>
        <li style="padding: 8px 0; color: #2C3E50; display: flex; align-items: center; gap: 10px;">
            <span style="color: #C9A962; font-weight: bold;">✓</span>
            Compravendita immobiliare
        </li>
    </ul>
    
    <!-- Link -->
    <a href="[INSERISCI URL PAGINA BBRE IMMOBILIARE]" style="color: #C9A962; font-weight: 600; text-decoration: none; display: inline-flex; align-items: center; gap: 8px;">
        Scopri di più →
    </a>
    
</div>
```

---

## SEZIONE 4: BRAND CARD - BBRE Finance

```html
<div style="background: #FAFBFC; padding: 40px; border-radius: 12px; margin: 20px; border: 2px solid transparent;">
    
    <div style="width: 70px; height: 70px; background: #C9A962; border-radius: 12px; display: flex; align-items: center; justify-content: center; font-size: 2rem; margin-bottom: 25px;">
        💰
    </div>
    
    <h3 style="font-family: Georgia, serif; font-size: 2rem; font-weight: 700; color: #0A1929; margin-bottom: 15px;">
        BBRE Finance
    </h3>
    
    <p style="color: #5A6C7D; font-size: 1.05rem; line-height: 1.7; margin-bottom: 25px;">
        Soluzioni finanziarie personalizzate: mutui, leasing, prestiti e finanziamenti 
        per privati, investitori e aziende.
    </p>
    
    <ul style="list-style: none; padding: 0; margin-bottom: 25px;">
        <li style="padding: 8px 0; color: #2C3E50; display: flex; align-items: center; gap: 10px;">
            <span style="color: #C9A962; font-weight: bold;">✓</span>
            Mutui prima casa e investimento
        </li>
        <li style="padding: 8px 0; color: #2C3E50; display: flex; align-items: center; gap: 10px;">
            <span style="color: #C9A962; font-weight: bold;">✓</span>
            Leasing immobiliare e strumentale
        </li>
        <li style="padding: 8px 0; color: #2C3E50; display: flex; align-items: center; gap: 10px;">
            <span style="color: #C9A962; font-weight: bold;">✓</span>
            Prestiti personali e aziendali
        </li>
        <li style="padding: 8px 0; color: #2C3E50; display: flex; align-items: center; gap: 10px;">
            <span style="color: #C9A962; font-weight: bold;">✓</span>
            Surroga e ristrutturazione mutui
        </li>
        <li style="padding: 8px 0; color: #2C3E50; display: flex; align-items: center; gap: 10px;">
            <span style="color: #C9A962; font-weight: bold;">✓</span>
            Consulenza finanziaria strategica
        </li>
    </ul>
    
    <a href="[INSERISCI URL PAGINA BBRE FINANCE]" style="color: #C9A962; font-weight: 600; text-decoration: none;">
        Scopri di più →
    </a>
    
</div>
```

---

## SEZIONE 5: BRAND CARD - BBRE Opere Edili

```html
<div style="background: #FAFBFC; padding: 40px; border-radius: 12px; margin: 20px; border: 2px solid transparent;">
    
    <div style="width: 70px; height: 70px; background: #C9A962; border-radius: 12px; display: flex; align-items: center; justify-content: center; font-size: 2rem; margin-bottom: 25px;">
        🔨
    </div>
    
    <h3 style="font-family: Georgia, serif; font-size: 2rem; font-weight: 700; color: #0A1929; margin-bottom: 15px;">
        BBRE Opere Edili
    </h3>
    
    <p style="color: #5A6C7D; font-size: 1.05rem; line-height: 1.7; margin-bottom: 25px;">
        Ristrutturazioni complete, nuove costruzioni, riqualificazioni energetiche 
        con gestione chiavi in mano del progetto.
    </p>
    
    <ul style="list-style: none; padding: 0; margin-bottom: 25px;">
        <li style="padding: 8px 0; color: #2C3E50; display: flex; align-items: center; gap: 10px;">
            <span style="color: #C9A962; font-weight: bold;">✓</span>
            Ristrutturazioni residenziali
        </li>
        <li style="padding: 8px 0; color: #2C3E50; display: flex; align-items: center; gap: 10px;">
            <span style="color: #C9A962; font-weight: bold;">✓</span>
            Frazionamenti e ampliamenti
        </li>
        <li style="padding: 8px 0; color: #2C3E50; display: flex; align-items: center; gap: 10px;">
            <span style="color: #C9A962; font-weight: bold;">✓</span>
            Efficientamento energetico
        </li>
        <li style="padding: 8px 0; color: #2C3E50; display: flex; align-items: center; gap: 10px;">
            <span style="color: #C9A962; font-weight: bold;">✓</span>
            Design e progettazione architettonica
        </li>
        <li style="padding: 8px 0; color: #2C3E50; display: flex; align-items: center; gap: 10px;">
            <span style="color: #C9A962; font-weight: bold;">✓</span>
            Gestione pratiche edilizie
        </li>
    </ul>
    
    <a href="[INSERISCI URL PAGINA BBRE OPERE EDILI]" style="color: #C9A962; font-weight: 600; text-decoration: none;">
        Scopri di più →
    </a>
    
</div>
```

---

## SEZIONE 6: BRAND CARD - BBRE Consulenza Credito

```html
<div style="background: #FAFBFC; padding: 40px; border-radius: 12px; margin: 20px; border: 2px solid transparent;">
    
    <div style="width: 70px; height: 70px; background: #C9A962; border-radius: 12px; display: flex; align-items: center; justify-content: center; font-size: 2rem; margin-bottom: 25px;">
        📊
    </div>
    
    <h3 style="font-family: Georgia, serif; font-size: 2rem; font-weight: 700; color: #0A1929; margin-bottom: 15px;">
        BBRE Consulenza Credito
    </h3>
    
    <p style="color: #5A6C7D; font-size: 1.05rem; line-height: 1.7; margin-bottom: 25px;">
        Gestione del credito aziendale e privato, pianificazione finanziaria, 
        ristrutturazione del debito e ottimizzazione fiscale.
    </p>
    
    <ul style="list-style: none; padding: 0; margin-bottom: 25px;">
        <li style="padding: 8px 0; color: #2C3E50; display: flex; align-items: center; gap: 10px;">
            <span style="color: #C9A962; font-weight: bold;">✓</span>
            Analisi e gestione del credito
        </li>
        <li style="padding: 8px 0; color: #2C3E50; display: flex; align-items: center; gap: 10px;">
            <span style="color: #C9A962; font-weight: bold;">✓</span>
            Ristrutturazione posizioni debitorie
        </li>
        <li style="padding: 8px 0; color: #2C3E50; display: flex; align-items: center; gap: 10px;">
            <span style="color: #C9A962; font-weight: bold;">✓</span>
            Pianificazione patrimoniale
        </li>
        <li style="padding: 8px 0; color: #2C3E50; display: flex; align-items: center; gap: 10px;">
            <span style="color: #C9A962; font-weight: bold;">✓</span>
            Ottimizzazione fiscale immobiliare
        </li>
        <li style="padding: 8px 0; color: #2C3E50; display: flex; align-items: center; gap: 10px;">
            <span style="color: #C9A962; font-weight: bold;">✓</span>
            Consulenza creditizia strategica
        </li>
    </ul>
    
    <a href="[INSERISCI URL PAGINA BBRE CONSULENZA]" style="color: #C9A962; font-weight: 600; text-decoration: none;">
        Scopri di più →
    </a>
    
</div>
```

---

## SEZIONE 7: CHI SIAMO

```html
<div style="padding: 80px 20px; background: linear-gradient(135deg, #0A1929 0%, #1a2f42 100%); color: white;">
    <div style="max-width: 1200px; margin: 0 auto; display: grid; grid-template-columns: 1fr 1fr; gap: 50px; align-items: center;">
        
        <!-- Testo -->
        <div>
            <h2 style="font-family: Georgia, serif; font-size: 3rem; font-weight: 900; margin-bottom: 30px;">
                Chi Siamo
            </h2>
            
            <p style="font-size: 1.15rem; line-height: 1.9; margin-bottom: 20px; opacity: 0.9;">
                BBRE Group nasce dall'esperienza consolidata nel settore immobiliare, finanziario ed edilizio, 
                con l'obiettivo di offrire un servizio integrato e completo ai propri clienti.
            </p>
            
            <p style="font-size: 1.15rem; line-height: 1.9; margin-bottom: 20px; opacity: 0.9;">
                La nostra forza risiede nella capacità di gestire ogni fase del processo: dall'individuazione 
                dell'opportunità immobiliare, al finanziamento, alla realizzazione dei lavori, fino alla gestione 
                e alla vendita finale.
            </p>
            
            <p style="font-size: 1.15rem; line-height: 1.9; opacity: 0.9;">
                Operiamo principalmente su Milano e provincia, con un team di professionisti specializzati 
                in ogni area di competenza: ingegneri, architetti, commercialisti, consulenti finanziari e legali.
            </p>
        </div>
        
        <!-- Valori -->
        <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px;">
            <div style="padding: 30px; background: rgba(255, 255, 255, 0.05); border-radius: 8px; backdrop-filter: blur(10px); border: 1px solid rgba(255, 255, 255, 0.1);">
                <h4 style="font-size: 1.3rem; margin-bottom: 12px; color: #C9A962;">Esperienza</h4>
                <p style="font-size: 0.95rem; line-height: 1.6;">Oltre 15 anni di operazioni immobiliari, edili e finanziarie con risultati certificati.</p>
            </div>
            
            <div style="padding: 30px; background: rgba(255, 255, 255, 0.05); border-radius: 8px; backdrop-filter: blur(10px); border: 1px solid rgba(255, 255, 255, 0.1);">
                <h4 style="font-size: 1.3rem; margin-bottom: 12px; color: #C9A962;">Trasparenza</h4>
                <p style="font-size: 0.95rem; line-height: 1.6;">Ogni operazione è documentata, ogni valutazione è certificata, ogni promessa è mantenuta.</p>
            </div>
            
            <div style="padding: 30px; background: rgba(255, 255, 255, 0.05); border-radius: 8px; backdrop-filter: blur(10px); border: 1px solid rgba(255, 255, 255, 0.1);">
                <h4 style="font-size: 1.3rem; margin-bottom: 12px; color: #C9A962;">Integrazione</h4>
                <p style="font-size: 0.95rem; line-height: 1.6;">Un unico interlocutore per tutte le tue esigenze: immobiliari, finanziarie ed edili.</p>
            </div>
            
            <div style="padding: 30px; background: rgba(255, 255, 255, 0.05); border-radius: 8px; backdrop-filter: blur(10px); border: 1px solid rgba(255, 255, 255, 0.1);">
                <h4 style="font-size: 1.3rem; margin-bottom: 12px; color: #C9A962;">Risultati</h4>
                <p style="font-size: 0.95rem; line-height: 1.6;">Focus sul ROI concreto: ogni progetto è studiato per massimizzare il ritorno sull'investimento.</p>
            </div>
        </div>
        
    </div>
</div>
```

**NOTA:** Per mobile, questa sezione potrebbe richiedere uno stacking verticale. Google Sites dovrebbe gestirlo automaticamente.

---

## SEZIONE 8: CALL TO ACTION FINALE

```html
<div style="padding: 80px 20px; background: white; text-align: center;">
    <div style="max-width: 900px; margin: 0 auto;">
        
        <h2 style="font-family: Georgia, serif; font-size: 3.5rem; font-weight: 900; color: #0A1929; margin-bottom: 30px;">
            Inizia il Tuo Progetto
        </h2>
        
        <p style="font-size: 1.3rem; color: #5A6C7D; margin-bottom: 40px;">
            Che tu sia un investitore, un proprietario immobiliare o un privato, 
            BBRE Group ha la soluzione giusta per te.
        </p>
        
        <div style="display: flex; gap: 20px; justify-content: center; flex-wrap: wrap;">
            <a href="mailto:barbieri@bbre.it" style="background: #C9A962; color: white; padding: 15px 40px; text-decoration: none; border-radius: 4px; font-weight: 600; font-size: 1.1rem;">
                Richiedi Consulenza Gratuita
            </a>
            <a href="tel:+393358083125" style="background: transparent; color: #0A1929; padding: 15px 40px; text-decoration: none; border-radius: 4px; font-weight: 600; font-size: 1.1rem; border: 2px solid #0A1929;">
                Chiamaci Ora
            </a>
        </div>
        
    </div>
</div>
```

---

## SEZIONE 9: FOOTER

```html
<div style="background: #0A1929; color: rgba(255, 255, 255, 0.8); padding: 60px 20px 30px;">
    <div style="max-width: 1400px; margin: 0 auto; display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 40px; margin-bottom: 40px;">
        
        <!-- Brand -->
        <div>
            <h3 style="font-family: Georgia, serif; font-size: 2rem; color: white; margin-bottom: 15px;">BBRE Group</h3>
            <p style="line-height: 1.8; margin-bottom: 20px;">
                Real Estate, Finance & Construction Excellence.<br>
                Il partner strategico per i tuoi investimenti immobiliari.
            </p>
            <p>
                <strong style="color: white;">Sede Operativa:</strong><br>
                Via Valosa di sopra, 26 — 20900 Monza (MB)<br>
                P.IVA: 13621430969
            </p>
        </div>
        
        <!-- Brand Links -->
        <div>
            <h4 style="color: white; font-weight: 600; margin-bottom: 20px;">Brand</h4>
            <ul style="list-style: none; padding: 0;">
                <li style="margin-bottom: 12px;">
                    <a href="[URL BBRE IMMOBILIARE]" style="color: rgba(255, 255, 255, 0.7); text-decoration: none;">BBRE Immobiliare</a>
                </li>
                <li style="margin-bottom: 12px;">
                    <a href="[URL BBRE FINANCE]" style="color: rgba(255, 255, 255, 0.7); text-decoration: none;">BBRE Finance</a>
                </li>
                <li style="margin-bottom: 12px;">
                    <a href="[URL BBRE OPERE]" style="color: rgba(255, 255, 255, 0.7); text-decoration: none;">BBRE Opere Edili</a>
                </li>
                <li style="margin-bottom: 12px;">
                    <a href="[URL BBRE CONSULENZA]" style="color: rgba(255, 255, 255, 0.7); text-decoration: none;">BBRE Consulenza Credito</a>
                </li>
            </ul>
        </div>
        
        <!-- Servizi -->
        <div>
            <h4 style="color: white; font-weight: 600; margin-bottom: 20px;">Servizi</h4>
            <ul style="list-style: none; padding: 0;">
                <li style="margin-bottom: 12px;">Investimenti Immobiliari</li>
                <li style="margin-bottom: 12px;">Ristrutturazioni</li>
                <li style="margin-bottom: 12px;">Finanziamenti</li>
                <li style="margin-bottom: 12px;">Consulenza Credito</li>
                <li style="margin-bottom: 12px;">Gestione Patrimoni</li>
            </ul>
        </div>
        
        <!-- Contatti -->
        <div>
            <h4 style="color: white; font-weight: 600; margin-bottom: 20px;">Contatti</h4>
            <ul style="list-style: none; padding: 0;">
                <li style="margin-bottom: 12px;">
                    <a href="mailto:barbieri@bbre.it" style="color: rgba(255, 255, 255, 0.7); text-decoration: none;">barbieri@bbre.it</a>
                </li>
                <li style="margin-bottom: 12px;">
                    <a href="tel:+393358083125" style="color: rgba(255, 255, 255, 0.7); text-decoration: none;">+39 335 808 3125</a>
                </li>
                <li style="margin-bottom: 12px;">
                    <a href="[LINKEDIN URL]" style="color: rgba(255, 255, 255, 0.7); text-decoration: none;">LinkedIn</a>
                </li>
                <li style="margin-bottom: 12px;">
                    <a href="[INSTAGRAM URL]" style="color: rgba(255, 255, 255, 0.7); text-decoration: none;">Instagram</a>
                </li>
            </ul>
        </div>
        
    </div>
    
    <!-- Footer Bottom -->
    <div style="text-align: center; padding-top: 30px; border-top: 1px solid rgba(255, 255, 255, 0.1); font-size: 0.9rem;">
        <p>&copy; 2026 BBRE Group SRL. Tutti i diritti riservati. | Privacy Policy | Cookie Policy</p>
    </div>
</div>
```

---

## 📋 ISTRUZIONI PASSO-PASSO PER GOOGLE SITES

### 1. PREPARAZIONE
- Apri Google Sites
- Crea un nuovo sito o apri quello esistente
- Assicurati di essere in modalità "Modifica"

### 2. INSERIMENTO SEZIONI
Per ogni sezione sopra:

**METODO A - Embed HTML (Consigliato):**
1. Clicca su "Inserisci" nel menu laterale
2. Seleziona "Embed"
3. Scegli "Incorpora codice"
4. Copia il codice della sezione
5. Incolla nel campo "Embed code"
6. Clicca "Inserisci"
7. Ridimensiona/posiziona la sezione

**METODO B - Blocchi Nativi (Se Embed non funziona):**
1. Usa i blocchi nativi di Google Sites per ricreare il layout
2. Copia solo il testo e formattalo manualmente
3. Aggiungi colori e stili usando gli strumenti di Google Sites

### 3. PERSONALIZZAZIONE
- Sostituisci `[DA INSERIRE]` con i tuoi dati reali
- Sostituisci `[URL ...]` con i link alle tue pagine
- Aggiungi il tuo logo
- Inserisci foto reali dei progetti

### 4. RESPONSIVE CHECK
- Clicca su "Anteprima" in alto a destra
- Testa su: Desktop, Tablet, Mobile
- Aggiusta spaziature se necessario

### 5. PUBBLICAZIONE
- Clicca "Pubblica" in alto a destra
- Scegli l'URL del sito
- Pubblica!

---

## ⚠️ LIMITAZIONI GOOGLE SITES DA CONOSCERE

**NON supportato:**
- JavaScript personalizzato (animazioni complesse)
- CSS avanzato (gradient complessi, blur effects)
- Font esterni via CDN (usa font Google integrati)

**Workaround:**
- Usa le animazioni native di Google Sites
- Usa colori solidi invece di gradient complessi
- Usa font della libreria Google Sites

---

## 🎨 PALETTE COLORI DA USARE

Salva questi codici colore nelle impostazioni tema di Google Sites:

**Colore Primario:** `#0A1929` (Navy scuro)
**Colore Secondario:** `#C9A962` (Gold/Bronzo)
**Testo:** `#2C3E50` (Grigio scuro)
**Testo Chiaro:** `#5A6C7D` (Grigio medio)
**Background:** `#FAFBFC` (Grigio chiarissimo)
**Bianco:** `#FFFFFF`

---

## 📞 CONTATTI

I dati reali già inseriti in tutte le sezioni:

- Email: `barbieri@bbre.it` ✅
- Telefono: `+39 335 808 3125` ✅
- Indirizzo: `Via Valosa di sopra, 26 — 20900 Monza (MB)` ✅
- P.IVA: `13621430969` ✅

---

## ✅ CHECKLIST FINALE

Prima di pubblicare, verifica:

- [ ] Tutti i link funzionano
- [x] Email: barbieri@bbre.it ✅
- [x] Telefono: +39 335 808 3125 ✅
- [x] Indirizzo: Via Valosa di sopra, 26 — Monza ✅
- [x] P.IVA: 13621430969 ✅
- [ ] URL brand inseriti (4 pagine)
- [ ] LinkedIn e Instagram inseriti
- [ ] Responsive ok su mobile
- [ ] Immagini caricate
- [ ] Logo inserito
- [ ] SEO: titolo pagina, meta description
- [ ] Google Analytics installato

---

## 💡 TIPS PRO

1. **Immagini:** Usa Unsplash/Pexels per foto professionali gratuite
2. **Logo:** Crea logo semplice su Canva (gratuito)
3. **Form Contatti:** Usa Google Forms integrato
4. **Analytics:** Aggiungi Google Analytics dalle impostazioni sito
5. **SEO:** Compila "Impostazioni sito" → Meta description e keywords
