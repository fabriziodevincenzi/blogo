---
title: "Cos'è l'Accordo Bizantino Federato"
publishDate: "30 July 2023"
description: "L'Accordo Bizantino Federato è il concetto sul quale si basa il protocollo della rete blockchain Stellar per raggiungere l'accordo tra i nodi della rete decentralizzata."
tags: ["blockchain"]
---

L'Accordo Bizantino Federato (Federated Byzantine Agreement o FBA) è un concetto chiave del protocollo di consenso di Stellar (Stellar Consensus Protocol o SCP). L'FBA è un approccio che consente a un gruppo di nodi (computer) di raggiungere un accordo su un insieme di informazioni, nonostante la presenza di nodi difettosi o malevoli.

Per capire l'FBA, è utile avere familiarità con il problema del generale bizantino. In questa situazione, un gruppo di generali deve coordinare le loro azioni per attaccare o ritirarsi da un nemico. Tuttavia, alcuni generali potrebbero essere disonesti o non affidabili, inviando messaggi contraddittori per sabotare il piano. L'obiettivo è che i generali onesti raggiungano un accordo sulla strategia, nonostante la presenza dei generali traditori.

Nel contesto di Stellar, l'FBA affronta un problema simile: come raggiungere un accordo tra nodi in una rete distribuita, in cui alcuni nodi potrebbero essere malevoli o difettosi. Invece di richiedere un consenso globale da tutti i nodi, l'FBA si basa su un modello federato, in cui un sottoinsieme selezionato di nodi, chiamati validatori, partecipa all'elaborazione delle decisioni di consenso.

Ogni validator nel protocollo SCP nomina un insieme di altri validatori, noti come quorum slice, che considera affidabili. Il consenso viene raggiunto quando un insieme di quorum slice sovrapposti si interseca, ovvero quando i validatori in ciascun quorum slice sono d'accordo. Ciò significa che anche se alcuni validatori possono essere difettosi o malevoli, la sovrapposizione dei quorum slice permette ai validatori onesti di raggiungere un accordo sulla validità delle transazioni.

L'uso dell'FBA nel protocollo di consenso di Stellar offre diversi vantaggi. Permette una scalabilità orizzontale, in quanto è possibile aumentare il numero di nodi nella rete senza compromettere la velocità o la sicurezza del consenso. Inoltre, l'FBA consente una maggiore flessibilità nella selezione dei validatori, consentendo una governance decentralizzata e inclusiva.

In sintesi, l'Accordo Bizantino Federato (FBA) nel contesto del protocollo di consenso di Stellar è un approccio che consente a un gruppo selezionato di nodi affidabili, chiamati validatori, di raggiungere un accordo sulla validità delle transazioni, nonostante la presenza di nodi difettosi o malevoli nella rete. Questo approccio favorisce la scalabilità, la flessibilità e la sicurezza del consenso distribuito.
