# Fuel&Go – Progetto Master AIDA
Obiettivo: Supportare la scelta ottimale della carta carburante e ridurre i costi di rifornimento lungo le autostrade italiane, integrando dati da fonti pubbliche e analisi personalizzate.
🌐 App Streamlit disponibile qui → fuel-prices-autostrade.streamlit.app
---
📁 Struttura del progetto e guida agli script
• Anagrafica_Distributori  
Genera una tabella con informazioni anagrafiche sui distributori presenti lungo la rete ASPI e registrati presso il MIMIT.
• Autostrade  
Scarica dal sito MIMIT i dati sui prezzi dei carburanti e altre informazioni relative agli impianti autostradali ASPI e MIMIT.
• Caselli_Allacciamenti  
Script di scraping per ottenere la mappa dei caselli e degli allacciamenti autostradali.
• Input_Networkx  
Costruisce la tabella dim_nodi e il grafo autostradale con nodi e archi, utilizzando NetworkX.
• Input_Streamlit  
Crea l’interfaccia interattiva dell’applicazione tramite Streamlit.
• Prezzi_Carburante  
Elabora la tabella fact_prezzi con i dati aggiornati sui prezzi dei carburanti.
• Veicoli  
Scarica e pulisce i dati relativi ai consumi di diversi modelli di veicoli, generando la tabella dim_consumo.
