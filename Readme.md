# Module de paiement B to B

## Changer le type de status validation de commande :

`paiementbtob/controllers/front/validation` => `postProcess()`

|        valeur         |              Description              |
| :-------------------: | :-----------------------------------: |
| $payment_status = 13; | En attende de paiement à la livraison |
| $payment_status = 2;  |           Paiement accepté            |
