# Définition des méthodes de gestion des branches de developpement long de features, correction de bugs et règles de commits

## Stratégie des Branches

Notre repository ce sépare en 3 types de branches disctinctes:

La branche "master" sera notre branche de déploiement, donc la branche la plus stable, tous les éléments qui sont mergés dans cette branche doivent être testé et validé par l'intégration manager. Aucun merge ne sera fait sur cette branche sans être d'abord passé par la "staging".

La branche "staging" sera notre branche de test, c'est une copie de la branche master mais elle contient des éléments instable (nouvelle feature, fix, refacto ... ) que nous devons testé et validé avant de merge sur la "master".

Les branches de développement/topic sont les éléments de développement ponctuels. Ce sont des branches à la durée de vie beaucoup plus courte uniquement destinées à accomplir une fonction. Chaque développeur peut créer autant de branches topic qu'il souahite et peut supprimer les branches qu'il a crée, elles doivent être définies comme suit : typeDeBranche_nom exemple feature_launchGame. Et doivent être push sur la "staging" pour être testé et validé.

## Règles de commit

Les commits doivent être claire et précis, Un commit commence donc toujours par le type de commit et le corps du commit explique clairement quels sont les modifications ou nouveaux ajouts et quels elements a été modifiés ou ajoutés.

Règles de commit : 
« type_de_branch élément changé/ajouté in name_components/page »


