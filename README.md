# Technical Test: AI-Powered Q&A System
**Description**
Ce projet implémente un système de questions-réponses basé sur un document texte ou PDF. Il utilise des modèles de traitement du langage naturel (NLP) pour extraire, analyser et répondre aux questions en fonction du contenu du document.

**Approche**
Le système suit quatre étapes principales :

Chargement du document → Extraction du texte depuis un fichier TXT ou PDF.
Encodage sémantique → Conversion du texte en vecteurs numériques à l’aide d’un modèle d’embeddings (all-MiniLM-L6-v2).
Stockage et recherche → Indexation et recherche des passages pertinents grâce à FAISS.
Génération de réponse → Utilisation du modèle Flan-T5-Small pour formuler une réponse basée sur le contenu trouvé.

**Choix Techniques**

PyPDF2 : Extraction de texte depuis un fichier PDF.
sentence-transformers : Génération d’embeddings pour la recherche sémantique.
FAISS : Recherche rapide des passages pertinents.
Flan-T5-Small : Génération de réponse rapide et efficace, optimisée pour CPU.

**Execution**
Merci de suivre les étapes mentionner dans le code pour que le projet s'éxecute correctement.

**Utilisation**
Exécuter le script en fournissant un fichier TXT ou PDF.
Poser une question en lien avec le document.
Voir les résultats.

**Conclusion**
Ce projet offre un système efficace et rapide pour interagir avec un document via un modèle IA. Idéal pour l’automatisation de la recherche d’informations
