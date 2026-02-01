# Sentiment-Analysis

<p>
Il progetto consiste nella <b>sentiment analysis</b> di un dataset di poesie tratto dal <b>Progetto Gutenberg</b>.
Il dataset scelto proviene da huggingface ed è formato da poesie del progetto Gutenberg https://huggingface.co/datasets/google-research-datasets/poem_sentiment. </p>
  <p>
L'analisi è stata condotta in due modalità:
</p>

<ul>
  <li>Su frasi integrali</li>
  <li>Su frasi ridotte</li>
</ul>

<p>
Le frasi ridotte sono state ottenute attraverso un processo di <b>tokenizzazione</b> e selezione delle seguenti
parti del discorso (<b>POS</b>):
</p>

<ul>
  <li>Nomi</li>
  <li>Verbi</li>
  <li>Avverbi</li>
  <li>Aggettivi</li>
</ul>

<p>
L’analisi del sentiment si è articolata nei seguenti passaggi:
</p>

<ul>
  <li>Calcolo degli embeddings</li>
  <li>Calcolo della similarità coseno</li>
  <li>Individuazione della similarità massima</li>
  <li>Assegnazione del sentiment</li>
</ul>

<p>
A ciascuna poesia del set di test è stato assegnato il sentiment della poesia più simile
(in termini di <b>similarità coseno</b>) presente nel training set.
</p>

<p>
Infine, sono state calcolate le metriche di <b>accuratezza</b> e i risultati ottenuti sono stati
<b>visualizzati graficamente</b>.
</p>

<h1>LIBRERIE</h1>

<p>Sono state usate le seguenti librerie:</p>

<ul>
  <li>Pandas</li>
  <li>NumPy</li>
  <li>Sentence-Transformers</li>
  <li>SpaCy</li>
  <li>Matplotlib</li>
  <li>Scikit-learn</li>
</ul>
