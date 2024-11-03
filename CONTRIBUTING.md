# Guide de Contribution

Merci de votre intérêt pour contribuer à ce projet ! Voici quelques lignes directrices pour vous aider à démarrer.

## Comment Contribuer

1. **Forkez le dépôt** : Cliquez sur le bouton "Fork" en haut de la page pour créer une copie de ce dépôt sur votre compte GitHub.

2. **Clonez votre fork** : Clonez le dépôt forké sur votre machine locale en utilisant la commande suivante :
    ```sh
    git clone https://github.com/votre-utilisateur/Data_Engineering_Rust_Sandbox.git
    ```

3. **Créez une branche** : Créez une nouvelle branche pour vos modifications :
    ```sh
    git checkout -b ma-nouvelle-fonctionnalité
    ```

4. **Faites vos modifications** : Apportez les modifications nécessaires à votre branche.

5. **Commitez vos modifications** : Commitez vos modifications avec un message de commit clair et descriptif :
    ```sh
    git commit -m "Ajout de ma nouvelle fonctionnalité"
    ```

6. **Poussez vos modifications** : Poussez vos modifications vers votre fork sur GitHub :
    ```sh
    git push origin ma-nouvelle-fonctionnalité
    ```

7. **Créez une Pull Request** : Allez sur le dépôt original et cliquez sur "New Pull Request" pour soumettre vos modifications pour examen.

## Code de Conduite

En contribuant à ce projet, vous acceptez de respecter notre [Code de Conduite](CODE_OF_CONDUCT.md).

## Style de Code

- Utilisez `cargo fmt` pour formater votre code.
- Utilisez `cargo clippy` pour vérifier la qualité de votre code.

## Tests

Assurez-vous que tous les tests passent avant de soumettre votre pull request. Vous pouvez exécuter les tests en utilisant la commande suivante :
```sh
cargo test