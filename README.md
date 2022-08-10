# ApiClientGenerator
ApiClientGenerator décrit les commandes pour générer les SDKs de [HubEeau](https://github.com/BRGM/hubeau). Il utilise le generateur [kiota](https://github.com/microsoft/kiota).

**Hub'Eau**, la plateforme pour faciliter l'utilisation des données ouvertes sur l'eau en France. Hub'Eau est la solution - sous forme d'API REST web - pour accéder aux données françaises sur l’eau, de façon centralisée et homogène. Autrement dit, Hub'eau permet le téléchargement immédiat de données sur l’eau depuis les principales banques de données nationales, par simple copie d’une requête (adresse internet) dans la barre d’adresse d’un navigateur :)
Les données restituées ont été pensées et préparées pour être fraîches (automatiquement et régulièrement mises à jour), immédiatement intelligibles (grâce à l'ajout de libellés descriptifs pour chaque code) et exploitables.

**Kiota** est un générateur de code basé sur OpenAPI pour créer des SDK pour les API HTTP. L'objectif est de produire un générateur de code léger, à faible maintenance, suffisamment rapide pour être exécuté dans le cadre de la chaîne d'outils de compilation, mais suffisamment évolutif pour gérer les API les plus importantes.

## Install l'outil kiota

```
dotnet tool install --global --prerelease Microsoft.OpenApi.Kiota
```


## Credits 
Merci à ces projets.

* [[BRGM / hubeau](https://github.com/BRGM/hubeau)], licence inconnue, Hub'Eau, la plateforme pour manipuler facilement les données ouvertes sur l'eau.
* [[microsoft / kiota]()],  MIT license, OpenAPI based HTTP Client code generator.

