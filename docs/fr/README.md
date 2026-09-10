# Parcours francais : commerce-payments (protocole Commerce Payments)

Lecture commentee du depot base/commerce-payments : un protocole permissionless qui reproduit on-chain le flux "authorize and capture" du commerce traditionnel, avec un systeme modulaire de collecteurs de tokens (ERC-3009, Permit2, pre-approbation, spend permissions) et un modele de frais borne cryptographiquement par le payeur.

Sommaire :

1. [Presentation du protocole Commerce Payments](01-presentation.md)
2. [PaymentInfo et le hash qui identifie un paiement](02-paymentinfo-hash.md)
3. [TokenStore, l escrow par operateur deploye a la demande](03-tokenstore.md)
4. [TokenCollector, l abstraction qui rend l autorisation modulaire](04-tokencollector.md)
5. [authorize, placer une reserve en escrow](05-authorize.md)
6. [capture, distribuer les fonds retenus](06-capture.md)
7. [charge, autoriser et capturer en une seule transaction](07-charge.md)
8. [void et reclaim, les deux chemins d annulation](08-void-reclaim.md)
9. [refund, rendre des fonds deja captures](09-refund.md)
10. [Le modele de frais et ses bornes cryptographiques](10-frais.md)
11. [ERC-3009 et Permit2, collecter par signature](11-collecteurs-signature.md)
12. [PreApproval et SpendPermission, les deux autres voies de collecte](12-collecteurs-approbation.md)
13. [Limites et perimetre de ce parcours](13-limites-perimetre.md)

Ce parcours est une lecture pedagogique du code source et de la documentation du depot, sans installation ni execution du projet.
