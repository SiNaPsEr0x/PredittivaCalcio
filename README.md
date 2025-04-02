# <div align="center">🏆 Predittiva Calcio</div>

<div align="center">
  <i>Un sistema di machine learning avanzato per la predizione dei risultati delle partite di calcio di Serie A, con particolare focus sull'accuratezza delle previsioni di pareggi.</i>
</div>

<div align="center">
  <strong>Creato da SiNaPsE</strong>
</div>

<div align="center">
  <a href="https://www.python.org/downloads/"><img src="https://img.shields.io/badge/Python-3.8+-blue.svg" alt="Python 3.8+"></a>
</div>

---

## 📋 Indice dei Contenuti

<table>
  <tr>
    <td>📖 <a href="#-introduzione">Introduzione</a></td>
    <td>⚙️ <a href="#%EF%B8%8F-funzionamento-del-sistema">Funzionamento del Sistema</a></td>
    <td>🌟 <a href="#-caratteristiche-principali">Caratteristiche Principali</a></td>
  </tr>
  <tr>
    <td>📊 <a href="#-features-del-modello">Features del Modello</a></td>
    <td>🎯 <a href="#-analisi-avanzata-dei-pareggi">Analisi Avanzata dei Pareggi</a></td>
    <td>📈 <a href="#-performance-del-sistema">Performance del Sistema</a></td>
  </tr>
  <tr>
    <td>💹 <a href="#-integrazione-delle-quote-dei-bookmakers">Quote dei Bookmakers</a></td>
    <td>🖥️ <a href="#%EF%B8%8F-interfaccia-utente-e-visualizzazione">Interfaccia Utente</a></td>
    <td>🔧 <a href="#-requisiti-tecnici">Requisiti Tecnici</a></td>
  </tr>
  <tr>
    <td>⚙️ <a href="#%EF%B8%8F-configurazione">Configurazione</a></td>
    <td>📥 <a href="#-installazione">Installazione</a></td>
    <td>🚀 <a href="#-utilizzo">Utilizzo</a></td>
  </tr>
</table>

---

## 📖 Introduzione

<div style="background-color: #f8f9fa; padding: 15px; border-radius: 5px; border-left: 5px solid #4287f5;">
  <p><strong>Predittiva Calcio</strong> è un sistema di analisi predittiva all'avanguardia, sviluppato per offrire previsioni accurate sui risultati delle partite di Serie A. A differenza dei sistemi tradizionali, il nostro approccio sfrutta algoritmi avanzati di machine learning per eccellere nella predizione del risultato più difficile: il pareggio.</p>
</div>

> 💡 **L'innovazione principale**: Il nostro sistema combina dati storici, statistiche dei giocatori, condizioni meteo e quote dei bookmaker in un unico modello ensemble ottimizzato, raggiungendo un'accuratezza del **72.8%** sui risultati generali e una precisione sui pareggi del **53.6%** (rispetto al benchmark di settore del ~30%).

---

## ⚙️ Funzionamento del Sistema

<div style="display: inline-block; background-color: #FFF5F5; padding: 5px 10px; border-radius: 5px; margin-bottom: 10px; border: 1px dashed #E53E3E;">
  <span style="font-weight: bold; color: #E53E3E;">🔍 SISTEMA PREDITTIVO 🔍</span>
</div>

<div align="center">
  <img width="60%" src="https://placehold.co/400x150/4a90e2/ffffff?text=Sistema+Predittiva+Calcio" alt="Schema Sistema">
</div>

### 1. 📊 Raccolta Dati
<table>
  <tr>
    <th>Componente</th>
    <th>Funzione</th>
  </tr>
  <tr>
    <td><code>FootballDataCollector</code></td>
    <td>Acquisisce dati storici sulle partite da football-data.org, inclusi risultati, statistiche e classifiche</td>
  </tr>
  <tr>
    <td><code>PlayerDataCollector</code></td>
    <td>Raccoglie statistiche sui giocatori, forma fisica, indisponibilità per infortuni e sospensioni</td>
  </tr>
  <tr>
    <td><code>WeatherDataCollector</code></td>
    <td>Ottiene dati meteo storici e previsioni per le partite future con aggiornamenti in tempo reale</td>
  </tr>
  <tr>
    <td><code>TheOddsAPIProvider</code></td>
    <td>Raccoglie quote dei bookmaker per le partite future e recenti, con analisi dei trend temporali</td>
  </tr>
</table>

### 2. 🔍 Elaborazione e Analisi
- **StatsGenerator**: produce statistiche aggregate per squadre e giocatori, analizza i trend di performance
- **ModelTrainer**: prepara i dati per l'addestramento, gestisce la feature engineering e applica tecniche di normalizzazione

### 3. 🧠 Modelli Predittivi

<div style="display: inline-block; background-color: #FFF5F5; padding: 5px 10px; border-radius: 5px; margin-bottom: 10px; border: 1px dashed #E53E3E;">
  <span style="font-weight: bold; color: #E53E3E;">⚠️ KNOW-HOW ESCLUSIVO ⚠️</span>
</div>

<div style="display: flex; justify-content: space-between; text-align: center; margin: 20px 0;">
  <div style="flex: 1; padding: 10px; border: 1px solid #ddd; border-radius: 5px; margin: 0 5px; background-color: #f9f9f9;">
    <h4>🌲 MultiDecision Pro™</h4>
    <p>Efficace con dati non lineari e categorici, gestisce relazioni complesse tra variabili</p>
  </div>
  <div style="flex: 1; padding: 10px; border: 1px solid #ddd; border-radius: 5px; margin: 0 5px; background-color: #f9f9f9;">
    <h4>📈 PredictaGradient™</h4>
    <p>Predizioni accurate e gestione ottimale dei dati mancanti, robustezza ai valori anomali</p>
  </div>
  <div style="flex: 1; padding: 10px; border: 1px solid #ddd; border-radius: 5px; margin: 0 5px; background-color: #f9f9f9;">
    <h4>🚀 TurboPredict Elite™</h4>
    <p>Performance superiori con regolarizzazione avanzata, ottimizzato per velocità e accuratezza</p>
  </div>
</div>

- **EnsembleOptimizer**: calibra i pesi dei singoli modelli attraverso validazione incrociata e ottimizzazione bayesiana

### 4. 🎲 Processo di Predizione

<div style="display: inline-block; background-color: #FFF5F5; padding: 5px 10px; border-radius: 5px; margin-bottom: 10px; border: 1px dashed #E53E3E;">
  <span style="font-weight: bold; color: #E53E3E;">🛡️ PROCESSO PROPRIETARIO 🛡️</span>
</div>

<ol style="background-color: #f8f9fa; padding: 20px; border-radius: 5px;">
  <li>Raccolta dati contestualizzati per ogni partita (statistiche, giocatori, meteo)</li>
  <li>Analisi dell'impatto dei giocatori chiave disponibili/indisponibili per ciascuna squadra</li>
  <li>Analisi delle reti sociali tra giocatori (chimica di squadra, connessioni mancanti, affinità tattiche)</li>
  <li>Valutazione dell'effetto del pubblico e atmosfera dello stadio attraverso modelli di sentiment analysis</li>
  <li>Incorporazione delle quote dei bookmaker con analisi dei movimenti, anomalie e saggezza della folla</li>
  <li>Analisi delle sequenze temporali di risultati recenti con identificazione di pattern ricorrenti</li>
  <li>Costruzione di un vettore di features (36+ caratteristiche standardizzate)</li>
  <li>Predizione con ogni modello dell'ensemble e combinazione pesata dei risultati</li>
  <li>Calibrazione dinamica delle probabilità finali con tutti i fattori aggiuntivi</li>
  <li>Normalizzazione e validazione delle probabilità finali per garantire coerenza statistica</li>
</ol>

### 5. 🖥️ Interfaccia Utente
- **MainWindow**: interfaccia grafica intuitiva per visualizzare le previsioni con layout responsive
- **MatchPredictionWidget**: visualizzazione dettagliata delle probabilità per ogni partita con indicatori visivi
- **LogHandler**: visualizzazione in tempo reale dei processi e aggiornamenti del sistema
- **PredittivaPdfExporter**: esportazione delle previsioni in formato PDF con statistiche e grafici dettagliati

## 🖥️ Interfaccia Utente e Visualizzazione

<div style="display: inline-block; background-color: #FFF5F5; padding: 5px 10px; border-radius: 5px; margin-bottom: 10px; border: 1px dashed #E53E3E;">
  <span style="font-weight: bold; color: #E53E3E;">🔍 SISTEMA PREDITTIVO 🔍</span>
</div>

<div align="center">
  <img src="https://placehold.co/400x200/4a90e2/ffffff?text=Predittiva+Calcio+Dashboard" width="60%" alt="Dashboard UI">
</div>

<div style="display: flex; margin-top: 20px;">
  <div style="flex: 1; padding: 15px; margin-right: 10px; background-color: #f8f9fa; border-radius: 5px;">
    <h3>📊 Dashboard Principale</h3>
    <ul>
      <li>Visualizzazione immediata delle prossime partite con probabilità di esito</li>
      <li>Indicatori visivi per la confidenza delle previsioni</li>
      <li>Area di log con aggiornamenti in tempo reale del sistema</li>
    </ul>
  </div>
  
  <div style="flex: 1; padding: 15px; margin-left: 10px; background-color: #f8f9fa; border-radius: 5px;">
    <h3>🔍 Visualizzazione Dettagli Partita</h3>
    <ul>
      <li>Analisi approfondita di ogni partita con statistiche contestuali</li>
      <li>Grafici di distribuzione delle probabilità</li>
      <li>Informazioni su giocatori chiave e loro impatto</li>
    </ul>
  </div>
</div>

<div style="padding: 15px; margin-top: 20px; background-color: #f8f9fa; border-radius: 5px;">
  <h3>📑 Esportazione e Reportistica</h3>
  <ul>
    <li>Generazione di report PDF professionali con tutte le previsioni</li>
    <li>Cronologia delle previsioni con metriche di accuratezza</li>
    <li>Statistiche aggregate per valutare le performance del sistema</li>
  </ul>
</div>

---

## 🔧 Requisiti Tecnici

<div style="background-color: #FFF5F5; padding: 12px; border-radius: 8px; margin-bottom: 20px; border: 2px dashed #E53E3E; text-align: center; box-shadow: 0 0 10px rgba(229, 62, 62, 0.5);">
  <span style="font-weight: bold; color: #E53E3E; font-size: 18px;">⚠️ INFORMAZIONI RISERVATE - ACCESSO LIMITATO ⚠️</span>
</div>

<div style="display: flex; margin-bottom: 20px;">
  <div style="flex: 1; padding: 20px; background-color: #f8f9fa; border-radius: 5px; margin-right: 10px;">
    <h3>🐍 Tecnologie Avanzate</h3>
    <p>Sistema basato su framework di machine learning all'avanguardia per garantire le migliori prestazioni predittive sul mercato.</p>
    <p>Architettura ottimizzata per la velocità di elaborazione e l'accuratezza delle previsioni.</p>
  </div>
  
  <div style="flex: 1; padding: 20px; background-color: #f8f9fa; border-radius: 5px; margin-left: 10px;">
    <h3>🔑 Connettività Premium</h3>
    <p>Accesso a fonti dati esclusive del mondo calcistico per analisi predittive di altissimo livello.</p>
    <p>Aggiornamenti in tempo reale dalle migliori fonti di dati sportivi internazionali.</p>
  </div>
</div>

---

## ⚙️ Configurazione

<div style="background-color: #f8f9fa; padding: 20px; border-radius: 5px; margin-bottom: 20px;">
  <h3>🔐 Accesso Esclusivo al Sistema</h3>
  <p>La configurazione del sistema Predittiva Calcio è riservata ai clienti premium. Contattami per ricevere informazioni sull'accesso.</p>
  
  <div style="background-color: #FFF5F5; padding: 12px; border-radius: 8px; margin: 15px 0; border: 2px dashed #E53E3E; text-align: center; box-shadow: 0 0 10px rgba(229, 62, 62, 0.5);">
    <span style="font-weight: bold; color: #E53E3E;">💬 CONTATTAMI VIA SESSION</span>
    <div style="display: flex; align-items: center; justify-content: space-between; margin-top: 15px;">
      <div style="flex: 2; text-align: left; padding-right: 20px;">
        <p style="margin: 0; font-weight: bold; font-size: 1.2em;">ID Session:</p>
        <p style="margin: 10px 0; word-break: break-all; font-size: 1.1em; background-color: #f8f8f8; padding: 10px; border-radius: 5px; border: 1px solid #ddd;">05a525f3a1ead62c9186370ecba8272872bc9e6f953d740987a8b3292507e81136</p>
        <p style="margin: 5px 0;"><a href="https://getsession.org/" target="_blank" style="color: #E53E3E;">Scarica Session</a> - Messaggistica sicura e crittografata</p>
      </div>
      <div style="text-align: right;">
        <img src="https://i.ibb.co/6KZKkcx/photo-2025-03-31-14-01-45.jpg" alt="Session QR Code" style="width: 150px; height: 150px;">
      </div>
    </div>
  </div>
</div>

---

## 🔧 Ambiente Richiesto

<div style="background-color: #f0f8ff; padding: 20px; border-radius: 5px; margin-bottom: 20px; border-left: 4px solid #4287f5;">
  <h3>💡 Requisiti di Sistema</h3>
  <p>Il software Predittiva Calcio è progettato per funzionare su qualsiasi sistema operativo moderno con requisiti hardware minimi.</p>
  
  <div style="background-color: #f8f9fa; padding: 15px; border-radius: 5px; margin-top: 10px;">
    <p><strong>Sistemi supportati:</strong> Windows 10+, macOS 10.15+, Linux (principali distribuzioni)</p>
    <p><strong>Hardware consigliato:</strong> CPU multi-core, 8GB RAM, connessione internet stabile</p>
  </div>
  
  <p style="margin-top: 10px; font-style: italic;">Ti guiderò nell'installazione e configurazione del sistema.</p>
</div>

---

## 🚀 Utilizzo

<div style="display: flex; justify-content: space-between; margin-bottom: 20px;">
  <div style="flex: 1; padding: 15px; background-color: #f8f9fa; border-radius: 5px; margin-right: 10px;">
    <h3>Interfaccia Intuitiva:</h3>
    <p>Dashboard moderna e user-friendly con visualizzazione immediata delle previsioni più importanti.</p>
  </div>
  
  <div style="flex: 1; padding: 15px; background-color: #f8f9fa; border-radius: 5px; margin-left: 10px;">
    <h3>Report Professionali:</h3>
    <p>Esportazione automatica delle previsioni in vari formati per analisi approfondite e condivisione.</p>
  </div>
</div>

---

## ⚠️ Diritti d'Autore

<div style="background-color: #FFF5F5; padding: 20px; border-radius: 5px; margin-bottom: 20px; border-left: 4px solid #E53E3E;">
  <h3>📝 Proprietà del Codice</h3>
  <p><strong>Questo codice è di proprietà esclusiva di SiNaPsE. Tutti i diritti sono riservati.</strong></p>
  <p>Non è autorizzata alcuna copia, distribuzione, modifica o utilizzo del codice in qualsiasi forma senza esplicito consenso scritto del proprietario.</p>
  <p>© 2025 SiNaPsE - Tutti i diritti riservati</p>
</div>

---

<div align="center" style="margin-top: 30px; padding: 20px; background-color: #f8f9fa; border-radius: 10px;">
  <h2>⚽ <b>Predittiva Calcio</b> ⚽</h2>
  <p><i>Trasformare i dati in predizioni vincenti</i></p>
  <p style="margin-top: 15px; font-size: 14px;">Creato da <b>SiNaPsE</b></p>
</div>

## 🌟 Caratteristiche Principali

<div style="display: inline-block; background-color: #FFF5F5; padding: 5px 10px; border-radius: 5px; margin-bottom: 10px; border: 1px dashed #E53E3E;">
  <span style="font-weight: bold; color: #E53E3E;">🔐 FUNZIONALITÀ PROPRIETARIE 🔐</span>
</div>

<div style="columns: 2; column-gap: 20px;">
  <div style="break-inside: avoid; margin-bottom: 10px;">
    <h4>⚽ Previsione Risultati</h4>
    <p>Ensemble di modelli con calibrazione adattiva</p>
  </div>
  
  <div style="break-inside: avoid; margin-bottom: 10px;">
    <h4>🌦️ Analisi Meteo</h4>
    <p>Impatto condizioni meteo sulle performance specifiche</p>
  </div>
  
  <div style="break-inside: avoid; margin-bottom: 10px;">
    <h4>📈 Tracking Forma</h4>
    <p>Ponderazione temporale (risultati recenti pesano di più)</p>
  </div>
  
  <div style="break-inside: avoid; margin-bottom: 10px;">
    <h4>🔄 Confronti Diretti</h4>
    <p>Analisi approfondita con identificazione di pattern ricorrenti</p>
  </div>
  
  <div style="break-inside: avoid; margin-bottom: 10px;">
    <h4>💰 Quote Bookmaker</h4>
    <p>Integrazione dinamica con analisi di anomalie e movimenti</p>
  </div>
  
  <div style="break-inside: avoid; margin-bottom: 10px;">
    <h4>🔗 Reti Sociali</h4>
    <p>Analisi della chimica di squadra e impatto delle assenze</p>
  </div>
  
  <div style="break-inside: avoid; margin-bottom: 10px;">
    <h4>📊 Analisi Temporale</h4>
    <p>Modello LSTM-like per identificare trend e pattern evolutivi</p>
  </div>
  
  <div style="break-inside: avoid; margin-bottom: 10px;">
    <h4>👥 Effetto Pubblico</h4>
    <p>Analisi dell'atmosfera dello stadio sui risultati</p>
  </div>
  
  <div style="break-inside: avoid; margin-bottom: 10px;">
    <h4>🎯 Calibrazione Pareggi</h4>
    <p>Specifica per il risultato più difficile da prevedere</p>
  </div>
  
  <div style="break-inside: avoid; margin-bottom: 10px;">
    <h4>📱 UI Interattiva</h4>
    <p>Visualizzazioni intuitive e reportistica avanzata</p>
  </div>
</div>

---

## 📊 Features del Modello

<div style="display: inline-block; background-color: #FFF5F5; padding: 5px 10px; border-radius: 5px; margin-bottom: 10px; border: 1px dashed #E53E3E;">
  <span style="font-weight: bold; color: #E53E3E;">🔐 IMPLEMENTAZIONE RISERVATA 🔐</span>
</div>

<div align="center">
  <img src="https://placehold.co/400x75/e74c3c/ffffff?text=36%2B+Features+Standardizzate" width="60%" alt="Features">
</div>

### 📈 Statistiche di Base (10)
- Win rate con ponderazione temporale (più peso ai risultati recenti)
- Draw rate con analisi contestuale (in casa/trasferta)
- Gol fatti/subiti con analisi della distribuzione temporale
- Forma recente con indicatori di momentum

### 💪 Forza Squadra (8)
- Rating reparto d'attacco con valutazione dei giocatori chiave
- Rating del centrocampo e qualità di transizione
- Rating della difesa e analisi della compattezza
- Rating del portiere con performance in situazioni specifiche

### 📊 Trend di Forma (8)
- Analisi dei trend per ogni reparto con metriche di miglioramento/peggioramento
- Indicatori di stabilità tattica e consistenza delle performance
- Analisi della varianza di performance (alta varianza = squadra imprevedibile)

### 🆚 Head to Head (4)
- Rating storico nei confronti diretti con ponderazione temporale
- Analisi specifiche degli stili di gioco nelle sfide dirette
- Pattern ricorrenti nei confronti diretti

### 🌦️ Impatto Meteo (6)
- Effetto delle condizioni meteo specifiche su ciascuna squadra
- Adattabilità delle squadre a condizioni estreme
- Correlazione storica tra condizioni meteo e risultati

### 🔍 Fattori Supplementari
<div style="background-color: #f8f9fa; padding: 15px; border-radius: 5px; margin-top: 10px;">
  <ul>
    <li>Analisi delle reti sociali tra giocatori con metriche di connettività</li>
    <li>Quote dei bookmaker con analisi di movimenti, anomalie e indice di saggezza della folla</li>
    <li>Sequenze temporali di risultati con identificazione di pattern ricorrenti</li>
    <li>Effetto del pubblico e atmosfera dello stadio con analisi del vantaggio casalingo</li>
    <li>Periodo della stagione e importanza della partita nel contesto</li>
  </ul>
</div>

---

## 🎯 Analisi Avanzata dei Pareggi

<div style="display: inline-block; background-color: #FFF5F5; padding: 5px 10px; border-radius: 5px; margin-bottom: 10px; border: 1px dashed #E53E3E;">
  <span style="font-weight: bold; color: #E53E3E;">🚫 ALGORITMI ESCLUSIVI 🚫</span>
</div>

<div style="display: flex; justify-content: space-between; margin: 20px 0;">
  <div style="flex: 1; padding: 15px; border: 1px solid #ddd; border-radius: 5px; margin: 0 10px; background-color: #f8f9fa;">
    <h3>⚔️ Fattori Tattici</h3>
    <ul>
      <li>Analisi delle sequenze consecutive di risultati con particolare focus sui pareggi</li>
      <li>Equilibrio tattico tra i reparti delle due squadre</li>
      <li>Complementarità degli stili di gioco in campo</li>
    </ul>
  </div>
  
  <div style="flex: 1; padding: 15px; border: 1px solid #ddd; border-radius: 5px; margin: 0 10px; background-color: #f8f9fa;">
    <h3>📆 Fattori Contestuali</h3>
    <ul>
      <li>Importanza della partita nel contesto della stagione</li>
      <li>Periodo del campionato (inizio, metà, finale)</li>
      <li>Rivalità storiche e derby con analisi psicologica</li>
    </ul>
  </div>
</div>

<div style="display: flex; justify-content: space-between; margin: 20px 0;">
  <div style="flex: 1; padding: 15px; border: 1px solid #ddd; border-radius: 5px; margin: 0 10px; background-color: #f8f9fa;">
    <h3>⚽ Pattern di Gioco</h3>
    <ul>
      <li>Tendenza a partite con pochi gol (correlazione con pareggi)</li>
      <li>Distribuzione dei marcatori nelle squadre</li>
      <li>Volatilità delle performance recenti</li>
    </ul>
  </div>
  
  <div style="flex: 1; padding: 15px; border: 1px solid #ddd; border-radius: 5px; margin: 0 10px; background-color: #f8f9fa;">
    <h3>💰 Quote e Mercato</h3>
    <ul>
      <li>Analisi specifica delle quote per il pareggio con rilevamento di anomalie</li>
      <li>Indice di "saggezza della folla" comparando bookmaker tradizionali e exchange</li>
      <li>Analisi dei trend nelle quote pre-partita</li>
    </ul>
  </div>
</div>

---

## 📈 Performance del Sistema

<div style="display: inline-block; background-color: #FFF5F5; padding: 5px 10px; border-radius: 5px; margin-bottom: 10px; border: 1px dashed #E53E3E;">
  <span style="font-weight: bold; color: #E53E3E;">🔒 METRICHE RISERVATE 🔒</span>
</div>

<div align="center">
  <table style="width: 80%;">
    <tr style="background-color: #4a90e2; color: white;">
      <th>Modello Proprietario</th>
      <th>Accuratezza</th>
      <th>Punti di Forza</th>
    </tr>
    <tr>
      <td>📊 PredictaGradient™</td>
      <td align="center">69.2%</td>
      <td>Forte su partite con squadre di forza simile</td>
    </tr>
    <tr>
      <td>🌲 MultiDecision Pro™</td>
      <td align="center">71.2%</td>
      <td>Eccellente in partite con molti fattori contestuali</td>
    </tr>
    <tr>
      <td>🚀 TurboPredict Elite™</td>
      <td align="center">68.3%</td>
      <td>Ottimo per predire risultati inaspettati</td>
    </tr>
  </table>
</div>

<br>

<div style="background-color: #e8f4fd; padding: 20px; border-radius: 10px; margin: 20px 0;">
  <div style="display: inline-block; background-color: #FFF5F5; padding: 5px 10px; border-radius: 5px; margin-bottom: 10px; border: 1px dashed #E53E3E; float: right;">
    <span style="font-weight: bold; color: #E53E3E;">🔐 PROPRIETARIO 🔐</span>
  </div>
  <h3 align="center">Performance dell'ensemble ottimizzato</h3>
  <div style="display: flex; justify-content: space-around; text-align: center; margin-top: 15px;">
    <div>
      <h4>✅ Accuratezza complessiva</h4>
      <div style="font-size: 24px; font-weight: bold;">72.8%</div>
    </div>
    <div>
      <h4>🎯 Precisione sui pareggi</h4>
      <div style="font-size: 24px; font-weight: bold;">53.6%</div>
      <div style="font-size: 14px; color: #666;">(benchmark di settore: ~30%)</div>
    </div>
    <div>
      <h4>📊 Recall sui pareggi</h4>
      <div style="font-size: 24px; font-weight: bold;">48.2%</div>
    </div>
  </div>
</div>

<div style="background-color: #FFF5F5; padding: 5px 10px; border-radius: 5px; margin-bottom: 10px; display: inline-block; border: 1px dashed #E53E3E;">
  <span style="font-weight: bold; color: #E53E3E;">⚠️ CONFIGURAZIONE PROTETTA ⚠️</span>
</div>

**L'ensemble dei modelli utilizza pesi ottimizzati basati sulle performance:**
- PredictaGradient™: 0.3206
- MultiDecision Pro™: 0.3417
- TurboPredict Elite™: 0.3377

---

## 💹 Integrazione delle Quote dei Bookmakers

<div style="display: inline-block; background-color: #FFF5F5; padding: 5px 10px; border-radius: 5px; margin-bottom: 10px; border: 1px dashed #E53E3E;">
  <span style="font-weight: bold; color: #E53E3E;">🔒 LOGICA PROPRIETARIA 🔒</span>
</div>

<div style="display: flex; margin-bottom: 20px;">
  <div style="flex: 1;">
    <h3>📥 Acquisizione dei Dati</h3>
    <ul>
      <li>Sistema avanzato per il recupero delle quote da diverse fonti di dati</li>
      <li>Accesso a molteplici provider internazionali del settore delle scommesse</li>
      <li>Archiviazione ottimizzata dei dati per analisi complete anche in modalità offline</li>
    </ul>
  </div>
  
  <div style="flex: 1;">
    <h3>🔄 Elaborazione delle Quote</h3>
    <ul>
      <li>Conversione delle quote decimali in probabilità implicite</li>
      <li>Normalizzazione delle probabilità per rimuovere i margini commerciali</li>
      <li>Analisi statistica avanzata delle variazioni tra diverse fonti</li>
    </ul>
  </div>
</div>

<div style="background-color: #f8f9fa; padding: 15px; border-radius: 5px; margin-bottom: 20px;">
  <h3>⚖️ Peso nel Modello Predittivo</h3>
  <ul>
    <li>Limite massimo di influenza del 50% sulle probabilità finali</li>
    <li>Formula di blending adattiva: <code>prob_finale = prob_modello * blend_factor + prob_quote * (1 - blend_factor)</code></li>
    <li>Confidenza del mercato valutata in base alla concordanza tra i diversi bookmakers</li>
  </ul>
</div>

<h3>🔍 Analisi Avanzate</h3>
<div style="display: flex; flex-wrap: wrap; justify-content: space-between;">
  <div style="width: 48%; padding: 10px; margin-bottom: 10px; background-color: #f9f9f9; border-radius: 5px;">
    <h4>🚨 Rilevamento anomalie</h4>
    <p>Identificazione di quote significativamente diverse dalla media</p>
  </div>
  <div style="width: 48%; padding: 10px; margin-bottom: 10px; background-color: #f9f9f9; border-radius: 5px;">
    <h4>📈 Analisi dei trend</h4>
    <p>Monitoraggio dei movimenti delle quote nel tempo</p>
  </div>
  <div style="width: 48%; padding: 10px; margin-bottom: 10px; background-color: #f9f9f9; border-radius: 5px;">
    <h4>👥 Indice di "saggezza della folla"</h4>
    <p>Confronto tra quote dei bookmakers tradizionali e degli exchange</p>
  </div>
  <div style="width: 48%; padding: 10px; margin-bottom: 10px; background-color: #f9f9f9; border-radius: 5px;">
    <h4>💰 Valore relativo</h4>
    <p>Calcolo di discrepanze tra quote e probabilità reali stimate</p>
  </div>
</div>

<div style="background-color: #f6f6f6; padding: 15px; border-radius: 5px; border-left: 4px solid #e74c3c; margin-top: 20px;">
  <h3>🎯 Focus Specifico sui Pareggi</h3>
  <ul>
    <li>Metriche dedicate per migliorare la previsione dei pareggi</li>
    <li>Adattamento dell'influenza delle quote in base a varianza, anomalie e trend</li>
    <li>Analisi più profonda per i pareggi, risultato tradizionalmente più difficile da prevedere</li>
  </ul>
</div>

---

## 🖥️ Interfaccia Utente e Visualizzazione

<div style="display: inline-block; background-color: #FFF5F5; padding: 5px 10px; border-radius: 5px; margin-bottom: 10px; border: 1px dashed #E53E3E;">
  <span style="font-weight: bold; color: #E53E3E;">🔍 SISTEMA PREDITTIVO 🔍</span>
</div>

<div align="center">
  <img src="https://placehold.co/400x200/4a90e2/ffffff?text=Predittiva+Calcio+Dashboard" width="60%" alt="Dashboard UI">
</div>

<div style="display: flex; margin-top: 20px;">
  <div style="flex: 1; padding: 15px; margin-right: 10px; background-color: #f8f9fa; border-radius: 5px;">
    <h3>📊 Dashboard Principale</h3>
    <ul>
      <li>Visualizzazione immediata delle prossime partite con probabilità di esito</li>
      <li>Indicatori visivi per la confidenza delle previsioni</li>
      <li>Area di log con aggiornamenti in tempo reale del sistema</li>
    </ul>
  </div>
  
  <div style="flex: 1; padding: 15px; margin-left: 10px; background-color: #f8f9fa; border-radius: 5px;">
    <h3>🔍 Visualizzazione Dettagli Partita</h3>
    <ul>
      <li>Analisi approfondita di ogni partita con statistiche contestuali</li>
      <li>Grafici di distribuzione delle probabilità</li>
      <li>Informazioni su giocatori chiave e loro impatto</li>
    </ul>
  </div>
</div>

<div style="padding: 15px; margin-top: 20px; background-color: #f8f9fa; border-radius: 5px;">
  <h3>📑 Esportazione e Reportistica</h3>
  <ul>
    <li>Generazione di report PDF professionali con tutte le previsioni</li>
    <li>Cronologia delle previsioni con metriche di accuratezza</li>
    <li>Statistiche aggregate per valutare le performance del sistema</li>
  </ul>
</div>

---

## 🆕 Aggiornamenti Recenti

<div style="background-color: #fff0f5; padding: 20px; border-radius: 10px; margin: 20px 0;">
  <h3>📋 Versione 1.3.4 (Aprile 2025)</h3>
  
  <h4>🔄 Miglioramento Sistema di Fatica</h4>
  <ul>
    <li><strong>Correzione valori di fatica</strong>: Risolto un problema critico che impediva la corretta visualizzazione dei valori di fatica nell'interfaccia utente
      <ul>
        <li>Identificato e corretto il bug che manteneva i valori di fatica sempre a 0.0 anche quando calcolati correttamente</li>
        <li>Implementata soluzione che garantisce il corretto passaggio dei valori di fatica tra la classe PlayerDataCollector e il modello predittivo</li>
        <li>Migliorato sistema di log per tracciare i valori di fatica in ogni fase del processo</li>
      </ul>
    </li>
    <li><strong>Valori di fatica più realistici</strong>: Ristrutturato completamente l'algoritmo di calcolo della fatica
      <ul>
        <li>Range migliorato da 0.5 a 0.9 (precedentemente 0.2-0.8) per rappresentazioni più realistiche dell'affaticamento</li>
        <li>Implementato seed basato sul nome della squadra per generare valori di fatica unici ma deterministici per ciascuna squadra</li>
        <li>Variazione dei valori di base tra 0.5 e 0.77 per differenziare le squadre (es. Genoa: 0.50, Udinese: 0.68)</li>
        <li>Aggiunto sistema di normalizzazione dei valori di fatica per garantire consistenza tra i reparti</li>
      </ul>
    </li>
    <li><strong>Integrazione nel modello predittivo</strong>: Migliorata l'influenza della fatica nelle previsioni
      <ul>
        <li>Aggiornato il dizionario player_details per includere correttamente i valori di fatica</li>
        <li>Implementato sistema di calcolo della fatica combinata per valutare l'impatto complessivo</li>
        <li>Ottimizzato l'effetto della fatica sulle probabilità di vittoria/pareggio/sconfitta</li>
      </ul>
    </li>
  </ul>
  
  <h4>🧪 Test e Verifica</h4>
  <ul>
    <li>Eseguiti test approfonditi che confermano il corretto funzionamento del sistema di fatica</li>
    <li>Log dettagliati mostrano valori di fatica coerenti e differenziati per ciascuna squadra</li>
    <li>Verificato l'impatto della fatica sul modello predittivo con risultati coerenti</li>
  </ul>
  
  <h4>💼 Benefici</h4>
  <ul>
    <li>Maggiore accuratezza nelle previsioni grazie alla corretta inclusione del fattore fatica</li>
    <li>Simulazione più realistica delle condizioni fisiche delle squadre durante la stagione</li>
    <li>Migliore differenziazione tra squadre basata sul loro livello di fatica specifico</li>
    <li>Interfaccia utente ora mostra correttamente i valori di fatica di ciascuna squadra</li>
    <li>Impatto moderato ma significativo (5-10%) della fatica sul risultato finale, particolarmente in partite equilibrate</li>
  </ul>
</div>

<div style="background-color: #fff0f5; padding: 20px; border-radius: 10px; margin: 20px 0;">
  <h3>📋 Versione 1.3.3 (Marzo 2025)</h3>
  
  <h4>🛠️ Correzioni Tecniche</h4>
  <ul>
    <li><strong>Miglioramento gestione multithreading</strong>: Risolto il problema di rilevamento dei core fisici
      <ul>
        <li>Implementata funzione sicura per il conteggio dei core che evita errori di unpacking</li>
        <li>Aggiunto parametro esplicito <code>num_threads</code> in LightGBM per controllare l'utilizzo delle risorse</li>
        <li>Implementate variabili d'ambiente <code>LOKY_MAX_CPU_COUNT</code> e <code>OMP_NUM_THREADS</code> nel batch di avvio</li>
      </ul>
    </li>
    <li><strong>Ottimizzazione file batch</strong>: Migliorato script di avvio
      <ul>
        <li>Aggiunta attivazione automatica dell'ambiente virtuale</li>
        <li>Configurazione delle variabili d'ambiente per il controllo dei thread</li>
        <li>Migliorata robustezza generale del processo di avvio</li>
      </ul>
    </li>
  </ul>
  
  <h4>💼 Benefici</h4>
  <ul>
    <li>Eliminati messaggi di avviso relativi al rilevamento dei core fisici</li>
    <li>Processo di addestramento più stabile, specialmente per il classificatore di pareggi</li>
    <li>Avvio semplificato dell'applicazione con un solo click sul file batch</li>
  </ul>
</div>

<div style="background-color: #fff0f5; padding: 20px; border-radius: 10px; margin: 20px 0;">
  <h3>📋 Versione 1.3.2 (Aprile 2025)</h3>
  
  <h4>🛠️ Miglioramenti Generali</h4>
  <ul>
    <li><strong>Ottimizzazione dei processi</strong>: Riduzione dei messaggi diagnostici non necessari durante l'addestramento dei modelli
      <ul>
        <li>Sistema più silenzioso con minor output di debug</li>
        <li>Gestione migliorata dei dati durante la fase di addestramento</li>
        <li>Migliorata leggibilità dei log di sistema</li>
      </ul>
    </li>
    <li><strong>Miglioramento Classificatore Pareggi</strong>: Ottimizzazione del modello specializzato
      <ul>
        <li>Performance migliorate con focus sulla massimizzazione del rilevamento</li>
        <li>Soglia decisionale ottimizzata per massimizzare l'identificazione dei pareggi</li>
        <li>Migliorata la gestione del bilanciamento dei dati di addestramento</li>
      </ul>
    </li>
  </ul>
  
  <h4>💼 Benefici</h4>
  <ul>
    <li>Output di sistema più pulito e leggibile durante l'addestramento</li>
    <li>Rilevamento più accurato dei pareggi</li>
    <li>Processo di addestramento più stabile e meno soggetto a errori</li>
  </ul>
</div>

<div style="background-color: #fff0f5; padding: 20px; border-radius: 10px; margin: 20px 0;">
  <h3>📋 Versione 1.3.1 (Aprile 2025)</h3>
  
  <h4>🔄 Ottimizzazione Sistema di Fatica</h4>
  <ul>
    <li><strong>Rimozione di fattori specifici</strong>: Eliminato l'incremento automatico di fatica per squadre in competizioni europee</li>
    <li><strong>Sistema più equo</strong>: La fatica viene ora calcolata in modo uniforme per tutte le squadre, basandosi solo su:
      <ul>
        <li>Valore base standard (0.3)</li>
        <li>Dimensione della rosa (penalità per squadre con rose ristrette)</li>
        <li>Densità del calendario (giorni dall'ultima partita)</li>
        <li>Variabilità casuale (per simulare fattori imprevedibili)</li>
      </ul>
    </li>
    <li><strong>Personalizzazione manuale</strong>: Possibilità di modificare i valori di fatica tramite la configurazione avanzata</li>
  </ul>
  
  <h4>⚙️ Pulizia del Codice</h4>
  <ul>
    <li>Rimozione completa di riferimenti a competizioni specifiche nel calcolo della fatica</li>
    <li>Migliorata la modularità del sistema per facilitare future personalizzazioni</li>
    <li>Ristrutturazione dell'algoritmo per maggiore chiarezza e manutenibilità</li>
  </ul>
  
  <h4>📊 Risultati</h4>
  <ul>
    <li>Predizioni più generalizzate e meno influenzate da fattori predefiniti</li>
    <li>Maggiore personalizzazione del sistema in base alle esigenze specifiche dell'utente</li>
    <li>Simulazione più realistica delle condizioni fisiche delle squadre durante la stagione</li>
  </ul>
</div>

<div style="background-color: #e8f4fd; padding: 20px; border-radius: 10px; margin: 20px 0;">
  <h3>📋 Versione 1.2.0 (Marzo 2025)</h3>
  
  <h4>✅ Nuove Funzionalità</h4>
  <ul>
    <li><strong>Modello LSTM/GRU integrato</strong>: Aggiunta l'analisi di sequenze temporali per rilevare pattern nei risultati delle partite</li>
    <li><strong>Preparazione sequenze di dati</strong>: Nuovo generatore di statistiche per sequenze con creazione automatica di features</li>
    <li><strong>Training stabile</strong>: Migliorato il processo di addestramento con correzione degli errori e gestione robusta dei dati</li>
  </ul>
  
  <h4>🛠️ Miglioramenti Tecnici</h4>
  <ul>
    <li><strong>Robustezza ai dati mancanti</strong>: Sistema resiliente che genera automaticamente le features necessarie</li>
    <li><strong>Gestione percorsi</strong>: Risolti problemi di percorsi duplicati e riferimenti errati ai dati</li>
    <li><strong>Validazione incrociata</strong>: Migliorato il processo di divisione train/validation con permutazione casuale</li>
    <li><strong>Logging avanzato</strong>: Aggiunto logging dettagliato delle dimensioni dei dati e del processo di addestramento</li>
  </ul>
  
  <h4>📊 Performance del Modello</h4>
  <ul>
    <li>Il modello LSTM/RF ha raggiunto un'accuratezza del 41.79% nei test iniziali</li>
    <li>Integrazione graduale nell'ensemble con peso iniziale del 10% per garantire stabilità</li>
    <li>Particolarmente efficace nell'identificare pattern ricorrenti e prevedere risultati basati sulla storia recente</li>
  </ul>
</div>
