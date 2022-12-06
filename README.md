# ESILV-Python-for-data-analysis-Diabetes

Ce projet a pour but de trouver un modèle de Machine Learning capable de trouver si un patient admis à cause du diabète sera réadmis pour la même raison plus tard.

Nous avons le dataset suivant : Diabetes 130-US hospitals for years 1999-2008.

Les étapes de notre étude pour prédire la réadmission des patients :

Etape 1 : Exploration du dataset et nettoyage​

Etape 2 : Features Engineering et visualisation (lien entre notre variable de prédiction et les autres variables)​

Etape 3 : Train-Test Splitting​

Etape 4 : Encodage​

Etape 5 : Standardisation​

Etape 6 : Création des modèles​

Etape 7 : Hyperparameters Tuning + conclusion

Etape 8 : API Flask

Conclusion :

Notre étude s'est porté sur des données venus d'hôpitaux renseignant sur des procédures cliniques et des diagnostics de patients diabétiques, afin de construire un modèle prédictif de machhine learning permettant d'identifier les patients diabétiques qui ont une probabilité plus élevée d'être réadmis à l'hôpital. D'après notre analyse sur 7 modèles de Machine Learning, dont la régression logistique, Linear SVC, Linear Discriminant Analysis, Decision Tree Classifier, Random Forest Classifier, Gradient Boosting Classifier, Cat Boost Classifier; en termes de recall, d'accuracy de courbe ROC, d'AUC et de matrice de confusion, le meilleur modèle à la fin s'est avéré être le Cat Boost Classifier optimisé avec les hyperparamètres, donnant un recall de 51,01%. Les variables clés qui affectent le taux de réadmissions sont par exemple, le nombre de diagnostics, le nombre de procédures de laboratoire, le nombre de médicament ou le nombre de fois qu'un patient a séjourné à l'hôpital et l'insuline. Par la suite, on a crée un API avec Flask et on a pu entrer nos données brutes sur Postman et en retour cela nous prédisait la réadmission de ce patient avec 0 pour non-admis et 1 pour réadmis.

