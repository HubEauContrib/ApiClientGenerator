# ApiClientGenerator
ApiClientGenerator décrit les commandes pour générer les SDKs de [HubEeau](https://github.com/BRGM/hubeau). Il utilise le generateur [openapi-generator](https://openapi-generator.tech/).

**Hub'Eau** est la plateforme pour faciliter l'utilisation des données ouvertes sur l'eau en France. Hub'Eau est la solution - sous forme d'API REST web - pour accéder aux données françaises sur l’eau, de façon centralisée et homogène. Autrement dit, Hub'eau permet le téléchargement immédiat de données sur l’eau depuis les principales banques de données nationales, par simple copie d’une requête (adresse internet) dans la barre d’adresse d’un navigateur :)
Les données restituées ont été pensées et préparées pour être fraîches (automatiquement et régulièrement mises à jour), immédiatement intelligibles (grâce à l'ajout de libellés descriptifs pour chaque code) et exploitables.

**OpenAPI Generator** permet la génération automatique de bibliothèques clientes API (génération SDK), de stubs de serveur, de documentation et de configuration en fonction d'une spécification OpenAPI (v2, v3)

## Installer avec Docker

```
docker run --rm  -v ${PWD}:/local openapitools/openapi-generator-cli generate  -i /local/api-docs.json  -g csharp-netcore  -o /local/out/csharp --additional-properties=targetFramework=net6.0,netCoreProjectFile=true,packageName=HubEauKit
```

## Credits 
Merci à ces projets.

* [[BRGM / hubeau](https://github.com/BRGM/hubeau)], licence inconnue, Hub'Eau, la plateforme pour manipuler facilement les données ouvertes sur l'eau.
* [[OpenAPITools / openapi-generator](https://github.com/OpenAPITools/openapi-generator)], OpenAPI Generator allows generation of API client libraries (SDK generation), server stubs, documentation and configuration automatically given an OpenAPI Spec (v2, v3), [https://openapi-generator.tech/](https://openapi-generator.tech/)

