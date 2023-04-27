G-Form Notifier By Yasunaii_

Ce projet est un script Google Apps qui permet de notifier un serveur Discord chaque fois qu'un nouveau formulaire est soumis. Le script a été conçu pour être utilisé avec le formulaire de recrutement de joueurs de la guilde Oni Korp, mais il peut être facilement adapté pour d'autres formulaires.
Dans le cas de la Oni korp le lien envoyé été celui ou l'on pouvait consulter les réponse individuelle des formulaire envoyé ! 

Configuration
1. Créez votre formulaire avec G-Form.
2. Cliquez sur les trois petits points à droite du bouton "Envoyer".
3. Cliquez sur "Editeur de script" et collez-y mon script.
4. Modifiez les variables "discordUrl" et "responseUrl" (les commentaires vous décrivent leur effet).

4. Maintenant, vous devez gérer vos déclencheurs :

4.1 A gauche, sélectionnez l'onglet "Déclencheurs".

4.2 Ajoutez un nouveau déclencheur.

4.3 Paramétrez le déclencheur comme suit :

4.4 Choisissez la fonction à exécuter : "OnFormSubmit".

4.5 Choisissez le déploiement à exécuter : "Head".

4.6 Sélectionnez la source de l'évènement : "Basé sur le formulaire".

4.7 Sélectionnez un type d'évènement : "Lors de l'envoi du formulaire".

4.8 Paramètre de notification d'échec : "Recevoir une notification immédiatement".

4.9 Enregistrez le déclencheur avec ces paramètres.

4.10 Vous devez donner les autorisations au déclencheur d'exécuter le code.

Personnalisation
Vous pouvez personnaliser le message envoyé sur votre serveur Discord en modifiant la fonction createMessage(). 
Cette fonction génère le message qui sera envoyé, et vous pouvez y modifier le titre, la description et les champs du message.
Si vous vous y connaisez mal en code ne vous inquité pas toutes les ligne ou la personnonnalisation est possible j'y est ajouté un commentaire ! 

Crédits
Ce script a été créé par Yasunaii_, un membre de la Structure Oni Korp. 
Si vous avez des questions ou des commentaires, n'hésitez pas à me contacter sur Discord. ( Yasunaii_#0220 ) 
Ps : si mon discord a changer il y'a mon twitter sur mon profil ! 