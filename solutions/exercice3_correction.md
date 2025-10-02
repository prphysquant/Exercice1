# Exercice 3 – Arborescence hiérarchisée

## 1. Création de l'arborescence actualites/politique
```bash
mkdir -p actualites/politique
```

## 2. Création du sous-dossier élections et du fichier candidats.txt
```bash
mkdir actualites/politique/elections
touch actualites/politique/candidats.txt
```

## 3. Ajout des noms dans candidats.txt
```bash
echo -e "Issoufou\nHama\nSeini" > actualites/politique/candidats.txt
```

## 4. Remonter de deux niveaux pour revenir dans actualites
```bash
cd actualites/politique/elections
cd ../..
```

## 5. Création du dossier buzz
```bash
mkdir buzz
```

---

### Captures de commandes

```bash
$ ls actualites
politique

$ ls actualites/politique
elections  candidats.txt

$ cat actualites/politique/candidats.txt
Issoufou
Hama
Seini

$ ls actualites
politique  buzz
```

---

### Remarques personnelles
Bien penser à utiliser `mkdir -p` pour créer plusieurs niveaux de dossiers d’un coup.  
L’ajout de texte multi-ligne dans un fichier se fait facilement avec `echo -e`.