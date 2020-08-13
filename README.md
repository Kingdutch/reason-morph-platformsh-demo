# Reason Morph Platform.sh - Demo 

This repository is based on the [Morph GraphQL Server Pesy Template](https://github.com/reason-native-web/morph-graphql-server-pesy-template)

This template can be used to get up and running quickly with [`Morph`](https://github.com/reason-native-web/morph).

Platform.sh configuration has been added in `.platform.app.yaml` and `.platform/` to see if this runs on Platform.sh. Platform.sh doesn't support OCaml as runtime so we use Node.js instead and build everything in the build step.

## Creation

This repository was created with the following commands. After which git was added and the Platform.sh configuration was manually created.

```
yarn global add esy pesy@next

mkdir morph-playground
cd morph-playground

pesy --template=reason-native-web/morph-graphql-server-pesy-template

esy start
```
