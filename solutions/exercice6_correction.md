# Exercice 6 – Dossier personnel et gestion de fichiers

## 1. Création d’un dossier personnel et entrée dedans
```bash
mkdir mon_dossier
cd mon_dossier
```

## 2. Création des fichiers banque.txt, sante.txt et du fichier caché .mdp
```bash
touch banque.txt sante.txt .mdp
```

## 3. Ajout de contenu dans banque.txt et sante.txt
```bash
echo "Relevé bancaire janvier." > banque.txt
echo "Vaccination complète." > sante.txt
```

## 4. Vérification de la présence de .mdp
```bash
ls -a
```

## 5. Renommage de sante.txt en medical.txt
```bash
mv sante.txt medical.txt
```

## 6. Déplacement de banque.txt et medical.txt dans un sous-dossier documents
```bash
mkdir documents
mv banque.txt medical.txt documents/
```

## 7. Suppression uniquement du fichier caché .mdp
```bash
rm .mdp
```

---

### Captures de commandes

```bash
$ ls -a
.  ..  documents  .mdp

$ ls documents
banque.txt  medical.txt
```

---

### Remarques personnelles
Bien penser à utiliser `ls -a` pour voir les fichiers cachés.  
Créer le dossier `documents` avant de déplacer les fichiers.  
Aucune difficulté particulière.