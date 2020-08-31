# TODO

A simple TODO full stack application using AWS Amplify. The Authentication module is provided using AWS Cognito.
AWS Amplify documentation: https://docs.amplify.aws/start/q/integration/vue
To integrate a lambda function with node REST API into the amplify application: https://docs.amplify.aws/lib/restapi/getting-started/q/platform/js

## Project setup

```
yarn install
```

### Compiles and hot-reloads for development

```
yarn serve
```

### Compiles and minifies for production

```
yarn build
```

### Lints and fixes files

```
yarn lint
```

### Amplify commands

`init` Initializes a new project, sets up deployment resources in the cloud, and makes your project ready.
`configure` Configures the attributes of your project for amplify-cli, such as switching front-end framework and adding/removing cloud-provider plugins.
`push` Provisions cloud resources with the latest local developments.
`pull` Fetch upstream backend environment definition changes from the cloud and updates the local environment to match that definition.  
`publish` Executes amplify push, and then builds and publishes client-side application for hosting.  
`serve` Executes amplify push, and then executes the project's start command to test run the client-side application locally.  
`status` Shows the state of local resources not yet pushed to the cloud (Create/Update/Delete).  
`delete` Deletes all of the resources tied to the project from the cloud.  
`<category> add` Adds a resource for an Amplify category in your local backend  
`<category> update` Update resource for an Amplify category in your local backend.  
`<category> push` Provisions all cloud resources in a category with the latest local developments.  
`<category> remove` Removes a resource for an Amplify category in your local backend.  
`<category>` Displays subcommands of the specified Amplify category.  
`mock` Run mock server for testing categories locally.  
`codegen` Generates GraphQL statements(queries, mutations and eventHandlers) and type annotations.  
`env` Displays and manages environment related information for your Amplify project.  
`console` Opens the web console for the selected cloud resource.
`push` will build all your local backend resources and provision it in the cloud
`publish` will build all your local backend and frontend resources (if you have hosting category added) and provision it in the cloud

### Demo

https://dev.d2j7qe756odvvl.amplifyapp.com/

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).
