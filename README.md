# kodeku

A Cli to help generate framework nodejs.

### usage

```sh
kodeku
```
## TODO
* [x] Choose a library to use for user interactions
* [ ] CLI will ask questions:
   * [ ] Check if kodeku.json already exists...
   * [ ] what is the name of the project
       * Default to current directory name
   * [ ] What type op the project ?
       * node-express
       * static
       * react
       * vue
       * static build
       * lambda
   * [ ] Which file is the entry point?
   * [ ] Would you like to specify an alias ?
       * Allow one or more
   * [ ] Would you like to add kodeku-build to your package.json
       * Only promptif React / Vue or static-buld
   * [ ] Would you like to deploy?
   