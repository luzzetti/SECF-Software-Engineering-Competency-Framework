# Agents.md

Questo file guida chi usa l'AI per creare o revisionare **Competency Card** ed **esercizi pratici** nel repository SECF.

## Obiettivo

Produrre contenuti coerenti con il framework descritto in questo repository:

- centrati su competenze, non su tecnologie;
- ancorati a problemi realistici;
- orientati a raccogliere evidenze osservabili;
- scritti in modo chiaro, sintetico e mantenibile;
- allineati ai principi del SECF, ai livelli di competenza cumulativi `L0`-`L5` e alla sintesi di profilo `E0`-`E5` usata dopo il colloquio.

Prima di scrivere una nuova card o un nuovo esercizio, leggere almeno:

- `02 - Principles/principles.adoc`
- `05 - Interview guide/interview-guide.adoc`
- il documento della competenza interessata in `06 - Competencies/**` oppure in `proto-v2/competenze/**` se si sta lavorando sulla nuova struttura;
- `proto-v2/ladder/secf-progression-framework.adoc`;
- `proto-v2/struttura-cards/creazione-scheda-operativa.prompt` quando serve allineare il formato delle schede.

## Principi di progettazione

### 1. Parti sempre da una situazione concreta

Ogni card deve descrivere un contesto di lavoro plausibile.
La domanda di base deve partire da una situazione osservabile, non da una definizione astratta.

Preferire formulazioni del tipo:

> Ti trovi in questa situazione. Come procederesti?

Evitare formulazioni come:

- "Cos'e..."
- "Spiegami..."
- domande puramente mnemoniche

### 2. Valuta il ragionamento, non la memoria

La card deve far emergere:

- analisi del problema;
- decisioni motivate;
- trade-off;
- alternative considerate;
- gestione dei vincoli e del contesto.

Se una domanda richiede soprattutto nozioni teoriche, probabilmente non e una buona card.

### 3. Mantieni separati base, approfondimenti e livelli

La struttura deve rispettare questa logica:

- la domanda di base individua il livello iniziale;
- le domande di approfondimento esplorano progressivamente livelli piu alti;
- i livelli descrivono evidenze cumulative, non categorie indipendenti;
- la scheda valuta una singola competenza; il profilo complessivo `E0`-`E5` si assegna dopo il colloquio usando l'insieme delle evidenze raccolte.

Non mischiare nella stessa domanda segnali di piu livelli senza una progressione chiara.

### 4. Documenta cio che serve, non tutto

La card deve contenere solo cio che aiuta l'intervistatore a valutare in modo affidabile:

- scopo della competenza;
- cosa osservare;
- domanda di base;
- domande di approfondimento;
- segnali positivi;
- segnali di attenzione;
- livelli `L0`-`L5`;
- eventuali note utili.

Evita ridondanze con il codice o con altri documenti del framework.

### 5. Scrivi per chi valuta

Il destinatario principale e l'intervistatore.
Il testo deve aiutarlo a capire:

- che cosa sta cercando;
- quali evidenze aspettarsi;
- come approfondire;
- quando fermarsi;
- come distinguere un livello dall'altro.

Il candidato non e il lettore primario del documento.

## Regole per una buona Competency Card

Ogni card dovrebbe avere queste caratteristiche:

- descrive una sola competenza;
- usa un linguaggio concreto e professionale;
- resta neutra rispetto a stack e vendor;
- non presume una sola soluzione corretta;
- permette risposte diverse ma valutabili;
- contiene domande che crescono in profondita senza cambiare tema;
- mantiene coerenza con il resto del framework.

## Regole per gli esercizi pratici

Quando crei un esercizio, preferisci scenari che:

- simulano un problema reale di lavoro;
- richiedono osservazione diretta del comportamento;
- sono risolvibili in tempi ragionevoli;
- producono evidenze utili per una o piu competenze;
- non dipendono da dettagli inutili dell'ambiente;
- hanno criteri di valutazione comprensibili.

Un buon esercizio:

- mette il candidato in una situazione credibile;
- espone decisioni, priorita e compromessi;
- non e un quiz travestito;
- non misura solo velocita di esecuzione;
- non richiede una risposta unica.

## Criteri di qualita

Prima di considerare pronta una card o un esercizio, verificare che:

- la competenza sia chiaramente identificabile;
- la situazione sia realistica;
- la domanda di base non sia ambigua;
- gli approfondimenti siano progressivi;
- i segnali positivi siano osservabili;
- i segnali di attenzione siano davvero utili;
- i livelli siano coerenti con i principi del framework e con la progressione `L0`-`L5`;
- il testo non introduca tecnologie come se fossero la competenza;
- il contenuto sia breve quanto basta per essere usato davvero.

## Anti-pattern da evitare

- Domande enciclopediche.
- Domande che premiano la memoria.
- Scenario troppo generico.
- Scenario costruito intorno a un framework specifico senza motivo.
- Livelli scritti come se fossero scale indipendenti.
- Segnali positivi troppo vaghi.
- Segnali di attenzione morali o soggettivi.
- Eccesso di dettagli che non cambiano la valutazione.
- Documentazione duplicata rispetto ad altri file.

## Stile di scrittura

- Usa frasi brevi e dirette.
- Preferisci verbi concreti.
- Mantieni un tono tecnico e professionale.
- Usa esempi solo se chiariscono davvero.
- Non appesantire con spiegazioni ridondanti.
- Mantieni la coerenza terminologica con il resto del repository.

## Struttura consigliata per una card

Quando utile, segui questa sequenza:

1. Identificativo della competenza.
2. Area e priorita.
3. Scopo.
4. Cosa osservare.
5. Domanda di base.
6. Domande di approfondimento.
7. Segnali positivi.
8. Segnali di attenzione.
9. Livelli.
10. Note.

## Processo consigliato

Quando devi creare una nuova card o un nuovo esercizio:

1. Leggi la competenza di riferimento.
2. Individua il comportamento che vuoi osservare.
3. Scrivi prima il contesto, poi la domanda.
4. Definisci cosa distingue un livello dall'altro.
5. Scrivi segnali positivi e segnali di attenzione.
6. Rimuovi ogni dettaglio superfluo.
7. Rileggi per verificare che la card sia usabile in colloquio.
8. Verifica che il profilo `E0`-`E5` non venga confuso con i livelli della singola competenza.

## Regola finale

Se un contenuto non aiuta a raccogliere evidenze migliori, probabilmente non va aggiunto.
