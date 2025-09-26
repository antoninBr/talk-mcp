---
mode: agent
tools: ['changes', 'fetch', 'githubRepo', 'problems', 'usages', 'runCommands', 'runTasks', 'edit', 'runNotebooks', 'search', 'new', 'extensions', 'vscodeAPI', 'think', 'testFailure', 'openSimpleBrowser', 'todos', 'runTests', 'local-tavily-mcp', 'mcp_k8s', 'podman', 'context7']
---

Dans le dossier demo/python de workspace créé un simple projet de test Python très simple sans persistance et sans README avec un endpoint rest qui sert juste à afficher des informations statiques sur une personne nommé __Antonin Brugnot__. Respecte les bonnes pratiques de développement python avec context7.

Pour avoir ces informations statiques éffectue une recherche sur la personne nommé __Antonin Brugnot__.

Une fois cela fait, créé un fichier README.md avec une description du projet et les instructions pour le construire et l'exécuter, utilises des exemples sur github.

Utilise #podman pour créer une image et ensuite déployer le conteneur dans un pod sur le namespace default du cluster k8s local __kind-kind-cluster__. **Interdiction d'utiliser un cluster k8s distant**.
