# Fuel&Go – Analisi dei prezzi carburante sulle Autostrade italiane

Progetto sviluppato nell’ambito del Master AIDA, con l’obiettivo di supportare la scelta della carta carburante più conveniente e ottimizzare i costi di rifornimento lungo la rete autostradale italiana.

L’applicazione interattiva è disponibile qui:  
👉 https://fuel-prices-autostrade.streamlit.app/

---
## 📌 Descrizione del progetto

Fuel&Go integra dati provenienti da fonti pubbliche (ASPI, MIMIT) per costruire una pipeline completa che va dalla raccolta dei dati alla visualizzazione interattiva.  
Il progetto include:

• Raccolta automatizzata dei dati (scraping e download da fonti ufficiali)
• Pulizia, trasformazione e modellazione
• Costruzione di un grafo autostradale
• Analisi dei prezzi carburante
• Dashboard interattiva per confrontare costi, distributori e percorsi

---
## 🗂️ Struttura del repository

1. `Anagrafica_Distributori`
Script per generare la tabella anagrafica dei distributori presenti sulla rete ASPI e registrati presso il MIMIT.
2. `Autostrade`
Download dei dati dal portale MIMIT: prezzi carburante aggiornati e informazioni anagrafiche sugli impianti ASPI/MIMIT.
3. `Caselli_Allacciamenti`
Scraping della tabella che descrive caselli e allacciamenti autostradali, utile per la costruzione del grafo.
4. `Input_Networkx`
Creazione della tabella dim_nodi e del grafo autostradale (nodi e archi) tramite NetworkX.
5. `Input_Streamlit`
Script dedicato alla costruzione della dashboard interattiva con Streamlit.
6. `Prezzi_Carburante`
Generazione della tabella fact_prezzi contenente i prezzi carburante aggiornati e normalizzati.
7. `Veicoli`
Download e pulizia dei dati relativi ai consumi dei vari modelli di veicoli, con creazione della tabella dim_consumo.
---
## 🧱 Tecnologie utilizzate
• Python (Pandas, BeautifulSoup, NetworkX)
• Streamlit per la dashboard
• GitHub per versionamento e collaborazione
• CSV come formato di scambio dati
• Scraping per fonti prive di API

---
## 🚀 Funzionalità principali
• Confronto dei prezzi carburante lungo le autostrade italiane
• Visualizzazione dei distributori e dei tratti autostradali
• Analisi dei consumi in base al modello di veicolo
• Supporto decisionale per la scelta della carta carburante più conveniente

