# Installer un système

## Lubuntu sur une machine virtuelle

Considérons que vous avez installé le logiciel **Virtual Box** pour créer une machine virtuelle.

1. Tout d'abord lancé votre logiciel.

2. Créez une nouvelle vm en cliquant sur **nouvelle**

   ![Première étape](./images/00.png)

3. Choisissez l'emplacement que prendra votre dossier, puis aller sur internet pour installer l'ISO en cherchant simplement **Lubuntu ISO** et l'installer et sélectionnez le fichier dans Virtual Box **Lubuntu** puis cliqué sur **suivant**.

   ![Définir l'emplacement](./images/01.png)

4. Déterminez la puissance de votre machine virtuelle. Pour cette exemple les paramètres de bases suffiront.

   ![Deuxième étapes image 1](./images/02.png)

   ![Deuxième étapes image 2](./images/03.png)

- Un récap de vos choix sera ensuite fait.

  ![Deuxième étapes image 3](./images/04.png)

5. Puis démarrez votre machine virtuelle en sélectionnant la vm désiré en cliquant simplement sur démarrer.

- Au passage quelque autre possibilité son marquées sur l'image si-dessous.

  ![Démarrer](./images/05.png)

6. Lorsque cela est fait une fenêtre s'ouvrira et vous appuyerez sur **entrée** quand vous serez sur **Try or install Lubuntu**.

   ![Lancer la vm](./images/06.png)

7. Quand vous arrivez sur votre bureau; cliquez sur **install Lubuntu**.

- Vous pouvez remarquer en bas à droite de votre écran une petite flèche. Elle vous permet de savoir lorsque vous êtes ou n'êtes pas sur la machine virtuelle.

- Elle est noir lorsque vous êtes en dehors et verte quand vous êtes dedans.
  ![Install lubuntu](./images/07.png)

8. Maintenat configurez votre machine virtuelle comme vous le souhaitez et en vous basant sur votre situation en appuyant sur suivant à chaques étapes complétées.

   ![configuration 1](./images/08.png)

   ![configuration 2](./images/09.png)

   ![configuration 3](./images/10.png)

9. Dans notre cas choisissez **effacer le disque** puis cliquez sur **suivant**.

   ![configuration 4](./images/11.png)

10. Maintenat définissez vous un nom d'utilisateur ainsi que votre mot de passe avec au minimum 4 caractères.

    ![configuration 5](./images/12.png)

- Un résumé sera encore montré. Puis cliquez sur **installer**

  ![configuration 6](./images/13.png)

- Une installation se mettra ensuite en route.

  ![configuration 7](./images/14.png)

11. Cliquez sur **Terminé** quand l'installation sera terminée

    ![Fin](./images/15.png)

12. Bravo vous avez installé Lubuntu sur une machine virtuel !

    ![Fin finale](./images/16.png)

## Faire les mises à jour

1. Quand vous êtes sur le bureau cliquez sur le logo en bas à gauche, puis dans **outils système** et aller dans **Qterminal**

   ![aller dans le Terminal](./images/17.png)

2. Dans le Terminal tapez `sudo apt update` pour chercher les mises à jour et appuyez sur **entrée**. Rentrez votre mot de passe et appuyez sur **entrée**. Attention il ne sera pas marqué !

   ![manipulation dans le terminal 1](./images/18.png)

3. Maintenat il faut faire les mises à jour en marquant `sudo apt upgrade` puis **entrée** et répondre oui lorsqu'on nous demande si nous sommes sur de vouloir le faire en marquant `O` quand ça nous le sera demandé. Puis **entrée**

   ![manipulation dans le terminal 2](./images/19.png)
   ![manipulation dans le terminal 3](./images/20.png)

4. Si cette image apparait cela veut dire que les mises à jour se lancent.

   ![manipulation dans le terminal 4](./images/21.png)

Bravo ! Vous avez réussi à faire toutes les mises à jour.

## Installer des logiciels

1. Retourner dans le Terminal. Puis écrire `sudo apt install *le nom du logiciel*`

   ![installer des logiciels](./images/22.png)

Maintenat vous savez comment lancer **Lubuntu**, faire les **mises à jour** et installer une **application** !
