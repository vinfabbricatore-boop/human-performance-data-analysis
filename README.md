## Data Dictionary

Il dataset contiene 19 variabili, strutturate in 4 macro-categorie logiche per separare i tratti individuali dagli stati dinamici:

**1. Identificativi e Struttura Temporale
* `trajectory_id` (int): Identificativo univoco dell'agente.
* `step` (int): Numero progressivo dell'osservazione.
* `timestamp` (object): Orario esatto della registrazione.

**2. Differenze Individuali (Tratti stabili)**
* `skill_baseline` (float): Livello di competenza base dell'agente.
* `fatigue_sensitivity` (float): Vulnerabilità intrinseca all'accumulo di fatica.
* `resilience_factor` (float): Capacità di mantenere la performance sotto stress.

**3. Condizioni del Task (Variabili Indipendenti)**
* `task_type` (object): Tipologia di compito.
* `task_difficulty` (float): Livello di difficoltà intrinseca.
* `time_pressure` (object): Presenza di pressione temporale.

**4. Performance, Stati Dinamici e Rischio (Variabili Dipendenti)**
* `reaction_time` (float): Tempo di risposta in millisecondi.
* `error_rate` (float): Frequenza di errore nell'istante specifico.
* `motivation` (float): Livello di motivazione attuale.
* `regime` (object): Stato psicofisico generale (NORMAL, STRESSED, BURNOUT).
* `error_severity` (object): Gravità dell'errore commesso.
* `downstream_cost` (int): Costo operativo derivato dall'errore.
* `risk_score` (float): Punteggio di rischio operativo complessivo.
* `mission_failure_probability` (float): Probabilità di fallimento della missione.
* `expected_loss` (float): Perdita attesa calcolata.
* `intervention_effectiveness` (float): Efficacia delle misure di mitigazione.