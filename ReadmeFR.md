# ChatGPTFreeAPI

Bienvenue sur l'API ChatGPT Free, une API qui donne accès à l'API ChatGPT d'OpenAI gratuitement. Cette API permet aux étudiants ou individus de générer des réponses à partir de requêtes en utilisant le puissant modèle linguistique GPT-3.5. Elle est facilement accessible en envoyant une requête POST à un point d'accès spécifique.

## Utilisation

Pour utiliser l'API ChatGPT Free, envoyez simplement une requête POST à l'adresse suivante :

```
https://api-fakell.x10.mx/v1/chat/completions/
```

Par exemple, pour générer une réponse à la requête "Bonjour, comment ça va ?" en utilisant le modèle `gpt-3.5-turbo`, utilisez la commande `curl` suivante :

```sh
curl https://api-fakell.x10.mx/v1/chat/completions/ \
  -H 'Content-Type: application/json' \
  -d '{
  "model": "gpt-3.5-turbo",
  "messages": [{"role": "user", "content": "Bonjour, comment ça va ?"}],
  "stream": false
}'
```

Pour plus d'informations sur l'utilisation de l'API ChatGPT Free, vous pouvez consulter la [documentation officielle de l'API fournie par OpenAI](https://platform.openai.com/docs/api-reference/chat/create). Cette documentation complète offre des informations détaillées sur l'utilisation de l'API, accompagnées d'exemples de code pour vous aider à démarrer.

## Limite

L'API ChatGPTFreeAPI a une limite de 5 requêtes par minute, ce qui est suffisant pour un projet personnel.

## Restez Connecté !

Si vous trouvez l'API ChatGPT Free utile, vous pouvez rester informé des derniers développements en me suivant. En suivant [moi](https://github.com/fakellgit), vous serez parmi les premiers à être informé des nouvelles fonctionnalités, mises à jour et améliorations apportées à l'API.

## Auteur
Fahendrena
[fakellyh@gmail.com](mailto:fakellyh@gmail.com)
