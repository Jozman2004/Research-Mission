# 📍 Système de Localisation Indoor pour Maintenance Industrielle

## 📖 Description
Ce projet vise à concevoir et prototyper un système de localisation indoor permettant de positionner un opérateur dans un atelier industriel et de le guider automatiquement vers les équipements nécessitant une maintenance.

## 🎯 Objectifs
- Concevoir un système de localisation sans GPS  
- Exploiter l’infrastructure Wi-Fi existante  
- Améliorer la précision grâce à la fusion de capteurs  
- Assister les opérateurs dans leurs déplacements  

## 🧠 Concepts clés
- Localisation Wi-Fi (RSSI / RTT)  
- SLAM (Simultaneous Localization and Mapping)  
- WiSLAM  
- IMU / Dead Reckoning (PDR)  
- Fusion de données (Wi-Fi + IMU + vision)  

## 🏗️ Architecture du système
Le système repose sur plusieurs modules :

### 1. Module de localisation Wi-Fi
- Estimation de position via RSSI ou RTT  

### 2. Module IMU
- Suivi des déplacements (pas, direction)  

### 3. Module de fusion
- Filtre de particules / SLAM  

### 4. Interface utilisateur
- Guidage en temps réel (mobile ou tablette)  

## ⚙️ Méthodologie
1. Étude de l’état de l’art  
2. Sélection de deux approches de localisation  
3. Implémentation des solutions  
4. Évaluation des performances  

## 📊 Critères d’évaluation
- Erreur de localisation (en mètres)  
- Précision (%)  
- Robustesse aux perturbations  
- Coût de calcul  

## 🚀 Technologies utilisées
- Python / MATLAB  
- Machine Learning (KNN, SVM, LSTM)  
- Capteurs (Wi-Fi, IMU)  
- Algorithmes SLAM  

## 🧪 Expérimentation
Les tests sont réalisés dans un environnement simulant un atelier industriel afin d’évaluer les performances en conditions proches du réel.

## 📈 Résultats attendus
- Précision de l’ordre du mètre  
- Localisation en temps réel  
- Optimisation des déplacements des opérateurs  

## 🔮 Perspectives
- Intégration avec la réalité augmentée  
- Connexion avec des systèmes IoT  
- Déploiement en environnement industriel réel  

## 👥 Équipe
- Rosilia MODJO  
- Nadia TCHUENTE  
- Joseph NKOULOU  

## 👨‍🏫 Encadrants
- Aloys NGUEPI  
- Humphrey OJONG  

## 📅 Année académique
2025 – 2026  

## 🏷️ Mots-clés
Localisation indoor, WiSLAM, Industrie 4.0, Maintenance intelligente, Fusion de capteurs  
