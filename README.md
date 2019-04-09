# TP-du-siecle

Pour récupérer le projet en local :

```bash
git checkout .  (Supprime tout le contenu de la branche en cours!)
git checkout master
git pull
git rebase master (màj la branche au contenu supprimé)
composer install
git checkout labranche

```

Pour push la branche :

```bash
git add .
git commit -m "Le commit"
git push origin labranche
```

Pour fusionner la branche et le projet :

```bash
git checkout master
git merge labranche
git branch -d labranche
git branch labranche
```

