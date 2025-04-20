
---

### 📄 Fichier `conditions_boucles.md`

```markdown
# 🔁 Fiche Mémo – Conditions & Boucles

## 🎯 Les Conditions

Elles permettent de **prendre des décisions** dans le code.

### 🔹 Condition simple

```cpp
if (age > 18) {
   print("Majeur");
}

### 🔹 Condition avec else


```cpp
if (age > 18) {
   print("Majeur");
} else {
   print("Mineur");
}

### 🔹 Condition avec else if

if (note >= 16) {
   print("Très bien");
} else if (note >= 10) {
   print("Moyen");
} else {
   print("Échec");
}

🔄 Les Boucles

🔸 Boucle while (tant que)

int i = 0;
while (i < 5) {
   print(i);
   i++;
}


🔸 Boucle for (pour)
for (int i = 1; i <= 10; i++) {
   print(i);
}

💡 Bonnes pratiques
Attention aux boucles infinies ! Toujours avoir une condition d’arrêt.

Les indentations rendent le code lisible.

Utilise les conditions combinées avec && (et), || (ou), ! (non).

✅ À retenir
if, else, else if = décisions

while, for = répétitions

Bien gérer les conditions pour éviter les erreurs de logique
