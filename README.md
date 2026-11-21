# BDNV project

Proiect pentru cursul **Baze de date NoSQL și vectoriale** (FMI, Universitatea din București, 2026–2027).

**Tema aleasă:** T10 – Agent de suport pentru clienți cu memorie persistentă și aprobare umană.

## Pe scurt

Un agent de suport (LangChain `create_agent`, model local Qwen 2.5 7B prin Ollama) pentru un magazin online / agenție de turism. Agentul:

- citește date din MongoDB Atlas prin instrumente cu drepturi doar de citire (find, agregări, căutare semantică în catalog);
- execută acțiuni cu efecte (anularea unei comenzi, emiterea unui voucher, schimbarea adresei) numai după aprobarea unui operator uman (middleware human-in-the-loop);
- ține minte conversația (checkpointer MongoDB) și preferințele clientului între sesiuni (colecție dedicată de memorie pe termen lung);
- este evaluat pe cel puțin 20 de scenarii: rata de rezolvare, corectitudinea apelurilor de instrumente, token-uri pe conversație, cazuri de eșec.

## Stare

Repository inițializat. Codul, documentația tehnică, diagramele, prezentarea și demo-ul video urmează.

## Echipa

- Christian
- <coleg>

## Utilizarea instrumentelor AI

Se completează pe parcursul proiectului (instrumente folosite și pentru ce părți: cod, text, imagini, video).
