# Exercice 5 – Projet scolaire

## 1. Création de l’arborescence en une seule commande
```bash
mkdir -p projet_scolaire/maths projet_scolaire/sciences
```

## 2. Création et remplissage de equations.txt dans maths
```bash
echo "x^2 + y^2 = z^2" > projet_scolaire/maths/equations.txt
```

## 3. Création et remplissage de expériences.txt dans sciences
```bash
echo "eau + huile = séparation" > projet_scolaire/sciences/expériences.txt
```

## 4. Renommage de equations.txt en geometrie.txt
```bash
mv projet_scolaire/maths/equations.txt projet_scolaire/maths/geometrie.txt
```

## 5. Déplacement de expériences.txt dans maths
```bash
mv projet_scolaire/sciences/expériences.txt projet_scolaire/maths/
```

## 6. Suppression du dossier sciences (qui est maintenant vide)
```bash
rmdir projet_scolaire/sciences
```

---

### Captures de commandes

```bash
$ ls projet_scolaire/maths
geometrie.txt  expériences.txt

$ cat projet_scolaire/maths/geometrie.txt
x^2 + y^2 = z^2

$ cat projet_scolaire/maths/expériences.txt
eau + huile = séparation

$ ls projet_scolaire
maths
```

---

### Remarques personnelles
Bien penser à utiliser `rmdir` pour supprimer un dossier vide.  
Attention à l’orthographe des fichiers et à bien déplacer avant de supprimer.