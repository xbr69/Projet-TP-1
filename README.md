# 🧾 Travail à rendre

**Date limite :** jeudi **13 novembre 2025 à 14h00**  
**Envoi par mail à :** [web@xavierbroutin.com](mailto:web@xavierbroutin.com)

---

## Critères d’évaluation

- Utilisation du **camelCase** pour nommer les variables et fonctions  
- **Nommage explicite** des variables et fonctions  
- **Lisibilité** du code et des commentaires  
- Le **code doit être fonctionnel**  
- Utilisation de **variables**, **boucles**, **conditions** (`if`, `switch`), **fonctions**, etc.

---

## Énoncé de l’exercice

Vous êtes **développeur dans une entreprise de transport de marchandises**.  
Le service **comptabilité** vous demande de réaliser un programme qui permet de calculer et d’afficher les résultats suivants dans la console :

- Le **chiffre d’affaires total** de l’année  
- Le **chiffre d’affaires par mois**  
- Le **mois avec le plus grand chiffre d’affaires**  
- Le **mois avec le plus petit chiffre d’affaires**  
- La **moyenne** des chiffres d’affaires  
- Le **nombre de mois** avec un chiffre d’affaires **supérieur à la moyenne**

---

## Exemple de sortie attendue dans la console

```
Chiffre d'affaires total : XXXXXXX euros
Chiffre d'affaires par mois :
Janvier : XXXXXXX euros
Février : XXXXXXX euros
Mars : XXXXXXX euros
Avril : XXXXXXX euros
Mai : XXXXXXX euros
Juin : XXXXXXX euros
Juillet : XXXXXXX euros
Août : XXXXXXX euros
Septembre : XXXXXXX euros
Octobre : XXXXXXX euros
Novembre : XXXXXXX euros
Décembre : XXXXXXX euros
Le mois avec le plus grand chiffre d'affaires : Décembre
Le mois avec le plus petit chiffre d'affaires : Février
La moyenne des chiffres d'affaires : XXXXXXX euros
Le nombre de mois avec un chiffre d'affaires supérieur à la moyenne : X
```

---

## Code de départ fourni

```javascript
// Le code suivant est mis à votre disposition pour initialiser au hasard les chiffres d'affaires mensuels :
const chiffresAffairesMensuels = [];
for (let i = 0; i < 12; i++) {
  chiffresAffairesMensuels.push(Math.floor(Math.random() * 1000000));
}
```

---

## Bonus

> Remplacez la boucle `for` de génération des chiffres d’affaires initiaux par une **saisie manuelle** via un `prompt`.  
> ⚠️ **Attention à la validation** des données entrées.
