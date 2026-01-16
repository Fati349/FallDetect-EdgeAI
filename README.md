# Aperçu du Projet
Détection de chutes en temps réel par analyse audio embarquée sur EFR32MG24
Un système de surveillance pour personnes âgées utilisant le Machine Learning sur microcontrôleur
## Composants Principaux
**Matériel**

- Microcontrôleur : EFR32MG24 (Cortex-M33 @ 78MHz)
- Capteur : Microphones I2S
- Indicateurs : LEDs RGB (Vert/Orange/Rouge)

**Logiciel**

- Plateforme ML : Edge Impulse Studio
- Extraction Features : MFCC (pipeline Edge Impulse)
- Modèle ML : CNN 1D quantifié INT8 (TensorFlow Lite via Edge Impulse)
- Optimisation : EON Compiler (Edge Impulse)
- Fenêtre d'analyse : 2 secondes
