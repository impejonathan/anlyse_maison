# anlyse_maison
projet d'analyse des ventes de maison aux usa plus particulièrement  comté de king

ce fichier regroupe 4 dossiers :
    - data_Cleaning_Analysis.ipynb (l'analyse des données du csv) 
    - data_Prepation.ipynb (preparation des données mise en forme et suppression de données)
    - data_modelisation.ipynb ( test des modèles pour avoir le meilleur score :
                                                                        - KNeighborsRegressor
                                                                        - LinearRegression
                                                                        - RobustScaler
                                                                        - Ridge
                                                                        - Lasso
                                                                        - StandardScaler )

    - pipeline.ipynb ( c'est ce dossier que j'ai utilisé pour la création du pickle  -- knn_model_maison.pkl -- 
                       Le score KNN sur les données de test est : 0.8249254049111474 )