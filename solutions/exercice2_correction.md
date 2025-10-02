# Exercice 2 – Organisation thématique

## 1. Création du dossier conteneur et des sous-dossiers
```bash
mkdir -p conteneur/voitures conteneur/ustensiles conteneur/électronique
```

## 2. Création et remplissage de mes_voitures.txt
```bash
echo -e "benz\ntoyota\nhonda" > conteneur/voitures/mes_voitures.txt
```

## 3. Création et remplissage de cuisine.txt
```bash
echo -e "cuillere\nmarmite\ncouteau" > conteneur/ustensiles/cuisine.txt
```

## 4. Vérification du contenu de cuisine.txt
```bash
cat conteneur/ustensiles/cuisine.txt
```

## 5. Liste du contenu du dossier conteneur
```bash
ls conteneur
```

---

### Captures de commandes

```bash
$ ls conteneur
voitures  ustensiles  électronique

$ cat conteneur/ustensiles/cuisine.txt
cuillere
marmite
couteau
```

---

### Remarques personnelles
Aucune difficulté particulière, bien penser à utiliser `echo -e` pour les retours à la ligne.