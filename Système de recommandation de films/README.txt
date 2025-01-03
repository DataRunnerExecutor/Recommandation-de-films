
-- README --


Lien vidéo YouTube : "https://www.youtube.com/watch?v=rspzzsMRl-E&t=11s"
Lien image : "https://img.freepik.com/vecteurs-premium/fond-film-cinema-premiere_41737-251.jpg?w=900"

Commande terminal Power Shell : PS "C:\Users\dassi\OneDrive\Bureau\Système de recommandation de films\Script.py.py"
Fonctionne aussi avec VisualStudio Code

Utiliser ce code sur un IDE pour importer la base de données : 
import pandas as pd
df = pd.read_csv(r'C:\Users\dassi\OneDrive\Bureau\Système de recommandation de films')
df.head()

-- CONSIGNES --

Vous êtes un Data Analyst freelance, un cinéma en perte de vitesse situé dans la Creuse vous contacte. Il a décidé de passer le cap du digital en créant un site Internet taillé pour les locaux.
Pour aller encore plus loin, il vous demande de créer un moteur de recommandations de films qui à terme, enverra des notifications aux clients via Internet.
Pour l’instant, aucun client n’a renseigné ses préférences, vous êtes dans une situation de cold start. Mais heureusement, le client vous donne une base de données de films basée sur la plateforme IMDb.
Commencez par une étude de marché sur la consommation de cinéma dans la région de la Creuse, afin de mieux comprendre les attentes et les préférences du public local. Cette étape préliminaire vous permettra de définir une orientation adaptée pour la suite de l’analyse de votre base de données.
Après cette étude, réalisez une analyse approfondie de votre base de données pour identifier des tendances et caractéristiques spécifiques. Cette analyse devrait inclure : l’identification des acteurs les plus présents et les périodes associées, l’évolution de la durée moyenne des films au fil des années, la comparaison entre les acteurs présents au cinéma et dans les séries, l’âge moyen des acteurs, ainsi que les films les mieux notés et les caractéristiques qu’ils partagent.
Sur la base des informations récoltées, vous pourrez affiner votre programmation en vous spécialisant par exemple sur les films des années 90 ou les genres d’action et d’aventure, afin de mieux répondre aux attentes du public identifié lors de l’étude de marché

Après cette étape analytique, sur la fin du projet, vous utiliserez des algorithmes de machine learning pour recommander des films en fonction de films qui ont été appréciés par le spectateur.
Le client vous fournit également une base de données complémentaires venant de TMDB, contenant des données sur les pays des boîtes de production, le budget, les recettes et également un chemin vers les posters des films. Il vous est demandé de récupérer les images des films pour les afficher dans votre interface de recommandation.

-- APPLICATION --

Nous sommes l'entreprise freelance Cinéma Movie Time composée de Mourad, Dalia, Vanessa et Adrien.
A la demande du client notre cible a été définie : Notre sélection se fera sur les films américains en VF entre 1990 jusqu'à nos jours et sera classé par Nom de films, par Genre ( action, thriller, … ), par année, par Nom d'acteurs et Nom de réalisateurs.
Le système de recommandation de film est disponible avec Streamlit, bon visionnage ! 😊
