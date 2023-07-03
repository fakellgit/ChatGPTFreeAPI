# ChatGPTFreeAPI

Bienvenue sur ChatGPT API Free, une API gratuite qui vous permet d'accéder à l'API ChatGPT d'OpenAI.

ChatGPT API Free est un outil puissant qui permet aux utilisateurs de générer des réponses à des prompts en utilisant le modèle de langage GPT-3.5. L'API est facile à utiliser et peut être accessible en envoyant une requête POST à un endpoint spécifique.

## Utilisation

Pour utiliser ChatGPT API Free, envoyez simplement une requête POST à l'endpoint suivant :

```
http://fakell.raidghost.com/v1/chat/completions/
```

Par exemple, pour générer une réponse au prompt "Bonjour, comment ça va ?" en utilisant le modèle `gpt-3.5-turbo`, envoyez la commande `curl` suivante :

```sh
curl http://fakell.raidghost.com/v1/chat/completions/ \
  -H 'Content-Type: application/json' \
  -d '{
  "model": "gpt-3.5-turbo",
  "messages": [{"role": "user", "content": "Bonjour, comment ça va ?"}],
  "stream": false
}'
```

Si vous avez besoin de plus d'informations sur l'utilisation de ChatGPT API Free, vous pouvez consulter la [documentation officielle de l'API fournie par OpenAI](https://platform.openai.com/docs/api-reference/chat/create). La documentation est très complète et fournit des informations détaillées sur l'utilisation de l'API, ainsi que des extraits de code pour vous aider à démarrer.

## Suivez-moi !

Si vous trouvez ChatGPT API Free utile, vous pouvez rester à jour sur les derniers développements en me suivant. En suivant [moi](https://github.com/fakellgit), vous serez le premier à être informé des nouvelles fonctionnalités, mises à jour et améliorations apportées à l'API.

## Auteur
Fahendrena
[fakellyh@gmail.com](mailto:fakellyh@gmail.com).
