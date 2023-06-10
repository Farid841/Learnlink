# Learnlink

Ce projet est un blog interactif qui permet à plusieurs personnes de discuter sur un sujet spécifique en créant des "chambres" dédiées. Il offre aux utilisateurs la possibilité de créer leur propre chambre (appelée également "canal" ou "channel"), où plusieurs personnes peuvent rejoindre et participer aux discussions en temps réel. Pour participer à une chambre, les utilisateurs doivent être connectés à l'application.

Ce concept ressemble à un blog traditionnel, mais avec une dimension plus interactive et collaborative. Au lieu de simplement commenter les articles ou les publications d'une seule personne, les utilisateurs peuvent créer des espaces de discussion dédiés à un sujet précis. Cela encourage l'échange d'idées, de connaissances et de perspectives entre les participants.

Les chambres peuvent être créées par n'importe quel utilisateur de l'application, ce qui permet une diversité de sujets et d'interactions. Chaque chambre a ses propres règles et thèmes, permettant aux utilisateurs de se concentrer sur des sujets qui les intéressent. Cela crée une communauté dynamique où les utilisateurs peuvent rejoindre différentes chambres en fonction de leurs centres d'intérêt.

En somme, ce projet combine les aspects d'un blog traditionnel avec une approche plus interactive et collaborative, permettant à plusieurs utilisateurs de créer et de participer à des chambres de discussion sur des sujets spécifiques.

## Prérequis

Avant d'installer et d'exécuter le projet, assurez-vous d'avoir les éléments suivants :

- Python 3.8 ou version ultérieure
- pip (le gestionnaire de packages Python)

## Installation

Suivez ces étapes pour installer et exécuter le projet :

1. Clonez le référentiel GitHub :



2. Accédez au répertoire du projet :

```
     cd learnlink
 ```


3. Créez un environnement virtuel pour isoler les dépendances Python :

 ```
     python3 -m venv venv
 ```


4. Activez l'environnement virtuel :

   - Sur macOS et Linux :

     ```
     source venv/bin/activate
     ```

   - Sur Windows :

     ```
     venv\Scripts\activate
     ```


5. Installez les dépendances du projet à l'aide de pip :

   ```
     pip install -r requirements.txt
   ```


6. Effectuez les migrations de la base de données :

    ```
        python manage.py migrate
    ```


7. Lancez le serveur de développement :

    ```
        python manage.py runserver
    ```


8. Accédez à l'URL suivante dans votre navigateur :

    ```
        http://localhost:8000/
    ```


9. Vous devriez maintenant voir l'application en cours d'exécution localement sur votre machine.


10. Pour effectuer un changement de mot de passe dans Django, vous pouvez suivre les étapes suivantes :

     1 Créez un compte superutilisateur en exécutant la commande suivante dans votre terminal :

    bash

          python manage.py createsuperuser

     Suivez les instructions pour fournir un nom d'utilisateur, une adresse e-mail (facultatif) et un mot de passe pour le compte superutilisateur.
