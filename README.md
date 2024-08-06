# GitHub-Command

Voici une liste des commandes Git de base ainsi que leurs rôles et des exemples d'utilisation :

### Configuration
1. **`git config`**
   - **Rôle**: Configure les options utilisateur.
   - **Exemple**: 
     ```bash
     git config --global user.name "Votre Nom"
     git config --global user.email "votre.email@example.com"
     ```

### Initialisation et Clonage
2. **`git init`**
   - **Rôle**: Initialise un nouveau dépôt Git.
   - **Exemple**: 
     ```bash
     git init
     ```

3. **`git clone`**
   - **Rôle**: Clone un dépôt existant.
   - **Exemple**: 
     ```bash
     git clone https://github.com/utilisateur/projet.git
     ```

### Gestion des Fichiers
4. **`git add`**
   - **Rôle**: Ajoute des fichiers à l'index.
   - **Exemple**: 
     ```bash
     git add fichier.txt
     git add .
     ```

5. **`git rm`**
   - **Rôle**: Supprime des fichiers de l'index et du répertoire de travail.
   - **Exemple**: 
     ```bash
     git rm fichier.txt
     ```

6. **`git mv`**
   - **Rôle**: Déplace ou renomme des fichiers.
   - **Exemple**: 
     ```bash
     git mv ancien_nom.txt nouveau_nom.txt
     ```

### Validation des Modifications
7. **`git commit`**
   - **Rôle**: Valide les modifications dans l'historique.
   - **Exemple**: 
     ```bash
     git commit -m "Message de commit"
     ```

8. **`git commit --amend`**
   - **Rôle**: Modifie le dernier commit.
   - **Exemple**: 
     ```bash
     git commit --amend -m "Nouveau message de commit"
     ```

### Historique et Log
9. **`git log`**
   - **Rôle**: Affiche l'historique des commits.
   - **Exemple**: 
     ```bash
     git log
     ```

10. **`git diff`**
    - **Rôle**: Affiche les différences entre les fichiers.
    - **Exemple**: 
      ```bash
      git diff
      ```

11. **`git status`**
    - **Rôle**: Affiche l'état des fichiers dans le répertoire de travail et l'index.
    - **Exemple**: 
      ```bash
      git status
      ```

### Branches
12. **`git branch`**
    - **Rôle**: Liste, crée ou supprime des branches.
    - **Exemple**: 
      ```bash
      git branch
      git branch nouvelle-branche
      git branch -d branche-a-supprimer
      ```

13. **`git checkout`**
    - **Rôle**: Change de branche ou restaure des fichiers de l'historique.
    - **Exemple**: 
      ```bash
      git checkout nom-de-branche
      git checkout -- fichier.txt
      ```

14. **`git switch`**
    - **Rôle**: Change de branche (alternative plus moderne à `git checkout` pour changer de branche).
    - **Exemple**: 
      ```bash
      git switch nom-de-branche
      git switch -c nouvelle-branche
      ```

### Fusion et Rebasage
15. **`git merge`**
    - **Rôle**: Fusionne des branches.
    - **Exemple**: 
      ```bash
      git merge nom-de-branche
      ```

16. **`git rebase`**
    - **Rôle**: Applique des commits d'une branche sur une autre.
    - **Exemple**: 
      ```bash
      git rebase nom-de-branche
      ```

### Remotes
17. **`git remote`**
    - **Rôle**: Gère les dépôts distants.
    - **Exemple**: 
      ```bash
      git remote -v
      git remote add origin https://github.com/utilisateur/projet.git
      ```

18. **`git fetch`**
    - **Rôle**: Récupère les modifications depuis un dépôt distant.
    - **Exemple**: 
      ```bash
      git fetch origin
      ```

19. **`git pull`**
    - **Rôle**: Récupère et intègre les modifications depuis un dépôt distant.
    - **Exemple**: 
      ```bash
      git pull origin main
      ```

20. **`git push`**
    - **Rôle**: Envoie les modifications vers un dépôt distant.
    - **Exemple**: 
      ```bash
      git push origin main
      ```

### Autres Commandes Utiles
21. **`git stash`**
    - **Rôle**: Sauvegarde temporairement les modifications locales.
    - **Exemple**: 
      ```bash
      git stash
      git stash pop
      ```

22. **`git tag`**
    - **Rôle**: Crée, liste ou supprime des tags.
    - **Exemple**: 
      ```bash
      git tag
      git tag -a v1.0 -m "Version 1.0"
      git tag -d v1.0
      ```

### Annulation des Modifications
23. **`git reset`**
    - **Rôle**: Réinitialise l'index et/ou le répertoire de travail.
    - **Exemple**: 
      ```bash
      git reset --soft HEAD~1
      git reset --hard HEAD~1
      ```

24. **`git revert`**
    - **Rôle**: Annule un commit spécifique.
    - **Exemple**: 
      ```bash
      git revert <commit_id>
      ```

### Sauvegarde de Travail en Cours
25. **`git stash`**
    - **Rôle**: Sauvegarde temporairement les modifications locales.
    - **Exemple**:
      ```bash
      git stash
      git stash pop
      ```

Cette liste couvre les commandes Git les plus courantes et essentielles. Si vous avez des besoins spécifiques ou des cas d'utilisation particuliers, n'hésitez pas à demander !
