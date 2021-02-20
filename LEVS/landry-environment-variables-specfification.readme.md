
## The Landry Environmental Variable Specification





## Goals



1. The Application can read env variables on the node and persist them to keys when the application starts

2. In addition, the app

3. Engineers can check in env keys and default values into version control.



## Specification



1. The application shall reference a reserved env var, `ENVIRONMENT`, to determine its logical environment, which defaults to `default` if it is not set or is an empty string.

2. The application shall scan a file located in the root of the project, called `env.default.yaml` to determine the list of keys that the application shall populate

3. When an env value is requested, the application shall return the following result determined as follows.

4. The value set on the system's environmental variables

5. If that doesn't exist, then the value specified in the `env.logical_environment.yaml file`, where logical_environment matches the env var assigned to `ENVIRONMENT`.

6. If that doesn't exist, then the value specified in the `env.default.yaml` file.

7. The `env.default.yaml` shall be checked into version control. Other env.*.yaml files shall be barred from version control


## Implementation suggestions
Most default 'env' libraries and APIs almost conform to this spec. Building a new library will usually amount to using an existing implementation and wrapping it.




## Template for tracking implementation status

## Implementation tracking legend



## Implementation status