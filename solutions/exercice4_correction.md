# Exercice 4 – Fichiers cachés et arborescence

## 1. Création d’un fichier caché dans le répertoire personnel
```bash
touch ~/.configuration
```

## 2. Vérification de la présence du fichier caché
```bash
ls -a ~ | grep .configuration
```

## 3. Création de l’arborescence créations/crayons en une seule commande
```bash
mkdir -p créations/crayons
```

## 4. Création du fichier couleurs.txt dans crayons
```bash
touch créations/crayons/couleurs.txt
```

## 5. Renommage du fichier couleurs.txt (le nom reste le même, donc pas d’action réelle)
```bash
mv créations/crayons/couleurs.txt créations/crayons/couleurs.txt
```

## 6. Remonter dans créations et créer gomme.txt puis le déplacer dans crayons
```bash
cd créations
touch gomme.txt
mv gomme.txt crayons/
```

## 7. Retour au répertoire personnel
```bash
cd ~
```

---

### Captures de commandes

```bash
$ ls -a ~ | grep .configuration
.configuration

$ ls créations/crayons
couleurs.txt  gomme.txt
```

---

### Remarques personnelles
Le renommage du fichier couleurs.txt n’était pas nécessaire car le nom ne change pas.  
Bien penser à utiliser `ls -a` pour voir les fichiers cachés.