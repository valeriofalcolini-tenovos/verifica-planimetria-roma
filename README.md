# Verifica Planimetria Roma

Strumento web per una **pre-verifica** di una planimetria residenziale nel Comune di Roma.

Apri la pagina, carica la planimetria (PDF o immagine) come riferimento, inserisci i vani con superficie, altezza e superficie finestrata, e lo strumento segnala ogni requisito rispettato, in tolleranza o non conforme. Una seconda sezione guida la verifica di ciò che la planimetria non può dimostrare: stato legittimo, destinazione d'uso, PRG, vincoli.

## Cosa verifica

**Requisiti igienico-sanitari (calcolati)**
- Altezze minime: 2,70 m vani abitabili, 2,40 m servizi (DM 5/7/1975 art. 1, R.E. Roma artt. 40-42); 3,00 m in seminterrato (art. 38); 2,50 m media nel sottotetto (art. 43)
- Superfici: camera singola 9 m², doppia 14 m², soggiorno 14 m² (DM art. 2, R.E. art. 40)
- Superficie per abitante: 14 m² per i primi quattro, 10 m² per i successivi; monolocale 28/38 m² (DM artt. 2-3)
- Rapporto aeroilluminante 1/8 (DM art. 5, R.E. art. 40 f)
- Cucina: volume ≥ 15 m³ e finestra apribile ≥ 1,50 m² (R.E. art. 41 a)
- Bagno: dotazione completa, aerazione naturale o forzata (DM art. 7, R.E. art. 41 b)
- Ripostiglio con finestra oltre 4 m² (R.E. art. 42 b)
- Deroga Salva Casa: altezza fino a 2,40 m, monolocali 20/28 m², alle condizioni indicate da Roma Capitale (prot. QI/2024/0205723)
- Tolleranza del 2% per le misure igienico-sanitarie (DPR 380/2001 art. 34-bis)

**Checklist guidata (non calcolabile dalla planimetria)**
- Stato legittimo (art. 9-bis DPR 380/2001)
- Destinazione d'uso (art. 23-ter) e agibilità (art. 24)
- Componente PRG e tessuto, variante NTA approvata il 23/7/2026, Città Storica
- Carta per la Qualità
- Vincoli culturali (Parte II D.Lgs. 42/2004, Vincoli in Rete)
- Vincoli paesaggistici (PTPR Lazio DCR 5/2021, rettifica DGR 1078/2025; SITAP)

## Limiti

Non sostituisce l'asseverazione di un tecnico abilitato. Non verifica fattore di luce diurna, impianti, antincendio, barriere architettoniche, né il Titolo III bis del Regolamento Edilizio (Del. A.C. 90/2026), che riguarda nuove costruzioni, demolizioni con ricostruzione e ampliamenti oltre il 15% di SUL.

I dati inseriti restano nel browser (localStorage) e non vengono inviati a nessun server.

Normativa aggiornata a novembre 2026.
