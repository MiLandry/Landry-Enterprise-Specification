  ## The Landry Environmental Variable Specification



## Goals

 1. The Application can read env variables on the node and persist them to keys when the application starts
 2. In addition, the app
 3. Engineers can check in env keys and default values into version control.

## Specification

 1. The application shall reference a reserved env var, `ENVIRONMENT`, to determine its logical environment.
 2. The application shall scan a file located in the root of the project, called `env.default.yaml` to determine the list of keys that the application shall populate
 3. When an env value is requested, the application shall return the following result determined as follows.
	 1. The value set on the system's environmental variables
	 2. If that doesn't exist, then the value specified in the `env.logical_environment.yaml file`, where logical_environment matches the env var assigned to `ENVIRONMENT`.
	 3. If that doesn't exist, then the value specified in the `env.default.yaml` file.
 4. The `env.default.yaml` shall be checked into version control. Other env.*.yaml files shall be barred from version control
