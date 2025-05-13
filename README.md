# TIPE – Freinage Automobile par Fluides Magnétorhéologiques

**Titre complet :** Usage des fluides magnétorhéologiques pour les applications de freinage automobile  
**Note obtenue :** 17,5/20 aux concours des Grandes Écoles d’ingénierie

## 🎯 Objectif  
Explorer l'efficacité des suspensions semi-actives à base de fluides magnétorhéologiques (MR) pour améliorer la sécurité routière et le confort de conduite, notamment lors du passage sur un ralentisseur urbain.

## 🔬 Méthodologie expérimentale

### 1. Étude de l’amortissement classique
- **Matériel :**
  - Oscillateur (f = 2 Hz) avec masse (150g), ressort (k = 80 N/m)
  - Arduino Mega + accéléromètre MPU6050
  - Lecteur SD pour acquisition des données
- **Conditions testées :**
  - Amortissement à l’air libre puis dans l’eau
- **Résultat :**
  - Amortissement exponentiel plus rapide dans l’eau

### 2. Simulation de passage sur un ralentisseur (RC)
- **Montage :**
  - Voiture RC (échelle 1/10) équipée d’un accéléromètre
  - Maquette de ralentisseur à pente trapézoïdale (échelle 1/10)
- **Essais :**
  - À 7,5 cm/s → Accélération verticale maximale : 0,6G  
  - À 12 cm/s → Accélération verticale maximale : 0,8G

### 3. Comparaison avec véhicules réels
- **Tests réalisés sur :** Citroën DS4 et Peugeot 3008
- **Vitesses testées :** 30 km/h et 50 km/h
- **Résultats :**
  - Amortisseurs semi-actifs réduisent les pics d’accélération (jusqu’à 6x moins à 50 km/h)

## 🧪 Étude des fluides magnétorhéologiques (MR)

### Création du fluide MR
- **Composition :**
  - 70 cL d'huile végétale  
  - 250 g de limaille de fer (90 μm)  
  - 30 cL de détergent

### Expérimentation
- **Objectif :** Contrôler la viscosité du fluide via un champ magnétique
- **Montage :**
  - Solénoïde, alternostat, teslamètre, noyau ferromagnétique
  - Masse en régime libre dans le fluide MR
- **Courants testés :** 0 A, 0.5 A, 1 A, 1.5 A
- **Résultat :** Le fluide se solidifie partiellement sous l’effet du champ magnétique, modifiant le comportement d’amortissement

## ✅ Conclusion

### Avantages :
- Confort de conduite amélioré
- Meilleure tenue de route
- Adaptabilité aux conditions de conduite
- Réduction de la consommation de carburant (grâce à l’optimisation du contact sol/route)

### Inconvénients :
- Coût de fabrication élevé
- Entretien nécessaire (risque de sédimentation)

## 🧰 Technologies utilisées
- Arduino Mega
- Accéléromètre MPU6050
- Lecteur SD
- Teslamètre, alternostat, solénoïde
- Maquette imprimée / construite à l’échelle

---

**Candidat :** N° 33332  
**Sujet :** Optimisation de l’amortissement lors du franchissement d’un ralentisseur urbain  
**Année :** TIPE de 2e année – filière PSI  
