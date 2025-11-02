# 🤖 Tutorial Interattivo: Architettura Transformer

Un tutorial interattivo e visuale per comprendere l'architettura Transformer, introdotta nel paper "Attention is All You Need" (2017).

## 📋 Descrizione

Questo progetto offre un tutorial completamente interattivo che ti permette di esplorare visivamente come funziona l'architettura Transformer, alla base di modelli moderni come GPT, BERT, e molti altri.

## ✨ Caratteristiche

- **Visualizzazione Interattiva**: Clicca su ogni componente per esplorare spiegazioni dettagliate
- **Animazioni**: Osserva il flusso dei dati attraverso l'encoder e il decoder
- **Demo di Traduzione**: Vedi come il Transformer traduce da una lingua all'altra
- **Visualizzazione Q, K, V**: Esplora le matrici Query, Key e Value in dettaglio
- **Confronto RNN vs Transformer**: Capisci i vantaggi dei Transformer rispetto alle RNN
- **Playground Attention**: Sperimenta con i meccanismi di attention in tempo reale
- **Multi-Head Detail**: Visualizza come ogni testa di attention cattura pattern diversi
- **Positional Encoding 3D**: Visualizzazione interattiva del positional encoding
- **Simulazione Training**: Osserva il processo di addestramento con loss curves
- **Calcolatore di Complessità**: Calcola FLOPS, memoria e tempo per il tuo modello
- **Quiz Interattivo**: Testa la tua comprensione dei concetti
- **Code View**: Visualizza implementazioni in PyTorch, TensorFlow e pseudo-code
- **Debug Mode**: Ispeziona i tensori step-by-step attraverso la rete

## 🚀 Come Avviare il Progetto in Locale

### Prerequisiti

- Un browser web moderno (Chrome, Firefox, Safari, Edge)
- Nessuna installazione richiesta! È tutto HTML, CSS e JavaScript vanilla

### Metodo 1: Apertura Diretta (Più Semplice)

1. **Scarica il repository**:
   ```bash
   git clone https://github.com/TheEmilz/capire_transformers.git
   cd capire_transformers
   ```

2. **Apri il file HTML**:
   - Fai doppio click su `v6.html`
   - Oppure trascinalo nel tuo browser
   - Oppure clicca con il tasto destro → "Apri con" → Seleziona il tuo browser

3. **Inizia a esplorare!** 🎉

### Metodo 2: Server HTTP Locale (Raccomandato)

Sebbene non sia strettamente necessario, usare un server HTTP locale può garantire il funzionamento ottimale:

**Con Python 3**:
```bash
cd capire_transformers
python3 -m http.server 8000
```

**Con Python 2**:
```bash
cd capire_transformers
python -m SimpleHTTPServer 8000
```

**Con Node.js (usando npx)**:
```bash
cd capire_transformers
npx http-server -p 8000
```

**Con PHP**:
```bash
cd capire_transformers
php -S localhost:8000
```

Poi apri il browser e visita: `http://localhost:8000/v6.html`

## 🎮 Come Usare il Tutorial

1. **Esplora i Componenti**: Clicca su ogni blocco (Input, Embedding, Attention, ecc.) per vedere spiegazioni dettagliate
2. **Anima il Flusso**: Usa il pulsante "▶️ Anima Flusso Dati" per vedere come i dati si muovono attraverso la rete
3. **Demo Interattive**: Prova tutte le demo disponibili:
   - 🌍 Demo Traduzione
   - 🔍 Visualizza Q, K, V
   - 🔄 RNN vs Transformer
   - 🎮 Playground Attention
   - 🎯 Multi-Head Detail
   - 📊 Positional Encoding 3D
   - 📈 Training Visualization
   - 🧮 Complexity Calculator
   - 🎓 Quiz
   - 💻 Code View
   - 🐛 Debug Mode
4. **Impara con il Quiz**: Testa la tua comprensione con domande interattive

## 🌐 Compatibilità Browser

Il tutorial funziona su tutti i browser moderni:

- ✅ Google Chrome (versione 90+)
- ✅ Mozilla Firefox (versione 88+)
- ✅ Safari (versione 14+)
- ✅ Microsoft Edge (versione 90+)
- ✅ Opera (versione 76+)

## 📱 Responsive Design

Il tutorial è ottimizzato per:
- 💻 Desktop
- 📱 Tablet
- 📱 Smartphone (alcune visualizzazioni sono adattate per schermi piccoli)

## 🎯 Cosa Imparerai

- Come funziona il meccanismo di **Self-Attention**
- L'architettura completa del **Transformer** (Encoder e Decoder)
- Il concetto di **Multi-Head Attention**
- Come funziona il **Positional Encoding**
- Le differenze tra **Transformer e RNN**
- La **complessità computazionale** dell'architettura
- Come il Transformer viene utilizzato in **traduzione**, **generazione di testo**, e altro

## 🔧 Tecnologie Utilizzate

- **HTML5**: Struttura della pagina
- **CSS3**: Styling e animazioni (gradients, transitions, animations)
- **JavaScript Vanilla**: Tutta la logica interattiva e le visualizzazioni
- **Canvas API**: Per visualizzazioni 3D e grafici

## 📚 Risorse Aggiuntive

- [Paper originale: "Attention is All You Need"](https://arxiv.org/abs/1706.03762)
- [The Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/)
- [Transformer Architecture - Documentazione PyTorch](https://pytorch.org/docs/stable/generated/torch.nn.Transformer.html)

## 🤝 Contribuire

Contributi, issues e feature requests sono benvenuti!

## 📄 Licenza

Questo progetto è distribuito sotto licenza MIT. Vedi il file `LICENSE` per maggiori dettagli.

## 👨‍💻 Autore

**TheEmilz**

---

⭐ Se trovi utile questo progetto, lascia una stella su GitHub!
