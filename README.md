# WebAuthn API analysis

**Bachelor's thesis** on WebAuthn API at Ca'Foscari University, see <ins>DOCUMENTATION/REPORT.pdf</ins> for a project explanation, language used is <ins>italian</ins>.

## Abstract

L'utilizzo di password testuali nei processi di registrazione e autenticazione di un utente presso un servizio web ha accompagnato internet nella sua esistenza. Negli anni '60 Fernando Corbató inventò questa tecnologia, da allora è stata il principale metodo con il quale si effettua l'identificazione di un utente attraverso un elaboratore.

Molte tecnologie alternative furono create, un esempio su tutte sono le password grafiche, queste però non sostituirono mai l'utilizzo della password testuale, anche a causa di un'usabilità minore percepita dall'utente utilizzatore.

Lo scopo di questa tesi è quello di presentare il protocollo FIDO2 e nel dettaglio WebAuthn API, una nuova tecnologia alternativa alle password testuali che mira ad eliminare l'utilizzo di esse nelle registrazioni ed autenticazioni effettuate in qualsiasi sito web, con un occhio alla sicurezza ed alla privacy dell'utente usufruente.
Verrà analizzata nel dettaglio l'implementazione di questa nuova soluzione, concentrandosi poi nell'aspetto della sua affidabilità, andando ad approfondire singolarmente le possibili vulnerabilità riscontrate e modellando questa tecnologia all'interno di un software che ha permesso di confermare le criticità trovate in determinate condizioni e la solidità dell'API in altre.

