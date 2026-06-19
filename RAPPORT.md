# Exemple de soumission d'activité
ÉTS - LOG430 - Architecture logicielle - Été 2026

Étudiant(e) : Chris-Emmanuel Berton

# Questions
(Il est obligatoire d'ajouter du code, des captures d'écran ou des sorties de terminal pour illustrer chacune de vos réponses.)

## 1. Question 1 : Quelle réponse obtenons-nous à la requête à POST /payments ? Illustrez votre réponse avec des captures d'écran/du terminal.
Réponse
Erreur interne lorsque utilise krakend et problème de permissions lorsque passe par API directement.


![KrakenD error](image-7.png)

![alt text](image-8.png)

![Erreurs](image-6.png)

## 2. Question 2 : Quel type d'information envoyons-nous dans la requête à POST payments/process/:id ? Est-ce que ce serait le même format si on communiquait avec un service SOA, par exemple ? Illustrez votre réponse avec des exemples et captures d'écran/terminal.

![Post orders](image-1.png)

![Get Orders](image-3.png)



![Get payments id](image-5.png)

## 3. Question 3 : Quel résultat obtenons-nous de la requête à POST payments/process/:id?

Le résultat retourne une erreur car il ne reconnait pas le endpoint.

![Endpoint introuvable](image-9.png)
## 4.  Question 4 : Quelle méthode avez-vous dû modifier dans log430-labo05-payment et qu'avez-vous modifiée ? Justifiez avec un extrait de code.
Réponse
![Process Payment](image-10.png)
La méthode modifiée est la méthode process_payment. La valeur de retour et la requête ont été modifiés.

## 5.  Question 5 : À partir de combien de requêtes par minute observez-vous les erreurs 503 ? Justifiez avec des captures d'écran de Locust.

## 6. Question 6 :  Que se passe-t-il dans le navigateur quand vous faites une requête avec un délai supérieur au timeout configuré (5 secondes) ? Quelle est l'importance du timeout dans une architecture de microservices ? Justifiez votre réponse avec des exemples pratiques.



# Déploiement
(Le cas échéant, décrivez votre pipeline CI/CD et ce que vous avez appris dans ce laboratoire en ce qui concerne le déploiement. Il est obligatoire d'ajouter du code, des captures d'écran ou des sorties de terminal pour illustrer votre réponse.)