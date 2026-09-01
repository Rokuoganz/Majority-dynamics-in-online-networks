# Majority-dynamics-in-online-networks
Repository del progetto "Majority-dynamics-in-online-networks" per il corso di Reti Sociali del Corso di Laurea Magistrale in Informatica.

## Autore
<a href="https://github.com/Rokuoganz/GameInsight/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Rokuoganz/GameInsight" />
</a>

* [Francesco Ferrara](https://github.com/Rokuoganz)

# Overview

Il progetto analizza il problema della **Majority Influence Diffusion** all'interno di una rete sociale rappresentata mediante un grafo. L'obiettivo è selezionare un seed set sotto vincolo di budget, massimizzando il numero di nodi influenzati e valutando la robustezza della soluzione rispetto a modifiche strutturali della rete.

Sono stati confrontati tre algoritmi di selezione del seed set: **Cost-Seeds-Greedy**, **Weighted Target Set Selection** e **Real-Gain Greedy**, quest'ultimo sviluppato nell'ambito del progetto.

## Obiettivi

* Analizzare il processo di diffusione dell'influenza secondo il modello Majority.
* Confrontare differenti algoritmi per la selezione del seed set.
* Valutare l'effetto di differenti funzioni di costo e valori del budget.
* Analizzare la robustezza dei seed set rispetto alla rimozione di archi e vertici della rete.
* Rappresentare e confrontare i risultati ottenuti attraverso grafici.

## Rete
Gli esperimenti sono stati condotti sulla rete **facebook_combined**, proveniente dal **Stanford Network Analysis Project (SNAP)**.
La rete viene utilizzata per simulare il processo di diffusione dell'influenza e le successive perturbazioni strutturali.

Dataset originale disponibile su SNAP: [https://snap.stanford.edu/data/ego-Facebook.html](https://snap.stanford.edu/data/ego-Facebook.html)

## Strumenti e Tecnologie

<div style="display: flex; align-items: center; gap: 30px;">
  <img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" width="50"/>
  <img src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" width="50"/
</div>

* **Python**: linguaggio utilizzato per l'implementazione degli algoritmi e delle simulazioni.
* **NetworkX**: libreria utilizzata per la gestione e l'analisi dei grafi.
* **Google Colab**: ambiente utilizzato per lo sviluppo e l'esecuzione degli esperimenti.

## Installazione e Uso

1. Scaricare i file .ipynb.
2. Aprire i file .ipynb tramite Google Colab.
4. Eseguire tutte le celle tramite Colab

## Struttura del Progetto

* [Documentazione.pdf](Majority_Dynamics_In_Online_Networks.pdf): documentazione completa del progetto e analisi dei risultati.
* [Dataset/](facebook_combined.txt): directory contenente la rete utilizzata.
* [Notebook/](MaxInfluence.ipynb): directory contenente i notebook utilizzati per l'implementazione e gli esperimenti.
