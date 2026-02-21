Tip Application

Une application Android simple et élégante pour calculer les pourboires, développée avec **Jetpack Compose**.

 * Fonctionnalités : 

-  Saisie du montant de la facture
-  Définition d'un pourcentage de pourboire personnalisé
- Option pour arrondir le pourboire à l'entier supérieur
- Affichage du pourboire formaté selon la devise locale

 * Technologies utilisées : 

- Langage : Kotlin
- Framework UI : Jetpack Compose
- Architecture : Composable avec remontée d'état (State Hoisting)

 * Comment ça fonctionne ?

1. Entrez le montant de la facture
2. Entrez le pourcentage de pourboiresouhaité
3. Activez "Arrondir le pourboire" si vous souhaitez arrondir au dollar supérieur
4. L'application affiche instantanément le montant du pourboire calculé

* Structure du projet : 

com.example.tipapp/
├── MainActivity.kt          
└── ui/theme/
    └── TipTimeTheme.kt      

 * Composables principaux :

| Composable | Description |

| TipTimeLayout | Écran principal avec toute la logique UI |
| EditNumberField | Champ de saisie numérique réutilisable |
| RoundTheTipRow | Ligne avec libellé et interrupteur |
| calculateTip() | Logique métier du calcul du pourboire |

* Captures d'écran :
  <
<img width="1920" height="1080" alt="Screenshot (138)" src="https://github.com/user-attachments/assets/262402b7-3be5-4416-a1ab-eb34e8365277" />

<img width="1920" height="1080" alt="Screenshot (139)" src="https://github.com/user-attachments/assets/41be5c56-6bcf-4ca2-aa59-1668b49f36af" />

<img width="1920" height="1080" alt="Screenshot (140)" src="https://github.com/user-attachments/assets/aa1d3775-4739-44be-bb2d-05f843d6f9de" />

<img width="1920" height="1080" alt="Screenshot (141)" src="https://github.com/user-attachments/assets/91fe811a-6300-4a90-a4f6-8f324e1239c1" />

<img width="1920" height="1080" alt="Screenshot (142)" src="https://github.com/user-attachments/assets/76b30fa1-abf5-4373-8aa7-8fffc2deb5bf" />


