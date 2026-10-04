# Surveillance

Vérifie toutes les 15 minutes que https://tracker.exploit-it.com répond. Si le site ne répond pas trois fois de suite
(environ 2 minutes), le run échoue et GitHub envoie un mail au propriétaire du dépôt.

Dépôt public exprès : les minutes GitHub Actions y sont gratuites et ne touchent pas au quota des dépôts privés.
Essai à la main : onglet Actions, « Surveillance du site », Run workflow (une adresse fausse permet de tester l'alerte).
