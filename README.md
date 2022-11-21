<h1><center>Projet: Détection de la démence</center></h1>

L'objectif de ce dépôt est de mettre en place un modèle prédictif, chargé de détecter la présence de démence chez un patient, en fonction des données cliniques disponibles.
Les données sont fournis dans un tableur, dont le contenu est le suivant:

- **Nombre de lignes et de colonnnes** : 373 lignes et 15 colonnes

 - **Variables**: 
     - nWBV: Volume total du cerveau, normalisé 
     - ASF: Volume intracranien du patient, normalisé
     - eTIV: Estimation du volume intracranien du patient, exprimé en mm3
     - Visit: Nombre de visite nécésessaire pour statuer sur la présence d'une démence
     - MR Delay: Non défini, probablement lié à la mesure de l'IRM
     - Age: Age du patient, exprimé en année
     - EDUC: Age du patient à la fin de ces études, exprimé en année
     - MMSE: Mini-Mental State Examination score (de 0(pire) à 30(meilleur)). C'est un test d'évaluation des fonctions cognitives et des capacités mnésiques d'un individu.
      - SES: Statut socio-économique tel qu'évalué par l'indice Hollingshead (de 1(meilleur) à 5(plus bas))
      - CDR: Taux de démence clinique (0 = pas de démence, 0.5 = démence très sévère, 1 = démence sévère, 2 = démence modérée)  
      - Sex: Sexe du patient
      - Subject ID: identifiant du patient
      - MRI ID: identifiant de l'IRM du patient
      - Hand: main dominante, variable peu pertinente car tous les patients sont droitiers.
      - Group: En fonction de leur état cognitif, les patients sont regroupés dans 3 classes.
