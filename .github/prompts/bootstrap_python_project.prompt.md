---
mode: agent
---
Dans le dossier demo/python de workspace créé un simple projet de test Python très simple sans persistance et sans README avec un endpoint rest qui sert juste à afficher des informations statiques sur une personne nommé __Antonin Brugnot__ en utilisant #context7.

Pour avoir ces informations statiques éffectue une recherche sur la personne nommé __Antonin Brugnot__ avec #local-tavily-mcp.

Une fois cela fait, créé un fichier README.md avec une description du projet et les instructions pour le construire et l'exécuter, utilises des exemples sur github avec #mcp-github.

Utilise #podman pour créer une image et ensuite déployer le conteneur dans un pod sur le namespace default du cluster k8s local __kind-kind-cluster__ avec #mcp_k8s. **Interdiction d'utiliser un cluster k8s distant**.
