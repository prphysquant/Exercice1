
# Exercice 1 – Manipulation de fichiers et dossiers en CLI
# je suis avec Mariam

## 1. Création du dossier cli_tmp
```bash
mkdir cli_tmp
```

## 2. Création du fichier dans cli_tmp
```bash
touch cli_tmp/je_suis_dans_tmp.txt
```

## 3. Entrer dans cli_tmp
```bash
cd cli_tmp
```

## 4. Créer un fichier vide et un sous-dossier
```bash
touch in_cli_tmp.txt
mkdir in_cli_tmp
```

## 5. Supprimer je_suis_dans_tmp.txt
```bash
rm je_suis_dans_tmp.txt
```

## 6. Retour au home et suppression complète
```bash
cd ~
rm -rf cli_tmp
```

## 7. Création multiple de dossiers
```bash
mkdir grand_parent parent grand_frere grande_soeur ami connaissances
```

## 8. Création et déplacement de fichier
```bash
cd grand_frere
touch bachir
mv bachir ../ami/
```

## 9. Déplacement du dossier ami
```bash
cd ~
mv ami parent/
```

## 10. Affichage chemin absolu
```bash
pwd
```

## 11. Retour au répertoire personnel
```bash
cd ~
```

---

### Captures de commandes

```bash
$ ls
grand_parent  parent  grand_frere  grande_soeur  ami  connaissances

$ ls parent/
ami

$ ls parent/ami/
bachir

$ pwd
/Users/manomiagyaouabdoulmagid
```

---

### Remarques personnelles
Aucune difficulté particulière, bien suivre chaque étape et vérifier avec `ls` et `pwd` à chaque manipulation.
