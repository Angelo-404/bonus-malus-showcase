# Gestionale Bonus/Malus

Il codice di questo progetto è privato perché è in prova presso un'azienda. Qui racconto cosa fa e come è costruito.

## Cosa fa

Misura l'efficienza degli operatori di produzione in un'azienda metalmeccanica, trasforma i dati di lavoro in
punteggi e costruisce una classifica. I ruoli sono due. L'amministratore, cioè i capi e l'ufficio, inserisce i dati e
decide i punteggi. L'operatore ha una schermata tutta sua, in sola lettura, dove vede i propri risultati e nient'altro.

Viene dal mio lavoro precedente: per sette anni sono stato dall'altra parte, alla macchina, e so come si legge un
numero di efficienza quando sei tu a produrlo.

## Come è costruito

React, TypeScript e Vite per l'interfaccia, con Tailwind e componenti shadcn/ui. Supabase con PostgreSQL per i dati
e per gli accessi per ruolo. Recharts per i grafici.

## Come l'ho verificato

Test automatici sulle regole di calcolo, un audit dei permessi e una revisione completa prima di metterlo in mano
all'azienda.

## Stato

In prova gratuita presso un'azienda metalmeccanica della provincia di Bologna.
