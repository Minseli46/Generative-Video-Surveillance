# Generative-Vidéo-Surveillance

Le projet a pour ambition d’explorer les solutions existantes d’analyse vidéo et d’évaluer les gains offerts par l’IA générative. Sur la base de ces travaux préliminaires, l’objectif est de développer un modèle d’IA dédié à l’analyse vidéo capable de :

1. **Renforcer la détection d’anomalies**  
   Détecter plus finement les événements atypiques (intrusions, comportements inhabituels) grâce à l’apport de réseaux génératifs pour modéliser le « normal ».

2. **Anticiper les comportements suspects**  
   — Si faisable, prédire les actions à risque ou menaces potentielles avant leur manifestation, en s’appuyant sur des séquences vidéo historiques et sur des techniques de forecasting par IA.

3. **Traiter les flux en temps réel**  
   — Si possible, analyser et qualifier les images vidéo à la volée, pour une intervention immédiate et un retour d’alerte quasi instantané.

Ce projet vise à démontrer l’efficacité et la robustesse de ces systèmes intelligents dans des contextes complexes (vidéo-surveillance, environnements industriels, transports, etc.).

---

### Fonctionnalités clés

- **Collecte et prétraitement**  
  Workers asynchrones pour ingérer des flux RTSP, vidéo locale ou API tierces, avec étapes de découpage et normalisation.

- **Détection et modélisation**  
  Combinaison de CNN/transformers pour l’analyse spatiale/temps ; auto-encodeurs et GANs pour apprendre la distribution des scènes normales.

- **Mécanismes d’anticipation**  
  Modules de prévision séquentielle (LSTM, temporal transformers) pour estimer la probabilité d’événements futurs.

